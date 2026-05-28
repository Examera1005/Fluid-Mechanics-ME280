# EPFL ME-280: Fluid Mechanics — Complete Course Notes
## Mechanical Engineering BSc (Spring 2026)

This repository contains the complete, mathematically rigorous LaTeX transcription and vector schematics for the **ME-280 Fluid Mechanics** course taught by **Prof. Tobias Schneider** at the École Polytechnique Fédérale de Lausanne (EPFL).

The source document compiles comprehensive handwritten lecture notes into a professional, publication-quality LaTeX document utilizing advanced differential operators, continuum mechanics formulations, and custom vector diagrams.

---

## ���� Version Française

### Description du Projet
Ce dépôt héberge la transcription complète et rigoureuse en LaTeX ainsi que les schémas associés pour le cours de **Mécanique des Fluides (ME-280)** dispensé par le **Prof. Tobias Schneider** à l'EPFL (Section de Génie Mécanique).

 L'objectif de ce projet est de fournir une ressource d'étude claire, structurée et exhaustive, couvrant l'ensemble des fondements théoriques, des formulations mathématiques complexes (équations aux dérivées partielles) et des applications physiques du cours.

### Contenu du Cours & Structure Théorique
Le document est structuré de manière linéaire suivant le formalisme rigoureux du cours de l'EPFL :

1. **Cinématique des Fluides & Descriptions Éléments :**
   * Descriptions Lagrangienne et Eulérienne, dérivée matérielle (substantielle) d'un champ scalaire ou vectoriel :
     $$\frac{D\mathbf{u}}{Dt} = \frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla)\mathbf{u}$$
   * Lignes de courant, trajectoires, lignes d'émission (streaklines).
   * Tenseur des taux de déformation $\mathbf{D}$ et tenseur de taux de rotation (vorticité) $\mathbf{\Omega}$.

2. **Lois de Conservation Généralisées (Théorème de Transport de Reynolds - RTT) :**
   * Formulation intégrale et différentielle de la conservation de la masse (Équation de continuité) :
     $$\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{u}) = 0$$
   * Conservation de la quantité de mouvement et théorème du moment cinétique.

3. **Dynamique des Fluides Parfaits (Inviscides) :**
   * Équations d'Euler pour un fluide compressible et incompressible.
   * Intégration le long d'une ligne de courant : Théorème de Bernoulli généralisé et restrictions d'application.
   * Écoulements potentiels irrotationnels, fonction de courant $\psi$ et potentiel des vitesses $\phi$.

4. **Dynamique des Fluides Visqueux (Équations de Navier-Stokes) :**
   * Postulats de Stokes pour un fluide Newtonien, tenseur des contraintes visqueuses $\boldsymbol{\tau} = 2\mu \mathbf{D} + \lambda (\nabla \cdot \mathbf{u})\mathbf{I}$.
   * Formulation complète des équations de Navier-Stokes pour un fluide incompressible à propriétés constantes :
     $$\rho \left( \frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla)\mathbf{u} \right) = -\nabla p + \mu \nabla^2 \mathbf{u} + \rho \mathbf{g}$$
   * Solutions exactes analytiques : Écoulement de Couette, écoulement de Poiseuille (canal et conduite cylindrique).

5. **Analyse Dimensionnelle & Similitude :**
   * Théorème $\Pi$ de Buckingham, identification des nombres adimensionnels cardinaux : Nombre de Reynolds ($Re$), de Froude ($Fr$), de Mach ($Ma$), et d'Euler ($Eu$).
   * Conditions de similitude géométrique, cinématique et dynamique pour les essais sur modèles réduits.

6. **Théorie de la Couche Limite (Introduction) :**
   * Approximation de Prandtl, équations de la couche limite sur plaque plane, épaisseur de déplacement $\delta^*$ et de quantité de mouvement $\theta$.

