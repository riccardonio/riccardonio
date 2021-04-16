# Project Navigation #
Teach an agent how to collect yellow banans

### Environment ###
This project uses the Unity Environment "Banana", a square world disseminated with blue and yellow bananas.

The agent get a reward of +1 for every collected yellow banana, while he gets -1 when a blue banana is collected.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward.
* 1 - move backward.
* 2 - turn left.
* 3 - turn right.

The goal is to collect as many yellow bananas as possible, while avoiding blue bananas.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.

### Getting started

The required packages are listed in the file _requirements.txt_

In particular these packages are required to run the script:
* pytorch
* unityagents
* numpy

The app _Banana.app_ should also be in current working folder.

### Instructions

To run the code in the repository open the jupyter notebook _Navigation.ipynb_




