# Feelings Field Guide

A color-coded, phone-friendly guide for naming what you feel.

## Why I made this

I struggle to know what I'm feeling. Often I can tell something is going on inside, but I can't put a name to it, and "fine," "stressed" or "off" is about as far as I get. I wanted a quick reference I could pull up in the moment: something that helps me dig into a feeling, find the word that actually fits, and learn a little about what it might be asking for. The more I use it, the easier it gets to name what I'm feeling without it.

Thank you to my men's group for the inspiration to build this, and for the support that makes this kind of work feel possible.

Twelve feeling families, ordered from pleasant to unpleasant (Joy, Loving, Peaceful, Hopeful, Strong, Surprised, Confused, Tired, Sad, Afraid, Angry, Ashamed), plus Body sensations. Each family has three groups from mild to intense. Tap any word to open a deep dive with:

- what the feeling tends to sound like inside
- eight more specific words, each with a short meaning
- what the feeling may be asking for
- one small thing to try
- links to the milder or more intense version

Also included:

- **A private log.** Save a feeling with an optional note and see which families show up most over the last week. Entries stay on the device; nothing is sent anywhere.
- **Light, dark or system theme**, in Settings & help.
- **Search** across every word, and deep links like `#sad` or `#sad-hurt`.
- **Works offline** after the first visit.

## Use it like an app

- **iPhone or iPad:** open the site in Safari, tap **Share → Add to Home Screen**.
- **Android:** open it in Chrome, tap **⋮ → Add to Home screen** (or **Install app**).

It opens full-screen with its own icon.

## How it's built

One self-contained `index.html` with no build step. The only outside dependency is the Fredoka and Lexend fonts from Google Fonts. All feeling data lives in the `D` and `BODY` arrays near the top of the script, so adding or editing words happens in one place.

- `sw.js` caches the app for offline use. **Bump `VERSION` in `sw.js` whenever `index.html` changes**, or installed copies keep showing the old version.
- `manifest.webmanifest` and the icon PNGs make the home-screen install work.

## Credits

Inspired by Abby VanMuijen's feelings wheel (@avanmuijen) and the feelings lists of Nonviolent Communication and the Hoffman Institute.

## Hosting

Served by GitHub Pages from the `main` branch root.

## License

[MIT](LICENSE), covering the code and the feeling words and meanings alike. Fork it, adapt it, make your own version; keep the notice.
