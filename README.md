<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LearnGermanwithMaja</title>
  <style>
    body {
      background-color: white;
      font-family: Arial, sans-serif;
      color: black;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    h1 {
      font-size: 48px;
      text-decoration: underline;
      margin-top: 40px;
    }

    /* Überschrift in Blau entfernt, kein <h2> in Blau mehr */

    img {
      margin-top: 30px;
      width: 200px;
      height: auto;
      border-radius: 10px;
    }

    /* Neue Sektion für den Support-Text */
    .support-text {
      margin-top: 20px;
      font-size: 16px;
      color: black;
    }

    .support-link {
      color: blue;
      text-decoration: underline;
    }

    h2 {
      font-size: 32px;
      text-decoration: underline;
      margin-top: 60px;
    }

    p {
      max-width: 800px;
      margin: 40px auto;
      line-height: 1.6;
      font-size: 18px;
    }

    button {
      background-color: #f0f0f0;
      border: 1px solid #ccc;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      margin: 5px;
    }

    /* Hintergrundfarben für die Level-Buttons */
    .a1, .a2 {
      background-color: #ADD8E6; /* Hellblau */
    }
    .b1, .b2 {
      background-color: #6495ED; /* Mittelblau */
    }
    .c1, .c2 {
      background-color: #00008B; /* Dunkelblau */
      color: white; /* Textfarbe auf dunkelblau sichtbar machen */
    }

    .section {
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <!-- Hauptüberschrift -->
  <h1>LearnGermanwithMaja</h1>

  <!-- Unterstützungstext -->
  <div class="support-text">
    <p>you can support the language learning project here:</p>
    <a class="support-link" href="https://ko-fi.com/germanwithmaja" target="_blank">https://ko-fi.com/germanwithmaja</a>
  </div>

  <!-- Bild von dir -->
  <img src="foto%20maja.jpg" alt="Foto Maja" />

  <!-- Vorstellung -->
  <h2 class="section">Vorstellung</h2>

  <p id="intro-text">
    Hallo! Ich bin Maja, ich unterrichte seit zirka fünf Jahren Deutsch an Interessierte aus der ganzen Welt.
    Ich biete Deutschkurse für alle Niveaustufen an und ich liebe es neue Menschen kennenzulernen und ihnen dabei zu helfen, ihre Ziele zu erreichen!
    Auf meiner Webseite findest du meine Kurse und auch Materialien, die dir helfen können, dein Deutsch zu verbessern.
  </p>

  <!-- Übersetzung Button -->
  <button onclick="translateText()">Übersetzung / Translation</button>

  <!-- Podcasts Abschnitt -->
  <h2 class="section">Podcasts</h2>

  <!-- Podcast-Buttons mit Hintergrundfarben -->
  <div>
    <button class="a1">Niveau A1</button>
    <button class="a2">Niveau A2</button>
    <button class="b1">Niveau B1</button>
    <button class="b2">Niveau B2</button>
    <button class="c1">Niveau C1</button>
    <button class="c2">Niveau C2</button>
  </div>

  <!-- Hier kannst du Podcast-Links oder -Inhalte einfügen -->

  <!-- Bücher Abschnitt -->
  <h2 class="section">Bücher</h2>

  <!-- Buch-Buttons mit Hintergrundfarben -->
  <div>
    <button class="a1">Niveau A1</button>
    <button class="a2">Niveau A2</button>
    <button class="b1">Niveau B1</button>
    <button class="b2">Niveau B2</button>
    <button class="c1">Niveau C1</button>
    <button class="c2">Niveau C2</button>
  </div>

  <!-- Hier kannst du Buchlinks oder -Dateien einfügen -->

  <script>
    function translateText() {
      const text = document.getElementById("intro-text");
      if (text.innerText.startsWith("Hallo!")) {
        text.innerText = "Hello! I am Maja, and I’ve been teaching German to learners from all around the world for about five years. I offer German courses for all levels and love meeting new people and helping them reach their goals! On my website, you’ll find my courses and materials that can help you improve your German.";
      } else {
        text.innerText = "Hallo! Ich bin Maja, ich unterrichte seit zirka fünf Jahren Deutsch an Interessierte aus der ganzen Welt. Ich biete Deutschkurse für alle Niveaustufen an und ich liebe es neue Menschen kennenzulernen und ihnen dabei zu helfen, ihre Ziele zu erreichen! Auf meiner Webseite findest du meine Kurse und auch Materialien, die dir helfen können, dein Deutsch zu verbessern.";
      }
    }
  </script>

</body>
</html>
