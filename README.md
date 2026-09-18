# Piotr Szefer — kancelaria

Strona w języku polskim i angielskim, publikowana przez istniejący projekt Cloudflare Pages `szefer-com` z gałęzi `main` repozytorium `yk7cdszj79-ux/szefer.com`.

Repozytorium zawiera gotowe pliki statyczne; `index.html` znajduje się w jego katalogu głównym. Publikacja nie wymaga Node.js ani instalowania zależności.

## Istniejąca konfiguracja Cloudflare Pages

- Framework: None.
- Build command: puste (równoważnie `exit 0`).
- Build output: katalog główny repozytorium (`.` / puste w obecnym panelu).
- Root directory: puste.
- Production branch: `main`.
- Domeny: `szefer.com`, `www.szefer.com`.

Zmiana na `main` uruchamia automatyczne wdrożenie. Aktualizacje przygotowuj w osobnej gałęzi i scalaj po odbiorze. Nie twórz nowego projektu ani nie zmieniaj DNS dla zwykłej aktualizacji plików.

Pliki `_headers` i `_redirects` są interpretowane przez Pages. Osobne strony 404 obsługują oba języki. Adresy techniczne `pages.dev` mają `noindex`; domena docelowa pozostaje indeksowalna.
