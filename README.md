# Multi-Agent Simulation: Resource Dynamics and Agent Interactions

Laboratory coursework developed for **Foundations of Economic Cybernetics**.

## Overview
This **NetLogo** project models a multi-agent system consisting of two heterogeneous agent populations interacting in a shared environment with renewable resources, grass patches.

The model highlights key cybernetic system concepts:
1. **Autonomy & Local Rules:** Each agent moves randomly and expends energy at each step (`energy - 1`). When stepping onto a green patch, the agent consumes the resource, gains energy, and turns the patch brown.
2. **Direct Agent Interactions:** Car-shaped agents (`agents2`) that occupy the same space as pedestrian agents (`agents1`) transfer energy to them and change color to yellow.
3. **Environment Regeneration:** Depleted patches have a fixed probability of regenerating over time.
4. **Emergent Behavior & Selection:** Agents whose energy reaches zero are automatically removed from the system (`die`).

## Repository Contents
* `Tema 1 seminar 2 - NetLogo.nlogo` - NetLogo simulation model source code.
* `Tema 1 seminar 2 Bazele Ciberneticii.docx` - Theoretical analysis covering autonomy, complexity, and adaptive behavior.

## How to Run
1. Open the model in **NetLogo**.
2. Click **setup** to initialize the agents and the grid.
3. Click **go** to run the simulation.
