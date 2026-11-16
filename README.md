# Reporte · Tu ecosistema digital (octubre 2026)

Sitio estático de una sola página. Los datos de octubre van dentro de `index.html`, así que no necesita API, variables de entorno ni build.

## Publicar en Vercel
1. Crea un repositorio nuevo en GitHub (privado) y sube estos archivos.
2. En Vercel: **Add New → Project**, importa el repositorio.
3. Framework Preset: **Other**. Sin Build Command ni Output Directory. **Deploy**.

La página no se indexa en buscadores (`robots.txt` y header `X-Robots-Tag`).
