
# HQN-RL: Hybrid Quantum–Neuromorphic Reinforcement Learning

This repository implements the HQN-RL pipeline: a hybrid scheme that uses a variational quantum optimizer (PennyLane) for policy exploration and a neuromorphic spiking actor (Norse/PyTorch) for low-latency execution.

### Features
- CARLA-compatible environment wrapper (`src/env/env_wrapper.py`)
- PennyLane-based variational quantum optimizer (`src/quantum/q_optimizer.py`)
- Norse-based spiking actor (`src/neuromorphic/snn_actor.py`)
- Hybrid HQN agent and training loop (`src/agent.py`, `src/train.py`)
- Sim-to-real adapter scaffold for ROS2 (`src/sim_to_real/ros_nodes.py`)
- Example experiment configuration in `experiments/example_config.yaml`

### Quick start (simulation)
1. Create a conda env and install requirements:
