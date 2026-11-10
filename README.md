# Café Nube — sitio web responsivo

## Objetivo
Desarrollar la presencia web de ejemplo de una cafetería local mediante HTML5 semántico y CSS moderno. El sitio presenta información general, productos y un formulario de contacto demostrativo.

## Tecnologías
- HTML5
- CSS3 (Flexbox y CSS Grid)
- Media query para pantallas de hasta 700 px
- Git y GitHub Pages para publicación

## Estructura
- `index.html`: contenido y estructura semántica.
- `styles.css`: presentación visual y adaptación responsiva.

## Ejecución local
Descarga o clona el repositorio y abre `index.html` en un navegador. Para editar, abre la carpeta en Visual Studio Code.

## Capturas
Agregar aquí capturas reales de:
1. Vista de escritorio.
2. Vista móvil (ancho aproximado de 390 px).
3. Código en el editor.
4. Resultados de los validadores W3C.

## Validación
Validar `index.html` en https://validator.w3.org/ y `styles.css` en https://jigsaw.w3.org/css-validator/.
Registrar la fecha, el resultado y corregir los errores que reporten las herramientas. No declarar validación aprobada sin ejecutar los validadores.

## Publicación con GitHub Pages
1. Crear un repositorio público llamado `cafe-nube`.
2. Subir `index.html`, `styles.css` y este README a la raíz.
3. En GitHub, abrir **Settings > Pages**.
4. En **Build and deployment**, elegir **Deploy from a branch**.
5. Seleccionar la rama `main` y la carpeta `/ (root)`, y guardar.
6. Esperar a que GitHub Pages publique el sitio. Copiar la URL pública generada y agregarla al reporte.

## Limitaciones conocidas
El formulario está maquetado para demostrar controles accesibles, pero `action="#"` no envía ni almacena mensajes. Para recibirlos se necesita un backend o un servicio de formularios.
