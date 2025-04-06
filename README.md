<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TuneDrop - Популярная музыка</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #111;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    header {
      background: #1db954;
      padding: 20px;
      text-align: center;
      font-size: 2em;
    }
    .container {
      padding: 20px;
      max-width: 800px;
      margin: 0 auto;
    }
    .track {
      background: #222;
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 10px;
    }
    .track h3 {
      margin: 0 0 10px 0;
    }
    audio {
      width: 100%;
      margin-bottom: 10px;
    }
    .download-btn {
      background: #1db954;
      color: white;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 5px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #1a1a1a;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>
  <header>TuneDrop</header>
  <div class="container">
    <div class="track">
      <h3>Imagine Dragons - Believer</h3>
      <audio controls>
        <source src="tracks/believer.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
      </audio>
      <a href="tracks/believer.mp3" download class="download-btn">Скачать</a>
    </div><div class="track">
  <h3>Dua Lipa - Levitating</h3>
  <audio controls>
    <source src="tracks/levitating.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
  <a href="tracks/levitating.mp3" download class="download-btn">Скачать</a>
</div>

<!-- Добавляй больше треков по такому же шаблону -->

  </div>  <footer>
    &copy; 2025 TuneDrop. Все права защищены.
  </footer>
</body>
</html>
