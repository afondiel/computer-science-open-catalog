# Reinforcement learning (RL) - notes :robot:

## Intro 

A machine learning approach/paradigm which enables a model to learning patterns from data with/without labels based on reward (if the model correctly learns a pattern) or a penalty otherwise.

RL provides a statistical framework based on two components :
- Agent(a) : takes actions that changes an existing state(S) of the environment
- Environment (b) : transites to a new/future state based on changes taken by the agent and provides feedback to the agent
- feedback : can either be positive(+) or negative(-), after set of feedbacks or iterations the agent tries to learn and optimize the future actions in order to get a maxime of (+) feedbacks => reward (function) 

Reward function : Q(s,a)
![Q(s,a)](q-function.PNG)

Learning strategy : 
- Value-based RL
- Policy search-based RL
- Actor-critic-based RL
## Applications 
- Robotics 
- Self-driving cars 
- Strategy games : chess/Go

## Tools / frameworks 
- OpenAI Gym
- TensorFlow
- Keras
- DeepMind Lab
- Pytorch
- Markov Chain/Markov Decision Process (MDP)
- TensorFlow


## References 

- [Reinforcement learning wiki](https://en.wikipedia.org/wiki/Reinforcement_learning)
- [Markov Chain](https://en.wikipedia.org/wiki/Markov_chain)
- [MDP](https://en.wikipedia.org/wiki/Markov_decision_process)
- [Stochastic Model](https://en.wikipedia.org/wiki/Stochastic_process)
- [Proba Theory](https://en.wikipedia.org/wiki/Probability_theory)
- [Bellman equation](https://en.wikipedia.org/wiki/Bellman_equation)
- [Sequential logic](https://en.wikipedia.org/wiki/Sequential_logic)
- [Finite-state machine](https://en.wikipedia.org/wiki/Finite-state_machine)

> *"It is difficult to free fools from the chains they revere." ~ Voltaire*
