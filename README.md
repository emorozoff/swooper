# swooper

A browser flight game: soar a glider over an **endless Himalaya-like mountain range**, riding ridge lift and thermals to stay aloft. Built from scratch with **our own realistic glider aerodynamics** — lift & drag from angle of attack, with stall, terminal velocity, loops and rolls all emerging from the physics rather than scripted limits.

Inspired by *Superflight*, but a clean-room original: our own code, our own flight model, our own continuous low-poly world — no assets from the original game.

**▶ Play:** https://emorozoff.github.io/swooper/

## Controls (keyboard / mouse)
- **↓ / S** — nose up · **↑ / W** — nose down
- **← / →** (or **A / D**) — roll / turn · **Q / E** — yaw (rudder)
- **Space (hold)** — airbrakes: spoilers pop up, bleeding speed and lift for a steeper descent
- **P** — freeze-frame pause (time + sound stop, study the view) · **Esc** — settings
- **Mouse drag** — look around the glider (eases back to chase when released)
- **M** — mute sound · **R** — restart

## Finding lift (soaring)
Dark patches on the ground and **cumulus clouds** mark strong thermals. Fly toward them, listen for the **variometer beep** (faster/higher = climbing), then circle to stay in the rising column.

## Sunset worlds (seeds)
Every world is a fixed sunset under a low warm sun with long shadows and atmospheric haze. The **seed** (set in the menu — it's saved in your browser, so the link stays clean) picks the mountains, the whole colour mood — golden, rosy, amber, or a rare cool "blue hour" — **and the prevailing wind** (each world blows from a different direction at a different strength), all harmonised so it always reads as one coherent sunset. Same seed → same world.

Strong thermals **darken the ground** beneath them — look down for the patch, up for the cumulus that caps it. Wind **speeds up over ridges and stalls in the lee**, so ridge soaring reads off the terrain. Fly too close and you'll **crash into the mountainside** (toggle off in settings); skim it instead and the air roars past.

## Flexible wings
The glider's wings bow up at the root under aerodynamic load (G), with a springy settle. Purely visual — physics is a point-mass, so the flex never changes how the glider flies.

Single `index.html`, Three.js via CDN, no build step.

## 3D model

The glider mesh is **"UNDERPOLY: Free Sailplane Glider"** by **UNDERPOLY Project**, used under CC-BY-4.0 (attribution required); its ailerons and rudder are animated in-engine from the flight controls.

> This work is based on ["UNDERPOLY: Free Sailplane Glider"](https://sketchfab.com/3d-models/underpoly-free-sailplane-glider-45ffefc38fcf4e76a9d0c2a4e76262ef) by [UNDERPOLY Project](https://sketchfab.com/underpolyproject) licensed under [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/).

🚧 Work in progress.
