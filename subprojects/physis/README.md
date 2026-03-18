# Physis - Physical AI Framework

Open-source Physical AI framework with simulator-first discipline.

Chinese shorthand: `物理 AI`

## Portfolio Position

Physis is now one of the two subprojects inside `Kinema`, Duckermind's umbrella
program for embodied world models and physical AI.

Inside Kinema:

- `Physis` owns simulator-first engineering, perception, control, runtime, and
  dataset discipline
- `Titan` owns long-horizon embodied agency, world models, hardware framing,
  and safety

## Stage

Stage 0: architecture and research scaffold.

## Goals

- define a clean simulator-first stack
- establish module boundaries for perception, control, and data
- keep the framework practical enough to evolve into real engineering work

## Structure

- `sim/`
- `perception/`
- `control/`
- `ros2_ws/`
- `datasets/`
- `docs/`

## License And Provenance

- This repository is licensed under `Apache-2.0`.
- Simulator code, models, datasets, and external components must be tracked by original source and license.
- Do not absorb third-party material unless the license clearly permits it.
- See `THIRD_PARTY_CODE_POLICY.md`.
