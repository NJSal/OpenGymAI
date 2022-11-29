# OpenGymAI: Reinforcement Learning & Deep Neural Networks Applied on Classic Atari Game, Ms. Pacman

A local environment was set up for this project and OpenAI Gym's library was imported in order to use of its functions (import gym) related to classic atari games (https://openai.com/blog/gym-retro/).

Reinforcement learning was used to train an agent, or player's character, to navigate and beat levels. Ms. Pacman was the classic Atari game used in this project.

TensorFlow's Keras API was utilized for creating a Sequential model that makes use of a Convolutional Neural Network (CNN), and numpy for matrix manipulation.

As the character navigates through the level it learns from experience through episodes where each episode allows the character to learn from its environment. An episode is made up of a sequence of observations that an agent has obtained from the game's environment, and rewards asscoiated with specific actions taken.

The amount of reward is maximized by Ms. Pacman (the character of the game used) by learning from good episodes in order to make better deicisions. An episode takes place when the character wins the level or dies. 



<img src = "https://recordit.co/slFhKrMSAi.gif" width="800" height="500"/><br>
