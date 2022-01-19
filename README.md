# CAPTAIN notebooks

Here we provide Jupiter notebooks demonstrating the main functionalities implemented in CAPTAIN. The program  uses reinforcement learning (RL) to optimize a conservation policy within the constraints of a limited budget and targeting a specific policy objective, such as the minimization of species loss or the maximization of protected area.  

The main output of the policy is the identification of areas of priority for conservation and solutions from different policy objectives can be used to quantify the tradeoffs among biodiversity protection, economic loss, area loss and other variables. 

The RL framework optimizes models based on simulated natural systems. these models can then be applied to empirical datasets. 

There are 4 main functionalities implemented in the program and described in the notebooks:

1. [Simulation of a natural system](https://github.com/captain-project/notebooks/blob/main/Biodiversity_simulation.ipynb) and its evolution under climate change and increasing anthropogenic disturbance
2. [Optimization of a policy using RL](https://github.com/captain-project/notebooks/blob/main/Policy_optimization.ipynb)
3. [Application of a trained policy on simulated datasets](https://github.com/captain-project/notebooks/blob/main/Policy_implementation.ipynb) 
4. [Application of a trained policy on empirical data](https://github.com/captain-project/notebooks/blob/main/Analysis_empirical_data.ipynb)