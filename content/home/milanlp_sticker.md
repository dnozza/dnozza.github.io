+++
# MilaNLP sticker widget created with the Blank widget.
widget = "blank"
headless = true
active = true
weight = 12

title = ""
subtitle = ""
+++

<script type="module" src="/js/sticker-forge.es.js"></script>
<sticker-forge id="milanlp-sticker" style="display:block;width:260px;height:260px;margin:0 auto;"></sticker-forge>
<script type="module">
  await customElements.whenDefined("sticker-forge");
  const sticker = document.querySelector("#milanlp-sticker");
  await sticker.setSource({
    "type": "image",
    "src": "/img/milanlp-logo.png",
    "name": "milanlp-logo.png"
  });
  sticker.setOptions({
    "outline": { "width": 18, "color": "#ffffff" },
    "edge": { "width": 2.4, "strength": 0.7 },
    "shadow": { "opacity": 0.22, "blur": 22, "distance": 16, "angle": 42, "color": "#191823" },
    "lighting": {
      "direction": { "x": -0.24, "y": 0.32, "z": 0.92 },
      "intensity": 1,
      "ambient": 0.28,
      "softness": 0.5
    },
    "peel": { "radius": 0.12, "stiffness": 0.45, "grabWidth": 22, "maxAngle": 3.55, "release": "snap" },
    "sound": { "enabled": true, "volume": 0.5 },
    "back": { "color": "#f7f5f2", "gloss": 0.7, "roughness": 0.3 },
    "material": {
      "type": "original",
      "intensity": 0.86,
      "scale": 1,
      "seed": 0.37,
      "holographicColors": ["#f2a7c5", "#8edfd5", "#9db4ea"]
    },
    "tilt": -3,
    "wind": 0.25,
    "quality": "high"
  });
</script>
