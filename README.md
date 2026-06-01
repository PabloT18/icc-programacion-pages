# ICC Programación - Prácticas y Evaluaciones

Este repositorio contiene páginas estáticas (HTML, CSS y JS) para mostrar prácticas y evaluaciones con sus indicaciones en formato web.

La idea principal es publicar el contenido en GitHub Pages para que se pueda consultar fácilmente desde una sola página de entrada.

## Objetivo del repositorio

- Publicar prácticas y evaluaciones en una interfaz web clara.
- Centralizar indicaciones académicas en páginas accesibles por enlace.
- Mantener una estructura simple para actualizar contenidos por unidad.

## Publicación en GitHub Pages

Este proyecto está preparado para servir contenido estático.
La página de inicio `index.html` redirige a:

- `unidad3/01-exa-interciclo-3.3.html`

Si GitHub Pages está habilitado en el repositorio, esa será la página que verá el usuario al ingresar al sitio.

## Estructura

- `index.html`: punto de entrada (redirige a la página activa).
- `unidad3/`: páginas de prácticas/evaluaciones por unidad.
- `css/`: estilos globales y de componentes.
- `js/`: scripts de comportamiento y protección visual.
- `assets/`: imágenes y recursos estáticos.

## Ejecución local

Puedes abrir el proyecto de forma directa:

1. Abre `index.html` en el navegador.
2. O usa Live Server en VS Code para visualizar cambios en tiempo real.

## Cómo agregar una nueva práctica o evaluación

1. Crea una nueva página HTML dentro de la carpeta de la unidad correspondiente.
2. Reutiliza estilos de `css/` y scripts de `js/` según sea necesario.
3. Actualiza `index.html` para redirigir a la nueva página principal que quieres mostrar.
4. Haz commit y push para publicar los cambios en GitHub Pages.

## Autor

- Ing. Pablo Torres
