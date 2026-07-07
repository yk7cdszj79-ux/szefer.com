# Kancelaria Radcy Prawnego Piotr Szefer

Statyczna wizytówka przygotowana pod Cloudflare Pages.

## Cloudflare Pages - Git integration

- Framework preset: `None`
- Root directory: `outputs/kancelaria-pages` jeśli repozytorium zawiera cały folder roboczy; puste, jeśli repozytorium zaczyna się bezpośrednio od tego katalogu
- Build command: `exit 0`
- Build output directory: `.`
- Deploy command: zostaw puste

Nie używaj `npx wrangler deploy` dla Pages. To jest komenda dla Workers i spowoduje błąd typu "Missing entry-point to Worker script or to assets directory".

## Direct Upload

Wgraj cały folder `kancelaria-pages` albo plik ZIP przez panel Cloudflare Pages.

## Wrangler CLI

Jeśli wdrażasz przez Wrangler, użyj:

```bash
npx wrangler pages deploy .
```

Cloudflare Pages wymaga pliku `index.html` w katalogu głównym publikowanych plików; ten folder już go zawiera.
