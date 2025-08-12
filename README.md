# MSMPR Crystallization Modelling & Parameter Estimation

## 📌 Project Overview
This project models a **Mixed-Suspension Mixed-Product Removal (MSMPR) crystallizer** using **Population Balance Equations (PBEs)** to simulate crystal growth, nucleation, and size distribution evolution. The model is validated against experimental **time vs concentration** data and kinetic parameters are estimated using nonlinear optimization.

## 🛠 Tools & Technologies
- **Programming Language:** Python
- **Libraries:** NumPy, SciPy (`solve_ivp`, `minimize`), Matplotlib
- **Methods:** ODE-based population balance modelling, parameter estimation, nonlinear optimization (L-BFGS-B)

## 📊 Key Features
- **5-ODE population balance model** representing nucleation, growth (length & width), and mass balance.
- **Parameter Estimation**: Optimizes 8 kinetic parameters  
  `A1`, `g1`, `A2`, `g2`, `kb1`, `b1`, `kb2`, `b2`  
  using **L-BFGS-B** to minimize sum of squared errors.
- **Process Analysis**:  
  - Concentration vs Time (model vs experimental)  
  - Supersaturation profiles  
  - Birth & growth rate curves  
  - Moment ratios (`M10/M00`) for crystal size distribution analysis.

## 📂 Repository Structure
all the file is given the folder 
