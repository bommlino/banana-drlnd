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
This project requires **Python 3.6.10** or higher, the Banana Collector Environment (see *Getting Started*) and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Torch](https://pytorch.org)
- [UnityAgents](https://github.com/Unity-Technologies/ml-agents)
- [OpenAI Gym](https://gym.openai.com)

See also the [Udacity Deep RL instructions page] https://github.com/udacity/deep-reinforcement-learning#dependencies

For the environment, you'll need the pre-built environment from Udacity:

### Getting Started

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.


### Run
In a terminal or command window, navigate to the top-level project directory `banana-drlnd/` (that contains this README) and run the following command:

```shell
$ jupyter notebook
```

This will open the Jupyter Notebook in your browser which you can use to explore and reproduce the experiments that have been run. 


### License
The contents of this repository are covered under the [MIT License](LICENSE).
