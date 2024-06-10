# ¡Hola! Soy Esau 👋

Bienvenido a mi perfil de GitHub. Soy un estudiante del CETis 17 con un poco de conocimiento sobre lenguajes de programación. En este README, te mostraré cómo crear una página web sencilla utilizando HTML y CSS.

## Cómo Crear una Página Web Sencilla

A continuación, se muestra un ejemplo de código HTML que explica cómo construir una página web básica. Este ejemplo incluye un encabezado, secciones de contenido y un pie de página, todo con un estilo simple proporcionado por CSS.

### Código HTML

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página Web Sencilla</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
        }
        section {
            margin: 2em;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a Mi Página Web Sencilla</h1>
        <p>Creada por Esau</p>
    </header>

    <section>
        <h2>Sobre Esta Página</h2>
        <p>Esta es una página web básica creada para demostrar cómo se puede hacer una página web sencilla con HTML y CSS.</p>
    </section>

    <section>
        <h2>Contenido</h2>
        <p>Aquí puedes agregar cualquier contenido que desees mostrar en tu página web.</p>
    </section>

    <footer>
        <p>&copy; 2024 Esau. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
