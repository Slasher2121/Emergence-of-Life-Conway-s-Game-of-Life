# Emergence of Life

A NetLogo implementation of Conway's Game of Life, built as an intro to agent-based modeling. Simple instructions leading to emergence of complex patterns.

## What this is

Every cell (patch) on the grid is either alive or dead. Each generation, cells live, die, or are born based on how many living neighbors they have — four simple rules applied to every cell simultaneously. From this, complex, self-organizing patterns emerge: stable shapes, oscillating patterns, and even patterns that travel across the grid (like the glider).

## How to run it

1. Download and install [NetLogo](https://ccl.northwestern.edu/netlogo/) (free)
2. Download `game-of-life.nlogo` from this repo
3. Open it in NetLogo
4. Click **setup** to randomly seed the grid, or **setup-glider** to load a known moving pattern
5. Click **go** to watch it evolve

## What to look for

- Random density (~30%) tends to settle into stable "still life" shapes and oscillating patterns after enough generations
- The glider pattern moves diagonally across the grid indefinitely, without ever changing shape — a clean example of emergent, deterministic motion arising from simple local rules
