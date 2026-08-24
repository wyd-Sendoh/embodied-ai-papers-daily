# 强化学习运动控制 (RL Locomotion & Control)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-08-24

### [Neural-Primitive: An Efficient End-to-end Local Planner with Primitive-based Imitation Learning for Autonomous Flight](https://arxiv.org/abs/2608.20948v1)

- **arXiv**: `2608.20948v1`  |  **提交日期**: 2026-08-21
- **作者**: Zhitao Liu, Guangtong Xu, Zihan Wang, Jialiang Hou, Chao Xu, Fei Gao

Autonomous flight in unknown cluttered environments is hindered by the computation-quality-memory trilemma of onboard trajectory generation. In this paper, we propose an efficient end-to-end local planner via imitation learning. A lightweight offline-primitive-based dataset collection framework is designed to produce safe and high-quality trajectory primitives in non-convex environments. A compact neural network directly maps sensory inputs to polynomial coefficients that inherently encode higher-order dynamical information. The learned policy generates smooth, empirically collision-free and…

---

## 📅 2026-08-21

### [Video2DoorTraversal: Push Door Traversal via Simulated Door Twins](https://arxiv.org/abs/2608.20251v1)

- **arXiv**: `2608.20251v1`  |  **提交日期**: 2026-08-20
- **作者**: Xincheng Tang, Yiji Chen, Youhan Xie, Wanyu Li, Zhengjie Shu, Lai Jiang et al.

Door opening and traversal is a long-horizon loco-manipulation task that requires precise handle interaction and coordinated base-arm control. We present Video2DoorTraversal, a single-video real-to-sim-to-real framework for wheel-legged mobile manipulators. Given one RGB video of a real door, DoorTwin reconstructs an instance-aligned, articulated, and simulation-ready door twin with realistic geometry and appearance. A simulation-in-the-loop agent converts the recovered articulation into a parameterized skill program and iteratively refines failed rollouts to generate physically executable…

---

### [DECOWAM: Decoupled Whole-Body World-Action Model for Legged Mobile Manipulation](https://arxiv.org/abs/2608.20114v1)

- **arXiv**: `2608.20114v1`  |  **提交日期**: 2026-08-20
- **作者**: Siyuan Ma, Boshi Zhang, Yutian Zhang, Qinglian Wu, Jiaqi Zhai, Dong Wei et al.

Mobile manipulation requires a robot to predict how locomotion and arm motion jointly alter future observations and control. Existing world-action models, developed largely for fixed-base platforms, do not explicitly distinguish camera ego-motion from base and arm actions. Here we introduce DECOWAM, a whole-body world-action model that separates these factors through dedicated conditional interfaces. DECOWAM freezes an adapted FastWAM backbone and trains residual adapters, an action-equivalent future bottleneck distilled from privileged observations, adversarially separated base and arm…

---

## 📅 2026-08-20

### [ADEPT: Accelerating Dexterity via Pre-Training and Post-Training using Reinforcement Learning](https://arxiv.org/abs/2608.19182v1)

- **arXiv**: `2608.19182v1`  |  **提交日期**: 2026-08-19
- **作者**: Jayjun Lee, Jessica Yin, Asif Rana, Nicholas Blauch, Sam Mady, Mohak Bhardwaj et al.

We introduce Accelerating Dexterity via Pre-Training (ADEPT), a large-scale reinforcement learning (RL) framework for learning sim-to-real transferable dexterity across high degree-of-freedom (DoF) robot embodiments that can solve long-horizon tasks directly from raw visuo-tactile perception. ADEPT pretrains a dexterous policy on a generic object reposing task, then post-trains downstream policies with this pretrained behavior as a prior. ADEPT enables learning new behaviors that are otherwise difficult to discover from scratch on multi-fingered robots and avoids learning the same set of…

---

### [GigaBrain-WBC-0.5: A Behavior World Model for Robust Whole-Body Control with Environment Interaction](https://arxiv.org/abs/2608.18234v1)

- **arXiv**: `2608.18234v1`  |  **提交日期**: 2026-08-18
- **作者**: Ziyang Cheng, Tianshu Tang, Jinxin Lan, Xinze Chen, Yuhan Gong, Zhichao Liu et al.

Whole-body motion tracking policies turn a humanoid into a robust control interface: the teleoperator---or an upstream model---only supplies a coarse movement intent, while the low-level policy keeps the robot balanced and physically feasible. Existing trackers deliver this interface only on flat ground: trained in empty scenes, they never learn how contact with terrain and objects reshapes their dynamics, and they attempt to teach the policy to balance under any command by continually enlarging the reference-motion corpus, which stops working once feasible behaviors become…

---

## 📅 2026-08-19

### [Iterative Grasp Pose Refinement: A Deep Reinforcement Learning Approach for 2D Vision](https://arxiv.org/abs/2608.17628v1)

- **arXiv**: `2608.17628v1`  |  **提交日期**: 2026-08-18
- **作者**: Amir Arsalan Nematollahi, Shayan Ahmadi, Mehdi Tale Masouleh, Ahmad Kalhor

Developing robots capable of understanding and manipulating objects requires compact, interpretable, and generalizable representations. This work proposes a reinforcement learning-based framework for robotic grasp refinement, integrating keypoint-based object representations with a Deep Q-Network (DQN). Using 2D overhead images captured in a simulated environment, a geometric-based algorithm generates initial grasp candidates, which are iteratively refined by the proposed framework, transforming failed grasps into successful ones. Experiments conducted on 300 objects from the Dex-Net dataset…

---

### [Robust Brachiation on a Life-Sized Dual-Arm Robot Using Waypoint-Guided Reinforcement Learning](https://arxiv.org/abs/2608.17320v1)

- **arXiv**: `2608.17320v1`  |  **提交日期**: 2026-08-18
- **作者**: Ayumu Iwata, Kento Kawaharazuka, Keita Yoneda, Takahiro Hattori, Kei Okada

Brachiation is a form of locomotion in which primates move primarily using their arms, enabling traversal in environments without footholds. However, this motion requires highly coordinated whole-body movement and precise timing control for bar grasping and release. As a result, achieving robust behavior on life-sized robotic platforms remains challenging. In this study, we present a reinforcement learning-based method to realize brachiation on a life-sized dual-arm robot. The core of the proposed approach is Waypoint-Guided Reinforcement Learning (WGRL), a learning framework for inducing…

---

### [PROBE: Manipulation-Grounded Visual Question Answering with VLM Agents](https://arxiv.org/abs/2608.17129v1)

- **arXiv**: `2608.17129v1`  |  **提交日期**: 2026-08-17
- **作者**: Vineet Bhat, Siyi Chen, Alex Zook, Xuning Yang, Stan Birchfield, Valts Blukis et al.

Vision-language Models (VLMs) excel at 2D grounding, spatial reasoning and agentic tool-based planning in static scenes. However, consider asking a home robot "Is my medication still in the cabinet?" The answer may be physically hidden behind a row of containers that must first be moved aside. Answering such questions in real-world cluttered environments requires reasoning in dynamic scenes: distractors must be manipulated to reveal occluded objects, and each action changes the scene the model must reason over. We formalize this setting as Manipulation-Grounded Visual Question Answering…

---

### [FetchMan: Learning Visual Humanoid Loco-Manipulation Policies from Simulated Experiences](https://arxiv.org/abs/2608.17027v1)

- **arXiv**: `2608.17027v1`  |  **提交日期**: 2026-08-17
- **作者**: Omar Rayyan, Zhi Li, Max Argus, Yuxin Jiang, Chang Yu, Chenfanfu Jiang et al.

Visual loco-manipulation policies that can generalize to novel scenes and objects have long been a goal of robotics research. However, today's data-hungry algorithms make collecting sufficient demonstrations a struggle for tabletop manipulation, and even more so for humanoids that must also walk and balance. Learning from simulated data and transferring that behavior to the real world, as is commonly done in locomotion, sidesteps this struggle, so we replicate that recipe for loco-manipulation. In doing so, we find that cloning synthetic demonstrations results in a low performance ceiling no…

---

## 📅 2026-08-18

### [DeepInsight II: One Trace from Benchmark to Robot](https://arxiv.org/abs/2608.16556v1)

- **arXiv**: `2608.16556v1`  |  **提交日期**: 2026-08-17
- **作者**: Siyi Li, Yuchen Kang, Wuliang Wang, Zhengjie Zhang, Jiangpin Liu, Jianhao Yao et al.

Across a Physical AI stack, evaluation maturity is inversely aligned with deployment risk: foundation models enjoy mature, standardized harnesses, while the embodied layers on which deployment actually turns remain fragmented across benchmark-specific simulators, embodiments, and interfaces. The first DeepInsight report (v1) unified evaluation across this stack behind three abstractions---task, resource, and result---but its quantitative evidence centered on the foundation-model layer; navigation and manipulation (System 1) and whole-body control (System 0) remained simulation case studies,…

---

### [Scaling Manual-Grounded Appliance Manipulation with Data Synthesis and Unified Planning](https://arxiv.org/abs/2608.15863v1)

- **arXiv**: `2608.15863v1`  |  **提交日期**: 2026-08-16
- **作者**: Yuxing Long, Lei Kang, Ziyan Yu, Yuzheng Gao, Bin Cheng, Jiyao Zhang et al.

Operating household appliances requires long-horizon planning that is state-dependent and robust to disturbances, yet existing large models fall short, as no sufficiently diverse, task-oriented dataset exists to support such planning. To bridge this gap, we propose MAGE, a scalable data synthesis pipeline that introduces a novel Hierarchical Appliance Graph (HAG) to automatically generate part grounding, long-horizon planning, and closed-loop recovery data from appliance manuals. With MAGE, we build UseAppliance, the first large-scale dataset for manual-grounded appliance manipulation…

---

### [Vision-Based Tactile Intelligence for Robotics: Sensing, Learning, and Embodied Manipulation](https://arxiv.org/abs/2608.15490v1)

- **arXiv**: `2608.15490v1`  |  **提交日期**: 2026-08-16
- **作者**: Peng Zhou, Jun Hu, Sihan Chen, Zeqing Zhang, Haofei Ma, Zhenyu Lu et al.

Tactile sensing is essential for robots in contact-rich tasks, yet many tactile sensors still provide sparse, low-dimensional signals that do not capture sufficient information for complex robotic perception and interaction. Vision-based tactile sensors (VBTSs) offer a powerful alternative by con-verting contact-induced deformation of a soft interface into im-ages. The image-based formulation gives VBTSs high-resolution, information-rich tactile observations that enable complex robotic tasks. This review surveys the full VBTS pipeline and treats sensing hardware, learning methods, simulation,…

---

## 📅 2026-08-17

### [OccPlanner: Goal-Aware Occupancy-Conditioned Diffusion Planner for Pixel-Goal Navigation](https://arxiv.org/abs/2608.14160v1)

- **arXiv**: `2608.14160v1`  |  **提交日期**: 2026-08-14
- **作者**: Binling Huang, Nianjin Ye, Xi Yang, Liang Hu, Zhou Huang, Shuang Wei et al.

Pixel-goal navigation specifies targets directly in the agent's camera view, but a target pixel provides neither metric depth nor traversability, making 3D goal grounding and collision-free continuous planning challenging. We present OccPlanner, a goal-aware occupancy-conditioned diffusion planner that grounds pixel goals in egocentric metric space and sequentially conditions the goal representation on temporal visual context and learned local 3D occupancy features. To provide occupancy supervision at scale, we introduce L3ROcc, which converts monocular RGB navigation videos into…

---

### [AgilePE: Autonomous UAV Pursuit-Evasion via Self-Play Reinforcement Learning](https://arxiv.org/abs/2608.14135v1)

- **arXiv**: `2608.14135v1`  |  **提交日期**: 2026-08-14
- **作者**: Wenhao Tang, Tianyang Chen, Zhejun Cui, Boyuan An, Jiayu Chen, Ruize Zhang et al.

Autonomous pursuit-evasion is a fundamental challenge for Unmanned Aerial Vehicles (UAVs), requiring rapid decision-making under tightly coupled dynamics and continuously changing opponent behaviors. Traditional rule-based or differential-game approaches often struggle with high-dimensional aerial interactions and agile maneuvering. We present AgilePE, a complete system for autonomous UAV pursuit-evasion via self-play reinforcement learning. AgilePE integrates agile low-level control, competitive policy optimization, and sim-to-real deployment in a unified framework. The policy directly maps…

---

## 📅 2026-08-14

### [RGB-D Video Generation for Improving Human-to-Robot Object Handover Prediction](https://arxiv.org/abs/2608.13028v1)

- **arXiv**: `2608.13028v1`  |  **提交日期**: 2026-08-13
- **作者**: Tianyu Sun, Zhoujie Fu, Zihui Gao, Bang Zhang, Guosheng Lin

Human-to-robot (H2R) object handover is a fundamental capability for human-robot collaboration, yet progress is hindered by the scarcity of large-scale, human-centric datasets and the significant sim-to-real gap. To address these challenges, we introduce Hand2Bot, an RGB-D video dataset that provides rich contextual information such as body posture and facial expressions, specifically collected for handover scenarios with real-world noise patterns. We further propose PassGen, a generative pipeline that leverages stable video diffusion and an Intention-Aware Temporal Face Encoder to synthesize…

---

### [EgoPHI: Estimating Contact and Force from Egocentric Vision](https://arxiv.org/abs/2608.13014v1)

- **arXiv**: `2608.13014v1`  |  **提交日期**: 2026-08-13
- **作者**: Andela Ilic, Rachel Schuchert, Yijing Jiang, Christian Holz

Understanding hand-object interaction from egocentric vision is essential for modeling how people physically engage with the surrounding world. Yet reasoning about physically grounded interaction requires estimating the forces acting on hands and objects, beyond localizing contact. We present EgoPHI, the first method that jointly estimates dense contact maps and 3D force distributions on hand and object meshes from a single monocular RGB image and object geometry. To address the lack of scalable ground-truth force annotations, we introduce a physics-based simulation pipeline that augments…

---

## 📅 2026-08-13

### [DaViNCi: A Dataset Towards Outdoor Vision-and-Language Navigation with Continuous Actions and Dynamic Elements](https://arxiv.org/abs/2608.11901v1)

- **arXiv**: `2608.11901v1`  |  **提交日期**: 2026-08-12
- **作者**: Zihao Xie, Pingrui Lai, Yitong Wu, Hua Yang

Vision-and-Language Navigation (VLN) has progressively expanded from indoor to outdoor environments. However, existing outdoor VLN datasets still rely on fixed discrete topological graphs for construction. It fails to align with the rapidly changing real-world outdoor environments and impedes the sim-to-real transfer of VLN agents. To address this limitation, we propose DaViNCi (\textbf{D}yn\textbf{a}mic \textbf{Vi}sion-and-Language \textbf{N}avigation in \textbf{C}ont\textbf{i}nuous Environment), the first outdoor VLN dataset that simultaneously introduces both continuous and dynamic…

---

## 📅 2026-08-12

### [Overcoming Data Scarcity and Confidentiality in Hardware Assurance via Synthetic Generation](https://arxiv.org/abs/2608.09914v1)

- **arXiv**: `2608.09914v1`  |  **提交日期**: 2026-08-10
- **作者**: Gijung Lee, Ronald Wilson, Damon L. Woodard, Domenic Forte

Hardware assurance relies on scanning electron microscopy (SEM) to verify nanoscale structures, but assembling the large, high-quality datasets required for automated analysis is impeded by time-intensive acquisition and strict intellectual property (IP) constraints on proprietary designs. We propose a privacy-preserving pipeline that secures IP by heavily distorting the functional design while generating a visually realistic synthetic dataset from a small set of initial examples. A StyleGAN first learns the distribution of hardware layout masks to generate novel, macroscopically varied…

---

## 📅 2026-08-11

### [SAFE-CHEM: Uncertainty-Aware Policy Switching for Robust Robotic Chemistry](https://arxiv.org/abs/2608.09303v1)

- **arXiv**: `2608.09303v1`  |  **提交日期**: 2026-08-10
- **作者**: Laura Jones, Shazil Shahzad, Ayesha Sana, Gabriella Pizzuto

The deployment of autonomous robotic systems in chemistry laboratories is accelerating experimental workflows and providing the foundational data for AI-driven scientific discovery. However, despite the success of data-driven methods in acquiring dexterous skills, safety remains a primary barrier to their deployment in high-risk domains, such as early-stage materials chemistry experiments. Specifically, learning-based policies frequently struggle to distinguish between safe and unsafe actions, leading to overconfident extrapolation and potentially catastrophic failures. To mitigate these…

---

## 📅 2026-08-07

### [From Economic Agents to Agentic Economies: A Systems Blueprint for Economic World Models](https://arxiv.org/abs/2608.06020v1)

- **arXiv**: `2608.06020v1`  |  **提交日期**: 2026-08-06
- **作者**: Jiale Han, Xiang Li, Jing Qian, Wenyuan Gu, Pin Gao, Ye Luo et al.

Economic World Models (EWMs) are generative economic models that simulate how economies evolve from within by modeling heterogeneous agents, their beliefs and actions, and the market and institutional mechanisms through which their interactions produce aggregate outcomes. This paper develops an implementation roadmap for building economic world models as generative engines in which heterogeneous agents act, interact, adapt, and co-evolve with markets and institutions, thereby producing economic dynamics from the inside. We organize EWM systems into a six-level capability ladder, from fixed…

---

### [Dual-Attention and Adversarial Transfer Networks for Sim-to-Real Cross-Orientation Wireless Sensing](https://arxiv.org/abs/2608.05664v1)

- **arXiv**: `2608.05664v1`  |  **提交日期**: 2026-08-06
- **作者**: Linfeng Du, Kehan Wu, Tong Zhang, Rui Wang

Millimeter-wave human activity recognition suffers significant performance degradation when the user's orientation changes relative to the sensing system, yet collecting labeled multi-orientation data is labor-intensive and costly. To eliminate the need for exhaustive multi-orientation measured data, we develop a physics-guided simulator that synthesizes orientation-diverse wireless training data from single-orientation motion. Specifically, to suppress orientation-induced feature variations, we propose a dual-attention network that extracts activity-discriminative and orientation-robust…

---

### [MobileWAM: Bridging World Action Models to Mobile Manipulation with Chain-of-Foresight](https://arxiv.org/abs/2608.04657v2)

- **arXiv**: `2608.04657v2`  |  **提交日期**: 2026-08-05
- **作者**: Zehua Fan, Junjie He, Wenxuan Song, Xi Wang, Wenqi Lyu, Linge Zhao et al.

World action models (WAMs) built on video generation backbones are a rising recipe for robot learning, yet remain confined to tabletop manipulation. Mobile manipulation demands simultaneous locomotion and whole-body manipulation amid scene-scale dynamics, yet is still dominated by dynamics-blind visual encoders with hand-crafted coordination. We bridge this gap with MobileWAM, a mixture-of-transformers architecture that fuses a pretrained video diffusion transformer with a lightweight action expert through layerwise joint attention, translating internet-scale motion priors into whole-body…

---

## 📅 2026-08-06

### [RORA: Realistic Object Reconstruction with Articulation](https://arxiv.org/abs/2608.04842v1)

- **arXiv**: `2608.04842v1`  |  **提交日期**: 2026-08-05
- **作者**: Hyesung Lee, Youngseon Lee, Kyutae Lee, Dongjun Lee, Yongseok Lee

Replicating real-world environments into simulation by realistic visual representation like NeRF and 3D Gaussian Splatting (3DGS) has emerged as an effective strategy to reduce the sim-to-real gap in robot learning. However, implementing object articulation during the real-to-sim process is still a challenging task. Existing motion tracking or learning based articulation methods shows low success rates on complex kinematic structures having multiple joints. Furthermore, those methods require scan of dynamic motion of objects, which makes reconstruction process much complicated. In this work,…

---

### [Explicit Language Memory for Long-Horizon Planning in Vision-Language-Action Models](https://arxiv.org/abs/2608.04765v1)

- **arXiv**: `2608.04765v1`  |  **提交日期**: 2026-08-05
- **作者**: Houze Xu, Jizhong Li, Ziyi Ye

Vision-language-action (VLA) models provide a unified paradigm for connecting visual perception, language understanding, and robotic control. However, existing VLA models still face major challenges in long-horizon tasks: sparse expert demonstrations constrain cross-task compositional generalization; the non-Markovian nature of long-horizon tasks makes it difficult for policies conditioned only on current observations to maintain temporal consistency; limited closed-loop error correction allows execution errors to accumulate; and end-to-end action fine-tuning may weaken the high-level…

---

### [MobileWAM: Bridging World Action Models to Mobile Manipulation with Chain-of-Foresight](https://arxiv.org/abs/2608.04657v1)

- **arXiv**: `2608.04657v1`  |  **提交日期**: 2026-08-05
- **作者**: Zehua Fan, Junjie He, Wenxuan Song, Xi Wang, Wenqi Lyu, Linge Zhao et al.

World action models (WAMs) built on video generation backbones are a rising recipe for robot learning, yet remain confined to tabletop manipulation. Mobile manipulation demands simultaneous locomotion and whole-body manipulation amid scene-scale dynamics, yet is still dominated by dynamics-blind visual encoders with hand-crafted coordination. We bridge this gap with MobileWAM, a mixture-of-transformers architecture that fuses a pretrained video diffusion transformer with a lightweight action expert through layerwise joint attention, translating internet-scale motion priors into whole-body…

---

### [SAFECAST: Robust Failure Detection for VLA Policies with Contrast-Set Training and Calibration](https://arxiv.org/abs/2608.04246v1)

- **arXiv**: `2608.04246v1`  |  **提交日期**: 2026-08-04
- **作者**: Harshitha Rajaprakash, Aditeya Prajapati, Rong Xue, Abrar Anwar, Jesse Thomason

Vision-language-action policies often fail under deployment-time distribution shifts such as clutter, distractor objects, lighting changes, novel objects, altered initial states, and reworded instructions. Hidden-state-based risk probes combined with functional conformal prediction can detect rollout failures, but their reliability depends on calibration data matching deployment conditions. We introduce SAFECAST, which leverages contrast set perturbations to improve hidden-state probe training and calibration for deployment time shift. SAFECAST statistically significantly improves failure…

---

## 📅 2026-08-05

### [Shooting for Contact: Contact-Implicit Multiple Shooting for Dynamic Motion Retargeting](https://arxiv.org/abs/2608.03116v1)

- **arXiv**: `2608.03116v1`  |  **提交日期**: 2026-08-04
- **作者**: Sergio A. Esteban, Jason H. K. Siu, Derrick Mach, Junheng Li, Vince Kurtz, Joel W. Burdick et al.

Motion retargeting approaches often prioritize kinematic similarity over whole-body dynamics, contact consistency, and actuation limits, yielding references that are difficult for reinforcement learning (RL) policies to reproduce, particularly for contact-rich behaviors. We present a contact-implicit, direct simulation-based multiple shooting (DSMS) framework that transforms kinematically feasible references into dynamically feasible whole-body trajectories. By embedding a differentiable simulator within a nonlinear program, DSMS resolves contact, friction, impacts, self-collision, and joint…

---

## 📅 2026-08-04

### [Certifying Plans under Model Mismatch: A Trilemma for Reachability from Scarce Data](https://arxiv.org/abs/2608.02453v1)

- **arXiv**: `2608.02453v1`  |  **提交日期**: 2026-08-03
- **作者**: Yanliang Huang, Zhen Zhang, Ahmad Hafez, Wenyuan Wu, Peng Xie, Zhuoqi Zeng et al.

Sim-to-real policies are designed under nominal dynamics, but target-system trials may yield only a few isolated one-step transitions. We study pre-execution certification of a fixed control sequence, such as an action chunk produced by a learned policy. If the sequence reaches an unobserved state-input region, the observations remain consistent with target systems whose trajectories separate along it by an arbitrarily large amount. Any deterministic certifier sound for all of them must then decline to certify or return a reachable tube with arbitrarily large projected width. For bounded…

---

### [Bridging the Sim-to-Real Gap in Parallel-Link Leg Mechanisms via Simulator-Side Dynamics Normalization](https://arxiv.org/abs/2608.01697v1)

- **arXiv**: `2608.01697v1`  |  **提交日期**: 2026-08-03
- **作者**: Jinsong Hong, Jangho Kim, Jihwan Lee, Donghyun Kim, Sehoon Oh

This paper addresses the sim-to-real gap in dynamics arising when a parallel-link mechanism is represented by a serial-tree surrogate in simulation. Conventional Jacobian-based state and torque mappings preserve consistency with the kinematic and virtual-work relations but do not account for the coordinate-induced redistribution of actuator inertia and damping and the linkage inertia omitted during serial-tree reduction. To address this gap, Simulator-Side System Normalization (S3N) is proposed to normalize the serial-tree simulator's effective dynamics while preserving its tree topology.…

---

### [STAR-VLM: Spatiotemporal Grounding Vision-Language Models for Motion and Velocity Estimation via Automotive Radar Supervision](https://arxiv.org/abs/2608.01535v1)

- **arXiv**: `2608.01535v1`  |  **提交日期**: 2026-08-02
- **作者**: Pou-Chun Kung, Aryaman Rao, Utkrisht Sahai, Hemanth Murali, Yi Liu, Rui-Yu Lin et al.

Vision-language models (VLMs) are emerging as a key component of embodied intelligence, with growing applications in auto-labeling and end-to-end autonomous driving. However, existing approaches for improving spatiotemporal reasoning in VLMs often rely on complex preprocessing pipelines, expensive human annotations, or synthetic data, which limit scalability and introduce potential sim-to-real gaps. Moreover, although these methods have improved spatiotemporal understanding, they still lack strong metric reasoning capabilities for dynamic scenes, such as estimating object motion in real-world…

---

### [Learning-Based Motion Planning for Dynamic Environments: From Foundational Algorithms to Emerging Paradigms](https://arxiv.org/abs/2608.00625v1)

- **arXiv**: `2608.00625v1`  |  **提交日期**: 2026-08-01
- **作者**: Zongyuan Shen, Shalabh Gupta, Shancheng Zhao, Dehua Zhou, Gao Wang, Rui Cheng et al.

Motion planning in dynamic environments is a fundamental problem in robotics, aiming to generate safe and efficient paths, trajectories, or control actions in the presence of moving obstacles, uncertain predictions, and multi-agent interactions. It has broad applications in autonomous driving, service robotics, warehouse logistics, human-robot collaboration, crowd navigation, and multi-robot systems. This survey reviews representative works published primarily between 2015 and 2025, with a particular focus on how recent learning-based advances extend, complement, or interact with classical…

---

## 📅 2026-08-03

### [RayViT: Ray-Conditioned Visual Representations for Viewpoint-Robust Imitation Learning](https://arxiv.org/abs/2607.29622v1)

- **arXiv**: `2607.29622v1`  |  **提交日期**: 2026-07-31
- **作者**: Qian Wang, Longrui Chen, Peiran Sun, Aleksandar Taranovic, Niklas Freymuth, Ge Li et al.

Visual imitation learning enables robots to acquire visuomotor skills directly from images, yet RGB observations lack explicit geometric cues, making learned policies brittle to camera perturbations. To address this, we propose \textbf{Ray-conditioned Vision Transformer Encoder (RayViT)}, a lightweight architecture that injects camera geometry into pretrained ViT backbones. RayViT represents camera geometry as a Plücker ray map, patchifies it into ray features, and uses gated cross-attention to produce a ray-conditioned class token. These ray features are added as dense positional embeddings,…

---

### [BWM: A Low-Cost High-Fidelity World Simulator for Robot Learning](https://arxiv.org/abs/2607.29302v1)

- **arXiv**: `2607.29302v1`  |  **提交日期**: 2026-07-31
- **作者**:  BWM Team

Reliable robot learning requires a world simulator that can predict action consequences before execution on physical hardware, including risky and failure-prone outcomes. Existing physics simulators require substantial asset construction and calibration and still face a sim-to-real gap, while video generators often lack precise control over their responses to fine-grained robot actions. In this paper, we present the Boundless World Model (BWM), an open-source, low-cost, high-fidelity world simulator for robot manipulation. BWM is an action-conditioned world model that combines…

---

### [TacPrint: A Wearable Fingertip Tactile Sensor for Human-to-Robot Contact Reproduction](https://arxiv.org/abs/2607.29231v1)

- **arXiv**: `2607.29231v1`  |  **提交日期**: 2026-07-31
- **作者**: Yongxi Liu, Chaofan Zhang, Xingyu Zhang, Xiangyin Bao, Boyue Zhang, Shaowei Cui et al.

Human-centric data collection is emerging as a significant paradigm for robot skill acquisition, but seamlessly integrating low-cost, scalable tactile sensing systems that capture fine-grained fingertip interactions without compromising natural operation remains a key challenge. This reduces the reliability of human-to-robot transfer in contact-rich tasks. In this work, we present TacPrint, a wearable fingertip tactile sensor, where protrusions on the inner surface of the silicone skin are aligned one-to-one with 24 capacitive taxels to enable localized capacitive responses. A…

---

## 📅 2026-07-31

### [Cross-Embodiment Transfer via Behavior-Aligned Representations](https://arxiv.org/abs/2607.27549v1)

- **arXiv**: `2607.27549v1`  |  **提交日期**: 2026-07-30
- **作者**: Ajay Sridhar, Jensen Gao, Jonathan Yang, Jean Mercat, Suneel Belkhale, Dorsa Sadigh

Recent progress in large-scale imitation learning for robot manipulation has been driven by leveraging datasets across a wide range of robot embodiments. However, achieving significant cross-embodiment transfer is often still challenging. In this work, we study the role of using behavior-aligned representations (e.g., object bounding boxes, language motions, end-effector traces of robot motion) in vision-language-action (VLA) models to promote cross-embodiment transfer. We hypothesize that by possessing invariances across embodiments while being predictive of robot actions, these…

---

## 📅 2026-07-29

### [Shared Voxel-Map-Based Cooperative Indoor UAV Guidance with a Multi-Agent Soft Actor-Critic Controller](https://arxiv.org/abs/2607.25728v1)

- **arXiv**: `2607.25728v1`  |  **提交日期**: 2026-07-28
- **作者**: Thomas Hickling, Dylan Wynne, Yu Su, Nabil Aouf

This paper presents a cooperative indoor UAV guidance framework that combines a shared voxel-map world model with a multi-agent Soft Actor-Critic (MASAC) controller. Multiple drones fuse 360 LiDAR observations into a common world-frame occupancy map, which is converted into a compact bird's-eye-view (BEV) representation and provided to each agent as an ego-aligned local crop. This integrate-in-world, act-in- ego design enables consistent multi-UAV spatial fusion whilst retaining decentralised continuous control. The policy combines BEV map features, near-field obstacle observations, and…

---

### [Egocentric Station Holding of Robotic Fish in Unknown Turbulent Background Flow](https://arxiv.org/abs/2607.24860v1)

- **arXiv**: `2607.24860v1`  |  **提交日期**: 2026-07-26
- **作者**: Xiaozhu Lin, Xu Huang, Hongru Dai, Xiaopei Liu, Junzhi Yu, Yang Wang

Approaching a target position and holding station in flowing water is a fundamental and critical capability for robotic fish operating in natural aquatic environments. Despite decades of advances in enhancing swimming efficiency and maneuverability, this capability remains underdeveloped, largely owing to the insufficiently characterized, highly nonlinear fluid-structure interactions inherent to freely swimming robotic fish in flows. To bridge this gap, we propose the SWiFT framework, a Swimming With Flow Toolbox that enables the efficient exploration of an egocentric station-holding policy…

---

## 📅 2026-07-28

### [Effective Parameters, Real Behavior: Renormalization for Robotics -- From Infinite Electron Mass to Sim-to-Real Gap](https://arxiv.org/abs/2607.24079v1)

- **arXiv**: `2607.24079v1`  |  **提交日期**: 2026-07-27
- **作者**: Youran Sun, Jiaxuan Guo, Xingyu Ren, Chugang Yi, Haizhao Yang

Bridging the sim-to-real gap is a central problem in robotics, and the prevailing approach is to build increasingly accurate simulators. Here, we propose another approach based on renormalization: using effective, resolution-dependent parameters to absorb details omitted by the simulator and reproduce real behavior. These parameters may differ from measured physical values because they compensate for what the simulator leaves out. We demonstrate this mechanism analytically for proportional--derivative (PD) control at finite simulation frequency, where proportional feedback changes the…

---

### [Anticipatory Risk-Guided Reinforcement Learning for Safe Flight Through Dynamic Clutter](https://arxiv.org/abs/2607.23565v1)

- **arXiv**: `2607.23565v1`  |  **提交日期**: 2026-07-26
- **作者**: Yuchao Mei, Guohao Zhang, Luxia Ai, Haopeng Chen, Wenbing Tao

Safe quadrotor navigation in cluttered and dynamic environments depends not only on instantaneous geometric perception, but more critically on anticipating collision risks induced by relative motion. Conventional modular pipelines frequently suffer from perception latency, while end-to-end learning methods relying on implicit scalar rewards often struggle to extract reliable spatio-temporal features without physics-grounded supervision. To address this, we propose an anticipatory risk-guided reinforcement learning framework. Leveraging privileged simulator states, we construct a directionally…

---

## 📅 2026-07-24

### [Grasp, Handover, Rotate: Bimanual Object Reorientation via Compositional Diffusion and Energy-Based Optimization](https://arxiv.org/abs/2607.21341v1)

- **arXiv**: `2607.21341v1`  |  **提交日期**: 2026-07-23
- **作者**: Wun Lam Yeung, Wenjun Liu, Yui Cheung Yu, Zhengyan Lambo Qin, Qijin She, Heng Li et al.

Bimanual object reorientation - picking an object, handing it over between two arms, and placing it in a desired target pose - is valuable when direct placement from the initial grasp is infeasible due to collisions, kinematic constraints, or poor final orientation. However, achieving this under multiple competing objectives remains challenging. We introduce BiCompoDiff, a compositional diffusion and energy-based framework that jointly optimizes grasp selection, handover, regrasp, and motion planning under multiple constraints. By combining a pretrained grasp diffusion model with bimanual…

---

### [FORGE-plus: Force-Budgeted Recovery for Contact-Rich Assembly with a Frozen LLM Supervisor](https://arxiv.org/abs/2607.21227v1)

- **arXiv**: `2607.21227v1`  |  **提交日期**: 2026-07-23
- **作者**: Kyupaeck Jeff Rah, Midum Oh

Force-conditioned reinforcement learning (RL) enables tight-clearance assembly under a commanded force ceiling, but practical deployment requires determining an appropriate force limit for each object and recovering from insertion failures without exceeding it. We present a two-layer framework in which a frozen, text-only large language model (LLM) assigns a per-object force ceiling before execution and selects recovery maneuvers from a fixed action menu using compact textual force signatures. The LLM never controls force directly: a low-level controller enforces the force ceiling, the…

---

### [Safe and Scalable Multi-Drone Payload Transport via CBF-based Reinforcement Learning with Zero-Shot Sim-to-Real Transfer](https://arxiv.org/abs/2607.20665v1)

- **arXiv**: `2607.20665v1`  |  **提交日期**: 2026-07-22
- **作者**: Jaeyoun Choi, Oswin So, Songyuan Zhang, Cooper Taylor, Chuchu Fan

Multi-drone payload transportation has emerged as a promising research paradigm with potential applications in construction, logistics, and disaster response. However, the complex coupled dynamics among drones, cables, and payloads pose significant challenges, and existing approaches remain limited in safety and scalability, particularly in dynamic and unstructured environments. In this work, we propose a learning-based framework for safe and scalable multi-drone cooperative payload transport. We introduce a minimal 2D abstraction that preserves the task-relevant drone-payload coupling…

---

## 📅 2026-07-23

### [SafeGen: Goal-Conditioned Video Diffusion of Safety-Critical Scenarios for VLM-Based Autonomous Driving](https://arxiv.org/abs/2607.19701v1)

- **arXiv**: `2607.19701v1`  |  **提交日期**: 2026-07-22
- **作者**: Jiangfan Liu, Zexuan Cui, Tianyuan Zhang, Zonglei Jing, Zonghao Ying, Yaoyuan Zhang et al.

VLMs are increasingly deployed in AD systems, creating an urgent need for rigorous safety evaluation under rare yet safety-critical scenarios. Among these, interactions with vulnerable road users represent a major source of real-world failures. However, existing safety-critical scenario generation methods predominantly rely on simulator-based pipelines, which suffer from a substantial sim-to-real gap and often fail to capture realistic, diverse, and unforeseen human-vehicle interaction dynamics. We present SafeGen, a goal-conditioned diffusion framework for safety-critical scenario generation…

---

## 📅 2026-07-22

### [Beyond Transformers: Linear Attention Policy for Open-Vocabulary Object Goal Navigation](https://arxiv.org/abs/2607.18794v1)

- **arXiv**: `2607.18794v1`  |  **提交日期**: 2026-07-21
- **作者**: Jiahong Zhang, Yifan Lin, Yandong Zhang, Sijun Shen, Kexin Wang, Yuqi Pan et al.

Open-Vocabulary Object Goal Navigation (OVON) requires agents to operate under partial observability, making effective internal state updates critical for navigation performance. This update is implemented by the policy network, where recent approaches adopt Transformer-based backbones with self-attention over a context window to integrate temporal information. However, our controlled experiments show that performance does not scale with context length under Transformer-based policies, questioning the suitability of self-attention for state integration in navigation. To this end, we propose…

---

### [Bridging the Sim-to-Real Gap under Real-Time Constraints in Autonomous Racing](https://arxiv.org/abs/2607.18586v1)

- **arXiv**: `2607.18586v1`  |  **提交日期**: 2026-07-20
- **作者**: Hossein Maghsoumi, Yaser P. Fallah

Autonomous racing exposes the sim-to-real gap under extreme operating conditions characterized by high speed, tight stability margins, and stringent real-time constraints. Although simulation is indispensable for development, controllers that perform well in simulation often degrade abruptly on physical platforms due to interacting effects of dynamics mismatch, estimation delay, and execution-layer latency. This paper frames sim-to-real transfer in autonomous racing as a full-stack, real-time systems problem. We introduce a structured three-layer perspective (Physical/Cyber/Execution) to…

---

### [Text-conditioned Segmentation for Tomato Phenotyping via Procedural Synthetic Data](https://arxiv.org/abs/2607.18576v1)

- **arXiv**: `2607.18576v1`  |  **提交日期**: 2026-07-20
- **作者**: Samy Mounir, Mikolaj Cieslak, Najmeddine Dhieb, Hakim Ghazzai, Jonathan Klein, Katja Froehlich et al.

Vision-based automation is an excellent candidate for reducing manual labor in greenhouse crop production and phenotyping. However, progress is constrained by the lack of annotated training data. Recent advances in vision-based foundational models have shown promising results in zero-shot generalization to novel domains, but their performance drops in complex agricultural environments. In this work, we present a sim-to-real framework for tomato plant segmentation that combines synthetic data generation with fine-tuning of a foundation model. We model a commercial cherry tomato greenhouse and…

---

## 📅 2026-07-21

### [Multi-scale closed-loop melt pool control for LPBF via policy optimization](https://arxiv.org/abs/2607.17438v1)

- **arXiv**: `2607.17438v1`  |  **提交日期**: 2026-07-19
- **作者**: Junan Lin, Riccardo Zuliani, Baris Kavas, Markus Bambach, John Lygeros, Efe C. Balta

Laser powder bed fusion (LPBF) is a metal additive manufacturing process where temperature stabilization is of vital importance to avoid defects such as distortion and cracking. Existing control methods require manual tuning, increasing the risk of part failure when printing complex geometries. This paper introduces a dual-loop, data-driven control strategy to stabilize the surface temperature, ensuring robustness and near-optimal performance in the presence of disturbances. The proposed method integrates (i) an in-layer linear output feedback control with gains optimized through policy…

---

## 📅 2026-07-20

### [A Task-Space Receding Horizon Controller for Fast Collision Avoidance](https://arxiv.org/abs/2607.15733v1)

- **arXiv**: `2607.15733v1`  |  **提交日期**: 2026-07-17
- **作者**: Mattia Penzotti, Marco Controzzi

Real-time collision avoidance for robotic manipulators requires fast reactions to unexpected obstacle motion and lookahead to avoid becoming trapped by near-future constraints. Full model predictive control can provide this foresight, but its online cost may grow quickly with horizon length, model fidelity, and the number of active geometric constraints. Conversely, horizon-free reactive methods are computationally efficient but can be short-sighted in dynamic clutter. We present a task-space receding-horizon controller that uses a short contact-consistent rollout to generate a terminal…

---

### [Difference-Based Relational Learning for Zero-Shot Object-Goal Visual Navigation With Direct Sim-to-Real Transfer](https://arxiv.org/abs/2607.15642v1)

- **arXiv**: `2607.15642v1`  |  **提交日期**: 2026-07-17
- **作者**: Guolei Qi, Feitian Zhang

End-to-end deep reinforcement learning (DRL) for zero-shot object-goal visual navigation remains challenged by the sim-to-real gap, particularly variations in object appearance and restricted camera field-of-view (FoV). This letter proposes a Temporal Difference-Relational Network (T-DRN) for robust zero-shot sim-to-real transfer. T-DRN combines a Siamese difference-based feature extractor, which computes relational difference between the target and observed objects to produce domain-independent representations, with a dual-frame temporal buffer that preserves short-term object continuity…

---

## 📅 2026-07-17

### [SUFLECA: Scaling Up Feature Learning for CAD-to-image Alignment](https://arxiv.org/abs/2607.15058v1)

- **arXiv**: `2607.15058v1`  |  **提交日期**: 2026-07-16
- **作者**: Saad Ejaz, Miguel Fernandez-Cortizas, Javier Civera, Holger Voos, Jose Luis Sanchez-Lopez

CAD-to-image alignment aims to estimate an object's 9D pose (rotation, translation, and anisotropic scale) from a single RGB image, enabling applications in robotics and augmented reality. Recent zero-shot methods use visual foundation models to match image regions to CAD models, yet typically their correspondences are appearance-driven and degrade under occlusion or sim-to-real domain shift. To address these limitations, we introduce SUFLECA (Scaling Up Feature LEarning for CAD Alignment), a weakly-supervised framework for zero-shot CAD alignment with two key contributions. First, SUFLECA…

---

### [Reinforcement Learning for the Full Strawberry Harvesting Process: Obstacle Separation, Detachment, and Placement](https://arxiv.org/abs/2607.14708v1)

- **arXiv**: `2607.14708v1`  |  **提交日期**: 2026-07-16
- **作者**: Changyou Miao, Teng Li, Ya Xiong

Severe occlusions and deformable plant structures introduce complex contact dynamics that challenge robotic strawberry harvesting. A policy-driven reinforcement learning (RL) framework with heuristic phase coordination was developed, in which obstacle separation, fruit detachment, and placement were formulated as a sequential decision-making task. A shared interaction-aware policy generated Cartesian motions across all task phases, while lightweight heuristic logic coordinated task progression and gripper events. A shared structured observation space was used to represent target, obstacle,…

---

### [NavCMPO: Critic-Guided MeanFlow Policy Optimization for Adaptive Navigation](https://arxiv.org/abs/2607.14643v1)

- **arXiv**: `2607.14643v1`  |  **提交日期**: 2026-07-16
- **作者**: Junjie An, Yi Wu, Xiao Liu, Yiqun Zhou, Yuechen Wu, Xiaoqing Guan et al.

End-to-end diffusion-based policies have demonstrated strong performance in mapless visual navigation, but their iterative denoising process introduces substantial inference latency, while behavior cloning limits performance to the quality of expert demonstrations. We present NavCMPO, a two-stage adaptive navigation framework that combines few-step MeanFlow trajectory generation, critic-guided refinement, and reinforcement learning fine-tuning. During pre-training, an obstacle proximity prediction task encourages the visual representation to capture obstacle-aware spatial information. To…

---

### [Action QFormer: Structured Representation Shaping under Action Supervision in Vision-Language-Action Models](https://arxiv.org/abs/2607.14635v1)

- **arXiv**: `2607.14635v1`  |  **提交日期**: 2026-07-16
- **作者**: Yufeng Ji, Wenhao Tang, Haoyi Niu, Koushil Sreenath, Yi Wu, Zhongyu Li

Action supervision in vision-language-action (VLA) models is often treated as a downstream objective for learning action prediction. In this paper, we study it instead as a force that shapes inherited multimodal representations. We show that this shaping has a dual effect: it is necessary for forming action-compatible representations, but when action supervision is applied too directly to the inherited multimodal pathway, it can also destabilize representations that support language-side processing and object grounding. To address this tension, we introduce Action QFormer, a query-based…

---

## 📅 2026-07-16

### [Vision-Based Obstacle Separation for Strawberry Harvesting in Clusters Using Hierarchical Reinforcement Learning](https://arxiv.org/abs/2607.13799v1)

- **arXiv**: `2607.13799v1`  |  **提交日期**: 2026-07-15
- **作者**: Teng Li, Hanfei Shi, Chunjiang Zhao, Ya Xiong

Selective harvesting in clustered strawberry environments is challenging because ripe fruits are often occluded by surrounding unripe fruits, making direct grasping unreliable. To address this problem, this paper proposes a hierarchical reinforcement learning framework, termed VGPA, which integrates a vision-guided decision mechanism and a Progressive Adaptive Exploration Strategy (PAES) for vision-based obstacle separation and harvesting. The task was decomposed into two sequential stages: obstacle separation and target grasping. At the high level, the vision-guided mechanism improved option…

---

### [Exploratory, Communicative, and Deployable: Vision-Driven Embodied Agents for Open-World Mobile Manipulation](https://arxiv.org/abs/2607.13653v1)

- **arXiv**: `2607.13653v1`  |  **提交日期**: 2026-07-15
- **作者**: Boyu Mi, Mengchen Ma, Yifei Yao, Xing Gao, Junting Chen, Yangzi Li et al.

Real-world deployment of embodied agents requires active exploration, visual grounding, and interactive intent disambiguation. However, existing frameworks often rely on privileged simulator states or assume complete instructions, bypassing realistic deployment challenges. To bridge this gap, we present REAL, an agentic framework for open-world mobile manipulation. REAL establishes sim-to-real-consistent environment APIs without oracle perception and integrates a simulated user to enable human-in-the-loop interaction. Within this environment, we design diverse task compositions to drive data…

---

## 📅 2026-07-15

### [Robust In-Hand Manipulation via Priors in Reinforcement Learning and Mechanical Design](https://arxiv.org/abs/2607.12105v1)

- **arXiv**: `2607.12105v1`  |  **提交日期**: 2026-07-13
- **作者**: Yifei Chen, Shihan Lu, Ed Colgate, Kevin Lynch

In-hand manipulation without external sensing is challenging due to uncertainties from finger-object contacts and disturbances by gravity. While reinforcement learning has shown promise in learning complex finger gaiting, existing approaches do not prioritize maintaining well-conditioned grasps for sustained manipulation. We introduce two complementary physics priors for robust in-hand rolling: a global grasp-quality prior derived from classical grasp analysis and a local contact-geometry prior based on fingertip curvature. The grasp-quality prior is used as a dense reward-shaping term that…

---

## 📅 2026-07-14

### [A Minimalist Retargeting-Guided Reinforcement Learning Recipe for Dexterous Manipulation](https://arxiv.org/abs/2607.11874v1)

- **arXiv**: `2607.11874v1`  |  **提交日期**: 2026-07-13
- **作者**: Yunhai Feng, Natalie Leung, Jiaxuan Wang, Lujie Yang, Haozhi Qi, Preston Culbertson

Recent work in humanoid whole-body control has found success with a simple recipe: retarget human motion to robot kinematic references, then train policies via reinforcement learning (RL) to track them. But how does this recipe transfer to dexterous manipulation? The answer is not obvious, as manipulation involves complex, contact-rich dynamics and requires delicate regulation of contact modes and forces. We present REGRIND, a minimalist retargeting-guided RL pipeline that learns dexterous manipulation policies from a single human demonstration. REGRIND retargets human hand-object motion to a…

---

### [NeuralActuator: Neural Actuation Modeling for Robot Dynamics and External Force Perception](https://arxiv.org/abs/2607.11734v1)

- **arXiv**: `2607.11734v1`  |  **提交日期**: 2026-07-13
- **作者**: Zhiyang Dou, John U. Onyemelukwe, Hangxing Zhang, Heng Zhang, Minghao Guo, Yunsheng Tian et al.

Differentiable simulators have advanced policy learning and model-based control, yet actuator dynamics remain an important source of sim-to-real error. This is particularly acute on low-cost platforms, where the linear current-to-torque relation $τ= K_tI$ becomes unreliable during commanded-target tracking because of friction, hysteresis, backlash, and thermal effects. We present NeuralActuator, a neural actuator model that jointly predicts (i) a simulator-equivalent generalized-effort surrogate for trajectory propagation on low-cost servo platforms, (ii) external force with a…

---

### [Affordance-Based Manipulation Planning with Text Goals and Sim-to-Real Generalisation via Real-to-Sim Image Conversion](https://arxiv.org/abs/2607.11004v1)

- **arXiv**: `2607.11004v1`  |  **提交日期**: 2026-07-13
- **作者**: Solvi Arnold, Rin Karashima, Tadashi Adachi, Takafumi Mochizuki, Kimitoshi Yamazaki

We present a manipulation planning system based on affordance recognition and action effect prediction. The system reasons through possible futures in visual form, and evaluates candidate plans by agreement of predicted outcomes with text-based goals set at run-time, using a multi-modal goal-matching module. Positions of objects named in the goal text are tracked through predictions even when occluded, making it possible to generate action plans even when objects become occluded, or when their initial descriptors cease to identify them in future states. We further expand the system with an…

---

### [A Single Diffusion-Policy Controller for Multi-Task Block Pushing with Zero-Shot Sim-to-Real Transfer](https://arxiv.org/abs/2607.10892v1)

- **arXiv**: `2607.10892v1`  |  **提交日期**: 2026-07-12
- **作者**: Haitong Ma, Haldun Balim, Yang Hu, Bo Dai, Na Li

Diffusion policies have shown promising empirical performance in representing and learning complex maneuvers for robots using behavior cloning (BC). In this paper, we explore training diffusion policies from scratch using reinforcement learning (RL) for multi-task robotic manipulation. Specifically, we aim to train a single diffusion policy for block-pushing tasks with multiple shapes. The proposed framework features a simple policy loss function, which is a reweighted evidence lower bound used in BC-based diffusion policy training and can seamlessly serve as the policy learning module in RL…

---

### [D-SafeMPC: Diffusion-Driven Safe Model Predictive Control with Discrete-Time Control Barrier Functions](https://arxiv.org/abs/2607.10842v1)

- **arXiv**: `2607.10842v1`  |  **提交日期**: 2026-07-12
- **作者**: Erdi Sayar, Ersin Daş, Joel W. Burdick, Alois Knoll, Erdal Kayacan

A key limitation on the use of diffusion models in robotic planning is their inability to inherently enforce safety or dynamical constraints, which often results in physically infeasible or unsafe outputs. Hybrid approaches that employ model predictive control (MPC) to address this problem can be unstable, as poor trajectory initializations from the diffusion model prevent the MPC from converging to a safe and feasible solution. To overcome these challenges, we propose D-SafeMPC, which enhances the interaction between diffusion and control. Our method guides the reverse diffusion process with…

---

### [Measure the Sim-to-Real Gap: Designing an Affordable Real-World Benchmark Platform for Reinforcement Learning in AIoT Systems](https://arxiv.org/abs/2607.10309v1)

- **arXiv**: `2607.10309v1`  |  **提交日期**: 2026-07-11
- **作者**: Rongping Zhou, Omid Tavallaie, Shuaijun Chen, Albert Y. Zomaya

Reinforcement learning (RL) is commonly employed to enhance the performance of autonomous systems, including the Autonomous Internet of Things (AIoT). However, the trial-and-error nature of RL, when conducted in real-world environments, is costly and hazardous in some scenarios. Consequently, the majority of RL research is conducted in simulation. This reliance introduces challenges related to the Sim-to-Real transferability. Evaluating the Sim-to-Real algorithmic robustness and the Sim-to-Real gap is a critical prerequisite for research aimed at improving RL performance in the real world.…

---

### [PIER-Flow: Physics-Informed Efficient Rectified Flow for Real-Time Mobile Robot Navigation](https://arxiv.org/abs/2607.10288v1)

- **arXiv**: `2607.10288v1`  |  **提交日期**: 2026-07-11
- **作者**: Shibo Li, Zhongcheng Wang, Jiahe Cao, Jianhua Yang, Ke Wu

Autonomous navigation in dense and highly dynamic environments requires both physically feasible control and low-latency replanning. Optimization-based methods such as Model Predictive Control (MPC) explicitly handle robot kinematics and safety constraints, but repeated nonlinear optimization can limit real-time responsiveness. Deterministic behavior-cloning policies enable efficient inference but may fail to represent multimodal avoidance behaviors, whereas diffusion policies capture multimodality at the cost of time-consuming iterative denoising. We propose PIER-Flow (Physics-Informed…

---

## 📅 2026-07-13

### [CORAL-AUV: CFD Oriented Reinforcement Learning for Autonomous Underwater Vehicles](https://arxiv.org/abs/2607.09557v1)

- **arXiv**: `2607.09557v1`  |  **提交日期**: 2026-07-10
- **作者**: Steven Roche, Milo Van Mooy, Nathan McGuire, Levi Cai, Jonathan P. How, Yogesh Girdhar

Fine grain control and positioning of autonomous underwater vehicles (AUVs) is critical for sampling, maintenance, and survey applications. Traditional control methods for AUVs are labor intensive and are not robust to changes in the vehicle configuration or environmental conditions. Reinforcement learning (RL) promises rapid controller development while handling a range of deployment parameters via domain randomization (DR). However, DR is still limited by the capacity of the underlying simulation to model real physics. In particular, drag physics are difficult to model and are a large…

---

### [Dec-MARVEL: Decentralized Multi-Agent Exploration without Communication under Budget Constraints](https://arxiv.org/abs/2607.09060v1)

- **arXiv**: `2607.09060v1`  |  **提交日期**: 2026-07-10
- **作者**: Janghyun Cho, Jimmy Chiun, Guillaume Sartoretti, Changjoo Nam

Multi-UAV exploration is often constrained by unreliable communication, limited field-of-view sensing (e.g., lightweight onboard camera), and finite travel budgets that require each robot to reserve enough budget to return to its base. We present Dec-MARVEL, a decentralized budget-aware exploration framework for communication-free teams with directional sensing. Rather than exchanging maps, goals, or messages, each robot coordinates through its incidental observations: any teammate trajectory within its field of view serves as a coordination signal. A graph-attention actor fuses local…

---

## 📅 2026-07-10

### [Time-to-Collision Based Dynamic Obstacle Avoidance Using Pretrained Vision Models for Robots in Unstructured Environments](https://arxiv.org/abs/2607.07885v1)

- **arXiv**: `2607.07885v1`  |  **提交日期**: 2026-07-08
- **作者**: Erik Jagnandan, Mulugeta Haile, Gregory Barber, Pratik Chaudhari

Dynamic obstacle avoidance in unstructured outdoor environments remains a critical challenge for autonomous mobile robots, particularly when large-scale robot-specific training data and simulation-based policies are impractical. We present a data-efficient, interpretable method for vision-based dynamic obstacle avoidance that operates entirely on real-world data, avoiding the sim-to-real transfer problem inherent in simulation-trained policies. Our approach leverages UniDepth, a large pretrained monocular depth estimation model, to produce dense depth maps from RGB video without requiring…

---

### [Unlocking Temporal Generalization in Hamiltonian Video Dynamics Models](https://arxiv.org/abs/2607.07763v1)

- **arXiv**: `2607.07763v1`  |  **提交日期**: 2026-07-08
- **作者**: Eli Laird, Corey Clark

World models are typically trained to predict discrete-time physical dynamics with a fixed step size baked into the model weights, preventing prediction at variable temporal resolutions. This matters for hierarchical planning, sim-to-real transfer, and scientific or game-engine applications that must query the same dynamics at multiple timescales. Hamiltonian Generative Networks (HGN) offer a principled path forward, grounding predictions in a continuous-time energy function that is, in principle, independent of the observation frame rate. In practice, however, their temporal generalization…

---

## 📅 2026-07-09

### [RoboSnap: One-Shot Real-to-Sim Scene Generation for Generalizable Robot Learning and Evaluation](https://arxiv.org/abs/2607.06699v1)

- **arXiv**: `2607.06699v1`  |  **提交日期**: 2026-07-07
- **作者**: Shujie Zhang, Jingkun Yi, Weipeng Zhong, Zirui Zhou, Yangkun Zhu, Hanqing Wang et al.

Recovering real-world scenes as interactive simulation environments can enable generalizable robot learning and reproducible policy evaluation. However, constructing scenes that are both physically stable and visually faithful remains slow and expensive. In this work, we present RoboSnap, a real-to-sim framework that turns a single RGB image into a simulation-ready scene. The key idea is a layered design that separates the physics-critical interaction area from the surrounding visual context: collision-aware foreground assets are refined for stable robot interaction, while a 3D Gaussian…

---

## 📅 2026-07-08

### [WristMimic: Full-Body Humanoid Control with Wrist-Guided Manipulation](https://arxiv.org/abs/2607.06438v1)

- **arXiv**: `2607.06438v1`  |  **提交日期**: 2026-07-07
- **作者**: Wongyun Yu, Youngwoon Kim, Minsu Cho

Retargeting human object interaction demonstrations to physics based simulation requires reproducing not only body motion but also the object motion and contacts that make manipulation succeed. However, position only hand trajectories do not specify the contact forces needed to manipulate objects, and directly tracking them can overconstrain contact rich finger behavior. We introduce WristMimic, a wrist guided whole body control framework that explicitly separates contact free body motion from contact rich hand manipulation. The contact free body and wrist are guided by kinematic pose…

---

### [Learning to Throw Objects Safely in Multi-Obstacle Environments](https://arxiv.org/abs/2607.06388v1)

- **arXiv**: `2607.06388v1`  |  **提交日期**: 2026-07-07
- **作者**: Mohammadreza Kasaei, Klemen Voncina, Hamidreza Kasaei

Robotic throwing enables fast and efficient object placement beyond the robot's immediate workspace, but reliable throwing in cluttered environments remains underexplored. Existing approaches, such as TossingBot, learn throwing strategies from visual input but assume obstacle-free settings. In this paper, we address the problem of throwing objects into a target basket while avoiding obstacles placed randomly in the scene. We introduce a potential field state representation that compactly encodes both basket attraction and obstacle repulsion on a fixed-size grid, enabling reinforcement…

---

### [GraspIT: A Dataset Bridging the Sim-to-Real gap and back for Validated Grasping SE(3) Pose Generation](https://arxiv.org/abs/2607.05869v1)

- **arXiv**: `2607.05869v1`  |  **提交日期**: 2026-07-07
- **作者**: Paul Koch. Adem Karakurt, André Sers

Robust robotic grasping of novel objects requires datasets that simultaneously provide photorealistic RGB-D observations, physically validated grasp quality annotations, and a principled bridge between simulation and the real world, which existing datasets lack to provide jointly. \textbf{GraspIT} addresses this gap: tabletop scenes in NVIDIA Isaac Sim are annotated via a four-stage physical slip-test on parallel Franka Panda instances, producing trajectory-reachability checks and continuous quality scores beyond force-closure.Of ${\sim}$2.3M candidates, 83% pass as \emph{good}…

---

### [Onnes: A Physics-Grounded Multi-Agent LLM Simulator for Cryogenic Fault Diagnosis in Quantum Computing Infrastructure](https://arxiv.org/abs/2607.05805v1)

- **arXiv**: `2607.05805v1`  |  **提交日期**: 2026-07-07
- **作者**: Praneeth Narisetty, Uday Kumar Reddy Kattamanchi, Shiva Nagendra Babu Kore

Dilution refrigerators are the enabling infrastructure of superconducting quantum computers, yet their fault diagnosis is still dominated by threshold alarms that report that something is wrong, not what. We present Onnes, a physics-grounded digital-twin simulator of a dilution refrigerator (a forward physics model with a learned real-fridge noise fingerprint) that drives a live multi-agent LLM operations layer, and use it for a controlled head-to-head between a zero-shot LLM agent panel and a supervised ML classifier on cryogenic fault diagnosis. The twin couples a real dilution-cooling…

---

### [Image2Sim: Scaling Embodied Navigation via Generative Neural Simulator](https://arxiv.org/abs/2607.05765v1)

- **arXiv**: `2607.05765v1`  |  **提交日期**: 2026-07-07
- **作者**: Zihan Wang, Seungjun Lee, Yinghao Xu, Gim Hee Lee

Embodied navigation aims to build agents that interpret multimodal goals, reason in 3D space, and reach target destinations reliably in the real world. However, progress remains constrained by the lack of scalable, high-fidelity, and physically grounded interactive environments. Although real-world scanned datasets offer visual realism, they are limited by scale. In contrast, synthetic simulators scale more easily but often exhibit large sim-to-real gaps. We introduce Image2Sim, a real-time neural simulation framework that constructs high-quality interactive environments from posed RGB-D…

---

### [Athena-WBC: Capability-Aligned Policy Experts for Long-Tail Humanoid Whole-Body Control](https://arxiv.org/abs/2607.04837v2)

- **arXiv**: `2607.04837v2`  |  **提交日期**: 2026-07-06
- **作者**: Yuan Jiang, Ningyuan Zhang, Xicun Yang, Yuzhi Jiang, Jie Chen

Large-scale humanoid motion-tracking controllers are commonly improved by reallocating training effort: difficult motions are sampled more often, isolated into smaller subsets, or assigned to specialized experts. We show that this view is incomplete. In strong whole-body-control baselines, a residual set of feasible training clips remains unsolved even under targeted training, especially for high-dynamic transitions and balance-critical motions. These failures arise not only from insufficient exposure, but from a mismatch between the motion demands and the effective capability induced by the…

---

### [RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies](https://arxiv.org/abs/2607.04434v2)

- **arXiv**: `2607.04434v2`  |  **提交日期**: 2026-07-05
- **作者**: Tianxing Chen, Yue Chen, Zixuan Li, Junyuan Tang, Kailun Su, Haoran Lu et al.

Generalist robot manipulation policies have advanced rapidly, yet existing benchmarks remain limited in systematically evaluating their capabilities. Many rely on simple, short-horizon, or skill-narrow tasks with limited capability coverage, and are often conducted only in simulation or only in the real world. Simulation enables scalable feedback but misses physical deployment challenges, while real-world evaluation is costly, time-consuming, and difficult to reproduce. We introduce RoboDojo, a unified sim-and-real benchmark for comprehensive evaluation of generalist robot manipulation…

---

## 📅 2026-07-07

### [Closing the Reality Gap: Zero-Shot Sim-to-Real Deployment for Dexterous Force-Based Grasping and Manipulation](https://arxiv.org/abs/2607.04940v1)

- **arXiv**: `2607.04940v1`  |  **提交日期**: 2026-07-06
- **作者**: Zhe Zhao, Zhibin Li, Yilin Ou, Mengshi Qi

Human-like dexterous hands with multiple fingers offer human-level manipulation capabilities but remain difficult to train the control policies that can deploy on real hardware due to contact-rich physics and imperfect actuation. We present a sim-to-real reinforcement learning method that leverages dense tactile feedback combined with joint torque sensing to explicitly regulate physical interactions. To enable effective sim-to-real transfer, we introduce (i) a computationally fast tactile simulation that computes distances between dense virtual tactile units and the object via parallel…

---

### [Athena-WBC: Capability-Aligned Policy Experts for Long-Tail Humanoid Whole-Body Control](https://arxiv.org/abs/2607.04837v1)

- **arXiv**: `2607.04837v1`  |  **提交日期**: 2026-07-06
- **作者**: Yuan Jiang, Ningyuan Zhang, Xicun Yang, Shidi Li, Yuzhi Jiang, Zhiyi Rong et al.

Large-scale humanoid motion-tracking controllers are commonly improved by reallocating training effort: difficult motions are sampled more often, isolated into smaller subsets, or assigned to specialized experts. We show that this view is incomplete. In strong whole-body-control baselines, a residual set of feasible training clips remains unsolved even under targeted training, especially for high-dynamic transitions and balance-critical motions. These failures arise not only from insufficient exposure, but from a mismatch between the motion demands and the effective capability induced by the…

---

### [SILO: Simulation-in-the-Loop Sim-to-Real Transfer for Multi-Stage Cable Routing](https://arxiv.org/abs/2607.04616v1)

- **arXiv**: `2607.04616v1`  |  **提交日期**: 2026-07-06
- **作者**: Stone Tao, Jie Xu, Hesam Rabeti, Yashraj Narang, Yijie Guo, Iretiayo Akinola

Linear-deformable manipulation remains challenging due to the complex deformations of objects such as cables and ropes. Prior data-driven approaches, particularly imitation learning, have shown some promise in narrowly defined settings but typically require thousands of demonstrations for specific tasks and cable types, limiting scalability and generalization. We introduce a sim-to-real reinforcement learning (RL) framework for multi-stage cable routing that leverages GPU-parallelized simulation to approximate linear deformable behaviors. Training across thousands of parallel simulations…

---

### [Mask2Real-WM: Segmentation Masks as a Sim-to-Real Bridge for Controllable Dexterous World Models](https://arxiv.org/abs/2607.04546v1)

- **arXiv**: `2607.04546v1`  |  **提交日期**: 2026-07-05
- **作者**: Riccardo O. Feingold, Davide Liconti, Chenyu Yang, Robert K. Katzschmann

Action-conditioned world models allow robots to predict the future consequences of candidate actions without additional physical interaction, supporting policy evaluation, planning, and data augmentation. We present Mask2Real-WM, a two-stage action-conditioned world model for dexterous manipulation that decouples pixel prediction into a dynamics model and a rendering model. The dynamics model predicts future segmentation masks from past masks and 23-DoF action sequences. The rendering model maps the predicted masks to photorealistic RGB using a ControlNet-augmented Stable Video Diffusion…

---

### [CCFM: Collision-Constrained Flow Matching for Safety-Critical Scenario Generation](https://arxiv.org/abs/2607.04451v1)

- **arXiv**: `2607.04451v1`  |  **提交日期**: 2026-07-05
- **作者**: Ke Li, Kaidi Liang, Yuxin Ding, Debojyoti Biswas, Xianbiao Hu, Ruwen Qin

Evaluation of autonomous vehicle (AV) planners in safety-critical closed-loop simulation is essential for real-world deployment. However, generating controllable safety-critical scenarios remains challenging. Existing approaches use soft guidance that provides only probabilistic preferences and cannot guarantee the satisfaction of geometric and severity constraints associated with specific collision types. We introduce Collision-Constrained Flow Matching (CCFM), a novel framework that guarantees precise collision control through hard physical constraints. CCFM consists of three key…

---

### [RoboDojo: A Unified Sim-and-Real Benchmark for Comprehensive Evaluation of Generalist Robot Manipulation Policies](https://arxiv.org/abs/2607.04434v1)

- **arXiv**: `2607.04434v1`  |  **提交日期**: 2026-07-05
- **作者**: Tianxing Chen, Yue Chen, Zixuan Li, Junyuan Tang, Kailun Su, Weijie Wan et al.

Generalist robot manipulation policies have advanced rapidly, yet existing benchmarks remain limited in systematically evaluating their capabilities. Many rely on simple, short-horizon, or skill-narrow tasks with limited capability coverage, and are often conducted only in simulation or only in the real world. Simulation enables scalable feedback but misses physical deployment challenges, while real-world evaluation is costly, time-consuming, and difficult to reproduce. We introduce RoboDojo, a unified sim-and-real benchmark for comprehensive evaluation of generalist robot manipulation…

---

## 📅 2026-07-03

### [Actuator Reality Shaping for Zero-Shot Sim-to-Real Robot Learning](https://arxiv.org/abs/2607.02205v1)

- **arXiv**: `2607.02205v1`  |  **提交日期**: 2026-07-02
- **作者**: Satoshi Yamamori, Koji Ishihara, Kentaro Minamikawa, Kiyoharu Ohomori, Taiyo Yazaki, Norikazu Sugimoto et al.

Sim-to-real transfer in robot learning is often limited by discrepancies between the ideal actuator dynamics assumed during policy training and the nonlinear, hardware-dependent behavior of physical motors. While conventional approaches attempt to bridge this gap by increasing simulator fidelity through system identification, domain randomization, or learned actuator models, we introduce an alternative paradigm: actuator reality shaping. Instead of modifying the simulator to match the real world, our method shapes the closed-loop behavior of physical actuators to match the idealized…

---

### [Multi-Rate Nonlinear Model Predictive Control for Wall-Supported Bipedal Locomotion of Quadrupedal Robots](https://arxiv.org/abs/2607.01574v1)

- **arXiv**: `2607.01574v1`  |  **提交日期**: 2026-07-02
- **作者**: Taizoon Chunawala, Jeeseop Kim, Kaveh Akbari Hamed

This paper presents a novel layered planning and control framework based on multi-rate nonlinear model predictive control (MR-NMPC) that enables quadrupedal robots to perform hybrid bipedal locomotion with wall-assisted support in constrained environments. Real-time trajectory optimization for this locomotion presents significant challenges, as the controller must simultaneously plan for both the contact points and the continuous trajectories of the robot's center of mass (CoM) and orientation within the robot's nonlinear dynamics while accounting for unilateral contact constraints,…

---

## 📅 2026-07-02

### [A Data-Enabled Primal-Dual Approach for Policy Learning with SDP Formulations](https://arxiv.org/abs/2607.00644v1)

- **arXiv**: `2607.00644v1`  |  **提交日期**: 2026-07-01
- **作者**: Han Wang, Feiran Zhao, Florian Dorfler

This paper develops a data-enabled primal-dual framework for learning optimal control policies for unknown linear discrete-time systems from online data. The proposed approach views the data-dependent control synthesis problem as a time-varying semidefinite program (SDP) whose coefficients are recursively updated from online closed-loop measurements. Instead of repeatedly solving a full SDP as new data arrive, the policy is updated online through lightweight primal-dual iterations, each consisting of a linear equation solve and a projection onto the positive semidefinite cone. The framework…

---

### [[Preprint] Dynamic Modeling, Gait Synthesis, and Control of a Novel Subsurface Bore Propagator](https://arxiv.org/abs/2607.00569v1)

- **arXiv**: `2607.00569v1`  |  **提交日期**: 2026-07-01
- **作者**: Lina van Brügge, Shruti Kotpalliwar, Anton Koval, Akshit Saradagi, George Nikolakopoulos

In this article, we present dynamic modeling, gait synthesis, and feedback control design for a modular novel subsurface robot, designed for human-free subsurface exploration and excavation. The subsurface propagator design is based on two major aspects: 1) anchor and propel movement like an earthworm and 2) excavation similar to tunnel boring machines. This design is decoupled into five separate modules: one drill head to excavate and create cavity for propagation, two modules to anchor the robot, and two modules to enable propagation of the body. In order to design a controller for each of…

---

### [ASPIRE: Agentic /Skills Discovery for Robotics](https://arxiv.org/abs/2607.00272v1)

- **arXiv**: `2607.00272v1`  |  **提交日期**: 2026-06-30
- **作者**: Runyu Lu, Yubo Wu, Ethan Kou, Letian Fu, Wenli Xiao, Ajay Mandlekar et al.

Traditional robot programming is challenging: it requires orchestrating multimodal perception, managing physical contact dynamics, and handling diverse configurations and execution failures. We introduce ASPIRE (Agentic Skill Programming through Iterative Robot Exploration), a continual learning system that autonomously writes and refines robot control programs in a code-as-policy paradigm while compounding experience into a reusable skill library. ASPIRE discovers skills that persist across tasks, simulation and real-world settings, and embodiments. It operates in an open-ended loop with…

---

### [3D Point World Models: Point Completion Enables More Accurate Dynamics Learning](https://arxiv.org/abs/2607.00148v1)

- **arXiv**: `2607.00148v1`  |  **提交日期**: 2026-06-30
- **作者**: Skand Peri, Hung Nguyen, Chanho Kim, Li Fuxin, Stefan Lee

Learning predictive models of the world enables robotic control through planning, potentially allowing robots to improvise solutions on new tasks. However, large video-based dynamics models lack explicit 3D spatial structure and suffer from geometrically inconsistent long-term rollouts with compounding errors. Emerging 3D dynamics models based on partial point clouds improve geometric consistency but remain sensitive to occlusions and accumulated prediction drift. To address these challenges, we present 3D Point World Models (3DPWM) - a task-agnostic world model that operates entirely in 3D…

---

### [A Synthetic-Driven Vision System for Assembly Step Recognition](https://arxiv.org/abs/2607.00129v1)

- **arXiv**: `2607.00129v1`  |  **提交日期**: 2026-06-30
- **作者**: Hui Zhang, Xuanang Lei, Rui Wang, Julian Ferchow, Mirko Meboldt

Quality control in industrial assembly is essential, and real-time monitoring of the assembly process is crucial for preventing costly defects and ensuring production reliability. Vision-based automated inspection offers a powerful solution for such real-time monitoring. However, due to the specialized industrial components and processes, training these models typically relies on task-specific real-world data, which is costly and labor-intensive to collect and annotate. In this paper, we propose a system that automatically generates realistic assembly sequences and further trains real-time…

---

### [Warp RL: Reshaping Base Policy Distributions for Dynamics Adaptation](https://arxiv.org/abs/2606.31043v2)

- **arXiv**: `2606.31043v2`  |  **提交日期**: 2026-06-30
- **作者**: Ethan Hirschowitz, Fabio Ramos

Residual reinforcement learning adapts a pretrained robot policy by learning an additive correction to its actions. While effective when adaptation amounts to shifting the base policy's action distribution, additive corrections cannot change the distribution's shape, scale, or state-dependent geometry -- limitations we formalize as wrong variance, miscalibrated confidence, and non-uniform correction. We show that these matter under dynamics shift: when the base distribution is geometrically mismatched to the shifted system, residual correction can underperform even the unadapted policy. We…

---

## 📅 2026-07-01

### [OopsieVerse: A Safety Benchmark with Damage-Aware Simulation for Robot Manipulation](https://arxiv.org/abs/2606.31993v1)

- **arXiv**: `2606.31993v1`  |  **提交日期**: 2026-06-30
- **作者**: Arnav Balaji, Arpit Bahety, Sriniket Ambatipudi, Daniel Lam, Junhong Xu, Roberto Martín-Martín

While robotic manipulation capabilities have advanced rapidly, physical safety remains a major barrier to deploying household robots: task success is insufficient if the robot damages itself or its surroundings. Simulation offers a harm-free alternative to costly and dangerous real-world training and evaluation, yet existing simulators lack general mechanisms to detect, quantify, and represent damage. To address this gap, we introduce OOPSIEVERSE, a unified simulation framework and benchmark for damage-aware household manipulation. OOPSIEVERSE provides damage as an explicit,…

---

### [SENSE-VAD: Sentient and Semantic Video Anomaly Detection for Autonomous Driving](https://arxiv.org/abs/2606.31875v1)

- **arXiv**: `2606.31875v1`  |  **提交日期**: 2026-06-30
- **作者**: Nghia T. Nguyen, Lokman Bekit, Yasin Yilmaz

Autonomous vehicles (AVs) must navigate not only motion-based hazards but also socially complex situations whose danger is constituted by inter-agent relationships rather than movement statistics alone. A child running away from a guardian, a person being carried by another, or a pursuer chasing a pedestrian across a sidewalk are all anomalous in social context, yet none produces an obvious motion signal that current anomaly detectors are equipped to flag. We introduce SENSE-VAD, the first synthetic video anomaly detection benchmark for autonomous driving explicitly designed around socially…

---

### [Efficient Sim-to-Real Transfer of World-Action Models from Synthetic Priors](https://arxiv.org/abs/2606.31101v1)

- **arXiv**: `2606.31101v1`  |  **提交日期**: 2026-06-30
- **作者**: Zixing Wang, Kausik Sivakumar, Jinghuan Shang, Yafei Hu, Zhaoming Xie, Ran Gong et al.

Bridging the sim-to-real gap is a core challenge in deploying learned manipulation policies. Sim-to-real learning is attractive because it can replace expensive real robot demonstrations with scalable synthetic data, yet world-action models have not previously been shown to transfer from simulation to real robotic manipulation. We study whether a world-action model can be trained from synthetic priors and deployed zero-shot in the real world. To this end, we build upon Cosmos Policy, a video diffusion model adapted for visuomotor control. We construct simulation environments with extensive…

---

### [Warp RL: Reshaping Base Policy Distributions for Dynamics Adaptation](https://arxiv.org/abs/2606.31043v1)

- **arXiv**: `2606.31043v1`  |  **提交日期**: 2026-06-30
- **作者**: Ethan Hirschowitz, Fabio Ramos

Residual reinforcement learning adapts a pretrained robot policy by learning an additive correction to its actions. While effective when adaptation amounts to shifting the base policy's action distribution, additive corrections cannot change the distribution's shape, scale, or state-dependent geometry -- limitations we formalize as wrong variance, miscalibrated confidence, and non-uniform correction. We show that these matter under dynamics shift: when the base distribution is geometrically mismatched to the shifted system, residual correction can underperform even the unadapted policy. We…

---

## 📅 2026-06-30

### [VLK: Learning Humanoid Loco-Manipulation from Synthetic Interactions in Reconstructed Scenes](https://arxiv.org/abs/2606.30645v1)

- **arXiv**: `2606.30645v1`  |  **提交日期**: 2026-06-29
- **作者**: Yen-Jen Wang, Jiaman Li, Sirui Chen, Takara E. Truong, Pei Xu, Pieter Abbeel et al.

Perception-based humanoid loco-manipulation requires connecting egocentric observations and task instructions to whole-body motion. Learning this mapping requires synchronized egocentric images, language commands, and robot-compatible kinematic trajectories, yet no existing data source provides this complete tuple at scale. We address this bottleneck by generating vision-language-kinematics (VLK) supervision synthetically in reconstructed scenes. Our pipeline leverages 3D Gaussian Splatting to reconstruct metric-scale indoor environments, synthesizes navigation and object-interaction…

---

### [OmniCoT: A Benchmark for Global and Multi-Step Panoramic Reasoning](https://arxiv.org/abs/2606.30378v1)

- **arXiv**: `2606.30378v1`  |  **提交日期**: 2026-06-29
- **作者**: Haocong He, Chenfei Liao, Zichen Wen, Zihao Dongfang, Xu Zheng, Bin Ren et al.

Multimodal Large Language Models (MLLMs) have demonstrated promising spatial reasoning capabilities, while these abilities remain underexplored in the emerging visual modality of panoramic imagery. The full 360°$\times$180° field of view of panoramas essentially supports complex global multi-step reasoning, which is also the fundamental advantage of panoramas in applications such as embodied intelligence. However, existing panoramic benchmarks largely focus on simplistic queries that rely on local cues or single-/few-step reasoning, thereby ignoring the fundamental advantage of panoramas and…

---

### [ReactiveBFM: Reactive Closed-Loop Motion Planning Towards Universal Humanoid Whole-Body Control](https://arxiv.org/abs/2606.30362v1)

- **arXiv**: `2606.30362v1`  |  **提交日期**: 2026-06-29
- **作者**: Xiao Chen, Weishuai Zeng, Xiaojie Niu, Zirui Wang, Jianan Li, Huayi Wang et al.

While current Behavior Foundation Models (BFMs) provide robust control priors for humanoids, they only execute pre-defined reference motions. As a result, they are vulnerable to environmental shifts and incapable of reactive whole-body coordination. Naively cascading them with generative motion planners fails to achieve true reactivity, as inevitable tracking discrepancies induce fatal cumulative exposure bias. To bridge this gap, we propose ReactiveBFM, a real-time closed-loop planning-control framework. At its core, we effectively mitigate exposure bias via a scheduled prefix sampling…

---

### [ConCent: Contact-Centric Real-to-Sim-to-Real Learning from One Demonstration](https://arxiv.org/abs/2606.30268v1)

- **arXiv**: `2606.30268v1`  |  **提交日期**: 2026-06-29
- **作者**: Heecheol Kim, Namiko Saito, Katsushi Ikeuchi, Yasuyuki Matsushita

Sim-to-real policy transfer -- deploying policies trained in simulation in the real world -- is a promising paradigm for scaling robot manipulation without large-scale real-world data. However, transferring simulation-trained policies remains challenging due to discrepancies in contact dynamics -- particularly in contact-rich tasks where subtle differences can alter task outcomes entirely. Because interaction between the manipulated object and the environment is mediated through contact, task success depends on accurately reproducing task-relevant contacts. Accordingly, in manipulation,…

---

### [Domain Adaptation with Adaptive Imagination for Visual Reinforcement Learning under Limited Target Data](https://arxiv.org/abs/2606.30192v1)

- **arXiv**: `2606.30192v1`  |  **提交日期**: 2026-06-29
- **作者**: Hyunwoo Park, Sang-Hyun Lee

Sim-to-real transfer remains a major obstacle for reinforcement learning (RL), especially for vision-based control where image observations exacerbate the state-distribution shift between simulation and the real world. Domain adaptation (DA) is a promising remedy for this challenge. Prior sim-to-real DA works have demonstrated encouraging results, yet these approaches typically assume substantially more target data, which is not available in practice. Indeed, their performance degrades significantly when the target data budget is reduced. To address this challenge, we propose AIDA (Adaptive…

---

### [SA-VLA: State-aware tokenizer for improving Vision-Language-Action Models' performance](https://arxiv.org/abs/2606.30113v1)

- **arXiv**: `2606.30113v1`  |  **提交日期**: 2026-06-29
- **作者**: Tengyue Jiang, Chunpu Xu, Jiayue Kang, Yao Mu

Discrete action tokenization provides a compact interface for autoregressive VLA policies, but accurately recovering continuous robot actions from discrete codes remains challenging. Existing tokenizers typically map each discrete code to a fixed continuous action prototype, ignoring the robot's current proprioceptive state. This limitation is particularly pronounced in manipulation, where the same action token may require different continuous controls under different joint configurations, object poses, and contact conditions. We therefore propose SA-VLA, a state-aware action tokenizer that…

---

### [FalconTrack: Photorealistic Auto-Labeled Perception and Physics-Aware Vision-Based Aerial Tracking](https://arxiv.org/abs/2606.29783v1)

- **arXiv**: `2606.29783v1`  |  **提交日期**: 2026-06-29
- **作者**: Yan Miao, Karteek Gandiboyina, Noah Giles, Hideki Okamoto, Bardh Hoxha, Georgios Fainekos et al.

Vision-based aerial tracking is critical in GPS-denied environments. Reliable perception for tracking depends on large-scale labeled data, yet most photorealistic datasets rely on heavy manual annotation and are time-consuming to produce. We present FalconTrack, a unified perception-and-tracking framework that (i) leverages a photorealistic editable simulator for automated label generation and (ii) combines multi-head perception with physics-aware tracking for zero-shot sim-to-real transfer. FalconTrack provides an automated labeling pipeline in a Gaussian Splatting simulator that isolates…

---

### [CORE Planner: Contextual-memory Oriented Reinforcement-learning in Unknown Environments for Robot Navigation](https://arxiv.org/abs/2606.29222v1)

- **arXiv**: `2606.29222v1`  |  **提交日期**: 2026-06-28
- **作者**: Jintao Kong, Zhihao Zhang, Weihuang Chen, Liming Chen, Zhongyu Guo, Shuaiyu Liu et al.

Autonomous navigation in unknown environments requires a robot to efficiently reach a predefined goal while exploring without prior maps. Although progress has been made in this area, most existing works still rely on traditional planning methods with hand-crafted rules, while learning-based methods often suffer from limited environmental memory and challenges in simulation-to-real (sim-to-real) transfer. To overcome these limitations, we propose a Contextual-memory Oriented Reinforcement-learning (CORE) planner for robot navigation in unknown environments. The proposed CORE planner…

---

### [Physics Models for Sim-to-Real Transfer in Professional-Level Robot Table Tennis](https://arxiv.org/abs/2606.28805v1)

- **arXiv**: `2606.28805v1`  |  **提交日期**: 2026-06-27
- **作者**: Christian Conti, Bilan Yang, Alexander Sigrist, Lorenzo Miele, Yamen Saraiji, Peter Dürr et al.

At competitive speeds and spins, a table tennis ball follows complex, counterintuitive trajectories that a robot must track and precisely counter within fractions of a second. Training a reinforcement learning policy capable of these skills is prohibitively expensive and dangerous in the real world, making high-fidelity simulation essential. Transferability of such policies, however, critically depends on how faithfully the simulation captures real-world dynamics--a requirement made even more stringent by the adversarial nature of the game, where any regime in which a model fails to…

---

## 📅 2026-06-27

### [VibeAct: Vibration to Actions for Contact-Rich Reactive Robot Dexterity](https://arxiv.org/abs/2606.27344v1)

- **arXiv**: `2606.27344v1`  |  **提交日期**: 2026-06-25
- **作者**: Yuemin Mao, Uksang Yoo, Jean Oh, Jonathan Francis, Jeffrey Ichnowski

Dexterous manipulation depends on contact events that are fast, local, and often visually occluded. Piezoelectric microphones offer a compact and high-bandwidth way to sense these interactions, but the resulting vibro-acoustic signals are difficult to simulate faithfully enough for end-to-end sim-to-real policy learning on dexterous robot hands. We propose VibeAct, a framework that bridges real vibrotactile sensing and simulation-based reinforcement learning through a shared physical representation of contact and slip. In the real world, we embed piezoelectric microphones into a dexterous…

---

### [Learning to Fold: prizewinning solution at LeHome Challenge 2026 (1st place online, 2nd offline)](https://arxiv.org/abs/2606.27163v1)

- **arXiv**: `2606.27163v1`  |  **提交日期**: 2026-06-25
- **作者**: Ilia Larchenko

I describe my solution to the LeHome Challenge 2026, an ICRA 2026 competition on bimanual garment folding. The system placed 1st of 62 teams in the online (simulation) round and 2nd in the real-world final. It improves a vision-language-action (VLA) policy with a reinforcement-learning loop. The policy is its own value function: the same network that predicts actions also predicts success, progress, and a few task-relevant future quantities, and those predictions drive advantage estimation, live failure detection, and candidate selection. The work mostly recombines existing RL ideas with…

---

### [RobOralScan: Learning Active Intraoral Scanning for Robotic Dental Reconstruction](https://arxiv.org/abs/2606.26955v1)

- **arXiv**: `2606.26955v1`  |  **提交日期**: 2026-06-25
- **作者**: Jinhyung Lee, Haeun Yun, Siwon Kim, Gihyun Baek, Sungho Moon, Sehyun Hwang et al.

Intraoral scanning is widely used for digital optical impressions in prosthodontic, implant, and orthodontic treatment, but full-arch and long-span scanning remain labor-intensive tasks with limited automation. In the confined oral cavity, operators must continuously adjust scanner motion while accumulating narrow field-of-view observations, making reconstruction quality sensitive to missing tooth surfaces and operator workload. We propose RobOralScan, which, to the best of our knowledge, is the first reinforcement learning (RL)-based pipeline for robotic automatic intraoral scanning.…

---

### [IDEA: Insensitive to Dynamics Mismatch via Effect Alignment for Sim-to-Real Transfer in Multi-Agent Control](https://arxiv.org/abs/2606.26575v1)

- **arXiv**: `2606.26575v1`  |  **提交日期**: 2026-06-25
- **作者**: Chenlong Liu, Zhuohui Zhang, Xinyan Chen, Zhipeng Wang, Bin Cheng, Bin He

Complex multi-agent control tasks remain challenging for traditional rule-based and model-based approaches, motivating the adoption of learning-based methods. However, learning-based methods often struggle with sim-to-real transfer because they rely on accurate dynamics modeling or system identification and learn policies in low-level control spaces that are highly sensitive to dynamics mismatch, making them costly and fragile in complex environments. To address this issue, we propose a sim-to-real method for multi-agent control, which is insensitive to dynamics mismatch via effect alignment.…

---

### [Play2Perfect: What Matters in Dexterous Play Pretraining for Precise Assembly?](https://arxiv.org/abs/2606.26428v1)

- **arXiv**: `2606.26428v1`  |  **提交日期**: 2026-06-24
- **作者**: Tyler Ga Wei Lum, Kushal Kedia, C. Karen Liu, Jeannette Bohg

Multi-fingered robots promise the speed and dexterity of human hands, yet challenging problems such as precise assembly have remained out of reach. These tasks are contact-rich, making data collection for imitation learning difficult, and sparse-reward, making direct exploration with reinforcement learning (RL) intractable. Consequently, prior work has made progress by structuring the problem with specialized grippers, tool attachments, and environment fixtures. In this work, we argue that before a robot can perfect precise assembly, it must first learn to play. We further ask the question:…

---

### [Cross-View Variance Correlation in Path-Traced Stereo:A Hidden Shortcut in Synthetic Training Data](https://arxiv.org/abs/2606.25483v1)

- **arXiv**: `2606.25483v1`  |  **提交日期**: 2026-06-24
- **作者**: Po-Ting Lin

Path-traced synthetic stereo data underlie a large fraction of modern disparity-estimation training pipelines. We report a previously unrecognised property of such data: while the Monte Carlo (MC) noise streams of the two cameras are statistically independent, the underlying \emph{variance fields} -- deterministic per-pixel functions of the rendering integrand -- are highly correlated once aligned by the ground-truth disparity warp. Across 20 scenes rendered with Mitsuba~3, the warped Pearson correlation reaches $ρ{=}0.754{\pm}0.016$ across 20 scenes at $\mathrm{SPP}{=}512$, and on a…

---

### [DynaMOMA: Instantaneous Prediction of Grasp Poses for Mobile Manipulation of Dynamic Objects](https://arxiv.org/abs/2606.25295v1)

- **arXiv**: `2606.25295v1`  |  **提交日期**: 2026-06-24
- **作者**: Zhinan Yu, Junyan Xu, Jiazhao Zhang, Zheng Qin, Yijie Tang, Yuhang Huang et al.

Mobile manipulation is a fundamental robotics task and has advanced rapidly in recent years, enabling robots to navigate, reach, and interact with objects in complex environments. However, mobile manipulation of dynamic objects remains highly challenging, as robots must coordinate the mobile base and arm while adapting to continuously evolving target poses. A key challenge lies in predicting temporally consistent short-horizon grasp trajectories from dynamic observations. In this work, we propose \ours{}, a dynamic mobile manipulation framework that couples instantaneous grasp trajectory…

---

