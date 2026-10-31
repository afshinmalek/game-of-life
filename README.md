<div align="center">

# 🧬 Conway's Game of Life — Swing GUI

### Java · Swing · Multithreading · Simulation

A Swing GUI for Conway's Game of Life with a threaded generation loop and a user-chosen grid size.

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-5382A1?style=for-the-badge&logoColor=white)
![Simulation](https://img.shields.io/badge/Simulation-6E4C13?style=for-the-badge&logoColor=white)

</div>

## What it does

| Feature | Detail |
|---|---|
| Conway's rules | Cells live, die, and are born by the classic neighbor-count rules |
| Threaded generations | The simulation loop runs on its own thread so the GUI stays responsive |
| User-chosen grid size | Pick the grid dimensions before the simulation starts |
| Swing GUI | Live, visual grid updates as generations advance |

## Run

```bash
javac GameOfLife.java
java GameOfLife
```

## Files

- `GameOfLife.java` — Swing GUI and threaded simulation (164 lines)

> Originally a Java Programming II (CIS 36B) project, extracted here as a standalone repo from [java-algorithms-and-concurrency](https://github.com/afshinmalek/java-algorithms-and-concurrency).
