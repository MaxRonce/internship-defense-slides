# Inferring galaxy properties from their light

Reveal.js slides for Maxime Ronceray's master's internship defense at CEA
Paris-Saclay / CosmoStat / Polymathic AI, supervised by François Lanusse and
Samuel Farrens.

The presentation is designed for a 15-minute talk followed by 15 minutes of
questions. It contains 29 main slides and six vertical backup slides.

## View the slides

The deck is self-contained and can be served with any static HTTP server:

```bash
python3 -m http.server 8000
```

Then open <http://127.0.0.1:8000/index.html>.

Reveal.js navigation:

- `Space` or `Right`: advance
- `Left`: go back
- `S`: speaker view
- `F`: fullscreen
- `Esc`: overview
- `Down` from the final slide: backup slides

## Edit with Lectern

```bash
npm install
npm run edit
```

Lectern opens a visual editor for `index.html`. Its annotations remain embedded
in the deck, so the HTML file is the canonical source.

To list pending annotations:

```bash
npm run notes
```

## Structure

| Movement | Slides | Target |
| --- | ---: | ---: |
| Problem and two-route plan | 1-3 | 1:15 |
| Physics-constrained inference | 4-17 | 6:51 |
| Data-driven representations | 18-27 | 5:38 |
| Synthesis and takeaways | 28-29 | 0:59 |
| Speaking buffer | | 0:17 |

Numerical claims and visual assets retain source and provenance information in
the slide captions and `assets/visual-provenance.json`. Posterior distributions
are retained throughout; medians are used only for the explicitly pointwise
redshift comparison.
