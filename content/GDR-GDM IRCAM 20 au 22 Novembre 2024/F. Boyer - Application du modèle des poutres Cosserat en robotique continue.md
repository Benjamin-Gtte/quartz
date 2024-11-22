---
Conférence: GDR GDM
Date: 2024-11-21
Speaker: Frédéric Boyer
Title: Application du modèle des poutres Cosserat en robotique continue
---
- Robotique continue: robots principalement liés à la chirurgie non invasive. 
- Another class of robotics: soft robotics. Nothing metallic, the idea is to create soft robots, such that it can interact with humans without putting him in danger. 
- **robots bio-inspired**: redondant robots. 
Then presentation focuses on redondant robots, bio inspired.
![[f.boyer.excalidraw|300]]
- it is based on the model of [[Cosserat beams]]: continuous stacking of rigid sections submitted to finite transformations. The idea is to work within the groupe of rotations for each section $se(3)$, which takes into account rotations and translations. Then, on the whole beam, we obtain a velocity field, as well as a spatial analogous to the velocity field, which is like strains. ![[Pasted image 20241121142255.png|200]]The equations of dynamics are deducted from the Hamilton's principle on the group. Before working on the space of parameters, we work on the group: the lagrangian depends on the actions of the group $g$: $\mathcal{L}(g,\dot{g},g')$. Calculating the variations of Euler-Poincaré grives the system of partial differential equations of Poincaré-Cosserat. The principle gives the closed formed of Reissner-Simo. 
- *La mécanique du solide est invariante à gauche* (arnold)
- In the Reissner Simo, the field $\xi$ is free. Because of it, it is possible to introduce kinematical internal constraints (authorised and constrained movements). By this framework, it is possible do recover standard beam models (such that the Kirchhoff beams for example).  
- The idea is that, we have a section on which we know the field of nterest (strain $\xi$), and we **reconstruct** the field over the whole robot. 
- ==Found that each of the actionning constraints (of robotics) can be put within the equations.==
- One big algorithm of robotics: the [[Newton-Euler's algorithm]]. The idea is to formulate the static inverse problem: we know the bonudary values, then we need to reconstruct the shape of the robot between the boundaries such that we have the actions at the edges that we want !![[F. Boyer 2.excalidraw]]