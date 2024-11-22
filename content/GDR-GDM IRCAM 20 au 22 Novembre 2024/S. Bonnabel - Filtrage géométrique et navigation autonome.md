---
Conférence: GDR GDM
Date: 2024-11-21
Speaker: Sylvère Bonnabel
Title: Filtrage géométrique et navigation autonome
---
Problème: étude de faisabilité d'une mission lunaire un des verrous étant la navigation. 
Spatial navigation 
- equations of movement of the rocket: on the rocket, we have inertial captors
- during the flight, we observe movement of stars to be able to correct the trajectory
Kalman 1960: [[Kalman filter]]
- The state is composed of the position, velocity, and orientation 
- The observations are implemented into a vector of position and orientation.
- Then we apply the correction, to change the state regarding what we have observed. 
- The key idea of the problem is that there are uncertainties within the state vector, and the correction vector. So, the question is how to propagate this uncertainty?
If we take a robot that moves forward, how to predict the uncertainty of the final displacement of the robot? The final possible displacement are displayed on what is called the **banana distribution**
![[S. Bonnabel banana.excalidraw]]
This distribution is said to be Gaussian when considered from the ==Lie group SE(2)==.
**Main idea** Use of general Lie groups to define uncertainties in mavigation. 
- ==Correspondency theorem between Lie groups and Lie algebra== It shows that 
