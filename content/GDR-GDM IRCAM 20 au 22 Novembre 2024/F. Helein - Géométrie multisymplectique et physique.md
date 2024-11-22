---
Conférence: GDR GDM
Date: 2024-11-21
Speaker: Fréderic Hélein
Title: Géométrie multisymplectique et physique
---
Le mot multisymplectique n'est pas fixe dans la littérature.
- Base : formulation Lagrangienne, variationnelle de la mécanique. From this point of view, the trajectories are from the real line to a manifold. The Euler-Lagrange equations are the critical points of the actions.
**The multisymplectic formalism**
- Consider a field, a map depending on multiple variables $u:X^n \to Y^n$. The action is on $L(x, u(x), du_x) dvol$. Then, we obtain the EL system of equations. **The question is : can we make the analogous of what Hamilton has done within mechanics with multiple variables?** That is what we do, by introducing momentums that are derivatives of the Lagrangians with respect to derivatives of the field + **suppose that there is a diffeomorphism between momentum and ''velocities'', such that the relationship is invertible**. The multisymplectic equations are called the ==first Volterra equations 1890==.
- The equations are often called De Donder-Weyl equations. Later developped by ==G. Prange (1915)==,==Carathéodory (1929)==, and ==H. Weyl (1935)==. ==De donder (1935)== generalised to Lagrangian densities depending on higher derivatives. Each of these ideas were initiated by ==Dedecker (1953)==. Fully accomplished by the Polish school by ==W. Tulczyjew (1965)==.
Geometrization
- First, consider the variables space time, arrival space coordinates, and the dual variables. If you watch the value of the field within the arrival space, and the value of the multi-momentum with respect to the derivative of the Lagrangian, we can traduce the Hamilton-Volterra-De Donder-Weyl  with a ==pre-multisymplectic (n+1)== form : The idea is that it is a (n+1) form  $$\omega= dp_i^\mu\wedge dy^i\wedge dvol(\partial_\mu,\dots) - d(H(x,y,p))\wedge dvol$$if n=1, the first term is equal to 1. One key idea is the definition of the volume form, which can be non trivial. Then **the HVDDW equations can be written that the restriction of the interior product of the pre-multisymplectic form** for any vector field $\xi$, its restriction to te submanifold of fields $\Gamma$ that verify the equations of Euler Lagrange read $$\omega(\xi,\dots)\vert_{\Gamma} = 0$$One geometric generalisation can be obtained by ==replacing the field maps by sections of a vector bundle==. With the idea, we obtain an $n$ form, such that $$\omega = d\theta$$called the multisymplectic form, which is not exactly the multisymplectic form presented before. The authors made by most of the authors is to add additional constraints on this multisymplectic form, to obtain the pre-multisymplectic form obtained right before. This construction from the general to the particular hints at the possibility of creating different multisymplectic form. 
**Definition of multisymplecic manifolds**
- A ==n-plectic== manifold is a manifold equipped with a (n+1) form such that the form is closed, and non degenerate. A Hamiltonian function on an n-plectic manifold is a function from the manifold to real numbers such that its exterior derivative is not equal to zero. Then, the equations of dynamics can be written as 
$$\text{for any vector field }\xi, dH(\xi) = 0 \Rightarrow \omega(\xi,\dots)\vert_{\Gamma} = 0$$
- example with the ==Klein-Gordon equations==. 

==An exact form is closed==.
==Les courbes hamiltoniennes sont des graphes au dessus de l'espace temps==. 

- Another general framework, definition of a pre-plectic manifold. Basic results
	- We can **find a variational principle** $A[\Gamma] = \int_{\gamma}\theta$ 
	- definition of ==observable==: $F$ is observable if there exists a vector field $\xi_F$ st $dF + \omega(\xi_F,\dots) = 0$. The vector field corresponds to a ==symmetry== of the system, in the sense of ==Noether's theorem==.
	- We **can build a bracket, analogous to the Poisson bracket** (antidymetric), but which is not exactly a Lie algebra, beacsue the left side of the Jacobi identity is equal not to zero, but to the derivative of the multisymplectic form: the bracket is exact/.
	- We can build observable functionals, such that we can build some kind of a Noether theorem. 
- Main principle: the set of solutions of a EL system is endowed with a canonical pre-symplectic structure. 

**Summary**
- the main question is : can we build something analogous of what is done within the symplectic formalism? The multisymplectic formalism provides a way to compare the different formulations of the classical equations of dynamics, with the Lagrangian formulation, the generalised Hamilton equations (multisymplectic versions), and the ==Poincaré-Cartan== point of view.

**Multisymplectic with gauge theories**
- ==Yang Mills== theory in the multisymplectic theory
- Idea to start: the interest of the multisymplectic theory is that you can work without making the choice of a time coordinate. But, with Yang Mills, for a field, you have a gauge. 

==Galiso 1955==
Schémas d'intégration multisymplectiques qui sont obtenus par Aziz permettent de retrouver naturellement des schémas aux volumes finis "bricolés".