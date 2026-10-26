# okazjauk-dot.github.io

Publiczne strony informacyjne aplikacji korzystających z Allegro REST API (wymóg Allegro: adres w nagłówku
`User-Agent` i w rejestracji aplikacji musi prowadzić do działającej strony z nazwą właściciela, celem aplikacji
i kanałem kontaktu).

| Strona | Aplikacja |
|---|---|
| `/` | lista aplikacji |
| `/mpagent/` | **Zarządzanie Allegro** (kod projektu `mpagent`) – `User-Agent: Zarządzanie-Allegro/0.1.0 (+https://okazjauk-dot.github.io/mpagent/)` |

Statyczny HTML bez kroku budowania – publikowany przez GitHub Pages z gałęzi `main`. Przy podniesieniu wersji
aplikacji zaktualizować numer wersji na stronie i w `MPAGENT_USER_AGENT`.
