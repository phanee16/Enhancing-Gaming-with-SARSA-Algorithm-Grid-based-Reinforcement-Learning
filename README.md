# Grid gaming environment
Reinforcement learning
SARSA

![image](https://user-images.githubusercontent.com/47351536/229378768-bb593c45-9ae4-468d-901f-7e20781f4ec7.png)


This reinforcement learning project focuses on teaching an agent to navigate through a 5x5 grid environment using the SARSA algorithm. The objective is to learn the optimal policy that maximizes the cumulative reward obtained by the agent while navigating the environment. The grid environment consists of 25 state spaces, where the agent can move up, down, left, or right. The agent receives rewards for reaching certain positions in the environment, such as the goal position, gold and diamond positions, and penalties for colliding with a monster or a bomb. By implementing the SARSA algorithm, the agent learns from its own experiences to update its policy for taking actions in the environment, resulting in improved navigation and better reward outcomes.

The project consists of two main components. First, the GridEnvironment class represents the environment and includes the logic for creating the grid, initializing the rewards and penalties, and updating the environment based on the actions taken by the agent. The second component is the SARSA_Agent function, which implements the SARSA algorithm to learn the optimal policy for the agent. The SARSA_Agent function takes several hyperparameters as input, such as epsilon (the exploration rate), alpha (the learning rate), gamma (the discount factor), and eps_decay_factor (the decay factor for epsilon). These hyperparameters affect the learning process and can be adjusted to improve the performance of the agent. The SARSA_Agent function outputs the learned Q_table, which represents the expected future reward for each action in each state, as well as some additional information such as the episode scores and the best path actions. The project also includes a render function to display the current state of the environment during the learning process, allowing for visualization of the agent's progress.

Overall, this project provides a practical implementation of reinforcement learning using the SARSA algorithm in a grid environment. By navigating the environment and receiving feedback in the form of rewards and penalties, the agent can learn to take optimal actions to maximize its cumulative reward. The project provides flexibility in adjusting the hyperparameters to fine-tune the learning process, and the render function allows for visualization of the agent's progress. The project can be extended to more complex environments and algorithms, making it a valuable starting point for exploring reinforcement learning.





