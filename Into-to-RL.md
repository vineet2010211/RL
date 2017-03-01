#### What makes a reinforcement learning different from the other machine learning paradigms? 
 * There is no supervisor only a **reward** signal.
 * Feedback is delayed, not instantaneous.
 * Time really matters (sequential, non i.i.d data).
 * Agent's actions affect the subsequent data it recieves.
 
 
 ### The Reinforcement Learning Problem 
 
 * Reward
    * A __reward__ Rt is a scalar feedback signal.
    * Indicates how well agent is doing at time step t.
    * Agent's job is to maximize cumalative reward.
    
Reinforcement learning is based in on the **Reward Hypothesis**

#### Examples of Rewards 
* Fly stunt manoeuvres in a helicopter 
    * +ve reward for following a desired trajectory. 
    * -ve reward for crashing.
* Managing an investment portfolio 
    * +ve reward for each $ in bank.


### Sequential Decision Making 
#### __Goal__ : select actions to maximise total future reward. 
* Actions might have long term consequences.
* Rewards may be delayed.
* It may be better to sacrifice immediate reward to gain more long-term reward. 
* Examples:
    * A Financial Investment (may take months to mature).
    * Refuelling a helicopter (might prevent a crash in several hours).
    * Blockcing opponent moves (might help wiining probability many moves in the future).
    
#### Agent and Environment 

\$\$ R_t, A_t, O_t \$\$
