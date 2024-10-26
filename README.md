# DeepLearning Car Racing Game

This project simulates a simple racing game environment where an agent, implemented with a Deep Q-Network (DQN), learns to navigate a circular track. The goal is for the agent to stay within track boundaries and complete laps while maximizing its reward.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Getting Started](#getting-started)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results and Visualization](#results-and-visualization)
6. [Future Improvements](#future-improvements)
7. [License](#license)

## Project Overview

This project demonstrates reinforcement learning by training an agent to drive on a circular track. It uses the DQN algorithm, where a neural network approximates Q-values to choose optimal actions based on the agent's position.

### Key Concepts:
- **Environment**: Simulated circular racing track with inner and outer boundaries.
- **Agent**: Learns to steer on the track by adjusting its angle based on Q-values.
- **Reward Structure**: Positive reward for staying on the track, negative reward for going out of bounds.

## Getting Started

### Prerequisites
Ensure the following are installed:
- **Python 3.7+**
- **TensorFlow** and **Keras** for DQN implementation
- **NumPy** and **Matplotlib** for calculations and visualizations

A Python virtual environment is recommended for dependency management.

## Installation

1. **Clone this repository**:
   ```bash
   git clone https://github.com/username/racing_dqn_project.git
   cd racing_dqn_project
   ```
   
2. **Install dependencies:**:
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage
   To start training the DQN agent and visualize each episode step-by-step:
   ```bash
   python src/main.py
   ```
   During training, a visualization of the agent’s trajectory and the track boundaries will display. The agent aims to stay within boundaries by learning through episodes.
   
## Configuring Hyperparameters
   To adjust training parameters like the number of episodes, epsilon decay, or learning rate, modify the constants at the top of main.py.

## Results and Visualization
As training progresses, a live plot shows the agent’s position, the track’s boundaries, and cumulative reward. After training, a Rewards over Episodes plot displays learning progress, with rewards expected to increase as the agent learns.

To see performance, a sample plot might look like:
```
Episode 1: Reward -20
Episode 2: Reward 15
...
```

## Future Improvements
Here are a few enhancements that could improve this project:

- Dynamic Track Generation: Introduce varied track layouts for more robust training.
- Obstacle Avoidance: Add obstacles or penalties for hitting certain areas.
- Reward Tuning: Experiment with reward structure for optimal learning.
- Model Optimization: Improve the neural network architecture and hyperparameters.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

Enjoy experimenting with reinforcement learning and DQN in this racing simulation!
