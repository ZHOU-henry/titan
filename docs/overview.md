# Overview

Kinema is Duckermind's umbrella for embodied world models and physical AI.

It merges the old two-project split into one coherent program:

- `Titan` handles long-horizon embodied agency, world-model architecture,
  hardware exposure, and safety framing
- `Physis` handles simulator-first engineering, perception, control, ROS
  runtime, and dataset discipline

## Program Thesis

Embodied intelligence should not be split into one repo that dreams about
agency and another that only talks about modules.

The serious path is to hold four things together:

- embodiment
- world modeling
- simulator-first engineering
- safety and control

## What Kinema Should Produce

- a cleaner portfolio story for embodied AI work
- an engineering map from simulator to runtime to physical deployment
- a research map from perception and control up to long-horizon agency
- explicit interfaces between practical framework work and longer-range machine
  intelligence questions
