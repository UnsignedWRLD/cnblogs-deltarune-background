# Cnblogs Deltarune Background Assets

Web-ready assets extracted from the Wallpaper Engine scene for the Cnblogs V2 theme.

- `fallback.webp`: 1920x1080 static fallback.
- `manifest.json`: browser layer order, coordinates, shader speeds, and sprite metadata.
- `layers/`: lossless WebP layers, including the original four-frame character
  and shadow sprite sheets. Animated frames use transparent edge gutters to
  prevent adjacent-frame bleed at fractional browser scales.

Use the jsDelivr manifest URL in `window.CtfBlogTheme.deltaruneManifest`.
