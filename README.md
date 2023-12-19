# Project-Planning-Assignment Reinforcement Learning
## Overview
Welcome to the Custom Gym Environment for our Logistic Bot Simulation! This project aims to provide a versatile and customizable environment for training intelligent agents, specifically Logistic Bots, in a simulated world. Leveraging the OpenAI Gym framework and building upon an existing template from a GitHub repository, we have crafted a unique and engaging simulation for experimenting with reinforcement learning algorithms.

## Customization

### Action and Observation Spaces

We've tailored the action space to be Discrete, simplifying the representation of possible actions. The observation space is a Dictionary of Discrete objects, offering a nuanced view of the environment state.

### Custom Classes

Three key classes drive the simulation:

1. **LogisticBot**: Represents intelligent agents interacting with the Factory and RechargeStation, making decisions based on the observed state.
2. **Factory**: Encapsulates the core processes, governing production, distribution, and other fundamental aspects.
3. **RechargeStation**: Provides a vital element for sustained engagement, allowing LogisticBots to replenish energy.

### Configuring and Placing Objects

The simulation's dynamic nature stems from the careful arrangement of objects. Configure and instantiate instances of LogisticBot, Factory, and RechargeStation to define their interactions and set initial parameters.

## Demo

![Demo 5 x 5 Grid](https://github.com/P1X3LD3M0N/Project-Planning-Assignment/blob/main/gym-examples/gym_examples/envs/temp/output.gif)
