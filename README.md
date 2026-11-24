# Rush for Ducks

An arcade endless-runner and platformer built as an installable Progressive Web App (PWA) and hosted on GitHub Pages at `https://sadia-saizy.github.io/Game_Rush_for_Duck/`.

## Features & Gameplay
- **Four Playable Heroes**:
  - **Peep (Level 1)**: Round yellow chick with a red crest, upward-looking eyes, and tall black legs featuring agile double-jumping.
  - **Quack (Level 3)**: Tall vertical-oval purple duck with a white sailor hat, air gliding, and a mid-air dive ground-smash earthquake.
  - **Hoot (Level 10)**: Stern lavender horned owl with slate-gray ear tufts, wing, and talons, yellow eyes, and a Sonic Hoot blast.
  - **Rosie (Level 13)**: Nimble female duck with rosy cheeks and red starry eyes that can scare off rivals.
- **Rival Hazard — Chirp**: Swooping red-breasted robin patrolling flight paths alongside ground obstacles.
- **Web Audio Sound Engine**: Synthesized sound effects for jumps, collectibles, abilities, level-ups, and mute toggling.
- **Mobile & Desktop Controls**: Keyboard (`Space` / `W` / `ArrowUp` to jump, `ArrowDown` / `S` to duck/dive, `E` / `Shift` for special ability, `C` to switch heroes, `P` / `Esc` to pause) as well as touch and swipe controls.

## Project Structure
- `index.html`: Single-file game application containing the canvas game loop, character rendering, HUD, modals, and sound engine.
- `manifest.json`: PWA web app manifest configured for standalone launch under `/Game_Rush_for_Duck/`.
- `sw.js`: Service worker precaching core assets and cleaning up outdated cache versions on activation.
- `icon.svg`: `512x512` vector app icon with a light/white backdrop and colors representing the cast.

## Deployment & PWA Notes
1. Push updates to the repository branch configured for GitHub Pages (`https://sadia-saizy.github.io/Game_Rush_for_Duck/`) with **Enforce HTTPS** enabled.
2. Bump the cache version constant in `sw.js` whenever updating cached assets (`index.html`, `icon.svg`, or `manifest.json`) so existing clients refresh cleanly.
3. On mobile devices, open the `https://` URL and use **Add to Home Screen** / **Install app** to launch in standalone mode.
