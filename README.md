# Visual-Guided-Dual-Arm-Synchronization-CoppSim

The objective is to synchronize the motion of two robots without sharing internal states, joint
angles, or trajectories. UR5 moves an object in a dynamic pattern; Franka must maintain alignment
using only what it sees through its camera. This setup resembles two people synchronising arm
motions: one performs a movement, the other follows purely by watching.
The system combines Lua scripts for IK control, Python/OpenCV for vision processing, and Cop-
peliaSim’s simulation environment.
