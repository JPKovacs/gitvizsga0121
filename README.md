Kovács János – Git vizsga lépések - 20230121

Könyvtár létrehozása az asztalon
git_vizsga_konyvtar

GIT BASH Here parancssal ablak megnyitása

Felhasználói adatok beállítása 
git config --global user.name "Kovács János"
git config --global user.email "janos.kovacs@hotmail.hu"

Felhasználói adatok lekérése (ellenőrzés)
git config user.name
git config user.email

Git inicializálása a projektbe
git init

git clone https://github.com/szabopeter92/git-vizsga0104

git_vizsga_konyvtar megnyitása Visual Studio Code-ban

cd git-vizsga0104

git add .

git commit -m "README és gitignore fájlok létrehozva"

git branch console

git checkout console

Fájlok módosítása a feladatnak megfelelően

git add .

git commit -m "A szükséges módosítások elvégezve incl README fájl"

git status

git checkout main

git merge console

git branch -D console

git remote add origin https://github.com/JPKovacs/gitvizsga0121.git

git push -u origin main
