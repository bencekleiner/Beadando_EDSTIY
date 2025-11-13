Készítette: 

- Kleiner Bence

Program neve:

- Autókatalógus

Leírás:

Egyszerű autókatalógus-kezelő program, ahol az autók adatai megadhatók, módosíthatók, törölhetők, kereshetők és elmenthetők.

A program indítása

A program az autokatalogus.py nevű fájlban található.

Futtatásához Python szükséges 

Indítás parancssorból:

- python autokatalogus.py

A program működése

A program indításakor 20 autó már betöltve látható a listában.

A főablak egyetlen fülből (tabból) áll, ahol az alábbi részek találhatók:

- Adatbevitel 

Itt adhatók meg az autó adatai:
- rendszám
- márka
- modell
- év
- szín
- ár

Gombok
- Hozzáadás
- Módosítás
- Törlés
- TXT mentés
- Kilépés
• Keresés

Valós idejű szűrés márka, modell, rendszám vagy szín alapján.

Lista

A táblázat mutatja az autók adatait, például:

AAA-111 | Toyota Corolla | 2018 | fehér | 4 490 000 Ft

Státuszsor

- Megjeleníti a találatok számát, illetve a legutóbbi műveletet (pl. „Hozzáadva”, „Törölve”).

Hibakezelés

Hibás rendszám esetén:

- Hibás rendszám! Formátum: AAA-111 (3 betű, kötőjel, 3 szám).

Hiányzó adat vagy már létező rendszám esetén megfelelő hibaüzenet jelenik meg.

Adatmentés

A-  TXT mentés gombbal a listában lévő autók elmenthetők egy .txt fájlba.

A fájl minden sora egy autót tartalmaz, például:

AAA-111 | Toyota Corolla | 2018 | fehér | 4 490 000 Ft

Kilépés

A Kilépés gombbal vagy az ablak bezárásával a program egyszerűen bezárható.

Felhasznált elemek

Modulok
- tkinter – grafikus felület
- ttk – modern widgetek
- messagebox – hibaüzenetek
- filedialog – fájlmentés
- dataclasses – Auto osztályhoz
- re – rendszám ellenőrzéséhez


