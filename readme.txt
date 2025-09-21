Készítette

Nagy Dániel József & Kürtösi Tamás
Képzés: Szoftverfejlesztő és -tesztelő
Dátum: 2025. szeptember 1.

Rendszer áttekintése

Ez a szoftver a képzés részeként készült vizsgaremek. A célja egy valós probléma megoldása – például [foglalási rendszer / galériakezelő / eseménykezelő – ide írd a te projekted témáját].
A rendszer felépítése:

Frontend: HTML, CSS, JavaScript [opcionálisan React / Bootstrap]
Backend: PHP [vagy más választott nyelv pl. Node.js, Python]
Adatbázis: MySQL [vagy PostgreSQL, SQLite, MongoDB]
Verziókezelés: Git, GitHub

Felhasználói szerepkörök

A rendszer kétféle felhasználót kezel:
Adminisztrátor
Bejelentkezhet a rendszerbe
Tartalmakat hozhat létre, módosíthat és törölhet (pl. galéria, események, szolgáltatások)
Jogosultsággal rendelkezik a teljes admin felülethez

Felhasználó

Nyilvános tartalmak megtekintése (pl. események, galéria)
Nem fér hozzá az admin funkciókhoz

(Ha nálad nincs regisztráció, hanem csak admin és galéria kezelő van, akkor ezt egyszerűen írd át a saját projektedhez: „A rendszerben csak az admin és a galéria-kezelő felhasználó létezik, nincs további regisztráció.”)

Verzió és környezet

PHP verzió: 8.x
Laravel verzió (ha használtad): 10.x / 11.x
Adatbázis: MySQL 8.x
Tesztkörnyezet: Windows 10/11 + XAMPP / Linux szerver
Böngészők: Google Chrome, Firefox, Edge

Telepítés

Klónozd a projektet:

git clone https://github.com/Urian91/ImPro


Telepítsd a függőségeket:

composer install
npm install && npm run dev


Hozd létre a .env fájlt és állítsd be az adatbázis kapcsolatot.

Futtasd a migrációkat:

php artisan migrate


Indítsd el a szervert:

php artisan serve

Verziókövetés

0.1.0 – Első működő prototípus

0.2.0 – Adatbázis csatlakoztatása

1.0.0 – Stabil verzió, admin és felhasználói funkciók