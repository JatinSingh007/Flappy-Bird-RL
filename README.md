# Flappy Bird Reinforcement Learning Project
## Overview
This project develops and evaluates two reinforcement learning (RL) agents – SARSA (λ) and Monte Carlo – to autonomously play the game Flappy Bird. The objective is to assess their learning rates, identify any limitations, and determine which agent better masters the game strategy.

### Author
Jatin Singh
MS Data Science and Business Analytics – ESSEC x CentraleSupelec
GitHub: salsa
### Environment
Training: TextFlappyBird-v0 (text-based, provides distance from pipes)
Testing: TextFlappyBird-screen-v0 (full-screen visual rendering)
### Implementation
Both agents were implemented using predefined hyperparameters and trained with an epsilon-decay strategy for optimal exploration and exploitation. Extensive hyperparameter tuning was conducted to enhance performance. Training involved 10,000 episodes, with further training on optimized parameters for in-depth analysis.

### Model Evaluation
Performance was assessed based on the following criteria:

Training Performance: Rewards and scores during training episodes.
State-Value Functions: Visualization of state valuations.
Convergence Time: Average rewards and scores as a function of the number of training episodes.
Generalization Capacity: Performance adaptability with varying game environment complexities.
Results
### Comparative analysis showed that:

The SARSA (λ) agent learned more quickly but with higher variability in performance.
The Monte Carlo agent demonstrated more consistent learning, with a gradual improvement in performance.
Future Applications
While these agents performed well in the provided text-based environments, additional modifications would be necessary for more complex environments like the original Flappy Bird game, due to continuous space considerations and computational constraints.

### Setup & Usage
Details on setting up the environment and running the agents can be found in Main_Assignment_Code.ipynb. Make sure to install all required dependencies before executing the code.
