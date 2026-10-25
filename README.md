# Neon Yokochō

A calm night stroll through a rain-soaked, neon-lit Tokyo back alley. Ramen counters, izakaya lanterns, a 24h konbini, vertical kanji signs, passers-by with light-up umbrellas, holo billboards and flying traffic overhead.

Rain is optional: switch between **Dry**, **Drizzle** and **Downpour**. The street gets wet and shiny, puddles slowly form and reflect the neon (and dry out again when the rain stops).

Live at https://erictempleton1.github.io/cyber-alley/ — Pages serves the `gh-pages` branch, which `.github/workflows/deploy.yml` mirrors from `main` on every push.

Single `index.html`, Three.js loaded from a CDN, no build step.

**Controls:** WASD to walk, Shift to run, drag to look, scroll to zoom, R to cycle rain. On touch, drag on the left half of the screen to walk.

## Neon Circuit + Clover Hill Rally (`/drive/`)

Three levels, picked on the start card (your last choice is remembered):
- **Neon Circuit**: a night street circuit in the neon city.
- **Alpine Pass**: a 1.6 km mountain road that climbs and dips around a central peak: rock faces, an avalanche-gallery tunnel, valley lakes, pines, snowy peaks and mountain goats. Armco on the drop side and a stone wall on the mountain side keep you on the road.
- **Clover Hill Rally**: a gravel stage through the Clover Hill farmland at golden hour: rolling hills the car pitches and rolls over, wind-blown grass, hay bales and chevron boards on the corners, the red barn and silo, the pond, and paddocks of grazing cows and sheep. Loose gravel grip, slower grass off the road, solid trees and bales, dust trails and gravel crunch; the car gets a rally light pod and mud flaps.

Live at https://erictempleton1.github.io/cyber-alley/drive/ (add `?level=rally` or `?level=alpine` to jump straight to a level).

### Neon Circuit details

A night street-circuit driving game in the same neon city, starring a boxy late-80s E30 M3: box flares, trunk wing, quad round headlights and cross-spoke wheels. Live at https://erictempleton1.github.io/cyber-alley/drive/

- **Fully synthesized sound** (no audio files): a 4-cylinder engine built from individual firing pulses through an exhaust-pipe resonance model, rev-limiter bounce, lift-off crackles, gearbox whine (including straight-cut reverse whine), tyre squeal, wind and wall scrapes.
- Weight transfer, tyre grip limits and power oversteer; 5-speed auto or manual; optional stability assist (turn it off to drift).
- Lap timer with last/best (best is saved), minimap, tachometer and digital speedo.
- Wet reflective streets, optional rain (less grip), autopilot attract mode, keyboard / touch / gamepad.

**Controls:** W/S gas & brake (hold S to reverse), A/D steer, Space handbrake, E/Q shift in manual (G toggles), C camera, R reset to track, P paint, U mph/km/h.
