# CS---370-Current-Emerging-Trends-AI-Artificial-Intelligence
# CS 370: Pirate Intelligent Agent

## Project Overview

This project involved developing an intelligent pirate agent capable of navigating a maze to locate hidden treasure. The goal was to apply reinforcement learning and neural networks to teach the agent how to make decisions, avoid obstacles, and identify a successful path to the treasure.

### What code was provided, and what did I create?

For this project, I was provided with starter code, including the `TreasureMaze.py` and `GameExperience.py` files. These files established the maze environment, supported the agent's interactions with the environment, and provided functionality for storing previous experiences.

My primary contribution was completing the deep Q-learning training algorithm in the Jupyter Notebook. I implemented the training process that allowed the pirate agent to explore the maze, select actions, receive rewards, and learn from previous experiences. The implementation used an epsilon-greedy strategy to balance exploration and exploitation, experience replay, and a neural network to estimate action values. During training, the agent achieved a final reported win rate of 100% over its recent training games after 1,000 epochs. This demonstrated significant improvement in its ability to navigate the maze, although successful training does not automatically guarantee success from every starting position.

## Connecting My Learning to Computer Science

### What do computer scientists do, and why does it matter?

Computer scientists study computational problems and develop technologies that help solve real-world challenges. Their responsibilities include designing algorithms, developing software, analyzing data, improving system performance, and protecting information. Their work matters because technology influences almost every industry, including healthcare, banking, education, and cybersecurity. As someone pursuing a career in cybersecurity, I recognize the importance of developing intelligent systems that are not only effective but also secure and reliable.

### How do I approach a problem as a computer scientist?

I approach problems by first understanding the requirements and identifying what needs to be accomplished. I then break the problem into smaller components, evaluate possible solutions, implement an approach, and test the results. Throughout CS 370, I learned that solving a problem often requires experimentation, patience, and continuous improvement.

The Pirate Intelligent Agent project reinforced this approach. I had to understand how the maze environment worked, implement the training algorithm, and examine the agent's performance. I also learned that errors and unexpected results are opportunities to investigate the underlying problem rather than simply change code without understanding it.

### What are my ethical responsibilities to the end user and the organization?

As a computer scientist, I have a responsibility to develop systems that protect users, respect privacy, maintain data security, and operate as reliably as possible. I must also consider fairness, transparency, and the potential consequences of incorrect system decisions.

This course strengthened my understanding that artificial intelligence should be evaluated carefully before being used in real-world environments. A model that performs well during training may still make mistakes when exposed to unfamiliar situations. Organizations must therefore monitor AI systems, address potential bias, and maintain appropriate human oversight. As I continue developing my skills in computer science and cybersecurity, I want to create solutions that users can trust and that organizations can deploy responsibly.



