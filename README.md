# whitework

Ez a repository a "photowork_on_white" projekt friss, tiszta importja.

Röviden
-------
- Fő fájl: `index.html`
- Stílusok: `css/style.css`
- Képek: `img/`

Előnézet
--------
A GitHub Pages címe (ha engedélyezve van):

https://bigsee1970.github.io/whitework/

Használat (lokálisan)
---------------------
Egyszerűen megnyithatod a `index.html` fájlt a böngésződben, vagy futtathatsz egy gyors helyi szervert:

PowerShell-ben:

```powershell
cd 'C:\Users\levai\Desktop\git\my-work'
# Python 3.x szükséges
python -m http.server 8000
# majd böngészőben: http://localhost:8000
```

Fejlesztés
---------
- Szerkeszd a fájlokat a `my-work` mappában.
- Változtatás után commit-old és push-old a `main` branch-re:

```powershell
git add .
git commit -m "Update site"
git push
```

GitHub Pages (deploy)
---------------------
A weboldal a `gh-pages` branch-ről szolgálható ki. Már létrehoztam és feltöltöttem a `gh-pages` branch-et, de a Pages beállítást a GitHub felületén szükséges ellenőrizni és engedélyezni:

1. Nyisd meg: https://github.com/bigsee1970/whitework/settings/pages
2. Forrás (Source): válaszd `gh-pages` branch és `/ (root)`.
3. Mentsd el. A változások publikálása néhány percet vehet igénybe.

Licence
-------
Egyelőre nincs licence megadva a repóhoz. Ha szeretnéd, javaslok egy egyszerű MIT licencet és hozzáadom.

Kapcsolat
--------
Ha kérdésed van, írj ide: `levai` (GitHub felhasználó)

Készítve: import script — módosítható README
