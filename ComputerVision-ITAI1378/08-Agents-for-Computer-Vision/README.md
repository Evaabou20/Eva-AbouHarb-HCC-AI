# AI Agent Concepts for Computer Vision

## Project Overview

This project explores the fundamental learning algorithms behind intelligent AI agents through hands-on implementations of reinforcement learning and distributed learning concepts. Instead of relying on pre-built implementations, I developed the core learning logic for each algorithm and evaluated how different agent architectures learn from rewards, interactions, and shared knowledge.

The project was completed as part of **ITAI 1378 – Computer Vision** at **Houston City College**.

---

## Objectives

- Implement the Q-learning update used by Deep Q-Networks (DQN).
- Explore how policy-gradient methods learn by updating action probabilities.
- Develop coordination rules for multi-agent systems.
- Implement federated averaging for distributed learning.
- Compare value-based and policy-based learning approaches.
- Understand how intelligent agents can support AI and computer vision applications.

---

## Technologies Used

- Python
- Google Colab
- Reinforcement Learning
- Deep Q-Network (DQN)
- Policy Gradient
- Multi-Agent Systems
- Federated Learning

---

## Techniques Implemented

- Q-Learning
- Policy Optimization
- Action Probability Updates
- Multi-Agent Coordination
- Collision Avoidance
- Federated Averaging
- Reinforcement Learning Experiments
- Learning Performance Comparison

---

## Part 1 – Deep Q-Network (DQN)

Implemented the Q-learning update rule by updating Q-values based on rewards, future expected rewards, the learning rate, and the discount factor.

Experiments compared different learning rates to observe how quickly the agent learned from repeated experiences.

---

## Part 2 – Policy Gradient

Implemented a policy-gradient agent that directly updates action probabilities based on received rewards.

Experiments demonstrated how rewarding different actions gradually changes the learned policy.

---

## Part 3 – Multi-Agent Systems

Implemented a coordination rule allowing multiple agents to communicate their positions and avoid collisions while navigating a shared environment.

Experiments compared system behavior using different numbers of agents.

---

## Part 4 – Federated Learning

Implemented federated averaging by combining the learned Q-values from multiple agents without sharing their original experiences.

This demonstrated how distributed learning enables collaborative model improvement while preserving data privacy.

---

## Part 5 – Comparing Learning Approaches

Compared Deep Q-Networks and Policy Gradient learning over multiple training episodes.

Observed how value-based and policy-based methods behaved under randomly generated rewards and compared their learning stability.

---

## Project Files

| File | Description |
|------|-------------|
| `Lab_AgentConcepts_AbouHarb_Eva_ITAI.ipynb` | Interactive notebook implementing DQN, Policy Gradient, Multi-Agent Systems, Federated Learning, and reinforcement learning comparisons. |

---

## Skills Demonstrated

- Reinforcement Learning
- Deep Q-Networks (DQN)
- Policy Gradient Methods
- Multi-Agent Systems
- Federated Learning
- Q-Learning
- Distributed AI
- Algorithm Design
- Python Programming
- Experimental Analysis

---

## Key Learning Outcomes

Through this project, I gained hands-on experience implementing several foundational AI agent learning techniques instead of relying on existing libraries. I learned how Deep Q-Networks estimate action values from rewards, how policy-gradient methods directly optimize action probabilities, how multiple agents coordinate to solve shared tasks, and how federated learning enables collaborative model improvement while protecting local data.

Comparing these learning strategies strengthened my understanding of the trade-offs between value-based, policy-based, multi-agent, and distributed AI approaches, as well as their potential applications in intelligent computer vision systems.
