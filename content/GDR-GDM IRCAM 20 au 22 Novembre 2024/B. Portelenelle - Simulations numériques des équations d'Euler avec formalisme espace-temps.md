---
Conférence: GDR GDM
Date: 2024-11-21
Speaker: Brice Portelenelle
Title: Simulations numériques des équations d'Euler avec formalisme espace-temps
---
**Formalisme espace temps**
- The space time is modeled as a pesudo-rimannian 4D manifold (link with [[B. Kolev - Théorie du second gradient dans le cadre relativiste - Covariance générale versus Objectivité]] and [[R. Desmorat - Sur la formulation covariante générale de l'hyperélasticité relativiste]])
- Introduction of the momentum-energy tensor $$T = 2\frac{\partial \mathcal{L}}{\partial g}$$where $\mathcal{L}$ is the contribution of matter to the density of energy.
The idea is to do classical fluid dynamics, with the space-time formalism. First works: finite elements, finite volumes (done by Zwart et al. 1999). Interest for classical CFD
- invariance by change of frame
- same scheme in space and time
- possible to refine locally the space-time grid
- finite volumes: conservative in time also

**Numerical fluid mechanics**
- start from the [[Navier stockes equations]]
- When we make assumptions (no heat transfer, no viscosity, no gravity) then we obtain the [[Euler equations]]. This is a system of equations (conservation of mass, of momentum, and energy), that can be expressed as one equation, similar to an **equation of conservation**. He then takes this formalism with the space time formalism: this assumption makes the time derivative within the former equation of conservation to vanish !
- Then, it is possible to obtain the conservation law, expressed with the tensor momentum-energy, exactly corresponding to the conservation of mass, linear momentum, and energy. 
- *Example in finite difference*. 
	- Usually, modelisation where we resolve time step by time step the whole solution in time
	- In this framework, calculation of the solution at the same time ! 
	![[B. Portelenelle.excalidraw]]
- [[finite volume method]]
	- Main idea: integration on control volumes, written in terms of fluxes with the Stockes theorem
	- Interests: conservative (equality of entrance and ou), easily usable with a non structure mech.
	- We have the finite volume in space, and the time integration is determine ad hoc (here it is the [[implicit Euler]] scheme = unconditionnaly stable)
	- Need f**or the choice of a flux**: here it is the [[Rusanov's flux]], or there exists the **HLL flux**
	- Then, applies these ideas with the space time formalism: a space-time flux.
==Big results: able to create a **space-time adaptative mesh**: adaptation of the space + time mesh due to events/geometric particularities (implicit scheme so no problem)==

**Remarques**
- respect the principle of causality when you have a non structured space-time mesh
- conditions entropiques chocs