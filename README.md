<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plataforma de Contenido Gratuito</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Plataforma de Contenido Gratuito</h1>
    <form id="upload-form" enctype="multipart/form-data">
        <label for="file">Sube tu archivo:</label>
        <input type="file" id="file" name="file" required>
        <button type="submit">Subir</button>
    </form>
    <div id="content-list"></div>
    <script src="script.js"></script>
</body>
</html>
