# Kinema - Embodied World Models And Physical AI

Open umbrella program for machine intelligence that has to sense, simulate,
decide, and act in the physical world.

Chinese shorthand: `具身世界模型`

## Position

Kinema consolidates Duckermind's embodied stack into one umbrella so the work
is no longer split across disconnected MVPs.

## Repository Host

Kinema is now hosted directly in the original `titan` repository.

The former standalone Titan repository content has been moved into
`subprojects/titan/`, and the former standalone Physis repository content has
been copied into `subprojects/physis/`.

## Subprojects

- `Titan`
  - long-horizon embodied agency, world models, hardware framing, and safety
- `Physis`
  - simulator-first physical AI framework across perception, control, runtime,
    and data

## Why This Umbrella Exists

- world models without a practical simulator and runtime stack stay abstract
- simulator and robotics frameworks without a strong agency and safety thesis
  stay shallow
- one umbrella makes the research layer, framework layer, and future system
  layer legible as one program

## Local Structure

- `docs/`
- `subprojects/titan/`
- `subprojects/physis/`

The subprojects are now embedded directly in this repository so future cleanup
of redundant MVP repositories does not orphan files.
