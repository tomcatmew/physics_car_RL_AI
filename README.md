# physics_car_RL_AI
Reinforcement Learning AI for physics simulated car\
Using Wheel Colliders + Mesh Colliders and Unity built-in physics system\
I used **checkpoint method** for training 

Contents - 目次
- [Environment Setup - 環境の設定](#set-ups)
- [Method - 実現方法](#method)
- [Trained Result - 学習結果](#trained-result)

# Set-ups
**Training map** and **Map with checkpoint setup**\
<img src="pictures/p1.png" alt="drawing" width="380"/>  <img src="pictures/p3.png" alt="drawing" width="460"/>\
**Physics car with wheel collider**\
![tp2](pictures/physics_car600.gif)

# Method
Agent shoots 7 rays. It will detect the distance to both the walls and checkpoints\
**Reward** is porpotional to the distance to the checkpoint\
<img src="pictures/p2.png" alt="drawing2" width="600"/>\

# Trained Result
3x Speed\
![tp3](pictures/trained_a.gif)

![tp4](pictures/trained_b.gif)
