# Mi Biblioteca Digital 📚

Aplicación web para docentes pensada para organizar documentos digitales (planificaciones, evaluaciones, recursos, plantillas administrativas y más) en una biblioteca visual, ordenada y fácil de usar desde el celular.

## Ver la app en vivo

Una vez publicada con GitHub Pages, va a estar disponible en:

```
https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/
```

## Características

- Pantalla de bienvenida con presentación de la app.
- Buscador y categorías (Planificación, Evaluación, Recursos, Administrativo, Comunicación, Herramientas digitales).
- Biblioteca de contenidos con tarjetas (título, descripción, categoría).
- Pantalla individual por contenido, con explicación y pasos.
- Favoritos guardados en el dispositivo (localStorage), sin necesidad de registro.
- Diseño responsive: celular, tablet y computadora.

## Cómo publicarla con GitHub Pages

1. Asegurate de que el archivo principal se llame `index.html` (en la raíz del repositorio).
2. Andá a **Settings → Pages** en este repositorio.
3. En **Source**, elegí la rama `main` y la carpeta `/ (root)`.
4. Guardá los cambios. GitHub va a generar la URL pública en uno o dos minutos.

## Tecnología

Un único archivo HTML con CSS y JavaScript (sin frameworks ni backend), por lo que no necesita instalación ni build: se abre directo en cualquier navegador.

## Personalización

- **Contenidos**: se editan en el arreglo `CONTENT` dentro del `<script>` de `index.html`.
- **Categorías**: se editan en el arreglo `CATEGORIES`.
- **Colores**: variables CSS al inicio del archivo (`:root`), en la sección `<style>`.
