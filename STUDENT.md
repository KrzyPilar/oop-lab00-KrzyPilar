# Moje wykonanie Lab00

- Login GitHub / pseudonim: KrzyPilar
- System i terminal (np. Windows + WSL Ubuntu): Windows 11 + PowerShell
- Edytor / IDE:	Visual Studio
- Wersja Git: 2.55.0.windows.5
- Wersja kompilatora C++: g++.exe (MinGW.org GCC-6.3.0-1) 6.3.0
- Wersje java i javac: java version "25.0.4.1", javac 25.0.4.1
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/KrzyPilar/oop-lab00-KrzyPilar/pull/1

## Uruchomienie lokalne
Wynik programu C++:
Hello from C++! Author: KrzyPilar

Wynik programu Java:
Hello from Java! Author: KrzyPilar

## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: 
- cpp/main.cpp: In function 'int main()':
cpp/main.cpp:6:5: error: expected ';' before 'return'
     return 0;
     ^~~~~~
- Przyczyna oraz sposób naprawy: brak średnika na końcu linii 5, naprawą jest dodanie średnika
- Commit z błędem (SHA lub link): https://github.com/KrzyPilar/oop-lab00-KrzyPilar/commit/73a6551f4aa411a15d67946c65c2da5b3e3448bb
- Czy Actions pokazały błąd, a po naprawie sukces? tak

## Krótkie odpowiedzi
1. Co różni commit od push? commit zapisuje zmiany w lokalnym repozytorium, natomiast push wysyła te zmiany do zdalnego repozytorium
i umożliwia pull request
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? aby pobrać zmiany z repozytorium zdalnego do lokalnego i zsynchronizować je
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? zielony wynik CI potwierdza, że program kompiluje się
i działa poprawnie, tj. nie zawiera błędów składniowych ani błędów związanych z testami. Nie potwierdza natomiast, że program
działa zgodnie z oczekiwaniami użytkownika, tj. nie zawiera błędów logicznych ani nie spełnia innych wymagań, 
jak wygląd lub funkcja programu.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: Moja maszyna lokalna nie posiadała odpowiedniego kompilatora Javy,
więc musiałem zainstalować JDK w odpowiedniej wersji
