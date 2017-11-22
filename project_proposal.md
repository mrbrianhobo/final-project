# steak
Do you suffer from a lack of motivation? Have you ever had tasks to complete that you just didn't feel like working on? steak is a productivity tool that will help you stay personally and financially accountable for goals that you set.

### Overview
steak is a stake-based TODO list dApp that works like any other TODO list. However, users must stake some asset along with the goal/task that they are creating. As these goals/tasks are completed, funds are reimbursed back to the user. 

### Idea/Motivation
##### Example
  - Alice sets a goal "Essay #1" to be completed in 2 weeks and stakes 1 ETH
  - Alice's 1 ETH is locked up for the 2 week period while she works on her essay
  - After 2 weeks, Alice finishes her essay and submits it to a validator to verify that it is completed. After validation, Alice's original stake is reimbursed to her.
  - If Alice doesn't complete her essay, her original 1 ETH stake is slashed and "donated" to a reward pool

##### Further Extensions
 - Reward users for completing tasks early (using "reward pool" from people who didn't complete their tasks)
 - Incrementally slash funds if tasks are completed late (lowers severity of not completing tasks, not all or nothing)
 - Incentivize validators to verify honestly
 - Incentivize users by not only reimbursing funds but also rewarding them with "interest" on top of completing task
 - Allow other parties to "bet" on outcome (Gnosis?)

### Project Design
##### Smart Contracts
steak will have 2 main smart contracts that interact with each other:
 - User Contract: handles normal user functionality (task creation, asset staking, payout)
 - Validator Contract: handles verification for tasks that have been completed

##### Frontend
Looking into using React (maybe?) or doing something simple in HTML/JS

##### Additional Components
IPFS, Gnosis (maybe?), oracalize (maybe?)