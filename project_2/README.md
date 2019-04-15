# Project 2: Continuous Control

## Project Details

For this project, the target is to train an agent to move a double-jointed arm to target locations.

A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

To train the agent, we use 20 identical copies of the agent to speed up the process. Each copy has its own copy of the environment.

The task is episodic. To solve the environment, the agents must get an average score of +30 (over 100 consecutive episodes, and over all agents). Specifically,

* After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 20 (potentially different) scores. We then take the average of these 20 scores.
This yields an average score for each episode (where the average is over all 20 agents).
* The environment is considered solved, when the average (over 100 episodes) of those average scores is at least +30.

## Getting Started

Install the Unity Machine Learning Agents (ML-Agents) v0.4 to run the project notebook. The details of the environment installation can be found from https://github.com/Unity-Technologies/ml-agents. To set up the environment in local machine, follow the following link: https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Getting-Started-with-Balance-Ball.md.


## Instructions

After getting the environment ready, edit the path of the data and run the entire project notebook file. 
