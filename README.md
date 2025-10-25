<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>opchicken_official</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #0b0b0b;
      color: white;
      text-align: center;
      overflow-x: hidden;
    }

    h1 {
      font-size: 3rem;
      color: #ff0000;
      text-shadow: 0 0 20px #ff0000, 0 0 40px #ff0000;
      animation: glow 2s ease-in-out infinite alternate;
      margin-top: 80px;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #ff0000, 0 0 20px #ff0000;
      }
      to {
        text-shadow: 0 0 30px #ff0000, 0 0 60px #ff0000;
      }
    }

    p {
      font-size: 1.2rem;
      color: #ccc;
      margin-top: 10px;
    }

    .buttons {
      margin-top: 60px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    a.button {
      text-decoration: none;
      color: white;
      background-color: #111;
      border: 2px solid #ff0000;
      padding: 15px 30px;
      border-radius: 12px;
      font-weight: 600;
      letter-spacing: 1px;
      box-shadow: 0 0 15px #ff0000;
      transition: all 0.3s ease;
      animation: pulse 2s infinite;
    }

    a.button:hover {
      background-color: #ff0000;
      color: #fff;
      box-shadow: 0 0 25px #ff0000, 0 0 50px #ff0000;
      transform: scale(1.08);
    }

    @keyframes pulse {
      0% {
        box-shadow: 0 0 10px #ff0000;
      }
      50% {
        box-shadow: 0 0 25px #ff0000, 0 0 50px #ff0000;
      }
      100% {
        box-shadow: 0 0 10px #ff0000;
      }
    }

    footer {
      margin-top: 80px;
      color: #666;
      font-size: 0.9rem;
      padding-bottom: 20px;
    }
  </style>
</head>
<body>
  <h1>opchicken_official</h1>
  <p>Watch the funniest chicken on the internet 🐔🔥</p>

  <div class="buttons">
    <a class="button" href="https://www.twitch.tv/opchicken_official" target="_blank">Watch the GOAT on Twitch</a>
    <a class="button" href="https://www.youtube.com/@opchicken_official/shorts" target="_blank">Watch the GOAT on YouTube</a>
  </div>

  <footer>© 2025 opchicken_official | The Coop Never Sleeps 🐔</footer>
</body>
</html>
