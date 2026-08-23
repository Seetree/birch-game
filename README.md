# PickUp (Project Birch)

A PC game built with Unity, featuring a cloud-connected leaderboard and a companion React web dashboard.

## Project Overview
* **Engine:** Unity (2022 LTS / 6000)
* **Language:** C#
* **Platform:** PC (Windows)
* **Frontend Dashboard:** React + Vite
* **Design Spec:** See [DESIGN.md](./DESIGN.md) for gameplay rules and leaderboard specs.

## Core Gameplay
Players spawn into custom map layouts, navigate environments, and collect randomly generated hidden items before the timer runs out. High scores and completion times are automatically synced to the global leaderboard.

## Repository Structure
```text
├── Assets/             # Unity game scripts, prefabs, and scenes
├── Packages/           # Unity package dependencies
├── ProjectSettings/    # Engine configuration
├── DESIGN.md           # Game Design Document (GDD) & API specs
└── README.md           # Project landing page