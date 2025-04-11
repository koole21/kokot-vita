<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Postavy z filmu Auta</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background-color: #e74c3c;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        .container {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
        }

        .character {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            margin: 10px;
            width: 250px;
            text-align: center;
            padding: 15px;
        }

        .character img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .character h3 {
            color: #e74c3c;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Postavy z filmu Auta</h1>
        <p>Seznam hlavních postav z filmu Auta</p>
    </header>

    <div class="container">
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Lightning_McQueen.png" alt="Lightning McQueen">
            <h3>Lightning McQueen</h3>
            <p>Rychlý závodník a hlavní hrdina filmů Auta.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/1/1b/Lightning_McQueen.png" target="_blank">Zobrazit obrázek</a>
        </div>
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/72/Mater.png" alt="Mater">
            <h3>Mater</h3>
            <p>Nejlepší přítel Lightninga, který je roztomilý a trochu klidnější.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/7/72/Mater.png" target="_blank">Zobrazit obrázek</a>
        </div>
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/7d/Doc_Hudson.png" alt="Doc Hudson">
            <h3>Doc Hudson</h3>
            <p>Moudrý a zkušený závodník, který má velký vliv na McQueena.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/7/7d/Doc_Hudson.png" target="_blank">Zobrazit obrázek</a>
        </div>
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/Sally_Carrera.png" alt="Sally Carrera">
            <h3>Sally Carrera</h3>
            <p>Stylová Porsche, která se stane McQueenovou láskou.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/0/01/Sally_Carrera.png" target="_blank">Zobrazit obrázek</a>
        </div>
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/f/fd/Chick_Hicks.png" alt="Chick Hicks">
            <h3>Chick Hicks</h3>
            <p>Závodník, který se snaží porazit McQueena za každou cenu.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/f/fd/Chick_Hicks.png" target="_blank">Zobrazit obrázek</a>
        </div>
        <div class="character">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/aa/Fillmore_Cars.png" alt="Fillmore">
            <h3>Fillmore</h3>
            <p>Vysoce ekologický mikrobus, který se drží filozofie míru a lásky.</p>
            <a href="https://upload.wikimedia.org/wikipedia/commons/a/aa/Fillmore_Cars.png" target="_blank">Zobrazit obrázek</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Postavy z filmu Auta</p>
    </footer>
</body>
</html>
