# We Wash PL8s

A 2D dish-washing game written in C with the CProcessing library. Scrub the dirt off each plate before the timer runs out, earn money for every clean plate, and spend it on upgrades in the shop.

First-year team project at Singapore Institute of Technology / DigiPen Institute of Technology Singapore, Oct to Dec 2025.

<img width="1592" height="887" alt="image" src="https://github.com/user-attachments/assets/029ed91d-812c-497a-b89d-00e68aa60838" />


## Features

- Scrub dirt off plates with the sponge, soap, faucet and bubble gun.
- A countdown timer that gives you more time for every plate you clear, and blinks when time is running out.
- A shop for upgrades, paid for with the money you earn.
- Days, a leaderboard, a tutorial and a game over screen.

## What I worked on (Dan Ng)

- **Sponge mechanics** (`src/entities/sponge.c`): equipping and unequipping the sponge, scrubbing dirt by dragging the mouse, and sponge upgrades.
- **Timer** (`src/systems/timer.c`): the countdown, extra time for each cleared plate, and the warning blink near the end.
- **Shop**: the shop menu and UI, linked to the money system.
- **Scenes**: the splash screen and the game over scene.

## Controls

| Action | Input |
|---|---|
| Pick up / put down the sponge | Hover over it and press E |
| Scrub | Hold the left mouse button and drag |
| Menus | Mouse |

## Build and run

You need Windows and Visual Studio 2022 with the **Desktop development with C++** workload.

1. Clone the repo.
2. Open `Game_Project.sln`.
3. Build and run (F5).

CProcessing is included in `Extern/CProcessing`.

## Team



Original repository: [limlz/Game_Project](https://github.com/limlz/Game_Project)
