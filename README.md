# Training a quadcopter how to fly using Reinforcement Learning

We design a four-rotor quadcopter agent which learns to takeoff and reach a target position. For training the agent, we use the DDPG algorithm (Deep Deterministic Policy Gradient) which implements an actor-critic framework and works well for continuous action spaces

## Documentation

### Theory
---
The agent implementation is based on the DDPG algorithm ([DDPG Paper](https://arxiv.org/pdf/1509.02971.pdf)) which was based on DPG and DQN algorithm. More details can be obtained on their respective papers:
* Deterministic Policy Gradient: [DPG Paper](http://proceedings.mlr.press/v32/silver14.pdf)
* Deep Q-networks: [DQN Paper](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)

### Installation
---
* Install jupyter notebook to open the main file. For new users, its recommended to install Anaconda from [here](http://docs.anaconda.com/anaconda/install/)
* Navigate to the specific folder and clone the repository using the following command:
    ```
    git clone https://github.com/jsarneja/teaching_a_quadcopter.git
    ```
* Open the jupyter notebook `Quadcopter_Project.ipynb`

## Contributing
---
We love pull requests from everyone. Here are some ways you can contribute:
* by reporting bugs
* by suggesting new features
* by writing or editing documentation
* by closing [issues](https://github.com/jsarneja/teaching_a_quadcopter/issues)