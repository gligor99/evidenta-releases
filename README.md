<p align="center"><img src="https://raw.githubusercontent.com/gligor99/evidenta-releases/main/icon.png" width="96" alt="Evidenta"></p>

<h1 align="center">Evidenta</h1>

<p align="center">Fakture, knjiga prihoda, porezi i doprinosi za samostalne preduzetnike u Republici Srpskoj.</p>

<p align="center"><b>Najnovija verzija: 1.0.6</b> (08.10.2026.) · <a href="https://github.com/gligor99/evidenta-releases/releases/latest">Preuzmi</a></p>

## Preuzimanje

Otvorite [najnovije izdanje](https://github.com/gligor99/evidenta-releases/releases/latest) i preuzmite fajl za svoj sistem:

| Sistem | Fajl |
|---|---|
| Windows | `Evidenta-Setup-x.y.z.exe` |
| macOS (Apple M1–M4) | `Evidenta-x.y.z-arm64.dmg` |
| macOS (Intel) | `Evidenta-x.y.z.dmg` |
| Linux | `Evidenta-x.y.z.AppImage` ili `evidenta_x.y.z_amd64.deb` |

## Instalacija

Evidenta još nije potpisana plaćenim certifikatom, pa sistem pri prvom pokretanju traži potvrdu. To se radi samo jednom.

- **Windows:** ako se pojavi „Windows protected your PC“, kliknite *More info* → *Run anyway*.
- **macOS:** prevucite Evidentu u *Applications* i pokrenite je. Kad javi da se ne može otvoriti, kliknite *Done*, pa *System Settings → Privacy & Security → Open Anyway*.
- **Linux:** `sudo apt install ./evidenta_*_amd64.deb`, ili `chmod +x Evidenta-*.AppImage` pa pokrenite.

Probni period traje 30 dana. Ključ licence unosite u *Postavke → Licenca i ažuriranja*.

## Šta je novo

### 1.0.6 — 08.10.2026.

#### Novo
- **Rokovi na početnoj:** porez (do 10.) i doprinosi (do 15.) za prethodni mjesec, fakture koje kasne ili uskoro dospijevaju i profakture koje ističu — sa iznosom i brojem dana.
- **Podsjetnici:** desktop obavještenje jednom dnevno kad nešto kasni ili ističe. Može se isključiti u *Postavke → Porezi i doprinosi*.
- **Rokovi u kalendar:** jednim klikom u Google, Apple ili Outlook kalendar (porez i doprinosi svaki mjesec, rokovi plaćanja faktura).
- **Izvoz u Excel:** knjiga prihoda, troškovi, fakture i profakture, klijenti i uplate poreza i doprinosa — za knjigovođu ili vlastite tabele.
- **Uplata poreza i doprinosa sa datumom:** kad označite mjesec kao plaćen, birate datum i iznos. Uplata koja je pokrila više mjeseci (npr. april i maj) može se rasporediti na te mjesece.

#### Izmjene
- Kašnjenje se prikazuje u godinama, mjesecima i danima („Kasni 1 godinu i 4 mjeseca“), a ne samo u danima.

### 1.0.5 — 08.10.2026.

#### Popravke
- **Doprinosi i porez:** mjesec za koji postoji uplata sa izvoda banke prikazuje se kao plaćen, i kad se iznos razlikuje od obračuna (npr. druga osnovica prošle godine).
- **Pravila iz izvoda:** kad za neku godinu nisu unesena pravila, a uplate sa izvoda pokazuju drugi iznos doprinosa, aplikacija predlaže prosječnu bruto platu za tu godinu jednim klikom.
- Mjeseci prije početka rada više se ne prikazuju kao neplaćeni.
- Uplata koja pokriva više mjeseci (npr. april i maj) raspoređuje se na sve te mjesece.

### 1.0.4 — 08.10.2026.

#### Novo
- **Skenirane i fotografisane fakture:** uvoz čita tekst i sa slike (PDF bez teksta, JPG, PNG), bez interneta, na bosanskom, hrvatskom, srpskom i engleskom.
- **Fakture iz bilo kog programa:** pored Invoice Ninje prepoznaju se uobičajene oznake (Broj računa, Datum, Za uplatu, Kupac, Invoice No, Total, Bill To…).
- **Ručna dopuna:** šta se ne pročita, upišete u pregledu uvoza; fajl se može otvoriti direktno iz tabele.
- **Ulazne fakture → troškovi:** računi koje ste dobili od dobavljača (kupac je vaša firma) upisuju se kao troškovi, sa kategorijom i originalom. Original se otvara iz liste troškova.

#### Popravke
- Nakon brisanja podataka više se ne vraćaju podaci iz stare verzije („SP Evidencija“).

### 1.0.3 — 08.10.2026.

#### Novo
- **Uvoz postojećih faktura:** izaberite PDF-ove ili cijeli folder sa fakturama koje ste ranije izdavali (npr. iz Invoice Ninje). Klijenti se prave automatski iz podataka kupca, duplikati se preskaču, a originalni PDF se čuva uz svaku fakturu.
- **Uvoz izvoda iz banke (CSV):** uplate zatvaraju fakture sa stvarnim datumom uplate i brojem izvoda, uplate doprinosa i poreza se prepoznaju iz poziva na broj, a troškovi i provizije banke se upisuju sami. Prenosi između vlastitih računa i isplate vlasniku se preskaču. Prije upisa sve možete pregledati i promijeniti, a ponovni uvoz istog izvoda ništa ne duplira. Za sada podržava CSV izvoz ProCredit banke.
- Oba uvoza su u *Postavke → Uvoz podataka*.

### 1.0.2 — 08.10.2026.

#### Novo
- **Čarobnjak za prvo pokretanje:** nova instalacija vas vodi kroz podatke o s.p.-u, bankovni račun, poreze i fakture. Svaki korak se može preskočiti i kasnije promijeniti u postavkama.
- **Splash ekran** dok se aplikacija učitava, umjesto praznog prozora.

#### Popravke
- **macOS:** aplikacija preuzeta s interneta više se ne prijavljuje kao „oštećena“. Pri prvom pokretanju otvara se preko *System Settings → Privacy & Security → Open Anyway*.
- Poruka o ažuriranjima je jasnija kad kopija aplikacije nije instalirana iz zvaničnog izdanja.

### 1.0.1 — 08.10.2026.

#### Novo
- **macOS za Intel:** pored Apple Silicon (M1–M4) postoji i verzija za starije Intel Mac-ove.
- **Obavijest o novoj verziji na macOS-u:** aplikacija javlja da je izašla nova verzija i nudi link za preuzimanje.

#### Popravke
- Windows instalacija je ponovo dio izdanja (u 1.0.0 je nedostajala).

### 1.0.0 — 08.10.2026.

Prvo izdanje.

- Klijenti, fakture i profakture sa četiri šablona, na bosanskom, engleskom ili dvojezično.
- Nacrt → izdata faktura (izdata se ne mijenja, ispravka ide preko storna), dnevnik izmjena.
- Knjiga prihoda, troškovi, radni sati i statistika.
- Porez 2% i godišnji minimum, zvanični Obrazac 1007, doprinosi i popunjene uplatnice.
- Pravila po godinama, lokalna SQLite baza, dnevni backup i vraćanje kopije.
- Probni period od 30 dana i licence; automatska ažuriranja na Windowsu i Linuxu.
