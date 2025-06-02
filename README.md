<!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VibeNation DJ Verseny × After</title>
  <style>
    body {
      margin: 0;
      background: black;
      color: white;
      font-family: 'Segoe UI', sans-serif;
      padding: 0;
    }
    header {
      text-align: center;
      background: #000;
    }
    header img {
      width: 100%;
      max-width: 1000px;
      height: auto;
      display: block;
      margin: 0 auto;
    }
    .countdown {
      text-align: center;
      font-size: 2em;
      padding: 30px 0;
      background: linear-gradient(135deg, #ff00cc, #3333ff);
      color: white;
    }
    .content {
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      color: #ff00cc;
    }
    ul {
      padding-left: 20px;
    }
    .lineup span {
      display: inline-block;
      background: #222;
      padding: 6px 12px;
      border-radius: 10px;
      margin: 5px;
    }
    a {
      color: #00ffff;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 40px 20px;
      color: #999;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <img src="VibeNation-DJ-Verseny.jpg" alt="VibeNation DJ Verseny Banner" />
  </header>

  <div class="countdown">
    Eseményig hátralévő idő:<br>
    <span id="timer">Betöltés...</span>
  </div>

  <div class="content">
    <h2>DJ Verseny & Afterparty</h2>
    <p>Valami új. Valami más. Egy este, ahol a tehetség a középpontban van – és utána jöhet a tánc hajnalig!</p>

    <h3>💥 DJ Verseny</h3>
    <ul>
      <li>📨 Nevezés: <a href="mailto:vibenation.hungary@gmail.com">vibenation.hungary@gmail.com</a></li>
      <li>📝 Tárgy: DJ verseny nevezés</li>
      <li>💸 Nevezési díj: 4000 Ft / fő (előre fizetendő)</li>
    </ul>

    <h3>🎉 Afterparty Line-Up</h3>
    <div class="lineup">
      <span>🎶 KOKO</span>
      <span>🎶 BEATRONIC</span>
      <span>🎶 BOYK</span>
      <span>🎶 PETRICK</span>
      <span>🎶 AMERICANBOY</span>
      <span>🎶 TYMO</span>
    </div>

    <h3>🎟️ Jegyár</h3>
    <ul>
      <li>2500 Ft / fő</li>
      <li>Csak a helyszínen váltható</li>
      <li>Elővételben a szervezőnél elérhető</li>
    </ul>

    <h3>📍 Helyszín</h3>
    <p>Kikötő Romkocsma – 1211, Budapest, Weiss Manfréd út 5-7</p>

    <h3>📲 Kövess minket!</h3>
    <p>
      <a href="https://www.instagram.com/vibenation_hungary" target="_blank">Instagram: @vibenation_hungary</a><br>
      <a href="https://www.facebook.com/VibeNationHungary" target="_blank">Facebook: VibeNation Hungary</a>
    </p>
  </div>

  <footer>
    Made with ❤️ by VibeNation Hungary – 2025
  </footer>

  <script>
    // Visszaszámláló – 2025.07.05. 19:00
    const countdown = () => {
      const now = new Date();
      const eventDate = new Date("2025-07-05T19:00:00");
      const diff = eventDate - now;

      if (diff <= 0) {
        document.getElementById("timer").innerText = "Már elindult az esemény! 🔥";
        return;
      }

      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
      const minutes = Math.floor((diff / (1000 * 60)) % 60);
      const seconds = Math.floor((diff / 1000) % 60);

      document.getElementById("timer").innerText = `${days} nap ${hours} óra ${minutes} perc ${seconds} mp`;
    };

    setInterval(countdown, 1000);
    countdown();
  </script>
</body>
</html><!DOCTYPE html>
<html lang="hu">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VibeNation DJ Verseny × After</title>
  <style>
    body {
      margin: 0;
      background: black;
      color: white;
      font-family: 'Segoe UI', sans-serif;
      padding: 0;
    }
    header {
      text-align: center;
      background: #000;
    }
    header img {
      width: 100%;
      max-width: 1000px;
      height: auto;
      display: block;
      margin: 0 auto;
    }
    .countdown {
      text-align: center;
      font-size: 2em;
      padding: 30px 0;
      background: linear-gradient(135deg, #ff00cc, #3333ff);
      color: white;
    }
    .content {
      max-width: 800px;
      margin: 40px auto;
      padding: 0 20px;
    }
    h2 {
      color: #ff00cc;
    }
    ul {
      padding-left: 20px;
    }
    .lineup span {
      display: inline-block;
      background: #222;
      padding: 6px 12px;
      border-radius: 10px;
      margin: 5px;
    }
    a {
      color: #00ffff;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 40px 20px;
      color: #999;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <img src="VibeNation-DJ-Verseny.jpg" alt="VibeNation DJ Verseny Banner" />
  </header>

  <div class="countdown">
    Eseményig hátralévő idő:<br>
    <span id="timer">Betöltés...</span>
  </div>

  <div class="content">
    <h2>DJ Verseny & Afterparty</h2>
    <p>Valami új. Valami más. Egy este, ahol a tehetség a középpontban van – és utána jöhet a tánc hajnalig!</p>

    <h3>💥 DJ Verseny</h3>
    <ul>
      <li>📨 Nevezés: <a href="mailto:vibenation.hungary@gmail.com">vibenation.hungary@gmail.com</a></li>
      <li>📝 Tárgy: DJ verseny nevezés</li>
      <li>💸 Nevezési díj: 4000 Ft / fő (előre fizetendő)</li>
    </ul>

    <h3>🎉 Afterparty Line-Up</h3>
    <div class="lineup">
      <span>🎶 KOKO</span>
      <span>🎶 BEATRONIC</span>
      <span>🎶 BOYK</span>
      <span>🎶 PETRICK</span>
      <span>🎶 AMERICANBOY</span>
      <span>🎶 TYMO</span>
    </div>

    <h3>🎟️ Jegyár</h3>
    <ul>
      <li>2500 Ft / fő</li>
      <li>Csak a helyszínen váltható</li>
      <li>Elővételben a szervezőnél elérhető</li>
    </ul>

    <h3>📍 Helyszín</h3>
    <p>Kikötő Romkocsma – 1211, Budapest, Weiss Manfréd út 5-7</p>

    <h3>📲 Kövess minket!</h3>
    <p>
      <a href="https://www.instagram.com/vibenation_hungary" target="_blank">Instagram: @vibenation_hungary</a><br>
      <a href="https://www.facebook.com/VibeNationHungary" target="_blank">Facebook: VibeNation Hungary</a>
    </p>
  </div>

  <footer>
    Made with ❤️ by VibeNation Hungary – 2025
  </footer>

  <script>
    // Visszaszámláló – 2025.07.05. 19:00
    const countdown = () => {
      const now = new Date();
      const eventDate = new Date("2025-07-05T19:00:00");
      const diff = eventDate - now;

      if (diff <= 0) {
        document.getElementById("timer").innerText = "Már elindult az esemény! 🔥";
        return;
      }

      const days = Math.floor(diff / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
      const minutes = Math.floor((diff / (1000 * 60)) % 60);
      const seconds = Math.floor((diff / 1000) % 60);

      document.getElementById("timer").innerText = `${days} nap ${hours} óra ${minutes} perc ${seconds} mp`;
    };

    setInterval(countdown, 1000);
    countdown();
  </script>
</body>
</html>
