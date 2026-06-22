# swooper

A browser flight game: soar a glider over an **endless Himalaya-like mountain range**, riding ridge lift and thermals to stay aloft. Built from scratch with **our own realistic glider aerodynamics** — lift & drag from angle of attack, with stall, terminal velocity, loops and rolls all emerging from the physics rather than scripted limits.

Inspired by *Superflight*, but a clean-room original: our own code, our own flight model, our own continuous low-poly world — no assets from the original game.

**▶ Play:** https://emorozoff.github.io/swooper/

## Controls (keyboard)
- **↓ / S** — nose up · **↑ / W** — nose down
- **← / →** (or **A / D**) — roll / turn · **Q / E** — yaw (rudder)
- **Space** — freeze-frame pause (time + sound stop, study the view) · **Esc** — menu (seed / settings / restart)
- **M** — mute sound · **R** — restart

## Finding lift (soaring)
Dark patches on the ground and **cumulus clouds** mark strong thermals. Fly toward them, listen for the **variometer beep** (faster/higher = climbing), then circle to stay in the rising column.

## Sunset worlds (seeds)
Every world is a fixed sunset under a low warm sun with long shadows and atmospheric haze. The **seed** (set in the menu, or `?seed=N` in the URL) picks both the mountains and the whole colour mood — golden, rosy, amber, or a rare cool "blue hour" — all harmonised so it always reads as one coherent sunset. Same seed → same world.

The valleys hold **lakes** that catch the sunset, the green lowlands are dotted with **forests and the odd village** for scale, **snow** flurries drift near the peaks, and strong thermals raise a faint **dust column** off the ground (so you can spot lift below as well as by the cloud above). Wind **speeds up over ridges and stalls in the lee**, so ridge soaring reads off the terrain.

## Flexible wings
The glider's wings bow up at the root under aerodynamic load (G), with a springy settle. Purely visual — physics is a point-mass, so the flex never changes how the glider flies.

Single `index.html`, Three.js via CDN, no build step.

🚧 Work in progress.
