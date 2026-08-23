# Emergence-of-Life-Conway-s-Game-of-Life
A NetLogo implementation of Conway's Game of Life, built as an intro to agent-based modeling. Simple Instructions leading to Emergence of Complex Patterns. 

## WHAT IS IT?

This is a model of Conway's Game of Life, a cellular automaton where simple local rules produce complex, emergent patterns. Each patch is either alive (green) or dead (black), and the grid evolves generation by generation based on how many living neighbors each patch has.

## HOW IT WORKS

Each patch counts its 8 neighbors. Rules applied each generation:
- A live patch with fewer than 2 or more than 3 live neighbors dies.
- A live patch with 2 or 3 live neighbors survives.
- A dead patch with exactly 3 live neighbors becomes alive.
All patches update simultaneously, based on the same previous generation.
