# Computed torque for restricted Lagrange-Euler systems via DAEs and LMIs

**Manuscript ID:** IEEE Latin America Transactions Submission ID: 10501 \
**Authors:**  
- Julián León 
- David Vázquez  
- Miguel Bernal

**Affiliation:** \
Sonora Institute of Technology\
Department of Electrical and Electronics Engineering\
Mexico

---

## 📁 Included Scripts

This repository contains all scripts required to reproduce the simulation and implementation results presented in the article.

| Script | Related Figure(s) | Description |
|--------|-------------------|-------------|
| `Case_Study_LMI` | None | Computes the gains K_p and K_d presented in the Case Study section of the article based on the LMIs in Equation (6). |
| `Study 3 actuators case` | Fig. 3 and Fig. 4 | Contains all the necessary information to simulate the 2-link planar RR arm system subject to a position constraint with three actuators. |
| `Study 2 actuators case` | Fig. 5 and Fig. 6 | Contains all the necessary information to simulate the 2-link planar RR arm system subject to a position constraint with two actuators. |
| `Rotary Arm LMI` | None | Computes the gains K_p and K_d presented in the Implementation on a Rotary Arm System section of the article based on the LMIs in Equation (6). |
| `control_RotaryArm` | None | Contains the function used for real-time implementation on the rotary arm system. |
| `Rotary Arm Real Data` | Fig. 8 | Contains the data from the real-time implementation of the rotary arm system. |

---

## 💻 Requirements

- MATLAB R2025a or later.
- Yalmip.

---

## ✉️ Contact

For questions or replication of results:  
miguel.bernal@itson.edu.mx
