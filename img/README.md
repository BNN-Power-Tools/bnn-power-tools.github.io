# Instrument images

Each instrument card on the landing page has an image carousel. Until an image exists, the slide shows a placeholder.

The current images are screenshots of the video-data-combinator prototype (800 × 517). Replace any file to change a slide.

To add an image, put it here with this name:

```
img/<instrument>/<slide number>.jpg   (or .png)
```

| Instrument | Folder | Slides on the page |
|---|---|---|
| TouchlineFX | `img/touchlinefx/` | 1: telestration tools · 2: clip list and export · 3: possession chain over the video |
| MatchMorph | `img/matchmorph/` | 1: event data in sync with video · 2: player metrics · 3: passing network |
| PitchScope | `img/pitchscope/` | 1: board from a real match frame · 2: team shapes · 3: board with the video frame |
| HalfSpace | `img/halfspace/` | 1: live tracking map · 2: pitch control · 3: possession value |

Images are cropped to the 105 : 68 pitch ratio (for example 1050 × 680 px). Keep each file under ~300 KB.

To add a fourth slide or more, copy one `<div class="slide">` block in `index.html` and change the number, caption and alt text. The dots update automatically.

Only use footage you have the rights to.
