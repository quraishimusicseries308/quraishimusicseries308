
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Quraishi Music Series</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background: linear-gradient(to right, #1f1c2c, #928dab);
      color: #fff;
      padding: 20px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }
    .logo {
      max-width: 300px;
      margin: 0 auto 20px;
      animation: float 3s ease-in-out infinite;
    }
    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }
    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .tagline {
      font-size: 1.2em;
      color: #ffd700;
      margin-bottom: 40px;
    }
    .downloads {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #2e2a3a;
      border-radius: 15px;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.2);
    }
    .card h3 {
      margin-bottom: 10px;
    }
    .download-btn {
      background: #ffd700;
      color: #000;
      padding: 10px 15px;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: background 0.3s;
    }
    .download-btn:hover {
      background: #e6c200;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="1000090152.png" alt="Quraishi Logo" class="logo" />
    <h1>Quraishi Music Series</h1>
    <p class="tagline">Aapke Jazbaat, Hamari Awaaz</p>

    <div class="downloads">
      <div class="card">
        <h3>Kuch Keh Raha Hoon</h3>
        <a href="#" class="download-btn">Download</a>
      </div>
      <div class="card">
        <h3>Tera Intzaar</h3>
        <a href="#" class="download-btn">Download</a>
      </div>
    </div>
  </div>
</body>
</html>
