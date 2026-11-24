# Scrappy FPS

A tiny first-person shooter in a single HTML file, built with three.js.

## Play

Open `index.html` in a browser, or serve it locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Controls

| Key | Action |
| --- | --- |
| WASD | Move |
| Mouse | Look |
| Left click (hold) | Shoot |
| Space | Jump (you can climb onto crates) |
| Shift | Sprint |
| Q | Dash (short burst, 1.2s cooldown) |
| F | Toggle fly (Space rises, C sinks; burns fuel, recharges on the ground) |
| R | Reload |
| 1 / 2 or scroll | Switch rifle / sniper |
| Right click (hold) | Scope in (sniper) |

Survive endless waves of box monsters. Red ones charge you, purple ones are tougher, and green **spitters** keep their distance and lob glowing orbs (they swell and glow right before firing — strafe or dash to dodge). After each wave, press 1, 2 or 3 to pick one of three random upgrades; they stack for the rest of the run. Kills sometimes heal you.

**Weapons:** the rifle is full-auto with 12 rounds. The sniper has 5 rounds, kills anything in one shot, and pierces through lines of enemies, but it fires slowly and is inaccurate unless scoped.
