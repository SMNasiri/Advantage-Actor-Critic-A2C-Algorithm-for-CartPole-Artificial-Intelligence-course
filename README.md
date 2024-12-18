# Advantage-Actor-Critic-A2C-Algorithm-for-CartPole-Artificial-Intelligence-course
This project demonstrates the implementation of the Advantage Actor-Critic (A2C) algorithm to solve the CartPole environment from OpenAI's Gym library. A2C is a reinforcement learning (RL) technique that uses two neural networks—an actor and a critic—to learn optimal policies and value functions for decision-making tasks.

The goal of the CartPole task is to balance a pole on a moving cart by applying forces to the cart. The agent is trained to maximize cumulative rewards by keeping the pole upright as long as possible.

## Features

- **Environment**: OpenAI Gym’s CartPole-v1.
- **Algorithm**: Advantage Actor-Critic (A2C).
- **Actor-Critic Framework**:
  - The actor predicts action probabilities.
  - The critic estimates the state value.
- **Advantage Calculation**: Utilizes the difference between observed returns and estimated state values to guide policy updates.
- **Visualization**: Includes training progress plots and performance demonstrations.

## Code Structure

- **Actor Network**: Outputs action probabilities based on the current state.
- **Critic Network**: Estimates the value of the current state.
- **Training Loop**:
  - Collects trajectories of states, actions, and rewards.
  - Computes advantages to optimize the actor and critic networks.
- **Evaluation**: Demonstrates the effectiveness of the trained policy on test episodes.

## Results

The A2C implementation successfully trains an agent capable of balancing the CartPole for extended periods. Training performance is visualized through reward curves, and the final model is tested for qualitative evaluation.

