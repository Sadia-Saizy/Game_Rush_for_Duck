# Rush for Ducks

🎮 **Play Now:** [https://sadia-saizy.github.io/Game_Rush_for_Duck/](https://sadia-saizy.github.io/Game_Rush_for_Duck/)

An arcade endless-runner and platformer built as an installable Progressive Web App (PWA) and hosted on GitHub Pages.

📱 **Scan to Play on Mobile:**
<img width="1170" height="1063" alt="BADD2813-E0B1-4762-A8FA-9637182B98BC_1_201_a" src="https://github.com/user-attachments/assets/c196bcbf-447a-47ff-874c-1a17ef35fde4" />
📱 **Scan to Play on Mobile:**
<br />
<img width="220" alt="Rush for Ducks QR Code" src="https://github.com/user-attachments/assets/c196bcbf-447a-47ff-874c-1a17ef35fde4" />
## Playable Cast & Rival
- **Peep (Level 1)**: Round yellow chick with a red crest, upward-looking eyes, and tall black legs featuring agile double-jumping.
- **Quack (Level 3)**: Tall vertical-oval purple duck with a white sailor hat, air gliding, and a mid-air dive ground-smash earthquake.
- **Hoot (Level 10)**: Stern lavender horned owl with slate-gray ear tufts, wing, and talons, yellow eyes, and a Sonic Hoot blast.
- **Rosie (Level 13)**: Nimble female duck with rosy cheeks and red starry eyes that can scare off rivals.
- **Chirp (Enemy Rival)**: Swooping red-breasted robin patrolling flight paths alongside ground obstacles.

## Gameplay & Controls
- **Web Audio Sound Engine**: Synthesized audio cues for jumping, collecting items, hero specials, level-ups, and mute toggling.
- **Keyboard Controls**:
  - `Space` / `W` / `ArrowUp`: Jump & Flap (hold with Quack to glide)
  - `ArrowDown` / `S`: Duck & Dive Ground-Smash
  - `E` / `Shift`: Hero Special Ability (Hoot & Rosie)
  - `C`: Switch unlocked hero
  - `P` / `Esc`: Pause / Resume
- **Mobile & Touch Controls**: Tap or swipe on the canvas, or use the on-screen **Jump / Fly**, **Duck / Dive**, and **Special** buttons.

## Repository Files
- `index.html`: Single-file game application with the canvas loop, character artwork, HUD, modals, and sound engine.
- `manifest.json`: Web app manifest configured for standalone launch under `/Game_Rush_for_Duck/`.
- `sw.js`: Service worker precaching core files and cleaning up old cache versions on activation.
- `icon.svg`: `512x512` vector app icon on a light/white background featuring colors from the cast.
- `README.md`: Project overview, controls, and deployment notes.

## Deployment & Mobile PWA Notes
1. Push changes to the branch configured for GitHub Pages and verify **Enforce HTTPS** is enabled under **Settings → Pages**.
2. Open `https://sadia-saizy.github.io/Game_Rush_for_Duck/` (using `https://`) and use **Add to Home Screen** / **Install app** for standalone mobile play.
3. Bump the cache name in `sw.js` whenever updating cached assets, refresh your browser, and re-add the Home Screen shortcut if an older icon or title remains cached.
