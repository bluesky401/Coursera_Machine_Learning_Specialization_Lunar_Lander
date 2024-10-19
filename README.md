### Overview
This project is part of the Coursera Machine Learning Specialization and applies unsupervised learning techniques to a simulated lunar lander.
This project implements a Deep Q-Learning agent to control a rover landing on a simulated lunar surface. 
The agent learns through reinforcement learning to optimize the landing process by adjusting the rover's thrust
based on state observations. Techniques such as experience replay and target networks are employed to stabilize 
learning, and neural network approximation is used for Q-value estimation.

The project utilizes OpenAI Gym for the lunar lander simulation environment and PyTorch to build and train the neural network.
Performance evaluation is conducted to ensure that the agent efficiently learns to land the rover safely.

### Features
Deep Q-Learning: A Q-learning agent with a deep neural network approximating the Q-values.
Experience Replay: Storing past experiences and sampling from them to break correlations in the data.
Target Networks: Using a separate target network to stabilize training.
Performance Evaluation: Monitoring the agent's landing success rate, fuel usage, and landing stability.
### Key Algorithms and Techniques
Deep Q-Network (DQN): Neural network to estimate Q-values based on state observations.
Experience Replay: Stores and samples past experiences to improve learning efficiency and stability.
Target Network: Separate network used to generate stable target Q-values for learning.
### Results
Successfully trained a Deep Q-Learning agent to land the lunar rover with minimal crashes.
Achieved smooth landings by balancing fuel usage and maintaining low landing velocities.
Demonstrated stable learning through experience replay and target network synchronization.
