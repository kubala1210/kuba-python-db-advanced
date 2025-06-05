> :white_check_mark: *Jeśli będziesz mieć problem z rozwiązaniem tego zadania, poproś o pomoc na odpowiednim kanale na Slacku, tj. `s8e08-python-db-advanced` (dotyczy [mentee](https://devmentor.pl/mentoring/)) lub na ogólnodostępnej i bezpłatnej [społeczności na Discordzie](https://devmentor.pl/discord). Pamiętaj, aby treść Twojego wpisu spełniała [odpowiednie kryteria](https://devmentor.pl/jak-prosic-o-pomoc/).*

&nbsp;

# `#03` Python i Bazy danych: Zaawansowane

Zdefiniuj dwa modele połączone relacją wiele-do-wielu:

- `Person`:
  - `id` – klucz główny (`Integer`),
  - `name` – imię osoby (`String`, wymagane).

- `Skill`:
  - `id` – klucz główny (`Integer`),
  - `name` – nazwa umiejętności (`String`, wymagane).

Utwórz tabelę pośredniczącą `person_skill`, która będzie przechowywać powiązania między osobami a umiejętnościami.

Twoje zadanie:
1. Dodaj kilka osób i kilka umiejętności.
2. Przypisz osobom wybrane umiejętności.
3. Dla jednej osoby wypisz listę jej umiejętności.
4. Dla jednej umiejętności wypisz listę osób, które ją posiadają.

**Wymagania techniczne:**
- Zastosuj `relationship()` z parametrem `secondary`.
- Wykorzystaj SQLAlchemy ORM do wykonania operacji.


&nbsp;
> :no_entry: *Jeśli nie posiadasz materiałów do tego zadania tj. **PDF, projekt + Code Review**, znajdziesz je na stronie [devmentor.pl](https://devmentor.pl/workshop-python-db-advanced)*

> :arrow_left: [*poprzednie zadanie*](./../02) | [*następne zadanie*](./../04) :arrow_right:
