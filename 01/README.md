> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s8e08-python-db-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#01` Python i Bazy danych: Zaawansowane

Zdefiniuj model `Note`, który reprezentuje notatkę zapisaną przez użytkownika.

Model powinien zawierać:

* `id` – klucz główny (`Integer`, automatycznie numerowany),
* `title` – tytuł notatki (`String`, wymagany),
* `body` – treść notatki (`Text`, wymagane),
* `pinned` – flaga logiczna (`Boolean`), domyślnie `False`.

Twoje zadanie:

1. Utwórz i zapisz do bazy dwie notatki.
2. Wyszukaj notatkę po tytule i wypisz jej treść.
3. Zmień status `pinned` jednej z notatek na `True` i zapisz zmiany.
4. Usuń drugą notatkę z bazy.

**Wymagania techniczne:**

* Użyj SQLAlchemy ORM.
* Zastosuj sesję (`Session`) oraz metody `.add()`, `.query()`, `.commit()`, `.delete()`.
* Nie musisz używać formularza do przesłania danych


&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-python-db-advanced)*

> :arrow_left: ~~*poprzednie zadanie*~~ | [*następne zadanie*](./../02) :arrow_right:
