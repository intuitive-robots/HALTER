# HALTER

**From Rollout to Reset: A Graph-Based Harness for Autonomous Long-Horizon
Manipulation Evaluation**

HALTER scores a long-horizon manipulation rollout on real hardware and restores
the scene for the next one without a human. It builds a spatial scene graph
online from RGB-D keyframes, and an LLM reasons over that graph to score the
rollout, to plan a reset over a library of learned atomic reset skills, and to
verify that the reset succeeded.

Project page: <https://intuitive-robots.github.io/HALTER/>

## Repository layout

- `main` — the codebase.
- `gh-pages` — the project page. Its source lives in `website/`, and the built
  site sits at the branch root, which is what GitHub Pages serves.

## Status

Code release is in progress.
