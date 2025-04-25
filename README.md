# AI-Game-Agent-With-Deep-Q-Learning-Using-reinforcement-Learning
A reinforcement learning-based project that trains an AI agent to master the classic Snake game using Deep Q-Learning with PyTorch.

🧠 Overview
This project demonstrates how an AI agent can autonomously learn to play the Snake game through Reinforcement Learning (RL). By applying Deep Q-Learning (DQN), the agent maximizes rewards (eating food) while avoiding penalties (collisions). It utilizes PyTorch for neural network implementation and Pygame to simulate the game environment.

🎯 Objectives
Train an AI agent to play Snake autonomously.

Maximize cumulative reward (score) through Reinforcement Learning.

Apply Deep Q-Networks (DQN) for high-dimensional state spaces.

🔑 Key Features
🧠 RL Algorithm: Deep Q-Learning (DQL)

⚙️ Frameworks: PyTorch & Pygame

🧠 Model: Feed-forward neural network to predict Q-values

📈 Experience Replay & Bellman Equation

🎮 Game Environment: Classic Snake game with real-time rendering

📊 Metrics: Score, survival time, Q-value convergence

🛠️ Technologies Used
Language: Python

Libraries: PyTorch, NumPy, Matplotlib, Pygame

IDE: VS Code / Jupyter / PyCharm

Training Techniques: Epsilon-greedy policy, experience replay, target networks

📦 Installation
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/snake-ai-dqn.git
cd snake-ai-dqn
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Run the Game (Training Mode)

bash
Copy code
python agent.py
Play Manually (Human Mode)

bash
Copy code
python snake_game_human.py
🧪 Model Details
Inputs: Game state (snake direction, food location, danger zones)

Outputs: Q-values for each possible move (straight, left, right)

Architecture:

Input Layer: 11 neurons

Hidden Layer: 256 neurons (ReLU)

Output Layer: 3 actions

Optimizer: Adam

Loss Function: Mean Squared Error (MSE)

📊 Evaluation Metrics
🏆 Score: Points collected by reaching food

🧭 Survival Time: Duration without collision

📉 Q-value Convergence: Indicates learning progress

📈 Win Rate: Success rate across episodes

💡 Future Scope
Gamified UI with real-time analytics

Web-based demo deployment using Flask or Streamlit

Model performance dashboard with engagement metrics

Interactive learning tutorials and multilingual support

AI tutors/chatbots for code walkthroughs

🙌 Team
T. Rohith (2111CS020410)

P. Sai Charan (2111CS020426)

C. Sai Kiran Kumar Reddy (2111CS020430)

R. Sri Harsha Rao (2111CS020431)

S. Sai Kiran Reddy (2111CS020432)

Guide: Prof. I Sweety Julia
Institution: Malla Reddy University, 2024

📜 References
Sutton & Barto – Reinforcement Learning: An Introduction

Mnih et al. – Deep Q-learning with Human-level Control

Patrick Loeber’s tutorial – GitHub Repo

