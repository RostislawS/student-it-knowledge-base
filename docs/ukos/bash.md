# UKOS — Bash Cheatsheet
## 1. `pwd` — bieżący katalog
Wyświetla ścieżkę aktualnego katalogu.
```bash
pwd
```
## 2. `ls` — lista plików
Wyświetla pliki i katalogi. Opcja `-la` pokazuje również ukryte pliki i szczegółowe informacje.
```bash
ls -la
```
## 3. `cd` — zmiana katalogu
Pozwala przejść do innego katalogu. `..` oznacza katalog nadrzędny.
```bash
cd docs/ukos
cd ..
```
## 4. `mkdir` — tworzenie katalogu
Tworzy nowy katalog. Opcja `-p` pozwala utworzyć również katalogi nadrzędne.
```bash
mkdir -p docs/ukos
```
## 5. `touch` — tworzenie pliku
Tworzy pusty plik, jeśli plik nie istnieje, albo aktualizuje czas jego modyfikacji.
```bash
touch bash.md
```
## 6. `cp` — kopiowanie pliku
Tworzy kopię pliku. Opcja `-r` służy do kopiowania katalogów.
```bash
cp bash.md bash-backup.md
cp -r docs docs-backup
```
## 7. `mv` — przenoszenie i zmiana nazwy
Przenosi plik lub zmienia jego nazwę.
```bash
mv bash-backup.md archive.md
```
## 8. `rm` — usuwanie pliku
Usuwa plik. Uwaga: usunięcie zwykle omija kosz systemowy, dlatego przed wykonaniem polecenia sprawdź nazwę pliku.
```bash
rm archive.md
```
## 9. `cat` — wyświetlanie zawartości
Wyświetla zawartość pliku tekstowego w terminalu.
```bash
cat bash.md
```
## 10. `clear` — czyszczenie terminala
Czyści widok terminala, ale nie usuwa plików ani historii poleceń.
```bash
clear
```