<p align="center"><img src="https://raw.githubusercontent.com/gligor99/evidenta-releases/main/icon.png" width="96" alt="Evidenta"></p>

<h1 align="center">Evidenta</h1>

<p align="center">Fakture, knjiga prihoda, porezi i doprinosi za samostalne preduzetnike u Republici Srpskoj.</p>

<p align="center"><b>Najnovija verzija: 1.0.0</b> (17.10.2026.) · <a href="https://github.com/gligor99/evidenta-releases/releases/latest">Preuzmi</a></p>

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

### 1.0.0 — 17.10.2026.

Prvo zvanično izdanje Evidente.

#### Poslovanje
- **Klijenti, fakture i profakture** sa četiri šablona, na bosanskom, engleskom ili dvojezično, u KM, EUR ili USD.
- **Nacrt → izdata faktura:** izdata se ne mijenja, ispravka ide preko storna. Svaka izmjena se bilježi u dnevnik.
- **Uvoz postojećih faktura** iz bilo kog programa, i skeniranih ili fotografisanih (PDF, JPG, PNG), bez interneta. Ulazni računi idu u troškove.
- **Uvoz izvoda iz banke (CSV):** uplate zatvaraju fakture, a porez, doprinosi i troškovi se upisuju sami.
- **Radni sati** sa tajmerom i prebacivanjem na fakturu.

#### Knjigovodstvo
- **Knjiga prihoda** koja se vodi sama, **troškovi** po kategorijama i **izvoz u Excel** za knjigovođu.
- **Porez 2%** i godišnji minimum, zvanični **Obrazac 1007** (mjesečni i godišnji), **doprinosi** i evidencija uplata sa datumom.
- **Uplatnice** za javne prihode, popunjene i sa predlošcima, sa linijama za potpis nalogodavca i ovlaštenog lica.
- **Rokovi na početnoj, podsjetnici** i dodavanje rokova u Google, Apple ili Outlook kalendar.

#### Ostalo
- Statistika, čarobnjak za prvo pokretanje, lokalna baza, dnevni backup i vraćanje kopije.
- Probni period od 30 dana. **Kupovina licence direktno iz aplikacije** (*Postavke → Licenca i ažuriranja*).
- Automatska ažuriranja na Windowsu i Linuxu, obavijest o novoj verziji na macOS-u. Verzije za Windows, macOS (Apple Silicon i Intel) i Linux.
