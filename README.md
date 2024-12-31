Real-time Excavation Trajectory Modulation for Slip and Rollover Prevention
=====
Datasets for data-driven model $\Delta \hat{f}_b$
-----
https://drive.google.com/drive/folders/1x1kj_N335QLfyz9zf6Amw_eYTLHYVXTY?usp=drive_link

## File Description
* data.txt
  - includes the whole dataset which is obtained at 100Hz and normalized.
* data_ind.txt
  - includes the row index of trajectories.
## Dataset structure
| Column Number | Description | Units |
|-----|-----|-----|
| 1-2  | Bucket tip configuration - position ($q_{b_x}, q_{b_y}$) | [m] |
| 3  | Bucket tip configuration - orientation ($q_{b_{\psi}}$) | [rad] |
| 4-5  | Bucket tip velocity - position ($\dot{q_b}_{x}$, $\dot{q_b}_y$) | [m/s] |
| 6  | Bucket tip velocity - orientation ($\dot{q_b}_{\psi}$) | [rad/s] |
| 7-8  | Excavation force ($f_{b_x}$, $f_{b_y}$)| [N] |
| 9  | Past trajectory area ($a_{q}$) | [m²] |




