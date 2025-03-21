<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galeria de Imagens</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
        }
        .gallery img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <h1>Galeria de Imagens</h1>
    <div class="gallery">
        <img src="/mnt/data/Screenshot_20250321-010103~2.png" alt="Imagem 1">
        <img src="/mnt/data/Screenshot_20250321-010408~2.png" alt="Imagem 2">
        <img src="/mnt/data/Screenshot_20250321-010422~2.png" alt="Imagem 3">
        <img src="/mnt/data/Screenshot_20250321-010351~2.png" alt="Imagem 4">
        <img src="/mnt/data/Screenshot_20250321-010401~2.png" alt="Imagem 5">
        <img src="/mnt/data/Screenshot_20250321-010322~2.png" alt="Imagem 6">
        <img src="/mnt/data/Screenshot_20250321-010341~2.png" alt="Imagem 7">
        <img src="https://placekitten.com/300/200" alt="Gato">
    </div>
</body>
</html>
