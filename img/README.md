# Instrument images

Each instrument card on the landing page has an image carousel. Until an image exists, the slide shows a placeholder.

To add an image, put it here with this name:

```
img/<instrument>/<slide number>.jpg   (or .png)
```

| Instrument | Folder | Slides on the page |
|---|---|---|
| TouchlineFX | `img/touchlinefx/` | 1: telestration on match footage · 2: player tracking with perspective drawing · 3: data-annotated graphic |
| MatchMorph | `img/matchmorph/` | 1: event data over live video · 2: calculated metrics · 3: passing network and possession chains |
| PitchScope | `img/pitchscope/` | 1: board from a real match moment · 2: shapes and movements · 3: board next to the video |
| HalfSpace | `img/halfspace/` | 1: tracking data on video · 2: pitch control · 3: possession value |

Images are cropped to the 105 : 68 pitch ratio (for example 1050 × 680 px). Keep each file under ~300 KB.

To add a fourth slide or more, copy one `<div class="slide">` block in `index.html` and change the number, caption and alt text. The dots update automatically.

Only use footage you have the rights to.
