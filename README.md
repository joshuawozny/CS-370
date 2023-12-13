# CS-370: Current/Emerging Trends ​/ Artificial Intelligence
<p>This course explores advanced topics in Computer Science through analysis of authentic scenarios. This course is an introduction to Artificial Intelligence and advanced Machine Learning algorithms.</p>


>Artificial Intelligence is one of the fastest-expanding fields in computer science and information technology. The phrases “machine learning” and “data science” are set to surpass “software engineer” in job descriptions on LinkedIn this year. As you progress toward graduation and begin to search for internships and full-time positions in IT, you will quickly learn that experience with artificial intelligence and machine learning is highly valued by industry leaders. https://learn.snhu.edu/d2l/le/content/1426517/viewContent/27469098/View

## Description
<p> The integration of Artificial Intelligence (AI) in gaming has revolutionized the way we interact with and experience games. In the realm of strategic and problem-solving games, AI plays a pivotal role in enhancing gameplay and providing dynamic challenges. A prime example of this integration is the use of deep Q-learning in pathfinding within games. Deep Q-learning, a sophisticated form of reinforcement learning, allows an AI agent, such as a pirate in a treasure hunt game, to navigate complex environments and achieve objectives efficiently. Unlike traditional AI approaches that follow predefined rules, deep Q-learning enables the agent to learn from its environment and improve over time, akin to human learning processes (AI Summer, n.d.; OpenAI, n.d.).  </p>

<p>The theme of this project is a popular treasure hunt game in which the player needs to find the treasure before the pirate does. We were tasked with writing code for the part of the game that represents the intelligent agent, which is a pirate in this case. The pirate will try to find the optimal path to the treasure using deep Q-learning. We were provided with two Python classes and this notebook to develop the game. The first class, TreasureMaze.py, represents the environment, which includes a maze object defined as a matrix. The second class, GameExperience.py, stores the episodes – that is, all the states that come in between the initial state and the terminal state. This is later used by the agent for learning by experience, called "exploration". This notebook shows how to play a game. We completed the deep Q-learning implementation for which a skeleton implementation has been provided.</p>

## Q-learning Implementation

>The agent learns to achieve a goal in an uncertain, potentially complex environment. In reinforcement learning, an artificial intelligence faces a game-like situation (OpenAI, n.d.).
<p>The implementation of deep Q-learning in this project involves building a neural network that approximates the Q-value function. It's structured to take the state of the game as input and output a Q-value for each possible action. The network updates its weights based on the agent's experiences, refining its action-prediction capability over time. As the agent interacts with the environment, it accumulates experiences, which are then used to update the model, refining its ability to predict the most rewarding actions. This iterative learning process embodies the core of deep Q-learning, enabling the agent to evolve its strategy over time. </p>

## References

AI Summer. (n.d.). The idea behind Actor-Critics and how A2C and A3C improve them. Retrieved from https://theaisummer.com/Actor_critics/ 
 

OpenAI. (n.d.). Emergent Tool Use. Retrieved from https://openai.com/blog/emergent-tool-use/ 
