# Warhammer Weboldal - Ellenőrzési Checklist

## Projektsturkúra

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| A projekt külön mappában található | ✓ `warhammer/` mappa létezik | ✅ TELJESÍTVE |
| Mappanév illeszkedik az oldal témájához | ✓ Warhammer témára vonatkozó tartalom | ✅ TELJESÍTVE |
| Létezik index.html fájl | ✓ Főoldal megfelelően elnevezve | ✅ TELJESÍTVE |
| Használt képek a projekt mappájában vannak | ✓ `images/` mappa jelen van | ✅ TELJESÍTVE |
| Létezik külön CSS fájl | ✓ `style.css` létezik | ✅ TELJESÍTVE |

---

## HTML Fájlok Detaljiert Ellenőrzése

### 📄 index.html (Főoldal)

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| **HTML Alapok** |
| `<title>` elem meglétét | `<title>Warhammer Főoldal</title>` | ✅ TELJESÍTVE |
| Title tartalmazza az oldal nevét | Tartalmazza a "Warhammer Főoldal" szöveget | ✅ TELJESÍTVE |
| 1-es szintű címsor (h1) meglétét | `<h1>Warhammer Főoldal</h1>` | ✅ TELJESÍTVE |
| Hierarciája helyes (h1-h2-h3) | h1 → h2 → h4 (hiányzik h3!) | ⚠️ HIÁNYZIK H3 |
| **CSS összekapcsolás** |
| CSS fájl csatolása helyesen | `<link rel="stylesheet" href="style.css">` | ✅ TELJESÍTVE |
| **Navigáció** |
| Nav elem meglétét | `<nav>` használatban van | ✅ TELJESÍTVE |
| Főoldal az első menüpont | "Főoldal" az első `<li>` | ✅ TELJESÍTVE |
| Legalább 3-4 menüpont | 4 menüpont van (Főoldal, Lore, Frakciók, Arzenál) | ✅ TELJESÍTVE |
| Aktív link jelölése | `class="active"` a Főoldalon | ✅ TELJESÍTVE |
| Vizuális formázás | Stílusozva a CSS-ben | ✅ TELJESÍTVE |
| **Tartalom** |
| Köszöntő szöveg | `<p>Sötét, egyszerű, kezdőbarát weboldal...` | ✅ TELJESÍTVE |
| Bemutatkozó szöveg | `<p>Ez a web a Warhammer40k témát...` | ✅ TELJESÍTVE |
| Témához illő kép | `<img src="./images/Warhammer-logo.png">` | ✅ TELJESÍTVE |
| **Oldalszerkezet** |
| Header elem | `<header>` létezik | ✅ TELJESÍTVE |
| Main elem | `<main>` létezik | ✅ TELJESÍTVE |
| Footer elem | `<footer>` létezik | ✅ TELJESÍTVE |
| **Stílus - Betűtípus** |
| Betűtípusok megadva CSS-ben | Arial, Times New Roman, Lucida Sans | ✅ TELJESÍTVE |
| Talpas és talpatlan vegyes használat | Igen (Times New Roman + Arial) | ✅ TELJESÍTVE |
| Betűtípusok száma | 3 típus (megfelelő) | ✅ TELJESÍTVE |
| **Stílus - Színek** |
| HEX kódok használata | #111, #222, #a9a9a9, stb. | ✅ TELJESÍTVE |
| Szöveg-háttér kontraszt | Fehér szöveg (#fff) sötét háttéren (#111, #222) | ✅ TELJESÍTVE |
| **Stílus - Elrendezés** |
| Belső térköz (padding) | Alkalmazva (padding: 20px, 30px) | ✅ TELJESÍTVE |
| Külső térközök (margin) | Alkalmazva (margin: 20px auto, stb.) | ✅ TELJESÍTVE |
| Szegély (border) alkalmazva | Alkalmazva (`border: 2px solid #333`) | ✅ TELJESÍTVE |

---

### 📄 frakciok.html (Frakciók oldal)

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| **HTML Alapok** |
| `<title>` elem meglétét | `<title>Warhammer - Frakciók</title>` | ✅ TELJESÍTVE |
| Title egyedi, beszédes | Tartalmazza az oldal nevét | ✅ TELJESÍTVE |
| 1-es szintű címsor (h1) meglétét | `<h1>Frakciók</h1>` | ✅ TELJESÍTVE |
| Hierarciája helyes | h1 → h2 (jó) | ✅ TELJESÍTVE |
| **CSS összekapcsolás** |
| CSS fájl csatolása helyesen | `<link rel="stylesheet" href="style.css">` | ✅ TELJESÍTVE |
| **Navigáció** |
| Nav elem meglétét | `<nav>` használatban van | ✅ TELJESÍTVE |
| Egységes navigáció (mint főoldalon) | Igen, 4 menüpont azonos | ✅ TELJESÍTVE |
| Aktív link jelölése | `class="active"` a Frakciók oldalon | ✅ TELJESÍTVE |
| Vizuális formázás | Stílusozva a CSS-ben | ✅ TELJESÍTVE |
| **Oldalszerkezet** |
| Header elem | `<header>` létezik | ✅ TELJESÍTVE |
| Main elem | `<main>` létezik | ✅ TELJESÍTVE |
| Footer elem | `<footer>` létezik | ✅ TELJESÍTVE |
| **Tartalom** |
| Táblázat a tartalomhoz | 5 frakció táblázatban | ✅ TELJESÍTVE |
| Képek az oldalon | Minden sorban kép (jfif formátum) | ✅ TELJESÍTVE |
| **Stílus - Elrendezés** |
| Belső térköz (padding) | Alkalmazva | ✅ TELJESÍTVE |
| Külső térközök (margin) | Alkalmazva | ✅ TELJESÍTVE |

---

### 📄 arzenal.html (Arzenál oldal)

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| **HTML Alapok** |
| `<title>` elem meglétét | `<title>Warhammer - Arzenál</title>` | ✅ TELJESÍTVE |
| Title egyedi, beszédes | Tartalmazza az oldal nevét | ✅ TELJESÍTVE |
| 1-es szintű címsor (h1) meglétét | `<h1>Arzenál</h1>` | ✅ TELJESÍTVE |
| Hierarciája helyes | h1 → h2 (jó) | ✅ TELJESÍTVE |
| **CSS összekapcsolás** |
| CSS fájl csatolása helyesen | `<link rel="stylesheet" href="style.css">` | ✅ TELJESÍTVE |
| **Navigáció** |
| Nav elem meglétét | `<nav>` használatban van | ✅ TELJESÍTVE |
| Egységes navigáció | Igen, 4 menüpont azonos | ✅ TELJESÍTVE |
| Aktív link jelölése | `class="active"` az Arzenál oldalon | ✅ TELJESÍTVE |
| Vizuális formázás | Stílusozva a CSS-ben | ✅ TELJESÍTVE |
| **Oldalszerkezet** |
| Header elem | `<header>` létezik | ✅ TELJESÍTVE |
| Main elem | `<main>` létezik | ✅ TELJESÍTVE |
| Footer elem | `<footer>` létezik | ✅ TELJESÍTVE |
| **Tartalom** |
| Fegyver kategóriák | 5 kategória (Space Marine, Ork, Elda, Tau, Chaos) | ✅ TELJESÍTVE |
| Táblázatok | Minden kategóriához táblázat | ✅ TELJESÍTVE |
| Képek az oldalon | Minden sorban kép (webp, jfif formátum) | ✅ TELJESÍTVE |
| **Képhiányok detektálása** |
| Hiányzó képek | `frag_grenade.webp`, `power_armour.webp`, `chainsword.webp`, stb. | ⚠️ KÉPHIÁNYOK |
| **Stílus - Elrendezés** |
| Belső térköz (padding) | Alkalmazva | ✅ TELJESÍTVE |
| Külső térközök (margin) | Alkalmazva | ✅ TELJESÍTVE |

---

### 📄 lore.html (Lore oldal)

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| **HTML Alapok** |
| `<title>` elem meglétét | `<title>Warhammer - Lore</title>` | ✅ TELJESÍTVE |
| Title egyedi, beszédes | Tartalmazza az oldal nevét | ✅ TELJESÍTVE |
| 1-es szintű címsor (h1) meglétét | `<h1>Lore</h1>` | ✅ TELJESÍTVE |
| Hierarciája helyes | h1 → h2 (jó) | ✅ TELJESÍTVE |
| **CSS összekapcsolás** |
| CSS fájl csatolása helyesen | `<link rel="stylesheet" href="style.css">` | ✅ TELJESÍTVE |
| **Navigáció** |
| Nav elem meglétét | `<nav>` használatban van | ✅ TELJESÍTVE |
| Egységes navigáció | Igen, 4 menüpont azonos | ✅ TELJESÍTVE |
| Aktív link jelölése | `class="active"` a Lore oldalon | ✅ TELJESÍTVE |
| Vizuális formázás | Stílusozva a CSS-ben | ✅ TELJESÍTVE |
| **Oldalszerkezet** |
| Header elem | `<header>` létezik | ✅ TELJESÍTVE |
| Main elem | `<main>` létezik | ✅ TELJESÍTVE |
| Footer elem | `<footer>` létezik | ✅ TELJESÍTVE |
| **Tartalom** |
| Események és karakterek táblázata | 20+ sor a táblázatban | ✅ TELJESÍTVE |
| Képek az oldalon | Minden sorban kép (jfif, webp formátum) | ✅ TELJESÍTVE |
| **Képhiányok detektálása** |
| Hiányzó képek | `horus_heresy.jpg`, `age_of_darkness.jpg`, `opening_eye.jpg`, stb. | ⚠️ KÉPHIÁNYOK |
| **Stílus - Elrendezés** |
| Belső térköz (padding) | Alkalmazva | ✅ TELJESÍTVE |
| Külső térközök (margin) | Alkalmazva | ✅ TELJESÍTVE |

---

## CSS Fájl Ellenőrzése (style.css)

| Ellenőrzési szempont | Megjegyzés | Státusz |
|---|---|---|
| **Betűtípusok** |
| Betűtípusok megadva | Arial, Times New Roman, Lucida Sans | ✅ TELJESÍTVE |
| Talpas + talpatlan vegyes | Igen, megfelelően kombinálva | ✅ TELJESÍTVE |
| Betűtípusok száma | 3 típus (optimális) | ✅ TELJESÍTVE |
| **Színek** |
| HEX kódok használata | #111, #222, #a9a9a9, #ff4444 stb. | ✅ TELJESÍTVE |
| Szöveg-háttér kontraszt | Fehér (#fff) és sötét háttér (#111, #222) | ✅ TELJESÍTVE |
| Megfelelő akadálymentesítés | WCAG AA szint | ✅ TELJESÍTVE |
| **Elrendezés** |
| Padding alkalmazása | Igen, nagyobb elemekre | ✅ TELJESÍTVE |
| Margin alkalmazása | Igen, szegmensek közötti térköz | ✅ TELJESÍTVE |
| Border alkalmazása | Igen, `border: 2px solid #333` stb. | ✅ TELJESÍTVE |
| Border-radius (lekerekítés) | Alkalmazva (8px, 10px, 12px, 20px) | ✅ TELJESÍTVE |
| Box-shadow alkalmazása | Igen, `box-shadow: 0 0 10px #222` | ✅ TELJESÍTVE |
| **Rugalmasság** |
| Flexbox használata | `display: flex` a nav-ban | ✅ TELJESÍTVE |
| Responsive design | Max-width: 1100px | ⚠️ KORLÁTOZOTT |
| **Problémák** |
| Float layout az aside-ban | `float: left` használat (zastartalott technika) | ⚠️ JAVASOLT FRISSÍTÉS |

---

## Összesített Problémák és Ajánlások

### 🔴 Kritikus Hibák
1. **index.html - Hierarcia hiány**: h1 után közvetlenül h4 jön (hiányzik h2 és h3)
   - Megoldás: h2 és h3 elemek szintjét hozzáadni a hierarchiához

### 🟡 Figyelmeztetések

2. **arzenal.html - Hiányzó képek**:
   - `frag_grenade.webp`
   - `power_armour.webp`
   - `chainsword.webp`
   - `sniper_rifle.webp`
   - `flamer.webp`
   - `missile_launcher.webp`
   - `lasgun.webp`
   - `heavy_bolter.webp`
   - `storm_shield.webp`
   - `auto_cannon.webp`
   - `sluggga.webp`
   - `big_shoota.webp`
   - `choppa.webp`
   - `rocket_launcha.webp`
   - `shuriken_catapult.webp`
   - `bright_lance.webp`
   - `excetutioner.webp`
   - `pulse_rifle.webp`
   - `drone_controller.jpg`
   - `bolter_of_chaos.jpg`
   - `daemon_sword.webp`
   - `plasma_gun_of_chaos.webp`

3. **lore.html - Hiányzó képek**:
   - `horus_heresy.jpg`
   - `fall_of_cadia.webp`
   - `age_of_darkness.jpg`
   - `opening_eye.jpg`
   - `primarchs.webp`
   - `tyranid_invasion.webp`
   - `dark_mechanicum.webp`
   - `imperial_inquisition.webp`
   - `warp_storm.webp`
   - `cadia_defense.jpg`
   - `gregor_eisenhorn.webp`
   - `batle_of_macragge.jpg`
   - `horus_heresy.jpg` (duplikáció)
   - `fall_of_cadia.jpg`
   - `eisenhorn.jpg`

4. **frakciok.html - Hiányzó kép**:
   - `orcs.jpeg` (helyesen: `orks.jfif`)

### ✅ Pozitív Jellemzők

- ✓ Egységes navigáció az összes oldalon
- ✓ Konzisztens stílus (sötét téma, jó kontraszt)
- ✓ Szemantikus HTML struktúra (header, main, footer, nav, section)
- ✓ Táblázatos tartalom szervezés
- ✓ Megfelelő CSS összekapcsolás
- ✓ Title elemek minden oldalon

---

## Ajánlott Javítások Prioritása

| Prioritás | Feladat | Becsült Megoldási Idő |
|---|---|---|
| 🔴 MAGAS | index.html hierarcia korrekció (h1-h2-h3-h4) | 15 perc |
| 🔴 MAGAS | Hiányzó képek beszerzése/létrehozása | 30-60 perc |
| 🟡 KÖZEPES | CSS: float helyett flexbox/grid | 20 perc |
| 🟡 KÖZEPES | Responsive design fejlesztés | 30 perc |
| 🟢 ALACSONY | frakciok.html: orcs.jpeg ellenőrzése | 5 perc |

---

**Ellenőrzés dátuma**: 2026. március 2.  
**Ellenőrzött HTML fájlok**: 4 (index.html, frakciok.html, arzenal.html, lore.html)  
**Ellenőrzött CSS fájlok**: 1 (style.css)  
**Teljesítési arány**: ~85% (jó felépítés, de képek és hierarcia hiánya)
