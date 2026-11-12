# JEV Tennis Picks

Statyczny dashboard publikujący wyłącznie bieżące prognozy JEV Tennis, niezmienne identyfikatory LOCK oraz rzeczywiste settlement.

Dashboard nie zawiera kluczy API, bazy SQLite, surowych CSV ani odpowiedzi źródłowego API. Dane historyczne używane lokalnie przez model pochodzą z archiwum zgodnego ze schematem Sackmann i podlegają licencji [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Publiczny eksport zawiera wyłącznie wyniki pochodne i jest przeznaczony do zastosowania niekomercyjnego.

Strona docelowa: `https://metalurg77.github.io/jev-tennis-picks/`.

Aktualizacja odbywa się z prywatnego projektu lokalnego przez `scripts/publish_github_pages.ps1`. Repozytorium publiczne nie wykonuje zapytań do RapidAPI.
