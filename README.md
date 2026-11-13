# 🦥 Sloth's World

A cosy little 3D browser game: guide a very unhurried sloth around its room and step onto the trampoline for automatic, progressively higher bouncing.

## Play

- **WASD** or **arrow keys** to move.
- On a phone or tablet, use the **virtual joystick**.
- Walk onto the **trampoline** and the sloth bounces automatically.
- Keep steering while airborne to hop off the trampoline.

## Run

No build step and no game engine installation required. This prototype is a single static `index.html` using [Three.js](https://threejs.org/) from a CDN.

For local development, use a static HTTP server (e.g. `python3 -m http.server 8000`) and open `http://localhost:8000`.

To publish, connect this repository to Netlify with **no build command** and the **repository root** as the publish directory. Alternatively, enable GitHub Pages for `main` / `/ (root)` in repository settings.

## Prototype features

- Orthographic, Zelda-inspired camera and lighting
- Cute GLB sloth character (`cute_sloth.glb`) and a decorated room
- Soft shadows, furniture, plants and a couple of suitably slow motivational signs
- Floor-inset trampoline with physics-based bounce and air steering (no step to climb)
- Collision detection for room boundaries, armchair, bookshelf and plant pots, with wall sliding
- Mobile touch controls and responsive layout

Built as a small, approachable foundation for further iterations.
