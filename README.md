# Hypersonic-Re-Entry-Capsule-CFD-Analysis-using-Ansys-Fluent
This repository contains a detailed Computational Fluid Dynamics (CFD) analysis of a hypersonic re-entry capsule using Ansys Fluent. The project simulates high-speed compressible flow around a blunt body for Mach numbers 2, 5, 10, and 17, capturing complex flow phenomena like shock waves, boundary layer behavior, and thermal effects.

📄 Project Overview
This project was completed as part of an advanced CFD assessment, covering all key stages of simulation from domain generation to post-processing and result interpretation.

🔬 Key Highlights
Geometry: Capsule modeled in Ansys SpaceClaim using simplified blunt-body geometry
Flow Domain: Far-field domain created to avoid boundary effects

Governing Equations:
Continuity
Momentum
Energy
Equation of state for compressible flow

🧩 Simulation Pipeline
Domain Generation: Circular surrounding fluid region with well-defined boundaries for far-field hypersonic flow.
Meshing Strategy:
Inflation layers for boundary layer resolution
Local refinement near shock zone
Unstructured/prismatic grid used efficiently

Solver Configuration:
Density-based solver for accurate shock capturing
SST k-ω turbulence model
Hybrid initialization
High Mach flow adjustments enabled

Boundary Conditions:
Inlet Mach (2, 5, 10, 17)
No-slip wall for capsule
Symmetry or far-field on outer domain
Pressure outlet

Post-Processing:
Pressure contours for all Mach cases
Analysis of flow separation, stagnation pressure, and wake behavior
Comparison of aerodynamic characteristics at each Mach level


📄 Full_Report.pdf: Complete documentation with equations, plots, and insights

💡 Skills & Insights Gained
Practical application of CFD for hypersonic aerodynamics
Mesh refinement techniques for complex flow gradients
Solver tuning for high-speed convergence
Advanced boundary setup for re-entry simulations
Post-processing and interpretation of flow physics

🧠 Challenges Overcome
Mesh instability at high Mach numbers
Achieving convergence for Mach 10+ cases
Accurate capture of thin shock layers and stagnation effects
Balancing computation cost with mesh density

📌 Tools Used
Ansys Fluent & SpaceClaim
CFD Post for visualization
Basic scripting/spreadsheet tools for result tabulation.
