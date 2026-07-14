# 四足机器人 (Quadruped Robots)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-07-14

### [AutoPath: Learning Transferable Goal-Conditioned Stochastic Path Prior for Safe Navigation Without Human Demonstrations](https://arxiv.org/abs/2607.11739v1)

- **arXiv**: `2607.11739v1`  |  **提交日期**: 2026-07-13
- **作者**: Ziyang Zhang, Boyang Zhou, Zesong Yang, Haocheng Peng, Zeming Gai, Xiao Liang et al.

Real-time navigation in cluttered and dynamic environments requires collision-free and dynamically feasible motion under limited perception. However, feasible navigation behaviors are inherently multimodal because multiple paths may exist around obstacles. In this paper, we formulate navigation as learning a transferable goal-conditioned stochastic path prior that models a reusable distribution over goal-aligned geometry-consistent local paths conditioned on local observations. This formulation enables structured sampling of navigation candidates, allowing multiple feasible paths to be…

---

### [Stop to Decide: Latency-Aware Proprioceptive Navigation Primitives for Mapping-Free Quadruped Inspection](https://arxiv.org/abs/2607.11204v1)

- **arXiv**: `2607.11204v1`  |  **提交日期**: 2026-07-13
- **作者**: Hanting Suo, Haonan Yan, Liang Wang, Aiguo Song

Compute-constrained quadrupeds often run their navigation loop far below the controller's design rate: sharing the onboard Jetson Orin with the vision pipeline slows our stair loop to about 15 Hz. This latency breaks a standard proprioceptive pattern: declaring stair-summit arrival from the body-pitch signal while still climbing. On a stepped platform whose 50 cm top is shorter than the robot (Unitree Go2, about 75 cm), in-motion detection overshoots the top edge with probability rising with the per-period advance v/f (the slowest about 15 Hz cell partly diluted by a separate non-arrival…

---

### [PAKE: Learning Whole-Body Loco-Manipulation with Partial Kinematic Embeddings](https://arxiv.org/abs/2607.11041v1)

- **arXiv**: `2607.11041v1`  |  **提交日期**: 2026-07-13
- **作者**: Zhengmao He, Moonkyu Jung, Hyeongjun Kim, Jiseong Lee, Hui Zhang, Jemin Hwangbo et al.

Loco-manipulation has recently shown promising capabilities; however, achieving high-precision control, managing the high-dimensional action space induced by many degrees of freedom (DoFs), and fully exploiting the inherent redundancy of whole-body systems remain challenging. In this paper, we propose a novel whole-body control framework that effectively addresses these challenges by decomposing the complex loco-manipulation problem into partial reference motion generation and low-level imitation control. We introduce a new Kinematic Normalizing Flow (KNF) model, trained on a large-scale…

---

### [TAC-LOCO: Unified Whole-Body Control for Quadrupedal TACtile-Informed LOCO-Manipulation](https://arxiv.org/abs/2607.10132v1)

- **arXiv**: `2607.10132v1`  |  **提交日期**: 2026-07-11
- **作者**: Muqun Hu, Yuhao Zhou, Kabir Ray Malik, Chi Lin, Won Suk Lee, Yu She et al.

Dynamic loco-manipulation requires legged robots to coordinate whole-body motion while maintaining stable physical interaction with grasped objects under uncertain external forces. While tactile sensing has been widely studied for robotic manipulation, its role in dynamic whole-body control remains largely unexplored. Existing works without tactile feedback commonly grasp firmly rather than regulate the grasp according to the interaction. We propose TAC-LOCO, a tactile-augmented unified reinforcement learning framework that encodes tactile array observations from compliant grippers into a…

---

## 📅 2026-07-10

### [Behavior Foundations for Quadruped Robots: ABot-C0 Technical Report](https://arxiv.org/abs/2607.07370v2)

- **arXiv**: `2607.07370v2`  |  **提交日期**: 2026-07-08
- **作者**: Xufeng Zhao, Fuzhi Yang, Jianhui Chen, Li Gao, Zhang Meng, Jie Gao et al.

The motion controller is one of the most fundamental modules in embodied intelligence systems. Driven by large-scale human motion-capture data and the motion-tracking paradigm, humanoid control has achieved remarkable progress in recent years. However, migrating this recipe to the quadrupedal setting is far less straightforward: animal motion data is scarcer and harder to capture at scale than human data, and cross-embodiment retargeting remains fragile. We present ABot-C0, a generalist motion-control system for quadruped robots that establishes three complementary behavior foundations: a…

---

## 📅 2026-07-09

### [Behavior Foundations for Quadruped Robots: ABot-C0 Technical Report](https://arxiv.org/abs/2607.07370v1)

- **arXiv**: `2607.07370v1`  |  **提交日期**: 2026-07-08
- **作者**: Xufeng Zhao, Fuzhi Yang, Jianhui Chen, Li Gao, Zhang Meng, Jie Gao et al.

In embodied intelligence systems, the motion controller serves as the critical bridge between semantic reasoning and physical execution. Humanoid control has progressed rapidly through large-scale human motion-capture data and motion-tracking paradigm. However, producing quadruped robots motion corpora with scalability and physical feasibility faces more fundamental obstacles: animal motion data is scarce, and cross-embodiment retargeting remains fragile. We present ABot-C0, a generalist motion-control system for quadruped robots that establishes three complementary behavior foundations: a…

---

### [Dynamic Object Detection and Tracking in Construction: A Fisheye Camera and LiDAR Sensor Fusion Model](https://arxiv.org/abs/2607.06896v1)

- **arXiv**: `2607.06896v1`  |  **提交日期**: 2026-07-08
- **作者**: Yilong Chen, Huili Huang, Yong K. Cho

Robust dynamic object detection and tracking are essential for enabling robots to operate safely and effectively alongside humans in complex environments such as construction sites. While LiDAR-based SLAM and occupancy grid methods offer viable solutions for detecting and tracking motion, many state-of-the-art 3D vision approaches rely heavily on pre-trained neural networks and require additional post-processing to identify moving objects. Sensor fusion techniques, combining the precision of LiDAR with the semantic richness of RGB imagery, offer a promising alternative. In this work, we…

---

### [CaLiSym: Learning Symplectic Dynamics of Real-World Systems through Structured Canonical Lifts](https://arxiv.org/abs/2607.06824v1)

- **arXiv**: `2607.06824v1`  |  **提交日期**: 2026-07-07
- **作者**: Aristotelis Papatheodorou, Pranav Vaidhyanathan, Natalia Ares, Ioannis Havoutis, Gerard J. Milburn

Physics-informed learning promises data-efficient and stable dynamics prediction, yet its strongest geometric guarantees have largely remained confined to closed conservative systems. This excludes many robotic systems of practical interest, where actuation, dissipation, and constraints continuously exchange energy and momentum with the environment. We introduce CaLiSym, a lightweight framework that extends exact symplectic learning to such systems by changing where the geometric prior is imposed. Rather than enforcing symplecticity on the measured physical state, CaLiSym embeds the state and…

---

## 📅 2026-07-08

### [UniLM-Nav: A Unified Framework for Zero-Shot Last-Mile Navigation](https://arxiv.org/abs/2607.06537v1)

- **arXiv**: `2607.06537v1`  |  **提交日期**: 2026-07-07
- **作者**: Zhuofan Zhang, Tianxu Wang, Guoxi Zhang, Yixiong Lin, Xilin Wang, Hongming Xu et al.

Mobile manipulation requires a robot to navigate to a target object or receptacle and then perform intended manipulation. However, reaching the vicinity of the target does not guarantee a manipulation-ready base pose, a problem known as last-mile navigation. Prior methods for last-mile navigation either rely on manual pose annotation or task-specific training, limiting their scalability to open-vocabulary settings with fine-grained spatial constraints. We propose UniLM-Nav, a unified framework for zero-shot open-vocabulary last-mile navigation. UniLM-Nav decomposes last-mile navigation into…

---

### [Calf-Integrated Arms for Bimanual Quadruped Loco-Manipulation](https://arxiv.org/abs/2607.06186v1)

- **arXiv**: `2607.06186v1`  |  **提交日期**: 2026-07-07
- **作者**: Yan Pan, Yuanchuan Ren, Chipui Chan, Jingcheng Sun, Chengxu Zhou

Most quadruped loco-manipulation designs trade manipulation capability against stance. A trunk-mounted arm sits high and usually carries a single arm; using the legs as manipulators lifts the manipulating leg off the ground; and even leg-mounted grippers reach two-handed tasks only by rearing onto the hind legs. This paper integrates a manipulator with a prismatic slider, two revolute joints, and a gripper into each front calf of a Unitree Go2. The two arms grasp objects at ground level and manipulate with both hands while all four feet stay planted, without rearing. With one arm carrying,…

---

### [EAGOR: Embodied Reasoning in Omni-direction](https://arxiv.org/abs/2607.06165v1)

- **arXiv**: `2607.06165v1`  |  **提交日期**: 2026-07-07
- **作者**: Shriram Damodaran, Soumyaratna Debnath, Yan Wu, Wei-Yun Yau, Addison Lin Wang

Omni-directional (360°) cameras provide embodied agents with a holistic view of their surroundings, making them suited for directional reasoning in tasks such as navigation and object search. Existing Vision Language Models (VLMs) project 360° observations to 2D equirectangular projection (ERP) images and process them using architectures designed for perspective images. However, they ignore the spherical nature of 360° observations, where each pixel represents a viewing direction relative to the agent. Consequently, their direction estimates often become inconsistent under camera view…

---

### [TypeGo: An OS Runtime for Embodied Agents](https://arxiv.org/abs/2607.05482v1)

- **arXiv**: `2607.05482v1`  |  **提交日期**: 2026-07-06
- **作者**: Guojun Chen, Alex Schott, Lin Zhong

Large language models (LLMs) can plan behavior for embodied agents from natural language, but treating the LLM as a request/response oracle on the critical path is fundamentally at odds with real-time control and concurrent goals. We argue for an operating-system-style runtime for embodied agents, and instantiate this idea in an early prototype, TypeGo. TypeGo structures LLM-based planning as asynchronous loops at multiple timescales that overlap with execution, and manages the agent's physical body like an OS manages hardware: the Skill Kernel arbitrates typed physical subsystems among…

---

## 📅 2026-07-07

### [Unsupervised Pixel-Level Semantic Left-Right Understanding of In-the-Wild Images](https://arxiv.org/abs/2607.05006v1)

- **arXiv**: `2607.05006v1`  |  **提交日期**: 2026-07-06
- **作者**: Weikang Wang, Tobias Weißberg, Florian Bernard

While various works address reflective symmetry understanding in 3D data and images, pixel-level semantic left-right prediction of in-the-wild images remains challenging, due to certain difficulties including the lack of 3D information, occlusion, object pose variation, partiality, etc. In this work, we propose an unsupervised learning framework to tackle this challenge. Leveraging recent advances in vertex-wise semantic left-right understanding of 3D data, our unsupervised learning method jointly utilises 3D shape and image datasets to infer pixel-wise semantic left-right predictions in…

---

### [Multi-Robot Open Adaptive Teaming Across Unseen Environments, Partners, and Scales](https://arxiv.org/abs/2607.04972v1)

- **arXiv**: `2607.04972v1`  |  **提交日期**: 2026-07-06
- **作者**: Yang Li, Feng Xue, Fan Mo, Yunhao Liu, Jianhong Wang, Ying Wen et al.

Deploying robot teams in the real world requires simultaneous adaptation to unseen environments, unknown partners, and varying team sizes, yet existing approaches often address these challenges in isolation under the closed-world assumption of fixed teammates. We formalize this as open adaptive multi-robot teaming and propose a hypergraphic-form game formulation that captures team-level cooperative relationships beyond pairwise interactions, providing a principled foundation for coordination structure inference when team composition changes dynamically within episodes. Unlike graph neural…

---

## 📅 2026-07-02

### [Learning Gait-Aware Quadruped Locomotion with Temporal Logic Specifications](https://arxiv.org/abs/2607.00442v1)

- **arXiv**: `2607.00442v1`  |  **提交日期**: 2026-07-01
- **作者**: Merve Atasever, Cagan Bakirci, Alfredo Reina Corona, Keyan Azbijari, Jyotirmoy V. Deshmukh

Reinforcement learning (RL) for quadruped locomotion commonly depends on fixed, hand-crafted, and Markovian reward functions that limit both interpretability of learned policies and lack explicit control over gait behaviors. We introduce a framework where distinct gaits are specified using parameterized constraints expressed in Signal Temporal Logic (STL). These include safety bounds, gait synchronization constraints, command tracking, and actuation bounds. From these specifications, we develop a reward shaping mechanism that provides learning agents a dense, continuous reward landscape that…

---

### [The Quadruped Soft Tail: Compliant Grasping and Swabbing for Contamination Surveys in Harsh Environments](https://arxiv.org/abs/2606.30900v2)

- **arXiv**: `2606.30900v2`  |  **提交日期**: 2026-06-29
- **作者**: Harald Minde Hansen, Nandita Gallacher, Kristin Y. Pettersen, Jan Tommy Gravdahl, Mario di Castro

Beryllium contamination surveys in radioactive areas are challenging for robots in environments cluttered with cables and electronics. To address this problem, we have developed a novel quadruped system augmentation: A lightweight, soft, and compliant tendon-actuated robotic tail mounted on a quadruped robot. The tail features a hollow, flexible backbone and a tendon-actuated soft gripper that enables the robot to pick up sampling tissues, swab contaminated surfaces, and release the tissues at designated collection locations for subsequent beryllium analysis. To enable intuitive…

---

## 📅 2026-07-01

### [Learning Locomotion on Discrete Terrain via Minimal Proximity Sensing](https://arxiv.org/abs/2606.31912v1)

- **arXiv**: `2606.31912v1`  |  **提交日期**: 2026-06-30
- **作者**: Jiale Fan, Connor Flynn, Tianao Xu, Junzhe He, Andrei Cramariuc, Marco Hutter et al.

Learning-based control has revolutionized dynamic locomotion, yet navigating unstructured terrain remains limited by a robot's incomplete awareness of imminent ground contact. While global perception systems such as LiDARs and depth cameras provide environmental context, they are frequently plagued by latencies, occlusions, and the high computational cost of dense geometric reconstruction. On the other hand, proprioceptive feedback is purely reactive, initiating corrections only after impact has occurred. This work explores embedding a minimal suite of low-cost, high-frequency infrared…

---

### [LLM-Powered Interactive Robotic Action Synthesis from Multimodal Speech, Gestures, and Music](https://arxiv.org/abs/2606.31158v1)

- **arXiv**: `2606.31158v1`  |  **提交日期**: 2026-06-30
- **作者**: Snehasis Banerjee, Ranjan Dasgupta

The quest for intuitive and natural human-robot interaction (HRI) remains a significant challenge in robotics. Traditional methods often rely on rigid, pre-programmed commands that limit the robot's expressiveness and adaptability. This paper introduces a novel framework that leverages the reasoning capabilities of Large Language Models (LLMs) to synthesize complex robotic actions from a rich tapestry of multimodal human inputs: natural speech, hand gestures, and music/sound beats. Our system architecture integrates a speech transcription model, a gesture recognition module, and a signal…

---

### [The Quadruped Soft Tail: Compliant Grasping and Swabbing for Contamination Surveys in Harsh Environments](https://arxiv.org/abs/2606.30900v1)

- **arXiv**: `2606.30900v1`  |  **提交日期**: 2026-06-29
- **作者**: Harald Minde Hansen, Nandita Gallacher, Kristin Y. Pettersen, Jan Tommy Gravdahl, Mario di Castro

Beryllium contamination surveys in radioactive areas are challenging for robots in environments cluttered with cables and electronics. To address this problem, we have developed a novel quadruped system augmentation: A lightweight, soft, and compliant tendon-actuated robotic tail mounted on a quadruped robot. The tail features a hollow, flexible backbone and a tendon-actuated soft gripper that enables the robot to pick up sampling tissues, swab contaminated surfaces, and release the tissues at designated collection locations for subsequent beryllium analysis. To enable intuitive…

---

## 📅 2026-06-30

### [KYON: Semi-Modular Wheel-Legged Quadruped With Agile Bimanual Capability](https://arxiv.org/abs/2606.30243v1)

- **arXiv**: `2606.30243v1`  |  **提交日期**: 2026-06-29
- **作者**: Luca Rossini, Arturo Laurenzi, Francesco Ruscelli, Yifang Zhang, Giovanbattista Gravina, Lorenzo Baccelliere et al.

This paper presents KYON, a hybrid wheel-legged quadruped robot equipped with a bimanual upper body for loco-manipulation tasks. The platform features a semi-modular design with a reconfigurable lower legs, enabling both wheeled and legged locomotion depending on the environment. A design approach that places actuators in the base and uses transmission mechanisms reduces distal inertia, improving agility and dynamic performance. The robot integrates a whole-body control framework together with a reinforcement learning based policy to handle nonlinear dynamics and enhance robustness to…

---

## 📅 2026-06-29

### [CacheMPC: Certified Cached Model Predictive Control for Quadruped Locomotion](https://arxiv.org/abs/2606.28300v1)

- **arXiv**: `2606.28300v1`  |  **提交日期**: 2026-06-26
- **作者**: Nimesh Khandelwal, Mehul Anand, Shakti S. Gupta, Mangal Kothari

Model Predictive Control (MPC) is the standard predictive layer in hierarchical quadruped controllers, but the per-cycle QP solve limits the update rate achievable on embedded processors. Because legged gaits revisit a bounded region of state space, MPC solutions admit caching and reuse. This paper proposes \emph{Certified CacheMPC}: a Locality-Sensitive-Hashed cache of horizon contact-force trajectories, partitioned by contact mode, retrieved at query time and accepted only when an a-posteriori per-query certificate confirms primal feasibility and a Lagrangian dual-gap upper bound on cost…

---

### [Unleashing Infinite Motion: Scaling Expressive Quadrupedal Motion via Generative Video Priors](https://arxiv.org/abs/2606.28237v1)

- **arXiv**: `2606.28237v1`  |  **提交日期**: 2026-06-26
- **作者**: Youzhi Liu, Li Gao, Yifei Qian, Liu Liu, Yang Cai, Ziqiao Li

Quadruped robots have achieved remarkable locomotion, yet their behavioral repertoire remains confined to a few gaits--far from the expressive, companion-like presence long envisioned for them. Attempts to import the humanoid recipe of large-scale motion data have inherited one tacit assumption: that robot motion must first pass through an animal body, making data collection dependent on cooperative animals, reconstruction fragile across species, and retargeting ill-posed across incompatible morphologies. We propose Uni-Mo, a fully automated pipeline that removes the animal from the loop by…

---

### [PPO-EAL: Exact Augmented Lagrangian Proximal Policy Optimization for Safe Robotic Control](https://arxiv.org/abs/2606.27861v1)

- **arXiv**: `2606.27861v1`  |  **提交日期**: 2026-06-26
- **作者**: Jiatao Ding, Songqun Gao, Andrea Del Prete, Matteo Saveriano

Reinforcement learning (RL) has emerged as a promising solution to accomplish complex robotic control tasks; however, most of the current work ignores the safety requirements. Safe RL seeks to maximize task performance while satisfying explicit physical constraints, but current algorithms struggle to learn the policy efficiently with precise constraint satisfaction. This work proposes PPO-EAL, a novel first-order constrained policy optimization framework that integrates exact augmented Lagrangian optimization into proximal policy optimization for safe robotic control. By combining clipped…

---

## 📅 2026-06-27

### [OctoSense: Self-Supervised Learning for Multimodal Robot Perception](https://arxiv.org/abs/2606.27317v1)

- **arXiv**: `2606.27317v1`  |  **提交日期**: 2026-06-25
- **作者**: Anthony Bisulco, Jeremy Wang, Kostas Daniilidis, Randall Balestriero, Pratik Chaudhari

We present OctoSense, an open-source sensor platform with stereo RGB and event cameras, LiDAR, a thermal camera, an inertial measurement unit, RTK-corrected global positioning system, and proprioception (CAN bus data from a car, and joint angles for a quadruped robot). The eponymous OctoSense dataset contains 59 hours of time-synchronized driving data across different types of environments at different times of the day, including situations with highly degraded sensors. We demonstrate multi-modal self-supervised learning using such real-world robotics data, where sensors have different…

---

### [MPC-Injection: Biasing Off-Policy Locomotion RL Toward Controller-Induced Behavior Basins](https://arxiv.org/abs/2606.26392v1)

- **arXiv**: `2606.26392v1`  |  **提交日期**: 2026-06-24
- **作者**: Roy Xing, Seyoung Ree, Brian Plancher

Reinforcement learning (RL) for locomotion frequently converges to locally optimal but undeployable behaviors, such as vibrating limbs or scooting on the torso, that maximize return without producing a usable gait. We present MPC-Injection, a low-overhead method that steers RL toward a designer-preferred gait by inserting transitions into the replay buffer from a model predictive controller solving the same Markov decision process. Unlike reward shaping, MPC-Injection does not require redesigning the task reward, and unlike adversarial imitation learning, it adds no discriminator, no…

---

### [Racing a Wheeled Quadruped: Active Load Transfer Mitigation via Model Predictive Control](https://arxiv.org/abs/2606.26313v1)

- **arXiv**: `2606.26313v1`  |  **提交日期**: 2026-06-24
- **作者**: Marla Eisman, Brian Lam, Samuel Sonnino, Francesco Borrelli

This paper presents a hierarchical control framework using model predictive control (MPC) and reinforcement learning (RL) for active roll control to manage lateral load transfer during autonomous racing of a wheeled quadruped. The framework integrates offline time-optimal raceline generation, an online MPC planner that actively minimizes the lateral Load Transfer Ratio (LTR), and a low-level, whole-body RL policy deployed directly onto the robot's 16 actuators. The MPC is based on a vehicle dynamics bicycle model of the Unitree Go2-W platform. The robot's leg actuators act as active…

---

### [Mixture-of-Experts RL for Fault-Tolerant Legged Locomotion](https://arxiv.org/abs/2606.25965v1)

- **arXiv**: `2606.25965v1`  |  **提交日期**: 2026-06-24
- **作者**: Giulio Turrisi, Ozan Pali, Luca Oneto, Claudio Semini

Legged robots deployed in planetary exploration and other remote environments must maintain reliable locomotion despite actuator failures and challenging terrain conditions. Although reinforcement learning has achieved strong results in legged locomotion, monolithic policies can struggle to efficiently represent the diverse control strategies required to compensate for different fault conditions. In this work, we propose a fault-aware modular control architecture that explicitly leverages fault-diagnosis information to activate specialized control experts associated with distinct actuator…

---

### [StairMaster: Learning to Conquer Risky Hollow Stairs for Agile Quadrupedal Robots](https://arxiv.org/abs/2606.25765v1)

- **arXiv**: `2606.25765v1`  |  **提交日期**: 2026-06-24
- **作者**: Xincheng Tang, Youhan Xie, Zhengjie Shu, Wanyu Li, Lai Jiang, Wenkang Hu et al.

Climbing hollow stairs remains a challenging problem for quadruped robots due to the high risk of leg trapping, severe depth sparsity, and high-frequency depth-sensing noise. In this paper, we propose StairMaster, a novel three-stage reinforcement learning framework for stable locomotion on such extreme discontinuous terrains. Our architecture integrates a Cross-Attention mechanism to extract structural features from noisy depth data, alongside a Spatial-aware Recurrent Unit (SRU) that maintains robust spatio-temporal memory to mitigate perception blind spots. To bridge the sim-to-real gap in…

---

### [MAPL: Multi-Objective Preference Learning for Robot Locomotion](https://arxiv.org/abs/2606.25398v1)

- **arXiv**: `2606.25398v1`  |  **提交日期**: 2026-06-24
- **作者**: Xiyue Chen, Muhan Lin, Shuyang Shi, Joseph Campbell

Reward design remains a major bottleneck in reinforcement learning for robot locomotion, where successful policies often depend on carefully tuned, task-specific reward functions. Preference-based reinforcement learning offers an alternative, but existing LLM-based methods typically ask for a single overall judgment between behaviors, making it difficult to capture the multiple competing objectives that underlie high-quality locomotion. We present Multi-Objective AI-Informed Preference Learning (MAPL), a framework that learns locomotion rewards from high-level natural language objectives…

---

### [WaveForward: An Omnidirectional Passive Wheeled Quadruped Robot with Casters](https://arxiv.org/abs/2606.25299v1)

- **arXiv**: `2606.25299v1`  |  **提交日期**: 2026-06-24
- **作者**: Chuanlin Zhao, Qifeng Zheng, Shuhan Wang, Tiancheng Ma, Weixian Lin, Xin Luo

Wheeled-legged robots possess both agile mobility for traversing complex terrains and high efficiency, making them suitable for long-distance transportation applications. Conventional actuated wheeled robots require specialized hardware and electrical design due to the incorporation of wheel components. We propose a novel and low-cost passive wheeled legged robot equipped with standard casters on each leg to obtain omnidirectional mobility. The control method employs an asymmetric actor-critic structure, enabling the utilization of the privileged information of the passive caster's angles and…

---

