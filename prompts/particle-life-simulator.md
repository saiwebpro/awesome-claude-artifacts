# Particle Life Simulator

**Category:** Creative / Generative Art
**Complexity:** 🟡 Medium
**Live demo:** _(add your reproduction link here)_
**Model used:** Claude Sonnet

## What it does

A canvas-based particle simulation where different "species" of particles attract or repel each other based on a randomized rule matrix, producing emergent, organic-looking motion (cells, swarms, orbits) purely from simple pairwise physics rules.

## The prompt

```
Build a particle life simulation in a single HTML file using canvas.
Rules:
- 4 particle "species" with different colors
- Each species has an attraction/repulsion value toward every other species
  (including itself), randomized on load
- Particles should move based on the sum of forces from nearby particles
- Add a "reshuffle rules" button that randomizes the attraction matrix
  and restarts the simulation
- No external libraries, no dependencies, single file
- Aim for satisfying, organic-looking emergent motion, not just chaos
```

## Follow-up refinements

```
1. "The particles are moving too fast and flying off screen, add
   velocity damping and wrap-around edges"
2. "Add a subtle trail effect behind each particle so the motion
   reads more clearly"
3. "Let me click and drag to add a temporary repulsion point where
   I click, like a mouse-scare effect"
```

## Why this worked

- **Explicit constraints up front** ("single file," "no dependencies") stopped Claude from reaching for a physics library that wouldn't be available in the artifact sandbox.
- **Describing the *feel* of the desired output** ("satisfying, organic-looking," not just "random") steered the parameter ranges Claude chose for the force calculations — vague requests tend to produce visually chaotic, less pleasing results.
- **Iterating in small, single-purpose follow-ups** (damping, then trails, then interaction) kept each diff small enough that Claude didn't regenerate the whole simulation from scratch and accidentally break working parts.

## Screenshot / GIF

<!-- Add a GIF of the simulation running here -->
