
## Hi there 👋

# Chinmayee Prabhakar <img align="right" width="250" alt="Baymax waving hello" src="https://media1.tenor.com/m/35cwOl7x56sAAAAd/baymax-bighero6.gif" />

**Robotics research • Multi-robot estimation • Learning-enabled dynamics & control • Aerial autonomy**

I am a robotics engineer with an M.S. in Mechatronics, Robotics & Automation Engineering (thesis track) from Worcester Polytechnic Institute. My research interests lie at the intersection of **state estimation, planning, and control**, with a focus on autonomous robots operating under uncertainty in sensing and dynamics. I am applying to robotics-related PhD programs for Fall 2027.

I have published first-author research on decentralized multi-robot localization and target tracking (ACC 2025) and physics-guided learning for contact dynamics (ICLR 2026 AI & PDE Workshop). Alongside research, I build end-to-end robotics software and embedded control systems.

[Research & projects](#selected-research) · [GitHub repositories](#featured-implementations) · [LinkedIn](https://www.linkedin.com/in/chinmayeeprabhakar/) · [Email](mailto:prabhakar.chinmayee@gmail.com)

## Selected research

**Decoupled Multi-Robot Localization and Target Tracking via Dynamic Covariance Scaling and Inverse Covariance Fusion**  
*Chinmayee Prabhakar and Siavash Farzan — American Control Conference (ACC), 2025*  
Decentralized estimation under noisy range-bearing measurements and limited communication. Combined unscented-transform propagation, dynamic covariance scaling for covariance intersection, and inverse-covariance-weighted target fusion.  
[Publication record](https://ieeexplore.ieee.org/document/11107921) · 

**When Does Physics Help? A Systematic Study of Physics-Guided Learning for Robotic Contact Dynamics**  
*First-author paper — ICLR 2026 AI & PDE Workshop*  
Systematic simulation study of data-only learning, physics-informed networks, and UDE-based approaches for material-conditioned contact dynamics, including sparse/noisy observations and transfer to previously unseen materials.  
[Paper (OpenReview)](https://openreview.net/forum?id=NsDwAHwNLB) ·

## Featured implementations

### Autonomous Aerial Robotics — vision-guided quadrotor planning and control

[![Indoor quadrotor simulation](https://raw.githubusercontent.com/Chinmayee-Prabhakar/Autonomous-Aerial-Robotics/main/assets/indoor_facility.png)](https://github.com/Chinmayee-Prabhakar/Autonomous-Aerial-Robotics)

6-DoF simulation with cascaded control, window perception, trajectory generation, a rotating-arm obstacle, and a Blender-image-guided end-to-end mission. The reported evaluation includes **3/3 completed predefined full missions**, two safe aborts in deliberately unsafe cases, and **214/214 source tests**. 
**Python · Blender · trajectory planning · feedback control** · [Code and demo](https://github.com/Chinmayee-Prabhakar/Autonomous-Aerial-Robotics)

### Perception Stack for Autonomous Navigation

Combined YOLO11 instance segmentation, Depth Anything V2 metric depth, and TwinLiteNetPlus road/lane predictions. Evaluated object-depth estimates using camera imagery and a separate KITTI LiDAR reference pipeline, including held-out comparisons and uncertainty analysis.  
**Python · PyTorch · computer vision · KITTI** · [Code, visualizations, and evaluation](https://github.com/Chinmayee-Prabhakar/perception-stack-autonomous-navigation)

### Incremental Structure from Motion + NeRF

Implemented image matching, triangulation, camera registration, and bounded local bundle adjustment, then trained NeRFs with supplied and recovered poses for novel-view synthesis. Demonstrations include ETH3D, synthetic Lego, and LLFF Fern, with documented limitations and quantitative comparisons.  
**Python · OpenCV · PyTorch · geometry** · [Code and rendered demos](https://github.com/Chinmayee-Prabhakar/Incremental-SfM-NeRF)

### Monocular ORB-Based Visual SLAM

Built an ORB-based system with essential-matrix geometry, map-based PnP, sparse mapping, and local bundle adjustment. Evaluated tracking successes and failures on KITTI Odometry.  
**Python · OpenCV · estimation** · [Code and evaluation](https://github.com/Chinmayee-Prabhakar/orb-slam-mono)

## Additional robotics projects

- [Robust quadrotor trajectory tracking](https://github.com/Chinmayee-Prabhakar/quadrotor-sliding-mode-control) — boundary-layer sliding-mode control for a simulated Crazyflie quadrotor.
- [Mobile manipulator cart pushing](https://github.com/Chinmayee-Prabhakar/Cart-Pushing-with-Mobile-Manipulator) — comparison of nonholonomic motion-planning approaches.
- [Motion Planning](https://github.com/Chinmayee-Prabhakar/Motion-Planning) · [Robot Controls](https://github.com/Chinmayee-Prabhakar/Controls) · [Robot Dynamics](https://github.com/Chinmayee-Prabhakar/Robot-Dynamics) — selected algorithm and controls implementations.

## Engineering background

My systems work includes embedded feedback control and automation at **SpadXTech**, a ROS 2 Nav2 costmap internship at **Void Robotics**, and manipulator teleoperation, haptic interfaces, and networked embedded control at **IISc**. Employer/institution-owned implementations are not published here.

**Get in touch:** [LinkedIn](https://www.linkedin.com/in/chinmayeeprabhakar/) · [Email](mailto:prabhakar.chinmayee@gmail.com)


