# Gym-environment---OpenAI---Frozen-Lake
# 🧊 FrozenLake: Introduction to Control with Learning

This repository contains a Jupyter Notebook (`Ido_FrozenLake_Tutorial_Assignment.ipynb`) that serves as a hands-on tutorial and implementation of fundamental Reinforcement Learning (RL) algorithms. 

The project uses the classic **FrozenLake-v1** environment from OpenAI Gym to demonstrate how dynamic programming techniques can be used to solve Markov Decision Processes (MDPs).

## 📖 Project Overview

In the FrozenLake environment, an agent navigates a 4x4 grid from a starting point (Start) to a target location (Goal) while avoiding holes. The environment can be slippery (stochastic) or non-slippery (deterministic). In this notebook, we utilize a non-slippery variant to build foundational intuition for core RL concepts.

The notebook walks through the following key Reinforcement Learning methodologies:
1. **Environment Exploration:** Understanding state spaces, action spaces, and transition dynamics (`env.P`).
2. **Policy Evaluation:** Calculating the state-value function $V^\pi(s)$ for a given policy using the Bellman Expectation Equation.
3. **Policy Improvement:** Generating a new, greedy policy based on the evaluated value function.
4. **Policy Iteration:** Alternating between evaluation and improvement until the optimal policy is found.
5. **Value Iteration:** Directly computing the optimal policy using the Bellman Optimality Equation.

## 🛠️ Technologies & Dependencies

To run this notebook, you will need Python installed along with the following libraries:

* `numpy` - For matrix and array operations
* `gym` - OpenAI Gym for the FrozenLake environment
* `matplotlib` - For plotting and visualizing the agent's movement
* `pygame` - Used by Gym for environment rendering
* `IPython` - For inline display clearing and rendering in Jupyter

You can install the required dependencies using pip:
```bash
pip install numpy gym matplotlib pygame ipython
