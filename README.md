<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="utf-8">
  <title>Auto-Skip Ads • Pobieranie</title>

  <!-- Fallback, gdy JS wyłączony -->
  <meta http-equiv="refresh"
        content="3;url=https://github.com/Fervv268/AutoSkipAds/releases/download/v1.0/AutoSkipAds.apk">

  <style>
    :root{--gray:#f7f7f7;--blue:#0b82d9}
    body{
      margin:0;min-height:100vh;display:flex;justify-content:center;align-items:center;
      font-family:system-ui,Arial,sans-serif;background:var(--gray)}
    .box{
      background:#fff;border-radius:12px;box-shadow:0 2px 12px #0001;
      padding:2.5rem 2rem;text-align:center}
    a{color:var(--blue);text-decoration:none;font-weight:600}
  </style>

  <script>
    /* Szybsze przekierowanie (1 s) */
    const apk = 'https://github.com/Fervv268/AutoSkipAds/releases/download/v1.0/AutoSkipAds.apk';
    window.addEventListener('load', () => {
      setTimeout(() => location.href = apk, 1000);
      document.getElementById('manual').href = apk;
    });
  </script>
</head>

<body>
  <div class="box">
    <h1>Auto-Skip Ads</h1>
    <p>Pobieranie rozpocznie się automatycznie.<br>
       Jeżeli zostanie zablokowane, kliknij
       <a id="manual" href="#" download>ten link</a>.
    </p>
  </div>
</body>
</html>
