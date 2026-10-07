# liftverse.app

Página web de LiftVerse (HTML estático en `public/`), publicada como Cloudflare Worker con archivos estáticos (`wrangler.jsonc`).

- `public/index.html`: página principal.
- `public/privacidad.html` y `public/terminos.html`: copiados de `appgym/legal/` (generados por `node scripts/buildLegalPages.js`).

Cada push a `main` se publica solo.
