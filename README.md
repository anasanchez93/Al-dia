# Al día

Nutrición, finanzas de casa y vencimientos en una sola app web instalable (PWA).

- **Nutrición** abre Synergética (`/Synerg-tica/`) tal cual está publicada.
- **Finanzas** abre Perrimón (`/Perrimon/`) tal cual está publicada.
- **Vencimientos** (`vencimientos.html`) guarda los datos en Supabase, en la tabla `vencimientos`, con la misma cuenta de Synergética.

Como las tres viven en `anasanchez93.github.io`, cualquier mejora que subas a Synergética o a Perrimón aparece sola en Al día.

## Archivos

- `index.html`: la barra de secciones y las tres apps.
- `vencimientos.html`: la sección de vencimientos.
- `supabase-vencimientos.sql`: crea la tabla (una sola vez, en el SQL Editor de Supabase).
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png`: para instalarla y que abra sin conexión.
