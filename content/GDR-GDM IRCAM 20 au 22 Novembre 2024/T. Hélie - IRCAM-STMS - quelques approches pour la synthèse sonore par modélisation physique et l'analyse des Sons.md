---
Conférence: GDR GDM
Date: 2024-11-21
Speaker: Thomas Hélie
Title: IRCAM-STMS - quelques approches pour la synthèse sonore par modélisation physique et l'analyse des Sons
---
[[Volterra series]]: how to capture the timbre evolution with respect to the sound dynamics?
- first effet observed is the brassy effect (effet de cuivrage d'un tube)
They made an extension to spatial terms (the volterra series were only on time) using Green functions.

**Power-balanced multiphysics**
- [[Port Hamiltonian System]] (PHS): a physical system is made of energy-storing components, passive components, external components. Each of the component either receive or store energy/power. In the PHS, we add conservative connection (th esum of received power is equal to zero)
- It is possible to represent PHS with a matrix representation, called the Input-State-Output representation. The matrix at stake is skew-symmetric, which ensures that we verify a power balance.