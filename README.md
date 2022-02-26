# Embodied-AI-Reactive-Hybrid-Architecture

<i>"Intelligence always manifests itself in behaviour and that we must understand the behaviour." - Rolf Pfeifer</i>

Author: Avinash Rai

Aseba Programming Language for Thymio 2 Robot

Notes:-
- Purpose: To design, implement, experiment and optimize a self-sustaining agent (robot) tasked to clean garbage repeatedly from its environment with high efficiency. 
- Experimented in different unpredictible environments which will also include other agents serving to deter the primary agent from its goal (and survival). 
- An agent has only two primary sensors (front and ground) at its disposable to percieve its environment. 
- Agents have been designed with guidance from different Design Architectures defined in the Embodied Cognition literature.


Three main robots functionalities:-
MAIN BEHAVIOUR      | FILE                            | DESIGN ARCHITECTURE
--------------------| --------------------------------|------------------------------------------------
Wall following      | robot_1_wall_following.aesl     | Reactive - "Subsumption Architecture"
Garbage Collection  | robot_2_garbage_collection.aesl | Hybrid - Motivated, Heirarchical and Reactive 
Wandering           | robot_3_wanderer.aesl           | Reactive

<b>Fig: Behaviour Action Selection Dynamics for Garbage Collection</b>
![action_selection_dynamics](https://user-images.githubusercontent.com/12041019/155834894-a212f629-bee6-43b7-afeb-b3e2b571beb2.jpg)

<b>Two environments:- </b>
1) simple_environment.playground
2) complex_environment.playground
