## GoIT Node.js Course Template Homework

Wykonaj forka tego repozytorium, aby wykonywać zadania domowe (2-6). Fork utworzy repozytorium na Twoim koncie na http://github.com

Dodaj mentora jako collaboratora.

Dla każdego zadania domowego utwórz nową gałąź (branch).

- hw02
- hw03
- hw04
- hw05
- hw06

Każda nowa gałąź dla zadania powinna być tworzona z gałęzi master.

Po zakończeniu wykonania zadania domowego na swojej gałęzi, należy zrobić pull request (PR). Następnie dodaj mentora do przeglądu kodu. Dopiero po zatwierdzeniu PR przez mentora możesz scalić gałąź z zadaniem domowym do gałęzi master.

Uważnie czytaj komentarze mentora. Popraw uwagi i zrób commit na gałęzi z zadaniem domowym. Zmiany automatycznie pojawią się w PR po wysłaniu commitu z poprawkami na GitHub. Po poprawkach ponownie dodaj mentora do przeglądu kodu.

- Podczas oddawania zadania domowego podaj link do PR.
- Kod JS jest czytelny i zrozumiały, do formatowania używany jest Prettier.

# Aplikacja Kontaktów

Aplikacja Kontaktów to REST API umożliwiające zarządzanie listą kontaktów. Pozwala użytkownikom na dodawanie, aktualizowanie, przeglądanie i usuwanie informacji kontaktowych. Dodatkowo, aplikacja wspiera oznaczanie kontaktów jako ulubione.

## Funkcjonalności

- **Lista kontaktów**: Pobierz listę wszystkich zapisanych kontaktów.
- **Szczegóły kontaktu**: Wyświetl szczegółowe informacje o konkretnym kontakcie.
- **Dodawanie kontaktu**: Umożliwia dodanie nowego kontaktu do listy.
- **Aktualizacja kontaktu**: Edytuj istniejące informacje kontaktowe.
- **Usuwanie kontaktu**: Usuń kontakt z listy.
- **Zarządzanie ulubionymi**: Oznacz kontakt jako ulubiony lub usuń oznaczenie.

## Technologie

Aplikacja została zbudowana z wykorzystaniem:

- Node.js
- Express.js - framework serwera
- MongoDB - baza danych
- Mongoose - ODM dla MongoDB
