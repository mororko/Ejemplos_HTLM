# Guía de las principales etiquetas de HTML

## Introducción
HTML (HyperText Markup Language) utiliza **etiquetas** para estructurar y organizar el contenido de las páginas web. A continuación, se presenta una lista de las etiquetas más importantes, organizadas por su función, y cuándo se utilizan.

---

## **Estructura básica**
1. **`<html>`**  
   - Contiene todo el código HTML de la página.  
   ```html
   <html>...</html>
   ```

2. **`<head>`**  
   - Define metadatos de la página como el título, enlaces a hojas de estilo, scripts, y configuraciones.  
   ```html
   <head>
       <title>Mi Página</title>
   </head>
   ```

3. **`<body>`**  
   - Contiene el contenido visible de la página, como texto, imágenes, y videos.  
   ```html
   <body>
       <h1>Bienvenido</h1>
       <p>Este es un ejemplo.</p>
   </body>
   ```

---

## **Encabezados y texto**
4. **`<h1>` a `<h6>`**  
   - Representan encabezados, desde el más importante (`<h1>`) al menos importante (`<h6>`).  
   ```html
   <h1>Título principal</h1>
   <h2>Subtítulo</h2>
   ```

5. **`<p>`**  
   - Define un párrafo.  
   ```html
   <p>Este es un párrafo de texto.</p>
   ```

6. **`<br>`**  
   - Inserta un salto de línea.  
   ```html
   Primera línea<br>Segunda línea
   ```

7. **`<strong>` y `<b>`**  
   - Resaltan texto en negrita. `<strong>` tiene un énfasis semántico (importancia), mientras que `<b>` es puramente visual.  
   ```html
   <strong>Importante</strong>
   <b>Texto en negrita</b>
   ```

8. **`<em>` y `<i>`**  
   - Resaltan texto en cursiva. `<em>` denota énfasis, mientras que `<i>` es solo visual.  
   ```html
   <em>Texto enfatizado</em>
   <i>Texto en cursiva</i>
   ```

---

## **Enlaces e imágenes**
9. **`<a>`**  
   - Define un hipervínculo.  
   ```html
   <a href="https://ejemplo.com">Visita Ejemplo</a>
   ```

10. **`<img>`**  
    - Inserta una imagen. Requiere el atributo `src` para la URL de la imagen y opcionalmente `alt` para texto alternativo.  
    ```html
    <img src="imagen.jpg" alt="Descripción de la imagen">
    ```

---

## **Listas**
11. **`<ul>` y `<ol>`**  
    - Define listas no ordenadas (`<ul>`) y listas ordenadas (`<ol>`).  
    ```html
    <ul>
        <li>Elemento 1</li>
        <li>Elemento 2</li>
    </ul>
    <ol>
        <li>Primero</li>
        <li>Segundo</li>
    </ol>
    ```

12. **`<li>`**  
    - Define un elemento dentro de una lista.  

---

## **Tablas**
13. **`<table>`**  
    - Crea una tabla.  
    ```html
    <table>
        <tr>
            <th>Columna 1</th>
            <th>Columna 2</th>
        </tr>
        <tr>
            <td>Dato 1</td>
            <td>Dato 2</td>
        </tr>
    </table>
    ```

14. **`<tr>`, `<th>`, `<td>`**  
    - `<tr>`: Define una fila de tabla.  
    - `<th>`: Define una celda de encabezado.  
    - `<td>`: Define una celda de datos.  

---

## **Formularios**
15. **`<form>`**  
    - Crea un formulario para enviar datos.  
    ```html
    <form action="/enviar" method="post">
        <input type="text" name="nombre">
        <button type="submit">Enviar</button>
    </form>
    ```

16. **`<input>`**  
    - Crea campos de entrada, como texto, contraseñas, etc.  
    ```html
    <input type="text" placeholder="Escribe aquí">
    ```

17. **`<button>`**  
    - Crea un botón interactivo.  
    ```html
    <button>Haz clic</button>
    ```

---

## **Elementos multimedia**
18. **`<audio>`** y **`<video>`**  
    - Insertan contenido de audio y video.  
    ```html
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
    </audio>
    <video controls>
        <source src="video.mp4" type="video/mp4">
    </video>
    ```

19. **`<iframe>`**  
    - Inserta contenido externo como un mapa o un video.  
    ```html
    <iframe src="https://www.youtube.com/embed/ID_DEL_VIDEO"></iframe>
    ```

---

## **Elementos semánticos**
20. **`<header>`, `<footer>`, `<main>`**  
    - Estructuran la página en secciones semánticas como encabezado, pie de página y contenido principal.  
    ```html
    <header>Encabezado</header>
    <main>Contenido principal</main>
    <footer>Pie de página</footer>
    ```

21. **`<article>`, `<section>`, `<aside>`**  
    - `<article>`: Para contenido independiente (artículos).  
    - `<section>`: Para agrupar contenido relacionado.  
    - `<aside>`: Para contenido relacionado como barras laterales.  
    ```html
    <article>Artículo</article>
    <section>Sección</section>
    <aside>Barra lateral</aside>
    ```

22. **`<nav>`**  
    - Define un menú de navegación.  
    ```html
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#contacto">Contacto</a>
    </nav>
    ```

---

## **Etiquetas misceláneas**
23. **`<div>`**  
    - Agrupa elementos, principalmente para aplicar estilos o scripts.  
    ```html
    <div class="contenedor">Contenido</div>
    ```

24. **`<span>`**  
    - Agrupa texto o elementos en línea para estilos o scripts específicos.  
    ```html
    <span style="color: red;">Texto rojo</span>
    ```

---

¡Estas etiquetas son fundamentales para construir páginas web modernas y efectivas! Cada una tiene atributos que permiten personalizar su funcionalidad y apariencia.
