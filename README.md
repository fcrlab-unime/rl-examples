# Reinforcement Learning by Examples

The Reinforcement Learning (RL) is a computational approach to learning from goal-directed interaction. It learns what to do, i.e., how to map situations to actions, in order to maximize a numerical reward signal. The learner is not told which actions to take, but instead must discover which actions yield the most reward by trying them. In this regard, actions affect not only the immediate reward but also the next situation and, therefore, all subsequent rewards.

RL is formalized as a Markov decision process. Indeed, a learning agent senses the state of its environment and takes actions that affect that state. The agent must have one or more goals relating to the state of the environment.

The most common challenge is balancing the trade-off between exploration and exploitation. To obtain a lot of reward, a RL agent must prefer actions tried in the past and found to be effective in producing reward. On the other hand, to discover other actions, the agent has to try actions not selected before. The agent has to *exploit* what it has already experienced in order to obtain reward, but it also has to *explore* in order to make better action selections in the future.

Many of the core algorithms of RL were originally inspired by biological learning systems. Indeed, this is the ML technique closest to how humans and animals learn. 

# Bibliography
- Reinforcement Learning: An Introduction. Second edition. Richard S. Sutton and Andrew G. Barto. The MIT Press.