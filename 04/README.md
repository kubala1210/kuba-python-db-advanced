> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s8e08-python-db-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#04` Python i Bazy danych: Zaawansowane

Zdefiniuj model `Measurement`, który przechowuje dane pomiarowe.

Model powinien zawierać:
- `id` – klucz główny (`Integer`),
- `device_name` – nazwa urządzenia (`String`, wymagane),
- `value` – wartość pomiaru (`Float`, wymagane),
- `timestamp` – data i czas pomiaru (`DateTime`, wymagane).

Twoje zadanie:
1. Dodaj przykładowe dane dla kilku urządzeń (każde z wieloma pomiarami).
2. Oblicz i wypisz:
   - liczbę pomiarów dla każdego urządzenia,
   - średnią wartość pomiaru dla każdego urządzenia.

**Wymagania techniczne:**
- Skorzystaj z `func.count()` i `func.avg()` oraz `group_by()`.
- Użyj SQLAlchemy ORM i sesji do zapytań.

&nbsp;

> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-python-db-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../03) | [*następne zadanie*](./../05) :arrow_right:
