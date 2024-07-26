# Connect4
This repository contains my solutions to the ConnectX challenge on Kaggle. The goal is to create agents that can play the ConnectX game efficiently using various strategies and algorithms.

I implemented the following agents:
* **Naive Agent:** Selecting winning moves and blocking opponents winning moves, otherwise random
* **OneStep Agent:** Looking ahead one step and selecting moves based on heuristic
* **nStep Agent:** Looking ahead n steps and selecting moves based on heuristic with minimax algorithm
* **DeepRL Agent:** Deep Reinforcement Learning agent that was trained against a random agent, the naive agent and the OneStep agent.

Competing agains each other, the nStep agent outperformed the other agents. Especially the DeepRL agent struggled to find winning strategies due to unsufficient training. However, in the challenge leaderboard the oneStep agent reached with 770 points and rank 50 the best result.

## Source
www.kaggle.com/competitions/connectx/overview/$citation
