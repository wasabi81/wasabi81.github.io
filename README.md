<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn GIF Website</title>
    <style>
        /* Zorgt dat de pagina de volledige hoogte gebruikt */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            display: flex;
            justify-content: center; /* Horizontaal centreren */
            align-items: center;     /* Verticaal centreren */
            background-color: #000000; /* Optioneel: zwarte achtergrond */
        }

        .gif-container {
            width: 90%;  /* Neemt 90% van de breedte in op kleine schermen */
            max-width: 800px; /* Wordt nooit breder dan 800px op laptops */
        }

        img {
            width: 100%;    /* Zorgt dat de GIF schaalt naar de container */
            height: auto;   /* Behoudt de juiste verhoudingen */
            display: block;
        }
    </style>
</head>
<body>

    <div class="gif-container">
        <img src="cv.gif" alt="Gecentreerde GIF">
    </div>

</body>
</html>
