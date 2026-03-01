# Capstone Project: UAV-mounted RIS Cooperative NOMA-MEC

**Title:** On the Performance and Optimization for Computation Offloading and Energy Robustness of UAV-mounted RIS Cooperative NOMA-MEC  
**Domain:** 6G Wireless Networks, Internet of Things (IoT), Mobile Edge Computing (MEC), Deep Reinforcement Learning  

## Overview
This project investigates the performance and multi-objective optimization of millimeter wave (mmWave) 6G IoT networks. It integrates an Unmanned Aerial Vehicle (UAV) equipped with a Reconfigurable Intelligent Surface (RIS) into a Non-Orthogonal Multiple Access (NOMA)-Mobile Edge Computing (MEC) architecture. The objective is to balance computation offloading reliability and energy robustness under highly realistic environmental and aerodynamic constraints.

## Key Contributions
- **Realistic Reliability Modeling:** Derives closed-form expressions for Successful Computation Probability (SCP) under Nakagami-m fading, probabilistic LoS/NLoS propagations, and ITU-standard weather attenuation (rain, fog, atmospheric gases).
- **Physics-based Energy Robustness:** Formulates a novel Energy Outage Probability (EOP) constraint that utilizes Blade Element Momentum Theory (BEMT) and thermodynamic laws to calculate dynamic propulsion power instead of idealized static models. Incorporates the mechanical penalties of wind drag and physical mass accumulation (e.g., rain, dust) on the UAV payload.
- **Multi-Objective Optimization:** Implements a Deep Reinforcement Learning framework utilizing Pareto Conditioned Networks (PCN) to jointly optimize the UAV-RIS's spatial positions and altitude. 
- **Performance Evaluation:** Demonstrates that the proposed PCN optimization successfully discovers the optimal Pareto frontier balancing communication reliability and physical robustness, actively outperforming traditional algorithms like PPO (Proximal Policy Optimization) and PSO (Particle Swarm Optimization).

## Project Team
- **Nguyễn Gia Huy** (Leader) – HE180064
- **Trần Đặng Quang Huy** (Member) – HE180383
- **Lưu Ngọc Sơn** (Member) – HE180294
- **Nguyễn Quang Huy** (Member) – HE181445

**Supervisor:** Dr. Ngô Trường Minh
