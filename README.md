<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Zufalls-Weiterleitung</title>
  <script>
    function randomRedirect() {
      if (Math.random() < 0.5) {
        window.location.href = "https://albertinum-coburg.de/lehrkraefte/";
      } else {
        window.location.href = "https://www.casimirianum.de";
      }
    }
    window.onload = randomRedirect;
  </script>
</head>
<body>
  <p>Weiterleitung läuft...</p>
</body>
</html>
