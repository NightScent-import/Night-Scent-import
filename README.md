# Night Scent Import — Catálogo de perfumes

Catálogo web de perfumes árabes, de diseñador/nicho y body splash (Ensenada, Buenos Aires).

## Contenido

- `index.html`: catálogo público (los clientes consultan por WhatsApp). Incluye "Muestra disponible" sobre el botón Consultar y el filtro "Muestras disponibles".
- `privado.html`: versión de uso interno, con contraseña.
  - Al tocar un perfume: precio en dólares, precio de compra y precio de venta recomendable (compra + $10.000, redondeado hacia arriba al próximo mil).
  - Botón **Pedido**: pegás el mensaje que mandó el cliente y devuelve los precios de venta listos para copiar.
  - Botón **Lista**: armás una lista de perfumes/decants con precios para pasar.
  - Ordenar por precio y copiar la lista de muestras por género.
  - Decants (venta): 5 ml $9.000 · 10 ml $13.000.
  - Los precios van cifrados dentro del archivo.
- `.nojekyll`: evita que GitHub Pages procese el sitio con Jekyll.

## Publicar en GitHub Pages

1. Creá un repositorio en GitHub y subí estos archivos a la rama `main`.
2. **Settings → Pages → Deploy from a branch → `main` / `/ (root)`**.
3. Quedan en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/` (público) y `.../privado.html` (con contraseña).

No subas al repositorio la carpeta `generador-privado` (tiene los precios sin cifrar).
