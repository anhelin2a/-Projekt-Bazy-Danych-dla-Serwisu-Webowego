# Projekt Bazy Danych dla Serwisu Webowego


Celem projektu jest stworzenie kompletnej bazy danych, która obsłuży użytkowników, posty, kalendarze, wydarzenia i inne funkcje potrzebne dla serwisu webowego. Baza powstała na potrzeby grupowego projektu: https://github.com/Velfoy/Project_web

Projekt jest nadal w trakcie rozwoju i planowane są dalsze modyfikacje. Nowe funkcjonalności oraz optymalizacje są na bieżąco dodawane, aby poprawić wydajność i bezpieczeństwo bazy danych. Funkcjonalności serwisu są rozszerzane, więc pojawią się kolejne tabele, procedury i funkcje.

## Struktura Pliku

Struktura skryptu SQL jest podzielona na kilka sekcji:  
A: Tworzenie bazy danych dla naszego serwisu.  
B: Dodanie mechanizmów szyfrowania w celu zapewnienia bezpieczeństwa.  
C: Usuwanie ograniczeń, co może być przydatne przy zmianie struktury bazy danych.  
D: Usuwanie procedur (jeśli istnieją).  
E: Usuwanie tabel zdefiniowanych przez użytkownika.  
F: Usuwanie i tworzenie funkcji.  
G: Usuwanie i tworzenie tabel.  
H: Tworzenie procedur do obsługi logowania użytkowników.  

## Obsługa Logowania i Rejestracji Użytkowników

Projekt zawiera procedury składowane do obsługi logowania i rejestracji użytkowników:

Rejestracja Użytkowników: Procedura UserRegistration pozwala na rejestrację nowych użytkowników z hasłowanymi hasłami.  
Walidacja Logowania: Procedura UserLogInValidation służy do weryfikacji poprawności danych logowania.  
Sprawdzanie Istnienia Użytkownika: Procedura CheckIfUserExists sprawdza, czy użytkownik już istnieje w bazie danych.  
Hashowanie Haseł: Procedura HashUserPassword pozwala na hashowanie hasła za pomocą algorytmu SHA-256.  

## Informacje Dodatkowe

Baza danych zawiera tabele do przechowywania postów, wiadomości i innych danych komunikacyjnych.
Kalendarze i Wydarzenia: Tabele Calendars i Events umożliwiają śledzenie wydarzeń związanych z użytkownikami.
