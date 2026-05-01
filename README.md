# ⚫ Gravity Sink

*An interactive black hole simulator. Move your mouse to create a gravitational pull that sucks in particles. Adjust strength, count, colors, trails. Watch chaos collapse into a swirling vortex.*

---

## What is this?

A physics-based particle toy where your cursor becomes a gravity well. Particles flow toward (or away from) your mouse, leaving glowing trails. Tweak sliders to change the gravitational strength, particle count, trail length, and color schemes. Click to flip attraction into repulsion. Hit "Explode" to scatter everything. It's mesmerizing, meditative, and oddly satisfying.

---

## Features

- **Real-time gravity simulation** — particles accelerate toward/away from cursor
- **Adjustable parameters:**
  - Gravity strength (1–100)
  - Particle count (50–1000)
  - Trail length (0–30 segments)
  - Color mode: Cyan / Magenta / Gold / Rainbow
  - Mouse influence multiplier (0–200%)
- **Attraction/repulsion toggle** — click anywhere to switch
- **Explode button** — instantly blast particles outward
- **Custom cursor** — glowing ring that reflects current mode (pink = attract, cyan = repel)
- **Live stats** — particle count, FPS, sink mass
- **Single HTML file** — no dependencies, instant play

---

## How to Use

1. Open `index.html`
2. Move your mouse around the canvas — watch particles swirl
3. Drag sliders to tweak behavior
4. Click to toggle between **Attract** (particles sucked in) and **Repel** (particles pushed away)
5. Click **Explode Outward** to scatter all particles
6. Click **Reset Particles** to respawn them randomly
7. Try Rainbow mode for maximum visual feast

---

## Technical Notes

- Canvas 2D with per-particle velocity integration
- Soft wall bouncing with dampening
- Trail rendering with alpha fade per segment
- Radial gradient for gravity sink visualization
- Shadow blur for neon glow
- Friction coefficient tuned for smooth motion
- FPS counter for performance monitoring

---

## The Real Story

I wanted something that feels like playing with a magnetic field. The particles have a mind of their own until your cursor exerts influence. The attraction/repulsion toggle lets you be both a black hole and a supernova. The trails give it that "flow field" aesthetic that's super hypnotic.

Also: the color modes each evoke a different vibe. Cyan feels digital, magenta feels cyberpunk, gold feels regal, rainbow feels chaotic-good.

---

*Made with ✨ and some serious orbital mechanics during a heartbeat build cycle.*

**Repo:** https://github.com/Kiloooai/gravity-sink
