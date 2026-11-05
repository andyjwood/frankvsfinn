# Frank VS Finn 🐱🏃‍♀️

A free, ad-free chase game for phones, tablets and desktops. Finn is running through a huge house, and Frank the fluffy white Persian cat wants a cuddle. Steer Finn around the room, dodge the slippers, and stay ahead of the cats for as long as you can.

**[▶ Play now](https://YOUR-USERNAME.github.io/YOUR-REPO/)**

## How to play

- **Steer:** drag your finger (or move your mouse) and Finn runs that way.
- **Run fast:** keep your finger far from Finn. If you hold it close to her, she slows down.
- **Don't turn back:** if you turn toward the cats or slow down too much, Frank pounces and the run ends.
- **Mind the slippers:** slippers pop up around the room. Tripping on one stuns Finn for a moment and lets the cats catch up.
- **Survive:** Frank gets a short head start, and another cat joins every 12 seconds (up to 7). Everyone runs faster as time goes on.
- **Score:** the time you survived. Your best time is saved on your device.

## Features

- A big room that scrolls as you run, with dark wood floors, light carpet, rugs, and beige and blue walls
- Cartoon characters drawn entirely in code
- Cats and slippers that increase as the game goes on
- Sound effects, with a mute button
- Works offline after the first load
- **No ads, no accounts, no tracking.** Everything stays on your device.

## Install it like an app

On an iPhone or iPad, open the game in Safari, tap **Share → Add to Home Screen**, and it opens full-screen with its own icon. On Android, use your browser's **Install app** or **Add to Home screen** option.

## Privacy

Frank VS Finn collects no data. Your best time is kept in your browser's local storage and never leaves your device. Clearing your browser's site data resets it.

## Run it yourself

It's plain HTML, CSS and JavaScript with no build step.

1. Download or clone this repo.
2. Open `index.html` in a browser, or host the folder anywhere that serves static files.

To publish with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## What's in the repo

| File | Purpose |
|---|---|
| `index.html` | The whole game |
| `manifest.webmanifest` | Home-screen app details |
| `sw.js` | Offline support and automatic updates |
| `icon-*.png` | App icons |

## Customizing

Near the top of the script in `index.html` you can change:

- The room's size and layout (`WW`, `WH`, `CARPETS`, `RUGS`)
- How fast the cats arrive and how many there can be (the `want` calculation in `updatePlay`)
- Running speed (`vmax` in `updatePlay`)
- Characters and colors (the `drawFinn`, `drawCat` and `drawSlipper` functions)

## Credits

An original game made for fun. It isn't affiliated with any other game or company.

## License

MIT. See `LICENSE`.
