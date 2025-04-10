# music-app-homepage
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Music Vibes</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(to bottom right, #1e3a8a, #6b21a8);
      color: white;
      padding: 20px;
    }
    h1 {
      text-align: center;
      font-size: 3em;
      margin-bottom: 40px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      overflow: hidden;
      box-shadow: 0 4px 20px rgba(0,0,0,0.2);
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card-content {
      padding: 15px;
    }
    .card-title {
      font-size: 1.25em;
      margin: 0 0 10px 0;
    }
    .card-artist {
      font-size: 0.9em;
      color: #cbd5e1;
      margin-bottom: 15px;
    }
    .play-button {
      background: none;
      border: 2px solid white;
      color: white;
      padding: 8px 16px;
      border-radius: 25px;
      cursor: pointer;
      font-weight: bold;
    }
    .play-button:hover {
      background: white;
      color: #1e3a8a;
    }
  </style>
</head>
<body>
  <h1>🎵 Music Vibes</h1>
  <div class="grid">
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="Midnight Dreams" />
      <div class="card-content">
        <div class="card-title">Midnight Dreams</div>
        <div class="card-artist">Luna Wave</div>
        <button class="play-button">▶ Play</button>
      </div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="Sunset Boulevard" />
      <div class="card-content">
        <div class="card-title">Sunset Boulevard</div>
        <div class="card-artist">Neon Nights</div>
        <button class="play-button">▶ Play</button>
      </div>
    </div>
    <div class="card">
      <img src="https://via.placeholder.com/300x200" alt="Ocean Eyes" />
      <div class="card-content">
        <div class="card-title">Ocean Eyes</div>
        <div class="card-artist">Blue Horizon</div>
        <button class="play-button">▶ Play</button>
      </div>
    </div>
  </div>
</body>
</html>
