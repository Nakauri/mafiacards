# FIFA World Cup 26 Mafia Card Maker

A single-file browser tool for making FIFA World Cup 2026 styled role cards for a forum mafia game. Open `index.html`, pick a country and player, fill in the role and abilities, choose a style, and download a PNG.

Everything (fonts, images, the 48-nation player dataset) is embedded in `index.html`, so it is a static site with no backend.

## Develop
`index.html` is generated. Edit `src/card-maker.src.html`, then run `node build.js` to rebuild (it embeds the assets from `assets/`).

## Deploy
Static site. On Vercel: import the repo, framework preset "Other", no build command, output directory = root. It serves `index.html`.
