# Musicalismo

Sitio web de Musicalismo: apertura con el logo y efecto de televisión antigua, y video del backstage con karaoke.

## Estructura

- `index.html`: la página completa (estilos, tipografía y código incluidos).
- `media/intro-loop.mp4`: loop de la apertura.
- `media/backstage.mp4`: montaje del backstage que se ve al entrar.
- `media/*.jpg`: imágenes de respaldo mientras cargan los videos.

## Publicar con GitHub Pages

1. Sube todo el contenido de esta carpeta a la raíz de un repositorio.
2. En el repositorio, ve a Settings → Pages.
3. En "Source" elige la rama `main` y la carpeta `/ (root)`, y guarda.
4. En un par de minutos la página queda en `https://<tu-usuario>.github.io/<repositorio>/`.

## Editar

Al inicio del bloque `<script>` final de `index.html` hay una sección marcada **Edita aquí**:

- `LETRAS`: líneas del karaoke. Para usar letras reales de canciones se necesita autorización de los titulares de derechos.
- `AUDIO`: ruta a un archivo de audio propio (por ejemplo `media/tema.mp3`) que suena al entrar.

La lista de canciones del menú está en el HTML, dentro de `<ol class="lista">`.

## Créditos tipográficos

TeX Gyre Adventor, bajo GUST Font License (uso y distribución libres).
