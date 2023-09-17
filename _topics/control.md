---

layout: single 
classes: wide
entries_layout: grid
author_profile: true 

title: "Optimization-based Multi-Contact Optimal Whole-body Control"

excerpt: "
Exploring two decades of advancements in whole-body control of humanoid robots, we will revisit the disparity between approximation methods and holistic controls, while assessing recent breakthroughs in near real-time optimization on legged robots, seeking solutions for future computational challenges.
"

---


Optimization based instantaneous whole-body control of humanoid robots has seen significant developments over the past two decades. Inspired by the seminal work [1] first implementing instantaneous dynamic robot control as a quadratic program (QP), this has enabled humanoid robots to realize constrained real-time control for a variety of tasks. However, due to the high number of degrees of freedom and the associated high computational complexity, real-time receding horizon optimal whole-body control (O-WBC) yet has to be realized on humanoid robots. Instead, researchers have proposed numerous approximation methods for whole-body motions under contact. After the whole-body dynamics are reduced to representative but simpler models, an optimal trajectory is computed for these representative values. The whole body motion is then recovered afterwards while observing the representative values [2]. In this workshop, we investigate how big the gap between these approximation methods and whole-body control still is, or if these approximation methods sufficiently reflect human motion planning capabilities after all. Recent promising computationally efficient methods have enabled near real-time O-WBC on quadrupeds [3, 4]. We study the feasiblity of these state-of-the-art methods for larger DoF robotics systems. We hope to find answers for what the way forward may be to tackle the remaining computational obstacles of O-WBC.


- [1] *Multiobjective Control with Frictional Contacts*. Abe et. al., Symposium on Computer Animation, 2007.
- [2] *Multi-contact Locomotion of Legged Robots*. Carpentier et. al., 2018.
- [3] *Inverse-Dynamics MPC via Nullspace Resolution*. Mastalli et. al., TRO 2023.
- [4] *Analytical Second-Order Partial Derivatives of Rigid-Body Inverse Dynamics*. Singh et. al., IROS 2022.

 

