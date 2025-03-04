#### Questions@:, Lecture 1 Questions
- Derive how to incrementally update a running average (how to compute
  an average of $N$ numbers using the average of the first $N-1$ numbers). [5]

- Describe multi-arm bandits and write down the $\epsilon$-greedy algorithm
  for solving it. [5]

- Define a Markov Decision Process, including the definition of a return. [5]

- Describe how does a partially observable Markov decision process extend the
  Markov decision process and how is the agent altered. [5]

- Define a value function, such that all expectations are over simple random
  variables (actions, states, rewards), not trajectories. [5]

- Define an action-value function, such that all expectations are over simple
  random variables (actions, states, rewards), not trajectories. [5]

- Express a value function using an action-value function, and express an
  action-value function using a value function. [5]

- Define optimal value function and optimal action-value function. Then define
  optimal policy in such a way that its existence is guaranteed. [5]

#### Questions@:, Lecture 2 Questions
- Write down the Bellman optimality equation. [5]

- Define the Bellman backup operator. [5]

- Write down the value iteration algorithm. [5]

- Define the supremum norm $||\cdot||_\infty$ and prove that Bellman backup
  operator is a contraction with respect to this norm. [10]

- Formulate and prove the policy improvement theorem. [10]

- Write down the policy iteration algorithm. [10]

- Write down the tabular Monte-Carlo on-policy every-visit $\epsilon$-soft algorithm. [5]

- Write down the Sarsa algorithm. [5]

- Write down the Q-learning algorithm. [5]

#### Questions@:, Lecture 3 Questions
- Elaborate on how can importance sampling estimate expectations with
  respect to $\pi$ based on samples of $b$. [5]

- Show how to estimate returns in the off-policy case, both with (a) ordinary
  importance sampling and (b) weighted importance sampling. [10]

- Write down the Expected Sarsa algorithm and show how to obtain
  Q-learning from it. [10]

- Write down the Double Q-learning algorithm. [10]

- Show the bootstrapped estimate of $n$-step return. [5]

- Write down the update in on-policy $n$-step Sarsa (assuming you already
  have $n$ previous steps, actions and rewards). [5]

- Write down the update in off-policy $n$-step Sarsa with importance
  sampling (assuming you already have $n$ previous steps, actions and rewards). [10]

- Write down the update of $n$-step Tree-backup algorithm (assuming you already
  have $n$ previous steps, actions and rewards). [10]

- Assuming function approximation, define Mean squared value error. [5]

- Write down the gradient Monte-Carlo on-policy every-visit $\epsilon$-soft algorithm. [10]
