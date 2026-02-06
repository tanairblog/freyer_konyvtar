# 📚 Frayer Könyvtár

Egy modern, böngészőben futtatható oktatási segédeszköz a **Frayer-modell** alapú fogalomfeldolgozáshoz. Az alkalmazás segítségével könnyedén létrehozhatsz, szerkeszthetsz és rendszerezhetsz fogalomkártyákat, amelyeket digitálisan tárolhatsz.

## ✨ Főbb funkciók

* **Vizuális megjelenítés:** A klasszikus Frayer-modell elrendezés (Definíció, Jellemzők, Példák, Ellenpéldák) modern, áttekinthető formában.
* **Fogalmak kezelése:**
    * Új fogalmak létrehozása.
    * Meglévő fogalmak szerkesztése.
    * Fogalmak törlése (biztonsági megerősítéssel).
* **Keresés:** Azonnali szűrés a fogalmak neve alapján.
* **Import / Export:**
    * Adatok mentése CSV fájlba (Excel-kompatibilis).
    * Korábbi adatbázisok visszatöltése.
    * *Megjegyzés: Az adatok a böngésző bezárásakor elvesznek, ha nem exportálod őket!*
* **Adatbiztonság:** Az alkalmazás figyelmeztet, ha mentetlen változtatásokkal próbálod bezárni az ablakot.
* **Reszponzív dizájn:** Mobilon, tableten és asztali gépen is optimalizált megjelenés.
* **Offline működés:** Egyetlen HTML fájlból áll, internetkapcsolat nélkül is használható (kivéve a betűtípusok első betöltését).

## 🚀 Használat

Mivel ez egy "single-file" (egyfájlos) alkalmazás, nincs szükség telepítésre vagy szerverre.

1.  Mentsd le a `frayer.html` fájlt a számítógépedre.
2.  Nyisd meg a fájlt bármelyik modern böngészőben (Chrome, Edge, Firefox, Safari).
3.  Kezdd el felvinni a fogalmakat az "Új hozzáadása" gombbal.

## 💾 Adatkezelés (CSV formátum)

Az alkalmazás `.csv` formátumot használ az adatok mentésére és betöltésére. Ez lehetővé teszi, hogy Excelben vagy Google Sheetsben is szerkeszthesd az adataidat.

**Az elvárt CSV struktúra importálásnál:**
A fájl kódolása legyen **UTF-8**. Az elválasztó karakter lehet pontosvessző (`;`) vagy vessző (`,`).

Fejléc sor (opcionális, de ajánlott):
`Név;Meghatározás;Jellemzők;Példák;Ellenpéldák`

**Példa sor:**
`"Négyszög";"Négy oldala van";"Zárt alakzat, 4 csúcs";"Téglalap, Rombusz";"Háromszög, Kör"`

## 🛠️ Technikai háttér

A projekt tisztán szabványos webes technológiákra épül, külső keretrendszerek (mint React vagy Vue) nélkül.

* **HTML5:** Szemantikus felépítés.
* **CSS3:** Flexbox és Grid layout, CSS változók a könnyű témázhatóságért.
* **JavaScript (ES6+):** Vanilla JS az állapotkezeléshez és a DOM manipulációhoz.
* **Betűtípus:** Google Fonts (Inter).

## ⚠️ Fontos tudnivalók

* **Mentés:** Az alkalmazás a böngésző memóriájában tárolja az adatokat. Ha frissíted az oldalt vagy bezárod a lapot exportálás nélkül, **az adatok elvesznek**. Mindig használd az "Exportálás" gombot a munka végeztével!
* **Képek:** A jelenlegi verzió csak szöveges adatokat kezel.

## 📝 Licenc

Ez egy nyílt forráskódú projekt, szabadon módosítható és felhasználható oktatási vagy magáncélra.
