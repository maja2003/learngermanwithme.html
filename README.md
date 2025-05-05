<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
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

    img {
      margin-top: 30px;
      width: 200px;
      height: auto;
      border-radius: 10px;
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

    .section {
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <!-- Hauptüberschrift -->
  <h1>LearnGermanwithMaja</h1>

  <!-- Bild von dir -->
  <img src="c:\Users\majaf\OneDrive\Desktop\Italki\foto maja.jpg" alt="foto maja">

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

  <!-- Podcast-Buttons -->
  <div>
    <button>Niveau A1</button>
    <button>Niveau A2</button>
    <button>Niveau B1</button>
    <button>Niveau B2</button>
    <button>Niveau C1</button>
    <button>Niveau C2</button>
  </div>

  <!-- Hier kannst du Podcast-Links oder -Inhalte einfügen -->

  <!-- Bücher Abschnitt -->
  <h2 class="section">Bücher</h2>

  <!-- Buch-Buttons -->
  <div>
    <button>Niveau A1</button>
    <button>Niveau A2</button>
    <button>Niveau B1</button>
    <button>Niveau B2</button>
    <button>Niveau C1</button>
    <button>Niveau C2</button>
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
