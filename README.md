# Reinforcement-Learning-Agent-for-Learning-Addition
This project implements a reinforcement learning agent to solve simple addition problems. The agent learns to select the correct number to add to the first number in an addition problem using Q-learning. Visualization includes the agent's learning progress and its problem-solving process.

#logic behind the project:

## Environment Setup:

Define an environment where the agent learns to solve simple addition problems.
The state represents the current addition problem (two random numbers).
The action represents the number the agent selects to add to the first number.
The reward is +1 for a correct solution and -1 for an incorrect solution.

# Agent Setup:

Implement a Q-learning agent to learn to solve addition problems.
The agent uses a Q-table to store action-values for each state-action pair.
Choose an action using an epsilon-greedy policy to balance exploration and exploitation.

## Training:
Train the agent by interacting with the environment.
Update the Q-values using the Q-learning update rule based on the reward received.
Repeat this process for a specified number of episodes.

## Testing:

Test the trained agent on a set of addition problems.
Print each problem along with the action the agent takes at each step.
Evaluate the agent's performance based on the average reward obtained.

## Visualization:

Visualize the agent's learning progress by plotting the average reward over episodes.
Plot the Q-values for each action in different states to show the agent's learning.
Print the agent's problem-solving process to observe its decision-making.
