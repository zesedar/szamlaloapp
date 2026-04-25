# Ismétlés-számláló (PWA)

Egy modern, letisztult és mobilra optimalizált edzéssegéd alkalmazás, amely segít az ismétlések és szettek pontos követésében. Az alkalmazás Progressive Web App (PWA) technológiára épül, így telepíthető telefonra és offline is teljes értékűen használható.

## 🚀 Főbb funkciók

* **Intelligens számláló:** Nagy, teljes képernyős koppintási felület az ismétlések rögzítéséhez.
* **Edzésprofilok:** Egyénileg testreszabható profilok . Piramis és fordított piramis gyakorlatok automatán. 
* **Időzítők:** Beépített pihenőidő-számláló és ismétlésenkénti tempókövető hangjelzéssel.
* **Interaktív visszajelzés:**
    * **Hangos számolás:** Magyar nyelvű hangbemondás (Web Speech API).
    * **Vizuális jelzések:** Színkódolt állapotok a pihenőhöz, aktív szetthez és a cél eléréséhez.
    * **Haptikus visszajelzés:** Rezgő megerősítés minden rögzített ismétlésnél.
* **Edzésnapló:** Automatikus mentés a napi teljesítményről és a korábbi edzések visszanézhetősége.
* **Képernyő ébrentartás:** Megakadályozza a kijelző kikapcsolását (Wake Lock) az edzés ideje alatt.

## 🛠 Technikai részletek

* **Offline támogatás:** Service Worker és Web Manifest a natív alkalmazásélményért.
* **Adattárolás:** `localStorage` alapú 
* **Külső függőség nélkül:** Tiszta HTML, CSS és JavaScript (Vanilla JS).

## 📖 Használat

1. Nyisd meg az `index.html` fájlt egy modern böngészőben.
2. Válassz egy profilt a felső listából, vagy állíts be újat a fogaskerék a ... vagy fogaskerék ikonra kattintva.
3. Koppints a kijelző közepére az ismétlések számolásához, vagy állísd be automatára. 
4. A szett végén használd az "Új szett" gombot a pihenőidő indításához. Ez szándékosan maradt manuális a beállítható pihenőidők ellenére is. 

---
