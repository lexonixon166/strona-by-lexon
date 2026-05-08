<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Liga Piłkarska</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>⚽ Liga Piłkarska</h1>
    <p>Oficjalna strona ligi</p>
</header>

<nav>
    <button onclick="show('terminarz')">Terminarz</button>
    <button onclick="show('wyniki')">Wyniki</button>
    <button onclick="show('aktualnosci')">Aktualności</button>
    <button onclick="show('wykluczenia')">Wykluczenia</button>
</nav>

<div class="container">

    <div id="terminarz" class="section active">
        <h2>📅 Terminarz</h2>
        <ul>
            <li>FC Warszawa vs FC Kraków</li>
            <li>FC Gdańsk vs FC Wrocław</li>
            <li>FC Poznań vs FC Łódź</li>
        </ul>
    </div>

    <div id="wyniki" class="section">
        <h2>🏆 Wyniki</h2>
        <ul>
            <li>FC Warszawa 3:1 FC Kraków</li>
            <li>FC Gdańsk 0:0 FC Wrocław</li>
        </ul>
    </div>

    <div id="aktualnosci" class="section">
        <h2>📰 Aktualności</h2>
        <ul>
            <li>Start nowego sezonu ligi!</li>
            <li>Nowy transfer w FC Warszawa</li>
            <li>Zmiany w VAR</li>
        </ul>
    </div>

    <div id="wykluczenia" class="section">
        <h2>🚫 Wykluczenia</h2>
        <ul>
            <li>Jan Kowalski – 2 mecze (czerwona kartka)</li>
            <li>FC Łódź – ostrzeżenie</li>
        </ul>
    </div>

</div>

<script src="script.js"></script>
</body>
</html>
