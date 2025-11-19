# Airline Crew Scheduling — Backtracking (Lab Assignment 4)

**Course:** Design and Analysis of Algorithms Lab (ENCA351)  
**Author:** DOLLIE 
**Instructor:** Dr. Aarti

## Project overview
This repository contains a backtracking & constraint satisfaction solution for a simplified Airline Crew Scheduling problem. The goal is to assign flights to fixed crew members while ensuring no overlapping flights and a minimum rest time between flights.

## Contents
- `crew_scheduling_notebook.ipynb` — Jupyter notebook with code, plots, and explanations.
- `crew_scheduling.py` — Optional script version of the solver.
- `requirements.txt` — Python packages.
- `images/` — Saved plots (Gantt charts, scaling graphs).

## How to run (Google Colab recommended)
1. Open `crew_scheduling_notebook.ipynb` in Google Colab.
2. Run the cells sequentially. Install dependencies where prompted, e.g. `!pip install memory-profiler`.
3. Edit the `flights` and `crew_members` lists to test different inputs.
4. Use the scaling experiment cell to profile runtime vs number of flights.

## Notes on complexity and limitations
- This approach uses exhaustive search (backtracking). Time complexity is exponential (practical only for small n).
- For real-world scheduling with many flights and constraints, recommend using:
  - Heuristics (greedy, local search)
  - Integer programming (PuLP, OR-Tools)
  - Constraint solvers (OR-Tools CP-SAT, z3)

## Citations / References
- CLRS — _Introduction to Algorithms_
- OR-Tools, PuLP documentation

