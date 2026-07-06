# Palette

**Live: [palette.joshua-garcia.com](https://palette.joshua-garcia.com)**

Paint with color, hear music. Notes are colors on a canvas; a playhead sweeps left to
right and plays whatever it crosses. Pitch snaps to a scale and time snaps to a grid,
so anything you paint comes out in key and in time.

Built with vanilla JS, Tone.js (Web Audio) and GSAP (motion). The instrument is a
sampled grand piano, self-hosted, so it plays offline.

## Playing it

- **Moods** (blue, green, red) set the color field, the key, and the tempo.
- **Colors** are your paints. The darkest plays bass; the rest climb from dark to bright.
- **Stroke speed** shapes each note: slow is bold, fast is soft, a flick becomes a flurry.
- **Surprise me** loads one of three songs, arranged in Palette's own voice: Frank Ocean,
  Alicia Keys, or Sade.

## Running locally

```
cd webapp
npx live-server --no-browser --port=5500
```

Open http://127.0.0.1:5500.

## Credits

Piano: Salamander Grand Piano by Alexander Holm (CC-BY 3.0). Tone.js (MIT).
GSAP (standard license). Work Sans (SIL OFL).
Album cover art © the respective rights holders, included to identify the songs.

## License

© 2026 Joshua Garcia. All rights reserved.
