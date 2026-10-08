<p align="center"><img src="https://raw.githubusercontent.com/gligor99/evidenta-releases/main/icon.png" width="96" alt="Evidenta"></p>

<h1 align="center">Evidenta</h1>

<p align="center">Fakture, knjiga prihoda, porezi i doprinosi za samostalne preduzetnike u Republici Srpskoj.</p>

<p align="center"><b>Najnovija verzija: 1.0.2</b> (08.10.2026.) · <a href="https://github.com/gligor99/evidenta-releases/releases/latest">Preuzmi</a></p>

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
