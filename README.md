<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuidado del Medio Ambiente</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa;
            color: #00695c;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #004d40;
        }
        .botones {
            margin: 20px 0;
        }
        button {
            background-color: #004d40;
            color: white;
            border: none;
            padding: 10px 20px;
            margin: 10px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #00796b;
        }
        iframe {
            width: 80%;
            height: 400px;
            border: 2px solid #004d40;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <h1>Cuidado del Medio Ambiente</h1>
    <p>Haz clic en los botones para aprender más sobre cada tema.</p>

    <div class="botones">
        <button onclick="mostrarIframe('https://www.reforestamosmexico.org/')">Reforestación</button>
        <button onclick="mostrarIframe('https://www.gob.mx/semarnat/acciones-y-programas/limpieza-y-reciclaje')">Limpieza</button>
        <button onclick="mostrarIframe('https://www.gob.mx/semarnat/acciones-y-programas/flora-y-fauna')">Flora</button>
        <button onclick="mostrarIframe('https://www.gob.mx/semarnat/acciones-y-programas/fauna')">Fauna</button>
    </div>

    <iframe id="contenidoIframe" title="Contenido Ambiental"></iframe>

    <script>
        function mostrarIframe(url) {
            document.getElementById('contenidoIframe').src = url;
        }
    </script>

</body>
</html>

