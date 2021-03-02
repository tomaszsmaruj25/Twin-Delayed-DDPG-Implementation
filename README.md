# Twin Delayed DDPG Implementation
A project made on the basis of a course on the Udemy platform:  [https://www.udemy.com/course/deep-reinforcement-learning/](https://www.udemy.com/course/deep-reinforcement-learning/)
The entire project was made in Google Collab.

<img src="assets/Ant.gif" width="450" height="300">

## Introduction
The aim of the project was to propose a control based on gain learning algorithms. I decided to implement an architecture that is an extension of the DDPG (Deep Deterministic Gradient Descent) algorithm, i.e. an architecture with an actor and a critic. 
The new architecture is called Twin-Delayed DDPG (TD3). Link to the article: [https://arxiv.org/pdf/1802.09477.pdf](https://arxiv.org/pdf/1802.09477.pdf).

## Architecture

<img src="assets/architecture.png" width="450" height="300">


## Simulation results

<img src="assets/HalfCheetah.gif" width="450" height="300">

<img src="assets/Hooper.gif" width="450" height="300">

<img src="assets/Walker.gif" width="450" height="300">

Bonus:
Unsuccessful simulation related to too short network learning 

<img src="assets/ant_fail.gif" width="450" height="300">
