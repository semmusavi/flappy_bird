# flappy_bird
The code uses a simple DQN architecture to learn the optimal policy for playing Flappy Bird.
Training involves exploring the environment, storing experiences in a replay memory, and updating the Q-network parameters.
Testing evaluates the trained agent's performance in the game.
Q-Learning:
Q-learning is a reinforcement learning algorithm used to find an optimal action-selection policy for a given finite Markov decision process.
In this context, the Q-values represent the expected cumulative future rewards for taking a particular action in a given state.
The DQN approximates the Q-function and is trained to minimize the temporal difference error between predicted and target Q-values.
In summary, the provided scripts demonstrate the application of Deep Q-Learning to teach an agent to play the Flappy Bird game efficiently. The training script trains the model, while the testing script evaluates its performance. Q-learning is at the core of the training process, guiding the agent to make optimal decisions in the game environment.
