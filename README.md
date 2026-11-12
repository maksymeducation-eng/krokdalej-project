# KrokDalej
 
Przeglądarkowa aplikacja to-do ze śledzeniem postępów. Projekt edukacyjny realizowany w ramach przedmiotu NPI.
 
## O projekcie
 
Ludzie często zapominają o swoich zadaniach i nie wykonują ich na czas. KrokDalej to proste i darmowe narzędzie, w którym użytkownik zakłada konto, loguje się z dowolnego urządzenia i widzi swoje zadania pogrupowane w cele z paskiem postępu.
 
**Dla kogo:** studenci oraz osoby uczące się lub budujące nawyki, które chcą mieć dostęp do zadań z każdego komputera.
 
## Funkcje (MVP)
 
- Rejestracja i logowanie (e-mail + hasło)
- Tworzenie, edycja i usuwanie celów
- Dodawanie, edycja i odhaczanie zadań przypisanych do celów
- Pasek postępu dla każdego celu (odsetek wykonanych zadań)
- Prywatność danych: hasła hashowane, HTTPS, brak dostępu do cudzych zadań
**Kryterium sukcesu MVP:** nowa osoba w mniej niż 2 minuty zakłada konto, tworzy cel z 3 zadaniami i widzi postęp.
 
**Poza zakresem:** aplikacja mobilna, współdzielenie list, logowanie przez Google, tryb offline.
 
## Stos technologiczny
 
| Obszar | Technologia |
|---|---|
| Backend | Java 21 (LTS), Spring Boot (REST API, Spring Security, Spring Data JPA) |
| Baza danych | PostgreSQL |
| Frontend | TypeScript + HTML |
| Wersjonowanie | GitHub |
| Zarządzanie zadaniami | Jira (Kanban) / GitHub Projects |
 
## Zespół
 
| Osoba | Rola |
|---|---|
| Hlib Steshenko | Manager, backend |
| Illia Shcherbakov | Backend, baza danych |
| Maksym Sevruk | Frontend |
| Artem Teletskyi | UI/UX designer |
 
## Harmonogram
 
1. **Koniec października 2026** – analiza ryzyk i wąskich gardeł
2. **Koniec października 2026** – nauka potrzebnych technologii
3. **Połowa listopada 2026** – kluczowe funkcjonalności i architektura aplikacji
4. **Grudzień 2026** – dokończenie aplikacji i przygotowanie do finalnego etapu
Terminy są orientacyjne i aktualizowane wraz z postępem prac.
 
## Główne ryzyka
 
- **Wyciek danych** – przeciwdziałanie: hashowanie haseł, HTTPS, test dostępu do cudzych zadań.
- **Rezygnacja użytkowników po kilku dniach** – motywacja przez pasek postępu.
## Weryfikacja rozwiązania
 
- Test z 10 osobami (utworzenie zadania w mniej niż 2 minuty)
- Ankieta w skali 1–5 (cel: średnia ≥ 4)
- Testy automatyczne logowania i liczenia postępu
## Uruchomienie
 
> Sekcja do uzupełnienia w miarę rozwoju projektu.
 
```bash
git clone https://github.com/maksymeducation-eng/krokdalej-project.git
cd krokdalej-project
```
 
## Linki
 
- Repozytorium: https://github.com/maksymeducation-eng/krokdalej-project
- Tablica projektu: https://github.com/users/maksymeducation-eng/projects/1
 
