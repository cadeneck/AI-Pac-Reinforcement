
# Reinforcement Learning Project

## Introduction
Embark on a journey through the realms of reinforcement learning where you'll bring to life agents capable of learning from their environment. This project introduces you to the foundational concepts of value iteration and Q-learning, tested across various domains from Gridworld to the iconic game of Pacman, and a simulated robotic controller known as Crawler.

### Key Features
- Implementation of value iteration agents for solving Markov Decision Processes (MDPs).
- Development of Q-learning agents adaptable to Gridworld, Crawler, and Pacman.
- Exploration of reinforcement learning principles through practical application and analysis.

### Dependencies
- Python (version 3.x recommended). No additional dependencies are required beyond Python and the project files.

## Usage
Leverage the included autograder to evaluate your solutions locally:

```bash
python autograder.py
python autograder.py -q q2
python autograder.py -t test_cases/q2/1-bridge-grid
```

## Files and Directories
- **To Edit and Submit**:
  - `valueIterationAgents.py`: Implement a value iteration agent for MDPs.
  - `qlearningAgents.py`: Develop Q-learning agents for various scenarios.
  - `analysis.py`: Analyze and answer questions related to the project.
- **Core Components** (Read only):
  - `mdp.py`, `learningAgents.py`: Base classes for MDPs and learning agents.
  - `util.py`, `gridworld.py`, `featureExtractors.py`: Utilities and environment implementations.
- **Supporting Files** (Can be ignored):
  - Includes environment abstract classes, graphical displays, the crawler environment, and autograding scripts.

## Reinforcement Learning in Gridworld
Start by manually controlling an agent in Gridworld to understand the dynamics:

```bash
python gridworld.py -m
```

Experiment with Gridworld's parameters to see how they affect the agent's behavior:

```bash
python gridworld.py -h
```

## Project Topics
- **Value Iteration**: Implementing a value iteration agent to solve known MDPs.
- **Q-Learning**: Developing agents that learn policies based on environmental feedback.
- **Analysis**: Reflecting on the behavior of your agents and the impact of various parameters.

## Contributing
While this project was primarily an academic exercise, contributions or suggestions for improvements are welcome. Please open an issue
or a pull request if you have suggestions.

## License
This project is licensed under the MIT License - see the https://inst.eecs.berkeley.edu/~cs188/sp22/projects/ file for details.

## Acknowledgments
- Course staff and fellow students for their support and feedback.
- The original creators of Pacman for inspiring this educational project.
