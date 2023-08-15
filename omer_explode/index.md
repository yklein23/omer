<!doctype html>
<html lang="en">
  <head>
    <title>&lt;model-viewer&gt; template</title>
    <meta charset="utf-8">
    <meta name="description" content="&lt;model-viewer&gt; template">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link type="text/css" href="./styles.css" rel="stylesheet"/>
  </head>
  <body>
    <!-- <model-viewer> HTML element -->
    <model-viewer src="omer _explode.glb" ar ar-modes="wall" camera-controls poster="poster.webp" shadow-intensity="1" auto-rotate>
      <button class="Hotspot" slot="hotspot-1" data-position="0.022385776679636718m 0.2122361802399487m 0.6195392436478465m" data-normal="1.6292069593415448e-7m -0.00019519948693515795m 0.9999999809485668m" data-visibility-attribute="visible">
          <div class="HotspotAnnotation">Side Covers</div>
      </button><button class="Hotspot" slot="hotspot-2" data-position="0.3075083053287242m 0.12549451230070202m 0.12269470403535532m" data-normal="0.9804017221211009m -0.1970087898089303m -2.646987221077702e-8m" data-visibility-attribute="visible">
          <div class="HotspotAnnotation">Main Duct</div>
      </button><button class="Hotspot" slot="hotspot-3" data-position="-0.0009080602483322875m -0.19182860591677325m 0.27319186260504347m" data-normal="0.6864218870598473m -0.7272020146325293m -0.001490932456157723m" data-visibility-attribute="visible">
          <div class="HotspotAnnotation">Invi Swing</div>
      </button>
      <div class="progress-bar hide" slot="progress-bar">
          <div class="update-bar"></div>
      </div>
      <button slot="ar-button" id="ar-button">
          View in your space
      </button>
      <div id="ar-prompt">
          <img src="ar_hand_prompt.png">
      </div>
    </model-viewer>
    <script src="script.js"></script>
    <!-- Loads <model-viewer> for browsers: -->
    <script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.2.0/model-viewer.min.js"></script>
  </body>
</html>
