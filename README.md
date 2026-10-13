# ✨ Dress-Up Star

A dress-up game that runs entirely in the browser. Choose a girl's hair, clothes, shoes, glasses, hats and accessories.

**Play it:** https://yuli2310.github.io/dress-up-game/

Built with plain HTML, CSS and JavaScript. No backend, no database, no API keys, no installs.

## How to play

1. Tap a category on the pink buttons on either side of the character (Skin, Hair, Top, Bottom, Dress, Shoes, Glasses, Hats, Extras, Scene).
2. Choose a style and a color in the panel.
3. Watch your character change on the left.

### Buttons

| Button | What it does |
| --- | --- |
| 🎲 Surprise me! | Picks a random outfit |
| 💃 Twirl | Spins the character around |
| 🔊 Sound on / 🔇 Sound off | Turns sound effects on or off |
| 📷 Save picture | Downloads your character as a PNG |
| ↩️ Start over | Resets to the default look |

### ⭐ My outfits

Press **Save this outfit** to keep a look (up to 12). Saved outfits show as small pictures; press **Wear** to bring one back. They are stored in your browser only, so they stay on the computer you used.

## Run it yourself

No setup needed. Download the project and open `index.html` in any modern browser.

```sh
git clone https://github.com/yuli2310/dress-up-game.git
open dress-up-game/index.html
```

## How it works

- The whole game is one file, `index.html`.
- The character is drawn with inline SVG, built from layers (background, hair, body, shoes, clothes, face, glasses, hat, extras).
- Sound effects are generated with the Web Audio API, so there are no audio files.
- Saved outfits use the browser's `localStorage`.
- Animations (blinking, bobbing, twirling, sparkles) use CSS and are turned off for people who have "reduce motion" set on their device.

## Deployment

Published with GitHub Pages from the `main` branch. Pushing to `main` updates the live site in a minute or two.
