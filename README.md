# swooper

A browser flight game: soar a glider over an **endless Himalaya-like mountain range**, riding ridge lift and thermals to stay aloft. Built from scratch with **our own realistic glider aerodynamics** — lift & drag from angle of attack, with stall, terminal velocity, loops and rolls all emerging from the physics rather than scripted limits.

Inspired by *Superflight*, but a clean-room original: our own code, our own flight model, our own continuous low-poly world — no assets from the original game.

**▶ Play:** https://emorozoff.github.io/swooper/

## Controls (keyboard)
- **↓ / S** — nose up · **↑ / W** — nose down
- **← / →** (or **A / D**) — roll / turn · **Q / E** — yaw (rudder)
- **M** — mute/unmute sound · **R** — restart · **Esc** — pause · **Space** — resume

## Finding lift (soaring)
Dark patches on the ground and **cumulus clouds** mark strong thermals. Fly toward them, listen for the **variometer beep** (faster/higher = climbing), then circle to stay in the rising column.

## Flexible wings
The glider's wings bow up at the root under aerodynamic load (G), with a springy settle (they bend up eagerly and ease back down). It's purely visual — physics is a point-mass, so the flex never changes how the glider flies.

Single `index.html`, Three.js via CDN, no build step.

🚧 Work in progress.
