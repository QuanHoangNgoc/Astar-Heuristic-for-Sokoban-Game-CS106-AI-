# Introduction
- Quan Hoang Ngoc
- Assignment 2 of _TTNT_  
- _HK2_, 2024
  
### about 
- In this project, we install an A* search algorithm to apply it to solve the Sokoban game.
- We design a new heuristic function for the A* algorithm and make a benchmark to evaluate its performance with the default heuristic function as well as the UCS algorithm. 
- The most important thing in the A* algorithm is designed to be a good heuristic function. There is a tradeoff between optimality and speed when designing heuristic functions.
- We also presented various ideas for the design heuristic function, where the heuristic function Q* that we proposed can find optimal solutions in all maps while the search time is not significant.

### show-off 
- [A* and Sokoban Game - Heuristic is piece of cake! - [AI course - CS106 - UIT]](https://youtu.be/wp_hpPnzQHg?feature=shared)

# Repo Structure 
- MAIN: some resources, guidelines, documents and reports of this project.
- SOURCE CODE: source code of this project.
- [Astar_Heuristic_for_Sokoban_Game](https://uithcm-my.sharepoint.com/:f:/g/personal/22521178_ms_uit_edu_vn/EtPMjp9oBZJOs-FB7S_2BhYBKIJ0Dz2M3XlWftQCxivsCA?e=rn6OCR)
  - Backup this project
  - Contain submit files   

# Pipeline
- UCS and A* implementation with guides. 
- Reuse source code from previous projects.
- Conducted experiments to evaluate. Hardware resource: ASUS ViVoBook, core intel i5, 12GB RAM.
- Present report and pack project. 

# How to install this project: 
- Download all source code and run file Sokoban.py to play a game. 
- If people want to change some attributes of this project to config, please change at constant.py. 
- The source code is organize as a MVC model with View is Sokoban.py and Controller is Game.py. 
- Thus, to change the algorithm that you want to use, please change at game.py >> auto_move(). 
- Customize algorithms at solver.py.
