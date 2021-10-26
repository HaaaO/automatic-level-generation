# automatic-level-generation
An archived group project for CSCI566 (alphabetical order by last name)

- Nathan Dennler
- Puneeth Reddy Gattikoppula
- Jignesh Modi
- Heramb Nemlekar
- Zhonghao Shi

Our project focuses on the problem of generating synthetic levels of a game such that the levels can be used to learn an optimal policy for playing the game. 

Given a few pre-existing game levels we used deep generative models (like GANs) to generate new additional game levels. We then trained an RL agent on these levels to learn a generalized policy of playing the game. Our hypothesis is that training the agent with the additional levels will lead to an optimal policy that performs better than the policy learned from the few pre-existing levels.

Our final objective is to learn such a generative model, train an RL agent with the generated levels and test its performance on a set of unseen game levels.
