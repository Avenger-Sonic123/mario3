# Pose-Controlled Mario — Later Snapshot

A related snapshot of the webcam-controlled platformer with expanded sprite resources.

**Repository created:** 2023-07-31  
**Project status:** Learning project / historical snapshot  
**Earliest recorded commit (author date):** 2023-07-31

## Features and implementation

- PoseNet nose tracking.
- Platformer movement and collision functions.
- Game-state and scoring logic.
- Bundled sprites and audio.

## Technologies

HTML, CSS, JavaScript, Bootstrap, jQuery, p5.js, p5.play, p5.sound, ml5.js, PoseNet.

## Project structure

| File | Purpose |
| --- | --- |
| [`characters_environment.js`](characters_environment.js) | Platformer engine and game-state functions |
| [`index.html`](index.html) | Main page and user interface |
| [`main.js`](main.js) | Project-specific JavaScript |
| [`p5.min.js`](p5.min.js) | JavaScript implementation |
| [`sprites.js`](sprites.js) | Sprite and environment setup |
| [`style.css`](style.css) | Page styling |

Key functions in the source:
- `characters_environment.js`: `game()`, `startGame()`, `changeGameStatud()`, `instializeInSetup()`, `initializeCharacterStatus()`, `instializeInDraw()`, `getCoins()`, `coinVanish()`, among others.
- `main.js`: `gotPoses()`.
- `sprites.js`: `setSprites()`, `setSpriteGroups()`, `loadStaticObjects()`, `loadAnimatedObjects()`, `loadPlatforms()`, `MarioAnimation()`.

## Run or explore locally

```bash
git clone https://github.com/Avenger-Sonic123/mario3.git
cd mario3
python -m http.server 8000
```

Open [http://localhost:8000](http://localhost:8000) in your browser. The local server requires Python 3; browser-based dependencies may also require internet access.

Allow camera access and follow the on-page instructions if initialization succeeds.

## Current status and limitations

This snapshot shares substantial code with mario2; no new gameplay feature is claimed without evidence. Runtime and asset rights are unverified.

## Related project snapshots

Other repositories in this project family:
- [Mario](https://github.com/Avenger-Sonic123/Mario) — repository created 2023-07-31
- [mario2](https://github.com/Avenger-Sonic123/mario2) — repository created 2023-07-31

## Attribution

This repository contains game/example code and assets. Original authorship and asset licenses have not been established; preserve existing source credits and verify rights before redistribution.

---

Source reference: [`f09f201e`](https://github.com/Avenger-Sonic123/mario3/tree/f09f201ee2f6dd586ddcfd8a674d2c080036535b) on `main`, verified against GitHub on 2026-11-24. Documentation is based on static source review; runtime behavior has not been tested.
