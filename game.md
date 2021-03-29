# Sitting Ducks

[:back: Back to home page](./)

<html lang="en-us">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <title>Unity WebGL Player | Sitting Ducks</title>
    <link rel="shortcut icon" href="game/TemplateData/favicon.ico">
    <link rel="stylesheet" href="game/TemplateData/style.css">
    <script src="game/TemplateData/UnityProgress.js"></script>
    <script src="game/Build/UnityLoader.js"></script>
    <script>
      var unityInstance = UnityLoader.instantiate("unityContainer", "game/Build/Builds.json", {onProgress: UnityProgress});
    </script>
  </head>
  <body>
    <div class="webgl-content">
      <div id="unityContainer" style="width: 960px; height: 600px"></div>
      <div class="footer">
        <div class="webgl-logo"></div>
        <div class="fullscreen" onclick="unityInstance.SetFullscreen(1)"></div>
        <div class="title">Sitting Ducks</div>
      </div>
    </div>
  </body>
</html>