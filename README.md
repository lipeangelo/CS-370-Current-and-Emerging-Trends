# CS 370 – Current and Emerging Trends in Computer Science

## Pirate Intelligent Agent | Deep Q-Learning

**Southern New Hampshire University (SNHU)**  
**Course:** CS 370 – Current and Emerging Trends in Computer Science  
**Language:** Python  
**Technologies:** TensorFlow, Keras, NumPy, Jupyter Notebook  
**Concepts:** Artificial Intelligence, Neural Networks, Reinforcement Learning, Deep Q-Learning

## Project Overview

The Pirate Intelligent Agent project demonstrates the application of deep reinforcement learning to an intelligent pathfinding problem. The objective was to train a pirate agent to navigate an 8×8 maze, avoid obstacles, and reach a treasure located in the bottom-right corner.

Rather than programming a predetermined path, I implemented a deep Q-learning algorithm that allows the agent to learn through repeated interactions with its environment. The agent receives rewards and penalties for its actions and gradually improves its decision-making strategy.

## Project Development

### What code was provided, and what did I create?

The project included starter code for the maze environment, experience replay functionality, and supporting neural network and testing utilities. The `TreasureMaze.py` module defined the maze environment, while `GameExperience.py` supported storing and sampling experiences during training.

My primary contribution was implementing the deep Q-learning training algorithm within the Jupyter Notebook. This involved integrating the neural network with the maze environment, implementing an epsilon-greedy exploration strategy, training the agent using experience replay, and updating a target network to improve training stability.

I also tested the trained model using the provided evaluation functions to verify that the agent could successfully navigate the maze.

### Results

The trained agent demonstrated successful navigation through the maze.

- Training achieved a 100% recent win rate.
- The completion check returned `True`.
- The agent successfully reached the treasure from the starting position `(0, 0)`.

These results demonstrated how reinforcement learning can enable an intelligent agent to learn effective decisions without explicitly programming every movement.

## Reflection

### What do computer scientists do, and why does it matter?

Computer scientists analyze problems, design algorithms, develop software, and create technologies that improve how individuals and organizations operate. Their responsibilities extend beyond programming because they must consider efficiency, reliability, security, and the broader impact of technology.

Throughout CS 370, I gained a deeper understanding of how artificial intelligence allows computers to recognize patterns, learn from experience, and make decisions. Technologies such as neural networks and reinforcement learning have applications in robotics, healthcare, transportation, and automation. Computer scientists play an important role in ensuring these technologies are developed responsibly and used to solve meaningful problems.

### How do I approach a problem as a computer scientist?

I approach problems by identifying the objective, understanding the requirements, and breaking complex challenges into smaller, manageable components. I then evaluate possible solutions, select appropriate tools and algorithms, implement the solution, and test its performance.

The Pirate Intelligent Agent project reinforced this approach. Instead of manually programming a route through the maze, I used reinforcement learning to train an agent to discover effective actions through experience. Developing the training algorithm required debugging, experimentation, and evaluating the agent's performance.

This experience strengthened my understanding that effective problem-solving involves continuous testing, learning, and improvement.

### What are my ethical responsibilities to the end user and the organization?

As an aspiring software engineer, I have a responsibility to develop systems that are secure, reliable, transparent, and respectful of users' rights. This includes protecting sensitive information, minimizing unnecessary data collection, addressing algorithmic bias, and ensuring that software performs as intended.

CS 370 helped me recognize that AI systems can produce inaccurate or biased results depending on their training data, algorithms, and design. Developers must evaluate these systems carefully, recognize their limitations, and consider how automated decisions may affect users and organizations.

I also believe that accountability and human oversight are essential, particularly when AI is used to make important decisions. My responsibility is not simply to create technology that works, but to ensure that it is trustworthy, ethical, and beneficial to society.

## Conclusion

This project provided hands-on experience with reinforcement learning, neural networks, and intelligent decision-making. It strengthened my Python programming, debugging, algorithm development, and problem-solving skills.

As I continue pursuing a career in software engineering, I look forward to applying these concepts to building intelligent, reliable, and user-focused applications.

## Project Files

**`Filipe_Angelo_ProjectTwo.ipynb`** — Jupyter Notebook containing the Pirate Intelligent Agent implementation, training process, model evaluation, and maze visualization.
