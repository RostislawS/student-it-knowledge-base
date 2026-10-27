# WARP — Git Cheatsheet
## 1. `git clone` — klonowanie repozytorium
Pobiera repozytorium ze zdalnego serwera.
```bash
git clone URL
```
## 2. `git status` — stan repozytorium
Wyświetla informacje o zmienionych plikach i aktualnej gałęzi.
```bash
git status
```
## 3. `git add` — przygotowanie zmian
Dodaje pliki do obszaru staging przed utworzeniem commita.
```bash
git add README.md
```
## 4. `git commit` — zapis zmian
Zapisuje przygotowane zmiany w historii repozytorium.
```bash
git commit -m "docs: update README"
```
## 5. `git push` — wysyłanie zmian
Wysyła lokalne commity do zdalnego repozytorium.
```bash
git push
```
## 6. `git pull` — pobieranie zmian
Pobiera i integruje zmiany ze zdalnego repozytorium.
```bash
git pull
```
## 7. `git fetch` — pobieranie informacji
Pobiera informacje o zmianach na zdalnym serwerze bez automatycznej integracji.
```bash
git fetch origin
```
## 8. `git switch` — zmiana gałęzi
Przełącza na istniejącą gałąź lub tworzy nową.
```bash
git switch main
git switch -c feature/example
```
## 9. `git branch` — lista gałęzi
Wyświetla lokalne gałęzie repozytorium.
```bash
git branch
```
## 10. `git log` — historia commitów
Wyświetla historię zmian.
```bash
git log --oneline
```
## Typowy proces pracy