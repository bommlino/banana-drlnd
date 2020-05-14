Banana Deep Reinforcement Learning Nanodegree
===========================

The goal is to train an agent to navigate a world and collect yellow bananas while avoiding blue bananas.
For the environment simulation the Unity Machine Learning Agents Toolkit is used. The simulation is used to visualize the agent as well as to train the agent by taking steps and using the rewards given.


<p align="center"><img src="https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif" alt="Udacity example" width="50%" style="middle"></p>

The description is copied from the Udacity instructions:

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. The state space has 37 dimensions and contains the agent’s velocity, along with a ray-based perception of objects around agent’s forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

- 0 - move forward.
- 1 - move backward.
- 2 - turn left.
- 3 - turn right.

The task is episodic, and to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes. 

The required report is [here](reports/Report.pdf).


### Install
This project requires **Python 3.6.10** or higher, the Banana Collector Environment (follow the instructions to download [here](drlnd/README.md)) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Torch](https://pytorch.org)
- [UnityAgents](https://github.com/Unity-Technologies/ml-agents)
- [OpenAI Gym](https://gym.openai.com)

See also the [Udacity Deep RL instructions page] https://github.com/udacity/deep-reinforcement-learning#dependencies

### Run
In a terminal or command window, navigate to the top-level project directory `banana-drlnd/` (that contains this README) and run the following command:

```shell
$ jupyter notebook
```

This will open the Jupyter Notebook in your browser which you can use to explore and reproduce the experiments that have been run. 


### License
The contents of this repository are covered under the [MIT License](LICENSE).