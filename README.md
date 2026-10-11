# Project page: Neural Voice-line Scheduling (MIG 2026)

Static site for "Constructing Dynamic Conversations with Neural Back-channel
Generation and Voice-line Scheduling". There is no build step: `index.html`
loads everything from `assets/` with relative paths.

- `index.html`: the page
- `paper.pdf`: camera-ready PDF
- `assets/video/`: overview video (720p) and the five control clips
- `assets/img/`: pipeline figure, result figures, video posters
- `.nojekyll`: tells GitHub Pages to serve the files as they are

Preview locally with `open index.html`.

The site is served by GitHub Pages from the `gh-pages` branch of
`EvanSamaa/NeuralSchedularRelease_page`:
https://evansamaa.github.io/NeuralSchedularRelease_page/

To update it, commit and `git push origin gh-pages`.
