
# Comparative Analysis of Breadth-first search and Reinforcement Learning Algorithms for Automating Pacman Gameplay.

1. Project Introduction:

In this article, we used two methods to automate playing the Pacman game: Breadth-first search (BFS) and Reinforcement Learning (RL). Each method was implemented and trained over a long period and on a large scale to ensure the best results. After a series of experiments, we evaluated the performance of the two algorithms based on different criteria such as: Winning time, winning rate, adaptability and pathfinding ability of Pacman. From the results obtained , we conclude that each method has its own advantages and dis-advantages depending on each case. The advantage of BFS is that it is easy to implement and can be considered an optimal solution in a simple environment. If in a complex environment, BFS will become ineffective and time-limited. In contrast, RL exhibits superior performance in a complex environment thanks to its ability to learn so that it can adapt to the current environment.

2. Usage:

First, you need to install the Python programming language on your computer because we use this language to build the game. Next, install the numpy and pygame libraries, which will help us run the program. After that, you need to download the "Code" folder. Finally, with the algorithms we have set up, you only need to select the corresponding Python files. For example, the BFS algorithm is in the "BFS_(completed).py" file ("BFS" folder), and the Reinforcement learning algorithm is in the "q_learning.py" file("RL folder"). Remember to include the "assets" folder in the same folder with your selected file.

3.Environment setup:

To build the full game of Pacman, we refer a Pacman construction video on Youtube. Here is the link of the video: https://www.youtube.com/watch?v=9H27CimgPsQ&t=10151s&pp=ygUUcGFjbWFuIGJ1aWxkaW5nIGNvZGU%3D. Based on the codes in the video, we have modified the the characters movement, so that the full environment is as deterministic as possible.The environment without AI algorithm can be found in the "environment" folder of the "Code" folder. The BFS and Reinforcement learning is implemented directly into this environment and are placed in "BFS" and "RL"(Reinforcement Learning) folder.

In this project, we do not need any database. The BFS will run continuously to give the agent the best direction throughout the process of playing, meanwhile the reinforcement learning will make the agent play many games and use the data from that history of playing to train the agent. The history data is a Q table, containing values estimated when taking an action at a state. As the number of Q values are quite large (204800 elements) and the table is 11-dimensional, we have to store it in a binary file ("q_table.npy" file in the "RL" folder). 

4. References:

- Goldberg, Marty. Pac-Man: The Phenomenon: Part 1, 2022.
- Jason Holdsworth. The Nature of Breadth-First Search, 1999.
- Mnih et al. Playing Atari with Deep Reinforcement Learning, 2013.
- Nikolaos Tziortziotis, Konstantinos Tziortziotis, and Konstantinos Blekas. Play Pac-Man using an advanced reinforcement learning agent.
- Nguyen Thi Thuan . Phuong phap hoc tang cuong (Master’s thesis, Hanoi University of science and technology), 2006

5. Contact Information: 

- Phan Gia Do - do.pg226026@sis.hust.edu.vn
- Tran Gia Khanh –  khanh.tg226048@sis.hust.edu.vn
- Nguyen Cong Dat - dat.nc226022@sis.hust.edu.vn
- Nguyen Trung Hieu - hieu.nt225971@sis.hust.edu.vn
- Le Van Hau - haulv226038@sis.hust.edu.vn
