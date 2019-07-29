# Udacity Reinforcement Learning
Solutions to the projects Udacity's Deep Reinforcement Learning Nanodegree program.

## Project Details
Train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

## Getting Started
Download the Banana environment: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

## Instructions
- **DQN**: Run solution-dqn.ipynb
- **Double DQN**: Run solution-double-dqn.ipynb
- **Dueling Double DQN**: Run solution-duel-dqn.ipynb