<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yorran Personal</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #000;
      color: white;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 20px;
    }

    .container {
      width: 100%;
      max-width: 420px;
    }

    .card {
      background: #0f0f0f;
      border: 1px solid #222;
      border-radius: 30px;
      padding: 35px 25px;
      text-align: center;
      box-shadow: 0 0 30px rgba(255,255,255,0.05);
    }

    .photo {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      background: #1f1f1f;
      margin: 0 auto;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #666;
      border: 4px solid #222;
    }

    .tag {
      margin-top: 20px;
      color: #777;
      letter-spacing: 3px;
      font-size: 12px;
      text-transform: uppercase;
    }

    h1 {
      margin-top: 10px;
      font-size: 32px;
    }

    .description {
      margin-top: 20px;
      color: #aaa;
      line-height: 1.6;
      font-size: 15px;
    }

    .badges {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 10px;
      margin-top: 25px;
    }

    .badge {
      background: #181818;
      border: 1px solid #222;
      padding: 10px 15px;
      border-radius: 999px;
      font-size: 12px;
      color: #ccc;
    }

    .buttons {
      margin-top: 35px;
      display: flex;
      flex-direction: column;
      gap: 15px;
    }

    .button {
      text-decoration: none;
      padding: 18px;
      border-radius: 18px;
      font-weight: bold;
      transition: 0.3s;
      display: block;
    }

    .primary {
      background: white;
      color: black;
    }

    .secondary {
      background: #181818;
      color: white;
      border: 1px solid #222;
    }

    .button:hover {
      transform: scale(1.02);
    }

    .footer {
      text-align: center;
      margin-top: 20px;
      color: #555;
      font-size: 12px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <div class="photo">
        SUA FOTO
      </div>

      <div class="tag">
        Personal Trainer
      </div>

      <h1>Yorran Stafuzza</h1>

      <p class="description">
        Consultoria online e acompanhamento presencial focado em emagrecimento, hipertrofia e evolução física.
      </p>

      <div class="badges">
        <div class="badge">Online</div>
        <div class="badge">Presencial</div>
        <div class="badge">Barretos/SP</div>
      </div>

      <div class="buttons">
        <a href="#" class="button primary">
          Consultoria Online
        </a>

        <a href="#" class="button secondary">
          Personal Presencial
        </a>

        <a href="#" class="button secondary">
          Falar no WhatsApp
        </a>

        <a href="#" class="button secondary">
          Meu Instagram
        </a>
      </div>
    </div>

    <div class="footer">
      © 2026 • Yorran Personal Trainer
    </div>
  </div>
</body>
</html>
