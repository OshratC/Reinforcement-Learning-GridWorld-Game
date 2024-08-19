# Reinforcement Learning GridWorld Game
GridWorld is a game where an agent learns to navigate and collect rewards using reinforcement learning (SARSA and Q-Learning). The environment includes slippery cells, coins, an end cell, and a moving police officer to avoid. The game features a real-time Pygame UI and graphical display of learning progress.

## Customization

You can customize the GridWorld environment by adjusting parameters such as:
- **Grid size**: Define the size of the grid.
- **Coins**: Set the number of coins and their positions on the grid.
- **Slippery cells**: Define cells where the agent might slip and move randomly.
- **Penalty cells**: Add cells that give penalties when the agent steps on them.
- **End cell**: Set the goal position that the agent needs to reach.

Additionally, you can modify learning parameters such as:
- **Alpha (learning rate)**: Controls the step size for learning.
- **Gamma (discount factor)**: Determines the importance of future rewards.
- **Epsilon (exploration rate)**: Adjusts the balance between exploration and exploitation during training.

## Features

- **Dynamic Environment**: The environment includes movable elements like police officers and slippery cells.
- **Reinforcement Learning Algorithms**: Choose between SARSA and Q-Learning for agent training.
- **Real-time Visualization**: Observe the agent's progress and the learning curve in real-time via the Pygame interface and dynamic graphing.
- **Interactive UI**: Select grid positions and parameters through an intuitive graphical interface.

