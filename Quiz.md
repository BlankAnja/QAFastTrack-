# QAFastTrack-

Co to są testy regresyjne?
Jeśli została wprowadzona nowa funkcjonalność do oprogramowania, wtedy testujemy czy wszystkie funkcjonalności, które były w aplikacji przed zmianą, nadal działają dobrze.

Co to jest GIT?
Program do rejestrowania historii zmian – kiedy zostały zrobione i przez jakiego użytkownika. Są w nim przedstawione zadania, które należą do konkretnego brunchu?

Jak może pisać kilku programistów na raz?
Każdy musi dodawać swoje kawałki do najnowszej wersji. Każdy pracuje na swojej gałęzi i każda zmiana po skończeniu musi być dodana do głównej gałęzi.

Co to jest test plan?
Zbiór przypadków testowych.

Co to są test case?
Jeden konkretny przypadek, który ma w sobie kroki i oczekiwany rezultat.

Jak się mają zadania do brunchów?
Brunch deweloperski jest oddzielny dla brunchu Master (dla klienta).
Najczęściej zadanie = brunch, ale może być też ileś zadań na jednym brunchu.

Jak się ustawia zadania w Kanbanie?
Wszystkie zadania daje się do tablicy i ustawia się priorytety. Nie ma terminów, więc koncentruje się na kolumnie "In progress"

Co to jest DOR?
Definicja co musi zostać spełnione, żeby developerzy mogli zacząć robotę.


---------------------
serwer + app
środowisko produkcyjne
-------------------
serwer + app
środowisko pre-prod (dla klienta / acceptance test)
------------------
serwer + app
środowisko testowe
--------------------
serwer + app
środowisko deweloperskie

Co to jest release version?
Wydanie wersji, które otrzymuje konkretny numer, np. W.0.0.12

------------------

Behavior Driven Development


Given (initial conditions)

When ( test steps) 

Then (exp results)


Jako Użytkownik będąc na ekranie detali filmu widzę dostępne trailery

Wchodzę na ekran detali filmu,
Dane się pobierają 
Na ekranie detali filmu widzę trailery

Jako Użytkownik mogę odtworzyć dostępny trailer na ekranie filmu
