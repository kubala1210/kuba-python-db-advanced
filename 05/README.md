> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s8e08-python-db-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#05` Python i Bazy danych: Zaawansowane

Zdefiniuj model `Item`, który reprezentuje element listy rzeczy.

Model powinien zawierać:
- `id` – klucz główny (`Integer`),
- `name` – nazwa przedmiotu (`String`, wymagane),
- `priority` – liczba całkowita oznaczająca priorytet (`Integer`), im mniejsza, tym wyższy priorytet.

Twoje zadanie:
1. Dodaj co najmniej 20 przykładowych elementów o różnych nazwach i priorytetach.
2. Posortuj elementy rosnąco po priorytecie.
3. Zaimplementuj paginację: wypisz tylko elementy od 11 do 15 miejsca (strona 3 przy 5 elementach na stronę).

**Wymagania techniczne:**
- Skorzystaj z metod `.order_by()`, `.limit()`, `.offset()`.
- Wykonaj zapytania przy użyciu SQLAlchemy ORM.


&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-python-db-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../04) | ~~*następne zadanie*~~ :arrow_right:
