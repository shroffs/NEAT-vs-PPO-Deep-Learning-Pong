# NEAT-vs-PPO-Deep-Learning-Pong-
Have NEAT and PPO compete against each other in games of pong.

## Road Map
1. create preprocessing for observations
2. implement and train PPO
3. implement and train NEAT
4. create envirnoment where 2 agents can play
5. see which algorithm can outplay the other

## Proximal Policy Optimization
PPO is policy optimization algorithm that using a standard Deep-RL flow with a special objective function that prevents policy updates from being too large and causing performance collapse. 
![PPO Objective Function](PPOLoss.png)

