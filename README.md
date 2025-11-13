Autókatalógus program – Felhasználói leírás
Kleiner Bence
Program neve: Autókatalógus
Leírás: Egyszerű autókatalógus-kezelő program, ahol az autók adatai megadhatók, módosíthatók, törölhetők, kereshetők és elmenthetők.
A program indítása
A program egy 'autokatalogus.py' nevű fájlban található. A futtatáshoz Python szükséges (ajánlott: Python 3.10 vagy újabb).
Indítás parancssorból:
python autokatalogus.py
A program működése
A program indításakor 20 autó már betöltve látható a listában. A főablak egyetlen fülből (tabból) áll, ahol az alábbi részek találhatók:
•	Adatbevitel (felső rész): itt adhatók meg az autó adatai (rendszám, márka, modell, év, szín, ár).
•	Gombok: Hozzáadás, Módosítás, Törlés, TXT mentés, Kilépés.
•	Keresés: valós idejű szűrés márka, modell, rendszám vagy szín alapján.
•	Lista: a táblázat mutatja az autók adatait.
•	Státuszsor: mutatja a találatok számát és az utolsó műveletet.
Hibakezelés
• Hibás rendszám esetén a program figyelmeztet: 'Hibás rendszám! Formátum: AAA-111 (3 betű, kötőjel, 3 szám).'
• Hiányzó adat vagy már létező rendszám esetén hibaüzenet jelenik meg.
Adatmentés
A TXT mentés gombbal a listában lévő autók elmenthetők egy .txt fájlba. A fájl minden sora egy autót tartalmaz az alábbi formátumban:
AAA-111 | Toyota Corolla | 2018 | fehér | 4 490 000 Ft
Kilépés
A 'Kilépés' gombbal vagy az ablak bezárásával a program bezárható.





Modulok
•	tkinter – grafikus felület
•	ttk – modern widgetek
•	messagebox – hibaüzenetek
•	filedialog – fájlmentés
•	dataclasses – Auto osztályhoz
•	re – rendszám ellenőrzéséhez
Osztályok
•	Auto – autó adatai
•	Katalogus – autók listájának kezelése
•	KatalogusTab – a teljes GUI működtetése
 Függvények
•	szam_egesz() – egész szám ellenőrzése
•	szam_penz() – ár ellenőrzése
•	penz_formaz() – ár formázása
•	rendszam_ellenorzes() – rendszám formátumának ellenőrzése

