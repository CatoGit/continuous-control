# Continuous Control using DDPG

In this project, a double-jointed arm learns to move to the desired target location. The arm itself is a single agent. 
The agent's goal is to keep its hand in the green sphere. It receives +0.1 reward for every step where this is the case. 
To maximize reward the agent has to keep its hand in the green sphere for as long as possible.

The environment is solved once the agent achieves an average of +30 reward over 100 episodes.

## Motivation

This learning approach can be relevant to teaching real-world robots how to reach target locations in the environment. 
Similar to this: 
[RL Robot Arm Learning](https://www.youtube.com/watch?v=ZVIxt2rt1_4)
## State and action space (Continuous)

The observation space consists of 33 dimensions corresponding to position, rotation, velocity and angular velocities of the arm. 
Each action consists of a vector with four numbers (each number has a value between -1 and 1). 
These four numbers correspond to the torque that can be applied to the agent's joints.

 
## Instructions

1. Follow the instructions [here](https://github.com/udacity/deep-reinforcement-learning#dependencies) to install all dependencies. 

2. Download the environment for your operating system from one of these links:  
    * Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
    * Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
    * Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
    * Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in the `continuous-control/` folder and unzip it.

3. Train your DDPG agent using `ContinuousControl.ipynb`. 

4. Watch your trained agent. Enjoy!
