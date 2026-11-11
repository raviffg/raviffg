# Raveendra Kumar Doddi (Ravi)

**Physical AI Training Data, Simulation Ground Truth & Solver-Grounded Evaluation Infrastructure**

[Portfolio & Technical Reports (`raviffg.github.io`)](https://raviffg.github.io) · [Email (`dodik8700@gmail.com`)](mailto:dodik8700@gmail.com)

---

Building deterministic evaluation harnesses, multi-physics failure corpora, and hardware-in-the-loop telemetry pipelines for physical AI and autonomous engineering systems. Work spans parametric B-Rep CAD/FEA verification, deformable surgical simulation ground truth, high-speed ECAD post-layout signoff, and contact-rich robotic manipulation. Every benchmark ships with fixed inputs, published thresholds, and a verdict a solver has to earn rather than a screenshot a reader has to trust.

## Frontier Physical AI & Solver Evaluation Benchmarks (2025–2026)

| Repository | What it evaluates | Stack |
| --- | --- | --- |
| [`forge-cad-eval`](https://github.com/raviffg/forge-cad-eval) | Solver-grounded parametric B-Rep feature-DAG extractor and 164-mate multi-CAD assembly evaluation harness with a five-rung topology/DFM/FEA gate ladder | Python |
| [`surgical-sim-bench`](https://github.com/raviffg/surgical-sim-bench) | 3D MRI Euclidean signed distance fields (SDF) and coupled Pennes bioheat surgical boundary benchmark | Python / VTK |
| [`physics-fea-bench`](https://github.com/raviffg/physics-fea-bench) | Automated Gmsh + CalculiX 3D tetrahedral FEA and 1,200 W liquid cold-plate conjugate heat transfer (CHT) grader | Python |
| [`pcb-physical-bench`](https://github.com/raviffg/pcb-physical-bench) | Deterministic post-layout verifier for high-speed return-plane discontinuities and IPC-2152 thermal runaway | Python |

## Robotics, Kinematics & Mechatronic Control Systems (2018–2024)

| Repository | What it implements | Stack |
| --- | --- | --- |
| [`kinematic-4dof-manipulator`](https://github.com/raviffg/kinematic-4dof-manipulator) | 4-DOF serial manipulator inverse kinematics and stall-current collision detection | C++ |
| [`nonholonomic-rrt-planner`](https://github.com/raviffg/nonholonomic-rrt-planner) | Kinodynamic RRT* trajectory planner with differential-drive curvature and velocity constraints | Python |
| [`tendon-compliant-gripper`](https://github.com/raviffg/tendon-compliant-gripper) | Antagonistic tendon excursion-tension coupling and adaptive grasp force controller | C++ |
| [`rplidar-occupancy-slam`](https://github.com/raviffg/rplidar-occupancy-slam) | 2D LiDAR log-odds occupancy-grid mapping and scan-matching loop closure | C++ |
| [`bldc-foc-telemetry`](https://github.com/raviffg/bldc-foc-telemetry) | Closed-loop BLDC field-oriented control (FOC), regenerative braking and low-side shunt telemetry | C |
| [`bms-thermal-guard`](https://github.com/raviffg/bms-thermal-guard) | Multi-cell Li-Ion Coulomb-counting SoC estimator and dT/dt thermal runaway fault guard | C |
| [`cnc-backlash-characterizer`](https://github.com/raviffg/cnc-backlash-characterizer) | Stepper microstepping hysteresis profiler and G-code corner-overshoot compensator | C++ |
| [`imu-ekf-attitude`](https://github.com/raviffg/imu-ekf-attitude) | 6-DOF MEMS IMU quaternion Extended Kalman Filter (EKF) and Allan variance bias calibration | C++ |

## Selected Publications & Patents (2016–2026)

**[J5 — 2024 · IJDIM]** R. K. Doddi, S. Rao, *"Physics-Constrained Verification and Telemetry Benchmark Suite for Data-Driven Electro-Thermal and Cyber-Physical Systems,"* Int. J. Data Sci. IoT Manag. Syst. (IJDIM), Vol. 3, No. 4, pp. 272–276, Nov 2024. [DOI: 10.64751/ijdim.2024.v3.n4.1468](https://doi.org/10.64751/ijdim.2024.v3.n4.1468)

**[J4 — 2023 · IJERST]** R. K. Doddi, D. M. Chen, S. Rao, *"Kinodynamic Trajectory Generation and Dynamic Feasibility Filtering for Serial Manipulators and Non-Holonomic Mobile Platforms,"* Int. J. Eng. Res. Sci. Tech. (IJERST), Vol. 19, No. 2, pp. 275–278, Apr 2023. [DOI: 10.62643/ijerst.2023.v19.n2.4827](https://doi.org/10.62643/ijerst.2023.v19.n2.4827)

**[J3 — 2021 · IJESAT]** R. K. Doddi, *"Consensus-Driven Quality Control and Constraint-Based Validation for Domain-Expert Engineering and Simulation Datasets,"* Int. J. Eng. Sci. Adv. Tech. (IJESAT), Vol. 21, Issue 5, May 2021. [DOI: 10.64771/ijesat.2021.v21.i05.4031](https://doi.org/10.64771/ijesat.2021.v21.i05.4031)

**[J2 — 2018 · IJERST]** R. K. Doddi, V. S. Nair, *"Automated Topological Healing and Tetrahedral Mesh Quality Verification for Parametric CAD-to-FEA Simulation Pipelines,"* Int. J. Eng. Res. Sci. Tech. (IJERST), Vol. 14, No. 3, pp. 127–131, Sep 2018. [DOI: 10.62643/ijerst.2018.v14.n3.4828](https://doi.org/10.62643/ijerst.2018.v14.n3.4828)

**[J1 — 2016 · IJESAT]** R. K. Doddi, S. K. Varma, K. Reddy, *"Automated Multi-Sensor Telemetry Filtering and Hardware-in-the-Loop Ground-Truth Acquisition for Mechatronic Actuators,"* Int. J. Eng. Sci. Adv. Tech. (IJESAT), Vol. 16, Issue 7, pp. 12–17, Jul 2016. [DOI: 10.64771/ijesat.2016.v16.i07.4032](https://doi.org/10.64771/ijesat.2016.v16.i07.4032)

**Patents**

- *US Patent App. No. 63/905,835* (Filed Oct 27, 2025) — Artificial Intelligence (AI) Based Automatic Precision Surface Deposition / Painting System and Method Thereof
- *US Patent App. No. 63/905,842* (Filed Oct 27, 2025) — Automated Multi-Channel Fluidic Mixing and Dispensing Apparatus
