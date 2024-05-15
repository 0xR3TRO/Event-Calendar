## Opis projektu

### Cel:

Projekt "Event Calendar" ma na celu dostarczenie użytkownikom narzędzia do zarządzania wydarzeniami poprzez prostą i intuicyjną aplikację internetową. Aplikacja umożliwia dodawanie, edytowanie oraz przeglądanie wydarzeń w kalendarzu, co pozwala na lepszą organizację czasu i planowanie aktywności.

### Opis funkcji:

- **Dodawanie wydarzeń:** Użytkownicy mogą dodawać nowe wydarzenia do kalendarza, określając tytuł, datę, godzinę, opis oraz lokalizację.
- **Edytowanie wydarzeń:** Możliwość edytowania szczegółów istniejących wydarzeń.
- **Przeglądanie kalendarza:** Intuicyjny interfejs do przeglądania miesięcznego, tygodniowego oraz dziennego widoku wydarzeń.
- **Powiadomienia:** Opcja ustawienia przypomnień o nadchodzących wydarzeniach.

## Analiza wymagań:

### Wymagania funkcjonalne:

- **Dodawanie wydarzeń:** Formularz do wprowadzania szczegółów wydarzenia, takich jak tytuł, data, godzina, opis i lokalizacja.
- **Edytowanie wydarzeń:** Interfejs umożliwiający modyfikację szczegółów wydarzeń.
- **Przeglądanie kalendarza:** Widoki kalendarza w formie miesięcznej, tygodniowej oraz dziennej.
- **Powiadomienia:** Możliwość ustawienia przypomnień o wydarzeniach poprzez e-mail lub powiadomienia push.

### Wymagania niefunkcjonalne:

- **Intuicyjność:** Łatwy w obsłudze interfejs, zrozumiały nawet dla nowych użytkowników.
- **Szybkość działania:** Aplikacja powinna szybko reagować na działania użytkownika, minimalizując opóźnienia.
- **Dostępność:** Aplikacja powinna być dostępna na różnych urządzeniach, w tym komputerach, tabletach i smartfonach.

## Projekt interfejsu:

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Przegląd kalendarza z opcjami dodawania i edytowania wydarzeń.
- _Okno dodawania/edytowania wydarzenia:_ Formularz do wprowadzania i modyfikowania szczegółów wydarzeń.
- _Widok kalendarza:_ Miesięczny, tygodniowy i dzienny widok kalendarza z oznaczonymi wydarzeniami.

### Mapa strony:

- _Strona główna_
  - Widok kalendarza
  - Opcja dodawania wydarzeń
  - Lista nadchodzących wydarzeń
- _Okno dodawania/edytowania wydarzenia_
  - Formularz dodawania/edytowania wydarzeń
- _Powiadomienia_
  - Ustawienia przypomnień

## Architektura systemu:

### Opis struktury danych:

Aplikacja przechowuje dane dotyczące wydarzeń, w tym:

- **Wydarzenia:** Informacje o tytule, dacie, godzinie, opisie i lokalizacji wydarzenia.
- **Powiadomienia:** Dane o ustawieniach przypomnień dla poszczególnych wydarzeń.

### Diagramy architektury:

Architektura oparta jest na strukturze MVC (Model-View-Controller), gdzie:

- **Model:** Odpowiada za logikę zarządzania wydarzeniami i powiadomieniami.
- **Widok (View):** Prezentuje interfejs użytkownika.
- **Kontroler (Controller):** Zarządza komunikacją między modelem a widokiem.

## Implementacja:

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js).
- **Backend:** Node.js (Express), MongoDB (baza danych).
- **Powiadomienia:** Usługi zewnętrzne takie jak Twilio dla SMS, SendGrid dla e-maili.

### Struktura kodu:

- _Katalogi/pliki:_ Oddzielne pliki dla logiki zarządzania wydarzeniami, interfejsu użytkownika, zarządzania powiadomieniami.
- _Style pisania kodu:_ Zastosowanie modularności, czytelności i komentarzy w kodzie.

## Testowanie:

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności funkcji dodawania i edytowania wydarzeń.
- **Testy integracyjne:** Upewnienie się, że komponenty współpracują ze sobą poprawnie.
- **Testy interfejsu użytkownika:** Sprawdzenie interakcji z użytkownikiem na różnych urządzeniach.
- **Testy wydajnościowe:** Ocena wydajności działania aplikacji przy różnych obciążeniach.

### Procedury testowania:

- Opracowanie zestawu przypadków testowych dla każdej funkcji aplikacji.
- Ustalenie procedur raportowania i naprawiania znalezionych błędów.

## Wdrożenie i konserwacja:

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie, poprawki, publikacja na platformach dostępnych dla użytkowników.
- **Terminy:** Określenie dat planowanych etapów wdrożenia.

### Procedury konserwacji:

- **Wsparcie techniczne:** Ustanowienie kanałów komunikacji z użytkownikami w celu zgłaszania problemów.
- **Aktualizacje:** Planowanie regularnych aktualizacji w zależności od potrzeb i feedbacku użytkowników.

## Harmonogram:

### Plan projektu:

- **Etapy realizacji:** Podział prac na konkretne zadania (np. implementacja funkcji dodawania, edytowania, testowanie).
- **Terminy:** Określenie czasu potrzebnego na każdy etap.

## Kosztorys:

### Szacunkowe koszty:

- **Rozwój aplikacji:** Wg godzin pracy lub zespołu programistów.
- **Koszty utrzymania:** Serwery, ewentualne opłaty za usługi zewnętrzne, wsparcie techniczne.
