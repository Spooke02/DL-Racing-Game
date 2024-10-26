## DL-Racing-Game
# Deep Learning Car Racing Game

# Racing DQN Project

![Racing DQN Project](docs/images/racing_track.png)

A Deep Q-Network (DQN) project that simulates a racing game where an agent learns to drive within a circular track using reinforcement learning.

## Features
- **Environment**: A customizable racing game environment with an inner and outer track boundary.
- **Agent**: DQN-based agent with exploration-exploitation behavior for learning optimal paths.
- **Visualization**: Real-time trajectory visualization to observe agent’s progress in each episode.

## Getting Started

### Prerequisites
- Python 3.7+
- Recommended to use a virtual environment

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/username/racing_dqn_project.git
   cd racing_dqn_project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Code
To start training the DQN agent:
```bash
python src/main.py
