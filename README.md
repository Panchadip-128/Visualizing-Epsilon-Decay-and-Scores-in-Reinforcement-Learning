Project Overview
Epsilon Explorer is a reinforcement learning project designed to explore and analyze the performance of an agent using an epsilon-greedy strategy. The primary objective of this project is to investigate how the agent learns over multiple episodes by balancing exploration (trying new actions) and exploitation (choosing the best-known actions). This project provides valuable insights into the agent's learning dynamics, highlighting the effects of epsilon decay on performance and score improvement.

Key Concepts
Reinforcement Learning
Reinforcement learning (RL) is a type of machine learning where an agent learns to make decisions by interacting with an environment. The agent receives feedback in the form of rewards or penalties based on its actions, allowing it to learn optimal strategies for maximizing cumulative rewards.

Epsilon-Greedy Strategy
The epsilon-greedy strategy is a popular approach used in reinforcement learning to balance exploration and exploitation. The strategy employs a parameter, epsilon (ε), which determines the probability of choosing a random action (exploration) versus the best-known action (exploitation). As training progresses, epsilon typically decays, allowing the agent to rely more on learned knowledge and less on exploration.

Score Tracking
Tracking the scores achieved by the agent during training provides valuable insights into its performance. By analyzing these scores, we can evaluate the effectiveness of different learning strategies and make informed decisions about tuning hyperparameters.


![ep_RL2](https://github.com/user-attachments/assets/4b369c79-64ff-4600-b329-30df9552ad18)
![epsilon_RL1](https://github.com/user-attachments/assets/8b577058-7e29-4776-9cb3-e9f8eaad2016)
