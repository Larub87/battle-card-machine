# Inteligencia competitiva · CDN

Piezas de inteligencia competitiva del sector CDN, con la marca Purpose & Prompt.
Sitio estático: cada archivo es un HTML autónomo, sin build ni dependencias que instalar.

## Archivos
- `index.html` — Página índice (hub) que enlaza las cuatro piezas
- `competitive-map-cdn.html` — Sector map (EN)
- `mapa-competitivo-cdn.html` — Mapa de sector (ES)
- `battle-cards-transparent-edge-en.html` — Battle cards (EN)
- `battle-cards-transparent-edge.html` — Battle cards (ES)

## Publicación (GitHub Pages)
Son archivos estáticos: GitHub Pages los sirve tal cual.
- La navegación interna usa `location.hash`, así que funciona sin configurar rutas ni reglas 404.
- Las tipografías (Playfair Display, Be Vietnam Pro, Lato) se cargan desde Google Fonts por HTTPS.
- `.nojekyll` evita el procesado de Jekyll (sitio estático puro).

## Mantenimiento
El contenido va embebido en cada HTML. Para actualizar una pieza, se regenera el archivo
y se vuelve a commitear; el enlace publicado no cambia.
