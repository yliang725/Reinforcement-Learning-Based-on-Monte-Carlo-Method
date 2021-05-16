# Reinforcement Learning Based on Monte Carlo Method (gym API FrozenLake8x8-v0)  

This program is to solve the FrozenLake8x8 with the MC control method.  
In this program, On-policy First Visit Monte Carlo Control was implemented on both none-slippery and slippery FrozenLake8x8.  
  
major parameters:  
  n_episodes = 500000  
  current_epsilon = 1.0  
  max_epsilon = 1.0  
  min_epsilon = 0.001  
  decay_rate = 0.0001  
  
After 500000 episodes, the results show that none-slippery FrozenLake8x8 scored 0.9794 and slippery FrozenLake8x8 scored 0.3113.  

The Jupyter notebook was compiled on Anaconda and Python 3.8 environment.  

https://gym.openai.com/envs/FrozenLake-v0/  
