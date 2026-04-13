<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mijn GitHub Website</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .container {
            width: 90%; /* De container vult 90% van het scherm */
            max-width: 1000px; /* Maar wordt nooit breder dan 1000px */
        }

        img {
            max-width: 100%; /* Zorgt dat de afbeelding nooit breder is dan het scherm */
            height: auto;    /* Behouwt de juiste verhoudingen */
            display: block;
            border-radius: 8px; /* Optioneel: een mooi rond hoekje */
            box-shadow: 0 4px 15px rgba(0,0,0,0.1); /* Optioneel: een lichte schaduw */
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="jouw-afbeelding.jpg" alt="Beschrijving van de afbeelding">
    </div>

</body>
</html>
