# JakQTableBrain
> [Github Repo Link](https://github.com/Stephen-Baxter/QTableBrain)

> [Demonstration](https://stephen-baxter.github.io/#AI_DEMONSTRATION_PAGE_)
## Class
1. JQTBrain(number_of_states_, number_of_actions_, alpha_, gamma_, q_table_ = [])

## JQTBrain Functions
1. GetAction(state_, chooses_random_action_ = false)
2. UpdateQTable(reward_1_, state_0_, action_0_, state_1_)
3. ResetQTable(alpha_ = this.alpha, gamma_ = this.gamma)

## JQTBrain Getter
1. qTable:
  
   Returns a copy of the qTable

## JQTBrain Instance Variables
1. alpha:
  
   Holds the learng rate that UpdateQTable uses to update the qTable
4. gamma:
  
   Holds the discount factor that UpdateQTable uses to update the qTable

## License
+ MIT License
