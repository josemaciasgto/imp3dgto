# imp3dgto
Herramientas de trabajo de impresión 3D — Impresiones 3D GTO.

## sitio/
Sitio web de catálogos para clientes: página de inicio + catálogos (Dragon Ball, Marvel, DC, Batman, Caricaturas Vintage).
Se publica automáticamente en Cloudflare (Workers con archivos estáticos, ver `wrangler.jsonc`) en cada push a `main`.

## codigos.tsv
Tabla de códigos de modelo (DB-001, MV-001…) → catálogo, sección, nombre y archivos en el Drive de Geek Madness.
