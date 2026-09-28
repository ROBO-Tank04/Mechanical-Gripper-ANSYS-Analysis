# 🔬 Structural FEA Analysis of Mechanical Gripper (ANSYS)

## Project Overview
This project presents the finite element analysis (FEA) and structural validation of the custom 2-finger parallel jaw mechanical gripper. Built upon the CAD assembly model, this analysis was performed using **ANSYS Workbench** as part of advanced industrial training with **My Equation**.

## Objectives
* Perform static structural simulation on the mechanical gripper assembly under simulated loading conditions.
* Evaluate critical structural parameters including total deformation, equivalent stress, elastic strain, and safety factor.
* Validate the structural integrity and reliability of the end-effector design for robotic material-handling applications.

## Software Used
* **ANSYS Workbench (Student Edition)** — For mesh generation, boundary condition setup, and static structural analysis.

## Analysis Setup & Methodology
* **Geometry Import:** Imported the multi-component CAD assembly model into ANSYS.
* **Meshing:** Generated and refined a finite element mesh across all components to ensure calculation accuracy.
* **Boundary Conditions:** 
  * Applied fixed supports to mounting regions.
  * Applied simulated loads and forces representative of operational payloads.

## Results & Findings
* **Total Deformation:** Evaluated the maximum and minimum displacement across the gripper structure under load.
* **Equivalent (von-Mises) Stress:** Analyzed stress concentrations to ensure peak stresses remain well within material yield limits.
* **Equivalent Elastic Strain:** Measured deformation behavior across component joints and links.
* **Safety Factor:** Inspected safety factor distributions to guarantee robust design margins and structural longevity.

## Learning Outcome
* Gained hands-on proficiency in setting up static structural simulations, applying mechanical constraints, and interpreting FEA solver outputs.
* Successfully linked digital 3D CAD modeling with real-world engineering validation workflows.

## Repository Contents
* ANSYS project files and simulation data reports documenting structural deformation, stress distribution, and safety factor evaluations.
