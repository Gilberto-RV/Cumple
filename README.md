# Para Marco

Página estática de cumpleaños hecha con HTML y CSS. Las fotos y videos se sirven desde `imagenes/`.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub y sube el contenido de esta carpeta (incluida `imagenes/`).
2. En el repositorio, abre **Settings → Pages** y selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. En tu proveedor DNS, crea un registro **CNAME** para `mimarco` que apunte a `<tu-usuario>.github.io` (sin `https://`).
4. Cuando el DNS se haya propagado, vuelve a **Settings → Pages**, escribe `mimarco.grvpp.com` en **Custom domain** y activa **Enforce HTTPS** cuando GitHub lo permita.

El archivo `CNAME` ya declara el dominio deseado para GitHub Pages. El subdominio empezará a funcionar después de crear el registro DNS y publicar el repositorio.

La página no requiere compilación ni dependencias. Las tipografías se cargan desde Google Fonts; si no hay conexión, se muestran fuentes de respaldo del dispositivo.
