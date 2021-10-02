Author: Huygens Ravelomanana
# Description:
+ We solved the cart pole game/problem from [gym.openai](https://gym.openai.com/envs/#classic_control) for 1500 steps/frames. 
+ We used 30000 episodes. 
+ We did a random search to find the best combination of hyperparameters:     learning_rate, gamma, epsilon, bin_size (for discretization).
    * Because of this, running the whole notebook will redo the search again
    * It is better to run the following sections consecutively instead (since we already know the best combination):
            + Installing packages
            + Importing Libraries
            + Creating the game environment
            + Defining functions for the Q-learning process
            + Playing using the best policy
