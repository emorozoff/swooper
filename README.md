# swooper

A browser flight game: soar a glider over an **endless Himalaya-like mountain range**, riding ridge lift and thermals to stay aloft. Built from scratch with **our own realistic glider aerodynamics** — lift & drag from angle of attack, with stall, terminal velocity, loops and rolls all emerging from the physics rather than scripted limits.

Inspired by *Superflight*, but a clean-room original: our own code, our own flight model, our own continuous low-poly world — no assets from the original game.

**▶ Play:** https://emorozoff.github.io/swooper/

## Controls (keyboard)
- **↓ / S** — nose up · **↑ / W** — nose down
- **← / →** (or **A / D**) — roll / turn · **Q / E** — yaw (rudder)
- **1–5** — wing/body **flexibility mode** (rigid · simple · advanced cantilever · fuselage whip · combined)
- **M** — mute/unmute sound · **R** — restart · **Esc** — pause · **Space** — resume

## Finding lift (soaring)
Dark patches on the ground and **cumulus clouds** mark strong thermals. Fly toward them, listen for the **variometer beep** (faster/higher = climbing), then circle to stay in the rising column.

## Flexible wings
The glider's wings and tail boom flex under aerodynamic load (G). Five flex models can be compared with keys **1–5**: rigid, simple root-bow, advanced multi-segment cantilever (the tip bows most, with spring-damper dynamics and a gust ripple), fuselage/boom whip, and combined. The flex is purely visual — physics is a point-mass, so it never changes how the glider flies.

Single `index.html`, Three.js via CDN, no build step.

🚧 Work in progress.
