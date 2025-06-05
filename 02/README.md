> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s8e08-python-db-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#02` Python i Bazy danych: Zaawansowane

Zdefiniuj dwa modele:

- `Author`:
  - `id` – klucz główny (`Integer`),
  - `name` – imię i nazwisko (`String`, wymagane).

- `Book`:
  - `id` – klucz główny (`Integer`),
  - `title` – tytuł książki (`String`, wymagany),
  - `author_id` – klucz obcy do tabeli `Author`.

Ustal relację: jeden autor może mieć wiele książek.

Twoje zadanie:
1. Dodaj dwóch autorów i kilka książek przypisanych do każdego.
2. Pobierz i wypisz wszystkie książki konkretnego autora (np. „Jan Nowak”).
3. Pobierz listę autorów, którzy mają więcej niż jedną książkę.

**Wymagania techniczne:**
- Skorzystaj z relacji `relationship()` i `ForeignKey`.
- Użyj SQLAlchemy ORM i sesji do wykonania operacji.


&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-python-db-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../01) | [*następne zadanie*](./../03) :arrow_right:
