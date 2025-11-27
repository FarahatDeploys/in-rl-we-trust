<<<<<<< HEAD
# in-rl-we-trust
A curated collection of Reinforcement Learning projects and experiments. This repository brings together multiple small, self-contained RL implementations, from classic control problems to modern deep RL techniques. Designed as a flexible playground for learning, prototyping, and comparing algorithms
=======
A collection of interactive environments + RL agents that learn to master them.

Welcome to in-rl-we-trust, a repository that explores how Reinforcement Learning (RL) agents can learn, adapt, and solve a variety of custom-built game environments.

This repo is built around a simple idea:

Make small, intuitive games — then teach machines how to beat them.

Perfect for students, researchers, and anyone who wants a hands-on playground for RL.

🎮 What’s Inside
✔ 1. Custom Pygame Environments

Lightweight, easy-to-understand environments built using Pygame.
Each environment is designed to be:

Simple for humans

Non-trivial for RL agents

Fully customizable

Deterministic or stochastic depending on the experiment

✔ 2. RL Agent Implementations

Each environment comes with one or more RL agents, such as:

Q-Learning

SARSA

Deep Q-Networks (DQN)

Policy Gradient Agents

Actor–Critic Variants

Custom planners or heuristic agents

Agents are provided with:

Training scripts

Evaluation scripts

Reward analysis

Saved models

✔ 3. Tutorials

A step-by-step guide on:

How to build a Pygame environment

How to define a state space and action space

How to create reward functions

How to train RL agents on your environment

How to visualize and log training performance

🕹 Current Environments
1️⃣ Cart Game

A simple left–right movement game where:

The player moves a cart horizontally

The goal is to collect objects for points

Score increases with movement + object collection

The environment supports boundary conditions, collision detection, and random object spawning

RL challenges:

Sparse reward (objects)

Continuous movement

Exploration vs exploitation

Time-penalized movement strategies

📁 Folder: cart_game/

🚧 Coming Soon

More environments will be added, such as:

Inverted Pendulum Simulator

Pong-like RL Playground

Gridworld Variants

Obstacle Avoidance Environment

Autonomous Driving Mini-Sim

Multi-agent environments

And agents for each.


📦 Repository Structure
in-rl-we-trust/
│
├── cart_game/
│   ├── cart_game.py
│   ├── agent_dqn.py
│   ├── agent_qlearning.py
│   ├── README.md
│   └── assets/
│
├── pendulum_game/
│   └── (coming soon)
│
├── utils/
│   ├── replay_buffer.py
│   ├── neural_networks.py
│   ├── wrappers.py
│   └── plotting.py
│
├── notebooks/
│   ├── Training_Analysis.ipynb
│   └── Agent_Visualization.ipynb
│
└── README.md


📩 Contact

If you're interested in robotics, RL, or simulations, feel free to reach out.
Happy to collaborate or discuss ideas!
>>>>>>> d996de7 (developed basic cart, within the cart pole balancer !)
