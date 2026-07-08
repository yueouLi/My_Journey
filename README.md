# Music

## How it works
- Player looks for `music/journey.mp3` (fallback: `music/journey.ogg`)
- If no file exists (or fails to load), the site **generates an ambient drone in real time** using Web Audio API — so it always sounds like something, even before you add a track

## Add your own track
1. Drop an MP3 into this folder, name it `journey.mp3`
2. Reload the page
3. Click the play button (bottom-right corner)

## Where to find copyright-safe music
- **YouTube Audio Library** — free, no attribution needed
  https://studio.youtube.com/channel/UC/music
- **Pixabay Music** — CC0
  https://pixabay.com/music/
- **Free Music Archive** — CC-licensed
  https://freemusicarchive.org/
- **Uppbeat** — free tier with attribution
  https://uppbeat.io/

## Genre suggestions for this site
- ambient / drone
- lo-fi minimal
- cinematic piano
- neo-classical / Nils Frahm style
- Brian Eno "Music for Airports" style

## Change the display name
In `index.html`, find `<div class="track" id="trackName">` and edit the text.
