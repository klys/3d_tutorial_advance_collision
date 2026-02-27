# 3d_tutorial_advance_collision

GameMaker Studio 1.x tutorial project focused on **advanced 3D collision handling**.

This appears to be part of a 3D tutorial series and includes custom collision script logic plus a minimal playable scene.

## Project

- Main file: `3dProject_Tutorial_1.project.gmx`
- Engine format: **GMX** (GameMaker Studio 1.x)

## Included Resources

- `scripts/place_meeting_ext.gml` — custom collision helper/extension logic
- Objects:
  - `obj_player`
  - `obj_camera`
  - `par_solid` (solid parent)
- Room:
  - `rooms/room0.room.gmx`
- Basic sprite/background assets for test geometry and player representation

## How to Open

1. Install **GameMaker: Studio 1.x**.
2. Open `3dProject_Tutorial_1.project.gmx`.
3. Run `room0` from the IDE.

> Note: GMX projects may require migration for GMS2+ and can break without manual fixes.

## Purpose

Use this repo as a reference for:

- 3D movement + camera setup in legacy GML workflows
- collision checks against parent solid objects
- tutorial-scale experimentation before integration into larger projects

## Suggested Next Improvements

- Add controls section (keyboard/mouse mappings)
- Document `place_meeting_ext.gml` behavior with examples
- Add screenshot/GIF of room0 running
