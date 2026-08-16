# Portafolio — Carlos Jaime

Sitio estático (HTML/CSS/JS puro) listo para publicarse en GitHub Pages.

## Estructura

```
index.html
assets/
  css/style.css
  js/main.js
  img/   ← capturas de pantalla de los proyectos
```

## Publicar en GitHub Pages

1. Entra a https://github.com/new y crea un repositorio público llamado **exactamente**:
   `cjaime-dev.github.io`
   (ese nombre exacto hace que el sitio quede en la raíz de tu dominio de GitHub Pages).
2. En tu computador, dentro de esta carpeta, ejecuta:
   ```bash
   git init
   git add .
   git commit -m "Primera versión del portafolio"
   git branch -M main
   git remote add origin https://github.com/cjaime-dev/cjaime-dev.github.io.git
   git push -u origin main
   ```
3. En GitHub, entra al repo → **Settings → Pages** → en "Build and deployment" selecciona **Deploy from a branch**, rama `main`, carpeta `/ (root)`. Guarda.
4. Espera 1–2 minutos y tu portafolio quedará publicado en:
   **https://cjaime-dev.github.io**

## Agregar un nuevo proyecto más adelante

Duplica un bloque `<article class="project">...</article>` dentro de `index.html`,
cambia el texto, las etiquetas de tecnología y las dos imágenes (`assets/img/`).
No hace falta tocar el CSS: los estilos ya están listos para cualquier cantidad de proyectos.

## Nota sobre las capturas

Las imágenes actuales muestran datos reales de los sistemas (nombres, NIT, montos).
Si quieres reemplazarlas por versiones con datos ficticios o difuminados antes de
que el sitio sea público, solo debes sustituir los archivos en `assets/img/`
manteniendo el mismo nombre de archivo.
