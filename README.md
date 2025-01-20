# DQN Forex Trading Agent

This project implements a Deep Q-Network (DQN) agent for trading in the Forex market using the `gym` environment.

## Project Structure

- `DQN.ipynb`: Jupyter notebook containing the implementation and training of the DQN agent.
- `README.md`: Project documentation.

## Requirements

- Python 3.7.7
- `gym`
- `matplotlib`

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/wliant/anytrading-drl.git
    cd anytrading-drl
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook DQN.ipynb
    ```

2. Run the cells to train and evaluate the DQN agent.

## Description

The notebook `DQN.ipynb` includes the following sections:

1. **Environment Setup**: Initializes the Forex trading environment.
2. **Random Actions Baseline**: Runs a baseline model with random actions.
3. **DQN Implementation**: Implements the DQN algorithm.
4. **Training**: Trains the DQN agent.
5. **Evaluation**: Evaluates the performance of the trained agent.

## Actor-Critic Method

The Actor-Critic method is a type of reinforcement learning algorithm that combines both policy-based and value-based methods. It consists of two main components:

1. **Actor**: The actor is responsible for selecting actions based on the current policy. It updates the policy parameters in the direction suggested by the critic to improve the policy.

2. **Critic**: The critic evaluates the actions taken by the actor by computing the value function. It provides feedback to the actor on how good the action was, which helps in updating the policy.

In this project, the Actor-Critic method is used to train the agent to make better trading decisions in the Forex market.
