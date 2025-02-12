**Key concepts:**

**Reinforcement Learning**: ML technique where an agent learns to make decisions by interacting with environment to achieve a goal.

  **The Bellman's equation**: 
    s-state, a-action, R-reward, γ-discount

  **Policy:** It is a rule that tells what action to take at any given possible state. and plan is a sequence of actions.

  **Living penalty** in reinforcement learning is -ve reward or cost associated with the passage of time or each action the agent takes. It discourages an agent from prolonging an episode unnecessarily 
  and encourages it to find the goal more quickly.

  **Q-learning** aims to find the best action to take in a given state, in order to maximize the reward.
      Q-learning is 'model-free', 'off-policy'and uses Q-table to select correct actions.

  Two approaches for action selection policy: **Exploration** and **Exploitation**
  
  **Temporal Difference** is a concept that focuses on difference an agent experience over time. it is model-free learning technique used to predict the total reward expected in the future.

**Deep Q-learning:** It is applied on complex problems and it involves 
  **Learning**(Q values comparison, backpropogation, weights updated again and again)
  **Acting**(Action selection policy applied ex: epsilon-greedy, epsilon-soft(1-epsilon), softmax)
  **Experience Replay** it involves storing the agent's experiences(state, action, reward, nextstate) at each time step in a replay buffer. This replay buffer saves experience samples that can be reused during
  Training. The replay memory is initialised with defined capacity.

  Continued..
  

  
  

  
