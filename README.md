# invito_cilla

Invito one-page (mobile-first) — festa di laurea.

- `invito_laurea/index.html` — pagina unica (HTML + CSS + JS inline), scroll-snap verticale
- `invito_laurea/assets/invito.mp4` — video introduttivo (H.264 + audio)
- `invito_laurea/assets/poster.jpg` — fotogramma poster del video
- `invito_laurea/assets/laurel-divider.svg` — divisore ad alloro dorato
- `index.html` — placeholder per la home del sito (root)

## Anteprima locale

```bash
python3 -m http.server 8000
# invito: http://localhost:8000/invito_laurea/
# home:   http://localhost:8000/
```

## Deploy su GitHub Pages

1. **Settings → Pages**
2. **Source:** `Deploy from a branch`
3. **Branch:** `main` / `/ (root)` → Save

L'invito sarà disponibile su:

- repo Pages: `https://<username>.github.io/invito_cilla/invito_laurea/`
- dominio custom: `https://<tuo-dominio>/invito_laurea/`

La root (`/`) resta libera per la home del sito.

> Nota: GitHub Pages su repository **privati** richiede un piano GitHub Pro/Team.
> Con un account Free, per pubblicare le Pages il repo va reso pubblico.
