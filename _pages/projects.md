---
layout: page
title: projects
permalink: /projects/
description: Research in embodied AI, multi-robot coordination, and robot learning.
nav: true
nav_order: 3
---

## Intervention-guided mobile manipulation

**Georgia Institute of Technology · Current research**

I am developing a framework that traces mobile-manipulation failures across navigation, perception, and contact, and coordinates physical recovery. The framework selectively adapts robot skills, residual controllers, and vision-language-action policies to improve long-term autonomy and task performance.

## SituLaMP

**Honda Research Institute USA · Summer 2026**

An LLM/VLM-based framework for long-horizon planning in heterogeneous multi-robot teams, with failure detection during execution, dynamic replanning, and task reallocation that preserves unaffected plan structure. I implemented PDDL planning, multi-robot simulation, and recovery logic for action, perception, and environmental failures, and designed benchmarks for task completion, robustness, recovery efficiency, generalization, and recovery cost.

## StratMamba

**AlphaZ, Inc. · IROS 2026**

StratMamba separates reactive obstacle processing from strategic, goal-directed navigation in a dual-stream Mamba-based PPO architecture for LiDAR-based obstacle avoidance. I built training and evaluation pipelines in IsaacLab and Gazebo and deployed the learned policy on a Unitree GO1 using ROS2, RSLidar-16, and VICON. Experiments compared timeout rate, path efficiency, navigation speed, and sim-to-real robustness against LSTM, Transformer, and vanilla Mamba baselines.

## CoReNav

**Conformal Calibrated Foundation Model Rewards for Object Navigation**

CoReNav combines imitation learning with reinforcement learning fine-tuning driven by foundation-model rewards, enabling semantically guided exploration without continuous high-latency model queries. Conformal prediction calibrates VLM-based room classification and LLM-generated object relevance priors to mitigate hallucinations and stabilize learning. I evaluated success rate, path optimality, and time efficiency on HM3D Semantics.

## CommCP

**Efficient Multi-Agent Coordination via LLM-Based Communication with Conformal Prediction · ICRA 2026**

CommCP addresses multi-agent multi-task embodied question answering (MM-EQA), where robots collaborate and exchange information to answer natural-language assignments. The decentralized communication framework uses conformal prediction to calibrate LLM-generated messages, improving communication reliability and efficiency while reducing distractions to other agents. I also created and released an MM-EQA benchmark with photo-realistic HM3D scenarios.

## LaMMA-P

**Generalizable Multi-Agent Long-Horizon Task Allocation and Planning with LM-Driven PDDL Planner · ICRA 2025**

LaMMA-P integrates LLM reasoning with PDDL planning heuristics for long-horizon tasks involving heterogeneous robot teams and a flexible number of agents. Its modular design connects language models, planners, and simulation environments for task decomposition and capability-aware allocation. I created MAT-THOR, an AI2-THOR-based benchmark with standardized tasks and metrics, and evaluated task success and planning efficiency.

## Quadruped robot teams for exploration and harvesting

**Dynamic Robotics and Control Laboratory, University of Southern California · 2022–2023**

I contributed to large-scale multi-robot systems involving teams of quadruped robots, developing task allocation, path planning, and coordination strategies for exploration. I conducted validation and data collection in simulation and real-world agricultural environments, including strawberry and raspberry fields.

See the [publications]({{ '/publications/' | relative_url }}) page for paper details and the [CV]({{ '/cv/' | relative_url }}) for my full research experience.
