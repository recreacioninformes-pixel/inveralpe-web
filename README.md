# Grupo InverAlpe — sitio web

Sitio estático (un solo `index.html`) listo para GitHub Pages.

## Imágenes (carpeta `img/`)
Guarda las imágenes del sitio actual con estos nombres exactos:

| Archivo en `img/` | Imagen original (grupoinveralpe.com/wp-content/uploads/...) |
|---|---|
| logo.png | 2026/01/LOGOTIPO-INVERALPE.png |
| icono.png | 2026/01/INVERALPEICO-300x300.png |
| hero.jpg | 2026/01/HomeGrupoInverAlpe.jpg |
| contacto.jpg | 2026/01/ContactoInverAlpe.jpg |
| torre-ares.jpg | 2026/07/WhatsApp-Image-2026-07-22-at-12.15.01-PM.jpeg |
| grandares.jpg | 2026/08/WhatsApp-Image-2026-08-10-at-1.41.59-PM.jpeg |
| plaza-paris.jpg | 2026/01/WhatsApp-Image-2026-01-14-at-4.21.00-PM.jpeg |

## Publicar en GitHub Pages
1. Crea un repositorio nuevo (p. ej. `inveralpe-web`) y sube `index.html` y la carpeta `img/`.
2. Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)` → Save.
3. En 1–2 minutos queda en `https://TU-USUARIO.github.io/inveralpe-web/`.

## Conectar el dominio nuevo (cuando lo compren)
1. Settings → Pages → Custom domain → escribe el dominio (p. ej. `www.inveralpe.mx`) → Save. Activa "Enforce HTTPS".
2. En el registrador, crea los DNS:
   - `CNAME` para `www` → `TU-USUARIO.github.io`
   - Registros `A` para el dominio raíz → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
