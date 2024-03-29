<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>demo-markdown</title>
    <link rel=" stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            color: white;
            padding: 0;
            background-color: rgb(109, 42, 42);
        }
        .container {
            display: flex;
        }
        .left-sidebar {
            flex: 0 0 25%;
            background: linear-gradient(rgb(109, 0, 0) 10%, black 100%);
            color: rgb(0, 0, 0);
            padding: 1.2em;
        }
        .content {
            flex: 0 0 75%;
            padding: 20px;
        }
        .link-list {
            list-style-type: none;
        }
        .link-list li {
            margin-bottom: 10px;
        }
        .link-list li a {
            text-decoration:dashed;
            color: #912a2a;
            font-stretch: expanded;
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="left-sidebar">
            <h3>Enlaces de interes
            <ul class="link-list">
                <li><a class="external-link" href="https://markdown.es/sintaxis-markdown/"><i
                            class="fa-brands fa-markdown"></i> sintaxis markdown</a></li>
                <li><a class="youtube-video" href="https://www.youtube.com/watch?v=3GymExBkKjE&t=195s"
                        target="_blank"><img class="fa-brands fa-youtube"><i class="fa-brands fa-youtube"></i>
                        Videotutorial Git - GitHub  </a>
                </li>
            </ul></h3>
        </div>
        <div class="content">
            <h1>JaviRomano</h1>
            <p>Espacio dedicado a enumerar las distintas capacidades y conocimientos adquiridos sobre informática,
                desde el enfoque de un alumno cursando DAM actualmente.</p>
            <ul>
                <li><a href="#">Programacion</a></li>
                <li><a href="#">Bases de datos</a></li>
                <li><a href="#">Sistemas</a></li>
                <li><a href="#">Lenguaje de marcas</a></li>
                <li><a href="#">Entornos de desarrollo</a></li>
            </ul>
        </div>

    </div>

</body>

</html>
