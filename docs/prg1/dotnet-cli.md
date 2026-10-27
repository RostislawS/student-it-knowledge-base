# PRG1 — .NET CLI Cheatsheet
## 1. `dotnet --version` — wersja SDK
Wyświetla wersję zainstalowanego .NET SDK.
```bash
dotnet --version
```
## 2. `dotnet --list-sdks` — lista SDK
Wyświetla wszystkie zainstalowane wersje .NET SDK.
```bash
dotnet --list-sdks
```
## 3. `dotnet new list` — lista szablonów
Wyświetla dostępne szablony projektów.
```bash
dotnet new list
```
## 4. `dotnet new console` — nowy projekt
Tworzy nowy projekt aplikacji konsolowej.
```bash
dotnet new console -n MyApp
```
## 5. `dotnet restore` — przywracanie zależności
Pobiera pakiety wymagane przez projekt.
```bash
dotnet restore
```
## 6. `dotnet build` — kompilacja (bob the builer)
Kompiluje projekt i wyświetla ewentualne błędy oraz ostrzeżenia.
```bash
dotnet build
```
## 7. `dotnet run` — uruchamianie programu
Kompiluje i uruchamia aplikację.
```bash
dotnet run
```
## 8. `dotnet clean` — czyszczenie projektu
Usuwa wyniki wcześniejszej kompilacji.
```bash
dotnet clean
```
## 9. `dotnet test` — uruchamianie testów
Uruchamia testy projektu, jeśli zostały przygotowane.
```bash
dotnet test
```
## 10. `dotnet publish` — przygotowanie aplikacji
Przygotowuje aplikację do wdrożenia.
```bash
dotnet publish -c Release
```
## Przykładowy proces pracy
```bash
dotnet new console -n MyApp
cd MyApp
dotnet restore
dotnet build
dotnet run
dotnet test
dotnet publish -c Release
```