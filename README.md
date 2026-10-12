# Mi semana en horas

Juego móvil del **Índice de Predictibilidad Urbana (IPU)** de Arcoíris ONG.
La persona cuenta su semana (agua, luz, movilidad, filas), ve su índice, elige medidas en tres escalones
(cotidiano, estructural, reglas) y arma un pliego de tres peticiones.

## Archivos
- `index.html`: el juego completo (una sola página, sin dependencias salvo Google Fonts).
- `og.png`: imagen para la vista previa en WhatsApp y redes.
- `favicon.png`, `apple-touch-icon.png`, `icon-512.png`: iconos.

## Configuración pendiente
- Dirección publicada: https://arcoirisrd.github.io/mi-semana-en-horas/ (si cambia, actualizar `og:image` en `index.html`).
- Para guardar respuestas, poner en `LAYER_URL` (al principio del script) la URL de la capa del formulario IPU v3, terminada en `/FeatureServer/0`. La capa debe ser pública y permitir solo añadir.

## Publicación
GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
