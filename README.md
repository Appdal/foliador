# Nara Foliador

Página web para foliar y sellar PDF (valorizaciones, expedientes) y para unir, extraer, dividir y girar hojas. Todo se procesa en el navegador; los archivos no se suben a ningún servidor.

## Publicar en GitHub Pages
1. Sube estos archivos a la raíz del repositorio.
2. En GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En 1–2 minutos queda en `https://<usuario>.github.io/<repositorio>/`.

## Cobrar más adelante
Hoy es gratis e ilimitado. En `index.html` busca `const PLAN=`:
- `cobro:true` activa el control y `hojasGratis` fija el límite gratis por PDF.
- `licenciaValida()` debe consultar tu pasarela o servidor (Mercado Pago, Culqi, etc.).

## Licencias de terceros
Ver `THIRD_PARTY_NOTICES.md`.
