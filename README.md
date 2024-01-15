# Sumptuous Excursion into Data Simmering-(ASEN 5044)
Final project for Statistical Estimation of Dynamical Systems - ASEN 5044 Fall 23

## Abstract
This paper presents a study on Cooperative Air-Ground Robot Localization, focusing on the development and validation of linearized and Extended Kalman filters for accurate and efficient tracking. The integration of aerial and ground-based robotic platforms poses unique challenges in the context of localization, requiring robust algorithms to handle the dynamic and diverse nature of the environment. To address this, two variants of the Kalman filter, namely the linearized Kalman filter (LKF) and the Extended Kalman filter (EKF), were developed to optimize the tracking performance of cooperative robotic systems. After a direct comparison on noisy data, it was found that the EKF performed better on measurement data corresponding to truth states that stray too far from the nominal trajectory.

## Contributions
1. Matthew - Generated the full nonlinear simulation of the system dynamics and created the LKF and LKF plots.
2. Nathan - Derived the CT Jacobians and DT linearized model about the specified nominal point and implemented the EKF and LKF to estimate state trajectories using observation data.
3. Grant - Simulated the linearized DT model and created the EKF and EKF plots.
