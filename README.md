# Reinforcement Learning Algorithms

This repository contains implementations of popular Reinforcement Learning (RL) algorithms learned during my Udemy course. Each algorithm is implemented in a separate Jupyter notebook, demonstrating how the model is trained. Accompanying each notebook is a video showcasing the model playing a game.

## Algorithms

### 1. **DQN (Deep Q-Network)**  
DQN is a value-based RL algorithm that uses deep neural networks to approximate Q-values. It improves over Q-learning by using experience replay and fixed Q-targets. DQN is efficient for environments with discrete action spaces.

**[Video: Model Playing Game](DQN/game_video.mp4)**

---

### 2. **DCQN (Double DQN)**  
Double DQN builds on DQN by addressing the overestimation bias of Q-values. It uses two networks to decouple action selection from Q-value estimation, leading to better stability and performance.

**[Video: Model Playing Game](DCQN/game_video.mp4)**

---

### 3. **SAC (Soft Actor-Critic)**  
SAC is an actor-critic algorithm that optimizes a stochastic policy in an off-policy way. It encourages exploration by maximizing entropy, making it suitable for continuous action spaces.

**[Video: Model Playing Game](SAC/game_video.mp4)**

---

### 4. **PPO (Proximal Policy Optimization)**  
PPO is a policy gradient method that aims to improve training stability by limiting the policy updates to small steps. It strikes a balance between simplicity and performance, making it widely used in RL.

**[Video: Model Playing Game](PPO/game_video.mp4)**

---

### 5. **A3C (Asynchronous Advantage Actor-Critic)**  
A3C uses parallel actor-learners to explore different parts of the environment simultaneously, making it faster and more efficient than traditional RL algorithms. It learns both the policy and value function.

**[Video: Model Playing Game](A3C/game_video.mp4)**
