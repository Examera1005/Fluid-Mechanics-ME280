## 🇬🇧 English Version

### Project Overview
This repository hosts the complete, mathematically comprehensive LaTeX transcription and accompanying schematics for the **Fluid Mechanics (ME-280)** course lectured by **Prof. Tobias Schneider** at EPFL (Mechanical Engineering section).

The purpose of this project is to provide an exhaustive, high-fidelity academic reference compiling advanced continuous mechanics theory, partial differential equations governing fluid flows, and detailed physical proofs.

### Curriculum & Technical Syllabus
The document mirrors the rigorous academic breakdown of the EPFL syllabus:

1. **Fluid Kinematics & Field Descriptions:**
   * Lagrangian vs. Eulerian viewpoints, material (substantial) derivative operator:
     $$\frac{D\mathbf{u}}{Dt} = \frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla)\mathbf{u}$$
   * Streamlines, pathlines, and streaklines topology.
   * Decomposition of motion: Strain-rate tensor $\mathbf{D}$ and spin (vorticity) tensor $\mathbf{\Omega}$.

2. **Integral & Differential Conservation Laws:**
   * Reynolds Transport Theorem (RTT) derivation and application to arbitrary control volumes.
   * Continuity equation (Conservation of Mass):
     $$\frac{\partial \rho}{\partial t} + \nabla \cdot (\rho \mathbf{u}) = 0$$
   * Cauchy's equation of motion (Conservation of Linear Momentum).

3. **Inviscid Flow Dynamics (Ideal Fluids):**
   * Euler equations derivation under barotropic assumptions.
   * Integration along a streamline: Generalized Bernoulli Equation and its exact mechanical limits.
   * Irrotational potential flows, velocity potential $\phi$, stream function $\psi$, and 2D superposition principles.

4. **Viscous Flow Dynamics (Navier-Stokes Equations):**
   * Constitutive equations for Newtonian fluids, viscous stress tensor parametrization $\boldsymbol{\tau}$.
   * Incompressible Navier-Stokes equations with constant dynamic viscosity $\mu$:
     $$\rho \left( \frac{\partial \mathbf{u}}{\partial t} + (\mathbf{u} \cdot \nabla)\mathbf{u} \right) = -\nabla p + \mu \nabla^2 \mathbf{u} + \rho \mathbf{g}$$
   * Exact laminar solutions: Planar Couette flow, Hagen-Poiseuille pipe flow, and film flows.

5. **Dimensional Analysis & Similitude:**
   * Buckingham $\Pi$ Theorem and scaling analysis.
   * Deep dive into non-dimensional scaling parameters: Reynolds ($Re$), Froude ($Fr$), Mach ($Ma$), and Euler ($Eu$) numbers.
   * Application to engineering scale modeling and dynamic similitude laws.

6. **Boundary Layer Theory Foundations:**
   * Prandtl's boundary layer scaling, Blasius boundary layer profile over a flat plate, skin friction coefficients, and flow separation criteria.

---

## 🛠️ Compilation & Repository Structure / Structure du Dépôt

This document is an independent student study resource compiled from lectures delivered at EPFL. It is not officially endorsed, certified, or approved by Prof. Tobias Schneider or the École Polytechnique Fédérale de Lausanne.
