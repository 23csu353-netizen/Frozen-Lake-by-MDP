Frozen Lake MDP – Value Iteration (Python + Tkinter GUI)

This project is a simple implementation of the Frozen Lake problem using Markov Decision Process (MDP) and Value Iteration. A graphical interface is created using Tkinter to visualize the lake grid, safe tiles, holes, start, goal, optimal policy arrows, and agent movement with slip probability.

Features

• Value Iteration
• Computes the optimal value function
• Calculates the best policy for each state
• Uses discount factor and slip probability

• Tkinter GUI
• Displays grid with colors:

S: Start

F: Frozen

H: Hole

G: Goal
• Shows arrows for optimal actions
• Blue circle represents the agent

• Interactive Controls
• Step – Move agent one step
• Auto Run – Agent moves automatically
• Reset – Restart the simulation

Grid Layout (4×4)

S F F F
F H F H
F F F H
H F F G

Start: Top-left
Goal: Bottom-right
Slip Probability: 10%
Holes: Red tiles

How It Works

The program performs Value Iteration on the grid.

Computes expected reward for each state.

Extracts the optimal policy.

GUI displays the grid and arrows.

Agent moves according to the policy, with slip risk.

Technologies Used

• Python
• Tkinter (GUI)
• MDP / Value Iteration
• Random module

How to Run

Install Python 3.x

Save your code as: frozen_lake_mdp.py

Run using the command:

python frozen_lake_mdp.py

Credits

Made for understanding Reinforcement Learning, MDP, and Value Iteration with a simple visual simulation.
