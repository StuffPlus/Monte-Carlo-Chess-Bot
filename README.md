# Chess engine with Deep Reinforcement learning
This is a reinforcement learning chess bot using the Monte Carlo Tree Search as the main way of choosing which move is the best to use. 

## How does the chess engine work?

This chess engine is based on AlphaZero by Deepmind. It uses a neural network
to predict the next best move. The neural network learns by playing against
itself for a high amount of games, and using their results to train the network.
The newly trained neural network is evaluated against the old network by playing
many games against each other, and the best network is kept. This process is repeated
for a long time.

## Installation

In the Documents folder is the installation guide and the user manual. Ignore chapter 1.3 in the installation as the Docker is not updated
