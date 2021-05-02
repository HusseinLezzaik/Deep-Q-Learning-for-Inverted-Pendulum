# Deep Q-Learning for Inverted Pendulum
Implemented Q-Learning and Deep Q-Learning to learn a controller that balances an Inverted Pendulum. The Reinforcement Learning simulation enviroment used for the agent i.e the Inverted Pendulum is Gym from OpenAI. And it learned how to change its action upon each observation to maximize it's reward, which is in this case to balance the rod.

## Overview of the Repository
The major content of this repo is:

* `cartpole_deepqlearn.py`: contains the code for the deep q-learning model for the cart pole.
*  `cartpole_qlearn.py`: contains the code for the q-learning model for the cart pole.

## Getting Started
1.  Clone repo: `git clone https://github.com/HusseinLezzaik/Deep-Q-Learning-for-Inverted-Pendulum.git`

2.  Install dependencies:
    ```
    conda create -n inverted-pendulum python=3.7
    conda activate inverted-pendulum
    pip install -r requirements.txt
    ```

## Acknowledgements
Original code: https://github.com/swagatk/RL-Projects-SK

## Contact
* Hussein Lezzaik : hussein dot lezzaik at gmail dot com
