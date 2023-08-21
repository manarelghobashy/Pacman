# Pacman
## Reinforcement Learning
- The notebook in Pacman-group11.rar file.

This project aims to train an AI agent to play the Atari 2600 game "Alien" using reinforcement learning 
techniques. The goal is to navigate through a maze-like environment, collect dots (destroy alien eggs), 
avoid enemies, and utilize power-ups to gain temporary advantages. The Atari 2600 game "Alien" 
serves as an ideal experiment due to its simplicity, well-defined rules, and clear objectives. By tackling 
this project, we can explore the capabilities of AI agents in solving complex real-world problems and 
gain insights into the application of deep reinforcement learning in-game environments.

Problem Formulation
The problem of making a DQN agent solve the Pac-Man game can be formulated as follows:
1. Environment: The environment is represented by the Pac-Man game, which includes the game 
screen (RGB image) and the game state (e.g., Pac-Man's location, enemy locations, remaining 
lives, score, etc.). The agent interacts with the environment by selecting actions from the action 
space.
2. State Space: The state space consists of RGB images of the game screen with a shape of (210, 
160, 3). Each image provides the agent with visual information about the game state, including the 
locations of Pac-Man, enemies, dots, power-ups, walls, and other relevant elements.

4. Action Space: The action space comprises nine possible actions: move up, move down, move 
left, move right, upright, up left, down right, down left, fire, and do nothing. The agent selects actions 
based on the observed state to control Pac-Man's movement and actions in the game.

5. Reward Scheme: The reward scheme is designed to provide feedback to the agent based on its 
performance in the game. Positive rewards are given when the agent achieves objectives such as 
eating dots, power-ups, and advancing to the next level. Negative rewards are assigned for failing 
to achieve objectives, losing lives, or making mistakes that result in a loss of progress or points. 
The agent aims to maximize its cumulative reward over time by making strategic decisions.

In this project, we trained a reinforcement learning agent to play Pac-Man using the DQN 
algorithm with various techniques such as replay buffer, warmup episodes, and window size. 
We conducted several trials with different hyperparameter settings and evaluated the agent's 
performance under varying conditions.




https://github.com/manarelghobashy/Pacman/assets/76270011/4bae1434-0972-4804-aa18-14109775dccf

