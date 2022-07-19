# Cliff-Walking
This repo contains the code to solve the cliff-walking environment using Sarsa &amp; Q-learning

# Description
![alt text](https://github.com/kwquan/FrozenLake_V1/blob/main/cliff_walking.png)

In this notebook[Cliff_Walking.ipynb], we shall solve the environment Cliff Walking using Sarsa & Q-learning. \
Aim: Cliff Walking involves moving an agent from Start(S) to Goal(G) in the shortest time possible. 
     If agent steps onto any of the cliff states, it goes to initial starting position with a reward of -100. \
     Episode terminates if agent reaches goal state[G] \
Gridspace: 4x12 \
Action space: 0[UP], 1[RIGHT], 2[DOWN], 3[LEFT] \
Rewards:
1) Each timestep: -1
2) Reach cliff(C): -100

# Documentation
https://www.gymlibrary.ml/environments/toy_text/cliff_walking/
