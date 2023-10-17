# JakQTableBrain
> [Github Repo Link](https://github.com/Stephen-Baxter/QTableBrain)

> [Demonstration](https://stephen-baxter.github.io/#AI_DEMONSTRATION_PAGE_)
## Class
1. JQTBrain(number_of_states_, number_of_actions_, alpha_, gamma_, q_table_ = []):  
   Initializing this class will initialize 2D array for the Q-table, alpha value, and gamma value. The parameters number_of_states_, number_of_actions_, alpha_, and gamma_ are numbers. If a 2D array of numbers with column length equal to number_of_actions_ and row length equal to number_of_states_ is given for q_table_ then q_table_ will be use for the Q-table.

## JQTBrain Functions
1. GetAction(state_, chooses_random_action_ = false):  
   If chooses_random_action_ is false then the index associated with the action associated with the highest Q-value for the given state_ is return else a random number between 0 and number of actions is return for action. The parameter state_ is a number and chooses_random_action_ is a boolean.
3. UpdateQTable(reward_1_, state_0_, action_0_, state_1_):  
   Updates the Q-value in the Q-table at state_0_ and action_0_ given reward_1_, state_0_, action_0_, and state_1_. The parameters reward_1_, state_0_, action_0_, and state_1_ are numbers.
4. ResetQTable(alpha_ = this.alpha, gamma_ = this.gamma):  
   Resets the qTable. If an alpha_ and gamma_ are given then the values are updated. The parameters alpha_ and gamma_ are numbers.

## JQTBrain Getter
1. qTable:  
   Returns a copy of the Q-table. The qTable return value is a 2d array of numbers with column length equal to number_of_actions_ and row length equal to number_of_states_.

## JQTBrain Instance Variables
1. alpha:  
   Holds the learng rate that UpdateQTable uses to update the qTable. The alpha is a number.
4. gamma:  
   Holds the discount factor that UpdateQTable uses to update the qTable. The gamma is a number.

## License
- MIT License

