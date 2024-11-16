##**Name:NITHYASHREE U R**
##**Company:CODETECH IT SOLUTIONS**
##**ID:CTO8DS9186**
##**Domain:Artificial Intelligence**
##**Duration:October to November 2024**
##**Mentor:Neela Santhosh Kumar**

# **Reinforcement Learning for Game Playing: Q-Learning Agent for Tic-Tac-Toe**

## **Overview**
This project demonstrates the application of **Reinforcement Learning (RL)** to train an agent to play **Tic-Tac-Toe** using the **Q-Learning** algorithm. The goal is to develop an intelligent agent that can learn to play Tic-Tac-Toe optimally through trial and error, interacting with the game environment and maximizing its cumulative rewards.

## **Project Structure**
The project consists of the following components:

1. **TicTacToeEnv**: A class defining the game environment. It simulates the Tic-Tac-Toe board, handles game rules, and provides feedback to the agent based on its actions.
2. **QLearningAgent**: A class implementing the Q-learning algorithm. The agent learns optimal strategies by updating its Q-values based on rewards it receives after performing actions in the environment.
3. **Training**: The agent is trained over multiple episodes to improve its decision-making ability and eventually play the game successfully.
4. **Evaluation**: After training, the agent is tested in 100 episodes, and its performance (wins, draws, and losses) is evaluated.

## **How It Works**
- **Q-Learning**: The agent uses a **Q-table** to store and update action-value estimates for each state-action pair. The agent uses the following learning process:
    - **Exploration**: The agent randomly explores the environment to gather experience.
    - **Exploitation**: The agent leverages learned knowledge to make the best possible decision based on the Q-values.
    - **Reward System**: The agent receives a positive reward for winning the game (+10), a negative reward for invalid moves (-10), and zero for a draw (0).

- **Training**: The agent plays many episodes of Tic-Tac-Toe against itself, improving over time. The **learning rate** (alpha), **discount factor** (gamma), and **exploration rate** (epsilon) are adjusted to refine the agent's learning process.

- **Evaluation**: Once trained, the agent is evaluated on how well it performs in 100 test games, where it plays against random moves.

## **Features**
- **Q-Learning Algorithm**: Implements a classic RL algorithm for learning optimal strategies.
- **Tic-Tac-Toe Game**: A fully functional game environment to test the RL agent.
- **Training & Evaluation**: Includes training on 10,000 episodes and performance evaluation across 100 test episodes.
- **Exploration vs Exploitation**: Uses epsilon-greedy strategy to balance exploration and exploitation.


