# VLA 视觉-语言-动作 (Vision-Language-Action)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-10-08

### [Rephrase Before You Act: Characterizing and Mitigating Language Sensitivity in Vision-Language-Action Models](https://arxiv.org/abs/2610.10526v1)

- **arXiv**: `2610.10526v1`  |  **提交日期**: 2026-10-07
- **作者**: Mikey Watts, Yuchen Cui

Vision-language-action models (VLAs) are strikingly sensitive to instruction phrasing and do not inherit the language robustness of the vision-language models they are built on. A one-word edit can move success by tens of points: $π_{0.5}$ turns on a LIBERO stove 100% of the time for "switch on the stove" and 2% for "switch on the hot plate", and a $π_0$ checkpoint finetuned with rephrase augmentation still shows swings of up to 61 points. We characterize this sensitivity with statistically tested single-edit swings and an oracle phrase search, which shows that phrasing alone nearly closes…

---

### [Q-Learning with Scalar Adjoint Matching](https://arxiv.org/abs/2610.10437v1)

- **arXiv**: `2610.10437v1`  |  **提交日期**: 2026-10-07
- **作者**: Yonghoon Dong, Minsung Yoon, Jaehyuk Kim, Jungwoo Park, Changyeon Kim, Jinwoo Shin

Flow policies capture rich and diverse action distributions, and fine-tuning them with off-policy RL to improve beyond the demonstrations has drawn growing interest. However, fine-tuning a flow policy against a learned value function is not trivial, because the policy generates its action over many flow steps. Adjoint matching offers a principled way to update the flow model itself by propagating value information from the final action back to each flow step, but it requires a vector--Jacobian product through the policy at every step, a cost that grows with the number of flow steps and the…

---

### [Explicit Geometric Chain-of-Thought for Vision-Language-Action in Autonomous Driving](https://arxiv.org/abs/2610.10390v1)

- **arXiv**: `2610.10390v1`  |  **提交日期**: 2026-10-07
- **作者**: Xingtai Gui, Yucheng Zhou, Dongqian Guo, Jiahao Gong, Feiyang Tan, Jianbing Shen

Vision-language-action~(VLA) models have emerged as a promising paradigm for autonomous driving. However, existing VLA models still suffer from a fundamental mismatch: driving actions require precise 3D geometric cues, while visual-language understanding and reasoning are largely conducted in a 2D semantic space. In this paper, we propose GeoCoTDrive, an explicit geometric chain-of-thought framework that grounds geometry in a planning-oriented manner. GeoCoTDrive follows a think with 2D first, drive with dedicated 3D priors paradigm. It first grounds 2D regions corresponding to…

---

### [Do Vision-Language-Action Models Understand Instructions? A Mechanistic Interpretability Study on Language Grounding](https://arxiv.org/abs/2610.10178v1)

- **arXiv**: `2610.10178v1`  |  **提交日期**: 2026-10-07
- **作者**: Theodor Wulff, Angelo Cangelosi

Vision-Language-Action models are designed to generalise across environments and task descriptions, raising the question of whether their action generation actually depends on the language instruction, or whether they largely rely on visual cues and superficial correlations. Robustness to variance in the visual and linguistic observation space is critical for real-world deployment, yet VLAs lack explicit grounding modules and instead rely on the intrinsic language grounding capabilities of their Vision-Language model backbones. For this reason, we conduct a controlled mechanistic…

---

### [Many Ways to Succeed: Diversity-Driven RL Fine-Tuning for VLA Generalization](https://arxiv.org/abs/2610.09943v1)

- **arXiv**: `2610.09943v1`  |  **提交日期**: 2026-10-07
- **作者**: Haoru Li, Jinmei Liu, Zhiyong Wang, Xiaoming Li, Zhenhong Sun, Daoyi Dong et al.

Reinforcement learning (RL) fine-tuning improves vision-language-action (VLA) policies through closed-loop experience, yet generalization beyond the fine-tuning distribution remains limited. Our analysis reveals a selective reshaping of exploration: RL contracts behavior globally, yet diversifies successful trajectories, elicits success with fewer rollouts, and covers more of the latent task-valid solution space than supervised fine-tuning. Broader successful-mode coverage may provide alternative strategies under distribution shifts. Inspired by this, we introduce DRIVE (Diversity-driven RL…

---

### [Juno: Taming Predictive Latents for Vision-Language-Action Models](https://arxiv.org/abs/2610.09940v1)

- **arXiv**: `2610.09940v1`  |  **提交日期**: 2026-10-07
- **作者**: Yuchen Zhu, Chenyi Xu, Yulin Zhang, Gang Xu, Wentao Zhu

Joint-embedding predictive architectures (JEPAs) predict masked or future observations in representation space, offering a natural source of predictive latents for vision-language-action (VLA) models. Yet making these latents useful across pretraining, policy learning, and deployment requires addressing three failures: mismatch with embodiment-specific control, interference with action learning, and teacher miscalibration under distribution shifts. We introduce Juno, a unified framework built around one action-conditioned JEPA that serves as a control-aligned representation backbone, a…

---

### [YUBI-STAG: Contact and Semantic-Rich Alignment for VLAs via Automated Video-Language Grounding](https://arxiv.org/abs/2610.09718v1)

- **arXiv**: `2610.09718v1`  |  **提交日期**: 2026-10-07
- **作者**: Masatoshi Tateno, Takehiko Ohkawa, Yueh-Hua Wu, Hanlong Li, Tatsuya Matsushima, Yoichi Sato et al.

Vision-Language-Action (VLA) models acquire broad manipulation capabilities via large-scale pretraining, yet eliciting them through language requires fine-grained alignment between instructions and physical interactions. Existing robot demonstrations typically provide only coarse task descriptions, omitting how actions are executed, including which gripper acts, which object is contacted, and how it is grasped and moved. We introduce YUBI-STAG, a framework for Spatio-Temporal Annotation and Grounding that automatically enriches manipulation demonstrations with interaction-rich semantics to…

---

### [RoboPace: Contact-Aware Time-Optimal Retiming for Action-Chunk Policies](https://arxiv.org/abs/2610.09696v1)

- **arXiv**: `2610.09696v1`  |  **提交日期**: 2026-10-07
- **作者**: Mimo Shirasaka, Takehiko Ohkawa, Takuya Okubo, Nicola Scianca, Tatsuya Matsushima, Kei Ota

Robot manipulation data collection has been shifting from teleoperation toward robot-free demonstrations, through interfaces such as the Universal Manipulation Interface (UMI) or directly from human hands. Vision-Language-Action (VLA) policies trained on such data inherit the demonstrator's timing. Yet human timing does not directly transfer to robots: compliant hands tolerate fast contact, whereas robots may overshoot due to actuator and tracking limitations; conversely, robots can move faster in free space. This motivates a unified approach that reconciles execution speed with contact…

---

### [Sparse Feature Policy Unlearning Mitigates State Hallucination in Vision-Language-Action Models](https://arxiv.org/abs/2610.09496v1)

- **arXiv**: `2610.09496v1`  |  **提交日期**: 2026-10-07
- **作者**: Jiho Lee, Jeongeun Park, Heayoun Choi, Taekyung Kim, Eunwoo Kim

Vision-Language-Action (VLA) models have shown strong generalization in robotic manipulation by leveraging rich representations from pretrained vision-language models. However, their deployment in real-world environments remains limited by recurring unreliable behaviors. In this work, we study state hallucination, a recurring failure pattern in which a VLA continues acting as if an unrealized robot-object state had been achieved. Our analyses find that state hallucination coincides with weakened attention to task-relevant visual regions, and a mechanistic interpretation via sparse…

---

### [TMT: Runtime Backdoor Detection for Vision-Language-Action Policies on Unseen Tasks](https://arxiv.org/abs/2610.09462v1)

- **arXiv**: `2610.09462v1`  |  **提交日期**: 2026-10-07
- **作者**: Zirun Zhou, Jingfeng Zhang, HaoChuan Xu, Xizhe Zhang, Elliott Wen, Jing Sun et al.

Backdoored vision-language-action (VLA) policies can preserve benign task performance while producing malicious actions when a trigger appears. Detecting such activation is difficult because malicious behavior can comprise individually plausible actions, while unfamiliar tasks introduce legitimate changes in observations and behavior. We introduce TMT, a runtime backdoor detector based on Token Manifold and latent Transition modeling. Trained on benign rollouts, its two branches assess input-token structure and prediction errors in adjacent-layer latent dynamics. A suspicious rollout…

---

### [TempoBridge: Language-Guided Tempo Control for Vision-Language-Action Policies](https://arxiv.org/abs/2610.09451v1)

- **arXiv**: `2610.09451v1`  |  **提交日期**: 2026-10-07
- **作者**: Yeonseo Lee, Hyosup Shin, Guebin Hwang, Sungho Jo

Vision-Language-Action (VLA) models are effective at understanding what task to perform, but provide limited control over how it should be executed, such as moving quickly or slowly. We introduce TempoBridge, a lightweight framework that uses frozen VLA representations to modulate actions according to tempo cues in the instruction at each task phase, without additional tempo-conditioned robot demonstrations or tempo-specific base-policy fine-tuning. TempoBridge extracts tempo cues from contextual VLM representations, aligns them with task progress through a causal phase router, and modulates…

---

### [Co-Evolving Robot Orchestrators and Policies through Deployment](https://arxiv.org/abs/2610.09228v1)

- **arXiv**: `2610.09228v1`  |  **提交日期**: 2026-10-06
- **作者**: Xilun Zhang, Maggie Wang, Erik Bauer, Hong-Xing Yu, Huang Huang, Jiajun Wu et al.

Vision-language-action (VLA) policies trained on large datasets are capable within their training domains, yet they still fail to generalize to the variety of situations a robot meets in real-world deployment. Agentic robot systems complement the policy with a vision-language model (VLM) orchestrator that learns when to call the policy, how to instruct it, and when to use scripted skills instead. However, because the harness is built around a frozen policy that has limited language steerability, the orchestrator can avoid the policy's failures but never overcome them. The policy becomes the…

---

### [Beyond Reconstruction: What Matters in Action Tokenization for Robot Policies?](https://arxiv.org/abs/2610.09170v1)

- **arXiv**: `2610.09170v1`  |  **提交日期**: 2026-10-06
- **作者**: Haoran Chen, Jingtian Ji, Samuel Wheeler, Kaylene Caswell Stocking, Matthew Walter

Autoregressive action-token policies such as vision-language-action models require action tokenizers to translate discrete token sequences into precise control actions in continuous space. Many action tokenizers learn the mapping between tokens and actions via a reconstruction objective. However, as we show through extensive analysis, sufficiently accurate action reconstruction is only one part of what makes a downstream robot policy successful. It is also critical that the policy is able to predict the right tokens for new observations, and that unseen policy token predictions still decode…

---

### [DIVA: Dual-Space Intent-Aware Visual Attenuation for Vision-Language-Action Policies](https://arxiv.org/abs/2610.09144v1)

- **arXiv**: `2610.09144v1`  |  **提交日期**: 2026-10-06
- **作者**: Kaixi Feng, Guoheng Sun, Ziyao Wang, Yexiao He, Zheyu Shen, Ang Li

Vision-language-action (VLA) policies typically feed dense visual patch tokens into a language-action backbone, preserving scene context but offering no explicit mechanism to regulate how strongly different visual tokens influence policy computation. We introduce DIVA, a Dual-Space Intent-Aware Visual Attenuation module with an anchor-then-attenuate design. DIVA combines high-level task intent with low-level visual evidence to estimate patch-wise relevance anchors, then applies them in two complementary spaces: it reweights projected visual tokens before backbone entry and persistently…

---

### [PAIR: Bridging Perception and Action in Vision-Language-Action Models](https://arxiv.org/abs/2610.09016v1)

- **arXiv**: `2610.09016v1`  |  **提交日期**: 2026-10-06
- **作者**: Kaixi Feng, Guoheng Sun, Ang li

Vision-language-action (VLA) models map visual observations and language instructions to continuous robot actions. This task requires a transition from representations that describe the scene and instruction to representations that support action generation. Many continuous-action VLAs leave this transition implicit and supervise it mainly through the final action-prediction loss. We introduce PAIR, a framework that learns a shared perception-action representation between these two spaces. During training, a Masked Action Autoencoder encodes expert action chunks into horizon-aligned Action…

---

### [CARE: Certifying Acceleration for Vision-Language-Action Inference](https://arxiv.org/abs/2610.08917v1)

- **arXiv**: `2610.08917v1`  |  **提交日期**: 2026-10-06
- **作者**: Rui Liu, Tong Zheng, Jindong Gu, Zhipeng Wang

While vision-language-action (VLA) models have advanced rapidly, running them at every control step remains expensive. Prior work accelerates VLA inference using techniques like action chunking and visual-token pruning, typically evaluating based on latency and average task success. However, acceleration may discard information and break tasks the original policy would solve, a risk hidden by average metrics. Measuring these failures is challenging because action deviations compound over closed-loop trajectories, meaning task failure is only observable across full episodes. We therefore…

---

## 📅 2026-10-07

### [Towards Efficient Robotic Manipulation Models with Self-Recursive Pruning](https://arxiv.org/abs/2610.08555v1)

- **arXiv**: `2610.08555v1`  |  **提交日期**: 2026-10-06
- **作者**: Zijia Chen, Yuenan Hou, Yu Li, Weijie Li, Li Liu

Network pruning can reduce parameter redundancy in robotic policies. However, generic pruning criteria are tailored for image recognition tasks and commonly designed to preserve weight magnitude, local reconstruction, or language-model likelihood rather than closed-loop action behavior. Directly applying these pruning algorithms to robotic tasks yields unsatisfactory performance. In this paper, we propose Loss-Conditioned Activation-Moment (LCAM) pruning, a training-free method for unstructured pruning of pre-trained robotic manipulation policies. Specifically, we first rank connections using…

---

### [WareFly-VLA: A Vision-Language-Action Framework for UAV Navigation and Human Tracking in Smart Warehouses](https://arxiv.org/abs/2610.08526v1)

- **arXiv**: `2610.08526v1`  |  **提交日期**: 2026-10-06
- **作者**: Thinh D. Le, Son T. Nguyen, Duong Q. Nguyen, Dung D. Le, Ngo Anh Vien, H. Nguyen-Xuan

Vision-Language-Action (VLA) models have achieved impressive results in robotic manipulation and ground-mobile navigation, yet language-conditioned control of unmanned aerial vehicles (UAVs) in smart warehouses remains largely unexplored, hindered by the lack of benchmarks that jointly provide continuous low-level flight actions, fine-grained natural-language target descriptions, and realistic industrial environments. This paper introduces WareFly-VLA, a photorealistic UAV VLA framework and dataset for language-guided human search, localization, and tracking in warehouse environments. It…

---

### [ActTune: Action-Aware Precision and GPU Operating-Point Adaptation for Energy-Efficient Vision-Language-Action Inference](https://arxiv.org/abs/2610.08444v1)

- **arXiv**: `2610.08444v1`  |  **提交日期**: 2026-10-06
- **作者**: Zou Qingyun, Bin Gao, Wenju Zhao, Weng-Fai Wong, Bingsheng He, Tulika Mitra

Vision-language-action (VLA) policies repeatedly invoke inference to control robots, making graphics processing unit (GPU) energy a recurring cost of task execution. Reducing energy per inference call, however, may not reduce energy per successful task if numerical errors increase failures or slower inference prolongs execution. We therefore target GPU energy per successful task while preserving task success and keeping the inference-latency increase within 10\%. Our approach builds on two observations: quantization sensitivity varies across action classes, model layers, and weights versus…

---

### [MIM-VLA: Learning Physical Interaction Representations from Gripper Motor Feedback](https://arxiv.org/abs/2610.08425v1)

- **arXiv**: `2610.08425v1`  |  **提交日期**: 2026-10-06
- **作者**: Jaeyoung Lee, Jiyeon Koo, Taehwa Kim, Yerin Cha, Andrew Jaeyong Choi

Vision-language-action (VLA) policies infer grasp actions primarily from visual observations and robot state, but do not explicitly represent the physical response observed after contact. We present MIM-VLA, a motor-feedback-based architecture that encodes recent gripper current, position, velocity, and signal validity as a 128-dimensional interaction token. A motor-only Motor Interaction Module (MIM) is pretrained with human-reviewed contact and interaction-phase labels and then conditions only the gripper-action pathway of SmolVLA; arm actions and the position-control interface remain…

---

### [VOMMI: Collecting and Leveraging Portable Demonstrations for Mobile Manipulation](https://arxiv.org/abs/2610.08220v1)

- **arXiv**: `2610.08220v1`  |  **提交日期**: 2026-10-06
- **作者**: Yutian Zhang, Xingrui Xiong, Siyuan Ma, Yang Li, Jiawen Wen, Jiaqi Zhai et al.

Portable mobile-manipulation demonstrations can help alleviate data scarcity for embodied intelligence, but obtaining reliable, low-cost, and robot-free motion supervision from RGB observations remains challenging. Existing approaches often rely on teleoperation or specialized devices equipped with additional sensing hardware, while directly using estimated visual odometry (VO) trajectories can introduce inconsistencies due to accumulated drift and imperfect motion supervision. We present the Visual-Odometry-Conditioned Mobile Manipulation Interface (VOMMI), a portable demonstration…

---

### [ViDAL: A Visual Dynamics-Grounded Action Latent Space for Vision-Language-Action Models](https://arxiv.org/abs/2610.08150v1)

- **arXiv**: `2610.08150v1`  |  **提交日期**: 2026-10-06
- **作者**: Yuan Xu, Yixiang Chen, Qisen Ma, Jiabing Yang, Peiyan Li, Kai Wang et al.

Vision-Language-Action (VLA) models have become a central paradigm for robot policy learning, which predict actions in three forms: raw action chunks, discrete action tokens, or continuous action latents. However, existing action representations primarily model action trajectories, with limited consideration of the visual dynamics induced by these actions. We introduce ViDAL, a Visual Dynamics-grounded Action Latent Space that anchors continuous action latents in the future visual dynamics of the scene. Specifically, ViDAL learns action latent space by training an Action Variational…

---

### [VLA-ACL: Action-Consistent Visual Token Pruning for Efficient Vision-Language-Action Models](https://arxiv.org/abs/2610.08133v1)

- **arXiv**: `2610.08133v1`  |  **提交日期**: 2026-10-06
- **作者**: Owen Du, Yang Yue, Jie Zhang, Jiaqi Pi, Chi Bene Chen, Gao Huang

Vision-Language-Action (VLA) models achieve strong robotic manipulation performance but incur high computational costs from processing long token sequences at every control step, limiting real-time deployment. Visual token pruning offers a direct solution, as visual patches dominate the input sequence and contain considerable redundancy. Existing approaches, however, either rely on indirect training-free heuristics, such as attention scores and motion thresholds, or require costly fine-tuning of the base VLA model. We introduce VLA-ACL (Action Consistency Learning), which learns a lightweight…

---

### [Adapting Vision-Language-Action Models to Unknown Visual Disruptions During Execution](https://arxiv.org/abs/2610.07946v1)

- **arXiv**: `2610.07946v1`  |  **提交日期**: 2026-10-06
- **作者**: Ahin Lee, Jinwoo Seo, Youngsoo Jang, Taesik Gong

Visual disruptions can arise while a robot is executing a task, leaving a vision-language-action (VLA) policy to respond without knowing the disruption type or timing. We introduce Self-supervised Adaptation from Leftover Trajectories (SALT), which uses the leftover trajectory, the unexecuted part of the previous action chunk, as self-supervision for test-time adaptation. Because consecutive chunks overlap in time, the leftover provides a temporally aligned target for the current prediction over the same future control interval. At the onset of a visual shift, the leftover can retain a plan…

---

### [StairVLA: Stage-Aware Hierarchical Action Generation for Vision-Language-Action Models](https://arxiv.org/abs/2610.07756v1)

- **arXiv**: `2610.07756v1`  |  **提交日期**: 2026-10-06
- **作者**: Shangyuan Yuan, Xinda Qi, Yujiang Pu, Wenliang Guo, Xiaobo Tan

Vision-language-action (VLA) models increasingly rely on diffusion- or flow-matching-based action heads to generate continuous robot actions. These action heads typically process the denoising trajectory in a largely uniform manner. However, we observe that the conditioning focus naturally shifts across denoising stages: early stages combine language instructions and visual observations to establish a coarse action trajectory, whereas later stages place greater emphasis on current visual observations for action alignment. Based on this insight, we introduce StairVLA, a stage-aware…

---

### [ESP: Energy-Score Policy for One-Step Multimodal Action Generation](https://arxiv.org/abs/2610.07696v1)

- **arXiv**: `2610.07696v1`  |  **提交日期**: 2026-10-06
- **作者**: Lilika Makabe, Heecheol Kim, Yasuyuki Matsushita

Generative action models based on diffusion and flow matching have been increasingly adopted in vision-language-action (VLA) policies for their ability to capture diverse behaviors, including multiple valid action sequences under the same observation and instruction. Their iterative sampling procedures, however, require repeated network evaluations to generate each action chunk, increasing inference latency in closed-loop control. We propose ESP (Energy-Score Policy), a teacher-free approach that maps policy context and noise directly to an action chunk in a single network evaluation. ESP…

---

### [Seeing the Invisible: Physics-Guided Visual Prompting for Temperature- and Radiation-Aware VLA Navigation](https://arxiv.org/abs/2610.07558v1)

- **arXiv**: `2610.07558v1`  |  **提交日期**: 2026-10-06
- **作者**: Hojoon Son, Fan Zhang

Vision-Language-Action (VLA) models have become a major paradigm for Vision-and-Language Navigation (VLN). However, in safety-critical facilities, invisible risks such as radiation or temperature spikes cannot be detected by an RGB camera, and handling each risk is expensive, requiring a new encoder, new data, and model retraining. We propose Physics-Guided Visual Prompting (PG-VP), a plug-and-play multimodal perception module that instead reuses what a frozen VLA model already does well: avoiding visible obstacles. Given a proximal radiation or thermal source, PG-VP performs a physics-guided…

---

### [Recursive Video In-Context Learning for Agentic Robot](https://arxiv.org/abs/2610.06843v1)

- **arXiv**: `2610.06843v1`  |  **提交日期**: 2026-10-05
- **作者**: Wenrui Bao, Xinxin Liu, Bingxin Xu, Yuzhang Shang

LLM agents that orchestrate frozen vision-language-action (VLA) policies improve across episodes through text memory, which records what the agent did but not how the task is done. A demonstration video shows it, but fits poorly into an agent's context. The full video slows every turn, fixed keyframes lose the contact detail that decides whether a grasp holds, and what the agent needs shifts from the task's structure while planning to the frames around each contact. We introduce Recursive Video In-Context Learning (RV-ICL), a training-free method that turns a demonstration into a hierarchy…

---

### [PlaySuite: A Large-Scale Benchmark for Interactive Visual Intelligence](https://arxiv.org/abs/2610.07127v1)

- **arXiv**: `2610.07127v1`  |  **提交日期**: 2026-10-05
- **作者**: Dheeraj Varghese, Anna Vettoruzzo, Walter Simoncini, Michelle Lorena Acevedo Callejas, Mohammad Mahdi Derakhshani, Kristof Meding et al.

Recent advances in multimodal foundation models yield strong performance on static perception and reasoning benchmarks, yet such evaluations largely overlook a central aspect of intelligence: acting competently in dynamic environments over extended time horizons. We introduce PlaySuite, a large-scale benchmark for evaluating interactive visual intelligence across more than 5K open-source video games curated from PyWeek and itch.io. Spanning diverse genres and engines, including Pygame, HTML5, Godot, and Unity, these independent games are largely out-of-distribution for current models,…

---

### [SimForcing: Distilling Simulation Motion Priors into Real-Domain Robot World Models](https://arxiv.org/abs/2610.06598v1)

- **arXiv**: `2610.06598v1`  |  **提交日期**: 2026-10-05
- **作者**: Xiaodong Wang, Tianle Li, Chuanxin Song, Junliang Xie, Zhanmi Zhong, Suiying Wu et al.

Action-conditioned robot world models must respond precisely to robot trajectories while preserving realistic visual dynamics, yet learning both from heterogeneous robot videos remains challenging. Simulation offers structured motion supervision, but appearance differences hinder direct transfer, and inaccurate simulation predictions can misguide real-video generation. We present SimForcing, a simulation-guided framework that uses simulation both as a source of transferable motion knowledge and as a controllable reference for prediction. First, we transfer motion knowledge from a simulation…

---

### [Odyssey: A Closed-Loop Benchmark for Long-Horizon Real-World Driving with Explicit Navigation Routes](https://arxiv.org/abs/2610.06469v1)

- **arXiv**: `2610.06469v1`  |  **提交日期**: 2026-10-05
- **作者**: Jungho Kim, Hongjae Shin, Seunghoon Yu, Heecheol Yoo, Myeongjun Kim, Jiyong Oh et al.

Closed-loop evaluation of end-to-end driving requires continuous rollouts that reveal how earlier decisions affect subsequent driving. However, existing benchmarks evaluate only short segments and fail to capture later consequences. Ambiguous directional commands also obscure the intended navigation objective. We introduce Odyssey, a closed-loop benchmark for long-horizon driving comprising 100 scenarios, each reconstructed from a 100-second nuPlan driving log to preserve the context of navigation maneuvers and traffic interactions. To provide a consistent navigation objective, Odyssey…

---

### [Wiring Matters: Injection Topology and Initialization of Affordance Heads in Vision-Language-Action Policies](https://arxiv.org/abs/2610.06318v1)

- **arXiv**: `2610.06318v1`  |  **提交日期**: 2026-10-05
- **作者**: Zijian An, Linhan Wang, Jiayan Wang, Shijie Geng, Ran Yang, Yiming Feng et al.

Dense affordance supervision is an appealing auxiliary signal for vision-language-action (VLA) policies, yet naively co-training an affordance head can severely damage instruction following. We present a controlled study of how to wire such a head into a modern VLA on the LIBERO benchmark. Our recipe reads the backbone through a stop-gradient and re-injects an intermediate head feature into the action expert via a learned bridge. The stop-gradient is a precondition: letting affordance gradients reach the backbone drops the policy below the headless base (85.5% vs. 93.1%). With the backbone…

---

### [VLA-ZO: Fast Zeroth-Order Adaptation for Vision-Language-Action Models](https://arxiv.org/abs/2610.06271v1)

- **arXiv**: `2610.06271v1`  |  **提交日期**: 2026-10-05
- **作者**: Jaemin Kim, Jiahn Kim, Taesik Gong

Adapting vision-language-action (VLA) models to deployment-time distribution shifts is important for reliable robotic operation, but conventional first-order adaptation can exceed the memory budget of inference-oriented deployment platforms. Zeroth-order (ZO) optimization offers a forward-only alternative with inference-level memory, but accurate gradient estimation requires many perturbation queries, making naive ZO prohibitively slow for large VLA models. We present VLA-ZO, a framework for fast ZO adaptation that exploits the structure of VLA computation. By confining adaptation to the…

---

### [Encoded but Not in Control: Revealing the Grounding Gap in Vision-Language Robot Policies](https://arxiv.org/abs/2610.06235v1)

- **arXiv**: `2610.06235v1`  |  **提交日期**: 2026-10-05
- **作者**: Shaohan Jiang, Jiahang Cao, Qiduo He, Fengting Deng, Kun Wu, Jingkai Sun et al.

Instruction following is central to language-conditioned robot policies: language should determine what to do when the same scene permits multiple valid actions. Yet successful execution alone cannot establish whether a policy follows the instruction or infers the task from the scene. We study this ambiguity through scene-preserving instruction interventions, using valid target substitutions, arbitrary nouns, and unrelated sentences while holding the scene fixed. We evaluate vision-language-action (VLA) policies and world-action models (WAMs) in simulation and in real-world experiments. Our…

---

### [Arm-wise Compositional Generalization in Dual-Arm Vision-Language-Action Models](https://arxiv.org/abs/2610.06184v1)

- **arXiv**: `2610.06184v1`  |  **提交日期**: 2026-10-05
- **作者**: Zaibin Zhang, Binghao Ran, Yuhan Wu, Zhongbo Zhang, Yifan Wang, Junwei Jiang et al.

Generalization in multi-arm collaboration can be studied as composing familiar atomic skills in new ways across arms. However, existing evaluations offer limited insight into which training and architectural choices support this ability under different coordination requirements. We introduce \textbf{ACG-Bench}, a benchmark for \emph{Arm-wise Compositional Generalization} that provides a common testbed for studying skill recomposition in dual-arm policies. It contains 23 task--condition pairs across 8 task families, with 6 in-domain conditions and 17 unseen compositions covering reordering,…

---

### [How (and How Not) to Use Data Augmentation in VLA Post-Training](https://arxiv.org/abs/2610.05994v1)

- **arXiv**: `2610.05994v1`  |  **提交日期**: 2026-10-05
- **作者**: Bram Grooten, Joaquin Vanschoren

Vision-language-action (VLA) models currently demonstrate strong performance in a wide range of real-world robotics tasks. However, they often still lack the generalization ability to handle large visual out-of-distribution shifts. Post-training of VLAs with reinforcement learning (RL) has been shown to benefit robustness, but significant room for improvement remains. In this work, we systematically study the effect of image augmentation on VLA post-training. We find that it is crucial to augment only the critic module during RL updates, while leaving the actor's input clean during both…

---

### [OGAM: Connecting Systematic Testing to Runtime Assurance through Object-Grounded Attention Monitoring for VLA Policies](https://arxiv.org/abs/2610.05878v1)

- **arXiv**: `2610.05878v1`  |  **提交日期**: 2026-10-05
- **作者**: Haki Darwish, Xiangyu Yin, Changwen Li, Rongjie Yan, Francisco Gomes de Oliveira Neto, Chih-Hong Cheng

Benchmarks expose vision-language-action (VLA) policies to few canonical instructions, while exhaustive deployment testing is impossible. We introduce Object-Grounded Attention Monitoring (OGAM), connecting systematic testing to runtime assurance: testing reveals attention divergence between successful and failed executions, and OGAM uses this signal to stop failures beyond the finite suite. We generate scene-grounded instructions through pairwise combinations of action templates and objects, and separately test meaning-preserving paraphrases. All 87 out-of-benchmark cases reveal problematic…

---

### [What the Guard Misses, the Robot Executes: Implied Harm in VLA Instructions](https://arxiv.org/abs/2610.05818v1)

- **arXiv**: `2610.05818v1`  |  **提交日期**: 2026-10-05
- **作者**: Sripad Karne, Arjun Balaji

Vision-language-action models (VLAs) act on instructions without being able to refuse, so screening harmful requests falls to monitors. We test whether these monitors catch ordinary robot tasks requested for harmful reasons, holding the task fixed while varying only how explicitly the intent is stated. $π_{0.5}$ completes the task at every level of explicitness, as often as for harmless controls. Text guards flag nearly every blunt request but few implied ones: up to 95% of implied-harm runs end with the task done and no flag raised, and up to 90% even after recalibrating on robot…

---

### [When to Switch: Reliable Action-Chunk Extension for Vision-Language-Action Models](https://arxiv.org/abs/2610.05719v1)

- **arXiv**: `2610.05719v1`  |  **提交日期**: 2026-10-05
- **作者**: Seonghoon Yu, Dongwon Kim, HyungRok Jung, Yoonjae Baek, Byung-kwan Lee, Suha Kwak et al.

Vision-Language-Action (VLA) models serve as unified policies for robotic manipulation, yet their expensive inference forces robots to pause between policy calls, resulting in stop-and-go execution that interrupts smooth motion and prolongs task completion. Extending the action chunk reduces policy calls and hence these pauses, but predicting farther into the future makes long-chunk execution unreliable. To understand where this unreliability arises, we analyze action errors within long chunks and find that they concentrate around transitions between manipulation subskills, growing sharply…

---

### [When Does Retrieval Help? A Study of In-Context Adaptation in Vision-Language-Action Models](https://arxiv.org/abs/2610.05492v1)

- **arXiv**: `2610.05492v1`  |  **提交日期**: 2026-10-04
- **作者**: Zixuan Liu, Joris Köster, Zizhan Zheng, Siavash Khajavi

Vision-language-action (VLA) models have shown strong potential as generalist robot policies, but adapting them to unseen tasks often requires costly parameter updates. Recent work such as RICL introduces in-context adaptability by retrieving expert demonstrations based on the current VLA observation and providing them as additional context at test time. The effectiveness of this adaptation therefore depends critically on the retrieval mechanism. In this work, we systematically study how different retrieval methods affect both retrieval quality and task performance within the RICL framework.…

---

### [EvoMem-VLA: State-Evolution Memory for Long-Horizon Robot Manipulation](https://arxiv.org/abs/2610.05418v1)

- **arXiv**: `2610.05418v1`  |  **提交日期**: 2026-10-04
- **作者**: Yuheng Na, Zhide Zhong, Junjie He, Junfeng Li, Haodong Yan, Jiaan Wang et al.

Most vision-language-action (VLA) models rely on current observations and lose task-relevant evidence once it leaves view, limiting performance on long-horizon, memory-dependent tasks. Existing efforts incorporate compressed historical features or sparse visual keyframes. However, isolated snapshots can leave the policy uncertain about what changed during past interactions and which action should follow. To overcome this limitation, we propose EvoMem-VLA, which constructs state-evolution memory by explicitly encoding and retaining observed changes between historical states. These change…

---

### [When and What to Prune? Stage-Aware Visual Token Pruning for Efficient VLA](https://arxiv.org/abs/2610.05273v1)

- **arXiv**: `2610.05273v1`  |  **提交日期**: 2026-10-04
- **作者**: Tianjun Shi, Haotian Xiong, Ziyu Gong, Qi Lu, Li Li

Visual token pruning is an effective way to accelerate vision-language models and is especially useful for vision-language-action (VLA) inference, where many visual tokens must be processed before predicting robot actions. Existing pruning methods usually estimate which tokens can be pruned based on attention scores or feature diversity, retaining tokens that are either highly attended or visually different from others. However, most of them use fixed pruning schedules, such as pruning once at a preset layer or pruning at uniformly spaced layers. Such schedules can be risky for VLA models,…

---

### [Vela: Scaling Vision-Language-Action Models with Adaptive Action Curve Parametrization](https://arxiv.org/abs/2610.05230v1)

- **arXiv**: `2610.05230v1`  |  **提交日期**: 2026-10-04
- **作者**: Yifan Li, Jiaxu Wang, Dongming Wu, Yicheng Jiang, Ryan Ji, Xiangyu Yue et al.

Most vision-language-action models represent future motion as fixed-rate action chunks, tying temporal resolution and prediction horizon to a fixed output budget. This pointwise representation wastes capacity on highly correlated neighboring actions, leaves temporal continuity and smoothness to be learned implicitly, and forces a tradeoff between long-horizon coverage and the local precision required for contact-rich manipulation. To address these limitations, we introduce Vela, a vision-language-action foundation model that represents future robot behavior as continuous trajectories. Vela…

---

### [A Safe Action Is Not Enough: Feasible-Future Decoding for Vision-Language-Action Policies](https://arxiv.org/abs/2610.05166v2)

- **arXiv**: `2610.05166v2`  |  **提交日期**: 2026-10-04
- **作者**: Tu Nguyen, Matthieu Zimmer, Vu Anh Vu, Ziyi Wang, Jannik Hammel Nielsen, Xuebing Zhou et al.

A safe action is not necessarily a viable one. A frozen vision-language-action (VLA) policy can favor a locally admissible move that leaves no policy-supported route to safe task completion. We call this the feasibility-likelihood gap: likelihood ranks the next move, while feasibility depends on the futures it leaves open. To bring those futures into the decision, we derive the exact next-block marginal of the history-conditioned policy-environment trajectory law restricted to safe task completion. The derivation reveals a candidate-dependent feasible-future mass: its support records whether…

---

### [Beyond LLM Serving: Characterizing Vision-Language-Action Workloads for Embodied AI System Design](https://arxiv.org/abs/2610.05062v1)

- **arXiv**: `2610.05062v1`  |  **提交日期**: 2026-10-04
- **作者**: Seonghun Jung, Sieun Moon, Jiyoung Jeong, Jimin Lee, Jaehyuk Huh

Vision-language-action (VLA) models translate multimodal observations into low-level robot actions. During robot operation, each control period sets an inference deadline, and overruns leave the robot acting on stale observations, reducing task success. Meeting this deadline motivates on-device or nearby edge execution, where a single robot requires batch-1 inference outside the design point of LLM serving systems. Although VLA architectures combine familiar vision-language, autoregressive, and diffusion-style components, their runtime behavior in this batch-1 control setting remains…

---

### [ProactiveVLA: Augmenting Embodied Memory through Proactive Environment Exploration](https://arxiv.org/abs/2610.06999v1)

- **arXiv**: `2610.06999v1`  |  **提交日期**: 2026-10-04
- **作者**: Shizuo Tian, Haodong Luo, Yutong Li, Yuebing Song, Yunxin Liu, Yuanchun Li

Rapid adaptation to a new environment requires a robot to acquire useful knowledge about local objects, states, and interactions from limited experience. Systems that combine a reasoning agent with a frozen vision-language-action model (VLA) can adapt through execution feedback and memory, making the choice of experience central to their effectiveness. Repeated practice of a target task may refine a familiar solution while leaving other interactions relevant to changed conditions untested. We introduce ProactiveVLA, which uses proactive environment exploration to acquire reusable knowledge…

---

### [GeoBridge-VLA: Geometry-Aware Residual Adaptation for Vision-Language-Action Models](https://arxiv.org/abs/2610.05026v1)

- **arXiv**: `2610.05026v1`  |  **提交日期**: 2026-10-04
- **作者**: Hyun Song, Kangmin Kim, Loren Jinsoo Um, Minhui Han, Jaehyeok Park, Taewan Cho et al.

Vision-language-action (VLA) models encode semantic information from vision-language pretraining, but manipulation also requires precise spatial reasoning. We present GeoBridge-VLA, a two-stage method for learning geometric features from a pretrained VLA's frozen visual encoder and using them for action prediction. Stage I trains a feature bridge and geometry decoder with depth supervision. Stage II freezes these modules and trains a gated residual interface together with the action-side projections and action expert. The residual augments the existing visual tokens without adding a second…

---

### [Triggering Generalist Reasoning via Predictive Uncertainty for Dual-System VLA](https://arxiv.org/abs/2610.05025v1)

- **arXiv**: `2610.05025v1`  |  **提交日期**: 2026-10-04
- **作者**: Hyemin Yang, Wooseong Jeong, Giwon Lee, Kuk-Jin Yoon

Dual-system Vision-Language-Action (VLA) models improve real-time robotic control by pairing a slow, reasoning-capable generalist with a fast specialist action expert. However, existing methods invoke the generalist at a fixed frequency, ignoring the fact that decision-making complexity varies throughout a rollout. This static strategy wastes computation in easy phases and can delay renewed reasoning when the scene changes unexpectedly. We propose TUD (Triggering generalist reasoning via predictive Uncertainty for Dual-system VLA), an adaptive inference framework that selectively skips…

---

### [DiVeR: Decision-Critical Verifier Learning for VLA Test-Time Scaling](https://arxiv.org/abs/2610.04933v1)

- **arXiv**: `2610.04933v1`  |  **提交日期**: 2026-10-04
- **作者**: Seongheon Park, Heecheol Kim, Shulin Tian, Lilika Makabe, Namiko Saito, Katsushi Ikeuchi et al.

Scaling robot data and model capacity has improved Vision-Language-Action (VLA) policies, but further progress is constrained by the high cost of robotic data. Verifier-guided test-time scaling offers an efficient alternative by sampling multiple action candidates and selecting the one most likely to lead to task success at inference time. Existing classification-based verifiers learn from trajectory-level outcomes but treat all visited states equally, even though their value for candidate discrimination can vary across a trajectory. At many states, plausible actions are similar and provide…

---

## 📅 2026-10-05

### [Detect and Suppress: A Mechanistic Defense against Adversarial Patches in VLA Models](https://arxiv.org/abs/2610.03498v1)

- **arXiv**: `2610.03498v1`  |  **提交日期**: 2026-10-02
- **作者**: Yukiya Horiba, Koshiro Aoki, Shunsuke Yasuki, Bum Jun Kim, Taiki Miyanishi

Adversarial patches can disrupt Vision-Language-Action (VLA) models by manipulating visual observations, leading to failures in robot control. However, it remains poorly understood which internal mechanisms underlie these failures and how targeted interventions can mitigate them. In this work, we mechanistically analyze VLA representations using a sparse autoencoder (SAE) and identify a feature whose activation strongly correlates with the presence of an adversarial patch. Based on this analysis, we suppress the identified feature at inference time only when a linear probe detects an attack.…

---

### [MobiAgent: Dual-Loop Recursive Policy Self-Improvement for Long-Horizon Mobile Manipulation](https://arxiv.org/abs/2610.03476v1)

- **arXiv**: `2610.03476v1`  |  **提交日期**: 2026-10-02
- **作者**: Chenzhi Liu, Yue Zhang, Jiehong Lin, Jianan Wang, Bo Wang, Zhongrui Wang et al.

Long-horizon mobile manipulation presents significant challenges due to compounding execution errors and capacity interference between locomotion and arm control. While recent Vision-Language-Action models excel at short-horizon tasks, they lack the hierarchical reasoning required for multi-stage objectives. Furthermore, existing hierarchical agents suffer from rigid sub-task mapping, inflexible replanning, and a lack of continuous learning. To address these limitations, we introduce MobiAgent, a dual-loop agentic framework that bridges robust deployment execution and recursive policy…

---

### [MixVLA: Adaptive Mixing of Non-Invariant Information for Generalizable Vision-Language-Action Models](https://arxiv.org/abs/2610.02898v1)

- **arXiv**: `2610.02898v1`  |  **提交日期**: 2026-10-02
- **作者**: Pingrui Zhang, Yu Zhang, Pengyuan Wu, Bin Wang, Haoming Song, Xianqiang Gao et al.

Vision-Language-Action (VLA) models have achieved remarkable advances in robotic manipulation, yet their zero-shot generalization under out-of-distribution (OOD) conditions remains limited. These models often entangle task-relevant invariant structure with environment-specific non-invariant factors, causing policies to rely on spurious appearance cues during action prediction. In this work, we propose \textbf{MixVLA}, a model-agnostic training framework that improves the generalization of VLA models without requiring additional OOD data or architectural modifications. The key component of…

---

### [FastOPD: On-Policy Distillation for Lightweight VLA Deployment](https://arxiv.org/abs/2610.02832v1)

- **arXiv**: `2610.02832v1`  |  **提交日期**: 2026-10-02
- **作者**: Yoojin Oh, Jeongsol Kim, Yeonwoo Seo, Jangho Park, Seonghyun Jin, Sunwoo Park et al.

Vision-Language-Action (VLA) foundation models have scaled rapidly to enhance manipulation performance and generalizability, but this scaling incurs high computational costs that render real-world deployment increasingly challenging. Existing approaches typically mitigate this issue by designing smaller architectures or reducing the iterative denoising steps in flow-based policies. In this work, we propose FastOPD, a foundation-to-lightweight VLA framework that enables the practical deployment of large-scale VLAs through efficient on-policy distillation. Specifically, FastOPD adapts a flow…

---

### [ManiPhysicsBench: Physics-Based Assessment of Object Preservation in VLA Manipulation](https://arxiv.org/abs/2610.02802v1)

- **arXiv**: `2610.02802v1`  |  **提交日期**: 2026-10-02
- **作者**: Sangwu Park, Yeonjun In, Wonjoong Kim, Sungwon Kim, Sein Kim, Chanyoung Park

Vision-language-action (VLA) models aim to perform diverse manipulation tasks, but task success in existing rigid-body benchmarks does not indicate whether they preserve objects. We introduce ManiPhysicsZoo, which consolidates literature-supported material properties, 3D meshes, and supporting references into reusable object assets. Using these assets, a solver-based assessment computes grasp-specific damage thresholds from object geometry, material properties, and recorded grasp conditions and compares them with recorded contact forces to assess potential deformation and fracture. Building…

---

### [SimpleTouch: Can Vision-Language-Action Models Master Contact-Rich Manipulation Without Tactile Policy Pretraining?](https://arxiv.org/abs/2610.02784v1)

- **arXiv**: `2610.02784v1`  |  **提交日期**: 2026-10-02
- **作者**: Chen Yang, Linzhe Shi, Changjie Wu, Hang Zhang, Ronghan Chen, Lingjun Zhang et al.

Tactile sensing provides essential contact information for robotic manipulation, yet incorporating it into pretrained vision-language-action (VLA) models remains challenging. A common concern is that simply introducing touch during task-specific fine-tuning may fail to bridge the cross-modal gap, yielding limited gains or even reduced success. Consequently, existing methods often rely on large-scale tactile policy pretraining or separate visuotactile alignment, adding data requirements and training stages. We introduce SimpleTouch, a simple VLA extension that augments $π_{0.5}$ with a tactile…

---

### [CHASE-VLA: Post-Training Quantization Framework for Vision-Language-Action Models with Chunk-Aware Scale Estimation](https://arxiv.org/abs/2610.02666v1)

- **arXiv**: `2610.02666v1`  |  **提交日期**: 2026-10-02
- **作者**: Jin Hyun, Jung Gyu Min, Gyuhyun Jung, Youngjoo Lee

Vision-Language-Action (VLA) models map visual observations and language instructions to continuous robot actions, but a diffusion-based action expert (AE) poses a key challenge for low-bit post-training quantization (PTQ). The AE is repeatedly invoked across denoising steps and policy queries, where fixed calibration scales can be mismatched with activation ranges that vary with denoising progress and intended motion. We propose CHASE-VLA, a chunk-aware PTQ method that exploits a VLA-specific signal readily available from the policy: the generated action chunk, including its unexecuted…

---

### [Imagine the Future, Internalize the Gist: Efficient VLA Reasoning via Internalized Spatiotemporal Imagination](https://arxiv.org/abs/2610.02626v1)

- **arXiv**: `2610.02626v1`  |  **提交日期**: 2026-10-02
- **作者**: Shenglan Li, Zhendong Mi, Hengyi Zhu, Jingwu Luo, Chun Kit Chan, Geng Yuan et al.

Vision-language-action (VLA) models increasingly incorporate intermediate reasoning to improve robotic manipulation, yet existing approaches primarily reason about observed states without explicitly anticipating future scene evolution. Extending such reasoning to explicit future rollouts at every inference step, however, introduces substantial computational overhead. We propose IG-VLA, a VLA reasoning framework that enables models to imagine the future and internalize the gist. Our Latent Spatiotemporal Reasoning learns to imagine task-relevant future scene evolution directly in visual…

---

## 📅 2026-10-02

### [DuoMind: Enabling Distributed Multi-Robot Coordination with Semantic Communication](https://arxiv.org/abs/2610.02161v1)

- **arXiv**: `2610.02161v1`  |  **提交日期**: 2026-10-01
- **作者**: Hanchu Zhou, Dechen Gao, Hang Wang, Brendan Lynch, Boqi Zhao, Qiyao Ma et al.

Vision-language models (VLMs) and vision-language-action models (VLAs) have recently driven rapid progress in general-purpose robots, yet most progress has focused on single-robot settings. Extending these capabilities to multi-robot systems remains challenging because robots must coordinate long-horizon behaviors while maintaining reliable, fine-grained execution. We introduce DuoMind, a distributed hierarchical framework for multi-robot coordination through semantic communication. Each robot uses a VLA-based action model for low-level execution and a VLM-based orchestrator for high-level…

---

### [UniWAM: Unified World-Action Model](https://arxiv.org/abs/2610.02054v1)

- **arXiv**: `2610.02054v1`  |  **提交日期**: 2026-10-01
- **作者**: Jiayi Chen, Wenxuan Song, Jingbo Wang, Shuai Zhou, Xicheng Gong, Zehua Fan et al.

Vision-language-action models benefit from the understanding and reasoning capabilities of pretrained vision-language models, but action-only supervision provides limited grounding in world dynamics. Conversely, world-action models inherit spatiotemporal priors from video generation models, yet remain limited in semantic understanding and reasoning under distribution shifts. We introduce UniWAM, a unified architecture that integrates a physical reasoner, a world generator, and an action predictor to jointly learn semantic understanding of the physical world, visual generation, and action…

---

### [Fewer Tokens, Better Action: GPT-6 Astra Robot Agents with 14% Higher Success Rate but 65% Fewer Tokens](https://arxiv.org/abs/2610.01939v1)

- **arXiv**: `2610.01939v1`  |  **提交日期**: 2026-10-01
- **作者**: Ruiyang Si, Jianxin Bi, Shunyu Yang, Rui Ni, Wenbo Huang, Qiang Wang et al.

Vision language model (VLM) agents can control robots through visual feedback and action primitives, but repeated model invocations and redundant observations incur substantial token overhead. We introduce PyRUA-Lean, an interactive code-execution framework that couples feedback-driven primitive composition with selective observation: the agent composes classical robot primitives and learned vision-language-action (VLA) policies into Python cells that perform conditional checks and local retries, returning only explicitly requested images and state feedback for replanning. Across 700…

---

### [ChunkVLA-AM: Parallel Action Chunking for Vision-Language-Action Robot Control in Additive Manufacturing](https://arxiv.org/abs/2610.01856v1)

- **arXiv**: `2610.01856v1`  |  **提交日期**: 2026-10-01
- **作者**: Zhugang Liu, Kaichuang Zhang, Jinman Zhang, Pu Sun, Martha Asare, Jose Hernandez et al.

Vision-language-action (VLA) models unify visual perception, language understanding, and action generation, offering new opportunities for automation in additive manufacturing (AM). However, deployment in AM remains challenging because adapting these models to unseen robot embodiments is costly, and performance can degrade under environment changes. In this work, we present a framework for deploying OpenVLA-OFT on a FAIRINO FR3 robot in a fixed AM workcell. A data pipeline converts monocular real-world demonstrations into OpenVLA-compatible TFDS/RLDS datasets to support adaptation to the FR3…

---

### [Continuous Conditioning of VLAs with Augmenting EMG and Visual Task Descriptors](https://arxiv.org/abs/2610.01794v1)

- **arXiv**: `2610.01794v1`  |  **提交日期**: 2026-10-01
- **作者**: Edward W. Staley, Connor O. Pyles, Rahul Hingorani, Frank Camargo, Griffin Milsap, Jared Markowitz et al.

Vision-Language-Action (VLA) models rely strongly on language for describing task information, despite having multimodal inputs. We hypothesize that other modalities in the state space may present opportunities for supplemental task conditioning, which may be particularly relevant in cluttered or otherwise ambiguous scenes. We introduce two tuned models to test this hypothesis: (1) an electrophysiology-conditioned VLA (EC-VLA) that incorporates 8-channel electromyography envelopes as continuous conditioning input concatenated to the proprioceptive vector, and (2) a visually-annotated VLA…

---

### [ATI-VLA: Action-Centric Predictive Vision-Language-Action Models via Actionable Alignment Then Adaptive Injection](https://arxiv.org/abs/2610.01741v1)

- **arXiv**: `2610.01741v1`  |  **提交日期**: 2026-10-01
- **作者**: Yijie Zhu, Rui Shao, Jie He, Wei Li, Bo Zhao, Yelin Wang et al.

Predictive Vision-Language-Action (VLA) models aim to improve robotic manipulation via future observation or world dynamics forecasting. However, existing approaches often fail to realize this potential and underperform direct action prediction models. We argue that these limitations stem from modality misalignment between observations and actions, together with joint optimization conflicts that drive learning away from an action-centric objective. To this end, we introduce ATI-VLA, an Action-Centric Predictive Vision-Language-Action framework via Actionable Alignment Then Adaptive Injection.…

---

### [Is Success All You Need? Investigating the Impact of Input Perturbations on VLA Behaviour in Tabletop Manipulation Tasks](https://arxiv.org/abs/2610.01351v1)

- **arXiv**: `2610.01351v1`  |  **提交日期**: 2026-10-01
- **作者**: Sophie Higham, Riccardo Andrea Izzo, Matteo Matteucci, Alessandro Suglia

Vision-Language-Action (VLA) models have achieved high task success rates on robot manipulation task benchmarks. More recently, there has been an emphasis on evaluating the robustness of VLA models to perturbations. However, this robustness is still predominantly measured through Task Success Rate (TSR). In this work, we propose a benchmark-agnostic evaluation framework to measure the behavioural robustness of models by characterising how successful trajectories are executed under perturbation. We implement this methodology by extending the widely-used LIBERO and LIBERO-Plus benchmarks.…

---

### [WBAG: A Whole-Body and Attached-Geometry Safety Framework for Vision-Language-Action Manipulation](https://arxiv.org/abs/2610.01083v1)

- **arXiv**: `2610.01083v1`  |  **提交日期**: 2026-10-01
- **作者**: Samuel Zhen, Siwon Jo, Yanze Zhang, Wenhao Luo

Vision-language-action (VLA) policies have demonstrated impressive capabilities in generalizable robotic manipulation, but their deployment in the real world remains challenging due to potential collisions involving different parts of the robot, manipulated objects, and the surrounding environment. Existing inference-time VLA safety frameworks typically rely on simplified end-effector-centered representations that do not explicitly model the full articulated robot and attached-object geometry. In this paper, we present WBAG, a safety framework that models the robot's whole-body and…

---

### [Divide-and-Remember: Recursive Action-Relevant Memory for Long-Horizon VLA Policies](https://arxiv.org/abs/2610.00982v1)

- **arXiv**: `2610.00982v1`  |  **提交日期**: 2026-10-01
- **作者**: Xuehui Yu, Eason Yu, Meiyi Wang, Haozhe Du, Stefano V. Albrecht, Harold Soh

Vision-language-action (VLA) models struggle on history-dependent manipulation tasks, where the current observation alone does not determine the action, and the policy needs a memory of the history. Existing memory methods decide what to remember by design, for example, keeping frames with large pixel changes, and show inconsistent gains across tasks. We view what to remember as an optimisation problem. From the POMDP formulation of imitation learning, we show that the optimal memory maximises the conditional mutual information $I(a_t; m_t \mid o_t)$ between the action and the memory given…

---

### [NarrativeFlow: Flow-Based Vision-Language-Action Model Using Robot Velocity Fields](https://arxiv.org/abs/2610.00981v1)

- **arXiv**: `2610.00981v1`  |  **提交日期**: 2026-10-01
- **作者**: Shota Kobayashi, Koki Seno, Daichi Yashima, Komei Sugiura

We focus on language-conditioned flow-based manipulation, where robot flows (robot velocity fields) serve as embodiment-agnostic, motion-centric representations for leveraging data collected from multiple robot platforms. This task is crucial because language-conditioned manipulation is essential for practical robotic systems, yet scaling robot foundation models remains limited by the labor-intensive collection of embodiment-specific data. Existing methods either coarsely approximate robot flows with sparse keypoint displacements, or cannot handle language-conditioned manipulation. To address…

---

### [eRLT: Efficient VLA Reinforcement Learning via Action-Relevant Token Routing](https://arxiv.org/abs/2610.00913v1)

- **arXiv**: `2610.00913v1`  |  **提交日期**: 2026-10-01
- **作者**: Dehao Huang, Jianbang Liu, Jianpan Gao, Chao Tang, Zilang Cen, Zedong Dan et al.

Vision-Language-Action (VLA) models provide strong behavioral priors for robotic manipulation, yet efficiently adapting them to downstream tasks remains challenging. Recent work addresses this challenge by adapting frozen VLAs through online reinforcement learning (RL), whose sample efficiency depends on the quality of the state representation used by the actor and critic. Existing methods construct such representations either with VLA-independent visual encoders or through fixed compression of internal VLA representations. Neither design explicitly extracts the task-specific action-relevant…

---

### [TOAST: Stochastic Robot Action Tokenization for Autoregressive Vision-Language-Action Models](https://arxiv.org/abs/2610.00899v1)

- **arXiv**: `2610.00899v1`  |  **提交日期**: 2026-10-01
- **作者**: Keisuke Shirai, Tomohiro Motoda, Hanbit Oh, Ryoichi Nakajo, Roman Mykhailyshyn, Ryo Hanai et al.

Autoregressive Vision-Language-Action models often represent continuous robot actions as discrete token sequences, enabling action prediction with standard next-token objectives. FAST has substantially improved this representation by compactly encoding action containing diverse temporal frequencies into relatively few tokens. However, while such compression reduces the number of action tokens required for autoregressive prediction, it does not necessarily improve the efficiency of policy learning from limited demonstrations. In particular, FAST typically assigns a single deterministic…

---

### [ECoMEM: Explicit Concept Memory for Memory-Dependent Robot Control](https://arxiv.org/abs/2610.00801v1)

- **arXiv**: `2610.00801v1`  |  **提交日期**: 2026-09-30
- **作者**: Yize Liu, Ke Wang, Mac Schwager, Yiqing Xu, Jiajun Wu

A robot may lose sight of an object it must later retrieve, need to recall what a person demonstrated earlier, or track which steps of a task it has already completed. Current vision-language-action (VLA) policies often fail once the information needed for action disappears from the current observation, making memory critical for long-horizon robot behavior. Existing approaches typically provide longer histories or learn implicit memory from observation-action trajectories. But action supervision tells a policy how to act, not what to remember: it does not specify which past facts should…

---

### [MIKASA-Robo-VLA: Benchmarking Memory in VLA Models for Long-Horizon Manipulation](https://arxiv.org/abs/2610.00604v1)

- **arXiv**: `2610.00604v1`  |  **提交日期**: 2026-09-30
- **作者**: Egor Cherepanov, Nikita Kachaev, Aleksandr I. Panov, Alexey K. Kovalev

Vision-language-action policies often see only one or a few recent frames, which makes it difficult to evaluate how they use information that disappears during a task. We introduce MIKASA-Robo-VLA, a benchmark of 90 language-conditioned manipulation tasks. All but 10 hide the cue an action depends on. Those 10 are reactive controls. MIKASA-Robo, the suite it rebuilds, has 32 tasks and uses language only in a representative VLA subset. Here every task provides an instruction, while memory-dependent tasks hide a task-relevant cue and reactive controls keep it available. For 70 tasks,…

---

### [When Reasoning Helps Action: Monitoring and Steering Chain-of-Thought in Vision-Language-Action Policies](https://arxiv.org/abs/2610.00601v1)

- **arXiv**: `2610.00601v1`  |  **提交日期**: 2026-09-30
- **作者**: Sathwik Karnik, Joseph JR. Lee, Aryaman Gupta, Somil Bansal

Reasoning-enabled VLA policies expose chain-of-thought (CoT) traces that appear to explain and guide their actions, creating a potential interface for runtime safety through reasoning monitoring and correction. In this work, we define and operationalize two evaluation axes for assessing when this interface can improve embodied behavior: correctability, which measures whether unreliable reasoning can be detected and improved during generation, and actionability, which measures whether reasoning corrections produce behaviorally meaningful changes in the intended direction. To enable…

---

### [Token-World: World Modeling in Vision-Language Model Token Space for Robot Manipulation](https://arxiv.org/abs/2610.00575v1)

- **arXiv**: `2610.00575v1`  |  **提交日期**: 2026-09-30
- **作者**: Chuyao Fu, Xiaowei Chi, Yuhan Rui, Yu-kai Wang, Zezhong Qian, Xiaojie Zhang et al.

A common approach to world-model simulation for vision-language-action (VLA) systems is to predict future RGB observations and then re-encode them into policy inputs, introducing an indirect interface between simulation and downstream policy execution. We instead investigate whether world dynamics can be modeled in a compact, policy-oriented state derived from VLM visual tokens. A key challenge is that raw VLM visual tokens are high-dimensional, making efficient and accurate autoregressive dynamics modeling challenging. To address this, we introduce Token-World, an action-conditioned world…

---

### [Same Scene, Different Task: Skill Alignment for Compositional Generalization in VLAs](https://arxiv.org/abs/2610.00524v1)

- **arXiv**: `2610.00524v1`  |  **提交日期**: 2026-09-30
- **作者**: Taegeun Yang, Youngju Na, Yoonki Cho, Sung-Eui Yoon

Vision-language-action (VLA) models often struggle to generalize to skill combinations absent from their fine-tuning demonstrations, even when every constituent skill has been demonstrated. We focus on a vision shortcut as one failure mode: during fine-tuning, visual observations can serve as a proxy for the instruction, so a policy may execute a demonstrated combination associated with similar observations rather than the instructed combination. This motivates training with counterfactual pairs formed by holding a demonstration observation fixed while changing the instruction to specify an…

---

### [Towards a General Humanoid Loco-Manipulation Model via Egocentric Whole-Body Human Data Pretraining](https://arxiv.org/abs/2610.00438v1)

- **arXiv**: `2610.00438v1`  |  **提交日期**: 2026-09-30
- **作者**: Chongyang Xu, Zhao Wu, Jin Chen, Yiming Jiang, Jinhui Ye, Yuming Jiang et al.

Humanoid whole-body manipulation has advanced rapidly, enabling policies to coordinate locomotion, posture, bimanual interaction, and dexterous hand movements. Meanwhile, egocentric human videos provide diverse examples of everyday interactions across objects and scenes, offering scalable supervision without robot operation. However, existing supervision from these videos provides limited coverage of whole-body movement and coordination with hand-object interaction, while obtaining such supervision through humanoid teleoperation is also costly and difficult to scale. We therefore explore how…

---

## 📅 2026-10-01

### [WorldAuditBench: Interactive 3D World Auditing with Multimodal Agents](https://arxiv.org/abs/2609.40325v1)

- **arXiv**: `2609.40325v1`  |  **提交日期**: 2026-09-30
- **作者**: Ziyan Jiang, Jingbo Yang, Jiabao Ji, Yujian Liu, Qiucheng Wu, Tommi Jaakkola et al.

As interactive 3D worlds are increasingly used to study intelligent behavior, it becomes important to develop efficient pipelines for identifying anomalies in these simulated environments, such as floating objects, traversable walls, or objects inconsistent with the surrounding scene. Multimodal AI systems, including vision-language models (VLMs) and vision-language-action models (VLAs), have shown potential for automating this task. However, 3D world auditing is complex, requiring the close coupling of two distinct capabilities: action, to navigate the 3D world and search for anomalies…

---

### [Tactile Curiosity Drives Robot Interaction](https://arxiv.org/abs/2609.40134v1)

- **arXiv**: `2609.40134v1`  |  **提交日期**: 2026-09-30
- **作者**: Klemens Iten, Alexander Proshkin, Bhavya Sukhija, Stelian Coros, Andreas Krause, Pieter Abbeel et al.

Mastering robot manipulation skills via reinforcement learning (RL) remains largely sample-inefficient. The most common RL algorithms rely on random action sampling to discover new strategies, resulting in agents that allocate most of their training budget to motions in free space, away from the contacts from which manipulation skills emerge. Existing intrinsic motivation methods based on model disagreement or epistemic uncertainty improve on isotropic noise, but they can also reward uncertainty in functionally irrelevant transitions, such as erratic motions in free space. In this work, we…

---

### [Multi-Link Safety Filtering for VLA Policies Around Moving Hazards](https://arxiv.org/abs/2609.40007v1)

- **arXiv**: `2609.40007v1`  |  **提交日期**: 2026-09-30
- **作者**: Yatharth Agarwal, Vijay Raghunathan

A vision-language-action (VLA) policy can finish a manipulation task while knocking over objects unrelated to it, so task success alone does not show that the policy is safe to deploy in clutter. We study how to keep a pretrained VLA policy clear of such hazards at run time without retraining it, which requires guarding more of the arm than the end effector, following the hazard as it moves, and sharing onboard compute with the policy. Our training-free shield covers the gripper, wrist, and forearm with five ellipsoids and filters every commanded motion through one barrier program against a…

---

### [EWAM: Emergent Depth-Wise Specialization in a Unified Embodied Model -- From Semantic Understanding through Visual Foresight to Action](https://arxiv.org/abs/2609.39973v1)

- **arXiv**: `2609.39973v1`  |  **提交日期**: 2026-09-30
- **作者**: Hao Wang, Jiajun Wen, Jingzhi Liu, Shuoshuo Xue, Zhiliang Chen, Min Lin et al.

Vision-language-action (VLA) policies emphasize semantic understanding, whereas world-action models (WAMs) learn predictive representations of environment dynamics. Systems that expose a policy to both sources often still concentrate action computation on a single expert. We present EWAM, an action-centric unified embodied model whose asymmetric joint attention lets action tokens read semantic, current-visual, predicted-future, and action information at every layer while the perceptual experts retain their distinct roles. Without layer-wise supervision, EWAM develops an emergent depth-wise…

---

### [When Instructions Retrieve Trajectories: Diagnosing and Mitigating Generalization Failures in VLA Models](https://arxiv.org/abs/2609.39971v1)

- **arXiv**: `2609.39971v1`  |  **提交日期**: 2026-09-30
- **作者**: Hung-Jen Chen, Yu-Hsun Hou, Yan-Hong Chen, Yan-Fu Chen, Binghua Cai, Min Sun et al.

Vision-language-action (VLA) models can exceed 90% success on in-distribution tasks and withstand nuisance changes that preserve the required action, yet fail under counterfactual changes that demand a different action. Aggregate robustness scores can therefore conceal a more specific failure, in which a policy responds to both language and vision yet does not combine them to select the action the task requires. We call this failure instruction-action binding. Instructions cue familiar trajectory families, and visual feedback adjusts their execution. Behavioral analyses of fine-tuned…

---

### [Toward Real-Time VLAs: Stage-Aware Two-Step Flow Denoising and System-Level Evaluation](https://arxiv.org/abs/2609.39822v1)

- **arXiv**: `2609.39822v1`  |  **提交日期**: 2026-09-30
- **作者**: Di Wu, Rongtian Shen, Ping Liu, Yan Shen, Zhenhan Yin, Shun Zuo et al.

Vision-language-action (VLA) models face a timing gap between low-rate inference and high-rate robot execution. We characterize this gap through end-to-end latency measurements of model inference and the robot execution chain. Repeated Flow Matching denoising contributes substantially to inference cost, while robot-side delays mainly arise from perception acquisition, communication scheduling, and physical response. Analysis of the velocity field shows relatively stable magnitude and direction in early integration, followed by stronger directional correction near the terminal steps. Based on…

---

### [Learning from Runtime Feedback through Failure-Bank Self-Evolution for Vision-Language-Action Models](https://arxiv.org/abs/2609.39820v1)

- **arXiv**: `2609.39820v1`  |  **提交日期**: 2026-09-30
- **作者**: Mingyue Cui, Zheyuan Liu, Yihan Zhu, Zheyuan Zhang, Meng Jiang

Vision-language-action (VLA) models generalize broadly across robotic manipulation tasks, but complex environments require balancing task success with unintended contact. Runtime shields can correct individual actions, but they leave the underlying policy unchanged, so repeated disagreements may create a persistent policy-shield mismatch that blocks task progress. To address this challenge, we introduce FailBank, a four-stage self-evolving framework that converts runtime feedback into persistent policy improvement. During collection, a fixed CBF-based safety module serves as an observe-only…

---

### [Inline Memory Meets Reusable Skills: Memory-centric Framework for Vision-Language-Action Model](https://arxiv.org/abs/2609.39794v1)

- **arXiv**: `2609.39794v1`  |  **提交日期**: 2026-09-30
- **作者**: Zaijing Li, Rui Shao, Bing Hu, Haoyu Zhang, Dongmei Jiang, Liqiang Nie

Vision-Language-Action (VLA) models have shown strong promise for general-purpose robotic manipulation, yet adapting them to new tasks and domains remains inefficient: existing methods often rely on parameter tuning, incurring substantial costs and risking catastrophic forgetting of previously learned tasks. To address this, we propose \textbf{Optimus-R}, a memory-centric VLA framework that formulates robotic adaptation as explicit query-skill memory tuning. Optimus-R introduces: (i) An \textbf{Inline Memory Interface for skill extraction}. It inserts learnable memory tokens into the VLA…

---

### [From Local Whole-Body VLA Behaviors to Scene-Scale Aerial Manipulation](https://arxiv.org/abs/2609.39670v1)

- **arXiv**: `2609.39670v1`  |  **提交日期**: 2026-09-30
- **作者**: Weixiang Guo, Rui Jin, Haotian Jin, Xinhang Xu, Ruiyang Liu, Haoran Zhao et al.

Vision-language-action (VLA) models enable task-conditioned interaction, but extending them to scene-scale aerial manipulation remains challenging due to costly whole-body demonstrations, latency-induced action-state misalignment, and cross-site behavior composition. We present a unified framework for synthetic policy training and scene-scale execution on articulated uncrewed aerial manipulators (UAMs). A scene-reconfigurable pipeline synthesizes task-conditioned, kinodynamically feasible trajectories and synchronized multiview observations for VLA training without physical-platform…

---

### [GroundingPI: A Grounding Foundation Model towards Physical Intelligence with Visual Primitives](https://arxiv.org/abs/2609.39601v1)

- **arXiv**: `2609.39601v1`  |  **提交日期**: 2026-09-30
- **作者**: Qize Yu, Lianrui Fan, Boyu Chen, Jiaqi Liang, Xini Ding, Yue Chen et al.

Precise grounding matters. It specifies which object is the target and where that object is, even in clutter and for tiny objects, and it has to be fast enough for closed-loop control. Yet vision-language-action (VLA) and world-action models (WAMs) take perception from general-purpose vision-language and video-generation backbones, which still fail in these settings. We introduce GroundingPI, a 4B grounding foundation model that generates points and boxes as quantized coordinates in a shared vocabulary. Training combines multimodal and spatial pretraining, supervised fine-tuning, and…

---

### [Discrete Forcing: Infusing Discrete Guidance into Continuous Denoising for Few-Step Action Experts](https://arxiv.org/abs/2609.39526v1)

- **arXiv**: `2609.39526v1`  |  **提交日期**: 2026-09-30
- **作者**: Jingbo Wang, Wenxuan Song, Wenhao Yu, Han Zhao, Xi Wang, Jiayi Chen et al.

Efficient action generation in vision-language-action (VLA) models requires capturing both coarse action structure and fine-grained details. Discrete action tokens provide compact structural representations but sacrifice precision, while continuous action tokens offer high precision but often require multiple denoising steps. We introduce Discrete Forcing, a flow-matching framework that combines these representations through an explicit coarse-to-fine generation process. It first predicts discrete action tokens to establish a coarse action structure, then uses them to guide continuous action…

---

### [MotionWeave: Learning Motion-Centered Future Dynamics for Vision-Language-Action Policies](https://arxiv.org/abs/2609.39324v1)

- **arXiv**: `2609.39324v1`  |  **提交日期**: 2026-09-30
- **作者**: Jingqiu Wang, Yan Wang

Vision-Language-Action (VLA) models have recently incorporated world models to provide richer dynamic supervision beyond sparse action labels. However, explicitly predicting future images or videos may include control-irrelevant appearance, while guidance derived from holistic future visual representations and shared global action features may fail to establish timestep-specific correspondence between actions and local visual changes. To address this issue, we propose MotionWeave, a motion-centric future-dynamics framework for action-chunk prediction with two modules: the Action-Induced…

---

### [The Planning Limits of Latent World Models](https://arxiv.org/abs/2609.39235v1)

- **arXiv**: `2609.39235v1`  |  **提交日期**: 2026-09-30
- **作者**: Ali Alrasheed, Basim Azam, Naveed Akhtar

World models offer a promising way to help robots understand how the physical world evolves and plan complex behaviours through imagination. Yet existing studies mainly demonstrate what these models can accomplish, leaving unclear when their predictions remain useful for planning and where they fail. We study this question using action-conditioned predictors built on five frozen self-supervised visual backbones: V-JEPA 2, V-JEPA 2.1, VideoMAEv2, VideoPrism, and DINOv2. We use frozen backbones to test representations intended to transfer across environments. We evaluate these models on diverse…

---

### [DSDyn-VLA: A Dual-Stream Dynamic Manipulation Framework with Motion Perception, Future Awareness, and Realtime Correction](https://arxiv.org/abs/2609.39198v1)

- **arXiv**: `2609.39198v1`  |  **提交日期**: 2026-09-30
- **作者**: Wenhao Li, Xiu Su, Yu Han, Yichao Cao, Shan You, Chang Xu

While Vision-Language-Action (VLA) models excel in static tasks, they struggle in dynamic environments where objects are in motion (e.g., conveyor belt manipulation). We identify three fundamental limitations hindering current VLAs in these scenarios: the \textbf{perception gap}, where static visual inputs lack temporal motion cues; the \textbf{latency gap}, where inference delays render actions obsolete; and the \textbf{control gap}, caused by the open-loop action chunk execution without real-time adjustment. In this work, we propose \textbf{DSDyn-VLA}, a Slow-Fast…

---

### [Exploiting Vulnerabilities: Universal Adversarial Attacks on Vision-Language-Action Models in Robotics](https://arxiv.org/abs/2609.39178v1)

- **arXiv**: `2609.39178v1`  |  **提交日期**: 2026-09-30
- **作者**: Songhua Yang, Ziyu Liu, Yuanwei Liu, Xuetao Li, Xuanye Fei, He Huang et al.

Recently, Vision-Language-Action (VLA) models have revolutionized robotic manipulation by seamlessly integrating visual perception, language understanding, and action generation in an end-to-end learning framework. However, since these models are designed to interact directly with the physical world and humans, their security is critical, and even small vulnerabilities can lead to catastrophic failures. In this work, we propose the Universal Adversarial Object, a sphere with optimized surface texture that significantly degrades task success rates when placed within the robot's field of view.…

---

### [Blackout vs. Freeze: Analyzing Physical Failure Modes of VLAs under Camera Faults](https://arxiv.org/abs/2609.39145v1)

- **arXiv**: `2609.39145v1`  |  **提交日期**: 2026-09-30
- **作者**: Heejae Suh, Jongwook Han, Zahra Gholami, Yohan Jo

Unreliable visual inputs can harm task performance and cause potential physical safety risks for vision-language-action (VLA) models. We analyze how $π0.5$ and GR00T models act under input faults such as image blackouts and freezing. We find that blackout and freezing produce distinct physical failure modes even when task-success rates are similarly low: freezing causes more extreme joint behavior, whereas blackout after gripper closure can cause more object drops, most markedly without proprioception. Selective intervention studies reveal that proprioception (current robot state) partly…

---

### [Cue the Flow: Steering Flow-Matching Policies for Open-World Delivery Manipulation](https://arxiv.org/abs/2609.38989v1)

- **arXiv**: `2609.38989v1`  |  **提交日期**: 2026-09-30
- **作者**: Haoxuan Wang, Griffin Galimi, Junhua Huang, Selina Song, Wayne Wu, Yan Yan et al.

Open-world goods delivery requires mobile manipulators to follow free-form user instructions and manipulate potentially novel objects. Existing dual-system approaches use high-level grounding models to convert language into grounded visual prompts, but their low-level controllers can remain brittle under noisy perception, dynamic scenes, and contact-rich interactions. We instead use a pretrained flow-matching vision-language-action model as the low-level control interface, leveraging its reactivity and robustness to environmental changes while treating the grounding output as a spatial cue…

---

### [PRICE the Action Chunks: Physical Relational Credit Assignment for Embodied Reinforcement Learning](https://arxiv.org/abs/2609.38890v1)

- **arXiv**: `2609.38890v1`  |  **提交日期**: 2026-09-30
- **作者**: Yangang Zou, Jiajun Lu, Weitao Zhou, Haibao Yu, Bozhou Zhang, Jiawei Wang et al.

Outcome-based reinforcement learning (RL) post-trains vision--language--action policies using terminal success signals, but assigns the same trajectory-level advantage to every action chunk. A failed episode can thus penalize useful early actions as if they caused the failure. Existing approaches seek finer-grained feedback through learned evaluators, adding task-specific supervision or additional model training. We explore, for the first time to our knowledge, whether physical relations across trajectories can provide action-chunk credit in embodied RL from terminal outcomes alone, without…

---

### [Online Evolution Strategy for Flow-Matching VLA Policies via Self-Supervised Trajectory Distribution Optimization](https://arxiv.org/abs/2609.38855v1)

- **arXiv**: `2609.38855v1`  |  **提交日期**: 2026-09-30
- **作者**: Gongxin Yao, Yongsheng Zhao, Jiayin Deng, Deng Liang, Han Gao, Lei Zhao et al.

Vision-Language-Action (VLA) models based on generative frameworks, such as Flow Matching, have recently achieved impressive performance in robotic manipulation. Unlike deterministic policies, Flow Matching enables VLA models to learn conditional action trajectory distributions, where latent noise vectors induce different actions under the same task scenario. However, we observe that these distributions are often ill-formed, with successful and failed behaviors coexisting while considerable probability mass remains in unfavorable regions. To this end, we propose Online-ES, an online…

---

### [Vision-Language-Action Autonomous Driving Agent with Language-based Memory](https://arxiv.org/abs/2609.38641v1)

- **arXiv**: `2609.38641v1`  |  **提交日期**: 2026-09-29
- **作者**: Kai Yan, Xiangyu Chen, Yulong Cao, Alex Naumann, Peter Karkus, Yan Wang et al.

Vision-Language-Action (VLA) foundation models have recently emerged as one of the prevailing solutions for autonomous driving, as they can utilize knowledge acquired during vision-language pretraining for accurate and interpretable driving. However, VLAs can take only a limited number of frames as visual input due to the high token cost of an image, which is problematic for memory-dependent tasks such as determining the arrival order at all-way stops and long-horizon driving scene understanding. Existing solutions use latent vector memories accessed through cross-attention, which are neither…

---

### [Correcting WHERE, Preserving HOW: Compositional Generalization for Vision-Language-Action Models via Referential Guidance](https://arxiv.org/abs/2609.38616v1)

- **arXiv**: `2609.38616v1`  |  **提交日期**: 2026-09-29
- **作者**: Yanyan Zhang, Disheng Liu, Xinpeng Li, Chaoda Song, Mohsen Hariri, Debargha Ganguly et al.

While Vision-Language-Action (VLA) models enable flexible action generation, their generalization across diverse environmental elements, including manipulated objects, destinations, and backgrounds, is limited by the lack of diversity in robotic training data. Trained end-to-end on such data, VLAs tend to exploit visual shortcuts, associating actions with task-irrelevant visual features rather than the intended task semantics. These shortcuts block recomposition of elements already seen by the policy, that is, compositional generalization. Existing approaches mitigate such entanglement…

---

### [Data-Efficient Adaptation of a Driving VLA to Class 8 Trucks](https://arxiv.org/abs/2609.38570v1)

- **arXiv**: `2609.38570v1`  |  **提交日期**: 2026-09-29
- **作者**: Satyajeet Das, Aaron Buxbaum, Niels Joubert, Gaurav S. Sukhatme

Class 8 trucks differ from passenger cars in geometry, dynamics, and maneuvering requirements. As a result, vision-language-action (VLA) models trained for passenger vehicles do not readily transfer to Class 8 trucks, particularly in unstructured scenarios such as accident scenes and construction zones. Rather than training a truck-driving VLA from scratch, we propose an adapt-then-steer strategy that adapts an off-the-shelf VLA to generate trajectories for Class-8 trucks in these challenging scenarios. In the adapt stage, we use NVIDIA's Alpamayo 1.5 as the base model, fine-tuning only its…

---

### [Memorize, Adapt, Ignore: Diagnosing Robot Learning Mechanisms under Training Data Variation](https://arxiv.org/abs/2609.38401v1)

- **arXiv**: `2609.38401v1`  |  **提交日期**: 2026-09-29
- **作者**: Ke Zhang, Danica J. Sutherland, Chao Liu

Training data variation, whether through designing a domain randomization (DR) scheme in simulation or curating demonstrations for imitation learning, is a primary lever for improving the robustness of robotic manipulation policies. Yet its underlying mechanisms remain poorly understood, and practitioners typically select randomization parameters through expensive trial and error. We investigate these mechanisms through a series of case studies, randomizing object size, color, and type as well as scene lighting and linguistic prompts across settings including pick-and-place RL in ManiSkill…

---

## 📅 2026-09-30

### [Rho: A Foundation for Efficiently Adaptable VLA Models](https://arxiv.org/abs/2609.38164v1)

- **arXiv**: `2609.38164v1`  |  **提交日期**: 2026-09-29
- **作者**:  Rho Team, Simran Bagaria, Daphne Chen, Dean Fortier, Jianlong Fu, Michael Harrison et al.

General-purpose physical AI models must combine broad visual and linguistic capabilities with precise control across robot embodiments and efficient adaptation to downstream tasks. We introduce Rho, a family of open-weights VLA models for bimanual manipulation designed for data-light task adaptation on 3 embodiments representative of dual-arm robots across research labs and the industry -- YAM Box, UR AI Trainer, and FR3 Duo. We systematically ablate Rho's action-expert architecture and training recipe, and show in controlled simulation and physical-robot experiments that embodiment…

---

### [MotorMind: Scaffolding General Vision Language Models for Zero-Shot Robot Manipulation](https://arxiv.org/abs/2609.38078v1)

- **arXiv**: `2609.38078v1`  |  **提交日期**: 2026-09-29
- **作者**: Bingxuan Li, Siqi Song, Yizhuo Wu, Jiarui Yao, Tong Zhang, Huan Zhang

Vision-language-action (VLA) models have advanced robotic manipulation, but their zero-shot generalization in new tasks and environments remains limited, and their reliance on specialized training keeps them from benefiting directly from rapidly advancing general-purpose vision-language models (VLMs). In parallel, recent agentic robotic systems leverage VLMs for high-level reasoning or coding agents for robot control, but often depend on extensive external models and tools, introducing additional complexity and cost. This motivates us to ask: Can a general-purpose VLM itself operate a robot…

---

### [WayFinder: Hierarchical Visual-Language-Action for Zero-Shot Waypoint Generation and Low-Level Kinematic Control](https://arxiv.org/abs/2609.37922v1)

- **arXiv**: `2609.37922v1`  |  **提交日期**: 2026-09-29
- **作者**: Timothy K Johnsen, Marco Levorato

Visual Language Action (VLA) models offer unprecedented generalization for autonomous robots; however, their real-world deployment is frequently bottlenecked by unreliable execution and the prohibitive computational cost of fine-tuning for specific robot embodiments and tasks. To bridge this gap, we propose WayFinder, an end-to-end, closed-loop hierarchical VLA framework that circumvents the need for fine-tuning by decoupling high-level task reasoning from low-level kinematic control. WayFinder utilizes a zero-shot, offboard Multimodal Large Language Model (MLLM) policy to process linguistic…

---

### [Explore, Execute, Evolve: A Skill Acquisition and Reuse Loop for Embodied Agents](https://arxiv.org/abs/2609.37810v1)

- **arXiv**: `2609.37810v1`  |  **提交日期**: 2026-09-29
- **作者**: Sicheng Xie, Yitong Chen, Haidong Cao, Shunlin Lu, Zuxuan Wu, Yu-Gang Jiang

Vision-language-action and world-action models have demonstrated impressive capabilities in robotics, yet generalization to unseen tasks remains challenging. More recently, general-purpose multimodal agents have shown great potential for zero-shot robotic task solving. However, they often incur high execution costs by reasoning and exploring the physical world from scratch. To reduce these costs, we introduce RoboSkill, a framework that connects skill acquisition and reuse through an Explore, Execute, Evolve loop. Within this loop, the agent explores to gather task-relevant information,…

---

### [Urgent Actions Go First: Urgency-Aware Denoising for Real-Time VLA Control](https://arxiv.org/abs/2609.37772v1)

- **arXiv**: `2609.37772v1`  |  **提交日期**: 2026-09-29
- **作者**: Zibo Wang, Haochen Han, Pengzhen Ren, Mingtong Dai, Fangming Liu

Diffusion and flow-matching Vision-Language-Action (VLA) policies generate action chunks through iterative denoising, incurring substantial inference latency that severely limits real-time robotic control. Existing acceleration methods treat an action chunk as a monolithic computational unit, ignoring a crucial physical reality of receding-horizon control: actions are generated jointly but consumed sequentially, resulting in inherently heterogeneous execution urgencies. We exploit this asymmetry to introduce Urgency-Aware Denoising (UAD), a novel inference-time framework that allocates…

---

### [Faster and Better? Benchmark Bugs and Design Limitations Distort the Evaluation of Vision-Language-Action Acceleration](https://arxiv.org/abs/2609.37771v1)

- **arXiv**: `2609.37771v1`  |  **提交日期**: 2026-09-29
- **作者**: Qiwei Chen, Kaijun Zhou, Nuohui Shi, Zhiyang Li, Yuxuan Feng, Jinyu Gu

Simulated manipulation benchmarks are the standard tool for evaluating vision-language-action (VLA) policies and the acceleration methods that reduce their inference latency for on-robot deployment. On these benchmarks, we observe that some training-free acceleration methods, which approximate the baseline policy's computation, achieve higher measured success rates than the baseline itself. Success rates alone cannot establish whether such gains come from better task execution or from evaluation flaws. We therefore investigate two kinds of benchmark flaws behind these gains: bugs, where the…

---

### [RawVLA: Embodied Neural Image Signal Processor For Robotic Manipulation](https://arxiv.org/abs/2609.37530v1)

- **arXiv**: `2609.37530v1`  |  **提交日期**: 2026-09-29
- **作者**: Shuhong Liu, Heng Zhou, Lingfeng Qian, Yuhao Fang, Xianbao Hou, Qianyu Zhou et al.

Vision-language-action (VLA) models typically operate on RGB images produced by a fixed camera image signal processor (ISP), leaving the imaging pipeline outside the learning and evaluation loop. We systematically examine the consequences of this overlooked design choice across five fundamental ISP dimensions: gain, sensor noise, chromatic response, tonal response, and bit depth. Our analysis reveals that RAW-to-RGB processing materially shapes both action prediction and manipulation success, with different ISP dimensions exerting substantially different effects. Guided by these findings, we…

---

### [Taming VLAs under Robot Execution Errors: Self-Compensation and Stress Testing](https://arxiv.org/abs/2609.37334v1)

- **arXiv**: `2609.37334v1`  |  **提交日期**: 2026-09-29
- **作者**: Sohyun Lee, Yoonjae Baek, Jaesang Won, Jinnyeong Kim, Kang Hyunwoo, Seung-Hwan Baek et al.

Vision-language-action (VLA) policies often fail when a robot's executed motion deviates from their commanded action. Such execution errors arise from the robot's mechanics and operating conditions, such as wear and payload changes. We propose self-compensating VLA, a deployment-time adaptation method that enables a VLA policy to pre-compensate for the robot's execution errors when generating commands. Without task rewards or labels, it updates the policy online using the residual between the action commanded by a VLA and the motion executed by the robot. To stress-test VLA robustness across…

---

### [Remember What You Did: Action-History Memory with Dual-Expert Denoising for Long-Horizon Vision-Language-Action Policies](https://arxiv.org/abs/2609.37307v1)

- **arXiv**: `2609.37307v1`  |  **提交日期**: 2026-09-29
- **作者**: Yaxin Zhao, Dianye Huang, Chenwei Wang, Chenguang Yang, Zhongliang Jiang

Vision-language-action (VLA) models have driven rapid progress in robotic manipulation, demonstrating strong fine-grained control and promising performance on long-horizon tasks. However, many existing VLAs lack explicit access to interaction history, making them vulnerable to perceptual aliasing: similar current observations and robot states at different task stages may induce action ambiguity and lower success rate. Existing methods incorporate temporal or progress cues through feature conditioning, action-prior modification, or sampling guidance. However, methods that jointly fine-tune…

---

### [V-JEPA Policy: Building Effective World-Action Models on Predictive Visual Latents](https://arxiv.org/abs/2609.37250v1)

- **arXiv**: `2609.37250v1`  |  **提交日期**: 2026-09-29
- **作者**: Yang Zhang, Jiangyuan Zhao, Chenyou Fan, Jiayu Hu, Xiu Yuan, Chenjia Bai et al.

World-action models (WAMs) couple future visual-state prediction with action generation. By adapting video generators or image-editing models pretrained at scale, a prominent line of recent WAMs inherits both predictive knowledge and the models in which it was learned. We ask whether a predictive visual latent space induced by large-scale predictive pretraining can instead provide a sufficient foundation for effective WAM learning without inheriting a complete pretrained visual generative model. To answer this question, we introduce V-JEPA Policy, a simple framework that builds a WAM on the…

---

### [EgoHumanoid-V2: Human-to-Humanoid Transfer of Coordinated Whole-Body Skills for Loco-Manipulation](https://arxiv.org/abs/2609.37181v1)

- **arXiv**: `2609.37181v1`  |  **提交日期**: 2026-09-29
- **作者**: Jin Chen, Yiming Jiang, Chongyang Xu, Modi Shi, Shijia Peng, Li Chen et al.

Human demonstrations capture diverse scenes and rich whole-body skills without requiring robot teleoperation. Prior work on egocentric transfer has emphasized scene generalization in loco-manipulation under decoupled control, leaving direct transfer of coordinated whole-body skills less explored. We present EgoHumanoid-V2, the first egocentric human-to-humanoid skill transfer framework for coordinated whole-body loco-manipulation. At its core, coarse-to-fine action alignment combines kinematic reference correction with dynamics-aware refinement. It improves end-effector pose accuracy while…

---

### [Disentangling Spurious Correlations in Vision-Language-Action Models via Predicting Domain-Invariant Latent Lookahead](https://arxiv.org/abs/2609.37165v1)

- **arXiv**: `2609.37165v1`  |  **提交日期**: 2026-09-29
- **作者**: Junghyun Kim, Ngseo Kim, ChungWoo Lee, Seoyeon Lee, Woo-Jeong Baek, Adam Zhou et al.

Vision-Language-Action (VLA) models remain brittle under visual distribution shifts, often relying on spurious correlations tied to domain-specific factors rather than task-relevant structure. We propose Domain-Invariant Latent Lookahead (DILL), a representation-learning framework that mitigates shortcut learning in VLA policies. Our key idea is to supervise policies with domain-invariant future latents learned from domain-transformed trajectory data. A Task-Domain Encoder is trained with contrastive objectives and Gaussian disentanglement regularization to separate task-relevant structure…

---

### [ReF-HIL: Shaping the Critic around Human Action Neighborhoods for Efficient Human-in-the-Loop Reinforcement Learning](https://arxiv.org/abs/2609.37131v1)

- **arXiv**: `2609.37131v1`  |  **提交日期**: 2026-09-29
- **作者**: Shaoyin Luo, Song Wang, Shibo Xia, Tianle Zhang, Zhaowei Liang, Guanghui Shen et al.

Human-in-the-loop reinforcement learning (HIL-RL) offers a promising route to efficient training of robotic manipulation policies by combining autonomous learning with human demonstrations and online corrections. However, insufficient use of successful human experience in value learning prolongs costly real-world training, while persistent imitation penalties can limit value-driven policy improvement. To address these limitations, we propose ReF-HIL, an efficient HIL-RL framework that uses human guidance to accelerate the learning process. Human-Reference-Guided Value Shaping learns an…

---

### [Speed in the Blind Spot: An Interpretability Analysis of Dynamic Perception in VLMs for Autonomous Driving](https://arxiv.org/abs/2609.37046v1)

- **arXiv**: `2609.37046v1`  |  **提交日期**: 2026-09-29
- **作者**: Katharina Winter, Stefan Englmeier, Fabian B. Flohr

Vision-Language Models are increasingly used in autonomous-driving systems, yet their ability to recover dynamic physical state from visual input remains insufficiently characterized. We study velocity understanding as a controlled diagnostic across three tasks: surrounding-agent speed, current ego speed, and short-horizon future ego-speed proposal. On nuScenes, we evaluate open-weight general-purpose and PhysicalAI VLMs, together with the driving-oriented Alpamayo-1.5 Vision-Language-Action model, using multiple input and output formulations. We combine verbal evaluation with temporal…

---

### [Beyond Token Importance: Preserving Spatial Scaffolds for Efficient Vision-Language-Action Inference](https://arxiv.org/abs/2609.36967v1)

- **arXiv**: `2609.36967v1`  |  **提交日期**: 2026-09-29
- **作者**: Jiayu Chen, Shuyong Gao, Jingkai Jia, Xiaosheng Bu, Jiyuan Fu, Lingyi Hong et al.

Existing VLA pruning strategies primarily select individual visual tokens according to task-level semantic relevance, while overlooking the spatial information required for robotic manipulation. To examine this limitation, we construct a simple Stride baseline that uniformly samples tokens along the flattened one-dimensional visual sequence, representing a purely geometric pruning strategy. Surprisingly, Stride outperforms semantic pruning and random pruning at certain pruning ratios, but collapses when the token budget is only slightly reduced. We characterize this phenomenon through the…

---

### [VLALight: A Vision-Language-Action Model for Traffic Signal Control](https://arxiv.org/abs/2609.36934v1)

- **arXiv**: `2609.36934v1`  |  **提交日期**: 2026-09-29
- **作者**: Pan Zhang, Siqi Lai, Kemu Dong, Hao Liu

Traffic signal control (TSC) is essential for improving urban mobility and reducing congestion. Although roadside cameras are widely deployed at signalized intersections and provide rich visual observations of evolving traffic, existing TSC methods typically rely on manually engineered traffic states or separate perception modules, creating a gap between physical observations and control decisions. We present VLALight, the first vision-language-action (VLA) model for end-to-end traffic signal control from multi-view roadside videos. VLALight directly maps visual observations to coordinated…

---

### [ComManip: Overfitting Manipulation Policies to Comfortable Regions](https://arxiv.org/abs/2609.36928v1)

- **arXiv**: `2609.36928v1`  |  **提交日期**: 2026-09-29
- **作者**: Yidan Lai, Xinyi Chen, Shuquan Man, Huiping Zhuang

Training robot manipulation policies relies on costly robot demonstrations, making large-scale data collection impractical. Meanwhile, to improve policy generalization, existing approaches seek greater diversity in visual observations by varying object placements, viewpoints, and robot configurations during data collection. However, under a limited demonstration budget, this strategy forces the policy to model diverse visual observations, providing insufficient supervision to learn reliable observation-action correspondences under similar local conditions. Our study reveals that policies…

---

### [AeroManip-VLA: Scalable Vision-Language-Action Learning for Aerial Manipulation with RL-Generated Demonstrations](https://arxiv.org/abs/2609.36915v1)

- **arXiv**: `2609.36915v1`  |  **提交日期**: 2026-09-29
- **作者**: Rui Huang, Yanlin Mu, Lidong Li, Yucong Wang, Zichen Yan, Lin Zhao

Aerial manipulators extend robotic manipulation into 3D workspaces that are difficult for ground-based robots to access, creating new opportunities for general-purpose manipulation. However, extending Vision-Language-Action (VLA) models to aerial robots introduces distinct challenges due to the tight coupling between manipulation and flight, continuously changing observations, and safety-critical physical interactions. These challenges demand diverse training data and systematic policy evaluation, yet collecting demonstrations and evaluating policies directly on physical aerial platforms are…

---

### [LexiconVLA: Learning Reusable Atomic Action Codebooks for Unseen Tasks](https://arxiv.org/abs/2609.36774v1)

- **arXiv**: `2609.36774v1`  |  **提交日期**: 2026-09-29
- **作者**: Zeming Wei, Jianheng Ye, Xinshuai Song, Sirui Chen, Yang Liu, Liang Lin

Vision-language-action (VLA) models struggle to reuse recurring interactions in unseen tasks. Our diagnostic study reveals that reliable task completion does not imply consistent execution of constituent atomic actions across task contexts. We present LexiconVLA, a retrievable atomic-action lexicon for cross-task reuse. Global and detail codebooks capture shared interaction structure and fine-grained execution variation, respectively, preserving both reusable patterns and execution details. Visual-Atomic Action Alignment couples trajectory reconstruction from visual state changes with visual…

---

### [T$^2$Mem: Learning Test-Time Memory for Robotics](https://arxiv.org/abs/2609.36720v1)

- **arXiv**: `2609.36720v1`  |  **提交日期**: 2026-09-29
- **作者**: Yize Liu, Huang Huang, Yining Hong, Zijian Du, Zhi Cao, Li Fei-Fei et al.

Memory-dependent robotic manipulation requires policies to use information that is no longer available in the current observation. Retaining history alone is insufficient: memory must preserve information that supports future actions. One challenge is whether a memory-free foundation model can learn to retain and use historical information from action demonstrations alone, without external memory support. We introduce T$^2$Mem, a framework that develops this capability within a pretrained vision-language-action policy, without external reasoning models or memory-specific annotations. T$^2$Mem…

---

### [Where Predictive Supervision Goes Shapes What VLA Policies Learn](https://arxiv.org/abs/2609.36645v1)

- **arXiv**: `2609.36645v1`  |  **提交日期**: 2026-09-29
- **作者**: Hanseul Kim, Jewon Yeom, Youngjoon Jeong, Minsoo Jo, Taesup Kim

Future prediction is increasingly used to improve vision-language-action (VLA) policies, based on the premise that anticipating scene evolution encourages representations useful for control. However, forecast quality alone does not establish that a policy has learned a better representation for action. This distinction matters under distribution shift, where successful control depends on preserving spatial state and likely scene change beyond familiar configurations. We study what determines whether predictive supervision improves the visual representation used by a VLA policy. Through…

---

### [Cooperative Multi-Agent Vision-Language-Action Models via Reinforced Fine Tuning](https://arxiv.org/abs/2609.36588v1)

- **arXiv**: `2609.36588v1`  |  **提交日期**: 2026-09-29
- **作者**: Ruixiao Xu, Wong Lik Hang Kenny, Zhiqian Liu, Jianing Guo, Hanxiao Li, Kejian Shi et al.

We study reinforcement learning (RL) methods for cooperative multi-agent Vision-Language-Action (VLA) models. This problem is challenging because VLAs are pretrained on large-scale single-agent data and therefore lack the fine-grained coordination skills required for inter-robot collaboration. Supervised fine-tuning (SFT) on multi-robot demonstrations partially bridges this gap, but its performance is bounded by the demonstration data and cannot improve from its own experience. We present a three-stage reinforced fine-tuning (RFT) pipeline for multi-agent VLAs. First, initialization-aware…

---

### [Reactive Real-Time Flow Policies via Asynchronous Distribution Alignment](https://arxiv.org/abs/2609.36540v1)

- **arXiv**: `2609.36540v1`  |  **提交日期**: 2026-09-29
- **作者**: Moritz Zoellner, Reece O'Mahoney, Ioannis Havoutis, Rohan Paleja

Generalist robot policies such as vision-language-action models (VLAs) have achieved remarkable generalization, but their inference delays can conflict with the demands of real-time control. Asynchronous execution avoids pauses between action chunks by predicting the next sequence of actions while the robot carries out the previous one. In this paper, we study whether asynchronous execution produces the same action distribution as the original VLA. We find that, for non-Markovian demonstrations, asynchronous execution can produce a fundamentally different action distribution, which can limit…

---

### [FineART: Fine-grained Annotated Robotic Trajectory Dataset and Vision-Language-Action Model for Bimanual Manipulation](https://arxiv.org/abs/2609.36416v1)

- **arXiv**: `2609.36416v1`  |  **提交日期**: 2026-09-29
- **作者**: Jade Choghari, Pepijn Kooijmans, Mansi Agarwal, Yusuf Umut Ciftci, Aseem Doriwala, Catherine Weaver et al.

Robots operating in real-world environments must execute complex, multi-step bimanual tasks over long horizons rather than single, isolated actions. Current manipulation datasets struggle to support this capability: although single-arm datasets reach hundreds of thousands of trajectories, they typically provide only one high-level instruction per episode while the rare bimanual effort that does label subtasks annotates only a fraction of its hours. We present FineART, a densely annotated bimanual manipulation dataset of 40,543 episodes, 1,718 hours, and 533,913 subtasks across 151 tasks. We…

---

### [StructRL: Online Structured Reinforcement Learning for Long-Horizon Vision-Language-Action Tasks](https://arxiv.org/abs/2609.36352v1)

- **arXiv**: `2609.36352v1`  |  **提交日期**: 2026-09-28
- **作者**: Ziyi Yin, Sangmin Woo, Kang Zhou, Sungyeon Kim, Aosong Feng, Haibo Ding et al.

Vision-language-action (VLA) models perform well on shorter-horizon manipulation tasks but still struggle with long-horizon tasks that require multiple dependent manipulations from a single command. Online reinforcement learning (RL) can improve these policies through environment interaction, yet many existing methods provide reward only after the complete task succeeds. However, such terminal supervision is sparse and does not distinguish early failures from rollouts that make substantial partial progress. We propose StructRL, an online RL framework that constructs structured intermediate…

---

### [Test-Time Adaptation of Manipulation Policies Under Actuator Degradation](https://arxiv.org/abs/2609.36182v1)

- **arXiv**: `2609.36182v1`  |  **提交日期**: 2026-09-28
- **作者**: Som Sagar, Ransalu Senanayake

Robot manipulation policies are usually trained under the assumption that a commanded action produces the same motion as it did during training even after hours of operation. Real hardware violates this assumption as the motors gradually heat up, current saturates near contact, voltage sags under load, thus the same policy action can produce a weaker, delayed, or noisier motion. These conditions are already measured by onboard telemetry, such as joint temperature, motor current, and supply voltage, yet this signal is typically used only for logging or safety checks rather than policy…

---

### [The Layer Mystery of VLA: An Information-Theoretical Analysis of VLA Latent Interface](https://arxiv.org/abs/2609.36118v1)

- **arXiv**: `2609.36118v1`  |  **提交日期**: 2026-09-28
- **作者**: Yuxiang Liu, Lizhi Yang, Fengze Xie, Aaron Ames, Yisong Yue

Vision-language-action (VLA) policies connect a pretrained vision-language backbone to an action head through a latent interface, but which backbone layers this interface should expose remains unclear. We study single-layer selection and multi-layer fusion for frozen backbones across three pretrained models and two manipulation benchmarks, LIBERO and CALVIN, with three policy-training seeds per configuration. Across three fusion mechanisms and three layer-subset strategies, 47 of 54 configurations underperform the best observed single-layer policy. Our stastical analysis further confirms that…

---

### [Zero-Shot Reactive Obstacle Avoidance for Generative Robot Policies](https://arxiv.org/abs/2609.35231v2)

- **arXiv**: `2609.35231v2`  |  **提交日期**: 2026-09-28
- **作者**: Weihang Guo, Lydia E. Kavraki

We propose NUDGE (Nudge Update via Differentiable GEometry), a training-free obstacle-avoidance procedure that can be incorporated in any robot policy based on diffusion or flow matching, including diffusion policies and vision-language-action models. Our work injects gradients from a signed distance field, a function returning each point's distance to the nearest obstacle, into the policy at inference time to steer it away from obstacles. It supports any common action parameterization, from absolute or relative joint poses to end-effector poses, through a differentiable joint-trajectory…

---

## 📅 2026-09-29

### [Humanoid Loco-Manipulation With Discrete VLA Model](https://arxiv.org/abs/2609.35709v1)

- **arXiv**: `2609.35709v1`  |  **提交日期**: 2026-09-28
- **作者**: Wenxin Shao, Siqi Chai, Kun Li, Kerou Zhang, Xinzhou Jiang, Wei Xu et al.

Vision-language-action (VLA) models using discrete action tokens have proven effective for controling robotic arms on manipulation tasks. For a humanoid, however, the whole-body action space -- legs, torso, arms, and hands -- is far higher-dimensional and heterogeneous, raising tokenization, training, and real-time inference challenges that the previous VLA models do not address. We present Holo-M, to our knowledge the first discrete VLA model for humanoid loco-manipulation that intrinsically exploits the language model by extending its vocabulary with action tokens. In this model, we devise…

---

### [Rethinking Causal Action Tokenization with Conditional Annealing in Flow Matching](https://arxiv.org/abs/2609.35469v1)

- **arXiv**: `2609.35469v1`  |  **提交日期**: 2026-09-28
- **作者**: Chenyu Zhang, Yuhang Cao, Daru Du, Yingxi Lu, Jing Shao, Ruoqu Chen et al.

Autoregressive Vision-Language-Action (VLA) models offer a scalable path to robot learning, yet existing action tokenizers treat tokenization as a compression problem, producing representations that are semantically misaligned with the autoregressive backbone. We propose CATok, a causal action tokenizer that reframes tokenization as a causally structured generative process. CATok introduces a conditional annealing mechanism that extracts action tokens by progressively annealing a flow-matching process: each token is conditioned on all preceding tokens and encodes the residual reconstruction…

---

### [Uni-VLaT: Whole-Body Tactile Adaptation of VLA Policies for Humanoid Loco-Manipulation](https://arxiv.org/abs/2609.35450v1)

- **arXiv**: `2609.35450v1`  |  **提交日期**: 2026-09-28
- **作者**: Zihao Wang, Shutong Liu, Siqi Zheng, Liu Cao, Ruoqi Chen, Rundong Liu et al.

Physical contact often determines how a humanoid should respond during loco-manipulation, yet vision and proprioception alone are often insufficient to characterize physical interaction, especially when the contact region is occluded. Unlike sparse force or torque measurements at predefined regions, distributed tactile sensing preserves spatially resolved contact patterns across the robot body. We therefore study how to integrate such whole-body tactile information into vision-language-action (VLA) policies for contact-rich control. Our approach, Uni-VLaT, introduces a tactile pathway whose…

---

### [Self-Evolving Coding Agents: From Digital Programs to Physical-World Intelligence](https://arxiv.org/abs/2609.35432v1)

- **arXiv**: `2609.35432v1`  |  **提交日期**: 2026-09-28
- **作者**: Hongcheng Gao, Jingjing Zhou, Zelin Zheng, Shijia Ge, Jay Zhu, Yazhe Wang et al.

Vision-language-action (VLA) and world-action (WAM) models map observations and instructions directly to robot actions. This directness ties a policy to training: minor layout or viewpoint changes cause failure, and instructions generalize poorly. The root cause lies in representation: task requirements, conditions, progress, and failure recovery are implicitly encoded in action sequences, making them difficult to inspect or revise. Digital coding agents offer a precedent: LLMs call tools, verify results, and revise from feedback as executable code. The same working pattern of explicit state,…

---

### [Spatial Grafting: Grounding 3D Features for Flow-Matching Robot Policies](https://arxiv.org/abs/2609.35249v1)

- **arXiv**: `2609.35249v1`  |  **提交日期**: 2026-09-28
- **作者**: Dingsheng Liu, Yangzheng Wu, Mahboubeh Asadi, Zhiyuan Li, Jinbang Huang, Yixin Xiao et al.

Pretrained robot manipulation policies such as vision-language-action models (VLAs) or world-action models (WAMs) leave interaction-relevant metric geometry implicit. Recent breakthroughs in spatial reconstruction can supply the necessary geometry reliably, but their features describe local shape without stating where it lies with respect to the robot. How best to deliver these features to a pretrained policy remains unresolved. We propose Spatial Grafting, a versatile, lightweight spatial module that binds frozen reconstruction features to metric, robot-relative geometry. Spatial Grafting…

---

### [Zero-Shot Reactive Obstacle Avoidance for Generative Robot Policies](https://arxiv.org/abs/2609.35231v1)

- **arXiv**: `2609.35231v1`  |  **提交日期**: 2026-09-28
- **作者**: Weihang Guo, Lydia E. Kavraki

We propose NUDGE (Nudge Update via Differentiable GEometry), a training-free obstacle-avoidance procedure that can be incorporated in any robot policy based on diffusion or flow matching, including diffusion policies and vision-language-action models. Our work injects gradients from a signed distance field, a function returning each point's distance to the nearest obstacle, into the policy at inference time to steer it away from obstacles. It supports any common action parameterization, from absolute or relative joint poses to end-effector poses, through a differentiable joint-trajectory…

---

### [RefineDrive: Reliable Failure-Guided Learning for Vision-Language-Action Driving](https://arxiv.org/abs/2609.35078v1)

- **arXiv**: `2609.35078v1`  |  **提交日期**: 2026-09-28
- **作者**: Zhe Sun, Ziyi Luo, Yehao Lu, Lei Zhou, Xi Li

Vision-Language-Action (VLA) models for autonomous driving rely heavily on successful expert demonstrations, leaving model-specific failures underexploited. Learning from these failures is hindered by unreliable diagnoses, poorly matched correction targets, and coarse rewards. We propose RefineDrive, a failure-guided post-training framework that learns from self-generated failures through targeted supervision and safety-aware reinforcement learning. Reliable Diagnosis derives structured, verifiable feedback on collisions and drivable-area violations directly from simulator states.…

---

### [Do Not Cut When Uncertain: Rejectable and Calibrated Decision Heads for VLA Policies in Robotic Harvesting](https://arxiv.org/abs/2609.35039v1)

- **arXiv**: `2609.35039v1`  |  **提交日期**: 2026-09-28
- **作者**: Heng Zhang

Vision-Language-Action (VLA) policies trained with behavior cloning or flow matching are optimized to output an action trajectory, but they cannot express "I don't know" or "I should not act." In robotic harvesting, occlusion makes single-frame decisions fundamentally ambiguous: identical pixels can correspond either to a cuttable stem or to no stem at all. Existing VLAs are forced to commit, leading to high-confidence errors with irreversible consequences. We argue that the failure mode of a VLA is determined not by backbone scale but by its output interface. We propose Rejectable and…

---

### [Learning to Act under Visual Interruptions with Vision-Language-Action Models](https://arxiv.org/abs/2609.35003v1)

- **arXiv**: `2609.35003v1`  |  **提交日期**: 2026-09-28
- **作者**: Mingle Jiang, Rui Xu, Yunke Wang, Chang Xu

Vision-language-action (VLA) models have demonstrated strong capabilities in robotic manipulation, but they are typically developed and evaluated with all camera streams available throughout task execution. When a camera stops delivering frames during task execution, the policy must continue acting without access to subsequent observations from the missing view. Despite its practical importance, how such interruptions affect closed-loop manipulation remains insufficiently understood. To investigate this problem, we introduce MAIL-Bench, a benchmark that evaluates visual interruptions with VLA…

---

### [ActionUNet: Improving Robustness of VLA Models with Efficient Multi-scale Fine-tuning](https://arxiv.org/abs/2609.34982v1)

- **arXiv**: `2609.34982v1`  |  **提交日期**: 2026-09-28
- **作者**: Di Zhu, Ziheng Yan, Fang Wan

Vision-Language-Action (VLA) models have shown great promise for robotic manipulation by mapping multi-modal semantics to physical actions. However, this mapping inherently struggles to align these coarse-grained semantics with fine-grained temporal execution. It leaves VLA models with limited generalization and insufficient robustness in cluttered environments. To overcome this issue, we propose ActionUNet, an efficient multi-scale fine-tuning framework that enhances pre-trained VLA models with minimal computational cost. ActionUNet first constructs a lightweight temporal U-Net within the…

---

### [RoboFL: Federated Expert Assembly for World Action Models](https://arxiv.org/abs/2609.34968v1)

- **arXiv**: `2609.34968v1`  |  **提交日期**: 2026-09-28
- **作者**: Rongyu Zhang, Ruizhi Fan, Yunfan Lou, Hengyu Fang, Shenli Zheng, Chenrui Wu et al.

Vision-language-action and world-action models are increasingly popular, yet remain bottlenecked by physical interaction data that is scarce, institutionally siloed, and task-heterogeneous. A natural federated solution is to let each client adapt a shared foundation model through parameter-efficient fine-tuning, avoiding the exchange of full-model updates. However, federating these adapters is nontrivial, as naive aggregation can entangle incompatible updates, while incorporating MoE-style routing into federated aggregation may dilute specialization and destabilize expert selection. We…

---

### [Adjoint Guidance Flow: Amortized Critic Guidance for VLA Policies](https://arxiv.org/abs/2609.34944v1)

- **arXiv**: `2609.34944v1`  |  **提交日期**: 2026-09-28
- **作者**: Jeongsol Kim, Youngjun Jun, Kyumin Choi, Youngmin Kim, Seonghyun Jin, Sunwoo Park et al.

Flow-based Vision-Language-Action (VLA) policies are typically trained by behavior cloning and thus do not explicitly optimize long-term task return. Critic guidance steers generation toward higher-value actions, but existing methods differentiate the critic through a one-step surrogate of the sampler and back-propagate a critic ensemble at every flow step. In contrast, here we propose Adjoint Guidance Flow (AGF), which amortizes trajectory-aware critic guidance into a lightweight guidance network while preserving the pretrained VLA policy. Specifically, we formulate critic-guided flow…

---

### [Don't Throw Away the Tail: Action Upcycling for Policy Acceleration](https://arxiv.org/abs/2609.34911v1)

- **arXiv**: `2609.34911v1`  |  **提交日期**: 2026-09-28
- **作者**: Taesung Kwon, Jangho Park, Sunwoo Park, Youngmin Kim, Seonghyun Jin, Youngjun Jun et al.

Modern robot policies predict a chunk of future actions from a single observation, execute only a prefix, and discard the rest before replanning. Choosing the length of this prefix, the execution horizon, poses a trade-off between reactivity and efficiency. A short horizon keeps the policy reactive to the environment, but requires frequent policy calls. Recent test-time methods adaptively select the horizon for each chunk, but they either read model internals, where the signal must be chosen for each architecture, or draw extra samples, which adds cost. We propose *Action Upcycling*, a…

---

### [D$^2$-VLA: Dual-Memory Dual-Frequency Vision-Language-Action Model For Long Dynamic Manipulation](https://arxiv.org/abs/2609.34792v1)

- **arXiv**: `2609.34792v1`  |  **提交日期**: 2026-09-28
- **作者**: Zijian Ye, Chengqi Wei, Wei Huang, Anlin Zheng, Chunyu Zou, Liangyu Wu et al.

Long-horizon manipulation requires robots to remember cues that are no longer in view while responding to moving objects. Yet vision-language-action (VLA) policies often rely on the latest observation, and refreshing their visual context typically requires another costly vision-language model (VLM) pass. We present D$^2$-VLA, which combines dual memory and dual-frequency control at the KV-cache interface of a pretrained VLA. D$^2$-VLA uses block-wise causal KV caching to encode observations incrementally and, guided by distinct temporal attention patterns, constructs separate historical KV…

---

### [Unified Trajectory Matching Policy Optimization: Diverse T2I Generation and VLA Generalization](https://arxiv.org/abs/2609.34688v1)

- **arXiv**: `2609.34688v1`  |  **提交日期**: 2026-09-28
- **作者**: Zhiyuan Ma, Jiaming Li, Lingzhen Li, Yu Liu, Xuekai Zhu, Dingkang Liang et al.

Reward-maximizing reinforcement learning (RL) is widely used to post-train stochastic diffusion and flow policies for text-to-image (T2I) generation. However, reward-maximizing RL causes policy mode collapse even under reference KL or entropy regularization, reducing the policy to a single high-reward mode. In T2I, this produces similar images and reward hacking. When extended to vision-language-action (VLA) models, the same collapse removes alternative successful strategies and weakens task and scene generalization. To address this limitation, we introduce Unified Trajectory Matching Policy…

---

### [Natural State-Prediction Accuracy can Hide Weak Controlled Responsiveness in VLA Readouts](https://arxiv.org/abs/2609.34684v1)

- **arXiv**: `2609.34684v1`  |  **提交日期**: 2026-09-28
- **作者**: Hyungjoon Kim, Wonbin Son, Mi Young Lee, Jun Young Lee, Seungmin Rho

Accurately decoding object states from the internal representations of vision-language-action (VLA) models does not establish that the predictions respond faithfully to changes in the target physical state. In natural observations, object state, robot configuration, occlusion, and task progress vary together, allowing contextual cues to contribute to prediction. In this paper, we introduce an evaluation framework that separates prediction accuracy, target-state responsiveness, and context stability using physically validated observations that cross target coordinates with robot contexts. We…

---

### [The Low-Rank Structure of VLA Reinforcement Learning](https://arxiv.org/abs/2609.34599v1)

- **arXiv**: `2609.34599v1`  |  **提交日期**: 2026-09-28
- **作者**: Minjae Oh, Yoonah Park, Jongwon Lim, Yohan Jo

Reinforcement learning (RL) is increasingly used to post-train vision-language-action (VLA) models, yet how RL reshapes these policies remains poorly understood. We find that RL across widely used flow-based VLA models, including $π_{0.5}$ and GR00T~N1.5/N1.6, on LIBERO, ManiSkill, MetaWorld, and CALVIN induces substantially lower-rank parameter updates that are highly concentrated in the action expert's Timestep Modules, a small and previously overlooked component. Through systematic module-replacement experiments, we further show that these modules capture a disproportionate share of the…

---

### [Brain-Conditioned Action Policies for Neural Motor Decoding](https://arxiv.org/abs/2609.34561v1)

- **arXiv**: `2609.34561v1`  |  **提交日期**: 2026-09-28
- **作者**: Luyao Jin, Running Zhao, Huan Zhao, Vincent C. K. Cheung, Wei-Hsin Liao

Motor brain-computer interfaces (BCIs) aim to decode motor intention, enabling people with paralysis to control external devices. Neural motor decoding typically learns task-specific mappings from neural activity to kinematics, yet remains constrained by scarce paired neural-action data. We propose BrainVLA, a framework that enables neural motor decoding by drawing on a pretrained vision-language-action (VLA) model through language-mediated alignment. BrainVLA mitigates reliance on scarce paired neural-action data by leveraging VLA policies. We first construct VLA-compatible datasets…

---

### [Where Memory Belongs: Ledger, an Object Ledger for Memory-Augmented VLAs](https://arxiv.org/abs/2609.34554v1)

- **arXiv**: `2609.34554v1`  |  **提交日期**: 2026-09-28
- **作者**: Tanguy Dieudonné, Jack B. Jedlicki, Heng Yang

Memory is essential for long-horizon, partially observed robotic manipulation: a robot must remember which object was placed in a drawer, whose cup it moved, or how many action cycles have elapsed. Recent vision-language-action (VLA) models embed memory directly inside the policy, but benchmarks show no single in-policy mechanism covers all spatio-temporal dimensions, trailing oracle methods by a wide margin. We argue that memory type dictates where memory should reside: short-term perceptual memory (repetition, timing, retracing) belongs inside the policy, while long-term object memory…

---

### [Gaze Prompts: Temporally Dense Human Attention for Vision-Language-Action Fine-Tuning](https://arxiv.org/abs/2609.34550v1)

- **arXiv**: `2609.34550v1`  |  **提交日期**: 2026-09-28
- **作者**: Yihan Zhou, Rui Yan, Mingcong Li, Zheyuan Huang, Xu Yang, Xueyang Guo et al.

Vision-Language-Action (VLA) fine-tuning pairs images with actions at every step, yet typically provides only a task-level language instruction, leaving moment-to-moment visual relevance implicit. We introduce \emph{eye-tracker-supervised gaze prompting}, which uses gaze recorded during VR teleoperation to provide frame-level visual guidance for VLA fine-tuning. During training, recorded gaze locations are rendered as crosshairs on the robot's head-camera images. At deployment, a lightweight predictor estimates gaze locations from recent images and the instruction, supplying the same type of…

---

### [Alignment-Guided Flow Transformer for Efficient Vision-Language-Action Policy Learning](https://arxiv.org/abs/2609.34467v1)

- **arXiv**: `2609.34467v1`  |  **提交日期**: 2026-09-28
- **作者**: Shengchao Hu, Peng Wang, Qiyang Zhou, Guodong Zheng, Yuqi Huang, Li Shen et al.

Recent advances in Vision-Language-Action (VLA) models point toward general-purpose robotic intelligence by unifying perception, instruction, and control. Despite impressive progress, existing VLA models often adapt poorly due to \emph{tri-modal misalignment} among vision, language, and action, which weakens action grounding and hurts generalization and fine-tuning efficiency. In this work, we present Alignment-Guided Flow Transformer (AGFT), a novel framework that explicitly enforces tri-modal alignment through a dedicated alignment loss, bridging the representational gap across modalities…

---

### [CAR-VLA: Complexity-Aware and Risk-Adaptive Reasoning for Autonomous Driving](https://arxiv.org/abs/2609.34387v1)

- **arXiv**: `2609.34387v1`  |  **提交日期**: 2026-09-28
- **作者**: Xiaolei Chen, Zhuolin He, Yuxuan Liang, Xu Li, Haotian Chen, Shi Fan et al.

Existing adaptive reasoning methods for driving Vision-Language-Action (VLA) models primarily focus on whether to reason, overlooking how reasoning should differ across driving situations. Our key insight is that while scene complexity informs reasoning depth, dynamic risk is equally critical for deciding how to reason in time-critical situations. We therefore propose CAR-VLA, a unified driving VLA model that jointly considers scene complexity and dynamic risk to guide reasoning depth, urgency, and focus. CAR-VLA maps four complexity--risk categories to three reasoning modes: \textit{Fast…

---

### [RoboIRGBench: Benchmarking Implicit Referential Grounding in Vision-Language-Action Models](https://arxiv.org/abs/2609.34384v1)

- **arXiv**: `2609.34384v1`  |  **提交日期**: 2026-09-28
- **作者**: Aernaer Akelijiang, Jiannan Li, Zhineng Chen, Jingjing Chen, Bin Zhu

Vision-Language-Action (VLA) models have shown strong capabilities in robotic manipulation, yet existing benchmarks typically assume that task-relevant information is explicitly specified in the instruction. In practice, however, humans frequently refer to objects, quantities, and relations implicitly, requiring robots to recover the intended target from linguistic and perceptual context. We study this capability as Implicit Referential Grounding (IRG) and introduce RoboIRG-Bench, a manipulation benchmark designed to systematically evaluate it. Built upon RoboMME, RoboIRG-Bench contains 40…

---

### [Text-Vision Synergistic Token Caching: A Training-Free Framework for Efficient Vision-Language-Action Inference](https://arxiv.org/abs/2609.34319v1)

- **arXiv**: `2609.34319v1`  |  **提交日期**: 2026-09-28
- **作者**: Qianer Li, Chengjie Zhang, Jingwen Chen, Zanjia Tong, Jiyuan Zhang, Hong Zhang

Vision-Language-Action (VLA) models enable generalizable robotic control but remain computationally expensive. Token caching provides a training-free, plug-and-play acceleration alternative. However, existing VLA caching does not fully exploit a key inductive bias of VLA models: text-vision synergy, wherein textual semantics guide the precise visual grounding of task-relevant regions. In particular, existing designs insufficiently account for head-wise reliability in attention aggregation and layer-wise stability in cache reuse. To address this, we propose Text-Vision Synergistic Token…

---

### [mmHRI: Towards Privacy-Preserving Human-Robot Interaction with Millimeter-Wave Radar](https://arxiv.org/abs/2609.34220v1)

- **arXiv**: `2609.34220v1`  |  **提交日期**: 2026-09-28
- **作者**: Junqiao Fan, Yuxuan Hu, Bofan Lyu, Yanshuo Lu, Pengfei Liu, Jiarui Zhang et al.

Assistive robots increasingly operate in many human-centered environments and perform various human-robot interaction (HRI) tasks, such as object delivery. However, most existing HRI systems rely on RGB cameras that continuously observe humans to respond to non-verbal commands, such as hand gestures. This raises privacy concerns in privacy- critical environments, such as hospital wards or restaurants, where direct camera observation of humans is restricted. To develop privacy-preserving HRI, we leverage millimeter-wave (mmWave) radar, which can sense human motion through privacy barriers…

---

### [WorldGuide: Learning Success-Failure Boundaries in Latent World Models for Vision-Language-Action Policies](https://arxiv.org/abs/2609.34206v1)

- **arXiv**: `2609.34206v1`  |  **提交日期**: 2026-09-28
- **作者**: Lin Liu, Lu Zhang, Ziying Song, Wu Yang, Yuzheng Zhuang, Yunzhi Zhuge et al.

Latent world models offer a promising way to improve Vision-Language-Action policies by capturing the consequences of actions. However, models trained primarily on expert demonstrations have limited exposure to failure outcomes and may struggle to distinguish visually similar successful and failed interactions. We propose \textbf{WorldGuide}, a framework that learns these distinctions in latent space and uses them to guide policy training. WorldGuide combines predictive pretraining on successful and failed trajectories with contrastive learning on matched success--failure pairs. The learned…

---

### [FailPatch: Failure Residual Patching for Vision-Language-Action Models](https://arxiv.org/abs/2609.34175v1)

- **arXiv**: `2609.34175v1`  |  **提交日期**: 2026-09-28
- **作者**: Peng Yu, Jiacheng Wang, Ziheng Zhang, Xuchong Zhang, Baoting Li, Zhuoyuan Yu et al.

Vision-Language-Action (VLA) policies are typically adapted using successful demonstrations, which provide direct action supervision but rarely cover failure-prone states. Deployment failures expose these states, yet lack the corrective actions needed for conventional supervised learning. We propose FailPatch, a failure-driven residual patching framework that decouples action supervision from execution-reliability supervision. Successful demonstrations ground how the policy should act, while deployment trajectories indicate when its behavior becomes unreliable. We further observe that action…

---

### [RAVEL: Asynchronous Rolling Inference for Flow-Based Vision-Language-Action Models](https://arxiv.org/abs/2609.34170v1)

- **arXiv**: `2609.34170v1`  |  **提交日期**: 2026-09-28
- **作者**: Yuhan Chen, Ke Yu, Pengfei Liu, Shuxun Wang, Yi Yang, Linchao Zhu

Flow-based vision-language-action (VLA) models are highly effective for generalist robot manipulation, yet their reliance on computationally expensive VLM encoding and multi-step iterative action generation imposes a significant latency bottleneck. The resulting inference latency makes it difficult for robots to respond quickly, especially in dynamic environments. We address this limitation with RAVEL (Rolling Asynchronous VLA Enabling Low-Latency Control), an asynchronous inference framework that addresses the computational bottlenecks of both the VLM backbone and the action expert. To…

---

### [Quantile Head for Vision-Language-Action Models](https://arxiv.org/abs/2609.34061v1)

- **arXiv**: `2609.34061v1`  |  **提交日期**: 2026-09-28
- **作者**: Xuan Wang, Yinan Wu, Haoran Duan, Jungong Han

Vision-Language-Action (VLA) models integrate pretrained Vision-Language Models (VLMs) with action heads for robot control. Common action heads have distinct limitations: point regression provides only a point estimate of the action distribution, while standard flow-matching samplers require costly iterative sampling. To address these limitations, we unify regression and flow matching under a shared objective and extend it to derive a quantile objective. This quantile objective guides the design of our Quantile Head, which predicts a median and positive gaps to form ordered marginal action…

---

### [Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation](https://arxiv.org/abs/2609.33872v1)

- **arXiv**: `2609.33872v1`  |  **提交日期**: 2026-09-27
- **作者**: Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang et al.

Robotic manipulation policies are advancing rapidly with increasing reliance on vision-language models for end-to-end decision making. However, reliable deployment remains challenging because many policies lack explicit mechanisms for predicting task outcomes and evaluating whether generated actions will achieve desired final states, causing execution errors to accumulate during long-horizon manipulation. We present Robot-GST, a geometry-aware spatio-temporal behaviour representation and evaluation framework that constructs a Gaussian-SAM robotic environment for real-to-sim policy…

---

### [Principal Steering Subspaces for Online Adaptation of Frozen Generative Robot Policies](https://arxiv.org/abs/2609.33765v1)

- **arXiv**: `2609.33765v1`  |  **提交日期**: 2026-09-27
- **作者**: Jialeng Ni, Nathan Zhao, Kunpeng Song

Generative robot policies provide expressive behavior priors, but updating a large diffusion or flow-matching model through online interaction is costly. Latent-space reinforcement learning avoids updating the pretrained generator by controlling its initial sampling noise, yet high-dimensional noise can have strongly anisotropic effects on decoded actions. We introduce Principal Steering Subspaces (PSS), a forward-query interface that constructs a fixed low-dimensional control basis from finite-difference decoder responses. Soft Actor-Critic controls the leading response directions, while the…

---

### [Does Adversarial Training Improve Generalization in Multi-View VLAs? Revealing and Mitigating View Collapse](https://arxiv.org/abs/2609.33707v1)

- **arXiv**: `2609.33707v1`  |  **提交日期**: 2026-09-27
- **作者**: Futa Waseda, Shuhei Kurita, Isao Echizen

Vision-language-action (VLA) models adapt pretrained vision-language models (VLMs) for closed-loop robot control, transferring their perceptual and semantic capabilities to action prediction. Despite strong in-distribution performance, however, VLAs often degrade under deployment shifts. Adversarial training (AT) offers a model-adaptive approach to robustness without explicitly anticipating individual shifts, but its effect on natural distribution-shift generalization in multi-view VLAs remains unclear. We study this question using a multi-view VLA directly adapted from a pretrained VLM and…

---

### [SLIP-VLA: Single-Step Latent Imagination for Policy Learning in Vision-Language-Action Models](https://arxiv.org/abs/2609.33575v1)

- **arXiv**: `2609.33575v1`  |  **提交日期**: 2026-09-27
- **作者**: Tianfu Li, Haoxuan Xu, Wenbo Chen, Haitian Li, Changchuan Yang, Xinhu Zheng et al.

Vision-Language-Action models are increasingly effective for robotic manipulation, yet most predict actions directly from current observations without explicitly modeling future scene evolution. Recent methods introduce future prediction to improve action generation, but dense future modeling often requires expensive iterative denoising, while one-step alternatives can underperform their multi-step counterparts. To reconcile efficient future modeling with strong action performance, we present SLIP-VLA, a policy learning framework that equips VLA models with a Single-Step Latent Imagination…

---

### [Resolving State-Representation Mismatch: State-Space Visual Reasoning for Open-Loop VLA Planning](https://arxiv.org/abs/2609.33412v1)

- **arXiv**: `2609.33412v1`  |  **提交日期**: 2026-09-27
- **作者**: Junhao Xiao, Haoxiang Zhao, Menghao Fang, Jinkui Zhang, Jinghan Yu, Xinyu Huang et al.

Despite rapid progress in vision-language-action (VLA) models, existing reasoning paradigms still face a fundamental \emph{state-representation mismatch} in open-loop planning. Given only an initial observation, models must internally simulate action-conditioned state transitions, whereas text-, pixel-, and latent-space reasoning can suffer from lossy spatial compression, error-accumulating visual generation, and bypass of intermediate latent tokens, respectively, undermining reliable long-horizon planning. We propose \textbf{State-Space Visual Reasoning} (SSVR), which decouples static visual…

---

### [Recursive Harness Distillation across Agents for Robot Manipulation](https://arxiv.org/abs/2609.33378v1)

- **arXiv**: `2609.33378v1`  |  **提交日期**: 2026-09-27
- **作者**: Seungyeon Kim, Junhoo Lee, Minkyu Kim, Baekseung Kim, Nojun Kwak

A central goal in robotics is to enable manipulation across changing tasks and environments. Vision-language-action (VLA) models provide broad manipulation capabilities but can struggle when execution requires diagnosing failures and adapting behavior. Strong agents can discover effective interventions through interaction with these policies. We propose Recursive Harness Distillation to accumulate this experience as reusable guidance across agents. A strong agent distills its experience into a playbook for a light agent, then recursively refines the playbook using the light agent's execution…

---

### [ActionGround: Training-Free Runtime Refinement of Frozen VLA Policies](https://arxiv.org/abs/2609.33256v1)

- **arXiv**: `2609.33256v1`  |  **提交日期**: 2026-09-27
- **作者**: Namai Chandra, Madhur Thareja, Shriram Damodaran, Addison Lin Wang

Vision-Language-Action (VLA) models map visual observations and language instructions directly to robot actions, but they do not explicitly represent the phase structure of manipulation tasks or the rigid-body dynamics governing execution. We present ActionGround, a neuro-symbolic, training-free runtime layer that wraps a frozen VLA policy without retraining, fine-tuning, or weight access, adding less than 1 ms of overhead per control step. A symbolic phase-aware finite-state machine identifies the manipulation phase (approach, grasp, transport, or place) and applies a phase-specific…

---

### [TAO-DA: Towards Autonomous Operation--A Dual-Arm Vision-Language-Action Model for Coordinated Manipulation](https://arxiv.org/abs/2609.33197v1)

- **arXiv**: `2609.33197v1`  |  **提交日期**: 2026-09-27
- **作者**: Yongsheng Zhao, Han Gao, Baoping Cheng, Jingyao Tang, Dian Zhou, Deng Liang et al.

Vision-Language-Action (VLA) models provide a unified framework for grounding high-level semantic information into low-level robot actions, enabling scalable robotic manipulation across diverse tasks. However, existing VLA models lack explicit mechanisms to disentangle the states and intents of the two arms, leading to unintended cross-arm interference that degrades task execution success. To address this issue, we propose a symmetric Dual-Arm Expert (DAE) architecture built upon a shared Vision-Language Model (VLM) backbone with decoupled, arm-specific expert towers. Expert selection is…

---

### [TimelyDAgger: Timing-Aware Expert Querying for VLA Policy Improvement](https://arxiv.org/abs/2609.33157v1)

- **arXiv**: `2609.33157v1`  |  **提交日期**: 2026-09-27
- **作者**: Zhixuan Zhao, Peiyan Li, Enhao Zhang, Yueran Tao, Hao Wang, Chenghao Yue et al.

DAgger improves robot policies by aggregating expert supervision from states visited during policy execution. Robot-gated DAgger automates expert queries, allowing the robot to decide when to request expert takeover. While existing gates emphasize detecting the need for assistance, takeover timing also shapes the content of these demonstrations and their value for policy learning. We propose TimelyDAgger, combining Bridge-PCA monitoring of internal vision-language-action (VLA) features with Feedback-guided Threshold Adaptation based on expert behavior to improve takeover timing. We introduce…

---

## 📅 2026-09-16

### [FluxVLA Engine: A One-Stop VLA Engineering Platform for Embodied Intelligence](https://arxiv.org/abs/2609.17210v1)

- **arXiv**: `2609.17210v1`  |  **提交日期**: 2026-09-15
- **作者**: Yinhao Li, Weixin Mao, Zihan Lan, Jikun Rong, Qirui Hu, Yiming Zhang et al.

Vision-language-action (VLA) models, world-action models (WAMs), and offline reinforcement learning methods are rapidly expanding the design space of embodied policies, yet turning these algorithms into reliable robot systems remains constrained by fragmented data formats, training stacks, evaluation protocols, inference runtimes, and embodiment-specific interfaces. We present $\mathrm{FluxVLA}$ Engine, an open, configuration-driven platform that turns heterogeneous embodied-policy components into a reproducible data-to-deployment workflow. Rather than introducing another policy model,…

---

### [Intrinsic Robot Rewarding: Reusing VLA Representations for Autonomous Evaluation and Policy Improvement](https://arxiv.org/abs/2609.17115v1)

- **arXiv**: `2609.17115v1`  |  **提交日期**: 2026-09-15
- **作者**: Tobias Schaffer, Mohab Elkhayat, Daniela Nicklas, Mustafa Almohamad, Elham Al-Fuqara

Vision-language-action (VLA) systems already bring together two valuable resources for robot learning: rich visual representations and demonstrations of successful task execution. Intrinsic Robot Rewarding (IRR) proposes to use these resources for a second, complementary purpose: evaluating the robot's own outcomes and providing feedback for policy improvement. Successful demonstration endpoints define task-specific references, and the policy's frozen visual encoder provides the feature space in which new outcomes are assessed. The core reward mechanism adds a reference bank and a scoring…

---

### [SWIM: Vision-Language-Grounded Soft Whole-Body Interactive Manipulation](https://arxiv.org/abs/2609.17035v1)

- **arXiv**: `2609.17035v1`  |  **提交日期**: 2026-09-15
- **作者**: Tingcong Liu, Aye Phyu Phyu Aung, Junjie Xiong, Siyi Ma, Bo An, Ke Wu et al.

Soft and continuum robots enable manipulation through distributed body deformation and contact, yet translating language and visual context into executable whole-body actuation remains a fundamental challenge. We present SWIM, a framework that maps an initial RGB observation and a language instruction to a complete actuation-command sequence. Its vision-language-action (VLA) policy, SWIM-VLA, combines a diffusion action head with Visual Soft Proprioception (VSP) through a shared representation of RGB observations, language instructions, and tendon states. The diffusion head models conditional…

---

### [sensVLA: Spatially-Grounded Vision-Language-Action Model for Autonomous Wheel Loader](https://arxiv.org/abs/2609.17021v1)

- **arXiv**: `2609.17021v1`  |  **提交日期**: 2026-09-15
- **作者**: Gopi Krishna Erabati, Bjarne Johannsen, Angus Stewart, Vardeep Singh Sandhu

Autonomous wheel-loader control requires joint reasoning over task semantics, egocentric vision, proprioception, and 3D scene geometry. We present sensVLA, a Vision-Language-Action (VLA) architecture that combines a Qwen3-2B Vision-Language Model (VLM) with a fully trainable transformer action expert trained by flow-matching velocity regression. sensVLA routes Bird's-Eye-View (BEV) features, extracted from fused front and rear lidar, directly to the action expert through a dedicated cross-attention pathway, while the VLM consumes front and rear RGB views to provide task-conditioned semantic…

---

### [TEMPO: Learning Temporal Context for Dynamic Robot Manipulation](https://arxiv.org/abs/2609.16864v1)

- **arXiv**: `2609.16864v1`  |  **提交日期**: 2026-09-15
- **作者**: Zhenyang Feng, Jimin Heo, Erik B. Sudderth, Unnat Jain

Vision-language-action (VLA) models have achieved impressive performance in quasi-static manipulation, but struggle in dynamic manipulation tasks because they operate on a single observation at inference time. We identify two representational failures that underlie this limitation. The first is motion ambiguity, where a single observation does not include scene dynamics and therefore cannot anticipate the future state of moving objects. The second is state aliasing, where visually similar observations from different points in a task require different actions. We argue that these failures…

---

### [The Robot Data Factory](https://arxiv.org/abs/2609.16705v1)

- **arXiv**: `2609.16705v1`  |  **提交日期**: 2026-09-15
- **作者**: Sami Haddadin, Ivan Laptev, Ian Reid, Dezhen Song, Cesare Stefanini, Abdalla Swikir et al.

Physical AI requires more than increasingly large robot datasets: intelligent robots acquire knowledge through continuous interaction with the physical world. We argue that the defining scientific resource of Physical AI is therefore not raw robot data alone, but robot experience - physically grounded interaction whose observations, actions, embodiment, context, and outcomes preserve the perception-action-consequence loop. We introduce the Robot Data Factory (RDF), a mission-driven infrastructure and methodology for continuously generating, validating, benchmarking, and reusing such…

---

### [SAVLA: Symmetry-Aware Vision-Language-Action Models for Robotic Manipulation](https://arxiv.org/abs/2609.16641v1)

- **arXiv**: `2609.16641v1`  |  **提交日期**: 2026-09-15
- **作者**: Junle Li, Weixian Waylon Li, Fuxiang Wu, Fusheng Hao, Fengxiang He

Vision-language-action (VLA) models have become the dominant paradigm for language-conditioned robot manipulation. However, although images and language instructions inherently encode geometric information, VLAs acquire their spatial competence purely from demonstrations. As a result, they are reliable only within the range of scene poses that the demonstrations cover. We propose SAVLA, an end-to-end symmetry-aware VLA model for robust and data-efficient policy learning. Our approach keeps the pretrained vision-language backbone entirely frozen while combining it with an equivariant…

---

### [Dense to MoE Adaptation for Compact Vision Language Action Policies](https://arxiv.org/abs/2609.16503v1)

- **arXiv**: `2609.16503v1`  |  **提交日期**: 2026-09-15
- **作者**: Muchun Niu, Shuang Chen, Yuzhou Wu, Linfeng Zhang

Vision language action (VLA) policies continue to grow in parameter count, making deployment on resource-constrained robot platforms difficult. The central goal is to reduce the number of LLM-side parameters retained in the deployed policy while preserving downstream task performance. Our approach, AdaDE, adapts selected dense feed forward blocks into mixture of experts (MoE) layers and derives expert retention masks from router statistics during fine tuning. The Dense2MoE conversion preserves the original dense FFN function at initialization, so expert deactivation can start without a…

---

### [XRoboToolKit-T: Teleoperation with High Stability and Precision with Tactile Sensing for Contact-rich Manipulation](https://arxiv.org/abs/2609.16437v1)

- **arXiv**: `2609.16437v1`  |  **提交日期**: 2026-09-14
- **作者**: Xiwen Dengxiong, Xueting Wang, Ke Jing, Rui Li, Yunbo Zhang

Collecting high-quality robot data for contact-rich manipulation tasks is essential for enabling robots to acquire real-world skills. However, existing data collection solutions often lack the capability to obtain stable and high-frequency tactile feedback, limiting their effectiveness in contact-rich manipulation scenarios. In this work, we propose a versatile teleoperation system with tactile-driven assistance to enable high-frequency and stable contact-rich manipulation. The proposed XRoboToolKit-T teleoperation system incorporates a tactile-informed force control architecture, designed to…

---

### [Beyond Single-Axis Testing: Paired Evaluation of Compound Robustness in Vision-Language-Action Policies](https://arxiv.org/abs/2609.15940v1)

- **arXiv**: `2609.15940v1`  |  **提交日期**: 2026-09-14
- **作者**: Hiroki Sawada, Shunichi Kasahara

Vision-language-action policies are typically evaluated one perturbation at a time, providing a useful diagnosis of their sensitivity to individual distribution shifts. Real-world deployment, however, may involve several shifts simultaneously, and it remains unclear how these individual robustness measurements compose. We ask whether compound robustness can be inferred from single-axis evaluations. We introduce LIBERO-CTRL, a six-axis benchmark that pairs each initial state across single-axis conditions and a matched simultaneous condition. This design reveals two opposing outcome changes…

---

### [GRAVA: Grounded Reasoning-to-Action Representation and Learning for Autonomous Driving](https://arxiv.org/abs/2609.15169v1)

- **arXiv**: `2609.15169v1`  |  **提交日期**: 2026-09-14
- **作者**: Xiao Liu, Haoyu Li, Jianghao Leng, Lin Wang, Chao Sun

Driving vision-language-action (VLA) models increasingly reason before acting, but their intermediate reasoning is often weakly grounded in physical scene evidence and loosely connected to executable behavior. We present GRAVA, a framework built around Grounded Reasoning-to-Action (GRA), which unifies grounding, reasoning, and action generation in a single autoregressive stream. GRA links action-relevant language references to 2D visual regions and ego-centric physical states, organizes object interactions and decisions in a trajectory-anchored typed graph, and serializes this structure into…

---

### [IMPACT-VLA: Interaction-aware Multimodal Propagation Attribution via Counterfactual Trajectories for Vision-Language-Action Policies](https://arxiv.org/abs/2609.15005v1)

- **arXiv**: `2609.15005v1`  |  **提交日期**: 2026-09-14
- **作者**: Jinwoong Kim, Sangjin Park

Vision-Language-Action (VLA) policies perform robot manipulation tasks using multimodal inputs such as visual observations, proprioceptive states, and language instructions. However, it remains unclear at which execution stages each modality contributes to final task success and how input interventions propagate through subsequent states, observations, and actions. Existing attribution approaches primarily measure local sensitivity or temporally aggregated importance, limiting their ability to capture phase-dependent contributions and cross-phase dependencies. We propose Interaction-aware…

---

### [World-Action Models for Robot Learning and Control: A Survey](https://arxiv.org/abs/2609.16074v1)

- **arXiv**: `2609.16074v1`  |  **提交日期**: 2026-09-13
- **作者**: Zuxing Lu, Hongjia Zhai, Guanzhi Wang, Huajian Zeng, Jiaqi Yang, Jingyu Liu et al.

Robots operating in open environments act under partial observability, physical constraints, and dynamic task contexts. Beyond mapping observations and language instructions to actions, they must anticipate how candidate actions may affect future states and task-relevant outcomes. Recent advances in world models, video generation, and Vision-Language-Action (VLA) policies have motivated the development of World-Action Models (WAMs), which couple future world prediction with executable action generation. This survey provides a robotics-oriented review of WAMs. We clarify their scope relative…

---

### [REVOLVE: An Automated Closed-Loop Framework for Evolving Robot Manipulation with Minimal Human Intervention](https://arxiv.org/abs/2609.14633v1)

- **arXiv**: `2609.14633v1`  |  **提交日期**: 2026-09-13
- **作者**: Hanyu Liu, Qian Li, Yizhu Ding, Jiayi Wen, Keqiang Ren, Yunsheng Ma et al.

Recent advances in data-driven robot manipulation policies have substantially improved task execution and generalization. However, real-world deployment still relies heavily on humans for failure assessment, correction, and environment reset, while models often fail to continually learn from failures and corrective experience. We present REVOLVE (Robot Evolving via Orchestrated Loops, Verification, and Experience), an automated closed-loop framework for evolving robot manipulation with minimal human intervention. Built on a unified software platform, REVOLVE integrates data collection, policy…

---

## 📅 2026-09-11

### [UniMPA: A Unified Memory-Prediction-Action Model via Action-Grounded Transition Modeling](https://arxiv.org/abs/2609.11875v1)

- **arXiv**: `2609.11875v1`  |  **提交日期**: 2026-09-10
- **作者**: Wei Li, Rui Shao, Jie He, Lingsen Zhang, Ziwei Liu, Liqiang Nie

Recent advances in Vision-Language-Action (VLA) models have improved robotic manipulation, yet observation-to-action learning remains limited by a fundamental transition realizability gap, manifested in three tightly coupled problems: (i) Transition ambiguity. Visually similar current observations may correspond to different manipulation phases and imply different subsequent transitions. (ii) Prediction--execution mismatch. A visually plausible predicted future observation does not necessarily correspond to a physically realizable transition. (iii) Experience--realization mismatch. A…

---

### [ActSafeGuard: Differentiable and Training-Aligned Constraint Enforcement for Flow-Matching Policies](https://arxiv.org/abs/2609.11697v1)

- **arXiv**: `2609.11697v1`  |  **提交日期**: 2026-09-10
- **作者**: Jianming Ma, Rongjun Jin, Xiaxi Si, Yang Zhang, Yiheng Li, Yue Gao

Vision-Language-Action (VLA) and World-Action Models (WAMs) have demonstrated strong capabilities in general-purpose robotic manipulation, yet their generated actions may violate hard physical constraints and therefore be unsafe or infeasible for deployment. Existing safety approaches either optimize statistical safety objectives without deterministic per-step guarantees or correct unsafe actions only during inference, creating a mismatch between policy training and execution. We introduce ActSafeGuard, a differentiable and training-aligned safeguard layer for flow-matching based policies.…

---

### [Your Model Already Knows Don't Teach It, Learn to Ask It: Soft Prompting for Few-Shot Adaptation of Vision-Language Models](https://arxiv.org/abs/2609.11310v1)

- **arXiv**: `2609.11310v1`  |  **提交日期**: 2026-09-10
- **作者**: Gautam Rajendrakumar Gare, Siyi Li, Hewei Wang, Cesar Daniel Hernandez, Wei Zhao, Wolfgang M. Pauli et al.

We address few-shot object detection with vision-language models (VLMs) in out-of-domain settings such as aerial, industrial, and medical imagery, using only ten annotated images for supervision. Existing adaptation methods are discrete prompt optimization and LoRA fine-tuning. We revisit a third option: soft prompting, where a small number of continuous prompt tokens are optimized while the pretrained backbone remains frozen. We identify two key design choices. First, placing prompt tokens at the cross-modal boundary between visual and text tokens outperforms other placements (10.0 vs. 8.4…

---

### [IMLE-VLA: Fast Single-Step Action Generation for Vision-Language-Action Policies](https://arxiv.org/abs/2609.10915v1)

- **arXiv**: `2609.10915v1`  |  **提交日期**: 2026-09-10
- **作者**: Kian Hosseinkhani, Qinhe Peng, George Shramko, Mehran Aghabozorgi, Jianing Qian, Tristan Engst et al.

Vision-language-action (VLA) policies leverage pretrained vision-language backbones to achieve strong cross-task generalization. A leading design couples this backbone with a dedicated continuous action head trained via diffusion or flow matching. However, such heads rely on iterative multi-step sampling, for example 10 Euler steps in $π_{0.5}$. This creates an inference bottleneck that produces stop-and-go movement in the robot and slower task completion. We introduce IMLE-VLA, which replaces the iterative action head with a single-step conditional generator trained via conditional Implicit…

---

### [HuRo: Robotizing Human Videos for Scalable VLA Pretraining](https://arxiv.org/abs/2609.10706v1)

- **arXiv**: `2609.10706v1`  |  **提交日期**: 2026-09-09
- **作者**: Jinho Jeong, Se June Joo, Jaehyun Kang, Dongyun Kim, Yena Kim, Hanjung Kim et al.

Human video datasets have emerged as a compelling alternative to expensive real-robot data, offering rich diversity at scale. To bridge the human-to-robot embodiment gap, existing approaches either robotize videos in task-matched settings or address observation and action alignment separately at scale. In this work, we systematically examine whether robotized human videos can provide effective and scalable supervision for pretraining vision-language-action (VLA) policies. To this end, we develop a robotization pipeline that converts heterogeneous human videos into robot-aligned observations…

---

## 📅 2026-09-10

### [Frequency-Conditioned Flow Matching for Vision-Language-Action Models](https://arxiv.org/abs/2609.10405v1)

- **arXiv**: `2609.10405v1`  |  **提交日期**: 2026-09-09
- **作者**: Haochen Niu, Shengye Dong, Hao Liu, Peiwen Lin, Wang Chuang

Robot actions are temporally correlated trajectories whose frequency components encode motion at different scales with highly non-uniform energy distributions. Yet Flow Matching--based vision-language-action (VLA) models typically generate actions in temporal coordinates, without explicitly modeling or systematically leveraging this frequency heterogeneity. We introduce \emph{FreqFM}, a frequency-conditioned Flow Matching framework for VLA models. It raises action frequency from an implicit trajectory property to an explicit conditioning dimension that spans the entire generation pipeline.…

---

### [FolDeX: A Physical-World Benchmark for Long-Horizon Robotic Manipulation of Deformable Objects](https://arxiv.org/abs/2609.10243v1)

- **arXiv**: `2609.10243v1`  |  **提交日期**: 2026-09-09
- **作者**: Chenhuan Liu, Yi Xu, Feng Wu, Hanyang Wang, Wenxiao Kuai, Weihao Ding et al.

Embodied AI, including vision-language-action and world-action models, must operate reliably in the physical world. Yet methods that perform well in simulation can degrade substantially on real robots, especially in long-horizon deformable-object manipulation, where policies must track changing states and execute reliable multi-stage bimanual interactions. Existing real-robot benchmarks mainly focus on short-horizon rigid-object tasks and offer limited coverage of long-horizon deformable manipulation. We introduce FolDeX, a physical-world benchmark built entirely from real-robot data, with…

---

### [RoboDrop: Curating VLA Post-Training Data via Local Gradient Compatibility](https://arxiv.org/abs/2609.10021v1)

- **arXiv**: `2609.10021v1`  |  **提交日期**: 2026-09-09
- **作者**: Runze Xu, Yuanfan Xu, Cuijie Xu, Shuang Dai, Yining Li, Yu Wang et al.

Vision--language--action (VLA) models acquire broad generalization through large-scale pretraining, yet adapting them to a new task and robot embodiment still requires post-training on newly collected data. Unlike pretraining, post-training targets task- and embodiment-specific adaptation, making it particularly sensitive to data quality. In practice, collected robot datasets often contain heterogeneous errors, including execution mistakes, sensor drift, and timestamp misalignment, which can impair post-training and policy performance. Manual inspection is costly, while existing data-cleaning…

---

### [Time-Frequency Geometric Cross-Attention for Chunked Vision-Language-Action Models](https://arxiv.org/abs/2609.09925v1)

- **arXiv**: `2609.09925v1`  |  **提交日期**: 2026-09-09
- **作者**: Shengye Dong, Haochen Niu, Hao Liu, Peiwen Lin, Chuang Wang, Shanmin Pang

Modern vision-language-action (VLA) policies predict a whole chunk of actions: one to two seconds of coordinated motion emitted in a single forward pass. Yet an action chunk is essentially a short multivariate trajectory, but inside these models it is a sequence of generic per-timestep hidden tokens decoded by a linear head. This under-serves two motion structures. First, frequency: a chunk superimposes a smooth global trend and fine corrective motion across time scales, and a single token entangles them. Second, cross-phase geometry: motions of different phases (reach, contact, grasp…

---

### [Modality-Decoupled Federated Learning for Privacy-Preserving Embodied Intelligence in 6G](https://arxiv.org/abs/2609.09591v1)

- **arXiv**: `2609.09591v1`  |  **提交日期**: 2026-09-09
- **作者**: Zhuodong Liu, Xiangyu Li, Chunhong Yuan, Hongyang Du, Bodong Shang, Qingqing Wu et al.

Sixth-generation (6G) wireless networks are expected to provide a key infrastructure for large-scale embodied intelligence, where heterogeneous robots collaborate through low-latency connectivity, edge intelligence, and distributed sensing. Vision-language-action (VLA) models offer a foundation by integrating visual perception, language understanding, and action generation into a unified closed-loop policy. However, training and adapting VLA models to distributed robotic agents introduce challenges in privacy protection, communication efficiency, and model heterogeneity. Existing federated…

---

### [No Free Checker: A Survey of Verifiers for Robot Policies](https://arxiv.org/abs/2609.09250v1)

- **arXiv**: `2609.09250v1`  |  **提交日期**: 2026-09-08
- **作者**: Yang Wan, Xihang Yue, Zhirui Liu, Ziyuan Chu, Shuxun Wang, Yuhan Chen et al.

A verifier for robot policies reads a candidate behavior and returns a score for how well it did, used both to evaluate vision-language-action policies and to train them. Verifiers range from success detectors and reward models to runtime monitors, safety filters, and temporal-logic specifications. We survey roughly 150 verifiers and compare them along two properties. Availability is how much a verdict costs, how early in a rollout the verdict arrives, and how often a verdict can be asked for. Availability rises as verdicts get cheaper, earlier, and denser. Credibility is how much a high…

---

## 📅 2026-09-09

### [DeCAL: Towards Physically-Grounded Dexterous Vision-Language-Action Models via Contact-Aware Latent Co-Imagination](https://arxiv.org/abs/2609.09119v1)

- **arXiv**: `2609.09119v1`  |  **提交日期**: 2026-09-08
- **作者**: Yankai Fu, Ning Chen, Junkai Zhao, Heng Zhang, Guocai Yao, Pengwei Wang et al.

Dexterous manipulation involves contact-rich and fine-grained interactions with the physical world, posing significant challenges for existing vision-language-action (VLA) models due to severe visual occlusions and complex contact dynamics. While recent works have incorporated tactile sensing into robotic manipulation, most approaches still rely on homogeneous multimodal fusion, lacking adaptive tactile integration and explicit modeling of physical dynamics. In this work, we present DeCAL, a physically-grounded dexterous vision-language-action model that unifies understanding, imagination and…

---

### [3DWay: Generalizing Robot Manipulation via 3D Consistent Waypoints](https://arxiv.org/abs/2609.08224v1)

- **arXiv**: `2609.08224v1`  |  **提交日期**: 2026-09-08
- **作者**: Ziqin Huang, Yingyue Li, Chenyangguang Zhang, Ruida Zhang, Yuxin Chen, Gu Wang et al.

Intermediate representations are key to bridging the modality gap between generalizable manipulation policies and large-scale pretrained vision-language models (VLMs). Among these, trajectory-based representations compactly represent motion-relevant cues, yet most existing approaches predict trajectories in 2D image space, resulting in intrinsic 3D ambiguity. Moreover, using 2D trajectories with depth still leaves the free-space waypoints ambiguous, limiting reliable 3D reasoning. To address this, we propose predicting 3D consistent waypoints (3DWay) from multi-view images. By reformulating…

---

### [WorldAgen: Unified State-Action Prediction with Test-Time World Model Training](https://arxiv.org/abs/2609.08162v1)

- **arXiv**: `2609.08162v1`  |  **提交日期**: 2026-09-08
- **作者**: Chi Wan, Kangrui Wang, Yuan Si, Pingyue Zhang, Manling Li

How can vision-language-action (VLA) models adapt to new environments where world dynamics shift? While recent research has combined world modeling and action prediction to improve VLA performance, existing methods largely rely on pretraining on static datasets, without mechanisms for active adaptation at deployment time. As a result, these models often fail to generalize when deployed in unseen scenarios with novel object configurations or dynamics. We present WorldAgen, a unified framework that jointly learns world modeling and action prediction while enabling Test-Time Training (TTT) to…

---

### [ComVLA: Communication-Aware Split Inference for VLA Models in 6G-Connected Robotics](https://arxiv.org/abs/2609.07838v1)

- **arXiv**: `2609.07838v1`  |  **提交日期**: 2026-09-07
- **作者**: Boliang Liu, Wint Yi Poe, Jingyun Di, Riccardo Trivisonno, Giuseppe Caire

Connected robotics is an emerging 6G application where mobile robots follow natural-language instructions to manipulate physical objects. The Vision-Language-Action (VLA) models that enable this are too large to run on the robot; a common trend is to offload inference to the cloud. The wireless link, however, limits how much sensing data the edge can transmit per control step. Two recent lines address this constraint: semantic communication codecs compress sensor data but require channel-specific retraining, and VLA token pruners select tokens from image but ignore the channel. Our insight is…

---

### [ICI-VLA: In-Context Imitation with Spatiotemporally Aligned Demonstrations for Vision-Language-Action Models](https://arxiv.org/abs/2609.07581v1)

- **arXiv**: `2609.07581v1`  |  **提交日期**: 2026-09-07
- **作者**: Songhua Yang, Ziyu Liu, Xuetao Li, Ruqi Xiao, Kangxin Zhu, Miao Li

Vision-Language-Action (VLA) policies are commonly adapted to new manipulation settings through additional gradient updates, which limits rapid deployment when task-specific data or compute is scarce. We present ICI-VLA, a training and retrieval framework that equips a text-action VLM with few-shot test-time adaptation through in-context demonstrations. Unlike mainstream VLA designs based on action-specific multimodal fusion, ICI-VLA retains the native text-generation interface. ICI-VLA updates its parameters only during offline training; at inference, the policy remains fixed and conditions…

---

### [Measuring Language Transfer in Robot Policies: Adding Greek to a Cosmos3 Vision-Language-Action Policy](https://arxiv.org/abs/2609.07470v1)

- **arXiv**: `2609.07470v1`  |  **提交日期**: 2026-09-07
- **作者**: Ayoub Kirouane, Georgios Giaples, Christos Petrocheilos

Robot foundation models are trained and evaluated predominantly in English, and robot demonstration corpora do not exist for most languages. We study the addition of Greek to an open vision-language-action stack using only machine-rephrased instructions and no architecture changes. The main challenge is measurement rather than translation. Several plausible instruments produce false conclusions: a color-histogram metric rewards noise, a single-goal benchmark scores 84.6% under correct Greek and 82.6% under deliberately wrong instructions, training loss fails to predict Greek success, and…

---

### [Large Discrete Policy: Advancing Explicit Behavior Modeling with Stochastic Iterative Scoring](https://arxiv.org/abs/2609.07049v1)

- **arXiv**: `2609.07049v1`  |  **提交日期**: 2026-09-07
- **作者**: Zhenxin Li, Nadine Chang, Xinglong Sun, Jingde Chen, Wenhao Yao, Zi Wang et al.

Behavior policies are often formulated as continuous generative models, whose iterative denoising processes are expressive but difficult to interpret and prone to producing implausible actions. We propose the Large Discrete Policy (LDiP), a fully discrete behavior modeling framework that selects actions from a large vocabulary of physically plausible candidates. Rather than perturbing actions, LDiP improves expressivity through stochastic iterative scoring: it progressively re-scores and prunes candidates with score-space stochasticity, enabling fine-grained ranking and exploration among…

---

### [MEMOBench: A Process Level Memory Benchmark for Robotic Manipulation](https://arxiv.org/abs/2609.07047v1)

- **arXiv**: `2609.07047v1`  |  **提交日期**: 2026-09-07
- **作者**: Haiyang Sun, Haoxiao Wang, Junming Chen, Weicheng Fang, Zihao Su, Jingkun Yi et al.

Robotic manipulation often requires acting on information that is no longer visible, yet Vision-Language-Action policies are usually evaluated when the current observation largely determines the next action. Existing robotic memory benchmarks expose this gap, but they still rely mainly on final task success and therefore conflate forgetting with manipulation failure. We present \textbf{MEMOBench}, a benchmark for process level memory evaluation in robotic manipulation. MEMOBench includes 30 history dependent tasks, 1{,}500 expert demonstrations, and 4{,}200 executable checkpoint instances…

---

### [GIFT: Goal-Injected Fine-Tuning for Efficient Manipulation Policy Adaptation](https://arxiv.org/abs/2609.07006v1)

- **arXiv**: `2609.07006v1`  |  **提交日期**: 2026-09-07
- **作者**: Xiaoyuan Fang, Shuo Feng, Yuxuan Wang, Enhua Cheng, Peng Zhou, Piji Li

Compared with relying solely on initial observations and language instructions, predicting goal images with generative models as high-level visual guidance can significantly enhance the robustness of Vision-Language-Action (VLA) models. However, most existing foundation models have not systematically incorporated goal image conditioning due to the high computational training cost. To this end, we propose Goal-Injected Fine-Tuning (GIFT), a lightweight and efficient fine-tuning framework that seamlessly integrates generated goal images into multiple representative pretrained VLA models. Our…

---

### [ContextFlow: In-Context Flow Matching for Robot Manipulation](https://arxiv.org/abs/2609.06852v1)

- **arXiv**: `2609.06852v1`  |  **提交日期**: 2026-09-06
- **作者**: Jian Ding, Xianjie Dai, Roei Herzig, Nussair Hroub, Jinjie Mai, Dengxin Dai et al.

Although highly effective in vision and language domains, applying in-context learning to robotics remains challenging. Existing autoregressive in-context imitation methods discretize continuous actions and exacerbate the accumulation of early prediction errors through next-token prediction, limiting their generalization on unseen task configurations. Meanwhile, flow-matching policies have been explored for continuous robot control and can help mitigate compounding errors; however, in-context imitation learning within a flow-matching framework remains underexplored. To address these…

---

### [Learning to Use Imagination: Progress-Conditioned Future Utilization for World Action Models](https://arxiv.org/abs/2609.06578v1)

- **arXiv**: `2609.06578v1`  |  **提交日期**: 2026-09-06
- **作者**: Yijie Zhu, Zitong Yu, Wei Li, Hui Ma, Wen Li, Rui Shao et al.

World Action Models (WAMs) extend Vision-Language-Action (VLA) models by incorporating future visual dynamics into action generation. However, existing WAMs often utilize imagined futures with limited adaptation to evolving execution progress, potentially introducing distracting or unreliable predictive cues. This limitation arises from two empirically identified forms of non-uniformity in future utility: (i) at the inter-progress level, the utility of imagined futures varies across execution stages as control demands change; and (ii) at the intra-progress level, individual future latents…

---

### [VLA-Corrector: Stage-Aware Observable State Understanding for Prompt-Based Closed-Loop Recovery of Vision-Language-Action Policies](https://arxiv.org/abs/2609.06508v1)

- **arXiv**: `2609.06508v1`  |  **提交日期**: 2026-09-06
- **作者**: Chang Song, Bin Qian, Yan Feng, Zhijie Song

Long-horizon robot manipulation with Vision-Language-Action (VLA) policies remains vulnerable to execution-time deviations, as final task success provides little information for diagnosing and correcting failures caused by action noise, object displacement, or goal misalignment. We introduce a stage-aware failure verification and Prompt Recovery framework that enables closed-loop correction of a fixed VLA policy without parameter updates or privileged simulator states. The framework introduces an observable-history-based Learned Verifier that jointly estimates manipulation progress and…

---

## 📅 2026-09-07

### [What Matters, When? Diagnosing and Improving Conditional Visual Grounding in Visuomotor Imitation Policies](https://arxiv.org/abs/2609.05376v1)

- **arXiv**: `2609.05376v1`  |  **提交日期**: 2026-09-04
- **作者**: Vivek Chavan, Pengtao Xie, Yahuan Shi, Oliver Heimann, Kevin Haninger, Jörg Krüger

Visuomotor imitation policies can achieve high performance under in-distribution visual conditions yet fail when visually similar objects or receptacles are introduced. We study this behavior as a problem of conditional visual grounding: the visual target required for successful control changes with the manipulation phase and, in more complex tasks, with the observed task state. Using Action Chunking with Transformers (ACT), we systematically introduce distractor objects and receptacles with controlled color and shape similarity and localize failures to picking and placement. We find that…

---

### [Towards Neuro-Symbolic Procedural Reasoning for Long-Horizon Vision-Language-Action Manipulation](https://arxiv.org/abs/2609.05369v1)

- **arXiv**: `2609.05369v1`  |  **提交日期**: 2026-09-04
- **作者**: Vivek Chavan, Yahuan Shi, Oliver Heimann, Kevin Haninger, Jörg Krüger

Vision-language-action (VLA) models can execute short manipulation skills, but remain brittle in long-horizon procedures requiring persistent task state, dependency-aware reasoning, conditional decisions, and reliable grounding. We investigate a neuro-symbolic framework that combines learned VLA control with explicit task graphs and multimodal procedural memory. Task graphs encode action dependencies, valid transitions, and branch conditions, while memory maintains the active step, completed actions, textual context, and task-relevant visual evidence. Together, these structures guide object…

---

### [RoboSPA: Can VLA Models Go Beyond Simple Scenes and Short-Horizon Tasks?](https://arxiv.org/abs/2609.05324v1)

- **arXiv**: `2609.05324v1`  |  **提交日期**: 2026-09-04
- **作者**: Zhenxuan Fan, Bo Zhang, Yutong Lin, Yuqian Yuan, Juekai Lin, Liang Liang et al.

Vision-Language-Action (VLA) models have shown promising progress in language-conditioned robotic manipulation. However, existing datasets and benchmarks mainly evaluate task completion under predefined settings, offering limited insight into model reasoning under increasing spatial and procedural complexity. We introduce \textbf{RoboSPA} (\textbf{Robo}t \textbf{S}patial-\textbf{P}rocedural \textbf{A}ssessment), a large-scale robotic manipulation dataset and benchmark for diagnosing embodied reasoning in VLA models. \texttt{RoboSPA} focuses on two core dimensions, Fine-Grained Spatial…

---

### [Temporal Tactile Encoding and Compliance for Intent-Aware Robot-to-Human Bimanual Handover](https://arxiv.org/abs/2609.05282v1)

- **arXiv**: `2609.05282v1`  |  **提交日期**: 2026-09-04
- **作者**: Pasquale Marra, Stefano Berti, Gabriele Mario Caddeo, Lorenzo Natale

Reliable robot-to-human handover requires the robot to infer when the person is ready to receive the object, and release it safely, comfortably, and at the right time. This is challenging because visual observations alone may not disambiguate clear taking intent from accidental contact, weak grasping, wrong-direction forces, or transient interactions. In this work we treat human-robot handover as an intrinsically multimodal problem. Our approach couples a VLA model with a compliance controller that reduces interaction forces during object transfer. We finetune the VLA model with human…

---

### [LIBERO-RECOVER: Beyond Task Success Towards Failure Recovery in Robotic Manipulation Models](https://arxiv.org/abs/2609.05178v1)

- **arXiv**: `2609.05178v1`  |  **提交日期**: 2026-09-04
- **作者**: Lin Liu, Zhicheng Bao, Lu Zhang, Ziying Song, Wu Yang, Shuai Tao et al.

Vision-Language-Action (VLA) or World Action (WAM) models have recently demonstrated remarkable performance in robotic manipulation. On LIBERO, SOTA method have achieved nearly 100\% success rates, seemingly suggesting that the models are ready for deployment in real world. However, near perfect performance on existing benchmarks can be misleading: success under ideal conditions does not imply real world robustness. Existing benchmarks primarily evaluate task completion from predefined initial states, while real world interactions inevitably involve failures such as failed grasps, collisions,…

---

### [Reasoning Without Inference Cost: Latent Semantic Scaffolding for Robot VLA Policies](https://arxiv.org/abs/2609.04893v1)

- **arXiv**: `2609.04893v1`  |  **提交日期**: 2026-09-04
- **作者**: Andrew Ting Yan Li, Zhuo Li, Zhelin Yang, Zhipeng Dong, Quentin Rouxel, Fei Chen

Vision-language-action (VLA) models are trained by imitation and capture what action to take but not why; adding causal reasoning improves manipulation, but current methods pay for it at inference time - generating reasoning tokens or rolling out predicted future states at every step, a cost that compounds over long horizons. We ask whether this benefit can instead be captured during training and discarded before deployment. We introduce Latent Semantic Scaffolding (LSS), an auxiliary loss applied during human-demonstration pretraining that aligns a VLA's action-token representations to text…

---

## 📅 2026-09-04

### [GIFT: Guided Intermediate Feature Training via Action-Oriented Structural Supervision for Robotic Manipulation](https://arxiv.org/abs/2609.04193v1)

- **arXiv**: `2609.04193v1`  |  **提交日期**: 2026-09-03
- **作者**: Yupeng Zheng, Xiang Li, Songen Gu, Yuhang Zheng, Shuai Tian, Weize Li et al.

Vision-language pre-training and predictive world modeling provide robot policies with rich semantic and dynamic visual features, but their native action and visual-prediction objectives may omit critical physical and task structure while retaining control-irrelevant visual redundancy. We call this mismatch between visual richness and control utility the action-sufficiency gap. We investigate whether this gap can be bridged by guiding intermediate features to preserve three control-relevant structure in robotic manipulation: geometry governing motion feasibility, affordance encoding…

---

### [Continuous Actions from Discrete Minds: Latent-Aligned Planning for End-to-End Autonomous Driving](https://arxiv.org/abs/2609.04070v1)

- **arXiv**: `2609.04070v1`  |  **提交日期**: 2026-09-03
- **作者**: Ruoyu Yao, Yusen Xie, Qingzhao Liu, Pei Liu, Zewei Yang, Yipeng Zhu et al.

Bridging the gap between the discrete reasoning of Vision-Language Models and the continuous, physics-constrained nature of autonomous driving remains a significant challenge. In this work, we introduce LaPla, a unified Vision-Language-Action (VLA) framework featuring latent-aligned planning to seamlessly ground semantic understanding in precise motion execution. We first design an action tokenizer based on a residual vector-quantized variational autoencoder (VQ-VAE), capturing vehicle kinematics and encoding trajectory features into a structured latent space. Rather than discrete codebook…

---

### [Toward Unified Robot Learning: Bridging Representation, Vision-Language-Action, and World Models](https://arxiv.org/abs/2609.03927v1)

- **arXiv**: `2609.03927v1`  |  **提交日期**: 2026-09-03
- **作者**: Shaunak A. Mehta, Ananya Hazarika, Haochen Zhang, Fan Yang, Ryo Moriyama, Wenkai Li et al.

For robots to operate reliably in real-world environments, they need to perceive their surroundings, act, and reason about the consequences of those actions. Rapid progress in the domains of representation learning, VLA models, and world models has significantly enhanced the capabilities of robot learning systems, enabling robots to work in increasingly complex environments. However, these paradigms are typically developed in isolation, resulting in fragmented systems that struggle with generalization, long-horizon temporal reasoning and planning, and deployment in unstructured environments.…

---

### [MINERVA: How Small Can a Manipulation Policy Be and Still Solve LIBERO?](https://arxiv.org/abs/2609.03715v1)

- **arXiv**: `2609.03715v1`  |  **提交日期**: 2026-09-03
- **作者**: Kohei Sendai, Tatsuya Matsushima, Yusuke Iwasawa

Vision-language-action (VLA) models with billions of parameters now dominate the LIBERO manipulation benchmark, but the model capacity actually required by the benchmark remains unclear. We introduce MINERVA (MINimal Efficient Robotic Vision-Action policy), a family of deliberately compact visuomotor policies designed to measure this task-specific capacity floor. A 0.54M-parameter policy achieves 95.1% average success over 2,000 rollouts on the four standard LIBERO suites, only 2.4 points below the reported LeRobot $π_{0.5}$ result despite using 7,700$\times$ fewer parameters. Performance…

---

### [WISE: World-model-guided Imagination Scheduling for Efficient Post-training of Vision-Language-Action Models](https://arxiv.org/abs/2609.03681v1)

- **arXiv**: `2609.03681v1`  |  **提交日期**: 2026-09-03
- **作者**: Chenhao Zhang, Hanyu Zhao, Hang Cheng, Tengfei Pan, Long Zeng

Post-training VLA policies typically rely on supervised fine-tuning with costly expert demonstrations or reinforcement learning with expensive and potentially unstable real-world exploration. World models offer a promising alternative by evaluating candidate behaviors through imagined futures, yet effective post-training requires more than accurate prediction: imagination must be scheduled where it is useful, bounded within reliable horizons, and translated into trustworthy policy supervision. In robotic manipulation, the value of imagination varies substantially across execution stages,…

---

### [Scaling Bimanual Household Manipulation from 1,500 hours of Demonstrations to On-Policy Corrections](https://arxiv.org/abs/2609.03591v1)

- **arXiv**: `2609.03591v1`  |  **提交日期**: 2026-09-03
- **作者**: Jiafeng Xu, Qi Li, Yan Shen, Yiyu Ren, Travis Davies, Shaowen He et al.

Learning generalist policies for robust bimanual manipulation is bottlenecked by the scarcity of high quality large scale human demonstration data. In this work, we release 1,500 hours of diverse bimanual manipulation demonstrations covering everyday household tasks, and use this comprehensive corpus to train XR-2, a powerful vision-language-action (VLA) model. Enabled by a purpose built high throughput data pipeline and a carefully designed multi stage training paradigm, XR-2 attains strong manipulation performance in our systematic experiments while retaining favorable training efficiency…

---

### [Air-Ground Collaborative Vision-and-Language Navigation via Shared Bird's-Eye Maps](https://arxiv.org/abs/2609.03483v1)

- **arXiv**: `2609.03483v1`  |  **提交日期**: 2026-09-03
- **作者**: Shuning Zhang, Liang Li, Yunheng Wang, Tao Wang, Yihang Kang, Renjing Xu

Air-ground collaborative Vision-and-Language Navigation (VLN) pairs an unmanned aerial vehicle (UAV) with a global bird's-eye view and an unmanned ground vehicle (UGV) with a local first-person view, yet the setting remains largely unexplored: existing training-free methods solve single-agent tasks but offer no collaboration mechanism, and a recent CARLA-Air evaluation found no stable cooperative behavior across five state-of-the-art VLA models; naive semantic communication or bidirectional coupling even degrades performance. We establish AGC-VLN (Air-Ground Collaborative VLN), the first…

---

### [R2S-Eval: Robot Evaluation with Real-to-Sim Calibration via Vision-Language Models](https://arxiv.org/abs/2609.03276v1)

- **arXiv**: `2609.03276v1`  |  **提交日期**: 2026-09-03
- **作者**: Yidi Wang, Feixiang Ruan, Ruoqu Chen, Jie Yin, Yang Yu, Mengdi Xu et al.

Evaluating robot manipulation policies is becoming increasingly important as generalist models, particularly vision-language-action (VLA) models, are deployed on physical robots. However, conventional real-world evaluation remains labor-intensive, unstable, and insufficiently informative. It requires repeated hardware trials, manual scene resets, and continuous operator monitoring, may produce different policy rankings across repeated evaluations, and primarily relies on success-rate metrics that provide limited information about execution quality. In contrast, humans assess robot performance…

---

### [Sensing Which Modality Matters: Evidence-Gated Regularization for Robust VLA Policies](https://arxiv.org/abs/2609.03142v1)

- **arXiv**: `2609.03142v1`  |  **提交日期**: 2026-09-02
- **作者**: Yue Yang, Diego Romeres, Chiori Hori, Gedas Bertasius, Daniel Szafir, Siddarth Jain

Vision-Language-Action (VLA) policies fuse multimodal sensory inputs, but training on limited and homogeneous robot demonstrations encourages spurious inter-sensor correlations rather than task-relevant signal, a failure we term modality entanglement. Under real-world occlusions and distractors, this manifests as nuisance sensitivity to corruption of uninformative sensors and single-modality insufficiency when only one informative sensor remains intact. We propose Evidence-Gated Regularization (EGR), a modality-agnostic training objective that introduces zero inference-time overhead. EGR…

---

## 📅 2026-09-03

### [HINT: Human-Intent Inception for Long-Horizon Robot Manipulation](https://arxiv.org/abs/2609.02653v1)

- **arXiv**: `2609.02653v1`  |  **提交日期**: 2026-09-02
- **作者**: Mingyu Mei, Haojie Xu, Shihao Jin, Zibo Dai, Qihao Cheng, Zhengrui Lv et al.

Humans can perform complex manipulations given a simple intent through an overall instruction, while continuously adapting to evolving visual observations. However, current vision-language action (VLA) models and other action policies struggle to realize this high-level intelligent behavior under dense, evolving visual inputs and sparse language guidance. Visual correlations can then dominate semantic intent, leading actions to follow visual shortcuts rather than human goals. We present HINT (Human-INTent INcepTion), an agentic framework inspired by the human manipulation principles: semantic…

---

### [Latent Cluster Analysis for Vision-Language-Action Models](https://arxiv.org/abs/2609.02634v1)

- **arXiv**: `2609.02634v1`  |  **提交日期**: 2026-09-02
- **作者**: Theodor Wulff, Sergio Lanza, Tamara Bila, Angelo Cangelosi, Stefan Wermter, Igor Farkas

Vision-Language-Action (VLA) Models are increasingly used in robotics for their ability to ground language and perception into action, yet the internal representations driving their behaviour remain poorly understood. We propose LAVLA, a framework for latent cluster analysis of VLA models, and conduct a layer-wise study of the state-of-the-art GR00T N1.5 model, with particular focus on its action decoder. To better characterise the latent space during action diffusion, we introduce a cross-attention-based embedding-weighting method that amplifies relevant features while suppressing less…

---

### [ZETA: A Controlled Study of Zero-Shot Cross-Embodiment VLA Transfer for Tabletop Manipulation](https://arxiv.org/abs/2609.02546v1)

- **arXiv**: `2609.02546v1`  |  **提交日期**: 2026-09-02
- **作者**: Mi Yan, Wenhao Zhang, Zhiqi Zhang, Yu Peng, Tangxinyu Wang, Lingfei Zhai et al.

Zero-shot generalization to unseen embodiments is important for generalizable vision-language-action (VLA) models as robot hardware evolves and task-specific data collection remains costly. However, a systematic understanding of this problem remains limited, in part because the literature lacks a unified zero-shot transfer definition and controlled evaluation settings that isolate embodiment changes from differences in tasks, scenes, or protocols. To address this gap, we first distinguish strict zero-shot transfer, where the target embodiment is absent from all training data, from…

---

### [Towards Zero-Shot Transfer Across Embodiments For Driving VLAs](https://arxiv.org/abs/2609.02341v1)

- **arXiv**: `2609.02341v1`  |  **提交日期**: 2026-09-02
- **作者**: Caio Azevedo, Stefano Sabatini, Sascha Hornauer, Fabien Moutarde

Vision-Language-Action models (VLAs) have shown strong potential in autonomous driving by leveraging multimodal pretraining for instruction following, visual reasoning, and scene-level generalization. In robotic manipulation, scaling VLA fine-tuning across multiple robot setups--especially when unifying representations across embodiments--has been shown to improve in-dataset performance and cross-embodiment generalization; in autonomous driving, however, VLAs remain largely trained on individual datasets and are rarely evaluated for zero-shot transfer to unseen datasets and camera rigs;…

---

### [PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies](https://arxiv.org/abs/2608.30378v2)

- **arXiv**: `2608.30378v2`  |  **提交日期**: 2026-08-31
- **作者**: Botong Zhao, Fang Yu, Tim Yu, Senhua Zhu, Xinyuan Chen, Yue Lu

Direct vision-language-action policies generate continuous robot actions efficiently, but standard behavior cloning leaves two complementary gaps: their representations are not explicitly required to describe how the scene evolves over multiple time scales, and deployment trajectories of unequal quality are often reused without separating useful dynamics from undesirable behavior. We introduce \method, a direct world-action policy that combines outcome-agnostic predictive learning with outcome-aware policy improvement. \method first retains a local fixed-offset JEPA objective and adds…

---

## 📅 2026-09-02

### [Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching](https://arxiv.org/abs/2609.01404v1)

- **arXiv**: `2609.01404v1`  |  **提交日期**: 2026-09-01
- **作者**: Jaewoo Park, Minyoung Lee, Sukmin Seo, Moonbin Yim, Hyunwook Yoon, Dohoon Ryu et al.

Multimodal Large Language Models (MLLMs) are strong perceivers of images and video. We ask how far that reach extends into acting: dropping an MLLM directly into a drone's control loop, with its entire action space declared solely in the prompt. Recent systems approach this setting but increasingly narrow the model's decision-making. We widen it back. We introduce DroneCATS-Agent, an architecture where the MLLM is a swappable component, and DroneCATS, a benchmark treating the model as the independent variable. Beyond merely flying toward a pixel, our agent entrusts the model to yaw and…

---

### [EmbodiedSkills: A Unified Framework for Orchestrating, Training, and Deploying VLA Agents](https://arxiv.org/abs/2609.01281v1)

- **arXiv**: `2609.01281v1`  |  **提交日期**: 2026-09-01
- **作者**: Wei Wang, Wenqiao Zhang, Yutong Lin, Yuqian Yuan, Tianwei Lin, Jinhao Mao et al.

Vision-language-action (VLA) models map visual observations and language instructions directly to robot actions, but long-horizon tasks require more than action prediction. An agent must coordinate perception, planning, execution, progress verification, and recovery as the physical state evolves. An action prediction or a model-generated skill decision does not, by itself, guarantee that the proposed operation is valid in the current state or that its outcome will be verified. We propose EmbodiedSkills, a unified framework that treats each skill decision as an execution proposal: the runtime…

---

### [REFACTOR-VLA: Unsupervised Library Learning of Typed Motor Programs](https://arxiv.org/abs/2609.01215v1)

- **arXiv**: `2609.01215v1`  |  **提交日期**: 2026-09-01
- **作者**: Riyaaz Shaik, Chandru Venkataraman

Most vision-language-action (VLA) models -- OpenVLA, $π_0$, RT-2, RDT-1B -- are monolithic: they emit raw motor commands or short action chunks without organizing behavior into reusable abstractions, so they degrade on long-horizon tasks and resist interpretation. Existing skill-discovery methods sidestep the core question of when two action sequences are behaviorally equivalent, either clustering contrastive embeddings or delegating the judgment to a language model uncalibrated to the robot's dynamics. We introduce REFACTOR-VLA, a wake/sleep system for learning reusable skills. Its sleep…

---

### [Knowing When to Stop: Adaptive Action Chunking via Internal Cross-Attention Dynamics in VLAs](https://arxiv.org/abs/2609.00908v1)

- **arXiv**: `2609.00908v1`  |  **提交日期**: 2026-09-01
- **作者**: Runze Xu, Xiaolong Shan, Shuang Dai, Yu Wang, Jincheng Yu

Action chunking is a standard execution strategy in modern Vision-Language-Action (VLA) frameworks, but fixed execution horizons impose a trade-off between efficiency and accuracy. Short chunks require frequent inference and may cause oscillatory behavior, whereas long chunks can become misaligned with newly observed states. We address this limitation with an adaptive action chunking approach based on internal cross-attention dynamics in the action expert. We observe that, as the prediction horizon extends, action-to-observation cross-attention becomes increasingly dispersed and its entropy…

---

## 📅 2026-09-01

### [Temporal Forcing: 4D Representation Alignment for Vision-Language-Action Models](https://arxiv.org/abs/2608.30643v1)

- **arXiv**: `2608.30643v1`  |  **提交日期**: 2026-08-31
- **作者**: Xingyu Ding, Yuzhong Zhao, Chunhai Zhao, Yinghuan Shi, Chaoyang Zhao, Yifan Zhang

Recent vision-language-action (VLA) methods improve manipulation performance by aligning their representations with 3D scene geometry. However, these methods often struggle with long-horizon manipulation and observation aliasing between visually similar states due to a lack of temporal information: the 3D scene geometry captures only the current state, rather than how it has evolved over time. To resolve this, we present Temporal Forcing, a 4D representation alignment method for VLA models. Specifically, we first introduce a history pathway that enables a vanilla VLA model to summarize…

---

### [Behavior-Skill: A Fine-Grained Benchmark for Evaluating Vision-Language-Action Policies in Long-Horizon Tasks](https://arxiv.org/abs/2608.30536v1)

- **arXiv**: `2608.30536v1`  |  **提交日期**: 2026-08-31
- **作者**: Chunyun Ma, Lun Luo, Xingjian Luo, Xiexing Feng, Hang Zhang, Wei Liu et al.

Reliable execution of long-horizon mobile manipulation tasks remains challenging because overall task success depends on the successful completion of multiple constituent skills. Existing benchmarks, however, still rely primarily on full-task rollouts and aggregate task-level metrics, making intermediate failures difficult to observe and analyze. We present Behavior-Skill, a benchmark that reformulates the learning and evaluation of long-horizon tasks around executable constituent skills. It contains 235,492 skill instances from 10,000 demonstrations across 50 household tasks and 34 semantic…

---

### [PAVE: Predictive Alignment and Value-Guided Evolution for World-Action Policies](https://arxiv.org/abs/2608.30378v1)

- **arXiv**: `2608.30378v1`  |  **提交日期**: 2026-08-31
- **作者**: Botong Zhao, Fang Yu,  Tim, Senhua Zhu, Xinyuan Chen, Yue Lu

Direct vision-language-action policies generate continuous robot actions efficiently, but standard behavior cloning leaves two complementary gaps: their representations are not explicitly required to describe how the scene evolves over multiple time scales, and deployment trajectories of unequal quality are often reused without separating useful dynamics from undesirable behavior. We introduce \method, a direct world-action policy that combines outcome-agnostic predictive learning with outcome-aware policy improvement. \method first retains a local fixed-offset JEPA objective and adds…

---

### [CometVLA: Co-Training on an Embodied Data Pyramid towards Physical Understanding](https://arxiv.org/abs/2608.30289v1)

- **arXiv**: `2608.30289v1`  |  **提交日期**: 2026-08-31
- **作者**: Hanwen Wan, Dafeng Chi, Linbo Zhai, Tianao Shen, Yuzheng Zhuang, Tianle Zhang et al.

Vision-language-action (VLA) models remain brittle in manipulation tasks that require physical commonsense. Current physical VQA data is typically disembodied and misaligned with robot action domains. Egocentric videos are used only as auxiliary pre-training. It remains unclear whether improved VLM physical understanding actually benefits downstream action generation. Therefore, we present CometVLA to close this gap. We construct CometData and CometBench, an embodied physical VQA corpus and benchmark strictly aligned with the robot's action data and embodiment. We introduce Global Action…

---

### [Rethinking Language's Role in Efficient VLA for Autonomous Vehicles: Toward Smarter, Trustworthy Driving](https://arxiv.org/abs/2608.30144v1)

- **arXiv**: `2608.30144v1`  |  **提交日期**: 2026-08-31
- **作者**: Tongfei Guo, Lili Su

Vision-Language-Action (VLA) models are reshaping autonomous driving (AD) by unifying perception, reasoning, and control through language, enabling semantic grounding, interpretable decisions, and better long-tail generalization. But language is expensive onboard: latency and memory budgets are tight, and autoregressive decoding is inherently sequential. This work reframes the central question as when and where language should act at inference, since inference cost recurs at every deployed frame while training cost is paid once. We introduce the Language Residue taxonomy to organize methods…

---

### [Aligning Multi-Trajectory Supervision with Policy Optimization for VLA Driving](https://arxiv.org/abs/2608.30122v1)

- **arXiv**: `2608.30122v1`  |  **提交日期**: 2026-08-31
- **作者**: Tian Zhang, Zhuo Huang, Hongrui Ye, Yu Wu, Zengmao Wang, Kaixuan Zhou

Vision-language-action (VLA) driving methods increasingly combine multi-trajectory imitation learning with group-relative policy optimization (GRPO), making trajectory selection critical to final performance. However, some high-scoring trajectories that improve imitation can degrade subsequent GRPO by inducing advantage estimates misaligned with the current policy's feasible behavior distribution, driving updates away from safe and compliant behaviors. To address this, we propose a novel framework that aligns multi-trajectory supervision with policy optimization. To address the policy…

---

### [Training-Free Action Correction for VLA Model Failures via Language Feedback](https://arxiv.org/abs/2608.29967v1)

- **arXiv**: `2608.29967v1`  |  **提交日期**: 2026-08-30
- **作者**: Owen Kwon, Pablo Ortega-Kral, Arthur Bucker, Jean Oh

Vision-Language-Action (VLA) models demonstrate strong semantic understanding yet exhibit systematic failures during deployment. The conditions under which these failures occur, and whether they can be corrected without retraining, remain poorly understood. In this paper, we take steps toward addressing this gap. We present CorrectVLA, a framework that translates task-level natural language corrections into additive action magnitude adjustments without modifying policy weights. A human provides a single task-level correction, applied uniformly across all rollouts without per-episode…

---

### [SymVD: Symmetric Vision Language Action Distillation for Robot Manipulation](https://arxiv.org/abs/2608.29828v1)

- **arXiv**: `2608.29828v1`  |  **提交日期**: 2026-08-30
- **作者**: Hyewon Choi, Donggyu Kim, Soojean Han

While pretrained Vision-Language-Action (VLA) models offer broad generalization capabilities in robotic manipulation tasks, adapting them to real-world environments or handling task shifts often requires substantial additional data and retraining. To address this, we propose Symmetric VLA Distillation (SymVD), a distillation framework that transfers knowledge from a large VLA teacher to a compact student policy by explicitly exploiting geometric symmetries in manipulation tasks, such as rotational and reflectional invariance. SymVD employs an equivariant actor-critic architecture and trains…

---

### [DriftingVLA: Native One-Step Vision-Language-Action Generation via Per-Dimension Temporal Drifting](https://arxiv.org/abs/2608.29749v1)

- **arXiv**: `2608.29749v1`  |  **提交日期**: 2026-08-30
- **作者**: Yuxuan Gao, Shiqi Zhang, Yedong Shen, Yifan Duan, Wenhao Yu, Xin Zhang et al.

Conventional flow-based vision-language-action (VLA) models support expressive continuous action generation but rely on multi-step refinement to produce each action chunk, increasing latency in online robot control. To address this issue, we introduce DriftingVLA, a native one-step VLA that generates a complete action chunk with a single action-expert forward pass. Rather than learning a flow field that requires iterative integration at inference, DriftingVLA uses a distribution-drifting objective to learn a direct noise-to-action-chunk mapping for one-step deployment. Since robot action…

---

### [AGM: Achievement-Grounded Memory for Closed-Loop Agents with Frozen VLA Policies](https://arxiv.org/abs/2608.29537v1)

- **arXiv**: `2608.29537v1`  |  **提交日期**: 2026-08-30
- **作者**: Hongbo Gao, Zeyu Ni, Xin Wen, Siyu Xu, Ruifeng Li

Frozen vision-language-action (VLA) policies offer broad manipulation skills but execute open-loop action chunks without tracking task progress, so the agent cannot reliably decide whether to continue, retry, or terminate. External memory is a natural remedy, yet it can be harmful when attempted actions are treated as completed progress, turning local execution errors into persistent task-state errors. We propose Achievement-Grounded Memory (AGM), a lightweight closed-loop framework for frozen VLA policies that represents a task as a subgoal sequence with a progress pointer and advances this…

---

### [SMILE: Smooth Motion for Improved Long-Horizon VLA Execution](https://arxiv.org/abs/2608.29432v1)

- **arXiv**: `2608.29432v1`  |  **提交日期**: 2026-08-29
- **作者**: Jongwoo Park, E-Ro Nguyen, Kanchana Ranasinghe, Cristina Mata, Xiang Li, Michael S Ryoo

Vision-Language-Action (VLA) models reduce inference cost by executing multiple actions per call, but longer horizons often degrade accuracy because raw chunks contain jitter and outliers. We introduce SMILE, an architecture-preserving interface that predicts B-spline coefficients and decodes them into smooth action sequences. SMILE changes only the action representation, enabling longer fixed horizons while retaining each baseline's backbone and model scale. We apply SMILE to SmolVLA, Evo1, VPP, and DAWN, improving accuracy and amortized inference efficiency across LIBERO, CALVIN, and…

---

### [AdaVLA: Adaptive Step Flow Matching for Training-free Acceleration of Vision-Language-Action Models](https://arxiv.org/abs/2608.29208v1)

- **arXiv**: `2608.29208v1`  |  **提交日期**: 2026-08-29
- **作者**: Sunghwan Han, Youngtae Han, Youngmin Yi

Vision-Language-Action (VLA) models, built upon Vision-Language Models (VLMs), have significantly enhanced robotic capabilities by leveraging internet-scale knowledge and multimodal reasoning. However, the intensive computational overhead of VLAs constrains on-device deployment, hindering real-time responses to environmental changes. While various acceleration techniques have been proposed, they often rely on fine-tuning or access to training datasets, which are frequently unavailable due to privacy and proprietary concerns. Moreover, although flow-matching-based VLAs have emerged as…

---

### [DREAM: Deployment-Time Demonstration Generation via Real-to-Sim for Scalable Policy Adaptation](https://arxiv.org/abs/2608.29078v1)

- **arXiv**: `2608.29078v1`  |  **提交日期**: 2026-08-29
- **作者**: Makoto Sato, Tatsuya Matsushima, Yutaka Matsuo, Yusuke Iwasawa

Vision-language-action (VLA) models have made strong progress in language-conditioned robot manipulation, but improving their performance in a new workspace still often requires action-labeled data from that environment. Collecting such data by human teleoperation is costly, especially when each workspace, object arrangement, or task may require new demonstrations. We present DREAM, a framework that generates fine-tuning data for a pretrained VLA from a captured workspace and a language instruction, without requiring a task-specific human demonstration. DREAM reconstructs the workspace,…

---

### [A Degradation-Tolerance Benchmark for Camera-Only End-to-End Driving](https://arxiv.org/abs/2608.29005v1)

- **arXiv**: `2608.29005v1`  |  **提交日期**: 2026-08-29
- **作者**: Haohua Que, Handong Yao

Camera-only end-to-end (E2E) driving models are nearing deployment, where the camera stream is degraded by blur, noise, low light, weather, frame loss, and memory faults. How much a policy tolerates before its driving breaks is unclear. Corruption-robustness benchmarks target detection or bird's-eye-view perception, not the planning output that drives the car. We present DriveDegrade, a benchmark for image-degradation tolerance in camera-only E2E driving. Sixteen corruption families at five severities are injected on the fly inside the image loader, one operator reaching fifteen policies, and…

---

## 📅 2026-08-31

### [DeicticVLA: Unifying Instruction Modes Based on Language and Deictic Gestures in a Single VLA](https://arxiv.org/abs/2608.28108v1)

- **arXiv**: `2608.28108v1`  |  **提交日期**: 2026-08-28
- **作者**: Kango Yanagida, Tatsuya Aoki, Yuichiro Yoshikawa, Takato Horii

Vision-Language-Action models (VLAs) allow users to specify manipulation tasks in natural language, but distinguishing a target or placement goal among objects of the same category or similar appearance requires detailed expressions that VLAs may not use reliably. We propose DeicticVLA, which canonicalizes Language Instruction (LI), Vision-Language Instruction (VLI), and Visual Instruction (VI) into a text prompt and deictic masks through text-prompt completion and deictic gesture grounding, enabling a single pretrained VLA to handle all three instruction modes. With a shared backbone,…

---

## 📅 2026-08-28

### [FlashVLA: Streaming Action Decoding for Fast and Asynchronous VLA Inference](https://arxiv.org/abs/2608.27384v1)

- **arXiv**: `2608.27384v1`  |  **提交日期**: 2026-08-27
- **作者**: Zekai Li, Jiaming Tang, Zhijian Liu

Vision-Language-Action (VLA) models are increasingly promising for robotic manipulation, yet their real-world deployment remains bottlenecked by high inference latency and unstable asynchronous execution. This challenge is particularly pronounced in flow-matching-based VLA models, where action decoding requires multiple iterative steps conditioned on the VLM context. While efficient inference methods improve control frequency and asynchronous methods reduce execution idle time, existing approaches often fail to jointly achieve low-latency inference and accurate, temporally consistent…

---

### [GRAFT: Grounded and Efficient Online Reinforcement Adaptation for Fine-Grained Robot Manipulation](https://arxiv.org/abs/2608.27079v1)

- **arXiv**: `2608.27079v1`  |  **提交日期**: 2026-08-27
- **作者**: Yibo Qiu, Haoliang Ye, Shu'ang Sun, Zan Huang, Ronald X Xu, Mingzhai Sun

Pretrained vision-language-action (VLA) policies provide strong priors for robot manipulation, yet adapting them online to fine-grained biomedical tasks remains challenging. Task success often hinges on subtle, view-dependent visual cues, while task-level rewards provide little guidance about which regions matter, making it difficult to learn task-relevant visual grounding from limited real-robot interaction. Online adaptation is further constrained by the computational cost of VLA inference and replay-based updates. We introduce GRAFT (Grounded Reinforcement Adaptation for Fast Task…

---

### [TemporalFlow-VLA: Learning Physically Grounded Execution History for Long-Horizon Robot Manipulation](https://arxiv.org/abs/2608.26821v1)

- **arXiv**: `2608.26821v1`  |  **提交日期**: 2026-08-27
- **作者**: Jiarui Yang, Yehao Lu, Yuning Su, Yu Zhong, Yufeng Xie, Yazhou Zhang et al.

Vision-language-action (VLA) models leverage pretrained vision-language representations for robot control, yet simply adding historical frames does not reliably capture recent physical change. This is especially problematic in multi-stage manipulation, where visually similar states may require different actions depending on prior execution. To address this challenge, we present TemporalFlow-VLA, which learns compact execution history through physically grounded temporal supervision. Using recorded robot states, robot geometry, and calibrated cameras, we construct robot-surface temporal flow…

---

### [Decoupling Planning and Control for Instructable Agents](https://arxiv.org/abs/2608.26788v1)

- **arXiv**: `2608.26788v1`  |  **提交日期**: 2026-08-27
- **作者**: Zineng Tang, Kelsey R. Allen, Sjoerd van Steenkiste, Ishita Dasgupta, Alane Suhr

Recent work shows that pre-trained, instruction-tuned vision-language models (VLMs) perform well at mapping from instructions and observations to high-level plans, but struggle to realize such plans as reliable low-latency action sequences in unfamiliar environments. At the same time, world-model controllers excel at fast observation-to-action control, but lack open-ended task guidance. In this work, we combine these strengths into a single system, Instruct-to-Act, where we train a world-model controller to act autonomously at high frequency when conditioned on sparse, higher-latency, and…

---

### [PredVLA: A Sub-Million-Parameter Predictive-Coding Policy for Robot Manipulation](https://arxiv.org/abs/2608.26673v1)

- **arXiv**: `2608.26673v1`  |  **提交日期**: 2026-08-27
- **作者**: Hiroki Sawada, Shunichi Kasahara

Large pretrained vision-language-action models dominate modern robot-manipulation benchmarks, but it remains unclear how much model scale is necessary for strong language-conditioned control, or whether fundamentally different control architectures can remain competitive at much smaller parameter budgets. We present PredVLA, a language-conditioned predictive-coding policy with only 0.68 million trainable network parameters and no robot-data pretraining, whose hierarchical generative recurrent dynamics predict visual features and proprioception while observations influence latent state only…

---

### [FLARE: A Failure-Aware Framework for Autonomous Correction and Recovery in Visual-Language Robotic Manipulation](https://arxiv.org/abs/2608.26645v1)

- **arXiv**: `2608.26645v1`  |  **提交日期**: 2026-08-27
- **作者**: Ganlong Zhao, Zijia Tang, Xingping Chen, Zhanghui Kuang, Ye Tian, Guanbin Li

Vision-Language-Action Models~(VLAs) have demonstrated significant promise in generalizing to complex, long-horizon robotic manipulation tasks. However, their performance remains brittle, as they are typically trained on trajectory-monotonic, failure-free demonstrations. This reliance on ``perfect" data leaves them unable to recover from common execution errors, such as a missed grasp, a dropped object, or an unexpected collision. In this paper, we propose FLARE, a novel framework that endows VLAs with robust error recovery capabilities through a ``Retry" and ``Reset" paradigm. First, we…

---

### [TrapVLA: Trapping Vision-Language-Action Models in Configured Failure Modes](https://arxiv.org/abs/2608.26578v1)

- **arXiv**: `2608.26578v1`  |  **提交日期**: 2026-08-27
- **作者**: Jun-Hui Liu, Kun-Yu Lin, Yi-Lin Wei, Xu-Han Chen, Yinghao Li, Zhuohao Li et al.

This work introduces Configured Failure Trapping, a novel backdoor attack task against Vision-Language-Action (VLA) models, which aims to activate attacks through stealthy textual triggers and induce configured failure modes. Unlike prior backdoor attacks that treat any task failure as a successful attack, Configured Failure Trapping requires the attacker to control how the robot fails (e.g., causing the robot to grasp with a specified positional offset), making it substantially more challenging and hard to detect. To support the new task, we propose an effective data engine for synthesizing…

---

### [LM-X: Explainable Action Modeling with Progress, Event, and Uncertainty Prediction for Generalist Robot Manipulation](https://arxiv.org/abs/2608.25757v2)

- **arXiv**: `2608.25757v2`  |  **提交日期**: 2026-08-26
- **作者**: Jin Lou, Zhiyuan Jing, Andong Chen, Xupeng Wang, Yuan Xu, Yuexuan Li et al.

Generalist vision--language--action (VLA) policies learn long-horizon behavior mainly through short-horizon action prediction and reveal little beyond sampled commands. This creates two coupled bottlenecks: a single action target must implicitly absorb task progress, intermediate intent, and local reliability, while these control states remain hidden during execution. Inspired by functional principles of biological sensorimotor control, we introduce LM-X , which organizes prediction across task, event, and motor scales without claiming anatomical correspondence. Three explicitly supervised…

---

## 📅 2026-08-27

### [StreamPI: Streaming Multimodal Temporal Modeling for Vision-Language-Action Models](https://arxiv.org/abs/2608.26067v1)

- **arXiv**: `2608.26067v1`  |  **提交日期**: 2026-08-26
- **作者**: Zhe Liu, Jinghua Hou, Yuxiang Lu, Zhenya Yang, Xianzhe Fan, Junwei Luo et al.

Vision-Language-Action (VLA) models have demonstrated effectiveness in robot manipulation, yet state-of-the-art models such as pi0.5 operate under a single-frame paradigm, limiting their ability to retain past observations and develop precise spatial perception. In this paper, we propose StreamPI, a streaming multimodal temporal modeling framework that equips single-frame VLA with temporal reasoning capability without introducing any additional parameters. One core design is instruction-anchored temporal modeling. It treats each (visual observation, language instruction) pair as an atomic…

---

### [One Policy, Many Embodiments: Unified Camera-Centric Action Geometry Pre-training for Heterogeneous Embodied Manipulation](https://arxiv.org/abs/2608.26058v1)

- **arXiv**: `2608.26058v1`  |  **提交日期**: 2026-08-26
- **作者**:  Xiaomi Embodied Intelligence Team, University of Macau,  :, Shaoqing Xu, Fang Li, Guozhi Zhan et al.

Scaling generalist vision-language-action (VLA) policies is severely bottlenecked by the inherent heterogeneity of embodied data, which spans diverse robot morphologies, camera configurations, and low-level action spaces. Existing paradigms typically address this mismatch through explicit action retargeting, human-to-robot video synthesis, or dataset-specific adaptation branches, fundamentally hindering the joint learning of a unified policy. We introduce UCAG-P, a camera-centric unified action formulation that structurally aligns heterogeneous embodied datasets into a shared geometric action…

---

### [MA-VLA: Multi-Arm Vision-Language-Action Model for Collaboration and Compositional Generalization](https://arxiv.org/abs/2608.25864v1)

- **arXiv**: `2608.25864v1`  |  **提交日期**: 2026-08-26
- **作者**: Zaibin Zhang, Junlan Xiao, Zhongbo Zhang, Yifan Wang, Li Kang, Yiran Qin et al.

Multi-arm collaboration is becoming a core capability in embodied manipulation. Recent vision-language-action (VLA) models integrate perception, language, and control, but most represent language as a single global instruction and do not provide an explicit mechanism for assigning and composing arm-specific behaviors. This design limits transfer to collaboration patterns that differ from those observed during training. We present MA-VLA, a unified framework for multi-arm collaboration via atomic action assignment. MA-VLA decomposes cooperative behavior into mid-level atomic prompts and…

---

### [TacForcing: Streaming Action Generation with Execution-Time Tactile Feedback](https://arxiv.org/abs/2608.25798v1)

- **arXiv**: `2608.25798v1`  |  **提交日期**: 2026-08-26
- **作者**: Jianbo Zhou, Boyuan Zhao, Yuzheng Zhang, Yiyang Chen, Wenxin Chen, Qiuyue Li et al.

Contact-rich manipulation requires adapting to contact states that can evolve substantially within an action horizon. However, chunk-based vision-language-action models predict complete action chunks from observations collected before execution, leaving tactile conditioning stale during execution. Existing tactile-reactive approaches typically rely on separate high-frequency controllers, which increase both architectural and training complexity. In this paper, we introduce TacForcing, a streaming action-generation framework that effectively incorporates execution-time tactile feedback.…

---

### [LM-X: Explainable Action Modeling with Progress, Event, and Uncertainty Prediction for Generalist Robot Manipulation](https://arxiv.org/abs/2608.25757v1)

- **arXiv**: `2608.25757v1`  |  **提交日期**: 2026-08-26
- **作者**: Jin Lou, Jingxuan Zhu, Andong Chen, Xupeng Wang, Yuan Xu, Yuexuan Li et al.

Generalist vision--language--action (VLA) policies learn long-horizon behavior mainly through short-horizon action prediction and reveal little beyond sampled commands. This creates two coupled bottlenecks: a single action target must implicitly absorb task progress, intermediate intent, and local reliability, while these control states remain hidden during execution. Inspired by functional principles of biological sensorimotor control, we introduce LM-X , which organizes prediction across task, event, and motor scales without claiming anatomical correspondence. Three explicitly supervised…

---

### [GaussianDream++: Efficient 3D Gaussian World Modeling for Robotic Manipulation](https://arxiv.org/abs/2608.25659v1)

- **arXiv**: `2608.25659v1`  |  **提交日期**: 2026-08-26
- **作者**: Yuqing Jiang, Zijian Zhang, Weitao Zhou, Jiawei Wang, Junjie He, Lei Yang et al.

Vision-Language-Action (VLA) policies have advanced language-conditioned robotic manipulation, yet action-imitation objectives provide only weak supervision for metric 3D structure and short-horizon physical evolution. Geometry-enhanced policies mainly improve current-scene grounding, whereas predictive policies often model future dynamics in RGB or latent spaces and may incur substantial deployment cost. GaussianDream demonstrates that training-time current Gaussian reconstruction and future Gaussian prediction provide effective 3D supervision, but its dense VGGT/TGE-based prefix jointly…

---

### [RA-VLA: Retrieval-Augmented VLA for Test-Time Adaptation](https://arxiv.org/abs/2608.25585v1)

- **arXiv**: `2608.25585v1`  |  **提交日期**: 2026-08-26
- **作者**: Sanghwan Jang, Minjin Jeon, Minsoo Kim, Seongjin Choi, Dongha Kim, Hwanjo Yu

Vision-Language-Action (VLA) models provide a versatile foundation for general robotic manipulation, yet they exhibit significant brittleness when confronted with novel task distributions. While In-Context Imitation Learning (ICIL) offers a training-free alternative, existing frameworks suffer from an adaptation bottleneck that hinders the effective translation of expert context to executable actions. This failure originates from superficial retrieval mechanisms and an inherent behavioral inertia that anchors the policy to its pre-trained priors. To address these limitations, we present…

---

### [A Taxonomy of Construction Task Activities for Robot Workers](https://arxiv.org/abs/2608.25395v1)

- **arXiv**: `2608.25395v1`  |  **提交日期**: 2026-08-26
- **作者**: Sadman Sakib, Zhangyi None Peng, Yujie Pang, Yu Otsuki, Mohammad Abdullah Al Faruque

Recent vision-language-action models offer a path toward robots with broader repertoires than conventional task-specific systems. Construction deployment, however, requires a precise inventory of worker activities and the capabilities needed to execute them. We present TARCAT, an occupation-grounded taxonomy derived from 91 O*NET tasks across seven high-employment construction occupations and 30 instructional videos of physical work. TARCAT defines 41 action primitives in 12 groups and three classes and provides a mechanism for composing parameterized primitive sequences into reusable skills.…

---

### [V-Link: Recovering Lost Visual Representations in Action DiT for Vision-Language-Action Models](https://arxiv.org/abs/2608.25308v1)

- **arXiv**: `2608.25308v1`  |  **提交日期**: 2026-08-26
- **作者**: Yehao Lu, Jiarui Yang, Yuning Su, Yufeng Xie, Yu Zhong, Yazhou Zhang et al.

Vision-language-action (VLA) models provide a scalable path toward generalist robotic manipulation by integrating visual perception, language understanding, and continuous action control. However, we reveal a critical limitation of VLA architectures: the action expert has limited access to the 3D geometric and 2D semantic information available in VLM features. This accessibility gap weakens perceptual grounding and limits performance on fine-grained robotic manipulation. To address this issue, we propose V-Link, which explicitly recovers visual representations during the vision-language (VL)…

---

### [GaussVLA: Geometry-Aware Spatial Reasoning for Vision-Language-Action Model](https://arxiv.org/abs/2608.24959v1)

- **arXiv**: `2608.24959v1`  |  **提交日期**: 2026-08-25
- **作者**: Md Selim Sarowar, Md Tanvir Islam, Sungho Kim, Sangtae Ahn

Vision-Language-Action (VLA) models encode visual observations as flat 2D patch tokens that carry no intrinsic geometric structure, and augmenting them with dense monocular depth injects per-pixel scalar values that encode neither surface orientation nor geometric confidence. This leaves the policy with limited structured spatial reasoning for action prediction. We propose GaussVLA, a Mamba-based VLA that incorporates two custom modules: Gaussian Spatial Tokenizer (GST) to lift frozen semantic and depth features into compact 3D Gaussian tokens, pools geometrically salient regions with learned…

---

## 📅 2026-08-26

### [Gripper-aware Vision Language Action Models](https://arxiv.org/abs/2608.24603v1)

- **arXiv**: `2608.24603v1`  |  **提交日期**: 2026-08-25
- **作者**: Hanyi Zhang, Zihong Luo, Tianyu Li, Khang Nguyen, Basu Hela, Shreyas Kumar et al.

Vision language action models (VLAs) have advanced general purpose robotic grasping and manipulation by enabling robots to interpret visual observations and natural language instructions to generate executable action sequences. However, existing VLAs often implicitly assume gripper invariance, despite grasping strategies being inherently embodiment-dependent. Different gripper types, such as parallel-jaw and suction, usually require distinct interaction strategies to achieve the same grasping objective. Moreover, current datasets for VLAs predominantly rely on parallel-jaw grippers, limiting…

---

### [PonderPounce: A Pretrained MLLM as an Episode Context Engine for Robot Control](https://arxiv.org/abs/2608.24115v1)

- **arXiv**: `2608.24115v1`  |  **提交日期**: 2026-08-25
- **作者**: Suhwan Choi, Jaeyoon Jung, Sungkyung Kim, Yunsung Lee, Youngjae Yu

Multimodal large language models (MLLMs) can integrate long visual histories, reason under partial observability, and infer behavior from a few examples. Yet vision-language-action (VLA) models generally inherit pretrained representations without using this contextual capacity as episode memory. Memory-dependent policies address this gap through purpose-built history mechanisms. PonderPounce instead reuses an MLLM's native causal context as robot memory. Ponder, a System2 MLLM, accumulates episode observations, demonstrations, and prior cognition in its native causal context and can generate…

---

### [TrAct: Bridging Robot Control and Visual Prediction with Visual Tracks](https://arxiv.org/abs/2608.24101v1)

- **arXiv**: `2608.24101v1`  |  **提交日期**: 2026-08-25
- **作者**: Zhi Cao, Howard Ji, Kevin Zhang, Kuangzhi Ge, Li Fei-Fei, Jiajun Wu et al.

Robot actions are inherently embodiment-specific and only weakly aligned with image-space visual changes, limiting their effectiveness as conditioning signals for robot world models. In contrast, visual tracks provide an embodiment-agnostic representation of how task-relevant points move through a scene, offering dense image-space guidance for accurate and spatially precise future video prediction. Building on this observation, we propose TrAct, a world-model-based robot decision-making framework that uses visual tracks as an intermediate interface between control and prediction. TrAct…

---

### [Hierarchical Skill Retrieval for Data-Efficient Adaptation of Vision-Language-Action Models](https://arxiv.org/abs/2608.24042v1)

- **arXiv**: `2608.24042v1`  |  **提交日期**: 2026-08-25
- **作者**: Haoran Hao, Shahram Najam Syed, Jeff Schneider, Jeffrey Ichnowski

While Vision-Language-Action (VLA) models pretrained on large-scale robot datasets provide a strong foundation for robot manipulation, their performance can degrade when adapted to new tasks with limited task-specific demonstrations. Retrieval offers a practical way to reuse existing demonstrations for data-efficient adaptation, but existing methods often rely on visual similarity, state-action representations, or task-level language matching. These approaches may overlook the hierarchical structure of long-horizon manipulation tasks, where complete task matches are rare but reusable skills…

---

## 📅 2026-08-25

### [Act with Intent: Distilling Behavior Intent for Vision-Language-Action Models](https://arxiv.org/abs/2608.23478v1)

- **arXiv**: `2608.23478v1`  |  **提交日期**: 2026-08-24
- **作者**: Sangoh Lee, Sangwoo Mo, Wook-Shin Han

Vision-Language-Action (VLA) models can turn multimodal context into robot actions, but their action decoders are still trained largely by behavior cloning. This supervises which motor command was demonstrated while leaving implicit the local objective served by the behavior under the instruction. Future-based supervision enriches action learning with frames, latent observations, trajectories, or motion representations, but these signals capture particular realizations of what may happen rather than the shared semantic objective of the forthcoming behavior. We propose Intention Distillation…

---

### [ROS2SmolVLA: Enabling Small Vision-Language-Action Models for Integration into Industrial-Grade Lightweight Robots](https://arxiv.org/abs/2608.23320v1)

- **arXiv**: `2608.23320v1`  |  **提交日期**: 2026-08-24
- **作者**: Nils Mandischer, Noah Böckmann, Ludwig Holl, Lars Mikelsons

Industrial demand changes the paradigms of production. Due to smaller batch sizes and more variations in products, companies face a growing challenge to adopt more adaptive production systems. In particular, robot-based automation is usually static and fails to respond to constantly changing processes. Vision-Language-Action (VLA) Models are a promising opportunity to mitigate this challenge by generating robot actions based on the observed system state. However, current research either focuses on large models that cannot be computed on premise, creating compliance and security challenges, or…

---

### [Think Only When Needed: Prompt-Authority Control for Selective Slow-Path Intervention in Vision-Language-Action Manipulation](https://arxiv.org/abs/2608.23224v1)

- **arXiv**: `2608.23224v1`  |  **提交日期**: 2026-08-24
- **作者**: Zhiruo Zhou, Zelin Li, Xiwen Chen, Jiazhuo Li, Chenwei Wang, Huiming Chen et al.

Retrieval can efficiently and effectively augment a frozen vision--language--action (VLA) policy without retraining, yet retrieved text becomes a control intervention once it enters the executed prompt. In a matched audit, raw appended text reduces mean success from 92.47\% to 3.00\%, while meaningful and length-matched meaningless appends both fail on all 500 states. This result identifies \emph{prompt-form collapse}: changing the instruction form, rather than adding useful semantics, can dominate execution. We introduce TOWN-VLA (Think Only When Needed), a prompt-authority interface that…

---

### [Pointing-VLA: Typed Spatial Grounding Interfaces for Vision-Language-Action Manipulation](https://arxiv.org/abs/2608.23138v1)

- **arXiv**: `2608.23138v1`  |  **提交日期**: 2026-08-24
- **作者**: Xiwen Chen, Zelin Li, Zhiruo Zhou, Huiming Chen, Chenwei Wang, Xiaojun Zhu

Vision-language-action (VLA) models often expose spatial grounding through autoregressive text coordinates or opaque action tokens, creating brittle interfaces between multimodal reasoning and robot execution. We present Pointing-VLA, a typed hidden-state spatial readout built on Embodied-R1. Geometry-specific heads predict normalized points, object-functional grounding (OFG) heatmaps, and visual trajectories without serializing geometry as text. For the evaluated Bridge/WidowX and physical pick-place deployments, an explicit execution contract assigns PICK to source-conditioned OFG and PLACE…

---

### [InstructMove: A Text-Indispensable Benchmark for Instruction-Following Manipulation](https://arxiv.org/abs/2608.22990v1)

- **arXiv**: `2608.22990v1`  |  **提交日期**: 2026-08-24
- **作者**: Mengao Zhao, Ziang Li, Chaodong Huang, Mengchen Ma, Haoyi Jiang, Yiwei Jin et al.

Vision-language-action (VLA) models have made general-purpose robot manipulation increasingly plausible by conditioning robot actions on natural-language instructions. A key test of such generality is whether policies actually follow language instructions. Yet many manipulation benchmarks leave this ability underdetermined: the intended object or destination is often visually salient or uniquely feasible, allowing policies to succeed without grounding the instruction. We argue that instruction-following evaluation should be text-indispensable: multiple actions should be visually and…

---

### [UniMem: Unifying Multimodal Memory and Control for Vision-Language-Action Models](https://arxiv.org/abs/2608.22869v1)

- **arXiv**: `2608.22869v1`  |  **提交日期**: 2026-08-24
- **作者**: Lars Osterberg, Maggie Wang, Mac Schwager

While Vision-Language-Action (VLA) models have leveraged internet-scale pretraining and task-focused finetuning to achieve strong performance on long-horizon tasks, they often struggle with non-Markovian tasks that require memory. Existing approaches to memory typically involve additional Vision-Language-Models (VLMs) for long-term memory management, introducing a memory bottleneck and a fractured training pipeline. Conditioning on multiple historical frames can provide the VLA with access to more descriptive features of past scenes, but can degrade performance if frames are chosen at…

---

### [Triplet2Track: A Hierarchical System with Object-Centric Representations for Reliable Long-Horizon Manipulation](https://arxiv.org/abs/2608.22800v1)

- **arXiv**: `2608.22800v1`  |  **提交日期**: 2026-08-24
- **作者**: Jianxiang Liu, Gaojing Zhang, Chuan Wen, Qipeng Liu, Yuxuan Zhao, Ning Guo et al.

Ensuring reliability in uncertain environments remains difficult for long-horizon robotic manipulation. End-to-end VLA models are data-heavy and opaque, making diagnosis and verification difficult. Hierarchical pipelines are more interpretable, but their plans are often weakly grounded in observations, weakly aligned with low-level actions, and computed without online feedback, leading to open-loop behavior and hallucinations. To address these issues, we introduce the Triplet-to-Track System (TTS), a closed-loop long-horizon imitation learning system that uses human videos to reduce reliance…

---

### [Robust Bimanual Vision-Language-Action Models via Embarrassingly Simple Modality Masking](https://arxiv.org/abs/2608.22419v1)

- **arXiv**: `2608.22419v1`  |  **提交日期**: 2026-08-23
- **作者**: Dongzhou Cheng, Ziang Li, Yixiao Zhou, Haojuan Li, Jinghao Zhang, Lei Lei et al.

Query-based Vision-Language-Action (VLA) models offer low-latency inference that is attractive for bimanual robotic manipulation, but we observe that they can still exhibit discontinuous actions and execution failures in complex dual-arm tasks. We hypothesize that unstable multi-view and language fusion is one contributing factor in these failures, often coinciding with attention spreading to distracting regions. To improve robustness, we introduce the Modality Masking Mechanism (M3), an embarrassingly simple, training-only strategy that requires no architectural changes or large-scale robot…

---

### [CIDER: Continual Interactive Distillation for Embodied Reinforcement Learning](https://arxiv.org/abs/2608.21899v1)

- **arXiv**: `2608.21899v1`  |  **提交日期**: 2026-08-22
- **作者**: Houlin Li, Minghui Xu, Guo Xu, Xuan Du, Xiaohan Yan, Chun Wang et al.

Human-in-the-loop real-world reinforcement learning enables rapid acquisition of effective robotic manipulation policies for individual tasks, often within tens of minutes. Yet it remains unclear how to extend this paradigm to continual learning, where a single policy must acquire new skills without losing previously learned behaviors. Existing real-world continual learning methods do not explicitly constrain prior behaviors, leading to severe catastrophic forgetting. We introduce Continual Interactive Distillation for Embodied Reinforcement Learning (CIDER), a continual reinforcement…

---

### [CounterAlign: Counterfactual Supervision for Vision-Language-Action Models](https://arxiv.org/abs/2608.21740v1)

- **arXiv**: `2608.21740v1`  |  **提交日期**: 2026-08-22
- **作者**: Haru Kondoh, Kei Ota, Asako Kanezaki, Yueh-Hua Wu

Vision-Language-Action (VLA) models are typically trained with behavior cloning (BC) on expert demonstrations. However, BC provides only positive supervision for expert actions, without explicit negative supervision indicating which actions are instruction-inconsistent or otherwise inappropriate. Reinforcement learning (RL) can provide such corrective signals, but often relies on externally specified rewards or curated non-expert data, both of which are costly to obtain in robotics. We show that offline RL for VLA models need not rely on curated non-expert trajectories: successful expert…

---

## 📅 2026-08-24

### [Just Noticeable Difference Modeling for Token Compression in Vision-Language-Action Models](https://arxiv.org/abs/2608.21247v1)

- **arXiv**: `2608.21247v1`  |  **提交日期**: 2026-08-21
- **作者**: Zhuoyuan Li, Rui Zhao, Jin Wang, Hanwei Zhu, Cong Zhang, Giuseppe Valenzise et al.

Token compression has become a key technique for reducing the inference cost of large foundation models, with approaches such as token pruning and KV-cache reuse widely adopted in vision-language models and recently explored for embodied agents. In embodied agents, tokens not only support perception and semantic understanding but also directly affect latency-sensitive closed-loop robot action prediction. Existing schemes typically guide compression using redundancy or importance cues, such as visual similarity, attention scores, and saliency. However, these cues only indirectly measure the…

---

### [PhysCaP: Grounding Code-as-Policy Agent with Physics-Informed Exploration](https://arxiv.org/abs/2608.21031v1)

- **arXiv**: `2608.21031v1`  |  **提交日期**: 2026-08-21
- **作者**: Chen-Yu Lin, Jing-Wen Chen, Hsueh-En Chang, Hung-An Chen, Sheng-Hsun Chang, Chi-Pin Huang et al.

We present PhysCaP, a Physics-Informed Code-as-Policy agent for active perception in robotic manipulation. While vision-language-action policies excel at imitating demonstrations, they rely on passive observation and fail to infer latent physical properties critical for manipulation. PhysCaP augments code-as-policy frameworks with a physics-informed exploration layer that enables explicit information-seeking through interaction. It introduces training-free physical property extraction modules that estimate object mass and stiffness from robot proprioception without additional sensors. To…

---

### [A Collaborative Multi-Modality Interaction for VLA-based End-to-End Autonomous Driving](https://arxiv.org/abs/2608.20890v1)

- **arXiv**: `2608.20890v1`  |  **提交日期**: 2026-08-21
- **作者**: Jingtao Sun, Xiaohai He, Yike Zhang, Dong Huang, Yaonan Wang, Ajmal Mian et al.

Vision-Language-Action (VLA) models have emerged as a powerful paradigm for end-to-end autonomous driving by jointly integrating perception, reasoning, and decision making within a unified multimodal framework. However, most existing VLA models formulate end-to-end autonomous driving as a visual question answering task, leading to unreliable and less interpretable decision reasoning. In addition, they fail to establish effective multi-modal interaction across heterogeneous sensors, thereby limiting robust scene perception and reliable driving reasoning in long-tail driving scenarios. To this…

---

### [CertVLA: Certified Defense against Physical Visual Attacks for Vision-Language-Action Models](https://arxiv.org/abs/2608.20791v1)

- **arXiv**: `2608.20791v1`  |  **提交日期**: 2026-08-21
- **作者**: Hui Lu, Zhijie Peng, Yuqi Lin, Zaijia Yang, Jiaming He, Shuhan Ye et al.

Vision-Language-Action (VLA) policies are vulnerable to localized physical perturbations, yet existing certified patch defenses target discrete labels and cannot directly certify continuous, temporally correlated actions. We introduce CertVLA, a certified defense for closed-loop VLA control under bounded patch and texture attacks. CertVLA proposes a calibrated region of behaviorally consistent actions, while deterministic covering masks ensure that at least one checked prediction is attack-free. Specifically, CertVLA normalizes action disagreement by the benign variation of each mask pair and…

---

### [Is Multimodal Speculative Decoding Ready for Diffusion-Based Parallel Drafting? A Survey and Empirical Diagnosis](https://arxiv.org/abs/2608.20743v1)

- **arXiv**: `2608.20743v1`  |  **提交日期**: 2026-08-21
- **作者**: Yantao Li, Huanlin Gao, Fang Zhao, Chao Tan, Qiang Hui, Shuting Liu et al.

Speculative decoding accelerates autoregressive generation by allowing a lightweight drafter to propose future tokens while a target model verifies them in parallel. Its lossless guarantee has motivated a line of work that pushes the drafter itself toward parallel generation. The most recent paradigm is block-parallel generative drafting, including diffusion-based methods such as DFlash and DSpark, achieving up to 3.6x speedup on common daily chatting tasks. While this transition is well studied in text-only LLMs, its applicability to multimodal models remains an open question. Existing…

---

### [ForeTime-VLA: Causal Future-Token Distillation from a World Action Model for Conveyor-Belt Manipulation](https://arxiv.org/abs/2608.20735v1)

- **arXiv**: `2608.20735v1`  |  **提交日期**: 2026-08-21
- **作者**: Siyuan Ma, Yutian Zhang, Boshi Zhang, Qinglian Wu, Jiaqi Zhai, Dong Wei et al.

Manipulating moving objects requires a policy to anticipate contact events, yet vision-language-action (VLA) policies are commonly fine-tuned from the current observation alone. World action models (WAMs) learn predictive dynamics, but running a video-scale teacher or explicitly imagining future frames at deployment is costly. We introduce ForeTime-VLA, a dense pi0.5 policy that distills a future-aware, action-equivalent representation from a frozen Fast-WAM-derived teacher while remaining causal at inference. Offline, current and future video latents are compressed into a whitened 64-D…

---

## 📅 2026-08-21

### [Planning-Oriented End-to-End Autonomous Driving: Architectures, Evaluation, and Emerging Paradigms](https://arxiv.org/abs/2608.20111v1)

- **arXiv**: `2608.20111v1`  |  **提交日期**: 2026-08-20
- **作者**: Yanchen Guan, Xingcheng Liu, Bin Rao, Chengyue Wang, Guofa Li, Yunjian Li et al.

End-to-end autonomous driving has evolved from camera-to-control regression toward planning-oriented systems that use structured representations, trajectory-level outputs, and increasingly realistic evaluation protocols. This survey reviews this transition across behavior cloning, conditional imitation learning, privileged distillation, BEV and vectorized planning, unified perception-prediction-planning architectures, world-model-based planners, and vision-language-action systems. We argue that the key distinction in modern end-to-end driving is not whether intermediate representations are…

---

### [EXIMO: VLM Guided Exploration of VLA Policies](https://arxiv.org/abs/2608.19891v1)

- **arXiv**: `2608.19891v1`  |  **提交日期**: 2026-08-20
- **作者**: Bhavya Sukhija, Oliver Groth, Mohit Shridhar, Tim Hertweck, Michael Bloesch, Markus Wulfmeier et al.

How to efficiently finetune robot policies to learn new tasks on the fly? State of the art robotic manipulation policies are based on behaviour cloning of large vision-language-action (VLA) models with billions of parameters on huge teleoperation datasets. While this simple approach has enabled significant advances for robotic manipulation, finetuning of VLA policies for learning new tasks still remains an open problem. In particular, collecting teleoperation datasets requires hundreds of hours of expensive human labour and the alternative, reinforcement learning (RL), can be notoriously…

---

### [OrthoSkillVLA: Continual Skill Learning via Gradient-Informed Skill Subspace Adaptation](https://arxiv.org/abs/2608.19589v1)

- **arXiv**: `2608.19589v1`  |  **提交日期**: 2026-08-20
- **作者**: Jiaqi Wang, Zhou Fang, Qiongfeng Shi, Yi Zhou

Pretrained Vision-Language-Action models provide a strong foundation for robot learning, but sequentially adapting them to diverse skills can perturb the representations and velocity mappings used by previous skills, leading to catastrophic forgetting. Architecture-based approaches improve retention by isolating skills but lead to increased inference footprint. Recent subspace-constrained methods restrict parameter updates in an orthogonal subspace to minimize interference but impose a unified constraint on the entire model. We analyze the distinct roles of internal VLA components and…

---

### [Fine-Tuning VLAs with Self-Demonstrated Generative Control for Multi-Task Manipulation](https://arxiv.org/abs/2608.19490v1)

- **arXiv**: `2608.19490v1`  |  **提交日期**: 2026-08-19
- **作者**: Prachi Garg, Steve Xing, Prahit Yaugand, Saurabh Gupta, Derek Hoiem

State-of-the-art vision-language-action (VLA) models such as $π_{0.5}$ exhibit strong semantic understanding, instruction following and task behavior. However, when deployed on new robots, even minor mismatches in hardware configuration relative to pretraining can cause severe performance drops. Finetuning the VLA on in-domain expert data from the new embodiment improves performance on the expert task but leads to a loss in its original instruction following and behavioral priors. In this paper, we propose a self-supervised method that generates online interaction rollouts from the zero-shot…

---

### [EATR-Stereo: Embodiment-Aware Token Routing of Paired Stereo Evidence for Humanoid Vision-Language-Action Control](https://arxiv.org/abs/2608.17453v3)

- **arXiv**: `2608.17453v3`  |  **提交日期**: 2026-08-18
- **作者**: Songwei Wu, Rui Zhao, Fan Yang, Zhongqiang Nie, Zhiduo Jiang, Wandong Sun et al.

Long-horizon humanoid vision--language--action (VLA) control with head-mounted stereo cameras requires visual interfaces that can exploit complementary views while maintaining compatibility with pretrained representations. Existing interfaces often discard complementary stereo evidence or fuse additional observations without preserving the native primary-view pathway and adapting auxiliary information to robot embodiment. We present EATR-Stereo, an embodiment-aware token-routing framework that retains primary-view tokens and constructs primary-aligned Cross-View Auxiliary Tokens (CVATs) by…

---

## 📅 2026-08-20

### [GS-VLA: Plug-and-Play Viewpoint Canonicalization for Frozen VLA Policies via Gaussian Splatting](https://arxiv.org/abs/2608.19066v1)

- **arXiv**: `2608.19066v1`  |  **提交日期**: 2026-08-19
- **作者**: Yechan Park, HyunJin Kim

This paper proposes a lightweight, plug-and-play framework that improves robustness to viewpoint shifts in Vision-Language-Action (VLA) policies without policy retraining. To our knowledge, this is the first approach to directly leverage 3D Gaussian-based novel-view synthesis for observation-space adaptation in VLA policies. Current VLA performance relies on the implicit assumption that training and deployment camera configurations are identical. Our experiments show that even a small displacement of the camera mount can reduce the success rate on the LIBERO benchmark from about 90% to about…

---

### [The Embodiment Gap in Robot Foundation Models](https://arxiv.org/abs/2608.18433v1)

- **arXiv**: `2608.18433v1`  |  **提交日期**: 2026-08-19
- **作者**: Yukiyasu Domae, Keisuke Shirai, Hanbit Oh, Ryoichi Nakajo, Tomohiro Motoda, Koshi Makihara et al.

Robot foundation models (RFMs), including vision-language-action (VLA) policies, are often discussed through a scaling view: more data, larger models, and broader benchmarks should improve generalization. In robotics, however, a model can generalize while work still remains before it can run on a robot with a particular body. The work required differs across methods and target robots, and those differences affect practical deployment. We call the gap between reusable models, representations, or data and their use in execution on the target robot the embodiment gap. This survey examines what…

---

### [Role-Conditioned Sub-Token Routing for Efficient Vision-Language-Action Policies](https://arxiv.org/abs/2608.18410v1)

- **arXiv**: `2608.18410v1`  |  **提交日期**: 2026-08-19
- **作者**: Wei Jiang, Wei Wang

Vision-Language-Action (VLA) models process long multimodal token sequences, making inference expensive in both memory and computation. Existing efficiency methods mainly reduce visual tokens, but aggressive token pruning becomes fragile because removing a token discards its entire representation. Sub-token compression provides a complementary alternative by retaining more tokens while reducing their value width. However, directly applying sub-token compression to VLA policies is less effective because information important for perception, language understanding, and control is distributed…

---

### [EATR-Stereo: Embodiment-Aware Token Routing of Paired Stereo Evidence for Humanoid Vision-Language-Action Control](https://arxiv.org/abs/2608.17453v2)

- **arXiv**: `2608.17453v2`  |  **提交日期**: 2026-08-18
- **作者**: Songwei Wu, Rui Zhao, Fan Yang, Zhongqiang Nie, Zhiduo Jiang, Wandong Sun et al.

Long-horizon humanoid vision--language--action (VLA) control with head-mounted stereo cameras requires visual interfaces that can exploit complementary views while maintaining compatibility with pretrained representations. Existing interfaces often discard complementary stereo evidence or fuse additional observations without preserving the native primary-view pathway and adapting auxiliary information to robot embodiment. We present EATR-Stereo, an embodiment-aware token-routing framework that retains primary-view tokens and constructs primary-aligned Cross-View Auxiliary Tokens (CVATs) by…

---

## 📅 2026-08-19

### [Plug-and-Play Traffic Element Awareness for End-to-End Autonomous Driving](https://arxiv.org/abs/2608.18035v1)

- **arXiv**: `2608.18035v1`  |  **提交日期**: 2026-08-18
- **作者**: Zongzheng Zhang, Jijun Wang, Saining Zhang, Shuo Wang, Yiru Wang, Hai Yang et al.

Traffic elements such as traffic lights and road signs play a fundamental role in human driving decisions and should naturally influence end-to-end driving performance. However, existing end-to-end driving research predominantly focuses on dynamic road participants (e.g., vehicles and pedestrians), while the role of traffic elements remains largely unexplored. The community still lacks a systematic study quantifying their impact, largely because public datasets rarely provide structured traffic-element annotations and modern driving systems vary widely in architecture and training paradigm.…

---

### [LIBERO-VIFO: Benchmarking the Capability and Safety of Visual Cue Following in Vision-Language-Action Models](https://arxiv.org/abs/2608.17600v1)

- **arXiv**: `2608.17600v1`  |  **提交日期**: 2026-08-18
- **作者**: Zhengyan Qian, Rui Yan, Alex Jinpeng Wang, Jinhui Tang

Visual cues are increasingly adopted to guide robot learning, but whether Vision-Language-Action (VLA) models can reliably follow authorized cues while disregarding unauthorized ones remains unclear. Existing work covers only a narrow range of cue forms and focuses on final task success, providing only a coarse assessment of cue-following capability. Treating all visual cues as authorized also leaves safety risks of unauthorized following unexplored. To address these gaps, we introduce LIBERO-VIFO, a benchmark to evaluate both the capability and safety of visual cue following in VLA models.…

---

### [Calibrated Predictive Safety for Heterogeneous Robots: An Action-Conditioned JEPA Framework with Model-Based Safety Shields](https://arxiv.org/abs/2608.17496v1)

- **arXiv**: `2608.17496v1`  |  **提交日期**: 2026-08-18
- **作者**: Kaiming Zhong, Tianhua Liu, Yue Wang

Vision-language-action policies generalize broadly but provide no execution-time guarantees; classical model-based planners respect kinematic and geometric constraints but generalize poorly. We study whether an action-conditioned Joint-Embedding Predictive Architecture (JEPA) world model can predict, before execution, both task progress and physical risk for candidate action chunks, and whether coupling these predictions to an embodiment-specific model-based safety shield yields a deployable pipeline for heterogeneous robots. We propose a receding-horizon decision pipeline: (1) a proposer…

---

### [Reuse Before You Retrieve: Diagnosing Headroom and Complementarity for Test-Time Augmentation of Embodied Multimodal Policies](https://arxiv.org/abs/2608.17484v1)

- **arXiv**: `2608.17484v1`  |  **提交日期**: 2026-08-18
- **作者**: Yuhwan Jeong, Kuk-Jin Yoon

Frozen vision-language-action (VLA) policies are increasingly improved at test time by sampling additional policy behaviors or introducing external demonstrations. Yet there is little guidance for deciding which intervention a deployed policy actually needs. Additional sampling is useful only when better behavior already exists within the policy's stochastic rollouts and can be identified, whereas retrieval is most useful when the relevant action prior is not reliably represented by the policy. We study this decision through two measurable factors, recoverable headroom and retrieval…

---

### [EATR-Stereo: Embodiment-Aware Routing of Paired Stereo Evidence for Humanoid Vision-Language-Action Control](https://arxiv.org/abs/2608.17453v1)

- **arXiv**: `2608.17453v1`  |  **提交日期**: 2026-08-18
- **作者**: Songwei Wu, Rui Zhao, Fan Yang, Zhongqiang Nie, Zhiduo Jiang, Wandong Sun et al.

Long-horizon humanoid vision--language--action (VLA) control with head-mounted stereo cameras requires visual interfaces that can exploit complementary views while maintaining compatibility with pretrained representations. Existing interfaces often discard complementary stereo evidence or fuse additional observations without preserving the native primary-view pathway and adapting auxiliary information to robot embodiment. We present EATR-Stereo, an embodiment-aware token-routing framework that retains primary-view tokens and constructs primary-aligned Cross-View Auxiliary Tokens (CVATs) by…

---

### [Prism-GRPO: Faster VLA Policy Optimization via Splitting Same-outcome Groups](https://arxiv.org/abs/2608.17423v1)

- **arXiv**: `2608.17423v1`  |  **提交日期**: 2026-08-18
- **作者**: Zeyun Deng, Yuzhe Lu, Yawei Wang, Linbo Liu, Qing Ping, Han Ding et al.

GRPO is increasingly used for reinforcement learning of vision-language-action (VLA) policies because, unlike PPO, it does not require training a critic. This simplification comes with a sampling cost: group-relative advantages require multiple rollouts from each scene. Under binary success rewards, groups whose rollouts all succeed or all fail have zero advantage and are discarded by dynamic sampling. These groups are especially common early in training, when most rollouts fail, wasting much of the expensive robotic rollout budget. We introduce Prism-GRPO, which augments binary outcome…

---

### [ORPA: Online Residual Policy Adaptation for Robot Manipulation Control with Human Feedback](https://arxiv.org/abs/2608.17323v1)

- **arXiv**: `2608.17323v1`  |  **提交日期**: 2026-08-18
- **作者**: Muhammad A. Muttaqien, Tomohiro Motoda, Ryo Hanai, Yukiyasu Domae

Robotic manipulation policies trained via imitation learning, such as Action Chunking with Transformers (ACT), can achieve strong performance under ideal conditions but often remain sensitive to small execution errors and distribution shifts. Correcting these failures typically requires dataset aggregation and full-policy retraining, which is computationally expensive and unsuitable for real-time deployment. In this work, we propose Online Residual Policy Adaptation (ORPA), a framework that enables immediate, feedback-driven correction of robot actions without modifying the underlying policy…

---

### [Teach and Grow: An Agent-Centered Architecture for General Robot Learning](https://arxiv.org/abs/2608.17209v1)

- **arXiv**: `2608.17209v1`  |  **提交日期**: 2026-08-17
- **作者**: Chang Nie, Zhe Liu, Hesheng Wang

End-to-end vision-language-action (VLA) and world-action models offer an elegant route to general-purpose robotics, but their reliability is bounded by validated physical coverage. When an unfamiliar object, sensor, embodiment, or contact falls outside that coverage and no validated fallback exists, correcting the failure requires new robot data, a policy update, and regression testing. This recurring burden is the retraining tax. Unlike text, embodied data must often be created by operating machines. We present Teach-and-Grow Learning (TGL), an agent-centered architecture for general robot…

---

### [Q-Learning With World Models](https://arxiv.org/abs/2608.17163v1)

- **arXiv**: `2608.17163v1`  |  **提交日期**: 2026-08-17
- **作者**: Perry Dong, Yueru Jia, Chelsea Finn, Dorsa Sadigh

Off-policy reinforcement learning (RL) has become increasingly sample-efficient, enabling applications such as RL fine-tuning of Vision-Language-Action models into reliable, high-performing policies. World models offer a further lever for sample efficiency, as they predict state changes rather than actions alone, but their success has largely been confined to supervised policy learning. Prior model-based RL methods often optimize the policy or value function directly on imagined rollouts, which is prone to compounding bias and struggles to scale to large, high-dimensional problems such as…

---

### [Inference-Time Attention Steering for Vision-Language-Action Driving Models](https://arxiv.org/abs/2608.17095v1)

- **arXiv**: `2608.17095v1`  |  **提交日期**: 2026-08-17
- **作者**: Darshan Nagendra Prasad, Lars Ullrich, Knut Graichen

Vision-language-action (VLA) driving models couple a reasoning stage with a diffusion-based trajectory decoder, but do not give a direct way to redirect attention toward safety-critical actors at inference time without retraining. We studied a bounded additive pre-softmax attention bias on the visual tokens of detector localized traffic actors on Alpamayo-R1's Qwen3-VL backbone. It is applied as a fail open forward pre-hook with no weight changes. On 50 lane-change scenarios from the Physical AI World Model Synthetic dataset. The trajectory decoder shows a monotonic dose response in the bias…

---

## 📅 2026-08-18

### [Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory](https://arxiv.org/abs/2608.16889v1)

- **arXiv**: `2608.16889v1`  |  **提交日期**: 2026-08-17
- **作者**: Bingxin Xu, Yuzhang Shang, Emilio Ferrara

Long-horizon robot manipulation chains many contact-rich skills into one multi-stage task. Vision-language-action (VLA) models increasingly master the individual skills, yet the chain still fails: errors compound beyond the policy's ability to correct, and one subtask silently constrains the next. A promising recipe freezes the VLA and puts an LLM agent in charge: it plans in language, moves in free space with analytic primitives, invokes the VLA only for contact-rich segments, and writes adaptation into language memory. Applied to long horizons, it breaks twice. (1) Competence comes from…

---

### [$τ_0$-VLA: a Hierarchical Robot Foundation Model with World-Model-Guided Test-Time Computation](https://arxiv.org/abs/2608.16885v1)

- **arXiv**: `2608.16885v1`  |  **提交日期**: 2026-08-17
- **作者**: Xiaowei Cai, Yunuo Cai, Bingao Chen, Jingxiao Chen, Zhi Chen, Siyuan Feng et al.

Long-horizon robot manipulation requires a robot to both execute individual skills reliably and sequence them coherently over extended tasks. Most hierarchical vision-language-action (VLA) models make each such decision with a single forward pass, leaving no mechanism to allocate additional computation to difficult or consequential choices. We introduce $τ_0$-VLA, a hierarchical robot foundation model that formulates high-level subtask generation as a compute-scalable inference problem through world-model-guided test-time computation. At each inference step, the high-level policy uses…

---

### [When State Becomes an Attack Surface: State-Semantic Injection in LLM-Driven Embodied Agents](https://arxiv.org/abs/2608.16806v1)

- **arXiv**: `2608.16806v1`  |  **提交日期**: 2026-08-17
- **作者**: Jiawei Liu, Jiacheng Guo, Tian Zhang, Yiwei Xu, Juan Wang, Jinlin Fan et al.

Large Language Models (LLMs) have demonstrated capabilities in in-context learning, task decomposition, step-by-step reasoning, and code generation, driving their gradual evolution from text generation models into the core of agents capable of perceiving environments, invoking tools, and executing tasks. Traditional LLM Agents typically obtain information through webpages, documents, databases, or external tools and generate corresponding invocation sequences according to user goals; when this technology is further integrated with robotic systems, large language models begin to undertake…

---

### [FabriMAE I Trust Myself? Self-Evaluating VLA Action Generation with Markov Attention Entropy](https://arxiv.org/abs/2608.16697v1)

- **arXiv**: `2608.16697v1`  |  **提交日期**: 2026-08-17
- **作者**:  Aniri, Chen Yilin, Jinhe Bi, Junfei Guo, Donglai Ran, Xu Bian et al.

Vision-Language-Action models (VLAs) integrate visual perception, language instruction, and action generation into end-to-end policies across heterogeneous architectures. However, enabling VLAs to self-evaluate their action generation reliability without external supervision remains a major challenge. Existing methods either rely on expert annotations or estimate uncertainty only from output statistics, largely ignoring internal signals. In this work, we observe that internal visual modality entropy exhibits consistent distinctions between successful and failed tasks across heterogeneous…

---

### [NebulaVLA: A Dual-Frequency Vision-Language-Action Model With Guide Action for Robotic Manipulation](https://arxiv.org/abs/2608.16503v1)

- **arXiv**: `2608.16503v1`  |  **提交日期**: 2026-08-17
- **作者**: Cong Zhao, Shuai Tian, Xu Zhang, Baocheng Ni, Xinguo Song, Xueying Sun et al.

Real-world deployment of Vision-Language-Action (VLA) models is often bottlenecked by efficiency-performance trade-offs, cross-embodiment generalization, and execution smoothness. We present NebulaVLA, an asynchronous dual-frequency architecture that decouples high-level semantic reasoning from low-level action control, optimizing computational resources and modularity. To bridge semantic gaps across heterogeneous robots, we introduce GESTURE-7, a unified language-grounded action representation. Furthermore, our Guide Action algorithm enforces kinematic continuity via mask-based smoothness…

---

### [Exposing the Long-tail in Embodied Urban Navigation via Scalable Learning from In-the-Wild Videos](https://arxiv.org/abs/2608.16476v1)

- **arXiv**: `2608.16476v1`  |  **提交日期**: 2026-08-17
- **作者**: Bingyi Xia, Han Bao, Zhewei Chen, Hanjing Ye, Jingwen Yu, Yuhan Pang et al.

Learning embodied urban navigation policies from real-world data is constrained by the cost of task-specific data collection and the limited coverage of rare yet safety-critical scenarios. To address these challenges, we present a scalable framework for learning point-goal urban navigation from web-scale in-the-wild egocentric videos while systematically exposing its long tail. The framework automatically annotates uncurated web videos with metric trajectories and structured navigation semantics, which are then used to train a vision-language-action policy for interpretable navigation…

---

### [SparkVLA: Stop-Aware Hierarchical VLA with Adaptive Action Chunking for Long-Horizon Manipulation](https://arxiv.org/abs/2608.16172v1)

- **arXiv**: `2608.16172v1`  |  **提交日期**: 2026-08-17
- **作者**: Xunyao Lei, Renjun Wu, Tianlin Huo, Xuesong Li

At every re-observation point in a hierarchical Vision-Language-Action (VLA) system, two interface decisions must be made: when to terminate the current subtask and how far to execute the proposed action chunk. These decisions are mutually dependent---the optimal stopping point depends on what the executor plans to do, while the optimal execution length depends on where the subtask boundary lies---yet existing architectures evaluate them in isolation, an asymmetry neither module can overcome alone. We present SparkVLA, a stop-aware hierarchical VLA that resolves this mutual dependency by…

---

### [US-VLA: An Ultrasound Vision-Language-Action Model for Embodied Abdomina](https://arxiv.org/abs/2608.16074v1)

- **arXiv**: `2608.16074v1`  |  **提交日期**: 2026-08-17
- **作者**: Cheng Zhang, Xingzheng Wu, Guihao Yan, Xifeng Hu, Zhi Liu, Mei Wu et al.

Artificial intelligence-assisted ultrasound scanning enhances diagnostic reliability and efficiency by providing real-time guidance for standardized image acquisition and reducing operator dependence. However, existing reinforcement learning and learning-assisted ultrasound scanning methods typically rely on carefully designed reward functions or extensive interaction data, which limits their generalization ability and stability across different devices, patient populations, and complex clinical scenarios. To address these challenges, we propose an ultrasound vision-language-action model…

---

### [GigaBrain-0.7: Scaling Embodied Foundation Models to Emergent Capabilities with a Three-System Architecture](https://arxiv.org/abs/2608.15875v1)

- **arXiv**: `2608.15875v1`  |  **提交日期**: 2026-08-16
- **作者**:  GigaBrain Team, Angen Ye, Axiang Sun, Can Jin, Chenxi Cheng, Chong Shi et al.

Vision-language-action (VLA) models have become a dominant paradigm for generalist embodied agents, demonstrating strong complex and long-horizon task completion in structured settings. Yet it remains an open question whether current VLA systems can benefit from more effective architectural design, scale to substantially larger and more heterogeneous data regimes, and achieve broader generalization across tasks and embodiments. To this end, we present GigaBrain-0.7, an embodied foundation model with substantially improved generalization across diverse robot embodiments. Specifically,…

---

### [ViTaR: Visuo-Tactile Residual Adaptation for Foundation VLA Manipulation](https://arxiv.org/abs/2608.15816v1)

- **arXiv**: `2608.15816v1`  |  **提交日期**: 2026-08-16
- **作者**: Yi Wang, Renjun Wu, Jinyan Liu, Xuesong Li

As Vision-Language-Action (VLA) models scale toward real-world deployment, contact-rich manipulation exposes a critical blind spot: these policies encode broad visual-semantic priors yet remain unaware of local contact events, producing identical actions whether contact is established, lost, or destabilized. Existing remedies either modify VLA internals, risking catastrophic forgetting, or demand online reinforcement under near-failure contact conditions. Both grant tactile unbounded influence over action generation, conflicting with the priors that make VLAs generalizable. We introduce…

---

### [GAINS: Leveraging Inconsistent Human Intervention Signals in Reinforcement Learning](https://arxiv.org/abs/2608.15707v1)

- **arXiv**: `2608.15707v1`  |  **提交日期**: 2026-08-16
- **作者**: Xinyi Zhang, Yinuo Zhao, Pei Ren, Lechun Jiang, Huiqian Jin, Lei Sun et al.

Correcting robot manipulation policies through human intervention holds great promise for real-world deployment, yet human operators are inherently imperfect in both the actions they provide and the timing of their intervention signals. While the former has been extensively discussed in reinforcement learning (RL), the latter remains underexplored. At high control frequencies, human intervention signals are often delayed and inconsistent across time and state space. In this work, we present GAINS, a framework for leveraging inconsistent human intervention signals in RL. At the core of GAINS,…

---

### [Robo-Dopamine 2.0: History-Conditioned and OOD-Aware Process Reward Modeling for Robotic Manipulation](https://arxiv.org/abs/2608.15680v1)

- **arXiv**: `2608.15680v1`  |  **提交日期**: 2026-08-16
- **作者**: Yijie Xu, Haopeng Jin, Run Zhou, Shengbang Liu, Sixiang Chen, Hongyang Cheng et al.

Vision-language-action (VLA) models improve robotic manipulation but remain vulnerable to compounding errors, scene changes, and off-trajectory states. Reinforcement learning can refine pretrained VLA policies, yet sparse success signals hinder exploration, while engineered dense rewards are costly and task-specific. Existing learned visual reward models often rely on static before-after observations, causing temporal ambiguity and weak discrimination between robustness-preserving variations and task-invalid failures under out-of-distribution (OOD) execution. We introduce Robo-Dopamine 2.0, a…

---

### [Algorithm-Architecture Co-Design for Efficient VLA Inference via Speculative Inference and Verification](https://arxiv.org/abs/2608.15636v1)

- **arXiv**: `2608.15636v1`  |  **提交日期**: 2026-08-16
- **作者**: Chunyu Qi, Zhuoran Song, Jian Weng, Haozhe Jiang, Xueyuan Liu, Naifeng Jing et al.

Vision-Language-Action (VLA) models have demonstrated remarkable capabilities in the field of embodied AI, but their high computational cost and limited predicted action length hinder real-time deployment. Although Dadu-Corki, a dedicated accelerator for efficient embodied AI, has been introduced, it does not exploit the inherent interaction patterns between the robot and its environment, which results in a relatively short predicted action length. We observe that robotic environments naturally alternate between active states-where precise actions are crucial-and inactive states-where actions…

---

### [EcoVLA: Energy-Efficient Device-Edge Co-Inference for Vision-Language-Action Models under Real-Time Constraints](https://arxiv.org/abs/2608.15502v1)

- **arXiv**: `2608.15502v1`  |  **提交日期**: 2026-08-16
- **作者**: Ao Zhou, Bo Dai, Le Yu, Xingyu Liu, Zeyu Hao, Lingkun Long et al.

Vision-Language-Action (VLA) models have emerged as a promising foundation for Embodied AI, but their high inference cost poses significant challenges for deployment in robotic systems. In practice, on-device inference is constrained by limited compute capacity and energy budgets, struggling to simultaneously satisfy real-time control and energy efficiency requirements. Alternatively, offloading the inference workload to an edge server is susceptible to fluctuations in system conditions, introducing unpredictable latency risks. Device-edge co-inference offers a promising solution, but…

---

### [Bit-Flip Attacks on Vision-Language-Action Models: Action-Decoding Architecture Shapes the Vulnerability](https://arxiv.org/abs/2608.15475v1)

- **arXiv**: `2608.15475v1`  |  **提交日期**: 2026-08-16
- **作者**: Yudong Gao, Linghan Chen, Wenhan Wu, Mia Zhou, Jiyao Wang, Kaiyan Ji et al.

Quantized Vision-Language-Action (VLA) models expose a weight-fault surface: Rowhammer-style faults can corrupt deployed INT8 bits. We present the first bit-flip attack on a VLA: a few gradient-selected flips reduce closed-loop success to $0\%$, while hundreds of random flips are harmless. Across four model variants spanning three action-head families, damaging bits concentrate in a few action-generating layers, but the empirical budget depends sharply on the head: direct regression and token policies fall in $1$--$5$ flips, whereas the evaluated flow-matching policies require…

---

### [PhaseLoRA: Control-Regime-Conditioned Low-Rank Adaptation for Continuous-Action Vision-Language-Action Policies](https://arxiv.org/abs/2608.15285v1)

- **arXiv**: `2608.15285v1`  |  **提交日期**: 2026-08-15
- **作者**: Yufei Guo, Yinan Wu, Haoran Duan, Guiguang Ding, Jungong Han

Parameter-efficient fine-tuning (PEFT) is a natural way to adapt pretrained vision-language-action (VLA) policies, but most adapter designs apply temporally static updates throughout a control rollout, overlooking the phase-dependent nature of continuous-action manipulation. Such policies traverse distinct regimes, including approach, contact transition, grasping, transport, and placement, each requiring different adaptation behaviors. We propose \textbf{PhaseLoRA}, a lightweight LoRA parameterization that conditions adaptation at each action-chunk prediction step using two weakly supervised…

---

### [Remember Smarter: Visual History Compressor and Hyperbolic Experience Space for Robotic Memory](https://arxiv.org/abs/2608.15269v1)

- **arXiv**: `2608.15269v1`  |  **提交日期**: 2026-08-15
- **作者**: Dai Zhou, Jiexi Yan, Tong Li, Yuxuan Wang, Cheng Deng

Long-horizon robot policies require compact access to recent observations and reusable experience without expanding the vision-language-action (VLA) context. We introduce Remember Smarter (RS), a plug-and-play module with complementary visual-history and hyperbolic experience-memory branches. Its visual branch compresses multi-view patch histories using bidirectional spatial Mamba and causal temporal Mamba, then exposes the resulting memory to action-facing hidden states through residual cross-attention while leaving the VLM visual-token stream unchanged. Its experience branch stores…

---

### [StructRL: Structured Action-Space Exploration for Flow-Based VLAs](https://arxiv.org/abs/2608.15139v1)

- **arXiv**: `2608.15139v1`  |  **提交日期**: 2026-08-15
- **作者**: Jiarui Yang, Bin Zhu, Jingjing Chen, Na Zou, Yanwei Fu, Jianggang Zhu et al.

Flow-based Vision-Language-Action (VLA) models are now widely used for continuous robotic manipulation, and online reinforcement learning (RL) is emerging as a key technique for adapting them to new tasks. Existing RL methods typically inject stochasticity inside the denoising chain, often through isotropic or temporally independent noise. However, effective robot exploration calls for structured noise: temporally smooth and scaled differently across action groups. We show that simply switching the in-chain noise to a structured form does not suffice: noise added at an intermediate flow time…

---

### [PACE: Phase-Progress-Aware Credit for Long-Horizon Embodied Manipulation](https://arxiv.org/abs/2608.15026v1)

- **arXiv**: `2608.15026v1`  |  **提交日期**: 2026-08-15
- **作者**: Chengye Song, Jiawei Zhang, Rui Song, Shengqi Wang, Xiangrong Zhang, Ziyi Wang et al.

Post-training of vision-language-action (VLA) models typically relies on expert demonstrations and policy interaction trajectories. However, in long-horizon manipulation, a single episode often spans hundreds of control steps and multiple phases, while success or failure is only revealed at episode termination. Policy improvement therefore requires step-level credit signals to distinguish behaviors that advance the task from those that stall or regress. We present PACE, a credit-assignment framework for post-training on long-horizon manipulation, centered on a phase-progress-aware critic.…

---

### [ForceU-VLA: A Force-Aware Vision-Language-Action Model for Embodied Ultrasound Scanning](https://arxiv.org/abs/2608.15009v1)

- **arXiv**: `2608.15009v1`  |  **提交日期**: 2026-08-15
- **作者**: Xingzheng Wu, Cheng Zhang, Guihao Yan, Xifeng Hu, Zhi Liu, Qing Cai

Embodied intelligent ultrasound scanning enables the automation and standardization of the ultrasound examination process by integrating perception, decision-making, and execution capabilities. However, existing methods suffer from loosely coupled modeling between force and ultrasound modalities and lack awareness of scanning stages, which limits their ability to capture dynamic probe-tissue interactions. To address these issues, we propose ForceU-VLA, a force-aware Vision-Language-Action model for autonomous embodied ultrasound scanning, which leverages force signals and ultrasound image…

---

## 📅 2026-08-17

### [Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation](https://arxiv.org/abs/2608.14379v1)

- **arXiv**: `2608.14379v1`  |  **提交日期**: 2026-08-14
- **作者**: Yuxuan Chen, Wanruo Zhang, Xiao Li

Vision-Language-Action (VLA) models have recently achieved promising performance in robotic manipulation. However, existing benchmarks mainly evaluate generalization on static manipulation tasks and largely overlook dynamic interaction scenarios. To address this gap, we present ReflexBench, a benchmark for reaction-critical manipulation. ReflexBench contains six dynamic tasks and introduces an evaluation framework that decouples simulator stepping from robot control while supporting configurable latency under synchronous and asynchronous inference. Building upon ReflexBench, we propose…

---

### [Evolve Vision-Language-Action Model into an Agent with On-the-fly Tool-use](https://arxiv.org/abs/2608.14047v1)

- **arXiv**: `2608.14047v1`  |  **提交日期**: 2026-08-14
- **作者**: Yi Ding, Yanzhao Yu, Xili Dai, Xianbiao Qi, Peiwen Sun, Xueqian Wang et al.

This paper integrates end-to-end Visual-Language-Action (VLA) models with agentic tool-use to propose Agentic Robot with Tool-use (ART). ART is a tool-injection framework that tunes any VLA model to leverage off-the-shelf tool modules for low-level vision, high-level affordance, and embodiment enhancement. Compared to vanilla VLA models with a whole continuous action solution space, ART reduces the complexity of the action solution space through tool-use, which not only improves generalizability across different tasks but also reduces data dependency. To demonstrate the advantages (high…

---

### [AdvDex: Learning Dexterous Manipulation from Human Demonstrations via Joint-Aligned Actions and Adversarial Learning](https://arxiv.org/abs/2608.14028v1)

- **arXiv**: `2608.14028v1`  |  **提交日期**: 2026-08-14
- **作者**: Zhiyue Zhao, Jingyi Wu, Hairuo Liu, Mingyu Liu, Liyang Li, Hengdi Zhang et al.

Dexterous manipulation is a fundamental capability for embodied intelligence, but scaling it remains difficult because robot demonstrations are expensive to collect and action spaces vary across embodiments. Policies trained on heterogeneous data can also entangle task-relevant visual cues with embodiment-specific appearance, limiting cross-embodiment generalization. We present AdvDex, a unified Vision-Language-Action framework for learning dexterous manipulation from human and robot demonstrations. First, we introduce OmniShare, a large-scale multimodal dataset of human manipulation…

---

### [SSP: An Event-Matched Syn2Sim2Phy Cross-Domain Evaluation Framework for Autonomous Driving VLA Models](https://arxiv.org/abs/2608.14024v1)

- **arXiv**: `2608.14024v1`  |  **提交日期**: 2026-08-14
- **作者**: Haojie Feng, Peizhi Zhang, Xinrui Zhang, Zhuoren Li, Junpeng Huang, Xiurong Wang et al.

Vision-language-action (VLA) models for autonomous driving jointly produce scene interpretation, language-based reasoning, and driving trajectories. Existing evaluations often use independently selected synthetic, simulated, and physical data, so measured performance gaps can be confounded by changes in scenario content rather than genuine domain sensitivity. We propose SSP (Synthetic-Simulation-Physical), an event-matched Syn2Sim2Phy evaluation framework that anchors cross-domain comparison to the same safety-critical interaction. Starting from a synthetic long-tail video, SSP builds a…

---

### [BICPO-VLA: Behavior-Identified Continuation Preference Optimization for Smooth Asynchronous Vision-Language-Action Control](https://arxiv.org/abs/2608.13924v1)

- **arXiv**: `2608.13924v1`  |  **提交日期**: 2026-08-14
- **作者**: Ming Shang, Yuchen Huang, Jiaoyang Chen, Haoyuan Hu, Han Yu, Liping Song et al.

The request-to-handoff gap has three coupled sources: ambiguity about the behavior intended at request time, physical-state drift accumulated during action generation, and residual incompatibility when the new action finally assumes control. BICPO-VLA addresses them in sequence. First, an instruction-aware causal history encoder identifies the behavior supported by the command and current task progress. Second, sequential Haar subspace generation decomposes each action chunk into complementary pairwise scaffold and residual coefficients, enabling two specialized generation stages followed by…

---

## 📅 2026-08-14

### [Decoding Task Progress from VLA Representations](https://arxiv.org/abs/2608.13474v1)

- **arXiv**: `2608.13474v1`  |  **提交日期**: 2026-08-13
- **作者**: Atiksh Bhardwaj, Edward Weiyi Duan, Prithwish Dan, Wei-Chiu Ma, Preston Culbertson

Vision-language-action models (VLAs) are moving rapidly towards deployment as general-purpose manipulation policies, but we currently lack basic tools for understanding what these models represent internally or for monitoring them at runtime. Leveraging ideas from mechanistic interpretability, we probe the residual stream of $π_{0.5}$ and find that task progress, the normalized time remaining in a trajectory, is linearly readable from the activations. We find that this signal is present in the pretrained PaliGemma backbone prior to training on any robot-specific data. A single linear probe…

---

### [UniTexture: Cross-Task Universal Adversarial Textures for Vision-Language-Action Models](https://arxiv.org/abs/2608.13453v1)

- **arXiv**: `2608.13453v1`  |  **提交日期**: 2026-08-13
- **作者**: Yukun Dai, Mingzhe Dai, Tianshi Wang, Fengling Li, Jingjing Li, Lei Zhu

Vision-Language-Action (VLA) models have emerged as generalist robotic policies capable of following diverse language instructions and performing a wide range of manipulation tasks. However, their direct control over embodied agents also exposes them to adversarial interference that may cause unsafe physical behaviors. Existing attacks on robotic policies are typically optimized for a single task or instruction, leaving the cross-task vulnerabilities of multitask VLAs largely unexplored. We introduce UniTexture, a cross-task universal adversarial texture attack that uses a single textured 3D…

---

### [FIRE-VLA: Failure-Informed Self-Evolution for Vision-Language-Action Models in Autonomous Driving](https://arxiv.org/abs/2608.13395v1)

- **arXiv**: `2608.13395v1`  |  **提交日期**: 2026-08-13
- **作者**: Hao Dou

Reinforcement learning improves autonomous-driving vision-language-action (VLA) models by evaluating trajectories sampled from the current policy. Group relative policy optimization (GRPO) learns from reward differences within each rollout group. When all sampled trajectories are poor, this relative signal can rank failures without identifying behavior outside the failed region. We introduce FIRE-VLA, a failure-informed self-evolution framework that converts such unresolved failures into privileged supervision for the next policy. Low-reward, low-diversity groups trigger self-distillation…

---

### [Temporal GRPO: Beyond Trajectory-Level Credit in Vision-Language-Action Reinforcement Learning](https://arxiv.org/abs/2608.13026v1)

- **arXiv**: `2608.13026v1`  |  **提交日期**: 2026-08-13
- **作者**: Yao Zhou, Hang Gao, Fengge Wu, Changwen Zheng, Wenwen Qiang

Outcome-driven reinforcement learning offers a scalable way to post-train vision-language-action (VLA) policies from sparse task-success feedback. In common GRPO-based VLA post-training, one rollout-level advantage is applied to every action in the trajectory. A rollout that completes several valid stages but fails later can therefore penalize the actions that produced its earlier progress. We call this trajectory-level credit aliasing. Temporal GRPO addresses this problem by constructing detectable task stages, aligning each rollout with stage-specific action intervals, and comparing only…

---

### [FlashDrive: Flash Vision-Language-Action Inference for Autonomous Driving](https://arxiv.org/abs/2608.12932v1)

- **arXiv**: `2608.12932v1`  |  **提交日期**: 2026-08-13
- **作者**: Zekai Li, Yihao Liang, Hongfei Zhang, Jian Chen, Yesheng Liang, Zhijian Liu

Vision-Language-Action (VLA) models promise to bring end-to-end reasoning to autonomous driving, but their computational cost remains far too high for real-time control. The core challenge is structural: VLA inference is not a single bottleneck but a cascade of four. Visual encoding wastes compute on overlapping video frames; language-model prefill recomputes context that could be carried over from the previous timestep; reasoning tokens are generated serially despite low entropy; and flow-matching denoising applies uniform compute to a non-uniform velocity field. Addressing any one stage in…

---

### [BrainWAM: Action-Space Coordination of Semantic Priors and Predictive Dynamics for Autonomous Driving](https://arxiv.org/abs/2608.12854v1)

- **arXiv**: `2608.12854v1`  |  **提交日期**: 2026-08-13
- **作者**: Bing Zhan, Shuyao Shang, Jiahao Gu, Shuo Lu, Yuan Xu, Zhao Wang et al.

Autonomous driving requires planning under both semantic constraints and predictive dynamics. Existing end-to-end driving approaches, however, typically emphasize only one side of this requirement: Vision-Language-Action (VLA) models exploit VLM priors for semantic reasoning, while World Action Models (WAMs) provide future-aware prediction through generative world modeling. This naturally motivates a unified planner that can leverage both semantic priors and predictive dynamics. However, we find that a naive combination through joint token-level attention suffers from an attention-allocation…

---

### [RoboSynChallenge: Mastering Real-World Dexterity via Generalizing Synthesized Manipulation Skills](https://arxiv.org/abs/2608.12416v1)

- **arXiv**: `2608.12416v1`  |  **提交日期**: 2026-08-12
- **作者**: Runyi Zhao, Ruixin Wu, Chengkun Li, Hongrui Zhang, Ang Li, Ruixing Jin et al.

Achieving generalizable robotic manipulation remains a central challenge in embodied intelligence. Despite rapid advances in model architectures and learning algorithms, progress is often limited by the scarcity and narrow diversity of real-world data. The RoboSynChallenge competition introduces a unified benchmark to evaluate and advance the generalizability of manipulation policies across a spectrum of tasks, environments, and difficulty levels. To alleviate the shortage of realistic data, the challenge integrates large-scale synthetic data generation with standardized real-world robotic…

---

## 📅 2026-08-13

### [DreamFly: Causal Memory and Receding-Horizon Diffusion Planning for Aerial Vision-Language Navigation](https://arxiv.org/abs/2608.12308v1)

- **arXiv**: `2608.12308v1`  |  **提交日期**: 2026-08-12
- **作者**: Yan Deng, Fei Xu

Aerial vision-language navigation (VLN) requires an embodied agent to integrate visual evidence over time, plan future actions, and determine when it has reached a navigation goal under partial observability. Although recent VLA models offer a promising perception-to-action paradigm, adapting them to aerial navigation remains challenging due to limited historical context, short planning horizons, and unreliable implicit termination. To address these challenges, we propose DreamFly, a diffusion-based aerial VLN framework built on Dream-VLA. DreamFly introduces a causally aligned historical…

---

### [Policy-Induced Hand Priors in Humanoid Dual-Arm Manipulation: Diagnosing and Mitigating Initial-Pose Dependence](https://arxiv.org/abs/2608.11769v1)

- **arXiv**: `2608.11769v1`  |  **提交日期**: 2026-08-12
- **作者**: Chaeyeon Jung, Juyoun Park

Vision-language-action (VLA) policies are expected to operate robustly across variations in the robot's initial configuration, yet aggregate task success can conceal pose-specific failures and inappropriate hand selection. This work investigates initial-pose dependence in VLA-based humanoid dual-arm manipulation. We characterize the initial-condition-dependent early hand preference as a policy-induced hand prior and quantify it using HandPriorScore, residual hand bias, and target responsiveness. Evaluations across multiple policies and 17 initial configurations reveal strong…

---

### [G0.5: One Autoregressive Stream for Robot Reasoning and Action](https://arxiv.org/abs/2608.11739v1)

- **arXiv**: `2608.11739v1`  |  **提交日期**: 2026-08-12
- **作者**: Yicheng Liu, Zibin Dong, Baijun Ye, Tianyuan Yuan, Tao Jiang, Anqi Yang et al.

The prevailing recipe for Vision-Language-Action (VLA) models couples a pretrained VLM with a separately trained flow-matching action expert. This makes the VLM a context encoder rather than a decision-maker. We introduce G0.5, a pretrained autoregressive VLA in which a single transformer decoder emits reasoning and action tokens under a single objective. Three components make this tractable at foundation-model scale: a learnable cross-embodiment action tokenizer that maps heterogeneous robot actions into a shared vocabulary; a native chain-of-thought stream interleaving task decomposition,…

---

### [StellaVLA: In-Context Structured Demonstration for Generalizable Vision-Language-Action Models](https://arxiv.org/abs/2608.11671v1)

- **arXiv**: `2608.11671v1`  |  **提交日期**: 2026-08-12
- **作者**: Siyu Xu, Yunke Wang, Zijian Wang, Dihao Zhu, Chenghao Xia, Chengbin Du et al.

Vision-Language-Action (VLA) models can follow instructions and manipulate objects, but their performance often collapses out of distribution (OOD), when the scene, viewpoint, or object differs from training. Adapting to each new situation typically requires collecting more data and fine-tuning. We present StellaVLA, a framework that instead adapts at test time by conditioning on a single retrieved demonstration. The key idea is to move beyond imitating what an expert did and instead convey why: an automated offline pipeline converts each raw trajectory into a structured demonstration, e.g.,…

---

### [VANE: Reliable Test-Time Training for Vision-Language-Action Models via Future Visual Representation Prediction](https://arxiv.org/abs/2608.09448v2)

- **arXiv**: `2608.09448v2`  |  **提交日期**: 2026-08-10
- **作者**: Hongjin Ji, Guoyang Xia, Luoyang Sun, Fangxiang Feng, Lei Ren

Test-time training (TTT) offers a lightweight way to adapt vision--language--action (VLA) policies from unlabeled deployment streams, but it remains difficult to use reliably in closed-loop manipulation. A shared adaptation space can mix incompatible task corrections, while an online update can alter subsequent actions before its consequences are known. We introduce a reliable TTT framework for VLA policies (VANE). VANE conditions prompt adaptation on the current vision--language context and learns from the future visual consequences of executed actions. Candidate updates are isolated from…

---

## 📅 2026-08-12

### [XCoT-VLA: Executable Chain-of-Thought for Vision-Language-Action Driving](https://arxiv.org/abs/2608.10976v1)

- **arXiv**: `2608.10976v1`  |  **提交日期**: 2026-08-11
- **作者**:  Foundation Model Team, XPeng Inc

Vision-Language-Action (VLA) models can connect scene understanding, semantic reasoning, and trajectory generation for autonomous driving. However, verbose natural-language Chain-of-Thought (CoT) is poorly suited to real-time control because it is open-ended, costly to decode, and difficult to optimize as an action-facing representation. We propose XCoT-VLA, which replaces descriptive rationales with compact executable CoT tokens learned from automatically constructed Reason-Action supervision. Logged trajectories provide action evidence, while scene context supplies causal semantics. The…

---

### [Neural Introspection Gating for Adaptive KV-Cache Reuse in Vision-Language-Action Models](https://arxiv.org/abs/2608.10824v1)

- **arXiv**: `2608.10824v1`  |  **提交日期**: 2026-08-11
- **作者**: Zhijie Wu, Kento Kawaharazuka, Kei Okada

Vision-Language-Action(VLA) models map camera images and language instructions directly to motor commands through a single autoregressive transformer. In real-time control, they still spend substantial compute recomputing key-value(KV) representations for visual tokens that barely change across neighboring frames. Recent work such as VLA-Cache reduces that cost by reusing KV states for visually static patches, but its policy relies only on observation-space heuristics and does not account for the model's own uncertainty. We propose Gated VLA-Cache, a lightweight, training-free extension that…

---

### [Embodied Multimodal Grounding for Open-Vocabulary Mobile Manipulation via Semantic 3D Gaussian Splatting](https://arxiv.org/abs/2608.10756v1)

- **arXiv**: `2608.10756v1`  |  **提交日期**: 2026-08-11
- **作者**: Huosen Ou, Dongni Song, Yuncong Wang, Tao Zhou, Yiding Ji

Embodied mobile manipulation requires language, visual observations, three-dimensional scene structure, and action feasibility to be aligned before execution. We study open-vocabulary target grounding with few-shot manipulation in local household workspaces and present an embodied multimodal grounding framework that integrates active multi-view Semantic 3D Gaussian Splatting (Semantic-3DGS), reachability-aware base positioning, and a diffusion-based vision-language-action policy. A task-driven local Semantic-3DGS serves as a shared interface across active sensing, language-conditioned 3D…

---

### [Lost in Reconstruction: Aligning Action Representations with Language in Vision-Language-Action Models](https://arxiv.org/abs/2608.10484v1)

- **arXiv**: `2608.10484v1`  |  **提交日期**: 2026-08-11
- **作者**: Li Wenjie, Yash Jangir, Ignacy Stepka, Yash Agarwal, Marion Kipsang, Yonatan Bisk

Action verbs describe not only the physical outcomes of actions, but also how those actions are performed. Yet action representations in vision-language-action models (VLAs) are typically optimized for reconstruction under L1/L2 losses in raw action space, where numerical proximity need not reflect linguistically meaningful distinctions. On BridgeV2, we show that action trajectories contain verb-grounding information beyond visual state changes, and that reconstruction-only discrete tokenization systematically erodes this information. To address this problem, we introduce SALT, a Semantically…

---

### [DriveVLA-M0: Failure-Aware Memory Augmentation for Autonomous Driving](https://arxiv.org/abs/2608.10413v1)

- **arXiv**: `2608.10413v1`  |  **提交日期**: 2026-08-11
- **作者**: Zebin Xing, Yupeng Zheng, Qiang Chen, Linbo Wang, Yichen Zhang, Pengxuan Yang et al.

Vision-Language-Action (VLA) models have recently emerged as a promising paradigm for end-to-end autonomous driving by enabling unified reasoning across perception, language, and planning. However, existing approaches lack mechanisms to exploit past failures or adapt to distribution shifts, causing the model to persistently underperform on similar scenarios where it has previously failed. In this paper, we propose DriveVLA-M0, a retrieval-augmented VLA with failure-aware latent memory. We construct a latent memory pool that stores failure cases along with their structure scene representations…

---

### [Hidden in Plain Sight: Diffusion-Based Unrestricted Robotic Attacks on Vision-Language-Action Models](https://arxiv.org/abs/2608.10393v1)

- **arXiv**: `2608.10393v1`  |  **提交日期**: 2026-08-11
- **作者**: Jiahui Han, Yuhui Yao, Xin Wang, Jiafei Cao, Mingxuan Zhang, Danfeng Shan et al.

Vision-Language-Action (VLA) models have shown strong capabilities in controlling robots across diverse manipulation tasks. However, their adversarial robustness remains largely underexplored, and exploiting this weakness can lead to physical-world harm. Existing attacks on VLA models often rely on pixel-space perturbations or white-box access, resulting in noticeable artifacts and limited deployability in real-world robotic systems. In this work, we propose DURA, a diffusion-based unrestricted robotic attack that generates visually natural adversarial patches for VLA models. DURA supports…

---

## 📅 2026-08-11

### [SLIM-0.5B: Learning Action-Grounded Predictive Latents for Robot Manipulation](https://arxiv.org/abs/2608.09771v1)

- **arXiv**: `2608.09771v1`  |  **提交日期**: 2026-08-10
- **作者**: Jingkai Wang, Zihan Tang, Gu Zhang, Mingyu Cao, Jiapeng Chen, Jingjiao Zhao et al.

Vision-language-action policies rely on large multimodal backbones to jointly perform perception, language conditioning, and action generation at every control step. Much of this capacity supports open-domain semantics, whereas continuous robot manipulation primarily requires compact representations of observations, actions, and the transitions induced by actions. Pixel-level world models provide another route, but predicting visual details irrelevant to control can be unnecessarily expensive. We propose SLIM (Self-supervised Latent Interaction Model), a compact 0.5B-parameter latent…

---

### [World Tokens: Enhancing Embodied Policies with Training-Time World Modeling](https://arxiv.org/abs/2608.09730v1)

- **arXiv**: `2608.09730v1`  |  **提交日期**: 2026-08-10
- **作者**: Qu Tang, Benhui Zhuang, Bo Yuan, Xue Yu, Longteng Guo, Junlan Feng

Vision-language-action (VLA) models are a widely adopted paradigm for embodied policies. They excel at efficient closed-loop control but do not explicitly model how physical scenes evolve as a task unfolds. Recently emerging world-action models (WAMs) leverage pretrained video world models to capture spatiotemporal evolution, yet retaining future generation or a large video backbone in the control loop substantially increases inference cost. We introduce World Tokens, an embodied policy architecture built around a World Adapter that bridges visual-language understanding, world-dynamics…

---

### [RecoverFly: A Failure-Aware Reinforcement Learning Post-Training Framework for Aerial Vision-Language Navigation](https://arxiv.org/abs/2608.09467v1)

- **arXiv**: `2608.09467v1`  |  **提交日期**: 2026-08-10
- **作者**: Boxiong Wang, Hui Kang, Geng Sun, Jiahui Li, Chao Yu, Daxin Tian

Unmanned aerial vehicle vision-language navigation (UAV-VLN) requires agents to translate visual observations and language instructions into reliable flight actions in complex environments. Although recent end-to-end UAV vision-language-action (UAV-VLA) policies reduce reliance on separately designed perception, planning, and control modules, their behavior-cloning objectives provide limited corrective supervision for interactive closed-loop execution. Reinforcement learning (RL) offers a promising solution, while its effectiveness is constrained by inefficient use of samples, long-tailed…

---

### [VANE: Reliable Test-Time Training for Vision-Language-Action Models via Future Visual Representation Prediction](https://arxiv.org/abs/2608.09448v1)

- **arXiv**: `2608.09448v1`  |  **提交日期**: 2026-08-10
- **作者**: Hongjin Ji, Guoyang Xia, Luoyang Sun, Fangxiang Feng, Lei Ren

Test-time training (TTT) offers a lightweight way to adapt vision--language--action (VLA) policies from unlabeled deployment streams, but it remains difficult to use reliably in closed-loop manipulation. A shared adaptation space can mix incompatible task corrections, while an online update can alter subsequent actions before its consequences are known. We introduce a reliable TTT framework for VLA policies (VANE). VANE conditions prompt adaptation on the current vision--language context and learns from the future visual consequences of executed actions. Candidate updates are isolated from…

---

### [Skills in Weights, Memory in Code: Hybrid Learning for Memory-Dependent Robot Manipulation](https://arxiv.org/abs/2608.09410v1)

- **arXiv**: `2608.09410v1`  |  **提交日期**: 2026-08-10
- **作者**: Yunhao Zhao, Zhenyang Ni, Haoyang Chen, Ruohan Zhang, Qi Zhu

Modern vision-language-action (VLA) policies have acquired broad manipulation skills, but typically generate each action chunk from the current observation or a short fixed-length history. However, real-world manipulation is often non-Markovian, requiring robots to retain and reason over task-relevant information from long-horizon interaction histories to determine the next action. To address this challenge, we propose HyMeS, a hybrid learning framework that leverages the reasoning and memory-management capabilities of coding agents to steer a Markovian VLA for memory-dependent manipulation.…

---

### [JEPA-WAM: Learning Vision-Language-Action Policies with Joint-Embedding World Modeling](https://arxiv.org/abs/2608.09381v1)

- **arXiv**: `2608.09381v1`  |  **提交日期**: 2026-08-10
- **作者**: Yihan Lin, Jiawei He, Shifeng Bao, Chen Zhao, Yang Li, Xiaobo Wang et al.

Robust robot control benefits from explicitly modeling state transitions, but video-generation world action models (WAMs) introduce substantial deployment cost. Existing latent WAMs avoid explicit future generation, but often compress predictive representations or separate predictive modeling from the representations used for action generation. We introduce JEPA-WAM, a latent WAM built in a pretrained V-JEPA space, which couples latent transition prediction with continuous action generation through a shared predictor. JEPA-WAM predicts a spatially structured joint current-future target that…

---

### [Trajectory Divergence Horizon Decision for Reliable Dual-Arm Surgical Subtask Manipulation](https://arxiv.org/abs/2608.09125v1)

- **arXiv**: `2608.09125v1`  |  **提交日期**: 2026-08-10
- **作者**: Mingwu Su, Guankun Wang, Jinsong Lin, Rulin Zhou, Ziyi Hao, Zhiwei Fang et al.

Surgical robotic systems are increasingly being adopted as clinical workload rises, motivating autonomous solutions for repetitive manipulation subtasks. Learning-based controllers improve generalization compared with rule-based and analytic approaches, but most are trained for individual tasks and remain difficult to reuse across procedures. Vision-Language-Action (VLA) models provide a unified framework that integrates visual perception, language grounding, and action generation, offering a promising path toward more composable surgical autonomy. However, existing VLA policies rely on…

---

### [From Recovery to Drop-off: How Action Post-training Reduces a VLM's Late-Layer Depth Decodability](https://arxiv.org/abs/2608.08904v1)

- **arXiv**: `2608.08904v1`  |  **提交日期**: 2026-08-09
- **作者**: Alexander Hackett, Arnaud Denis-Remillard, Axel Cassou

How much of a vision-language model's (VLM) spatial understanding remains after the action post-training process of building a vision-language-action model (VLA)? We probe depth perception, a primitive of spatiogeometric understanding, from every decoder layer of a weight-matched open-source base VLM/VLA pair: Molmo2-ER and MolmoAct2-LIBERO. First, the VLA decodes depth worse at every layer, a persistent gap we call the floor. Second, the degradation is not uniform: while the base VLM's depth decodability improves through its final layers, the VLA's collapses, an additional late-layer drop we…

---

### [WA-SpecDec: World-Aware Speculative Decoding for Vision-Language-Action Models](https://arxiv.org/abs/2608.08725v1)

- **arXiv**: `2608.08725v1`  |  **提交日期**: 2026-08-09
- **作者**: Zikang Wen, Yuning Zhang, Dong Yuan

Vision-language-action (VLA) policies generate robot controls autoregressively, making closed-loop latency dominated by repeated target-model forward passes. Speculative decoding reduces this cost by verifying blocks of draft action tokens in parallel, and recent VLA methods further relax token-level acceptance because small differences in action-token space often map to similar continuous controls. However, this relaxation remains scene-agnostic. A fixed token-distance tolerance treats the same action-token deviation as equally safe across states, although deviations that are harmless in…

---

### [Auditing Instruction-Trajectory Mismatches in Multimodal Robot Demonstrations](https://arxiv.org/abs/2608.07895v1)

- **arXiv**: `2608.07895v1`  |  **提交日期**: 2026-08-08
- **作者**: Simon Holk, Ryosuke Takanami, Tatsuya Matsushima, Yusuke Iwasawa, Yutaka Matsuo, Yueh-Hua Wu et al.

Robot demonstration datasets used to train vision-language-action policies can contain a subtle but harmful failure mode: trajectories that are behaviorally correct but paired with the wrong language instruction. We study post-hoc auditing of these Instruction-Trajectory Mismatches (ITMs). Unlike failed rollouts, ITMs often look plausible, and can corrupt the language-behavior mapping learned by the policy. We propose Multimodal Probabilistic Fusion (MMPF), a training-free auditing framework that treats each modality as an expert, estimates a task-label distribution from local neighborhood…

---

## 📅 2026-08-10

### [Depth-Wise Probing and Pruning of the Planning Token in a Driving Vision-Language-Action Model](https://arxiv.org/abs/2608.07361v1)

- **arXiv**: `2608.07361v1`  |  **提交日期**: 2026-08-07
- **作者**: Harisankar Babu, Benjamin Coors, Christopher Lang, Hendrik Berkemeyer, Tamim Asfour, Simon Foell

Vision-language-action (VLA) models route driving decisions through a deep language model, but it is unclear how much of that depth the action itself requires. We study a representative driving VLA whose entire plan is carried by a single planning token that a generative planner decodes into a trajectory. Borrowing the planner as a trajectory-space logit lens, we decode the planning token from every one of the 32 decoder layers and measure two signals: the linear decodability of the navigation command and trajectory compatibility with the frozen native planner. Our diagnostic shows that…

---

### [TEMPO: Semantic-Action Decoupled RL Post-Training for Vision-Language-Action Models](https://arxiv.org/abs/2608.07314v1)

- **arXiv**: `2608.07314v1`  |  **提交日期**: 2026-08-07
- **作者**: Ziheng Liu, Quantao Yang

Vision-language-action (VLA) models are commonly adapted to downstream manipulation tasks via supervised fine-tuning (SFT) or online reinforcement learning (RL) post-training. SFT is prone to distribution mismatch, and existing RL approaches typically apply a single, uniform update strategy to all model components, ignoring their distinct functional roles. We propose TEMPO, a semantic-action decoupled, two-timescale RL post-training framework for VLA models. TEMPO freezes the pretrained vision-language backbone to preserve general semantic representations, and restricts adaptation to two…

---

### [WNM-3D: A World Navigation Model with 3D Scene Conditioning for Closed-Loop VLN](https://arxiv.org/abs/2608.07267v1)

- **arXiv**: `2608.07267v1`  |  **提交日期**: 2026-08-07
- **作者**: Yuehao Huang, Yunzi Wu, Xiaotao Zhang, Xinhai Li, Jiankun Dong, Jiajun Lv et al.

Recent vision-language navigation (VLN) systems increasingly adapt pretrained vision-language models (VLMs) into vision-language-action (VLA) policies that map egocentric observations and language instructions directly to navigation actions. Although semantically capable, such action-centric training does not explicitly model how the agent's visual observations should evolve under its predicted motion. Generative world-action models (WAMs) jointly predict future observations and actions, yet existing WAMs for continuous VLN do not condition joint future-view and action generation on…

---

### [Cross-View Action Consistency for Camera-Robust Vision-Language-Action Policies](https://arxiv.org/abs/2608.06965v1)

- **arXiv**: `2608.06965v1`  |  **提交日期**: 2026-08-07
- **作者**: Bingqi Huang, Bingchuan Wei, Xuan Wang, Yingkai Cai, Zhaokui Wang

Vision-language-action (VLA) policies fine-tuned from a fixed scene camera can fail when the camera is moved, even when the task, objects, language, and robot state are unchanged. We study scene-camera viewpoint robustness using only a scene RGB image, language, and proprioception, without camera labels, extrinsics, depth, or point-cloud inputs. The wrist stream is masked throughout to prevent an unperturbed visual shortcut from confounding attribution to scene-camera variation. For flow-based VLAs, we propose to regularize the action-flow velocity field, the quantity directly integrated to…

---

### [AtlasVLA: Persistent World-Ego State Modeling for Vision-Language-Action Models](https://arxiv.org/abs/2608.06729v1)

- **arXiv**: `2608.06729v1`  |  **提交日期**: 2026-08-07
- **作者**: Guiyu Zhao, Longteng Guo, Yanghong Mei, Zilin Zhu, Yu Zhang, Bin Cao et al.

While Vision-Language-Action (VLA) models have advanced embodied AI, their fundamentally reactive paradigm severely limits performance in partially observable and long-horizon tasks. When restricted to a single wrist-mounted camera, they inevitably suffer from perception forgetting as objects exit the field of view, and temporal task-progress forgetting} during multi-step execution. To overcome these bottlenecks, we propose AtlasVLA, a novel framework that transitions from direct reactive manipulation to proactive reasoning through a persistent world-ego state. AtlasVLA features a dual-memory…

---

## 📅 2026-08-07

### [DyPES-VLA: Learning Shared Dynamics Priors and Embodiment-Specific Control for Cross-Embodiment Manipulation](https://arxiv.org/abs/2608.06374v1)

- **arXiv**: `2608.06374v1`  |  **提交日期**: 2026-08-06
- **作者**: Junfeng Li, Junjie He, Zhide Zhong, Yangyang Zheng, Pingyue Sheng, Jiayu Dong et al.

Vision-Language-Action (VLA) models have become a powerful paradigm for robot manipulation, but training a single generalist policy for heterogeneous robot embodiments remains an open problem. Existing methods have two main limitations. First, they underuse dynamics priors shared across diverse visual and interaction data, limiting cross-embodiment transfer. Second, they require extensive manual preprocessing to convert embodiment-specific actions into a common format. To overcome these limitations, we propose DyPES-VLA, a cross-embodiment VLA that learns shared Dynamics Priors and…

---

### [Beyond Flat Policies: Hierarchical Post-Training for Embodied Agents in Robotic Manipulation](https://arxiv.org/abs/2608.05999v1)

- **arXiv**: `2608.05999v1`  |  **提交日期**: 2026-08-06
- **作者**: He Kong, Zengjue Chen, Qi Wang, Qianli Xing, Runliang Niu, Peidong Liu et al.

Vision-language-action (VLA) models have demonstrated remarkable capabilities in robotic manipulation by leveraging pretrained vision-language models. However, existing post-training methods predominantly optimize VLA models as flat policies, making it difficult to explicitly model task progression and perform robust long-horizon manipulation. Although hierarchical approaches introduce task decomposition, they mainly rely on supervised learning from offline demonstrations and cannot effectively improve execution through online interaction. To address this limitation, we propose Hierarchical…

---

### [SkillMemo: Expert-guided Skill Memory Framework for Compositional Embodied Manipulation](https://arxiv.org/abs/2608.05970v1)

- **arXiv**: `2608.05970v1`  |  **提交日期**: 2026-08-06
- **作者**: Changyuan Wang, Chubin Zhang, Zhenyu Wu, Runhao Li, Angyuan Ma, Ke Chao et al.

Embodied visuomotor models, including Diffusion Policy (DP) and Vision-Language-Action (VLA) models, have demonstrated promising performance on robotic manipulation benchmarks. However, their potential remains fundamentally constrained by the scarcity of large-scale embodied trajectory datasets, leading to insufficient compositional generalization in out-of-distribution (OOD) scenarios with limited capability to capture reusable skill structures. To address this limitation, we propose Skill-Based Memory (SkillMemo) framework that implicitly decomposes long-horizon demonstrations into latent…

---

### [In-Context VLA: Endowing Vision-Language-Action Models with Language via In-Context Post-Training and Agentic Tool Use](https://arxiv.org/abs/2608.05738v1)

- **arXiv**: `2608.05738v1`  |  **提交日期**: 2026-08-06
- **作者**: Jiarui Yang, Wen Huang, Jiale Zhang, Maowei Hu, Hang Guo

Vision-Language-Action (VLA) models have become the dominant recipe for generalist manipulation, yet they are almost universally trained by behavior cloning: a policy imitates expert action chunks conditioned on a static image and a fixed instruction. A natural remedy is to inject explicit reasoning through textual chain-of-thought (CoT). We show, both empirically and analytically, that free-form textual CoT degrades low-level control: the reasoning it produces is ungrounded, its latency breaks closed-loop timing, and, crucially, the reasoning and action tokens are optimized against…

---

### [World-to-Wrist: Task-Conditioned Future Wrist Modeling for Fine-Grained Robot Manipulation](https://arxiv.org/abs/2608.05369v1)

- **arXiv**: `2608.05369v1`  |  **提交日期**: 2026-08-05
- **作者**: Yuhao Pan, Haosong Peng, Zhengshen Zhang, Zhengyang Yan, Yalun Dai, Fushuo Huo et al.

Vision-language-action (VLA) models often treat main-view and wrist-view observations as parallel visual inputs, overlooking their distinct roles in robot manipulation. Fine-grained manipulation, however, benefits from anticipating how wrist-local interactions may evolve under the global task context. To address this limitation, we present World-to-Wrist VLA (W2-VLA), a VLA model for fine-grained robot manipulation with task-conditioned future wrist modeling. Given current multi-view observations and a task instruction, W2-VLA contextualizes a set of latent modeling tokens as a compact…

---

## 📅 2026-08-06

### [BridgeVLA++: A Data-Efficient, Generalizable, and Memory-Augmented Vision-Language-Action Framework for 3D Manipulation](https://arxiv.org/abs/2608.05042v1)

- **arXiv**: `2608.05042v1`  |  **提交日期**: 2026-08-05
- **作者**: Peiyan Li, Yuze Zhu, Yixiang Chen, Qisen Ma, Yuan Xu, Jiabing Yang et al.

Leveraging pre-trained vision-language models (VLMs) to construct vision-language-action (VLA) models has emerged as a promising paradigm for 3D robot manipulation. However, existing 3D VLA methods remain data-hungry, exhibit limited generalization under distribution shifts, and lack explicit memory of past observations. These limitations hinder their application to data-scarce, open-world, and memory-dependent manipulation scenarios. Our previous work, BridgeVLA, improves data efficiency and generalization by preserving the input--output alignment of a pre-trained VLM during 3D action…

---

### [Suppression Sticks, Locality Is Fragile: A Closed-Loop Target-and-Control Audit of Task-Vector Negation in VLA Policies](https://arxiv.org/abs/2608.04692v1)

- **arXiv**: `2608.04692v1`  |  **提交日期**: 2026-08-05
- **作者**: Shaoguang Wang, Weiyu Guo, Rushi Dai, Yiren Zhao, Yandong Guo, Hui Xiong

Task-vector arithmetic offers a closed-form way to modify a model, yet its behavioral locality remains unclear in closed-loop robot control. We present a target-and-control audit of per-skill task-vector subtraction from multitask vision-language-action (VLA) policies. Across all ten LIBERO-Goal skills, subtraction produces three qualitatively different regimes: target-control separation for five skills, resistance for three, and global collapse for two. On held-out initial states, the five suppressible targets remain at 0% success; however, mean baseline-normalized control retention is only…

---

### [Mind-VLA: Instruction-Aware Spatial Representation Alignment for Vision-Language-Action Models](https://arxiv.org/abs/2608.04633v1)

- **arXiv**: `2608.04633v1`  |  **提交日期**: 2026-08-05
- **作者**: Xingyu Ding, Yuzhong Zhao, Yang Wu, Chaoyang Zhao, Chunhai Zhao, Yifan Zhang et al.

Recent Vision-Language-Action (VLA) methods improve generalization by aligning their representations with 3D scene geometry. However, these methods are fundamentally instruction-agnostic: the representations align the entire scene uniformly, neglecting the 3D geometry of the specific target object designated by the language instruction. This causes failures on fine-grained manipulation and target occlusion tasks, where success depends on accurate 3D understanding of the target object rather than the entire scene. To address this, we present Mind-VLA, an instruction-aware spatial…

---

### [Retrieve in Time, Correct in Frequency](https://arxiv.org/abs/2608.04527v1)

- **arXiv**: `2608.04527v1`  |  **提交日期**: 2026-08-05
- **作者**: Yuze Fan, Yue Cao, Pengjie Gao, Haojia Gao, Guangqiu Guo, Ziyue Zhang et al.

Frozen vision-language-action (VLA) policies generate temporally extended action chunks, but long-horizon manipulation remains vulnerable to accumulated execution error and visual aliasing across task stages. Successful rollouts provide useful corrective evidence, yet current frame retrieval can return progress-misaligned actions,while direct replay or time-domain fusion can overwrite the reactive structure of the policy proposal. We introduce Retrieve in Time, Correct in Frequency (RTCF), a training-free test-time correction framework that improves frozen VLA performance with low model-side…

---

### [GUARD: Grounding Uncertainty and Ablation-Based Risk Detection for Diffusion-Based VLAs](https://arxiv.org/abs/2608.04510v1)

- **arXiv**: `2608.04510v1`  |  **提交日期**: 2026-08-05
- **作者**: Suhas Hegde, Jitendra Yasaswi Bharadwaj Katta

Diffusion-based vision-language-action (VLA) policies can generate plausible actions even when their predictions are weakly grounded in the visual and language evidence defining the task. We introduce GUARD, a test-time failure detection method that measures this grounding without modifying the pretrained policy. GUARD estimates the influence of token-indexed entries in the final vision-language model key-value (KV) cache, constructs counterfactual caches by ablating salient KV entries, and compares their denoising responses with the original conditioning. Based on the comparison, we derive…

---

### [Deltoris: Enabling Real-time VLA Inference in Embodied AI via Bit-level Sparsity and Speculative Inference](https://arxiv.org/abs/2608.04428v1)

- **arXiv**: `2608.04428v1`  |  **提交日期**: 2026-08-05
- **作者**: Zheng Liu, Zeyu Guo, Zihan Liu, Anbang Wu, Han Zhao, Fangxin Liu et al.

Vision-language-action (VLA) models have emerged as a key component in embodied AI. Among existing approaches, diffusion-based VLA models achieve superior motion quality and generalization. However, diffusion-based VLA models are compute-intensive and must run at high control frequency, e.g., 50-200 Hz. Thus, it imposes strict latency and energy constraints on edge devices. In this work, we present Deltoris, an algorithm-hardware co-design framework for efficient diffusion-based VLA inference. First, we exploit the temporal similarity of consecutive inputs and propose a \textit{temporal-aware…

---

### [CofactVLA: Deconfounding Vision-Language-Action Models via Counterfactual Intervention](https://arxiv.org/abs/2608.04396v1)

- **arXiv**: `2608.04396v1`  |  **提交日期**: 2026-08-05
- **作者**: Yan Zhang, Yinan Wu, Haoran Duan, Jungong Han

Vision-Language-Action (VLA) models have driven significant progress in robotic manipulation, yet they fundamentally struggle with the vision-override phenomenon. Driven by the severe modality imbalance between dense visual streams and sparse linguistic instructions, VLAs frequently fall prey to causal confusion. Instead of treating language as the primary causal driver, the policy entirely bypasses the original instruction by overfitting to spurious visual confounders, such as prominent objects or familiar layouts. To systematically alleviate this bias, we formalize the process of action…

---

### [PhyAI: Real-Time Physical AI at the Edge, Scalable Rollouts in the Cloud](https://arxiv.org/abs/2608.03682v2)

- **arXiv**: `2608.03682v2`  |  **提交日期**: 2026-08-04
- **作者**: Chenghua Wang, Daliang Xu, Dongqi Cai, Duojin Sun, Hao Zhang, Haoze Qian et al.

Physical AI policies require inference throughout their lifecycle, including model evaluation, cloud reinforcement learning rollout, edge GPU serving, and onboard deployment. Although these settings share the same checkpoint and action semantics, they often rely on separate inference programs. To unify them, we build PhyAI, a Physical AI inference engine with a single runtime that keeps architecture-specific conditioning, solver, cache, and output logic in model adapters while sharing graph execution, kernels, memory management, and parallel services. The same codebase runs…

---

## 📅 2026-08-05

### [Track4Action: Distilling World-Centric 3D Tracker into Vision-Language-Action Policies](https://arxiv.org/abs/2608.03727v1)

- **arXiv**: `2608.03727v1`  |  **提交日期**: 2026-08-04
- **作者**: Chenyi Wang, Xinkai Wang, Bokai Lin, Jialin Tian, Fucheng Zhang, Cewu Lu et al.

Action labels tell a vision-language-action (VLA) policy which robot commands to imitate, but not how those commands change the 3D world. The aligned demonstration clip contains this missing supervision because its $K$ frame transitions record the geometry, motion, visibility, and camera change produced during the corresponding $K$ actions. We introduce Track4Action, a framework that distills this realized transition from a frozen world-centric 3D tracker into a current-observation VLA policy. During training, Track4World encodes the clip $V_{t:t+K}$ into a pooled tracker feature. Learnable…

---

### [PhyAI: Real-Time Physical AI at the Edge, Scalable Rollouts in the Cloud](https://arxiv.org/abs/2608.03682v1)

- **arXiv**: `2608.03682v1`  |  **提交日期**: 2026-08-04
- **作者**: Chenghua Wang, Daliang Xu, Dongqi Cai, Duojin Sun, Hao Zhang, Haoze Qian et al.

Physical AI policies require inference throughout their lifecycle, including model evaluation, cloud reinforcement learning rollout, edge GPU serving, and onboard deployment. Although these settings share the same checkpoint and action semantics, they often rely on separate inference programs. To unify them, we build PhyAI, a Physical AI inference engine with a single runtime that keeps architecture-specific conditioning, solver, cache, and output logic in model adapters while sharing graph execution, kernels, memory management, and parallel services. The same codebase runs…

---

### [Unified Visuomotor Targets: Supervising VLAs Beyond Physical Actions](https://arxiv.org/abs/2608.03563v1)

- **arXiv**: `2608.03563v1`  |  **提交日期**: 2026-08-04
- **作者**: Zhenyang Feng, Unnat Jain

VLA models are trained to predict robot actions from visual and language observations. This is a natural choice, but it creates a mismatch: VLMs encode rich, high-level representations of scenes and goals, while robot actions are low-level signals with limited task structure. We ask whether changing what the policy is trained to predict, rather than how it is architecturally designed, can yield better and more efficiently trained policies. We propose UVT (Unified Visuomotor Target), a unified latent prediction target that jointly encodes motor control and visual scene transition information,…

---

### [Continue or Replan? Bernoulli-Continuation Policy Learning for Adaptive Horizon Execution](https://arxiv.org/abs/2608.03483v1)

- **arXiv**: `2608.03483v1`  |  **提交日期**: 2026-08-04
- **作者**: Weichen Xu, Zhenhua Liu, Lin Luo, Yaobo Liang, Chengtang Yao, Qingyu Mei et al.

Existing chunk-based Vision-Language-Action (VLA) models execute a fixed number of actions (i.e., execution horizon) before replanning, turning replanning into a task-agnostic periodic schedule that is independent of task progress. As a result, when no replanning boundary falls before a critical manipulation stage, it is executed from a stale chunk rather than a freshly replanned one. To address this limitation, we propose Bernoulli-Continuation Policy (BCP), a lightweight, plug-and-play framework for adaptive horizon execution that keeps the base VLA frozen. Given a fixed-length action…

---

### [Structure-Aware Robust Fine-Tuning: Defending Vision-Language-Action Robots Against Physical Attention Hijacking](https://arxiv.org/abs/2608.03231v1)

- **arXiv**: `2608.03231v1`  |  **提交日期**: 2026-08-04
- **作者**: Jinquan Zhang, Dongfu Yin, Run Yang, Yufeng Yan, Zhen Tian, F. Richard Yu

Vision-Language-Action (VLA) policies promise general robotic manipulation, but their robustness against physical-world attacks remains fragile. In particular, we show that physically realizable adversarial patches can reliably induce failures by triggering a mechanism we call policy-critical action-to-vision attention hijacking, where action-conditioned attention is diverted from task-relevant regions to a localized patch. To demonstrate the threat, we propose Attention-Guided Semantic Disruption (AGSD), an Expectation-over-Transformation (EOT) optimized printable patch that jointly (i)…

---

### [DRIFT: Derailing Denoising Trajectories of Flow-Matching VLAs with Adversarial Patch Attack](https://arxiv.org/abs/2608.03207v1)

- **arXiv**: `2608.03207v1`  |  **提交日期**: 2026-08-04
- **作者**: Hoseong Tae, Jong-Seok Lee

Flow-matching vision-language-action (VLA) models such as pi0 generate robot actions by integrating a learned denoising velocity field, and have been reported to resist adversarial perturbations that readily fool autoregressive VLAs. We show that this robustness is largely illusory: it stems from prior attacks ignoring the multi-step denoising ODE. We introduce DRIFT (Denoising Redirection via Input perturbation of the Flow-matching Trajectory), a test-time universal adversarial patch placed on the robot's gripper that attacks the denoising velocity field of an off-the-shelf policy. Our…

---

### [How Should Vision-Language-Action Models Use Proprioceptive State?](https://arxiv.org/abs/2608.03052v1)

- **arXiv**: `2608.03052v1`  |  **提交日期**: 2026-08-04
- **作者**: Yiren Zhao, Ziyang Chen, Ziyang Rao, Pengteng Li, He Zhang, Weiyu Guo et al.

Recent Vision-Language-Action (VLA) models almost universally take robot proprioceptive state as input, yet wire it in incompatible ways -- serialized into text prompts, projected into the vision-language prefix, or fed directly to the action expert -- and almost always as a single current frame. Three questions remain open: (1) whether, and on which tasks, current state actually improves closed-loop control; (2) how much state history helps, and whether its benefit reflects genuine temporal variation rather than added conditioning capacity; and (3) where state should enter the model -- the…

---

### [ValueFormer: A Causal Transformer Value Function with Stage-Aware Labels for Semi-Autonomous Vision-Language-Action Policies](https://arxiv.org/abs/2608.02958v1)

- **arXiv**: `2608.02958v1`  |  **提交日期**: 2026-08-03
- **作者**: Inkyu Sa, Konstantin Stulov, Rajat Bhageria

Vision-Language-Action (VLA) policies trained by behavior cloning fail silently: from the action stream alone, a collapsing rollout looks much like one making clean progress, because imitation supplies no notion of progress. Reinforcement learning would supply one, but it is impractical here, where real-robot experience is costly and deformable food resists simulation. The cheap alternative, a terminal success / failure bit, is learnable in principle yet far too sparse to say when a rollout went wrong. We argue that the per-frame label, not the architecture, is the hard part: to be useful it…

---

### [ChainVLA: Chaining Vision-Language-Action Queries through a Unified Execution State for Long-Horizon Manipulation](https://arxiv.org/abs/2608.02326v2)

- **arXiv**: `2608.02326v2`  |  **提交日期**: 2026-08-03
- **作者**: Yuzhi Huang, Weijue Bu, Ziyi Xiong, Jie Wu, Fanding Huang, Jingyan Jiang et al.

Humans perform long-horizon manipulation by retaining knowledge of what earlier actions have established while continuously adapting the motion underway. By contrast, action-chunked vision-language-action (VLA) policies repeatedly replan from the current input at each query. Existing methods preserve either long-term task evidence through memory or short-term motion through action reuse and ensembling, leaving the cross-query handoff incomplete. We introduce ChainVLA, a 1.2B-parameter VLA policy that chains successive queries through a joint and revisable execution state. Progress Context…

---

### [Deferred Exposure of Future Trajectories for Verifiable Reasoning in Autonomous Driving VLMs](https://arxiv.org/abs/2608.01755v2)

- **arXiv**: `2608.01755v2`  |  **提交日期**: 2026-08-03
- **作者**: Zixuan Huang, Yang Zhou, Kaixuan Wang, Guli Zhang, Hongyan Xie, Yakun Zhu et al.

Recent Vision-Language-Action (VLA) models for autonomous driving (AD) increasingly utilize chain-of-thought (CoT) supervision to enhance the reasoning capabilities of their Vision-Language Model (VLM) components, yet existing annotation pipelines commonly expose the teacher model to the logged ground-truth (GT) future trajectory. We empirically show that this induces trajectory anchoring bias: teacher models rationalize the revealed outcome rather than infer a decision from scene evidence, producing less causally faithful CoTs and substantially more severe hallucinations, especially in…

---

## 📅 2026-08-04

### [Ego2Robot: Scalable Robot Data Synthesis from Egocentric Human Data](https://arxiv.org/abs/2608.02580v1)

- **arXiv**: `2608.02580v1`  |  **提交日期**: 2026-08-03
- **作者**: Ye Wang, Pei Lin, Xiong-Hui Chen, Haoqi Yuan, Zhixuan Liang, Yiyang Huang et al.

Learning generalizable robot manipulation policies requires large-scale and diverse demonstration data. Egocentric human manipulation videos offer rich scene and task diversity, and prior work has shown that retargeting and rendering such videos into robot-format data can yield effective per-task policies at small scale. However, whether this approach can provide pretraining benefits for vision-language-action models at scale remains unexplored. We present \textbf{Ego2Robot}, a scalable pipeline that converts egocentric human manipulation videos into robot training data through action…

---

### [Grounded Semantic Re-Binding for Robust Instruction Generalization in Vision-Language-Action Models](https://arxiv.org/abs/2608.02497v1)

- **arXiv**: `2608.02497v1`  |  **提交日期**: 2026-08-03
- **作者**: Zhaokai Yin, Zhipeng Zhang

Vision-Language-Action (VLA) models excel in robotic manipulation but suffer catastrophic performance drops when canonical instructions are simply paraphrased. Although this brittleness is typically addressed through costly data scaling, our probing reveals that the root cause is architectural rather than a lack of semantic understanding. Specifically, we demonstrate that current VLAs successfully retain the correct task identity internally. The failure actually stems from the joint encoding of dynamic visual observations and text, which introduces systematic feature shifts. Because the…

---

### [ChainVLA: Chaining Vision-Language-Action Queries through a Unified Execution State for Long-Horizon Manipulation](https://arxiv.org/abs/2608.02326v1)

- **arXiv**: `2608.02326v1`  |  **提交日期**: 2026-08-03
- **作者**: Yuzhi Huang, Weijue Bu, Ziyi Xiong, Jie Wu, Fanding Huang, Jingyan Jiang et al.

Humans perform long-horizon manipulation by retaining knowledge of what earlier actions have established while continuously adapting the motion underway. By contrast, action-chunked vision-language-action (VLA) policies repeatedly replan from the current input at each query. Existing methods preserve either long-term task evidence through memory or short-term motion through action reuse and ensembling, leaving the cross-query handoff incomplete. We introduce ChainVLA, a 1.2B-parameter VLA policy that chains successive queries through a joint and revisable execution state. Progress Context…

---

### [Learning Panorama-Aware VLA for Mobile Manipulation with Whole-Body Teleoperation](https://arxiv.org/abs/2608.02257v1)

- **arXiv**: `2608.02257v1`  |  **提交日期**: 2026-08-03
- **作者**: Donglin Yang, Haoran Chen, Xingyu Chen, Lixing Liu, Manyi Li, Changhe Tu et al.

Mobile manipulation is a key capability for embodied intelligence, enabling robots to accomplish complex multi-stage tasks in open-world environments. However, mobile manipulation poses two key challenges for vision-language-action (VLA) policies: At the data level, the efficient collection of high-quality whole-body demonstrations demands the coordinated control of both the mobile base and the robotic arms; at the model level, existing VLA models predominantly rely on local camera observations, whose limited field of view hinders global spatial understanding. To address these challenges, we…

---

### [Look Where It Matters: Adaptive Visual Refinement for Vision-Language-Action Models](https://arxiv.org/abs/2608.02197v1)

- **arXiv**: `2608.02197v1`  |  **提交日期**: 2026-08-03
- **作者**: Jin Cui, Yanbin Hu, Xinyue Long, Linkai Li, Boran Zhao, Pengju Ren

Visual representations of VLA models remain unreliable for spatially precise robotic manipulation. We uncover that vision encoders in VLAs also exhibit attention artifacts previously documented in generic Vision Transformers, and further show that, in embodied policies, these artifacts are closely associated with spatial perception capabilities acquired during post-training. As the encoder learns task-relevant information such as object location, depth ordering, and local geometry, limited global-token capacity causes part of this information to spill into low-information patch tokens. We…

---

### [Weights or Skills? A Survey of Robot-Learning Techniques: from Action-Predicting Weights to Robots that Write their Own Skills](https://arxiv.org/abs/2608.01851v1)

- **arXiv**: `2608.01851v1`  |  **提交日期**: 2026-08-03
- **作者**: Gaytri Jena, Kapil Wanaskar, Vinija Jain, Aman Chadha, Vasu Sharma, Amitava Das

Robot learning is splitting into two bets: policies that bake competence into frozen weights (vision-language-action, or VLA, models), and agents that write and refine their own executable skills as code. This survey organises the field around that axis of weights versus skills. Its central analytical contribution is a deep-dive that arranges code-as-policy methods by their degree of self-improvement, from zero-shot program synthesis, through closed-loop self-repair and persistent skill memory, to the sparsely populated cell in which execution feedback, skill memory, and evolutionary search…

---

### [Multi-View Unified Camera Fields: Geometry-Shaped Action-Facing Representations for RGB-Only Multi-Camera VLA Policies](https://arxiv.org/abs/2608.01826v1)

- **arXiv**: `2608.01826v1`  |  **提交日期**: 2026-08-03
- **作者**: Jiarui Yang, Yehao Lu, Yuning Su, Yufeng Xie, Yu Zhong, Haiyu Lan et al.

Vision-Language-Action (VLA) models have shown strong generalization in robotic manipulation, yet complex contact-rich tasks often benefit from multi-camera observations that jointly capture the end effector, objects, and targets under occlusion. Existing multi-camera VLAs usually concatenate view tokens, leaving action representations weak in metric depth and inconsistent across cameras. We introduce Multi-View Unified Camera Fields (MVUCF), a training-only framework that forms a shared action-facing latent field across views. A coordinate-query depth objective makes metric depth…

---

### [ReTouch: Empowering Contact-Rich Dexterous Manipulation with Online-Refined Tactile Prediction](https://arxiv.org/abs/2608.01824v1)

- **arXiv**: `2608.01824v1`  |  **提交日期**: 2026-08-03
- **作者**: Shiqi Zhang, Xin Zhang, Yedong Shen, Jiajun Deng, Yuxuan Gao, Sha Zhang et al.

Fusing tactile signals has proven effective for contact-rich manipulation, enabling robots to perceive contact states and adapt to rapidly changing physical interactions. Yet effectively integrating tactile feedback into dexterous manipulation remains underexplored. In this work, we introduce ReTouch, a vision-language-action model (VLA) that supports contact-rich dexterous manipulation through tactile predictions continually refined online using execution-time feedback. ReTouch builds on two main innovations for tactile representation and closed-loop action generation. First, its…

---

### [Deferred Exposure of Future Trajectories for Verifiable Reasoning in Autonomous Driving VLMs](https://arxiv.org/abs/2608.01755v1)

- **arXiv**: `2608.01755v1`  |  **提交日期**: 2026-08-03
- **作者**: Zixuan Huang, Yang Zhou, Kaixuan Wang, Guli Zhang, Hongyan Xie, Yakun Zhu et al.

Recent Vision-Language-Action (VLA) models for autonomous driving (AD) increasingly utilize chain-of-thought (CoT) supervision to enhance the reasoning capabilities of their Vision-Language Model (VLM) components, yet existing annotation pipelines commonly expose the teacher model to the logged ground-truth (GT) future trajectory. We empirically show that this induces trajectory anchoring bias: teacher models rationalize the revealed outcome rather than infer a decision from scene evidence, producing less causally faithful CoTs and substantially more severe hallucinations, especially in…

---

### [ProtoAct: Turning Wet-Lab Protocols into Embodied Robotic Actions](https://arxiv.org/abs/2608.01690v1)

- **arXiv**: `2608.01690v1`  |  **提交日期**: 2026-08-03
- **作者**: Zhe Liu, Jiaming Gu, Zhaohui Du, Zhe Wang, Huanbo Jin, Quan Lu et al.

Biological wet-lab protocols are written for trained researchers and often leave routine operations, state-dependent conditions, and contextual parameters implicit, making them difficult to translate into robot-executable actions. We present ProtoAct, a structured protocol-grounding framework that converts free-form biological procedures into state-aware, embodiment-ready action sequences. ProtoAct uses ProtoRAG to retrieve manually annotated examples for context-sensitive parsing, employs RefineChecker to detect and revise missing or inconsistent steps, and applies ActSchema to map the…

---

### [Uncovering and Mitigating Positional Blind Spots in Vision-Language-Action Models](https://arxiv.org/abs/2608.01573v1)

- **arXiv**: `2608.01573v1`  |  **提交日期**: 2026-08-03
- **作者**: Dongdong An, Pengjie Zhao, Yihao Huang, Wenbing Tang, Ziming He, Jiayi Zhu et al.

Recent Vision-Language-Action (VLA) models achieve promising performance in robotic manipulation, typically measured by success rates aggregated over predefined object configurations, an evaluation that implicitly assumes spatially uniform competence across the workspace. However, this assumption does not hold: even with the instruction and every other scene factor held fixed, merely relocating a task-irrelevant distractor can sharply raise the failure probability within localized, spatially coherent regions, which we term Positional Blind Spots (PBS). In this paper, we propose a two-stage…

---

### [Demystifying When and Why VLAs Fail in Contact-Rich Tasks and How to Fix Them](https://arxiv.org/abs/2608.01402v1)

- **arXiv**: `2608.01402v1`  |  **提交日期**: 2026-08-02
- **作者**: Carlota Parés-Morlans, Nils Kuhn, Isabel Liu, Alberta Longhini, Jeannette Bohg

We address the problem of understanding when and why Vision-Language-Action models struggle with contact-rich manipulation tasks that require precise physical interaction. Prior work has primarily focused on addressing contact failures through force-augmented architectures and training-time regularizers, yet the root causes of these failures remain underexplored. We identify two distinct failure modes underlying this gap. Precision failures are rooted in a flow-matching policy training mismatch, and force failures arise from the distinctive structure of force signals. We address each failure…

---

### [DreamTrajectory: Trajectory-Guided Action Generation with World Model Alignment for Mobile Manipulation](https://arxiv.org/abs/2608.01381v1)

- **arXiv**: `2608.01381v1`  |  **提交日期**: 2026-08-02
- **作者**: Zheng Yang, Wenjie Zhang, Xiangyu Chen, Wenxuan Song, Xianpeng Wang, Yihang Kang et al.

Mobile manipulation requires a robot to coordinate base and arm motion under continuously changing viewpoints and contact conditions, within an action space far larger than that of fixed-base manipulation. Existing Vision-Language-Action (VLA) policies are limited in two respects. (i)They map observations directly to whole-body action chunks, searching this large action space without an explicit task-space motion plan, which makes coordinated base--arm prediction imprecise. (ii)They execute the predicted chunk open-loop, without checking whether the actions can realize the motion the policy…

---

### [Hermite Curves as Trajectory Priors for Vision-Language-Action Models](https://arxiv.org/abs/2608.01265v1)

- **arXiv**: `2608.01265v1`  |  **提交日期**: 2026-08-02
- **作者**: Qi Lv, Jianming Xing, Zhao Yang, Mingyuan Yao, Yinan Shi, Yawei Jueluo et al.

Despite recent progress in Vision-Language-Action (VLA) models for robotic manipulation, the action chunk remains a weakly structured interface. Existing work typically flatten each chunk into per-timestep controls, relying on implicit data learning that manifests as jagged motion and boundary discontinuities during physical execution. To address these limitations, we introduce Hermite trajectory priors, parameterizing the chunk trajectory as a piecewise cubic Hermite curve defined by endpoint positions and velocities to explicitly enforce smoothness and continuity. We instantiate this fixed…

---

### [WAM-Diff2: Hierarchical AR-to-Diffusion Distillation for Highly Efficient Autonomous Driving VLA](https://arxiv.org/abs/2608.01035v1)

- **arXiv**: `2608.01035v1`  |  **提交日期**: 2026-08-02
- **作者**: Zhihao Zhu, Hanlin Shang, Mingwang Xu, Feipeng Cai, Zhuolin He, Yaoyi Li et al.

Vision-Language-Action (VLA) models have emerged as a prominent paradigm for end-to-end autonomous driving; however, their efficient deployment is severely constrained by high computational latency and exposure bias arising from sequential autoregressive decoding. Conversely, while specialized diffusion policies enable low-latency, parallel execution, training them from scratch typically yields narrow, single-task architectures that lack holistic visual-linguistic reasoning. Successfully transforming pre-trained autoregressive generalists into parallel diffusion models could combine…

---

### [VLAGuard: A Framework for Evaluating and Mitigating Physical Attention Hijacking in Vision-Language-Action Robots within Wireless Sensor Networks](https://arxiv.org/abs/2608.01028v1)

- **arXiv**: `2608.01028v1`  |  **提交日期**: 2026-08-02
- **作者**: Dongfu Yin, Jinquan Zhang

Deploying Vision-Language-Action (VLA) robots as mobile edge nodes within wireless sensor networks (WSNs) requires robust protection against physical adversarial threats. We present VLAGuard, a framework to assess and mitigate a critical vulnerability: policy-critical action-to-vision attention hijacking. We first introduce a stress-test module, Visuomotor Attention-guided Semantic Attack (VASA), using printable patches to severely distract the robot's action-conditioned cross-attention. To counter this, we propose Attention-Protective Fine-Tuning (APFT), a defense that stabilizes…

---

### [RL Bootstrapping of OpenVLA-OFT for a Novel Robot Embodiment](https://arxiv.org/abs/2608.01013v1)

- **arXiv**: `2608.01013v1`  |  **提交日期**: 2026-08-02
- **作者**: Damir Nurtdinov, Alexei Kornaev, Alexander Maloletov

Adapting a pretrained vision-language-action (VLA) policy to a new robot usually assumes embodiment-specific demonstrations. This assumption is especially restrictive for custom robots whose morphology differs strongly from the manipulators seen in large robot datasets. We study a harder setting: zero-demo embodiment alignment of OpenVLA-OFT on a cable-driven parallel robot (CDPR) with a simple gripper and a previously unseen control interface. Instead of supervised fine-tuning, we use reinforcement learning in simulation with dense geometric rewards computed from simulator state. The…

---

### [Latency-Tolerant Cloud-Edge Collaborative Vision-Language-Action Models via Emergent Representational Specialization](https://arxiv.org/abs/2608.00569v1)

- **arXiv**: `2608.00569v1`  |  **提交日期**: 2026-08-01
- **作者**: Daojie Peng, Fulong Ma, Bingtao Wang, Sheng Wang, Jun Ma

Deploying billion-parameter Vision-Language-Action (VLA) policies on mobile robots creates a systems conflict: semantic reasoning benefits from cloud GPUs, whereas closed-loop control must respond locally despite network delay and jitter. Existing hierarchical and asynchronous policies improve throughput, but their slow-path representations can still arrive stale or require explicit scheduling and delay cues. We introduce CloudEdgeVLA, a cloud-edge policy that treats temporal misalignment as a representation-learning problem. A cloud VLA encodes delayed observations into slowly varying task…

---

### [The Gate, Not the Cache: Gate Provenance Bounds the Closed-Loop Reliability of Training-Free VLA Token Skipping](https://arxiv.org/abs/2608.00391v1)

- **arXiv**: `2608.00391v1`  |  **提交日期**: 2026-08-01
- **作者**: Qi Luo, Shuaijun Liu, Hao Zhao, Kunlin Li, Xiaobo Wang, Ningxing Su et al.

Token skipping is a widely used training-free way to accelerate vision--language--action (VLA) models by bypassing computation for most visual tokens at each control step according to a gate. When the next gate is harvested from the previous accelerated forward, however, the tokens skipped at one step are also the ones least visible to the next gate, and the damage can compound across control steps until the task fails. We study the two mechanisms this class is built on, reuse and deletion, crossing each against where its gate signal comes from on identical episodes. At a skip ratio of 0.9 on…

---

## 📅 2026-08-03

### [WCM: A World Critic Model for Vision-Language-Action Reinforcement Learning](https://arxiv.org/abs/2607.29613v1)

- **arXiv**: `2607.29613v1`  |  **提交日期**: 2026-07-31
- **作者**: Senyu Fei, Xiaopeng Yu, Siyin Wang, Xianzhong Zhao, Jingjing Gong, Xipeng Qiu

Reinforcement learning (RL) post-training of Vision-Language-Action (VLA) models has shown strong promise for robotic manipulation. Among RL methods, critic-based approaches rely on a value estimator that predominantly operates on single-frame observations or single-frame VLM backbone latents, which is a fundamental mismatch with the partially observable nature of robot control. A naive approach to incorporate observation history into the critic incurs exponential complexity with high-dimensional visual space, and still fails because pure scalar-return regression provides insufficient…

---

### [FibVLA: An Efficient Temporal Vision-Language-Action Model with Fibonacci Sampling](https://arxiv.org/abs/2607.29596v1)

- **arXiv**: `2607.29596v1`  |  **提交日期**: 2026-07-31
- **作者**: Li Lin, Wujun Xu, Weiwei Meng, Kaiwen Xia, Kang Hao Cheong, Shuai Wang

Vision-language-action models (VLAs), which leverage the cognition of multimodal information to infer physical-world actions, provide a generalized solution for embodied AI applications. Conventional VLAs usually concentrate on current digital cognition. While some efforts are made to enhance VLAs' reasoning capabilities by capturing temporal information, encoding the long-context history causes an efficiency-decreasing issue. To reconcile the conflict between capturing temporal information and maintaining inference efficiency in VLAs, this paper introduces FibVLA, an efficient framework…

---

### [Safe Vision Language Action Models via Barrier Enhanced Flow Matching](https://arxiv.org/abs/2607.29569v1)

- **arXiv**: `2607.29569v1`  |  **提交日期**: 2026-07-31
- **作者**: Kasra Sinaei, Hung-Chieh Wu, Donald Ebeigbe

This article presents a modular inference framework that integrates Flow Matching generative models with formal Control Barrier Function (CBF) safety guarantees. Unlike existing methods that apply external safety filters to a model's final output, our approach modifies the Flow Matching denoising process within the model to inherently generate safe trajectories. By employing a smooth Log-Sum-Exponential aggregate barrier, we enforce safety over entire action chunks. This aggregate barrier ensures a minimal increase in computational overhead and does not alter the semantic intent of the model.…

---

### [ActFovea: Runtime Safeguarding for VLA Policies via Spatiotemporal Visual-Action Consistency](https://arxiv.org/abs/2607.29169v1)

- **arXiv**: `2607.29169v1`  |  **提交日期**: 2026-07-31
- **作者**: Wenda Yu, Tianshi Wang, Fengling Li, Xin Li, Jingjing Li, Lei Zhu

Vision-language-action (VLA) policies achieve strong performance in robotic manipulation but remain vulnerable to runtime disturbances that break the temporal alignment among visual observations, robot states, and executed actions. We introduce ActFovea, a plug-and-play safeguarding framework that detects and mitigates such failures without retraining or modifying the underlying VLA policy. ActFovea uses robot kinematics, proprioceptive states, and recent actions to construct action-conditioned foveated regions that retain contact-relevant areas and predicted motion corridors while…

---

## 📅 2026-07-31

### [ACE-Data-0: Human-Centric Ambient Capture as Embodied Data Engine](https://arxiv.org/abs/2607.28625v1)

- **arXiv**: `2607.28625v1`  |  **提交日期**: 2026-07-30
- **作者**: Yukang Cao, Haozhe Xie, Beichen Wen, Runmao Yao, Yinghao Liu, Yue Huang et al.

Embodied intelligence faces a fundamental data bottleneck. Models must capture how first-person perception, whole-body motion, dexterous manipulation, object state, sound, and touch evolve together as humans pursue goals over time. Existing datasets fragment this experience across viewpoints, modalities, or spatial scales, leaving the full perception-action loop only partially observed. We introduce the Ambient Capture Engine (ACE), a human-centric data engine that transforms real home environments into spatially calibrated, temporally synchronized recording studios. ACE operates at two…

---

### [RoboBRIDGE: A Modular Framework for Bridging Policies to Robust Real-World Robotic Agents](https://arxiv.org/abs/2607.27881v1)

- **arXiv**: `2607.27881v1`  |  **提交日期**: 2026-07-30
- **作者**: Sihyung Yoon, Minjong Yoo, Sanghyun Ahn, Seojeong Choi, Honguk Woo

Vision-Language-Action (VLA) models have attracted growing interest as a scalable approach to robotic manipulation. While these models are effective action predictors, deploying them as robotic agents exposes critical gaps: no mechanism for failure recovery, inconsistent execution over long horizons, and limited robustness to shifts in observations, tasks, or embodiments. Existing solutions address these limitations individually through model retraining or environment-specific modules, yet what is needed is a general framework that systematically transforms a pretrained VLA into a robotic…

---

### [RedFlow: Redirect Failure into Action-Level Corrections for Flow-matching VLA Policy](https://arxiv.org/abs/2607.27782v1)

- **arXiv**: `2607.27782v1`  |  **提交日期**: 2026-07-30
- **作者**: Zhengyang Yan, Junhao Li, Fangqi Zhu, Zijun Wang, Quanxin Shou, Yikun Miao et al.

Flow-matching Vision-Language-Action (VLA) policies have shown strong potential for robotic manipulation but often suffer from compounding errors caused by distribution shifts during deployment. While offline reinforcement learning (RL) provides a practical way to improve deployed policies using rollout data, existing methods either ignore failure data or exploit it only at the trajectory level, resulting in low learning efficiency and persistent errors. We propose **RedFlow**, a fine-grained offline RL framework that redirects failure experiences into action-level corrective supervision for…

---

### [RL$^2$-VLA: Adaptive RL Latent Compositional Steering with Test-Time Scaling for Vision-Language-Action Models](https://arxiv.org/abs/2607.26991v2)

- **arXiv**: `2607.26991v2`  |  **提交日期**: 2026-07-29
- **作者**: Derek Ming Siang Tan, Shailesh Shailesh, Srikrishna Iyer, William Wei Jie Teo, Yuanliang Ju, Qiao Gu et al.

Despite the impressive visuomotor capabilities enabled by Vision-Language-Action (VLA) models, their performance often degrades on challenging and out-of-domain tasks. Recent test-time steering and scaling methods improve performance without extensive data collection and retraining, but action samples often remain concentrated around similar behaviors and therefore inherit correlated failure modes. Moreover, existing methods apply the same intervention strategy at every timestep, regardless of whether the base policy is already likely to succeed. To address these limitations, we introduce…

---

## 📅 2026-07-30

### [TurboVLA: Real-Time Vision-Language-Action Model at 32 Hz on an RTX 4090 with <1 GB VRAM](https://arxiv.org/abs/2607.27205v1)

- **arXiv**: `2607.27205v1`  |  **提交日期**: 2026-07-29
- **作者**: Hengyi Xie, Chenfei Yao, Xianjin Wu, Xuanyang Xi, Yiping Tang, Di Xu et al.

Vision-language-action (VLA) models commonly adopt an LLM-centric $V \to L \to A$ pathway, where visual observations are projected into the representation space of a large language model before being decoded into robot actions. Although effective, this design incurs substantial computation and memory overhead at every policy invocation. In this work, we introduce TurboVLA, a new VLA paradigm that reformulates the conventional $V \to L \to A$ pathway as a direct $V + L \to A$ mapping. Instead of using a large language model as the central interface between perception and action, TurboVLA…

---

### [DLAM: Distributional Latent Actions with Temporal Constraints](https://arxiv.org/abs/2607.27138v1)

- **arXiv**: `2607.27138v1`  |  **提交日期**: 2026-07-29
- **作者**: Zuojin Tang, Feifan Luo, Haoyun Liu, Botai Yuan, Dekang Qi, Ronghan Chen et al.

Vision-language-action (VLA) models remain constrained by scarce action-labeled robot data, whereas action-free videos offer abundant observations of physical change. Latent action models can extract such priors, but reconstruction-trained codes may predict future observations without the structure required for joint generation with robot actions. Existing structured methods add temporal constraints but retain deterministic transition points, so residual errors in locally inferred transitions may propagate and compound under recursive composition. We introduce DLAM, a distributional…

---

### [RL$^2$-VLA: Adaptive RL Latent Compositional Steering with Test-Time Scaling for Vision-Language-Action Models](https://arxiv.org/abs/2607.26991v1)

- **arXiv**: `2607.26991v1`  |  **提交日期**: 2026-07-29
- **作者**: Derek Ming Siang Tan, Shailesh Shailesh, Srikrishna Iyer, William Wei Jie Teo, Yuanliang Ju, Qiao Gu et al.

Despite the impressive visuomotor capabilities enabled by Vision-Language-Action (VLA) models, their performance often degrades on challenging and out-of-domain tasks. Recent test-time steering and scaling methods improve performance without extensive data collection and retraining, but action samples often remain concentrated around similar behaviors and therefore inherit correlated failure modes. Moreover, existing methods apply the same intervention strategy at every timestep, regardless of whether the base policy is already likely to succeed. To address these limitations, we introduce…

---

### [CheckVLA: Execution-Time Verification with Action-Conditioned World Model for Long-Horizon Mobile Manipulation](https://arxiv.org/abs/2607.26789v1)

- **arXiv**: `2607.26789v1`  |  **提交日期**: 2026-07-29
- **作者**: Yushan Liu, Peibo Sun, Xintao Chao, Zhenyang Yang, Yifan Xie, Lingfeng Zhang et al.

Vision-language-action (VLA) policies commonly execute long-horizon mobile manipulation through open-loop action chunks, issuing multiple actions without receiving new high-level visual input. A committed chunk therefore implies how observations should evolve, but accidental deviations can violate this expectation while the remaining actions continue to propagate the error: commit-time policy confidence cannot react to a deviation that occurs after dispatch, and observation-only anomaly scores lack an action-conditioned reference for separating expected effects from unexplained changes. We…

---

### [Explicit Kinematic Guidance from Analytic Concepts for Vision-Language-Action Models](https://arxiv.org/abs/2607.26513v1)

- **arXiv**: `2607.26513v1`  |  **提交日期**: 2026-07-29
- **作者**: Mingyang Sun, Jiude Wei, Xiujian Liang, Qichen He, Donglin Wang, Cewu Lu et al.

Current Vision-Language-Action (VLA) models rely mainly on 2D inputs, neglecting the rich object structural information and commonsense knowledge inherent in the 3D physical world. This deficiency restricts their spatial awareness and adaptability for complex, high-precision manipulation. To bridge this crucial gap, we construct a Concept Expert module for VLA to build executable Analytic Concepts that represent objects as explicit, programmatic blueprints. Our mechanism operates in two synergistic phases: First, prior to VLA inference, the Concept Expert leverages 3D information from Vision…

---

### [CG-World: A Large-Scale World-State Dataset and Protocol for World Models](https://arxiv.org/abs/2607.26452v1)

- **arXiv**: `2607.26452v1`  |  **提交日期**: 2026-07-29
- **作者**: Yiming Cai, Fangjie Yu, Meiqing Yu, Ziyue Shi, Pengfei Yuan, Yong Guo

World models must learn the joint dynamics of states, actions, events, and observations, yet existing video, robotics, and simulation datasets usually capture only part of this structure. We introduce CG-World, a large-scale world-state dataset and protocol derived from industrial computer graphics production pipelines. CG-World explicitly records intermediate states, including multimodal semantics, spatial structure, skeletal and controller states, motion curves, camera and lighting parameters, physics caches, contact events, and multi-pass renderings. CG-World v1 contains approximately…

---

## 📅 2026-07-29

### [SAM3D-Guided Object-Centric Representation Alignment for Vision-Language-Action Models](https://arxiv.org/abs/2607.25912v1)

- **arXiv**: `2607.25912v1`  |  **提交日期**: 2026-07-28
- **作者**: Zonghe Liu, Shanyuan Jie, Xiaoquan Sun, Chen Cao, Zetian Xu, Zongsheng Liu et al.

Vision-Language-Action (VLA) models have shown strong potential for general robot manipulation, but most existing models rely on 2D visual-language backbones and lack fine-grained 3D understanding of target objects, especially under occlusion, pose variation, scale changes, and precise spatial interaction. We propose an object-centric 3D representation alignment framework built upon $π_0$, using SAM3D as a frozen 3D teacher to provide target-object 3D priors during training. Specifically, we localize task-relevant objects with object recognition models, generate corresponding object masks,…

---

### [HiFi-UMI: Learning Deployable Manipulation Policies from High-Fidelity UMI Data Alone](https://arxiv.org/abs/2607.25895v1)

- **arXiv**: `2607.25895v1`  |  **提交日期**: 2026-07-28
- **作者**: Simple AI,  :, Yuteng Wei, Jinming Ma, Jiawei Wang, Weitao Zhou et al.

Learning deployable manipulation policies is bottlenecked by the scarcity of data that is both high-fidelity and scalable. Real-robot teleoperation is accurate but costly to scale; robot-free UMI capture scales readily, and current practice uses the resulting data mainly for pre-training, adding a small real-robot "anchor" at post-training. We ask whether raising the fidelity of robot-free UMI data, rather than shrinking the real-robot fraction, can remove that anchor. We present HiFi-UMI, a portable UMI data-production system co-designed for trajectory accuracy, inter-gripper relative pose,…

---

### [A Causality-aware Infer-diagnose-refine Framework for Test-time Modality Adaptation in VLA Models](https://arxiv.org/abs/2607.25516v1)

- **arXiv**: `2607.25516v1`  |  **提交日期**: 2026-07-28
- **作者**: Haoyu Zhang, Yuwei Wu, Jin Chen, Gao Zhi, Zhenxin Diao, Mingyang Gao et al.

Vision-language-action (VLA) models predict sequential actions to execute tasks specified by language instructions, conditioned on visual observations and proprioceptive states. However, how to fuse modalities in VLA models remains an open problem, since robot manipulation involves dynamic phases, such as long-distance movements and close-range interactions, in which the importance of visual observations may vary over time. In this paper, we propose an infer-diagnose-refine (IDR) framework, a model-agnostic framework that can be integrated with diverse VLA architectures for refining action…

---

### [CoTinyVLA: Chain-of-Thought Distillation for a Sub-Billion-Parameter Vision-Language-Action Model](https://arxiv.org/abs/2607.25487v1)

- **arXiv**: `2607.25487v1`  |  **提交日期**: 2026-07-28
- **作者**: Minhyeok Lee, Chiyoung Kim, Chanhoe Gu, Seongrok Kim, Sanghyuk Roy Choi, Donghwan Hwang et al.

Vision-Language-Action (VLA) models translate natural-language commands into robot action sequences, but leading systems on the LIBERO-Plus robustness benchmark use three- to seven-billion-parameter backbones whose memory demands can exceed embedded robotic budgets. We present CoTinyVLA, a 0.9B-parameter action model on a Qwen3.5-0.8B backbone that obtains that robustness by structuring supervision instead of enlarging the model. Three components target different axes of the problem: dual-view temporal input of 16 history frames per step with textual camera and time markers; hierarchical…

---

## 📅 2026-07-28

### [Data Pyramid for Embodied Manipulation](https://arxiv.org/abs/2607.24744v1)

- **arXiv**: `2607.24744v1`  |  **提交日期**: 2026-07-27
- **作者**: Yifan Ye, Yankai Fu, Yaoxu Lv, Bohan Hou, Jun Cen, Lingdong Kong et al.

Multimodal foundation models learned to see and to speak by consuming the whole internet. Embodied agents admit no such shortcut, since they require data that couple observations with physical states and actions. These signals can be provided, to varying degrees, by multiple data sources. In this work, we organize the embodied data ecosystem as a "pyramid" spanning five complementary sources: real-robot data, UMI-style data, egocentric and exocentric data, simulation data, and general vision-language data. We organize the pyramid around the tension between scalability and robot alignment, and…

---

### [τ: Learning Touch-Augmented Vision-Language-Action Models from Future Visual Supervision](https://arxiv.org/abs/2607.24485v1)

- **arXiv**: `2607.24485v1`  |  **提交日期**: 2026-07-27
- **作者**: Ning Cheng, Jinan Xu, Wanlin Li, Yangzhi Chen, Jing Gao, Yiqun Wang et al.

Learning the informative tactile representation while effectively adapting it to pretrained Vision-Language-Action (VLA) models remains challenging at both the data and modeling levels. At the data level, limited task-specific demonstrations constrain representation quality, whereas large-scale pretraining incurs substantial costs. At the modeling level, existing methods either focus on instantaneous contact states or model temporal interaction dynamics using 6D wrench sequences, leaving high-dimensional tactile signals underexplored. To address these challenges, we present τ, a…

---

### [ArmnetBench v0.1: Parallel Real-World Evaluation of Manipulation Policies on a Low-Cost Arm Farm](https://arxiv.org/abs/2607.24481v1)

- **arXiv**: `2607.24481v1`  |  **提交日期**: 2026-07-27
- **作者**: Praveen Selvaraj, Lorenzo Uttini, Ville Kuosmanen

Real-world evaluation is a bottleneck in developing generalist robot manipulation policies. Each rollout requires physical hardware and an operator to set up, reset, and score it. We introduce ArmnetBench v0.1, a benchmark run on a fleet of low-cost SO-101 cells under light on-site supervision. v0.1 validates this arm farm end to end and compares 7 policies across 12 tasks with both single-arm and bimanual configurations. Each policy is trained or fine-tuned on 50 demonstrations per task; the benchmark contains 2,518 policy rollouts and 600 reference demonstrations. All 3,118 episodes carry a…

---

### [DeVA: Decoupled Video-Action Model with physical guidance for robot policy learning](https://arxiv.org/abs/2607.24159v1)

- **arXiv**: `2607.24159v1`  |  **提交日期**: 2026-07-27
- **作者**: Mengqi Zhang, Sahil Khose, Simar Kareer, Yuchen Song, Unnat Jain, Judy Hoffman

Generalizable robot manipulation requires policies that can anticipate how visual scenes evolve while executing language instructions. While recent Vision-Language-Action models benefit from large-scale pretraining, their predominantly static pretraining objectives provide limited supervision for physical dynamics and temporal causality, leaving control-relevant knowledge to be learned from downstream robot demonstrations. Video generative models offer a promising foundation by encoding rich spatiotemporal priors through future predictions. However, existing Video-Action Models either couple…

---

### [A Motion-Aware Vector Quantization Framework with Centroid Reuse for Efficient VLA Inference](https://arxiv.org/abs/2607.24148v1)

- **arXiv**: `2607.24148v1`  |  **提交日期**: 2026-07-27
- **作者**: Zhuoran Song, Haozhe Jiang, Chunyu Qi, Minnan Pei, Gang Li, Xiaoyao Liang et al.

Vision-Language-Action (VLA) models have demonstrated strong potential for embodied AI, yet their high inference latency on GPUs limits real-time deployment. Existing accelerators, such as Dadu-Corki, improve efficiency but treat VLA models as full-precision workloads, leaving substantial redundancy in both memory and computation underexploited. In this paper, we propose VQVLA, an algorithm-hardware co-design framework that accelerates VLA inference by exploiting weight similarity and execution dynamics. We first introduce MotionVQ, a motion-aware vector quantization scheme that dynamically…

---

### [FutureRTC: Real-Time Robot Execution with Anticipatory-Conditioned Action Chunking](https://arxiv.org/abs/2607.24008v1)

- **arXiv**: `2607.24008v1`  |  **提交日期**: 2026-07-27
- **作者**: Hai Jiang, Yixian Zou, Binbin Liang, Boqian Liu, Fanman Meng, Shuaicheng Liu

Real-time deployment of Vision-Language-Action (VLA) policies necessitates asynchronous execution, wherein subsequent action chunks are computed concurrently with the execution of the current chunk, leading to prediction-execution misalignment and manifesting as inter-chunk discontinuities. Existing methods either superficially smooth chunk boundaries, require costly policy optimization, or exclusively forward-predict proprioceptive states yet neglect critical visual observations. In this paper, we propose \textbf{FutureRTC}, a plug-and-play adaptation framework that predicts execution-time…

---

### [MulRobBench: A Decision-Level Benchmark for Safe and Security-Policy-Compliant Multimodal UAV Agents](https://arxiv.org/abs/2607.23870v1)

- **arXiv**: `2607.23870v1`  |  **提交日期**: 2026-07-26
- **作者**: Belal S. Alsinglawi, Weizheng Wang, Junyi Wu, Yi Jiang, Lianhai Lin, Merouane Debbah et al.

Smart-city airspace is transforming Uncrewed Aerial Vehicles (UAVs) from passive sensing platforms into cyber-physical decision makers that must follow operational rules under degraded observations and ambiguous language. Existing UAV and multimodal benchmarks evaluate perception, navigation, collaboration, and reasoning, but few assess whether physical evidence, protocol constraints, and action risk remain coupled during critical decisions. We introduce MulRobBench, an offline, protocol-conditioned benchmark for Vision-Language-Action (VLA) UAV agents in smart-city environments. MulRobBench…

---

### [A Few Words Go a Long Way: Language Guided Robot Policy Synthesis](https://arxiv.org/abs/2607.23784v1)

- **arXiv**: `2607.23784v1`  |  **提交日期**: 2026-07-26
- **作者**: Daphne Chen, Archit Ritesh Jain, Eric Goossen, Emma Romig, Michael Murray, Nick Walker et al.

While vision-language-action models have demonstrated impressive zero-shot manipulation capabilities, they remain fundamentally black box policies that are difficult to interpret, adapt, or correct when they inevitably fail. In this work, we propose ARCHITECT, a framework that treats robot policy acquisition as an interactive program synthesis task. ARCHITECT leverages the reasoning capabilities of LLM coding agents to synthesize modular robot programs that utilize a suite of perception and control tools. Unlike end-to-end models where distribution shift leads to unpredictable, cascading…

---

### [WCM: World-Cognition Model for Generalizable Human-Robot Interaction](https://arxiv.org/abs/2607.22999v1)

- **arXiv**: `2607.22999v1`  |  **提交日期**: 2026-07-25
- **作者**: Yuzhen Chen, KC Zhou

Language agents can now interact fluently with users in software, but robots still struggle to bring comparable interaction to physical tasks. Current robot-control paradigms, including vision-language-action policies and world-model-based planners, are mainly optimized for instruction execution, leaving users with little visibility into why an action is chosen and few mechanisms to redirect, correct, or teach the robot through interaction. To solve this problem, we present the World-Cognition Model (WCM), a human-centered embodied agent built on the SLAK architecture (Sensing, Logic, Action,…

---

## 📅 2026-07-27

### [One Hand Watches The Other: Dynamic Multi-Agent Cooperation for Sample-Efficient Bimanual Manipulation in Dynamic Environments](https://arxiv.org/abs/2607.22119v1)

- **arXiv**: `2607.22119v1`  |  **提交日期**: 2026-07-24
- **作者**: Jan Ole von Hartz, Abhinav Valada, Joschka Boedecker

Multi-stream robot manipulation policies achieve unparalleled sample efficiency and generalization by modeling actions relative to environmental reference frames. However, existing approaches typically assume these frames to be strictly exogenous. This causal assumption collapses in dynamic settings, such as when a single robot arm manipulates a moving object or when two arms coordinate, where each arm effectively becomes part of the dynamic environment of the other. We propose DynaMAC, a lightweight, policy-agnostic framework that resolves this causal limitation while preserving the sample…

---

## 📅 2026-07-24

### [AXIS: A Growable Community-Driven Data Engine for Scalable Robot Manipulation](https://arxiv.org/abs/2607.21588v1)

- **arXiv**: `2607.21588v1`  |  **提交日期**: 2026-07-23
- **作者**: Mengfei Zhao, Dihong Huang, Yikai Tang, Peihao Li, Mingxuan Yan, Ruiqi Zhuang et al.

Learning effective robot manipulation policies requires diverse, high-quality demonstrations, yet existing data pipelines are often difficult to scale because they rely on specialized hardware, centralized operators, or fixed task suites. We present AXIS, a growable community-driven data engine and benchmark for scalable robot learning, which enables browser-based teleoperation for large-scale demonstration collection, automatically generates and validates new manipulation tasks, and transforms community-collected demonstrations into training-ready data through automated success checking,…

---

### [TableVerse: A Large-scale Tabletop Dataset with Real-world Grounded Layouts for Generalizable Manipulation](https://arxiv.org/abs/2607.21017v1)

- **arXiv**: `2607.21017v1`  |  **提交日期**: 2026-07-23
- **作者**: Boyuan Wang, Yue Zhang, Xutao Xue, Xueyu Song, Yu Sun

The development of generalizable robotic manipulation policies is inherently bounded by the availability of large-scale, high-fidelity scene data. While recent automated synthesis methods attempt to bridge this gap via text-to-layout hallucination or simplified procedural generation, they frequently suffer from physical implausibility and fail to capture the complex, dense clutter of actual human environments. In this paper, we introduce TableVerse, a fully automated Real2Sim pipeline that shifts the paradigm from imaginative layout generation to deterministic reconstruction from…

---

### [HyWorldVLA: A Vision-Language-Action Model with Hybrid World Modeling for Autonomous Driving](https://arxiv.org/abs/2607.20988v1)

- **arXiv**: `2607.20988v1`  |  **提交日期**: 2026-07-23
- **作者**: Quanfu Yu, Xian Wu, Hao Xu, Liulong Ma

Vision-Language-Action (VLA) models augmented with world modeling represent a promising paradigm for end-to-end autonomous driving. While pixel-level future prediction enables fine-grained spatiotemporal reasoning, it compromises robustness in noisy driving scenarios. Conversely, latent-based world models alleviate this sensitivity but often incur limited interpretability and representational degradation due to absent pixel-level grounding. To reconcile this trade-off, we propose HyWorldVLA, a hybrid world-VLA framework that unifies pixel-level supervision and latent representation learning.…

---

## 📅 2026-07-23

### [LENS: LLM-guided Environment Simplification for Planning and Control in Clutter](https://arxiv.org/abs/2607.19633v1)

- **arXiv**: `2607.19633v1`  |  **提交日期**: 2026-07-22
- **作者**: Aileen Liao, Rachel Holladay, Dinesh Jayaraman, Michael Posa

Despite recent advances in general-purpose robotic manipulation, real-world multi-object clutter remains challenging to handle for today's prevalent approaches. The problem scales in complexity due to more objects and collisions, more unpredictable contact physics, distractors, and task ambiguity. Bridging this gap to real-world deployment requires effective scene abstractions; yet today, producing such abstractions requires extensive task-specific manual engineering, which does not scale. These abstractions are costly to generate and difficult to adjust or fine-tune. We instead propose a…

---

## 📅 2026-07-22

### [STeP: Signal Temporal Logic for Precise Specifications for Action Generation with Vision Language Models](https://arxiv.org/abs/2607.18580v1)

- **arXiv**: `2607.18580v1`  |  **提交日期**: 2026-07-20
- **作者**: Kasra Torshizi, Anukriti Singh, Sidharth Mathur, Khuzema Habib, Leo Du, Pratap Tokekar

Vision-language-action (VLA) models have shown impressive generalization, but often lack interpretability and can struggle to follow precise natural language instructions that encode spatial, temporal, and logical requirements. We propose a hierarchical framework that uses Signal Temporal Logic (STL) as a shared representation connecting high-level language understanding with low-level robot execution. A high-level policy leverages a VLM to decompose language instructions into high-level subtasks, generate STL specifications for each subtask, and choose a low-level policy for executing each…

---

## 📅 2026-07-21

### [Patch Policy: Efficient Embodied Control via Dense Visual Representations](https://arxiv.org/abs/2607.18236v1)

- **arXiv**: `2607.18236v1`  |  **提交日期**: 2026-07-20
- **作者**: Gaoyue Zhou, Zichen Jeff Cui, Ada Langford, Bowen Tan, Yann LeCun, Lerrel Pinto

Pretrained dense visual features from Vision Transformers (ViTs) are powerful yet have been underutilized in robot learning. Modern robot policies either compress each observation into a single global token, or rely on visual backbones trained from scratch, sacrificing both fine-grained spatial detail and the benefits of large-scale visual pre-training. While there exist policies that do operate on dense patch features like large vision-language-action models (VLAs), they tend to be heavy and slow, inheriting the full cost of a billion-parameter vision-language model (VLM) backbone. We close…

---

### [FM-VLA: Force-based Memory for Vision-Language-Action Models in Contact-Rich Manipulation](https://arxiv.org/abs/2607.18231v1)

- **arXiv**: `2607.18231v1`  |  **提交日期**: 2026-07-20
- **作者**: Ruicheng Li, Qixiu Li, Ruichun Ma, Yu Deng, Lin Luo, Zhiying Du et al.

Vision-language-action (VLA) models have achieved impressive generalization in robotic manipulation, and recent memory-augmented VLAs have relaxed the Markovian assumption by conditioning on past images or language summaries. Vision-based memory approaches address this by conditioning on sampled past image frames, but they are computationally expensive and fundamentally limited when temporal events are visually ambiguous, e.g., pushing a button multiple times with small movements. We propose FM-VLA, a VLA model with force-based memory, enabling temporal context reasoning for non-Markovian,…

---

### [Closing the Loop in Humanoid VLA: Persistent 3D Object Tokens for Verifiable Loco-Manipulation](https://arxiv.org/abs/2607.18016v1)

- **arXiv**: `2607.18016v1`  |  **提交日期**: 2026-07-20
- **作者**: Peng Ren, Haoyang Ge, Jiang Zhao, Cong Huang, Yukun Shi, Pei Chi et al.

Vision-language-action policies are a promising foundation for general robot control, but long-horizon humanoid loco-manipulation requires the robot to treat task objects as persistent physical entities across movement, contact, occlusion, and recovery. We study this problem as object-state divergence: the object state used to condition a whole-body action can differ from the state used to decide whether the action achieved the intended physical relation. We propose \emph{Persistent Object Tokenization} (POT), which maintains role-indexed 3D object records from RGB-D observations and converts…

---

### [Reasoning as a Double-Edged Sword: Architecture and Cross-Stage Robustness in Vision-Language-Action Models](https://arxiv.org/abs/2607.17786v1)

- **arXiv**: `2607.17786v1`  |  **提交日期**: 2026-07-20
- **作者**: Tuan Duong Trinh, Naveed Akhtar, Basim Azam

Does adding a reasoning step make a Vision-Language-Action (VLA) model more robust to perturbation? Intuitively, a policy that reasons before acting should absorb a perturbed input better than one that maps observations directly to actions. We test this premise head-on across three models that span the reasoning spectrum (no reasoning, a text chain-of-thought, and a latent iterative loop), perturbing each at the vision, reasoning, and action stages on LIBERO and SimplerEnv. Two questions organize the study: does the reasoning design shift robustness, and can the reasoning be read back at…

---

### [What Do They See? Interpreting Complex Road Scenarios Through the Eyes of Vision-Language-Action Models for Safe and Trustworthy Autonomous Vehicle Learning](https://arxiv.org/abs/2607.16938v1)

- **arXiv**: `2607.16938v1`  |  **提交日期**: 2026-07-18
- **作者**: Kalpana Panda, Wesley Maia, Vinti Agarwal, Ross Greer

End-to-end autonomous driving models are now able to navigate complex road scenarios, mapping raw sensor observations directly to observed paths for open-loop evaluation and often effective driving in closed-loop evaluation. Yet the internal logic of these safety-critical systems remains largely opaque, due to the complexity of traffic scenes. We propose a counterfactual ablation framework called Counterfactual Vision Action Analysis (CVAA) that systematically removes individual detected objects from front-camera images using photorealistic generative inpainting to prepare counterfactual sets…

---

### [PhyAgentOS: A Self-Evolving Operating System for Embodied Agents with Decoupled Cognitive Planning and Physical Execution](https://arxiv.org/abs/2607.16636v1)

- **arXiv**: `2607.16636v1`  |  **提交日期**: 2026-07-18
- **作者**: Yang Liu, Weixing Chen, Xinshuai Song, Tao Pu, Siwen Mo, Yongjie Bai et al.

Vision-language-action models, world models, and agentic planners each advance physical intelligence, yet their composition lacks a common execution abstraction, shared state, semantic verification, and persistent experience across heterogeneous embodiments. We present PhyAgentOS, a runtime foundation delivering scheduling, verification, memory, benchmarking, and safety as system-level services. Its Session-Centered Runtime treats a session, not an action, as the minimum unit of scheduling, compatibility preflight, supervised execution, evidence collection, and acceptance. To decouple…

---

## 📅 2026-07-20

### [JoyNexus: Service-Oriented Multi-Tenant Post-Training for VLA Models](https://arxiv.org/abs/2607.16074v1)

- **arXiv**: `2607.16074v1`  |  **提交日期**: 2026-07-17
- **作者**: Haoran Sun, Wentao Zhang, Junyang Hua, Hedan Yang, Yongjian Guo, Yifei Zhang et al.

The post-training of Vision-Language-Action (VLA) models is essential due to the diversity of simulators, robot embodiments, and task objectives. Existing compute services, whether offered as direct accelerator rental or batch-workload submission, typically allocate an exclusive set of GPU and CPU resources to a single tenant. While this paradigm maximizes client flexibility, it burdens users with infrastructure adaptation, and the fixed card-hour accounting model renders short or bursty workloads both expensive for tenants and inefficient for the service provider. To address these…

---

### [AC-VLA: Robust Out-of-Distribution Action Execution via Compositional Learning](https://arxiv.org/abs/2607.15714v1)

- **arXiv**: `2607.15714v1`  |  **提交日期**: 2026-07-17
- **作者**: Xiaojiang Peng, Kai Peng, Jie Lu, Zheng Lian, Zitong YU, Xiaobo Wang

Vision-Language-Action (VLA) models excel at end-to-end robotic manipulation but struggle with out-of-distribution (OOD) generalization when familiar sub-tasks are recombined in unseen configurations. We identify two mutually reinforcing failure modes: \emph{trajectory overfitting}, where models overfit to holistic trajectory patterns rather than compositional sub-skill semantics; and \emph{perceptual shortcut}, where action tokens over-rely on wrist-view textures at the expense of global spatial grounding. To address both, we introduce \textbf{AC-VLA}, a plug-and-play Action Compositional…

---

### [IMBench: A Benchmark for Intuitive Robotic Manipulation](https://arxiv.org/abs/2607.15641v1)

- **arXiv**: `2607.15641v1`  |  **提交日期**: 2026-07-17
- **作者**: Anurag Maurya, Sukhvansh Jain, Prajwal Avhad, Gautham Balachandran, Ziyi Zhou, Atharva Kshirsagar et al.

Humans combine reasoning and motor control to solve complex manipulation tasks under diverse constraints. They build an understanding of the physical world that helps them convert reasoning into actions and quickly adapt to new scenes, tasks, and rules. We refer to this capability as intuitive manipulation. Existing benchmarks fail to capture this integration: they evaluate physical reasoning in isolation from execution, or measure policy performance without requiring explicit reasoning. We introduce IMBENCH, a benchmark designed to evaluate intuitive manipulation as an integrated capability…

---

### [Think at 5 Hz, Act at 20 Hz: Asynchronous Fast-Slow Vision-Language-Action Inference for Closed-Loop Driving](https://arxiv.org/abs/2607.15621v1)

- **arXiv**: `2607.15621v1`  |  **提交日期**: 2026-07-17
- **作者**: Yun Li, Jiachen Gong, Simon Thompson, Ehsan Javanmardi, Qunli Zhang, Zifan Zeng et al.

Large language models bring instruction following and scene reasoning to end-to-end driving, but their inference latency collides with the control rate a vehicle requires. Existing closed-loop agents hide this gap by invoking the model on alternate simulation ticks and replaying the previous command in between, so half of all control outputs ignore the newest observations. We present a fast-slow architecture that removes this compromise. A frozen 7B vision-language backbone acts as the slow system, digesting navigation instructions and visual history at low frequency while exposing its…

---

## 📅 2026-07-17

### [RoboTTT: Context Scaling for Robot Policies](https://arxiv.org/abs/2607.15275v1)

- **arXiv**: `2607.15275v1`  |  **提交日期**: 2026-07-16
- **作者**: Yunfan Jiang, Yevgen Chebotar, Ruijie Zheng, Fengyuan Hu, Yunhao Ge, Jimmy Wu et al.

Recent robot foundation models operate with single-step or short-history visuomotor context. We introduce Test-Time-Training Robot Policies (RoboTTT), a robot model and training recipe that scale visuomotor context to 8K timesteps, three orders of magnitude beyond state-of-the-art policies, without growing inference latency. At this context length, we unlock new robot capabilities: one-shot in-context imitation from human video demonstrations, on-the-fly policy improvement, robustness to perturbations, and stronger performance on multi-stage, long-horizon tasks. We also observe, for the first…

---

### [Video = World + Event Stream](https://arxiv.org/abs/2607.15038v1)

- **arXiv**: `2607.15038v1`  |  **提交日期**: 2026-07-16
- **作者**: Lianghua Huang, Zhi-Fan Wu, Yupeng Shi, Wei Wang, Mengyang Feng, Cheng Yu et al.

We present Wan-Streamer v0.3, which reframes our native-streaming interaction model under a single organizing view: a video is a world plus an event stream. The world is the persistent context in which a video unfolds, including the environment, scene, subjects, ambient acoustic conditions, voice characteristics, and other relatively stable conditions. The event stream is everything that changes over time within that world, including scene or environmental changes, subject behavior, speech, and other sounds. This yields a general-purpose pretraining task over large amounts of real video:…

---

### [CosFly-VLA: A Spatially Aware Vision-Language-Action Model for UAV Tracking](https://arxiv.org/abs/2607.15004v1)

- **arXiv**: `2607.15004v1`  |  **提交日期**: 2026-07-16
- **作者**: Ruilong Ren, Songsheng Cheng, Yunpeng Zhou, Hanxuan Chen, Xiangyue Wang, Tianle Zeng et al.

Dynamic target tracking is essential for Unmanned Aerial Vehicles (UAVs) operating in complex urban environments, where both the target and the camera viewpoint change continuously. Existing Vision-Language-Action (VLA) policies can track visible targets effectively, but their performance often degrades when buildings, vegetation, or roadside objects block the line of sight. During sustained occlusion, a policy may lose the target state, execute actions toward an incorrect region, and amplify this error through subsequent observations until re-acquisition becomes impossible. To this end, we…

---

### [AeroAct: Action-Centered World-Action Models for Language-Conditioned Quadrotor Flight](https://arxiv.org/abs/2607.14997v1)

- **arXiv**: `2607.14997v1`  |  **提交日期**: 2026-07-16
- **作者**: Xinhong Zhang, Qiyuan Zhu, Yubo Huang, Haolin Chen, Runqing Wang, Yuhao Mo et al.

Language-conditioned quadrotor flight requires a policy to ground semantic goals, anticipate the visual consequences of ego-motion, and output control references that remain smooth and dynamically executable under rapidly changing first-person views. Existing aerial vision-language navigation and vision-language-action methods commonly use discrete actions, high-level waypoints, or instantaneous velocity commands, which provide limited supervision about how flight actions change future observations. We present AeroAct, an action-centered world-action model (WAM) for quadrotor navigation. To…

---

### [Towards Human-like Physical Intelligence: LifelongVision-Language-Action Learning for Robotic Manipulation](https://arxiv.org/abs/2607.14852v1)

- **arXiv**: `2607.14852v1`  |  **提交日期**: 2026-07-16
- **作者**: Yao He, Gan Sun, Wenqi Liang, Fazeng Li, Yang Cong

Similar to the natural capabilities of humans to sequentially learn new tasks, robots with Vision-Language-Action (VLA) models should possess lifelong learning ability to learn a new task when deployed in open-world environments. However, most recently proposed lifelong learning models aim to effectively learn the current task (plasticity) or maintain high accuracy on previous tasks (stability), while the plasticity-stability trade-off remains largely unsolved in robotic manipulation models. To address this fundamental challenge, we propose a cache-efficient lifelong Vision-Language-Action…

---

### [FoMoVLA: Bridging Visual Foresight and Motion Guidance for Vision-Language-Action Models](https://arxiv.org/abs/2607.14739v1)

- **arXiv**: `2607.14739v1`  |  **提交日期**: 2026-07-16
- **作者**: Wei Li, Peijin Jia, Yuan Ma, Xuefeng Jiang, Titong Jiang, Sheng Sun et al.

Vision-Language-Action (VLA) models have achieved impressive results in visuomotor policy learning, yet remain fundamentally reactive, mapping current observations and language to actions without explicit forward prediction of world dynamics. Existing visual foresight methods predict future visual states but lack explicit motion guidance: they show where to go but not how to get there. We argue that future feature prediction and sparse point tracking are naturally complementary: the former provides the goal state, while the latter captures the continuous motion path toward it. We propose…

---

### [Lights, Camera, Malfunction: When Illumination Robustness Leaves VLA Models Blind to Color](https://arxiv.org/abs/2607.14698v1)

- **arXiv**: `2607.14698v1`  |  **提交日期**: 2026-07-16
- **作者**: Marino Watanabe, Takami Sato, Kentaro Yoshioka

Vision-Language-Action (VLA) models have emerged as a powerful paradigm for general-purpose robot manipulation; however, their transition to real-world environments reveals vulnerabilities to minor environmental perturbations. We propose FLARE, an optimized physical spotlight attack framework that exploits these vulnerabilities via targeted illuminations, dropping baseline task success rates to zero without any access to model internals. While adversarial training is the standard countermeasure, we identify a critical and previously underestimated defensive pitfall: naive data augmentations…

---

### [Reflex: Real-Time VLA Control through Streaming Inference](https://arxiv.org/abs/2607.14695v1)

- **arXiv**: `2607.14695v1`  |  **提交日期**: 2026-07-16
- **作者**: Yuanchun Guo, Bingyan Liu

Flow matching Vision-Language-Action (VLA) models promise precise continuous control, but their iterative denoising nature introduces fundamental incompatibilities with real-time robotics: global timestep injection invalidates KV-caching, forcing a choice between slow $O(N^2)$ re-computation or mathematically incorrect cache reuse. We present \textbf{Reflex}, a framework that enables \textit{real-time streaming inference} for flow matching policies by exploiting the \textit{Timestep-Invariance Property} -- that perception encoders are functionally independent of the denoising loop. Reflex…

---

### [Representation-Aligned Tactile Grounding for Contact-Rich Robotic Manipulation](https://arxiv.org/abs/2607.14609v1)

- **arXiv**: `2607.14609v1`  |  **提交日期**: 2026-07-16
- **作者**: Ruilin Chen, Jingkai Jia, Tong Yang, Xinyu Zhou, Qiao Sun, Jiangwei Zhong et al.

Tactile-enhanced vision-language-action (VLA) policies have been introduced for contact-rich manipulation, where critical interaction states are often hidden from vision. Future tactile prediction is a promising way to use touch because it turns tactile outcomes into supervision for action-induced contact dynamics. Yet VLA policies contain representations with different roles, from perceptual encoding to motor prediction, making it unclear where this supervision should be applied. We study this as a representation-alignment problem. Through a linear probe analysis, we find that future tactile…

---

### [Active Real-World Factor-Based Evaluation for Generalist Robot Policies](https://arxiv.org/abs/2607.14439v1)

- **arXiv**: `2607.14439v1`  |  **提交日期**: 2026-07-16
- **作者**: Andrew Liao, Hanchen Cui, Karthik Desingh, Aryan Deshwal

Generalist robot manipulation policies trained on large, diverse datasets have shown remarkable promise across a wide range of tasks. However, rigorously evaluating these policies remains a fundamental challenge. Real-world performance depends on a large combinatorial space of task factors including object poses and camera viewpoints, making full, exhaustive evaluation intractable. Additionally, real hardware evaluation is slow and resource-intensive, so current practice is to use narrow test suites that can miss critical failure modes and misrepresent true deployment readiness. We propose an…

---

### [DiMaS: Distribution Matching for Steering Vision-Language-Action Models](https://arxiv.org/abs/2607.14280v1)

- **arXiv**: `2607.14280v1`  |  **提交日期**: 2026-07-15
- **作者**: Pegah Khayatan, Sara Meziane, Jayneel Parekh, Matthieu Cord

Flow-matching-based vision-language-action (VLA) models have emerged as powerful policies for robotic manipulation, yet a critical capability remains underexplored: fine-grained behavioral control, the ability to govern how a robot performs a task by intervening on its internal representations. Representation steering is a well-established interpretability tool for language and vision-language models, where behavioral features are typically encoded as linear directions, but we show that these classic methods fall short in VLAs. We propose DiMaS, a Distribution-Matching Steering strategy…

---

### [Never Too Late for Force: Accelerating VLA Post-Training with Reactive Force Injection](https://arxiv.org/abs/2607.14236v1)

- **arXiv**: `2607.14236v1`  |  **提交日期**: 2026-07-15
- **作者**: Yi Wang, Wendi Chen, Zimo Wen, Han Xue, Xueqi Li, Wenye Yu et al.

Pretrained vision-language-action (VLA) policies provide strong language-conditioned manipulation knowledge, but they remain largely vision-driven and can struggle once manipulation enters contact states where the scene is occluded, depth is ambiguous, or small force errors push execution off the offline demonstration distribution. We present LIFT (Late Reactive Injection of Force for VLA Post-Training), a force-aware post-training framework that adds contact reactivity to a pretrained VLA policy while preserving its general manipulation knowledge. LIFT grafts a reactive action expert beside…

---

### [VistaVLA: Geometry- and Semantic-Aware 3D Gaussian-Grounded VLA for Robotic Manipulation](https://arxiv.org/abs/2607.12356v2)

- **arXiv**: `2607.12356v2`  |  **提交日期**: 2026-07-14
- **作者**: Mohan Liu, Zhihao Gu, Xuanyu Chen, Haitian Zhang, Kaimin Mao, Yan Wu et al.

Vision-Language-Action (VLA) models have emerged as a powerful end-to-end paradigm for robotic manipulation by mapping language instructions and 2D visual inputs directly to actions. However, these models lack an explicit, scene-level 3D representation, limiting their ability to reason over spatial layouts and geometric constraints. While recent efforts incorporate explicit 3D cues, such as depth maps or point clouds, to improve geometric awareness, they primarily capture low-level structures and lack high-level semantic grounding in 3D space. In human cognition, interaction with the physical…

---

## 📅 2026-07-16

### [S-squared-VLA: Decoupling Semantic and Spatial Streams in Vision-Language-Action Models for Autonomous Driving](https://arxiv.org/abs/2607.13926v1)

- **arXiv**: `2607.13926v1`  |  **提交日期**: 2026-07-15
- **作者**: Jianguo Yu, Rukang Wang, Duanfeng Chu, Chen Wang, Renju Feng, Liping Lu

Vision-Language Models (VLMs) have demonstrated remarkable potential for high-level reasoning in autonomous driving, yet they fundamentally struggle to generate precise, low-level control actions. This limitation is rooted in a semantic-physical gap caused by the inherent mismatch between discrete language tokens and continuous trajectory planning. While Vision-Language-Action (VLA) architectures attempt to bridge this gap by unifying perception and control into a single policy, this entanglement creates a new bottleneck. Standard VLAs experience a severe spatial representation collapse,…

---

### [Learning Robust Execution in Robotic Manipulation with Agentic Reinforcement Learning](https://arxiv.org/abs/2607.13818v1)

- **arXiv**: `2607.13818v1`  |  **提交日期**: 2026-07-15
- **作者**: Xiaopeng Zhang, Yueyang Weng, Qi Liu, Yongjin Mu, Yanjie Li

Robotic manipulation poses fundamental challenges due to uncertainty, long-horizon execution, and compounding errors, which can easily destabilize execution and lead to task failure. Although recent vision-language-action (VLA) models exhibit strong generalization, they typically lack explicit mechanisms to assess execution stability and to recover when execution deviates from its nominal behavior. In this paper, we propose: (1) two complementary metrics to assess execution quality at runtime, and (2) an agentic reinforcement learning framework that learns to restore effective execution…

---

### [UESF-Bench: Benchmarking and Probing for Unified Embodied Seeking and Following](https://arxiv.org/abs/2607.13621v1)

- **arXiv**: `2607.13621v1`  |  **提交日期**: 2026-07-15
- **作者**: Kun Yu, Jianhua Yang, Yixiang Chen, Changwei Wang, Hongyuan Yu, Yan Huang et al.

Language-guided human following is an important capability for embodied agents, but existing benchmarks typically assume that the target person is visible at the start of an episode. This setting simplifies the problem and overlooks a more realistic requirement: an agent often needs to first find a language-described target and then persistently follow that target in a dynamic environment. While recent work has started to study human search, existing settings are typically evaluated in task-specific scenarios and often rely on stronger prior knowledge of the environment. Moreover, they…

---

### [Semantic Anchoring for Robotic Action Representations](https://arxiv.org/abs/2607.13597v1)

- **arXiv**: `2607.13597v1`  |  **提交日期**: 2026-07-15
- **作者**: Yuan Xu, Youheng Shi, Chengyang Li, Wentao Zhu, Yizhou Wang

Vision-Language-Action (VLA) models inherit rich semantic representations from pretrained Vision-Language Models, yet fine-tuning on limited robot demonstrations degrades this structure and undermines generalization. A fundamental question therefore arises: what constitutes a good action representation? Inspired by the mirror neuron theory's insight that observation and execution share an intention-level encoding, we examine whether a robot's action representations preserve the semantic structure captured by pretrained encoders. Systematic probing confirms that this structure erodes during…

---

### [Generalizable VLA Finetuning via Representation Anchoring and Language-Action Alignment](https://arxiv.org/abs/2607.13429v1)

- **arXiv**: `2607.13429v1`  |  **提交日期**: 2026-07-15
- **作者**: Dwip Dalal, Shivansh Patel, Chahit Jain, Jeonghwan Kim, Utkarsh Mishra, Alex Baratian et al.

Finetuning a pretrained vision-language model (VLM) on robot demonstrations via behavior cloning (BC) has become the standard recipe for vision-language-action (VLA) policies. However, BC finetuning progressively overwrites the pretrained representations that support visual and semantic generalization. Co-training on web image-text data, a common remedy, does not prevent this; it applies language and action losses to separate observations, leaving VLAs with language-action misalignment that standard manipulation benchmarks do not expose. We propose Anchor-Align, which augments BC with two…

---

## 📅 2026-07-15

### [ChunkFlow: Towards Continuity-Consistent Chunked Policy Learning](https://arxiv.org/abs/2607.12992v1)

- **arXiv**: `2607.12992v1`  |  **提交日期**: 2026-07-14
- **作者**: Zhao Yang, Yinan Shi, Mingyuan Yao, Wenyao Xue, Yawei Jueluo, Longjun Liu

Vision-language action (VLA) models increasingly adopt chunked action heads to satisfy real-time constraints; however, this introduces boundary jitter: overlapping regions between consecutive chunks often yield inconsistent predictions, degrading temporal coherence and the task success rate. Existing methods, such as inference-time blending, merely reweight mismatched proposals without correcting underlying errors, leading to residual accumulation under biased or noisy histories. We propose ChunkFlow, a seam-aware training-and-execution framework for chunked policies that aligns chunk…

---

### [ExToken: Structured Exploration for Efficient Vision-Language-Action Reinforcement Fine-tuning](https://arxiv.org/abs/2607.12931v1)

- **arXiv**: `2607.12931v1`  |  **提交日期**: 2026-07-14
- **作者**: Yilun Kong, Yunpeng Qing, Guozheng Ma, Haoyu Wang, Li Shen, Zhi Hou et al.

Reinforcement Learning (RL) has demonstrated significant potential for improving Vision-Language-Action (VLA) models on complex manipulation tasks. However, its practical scalability remains severely limited by the substantial cost of environmental interactions. In this work, we first investigate the exploration stagnation bottleneck in current VLA-RL frameworks and reveal that trajectory diversity is fundamentally more important to sample efficiency than the sheer quantity of collected rollouts. Motivated by these insights, we introduce RL Exploration Token (ExToken), a simple yet general…

---

### [Jetson-PI: Towards Onboard Real-Time Robot Control via Foresight-Aligned Asynchronous Inference](https://arxiv.org/abs/2607.12659v1)

- **arXiv**: `2607.12659v1`  |  **提交日期**: 2026-07-14
- **作者**: Zebin Yang, Qi Wang, Yunhe Wang, Xiurui Guo, Bo Yu, Shaoshan Liu et al.

Vision-Language-Action (VLA) models have achieved impressive performance on diverse embodied tasks. However, deploying VLA models on low-power onboard devices, such as the Jetson Orin, remains challenging due to their high computational complexity, which leads to substantial inference latency and low control frequency. Asynchronous inference can partially mask this latency by parallelizing action execution and subsequent inference, but it introduces two critical issues: perception-execution misalignment and long reaction time. In this paper, we propose Jetson-PI, a method for efficient VLA…

---

### [TrustVLA: Mechanism-Guided Inference-Time Defense Against Vision-Language-Action Backdoors](https://arxiv.org/abs/2607.12571v1)

- **arXiv**: `2607.12571v1`  |  **提交日期**: 2026-07-14
- **作者**: Pinhan Fu, Xianda Guo, Xuetao Li, Wenke Huang, Ruilin Wang, Weiheng Zhao et al.

Vision-Language-Action (VLA) models are deployed through pipelines that end users cannot audit, and a poisoned VLA can behave normally on clean observations while a small visual trigger redirects a long-horizon robot policy before any failure becomes observable. Existing vision or language defenses rarely explain what a triggered VLA representation looks like or how to recover behavior without retraining. We study this gap through two independently proposed VLA attacks from groups with distinct injection strategies, BadVLA and INFUSE; the latter persists after downstream clean adaptation.…

---

### [VistaVLA: Geometry- and Semantic-Aware 3D Gaussian-Grounded VLA for Robotic Manipulation](https://arxiv.org/abs/2607.12356v1)

- **arXiv**: `2607.12356v1`  |  **提交日期**: 2026-07-14
- **作者**: Mohan Liu, Zhihao Gu, Xuanyu Chen, Haitian Zhang, Kaimin Mao, Yan Wu et al.

Vision-Language-Action (VLA) models have emerged as a powerful end-to-end paradigm for robotic manipulation by mapping language instructions and 2D visual inputs directly to actions. However, these models lack an explicit, scene-level 3D representation, limiting their ability to reason over spatial layouts and geometric constraints. While recent efforts incorporate explicit 3D cues, such as depth maps or point clouds, to improve geometric awareness, they primarily capture low-level structures and lack high-level semantic grounding in 3D space. In human cognition, interaction with the physical…

---

### [Reducing Temporal Redundancy for Efficient Vision-Language-Action Inference](https://arxiv.org/abs/2607.12287v1)

- **arXiv**: `2607.12287v1`  |  **提交日期**: 2026-07-14
- **作者**: Yuzhou Wu, Yuxin Zheng, Muchun Niu, Yishan Yang, Tianhao Liu, hanwen kang et al.

Vision-Language-Action (VLA) models exhibit strong generalization for robotic manipulation, yet their high inference latency limits real time deployment. We identify two primary sources of temporal redundancy in existing VLA pipelines: repeated visual encoding of highly similar consecutive frames and multi step iterative sampling in diffusion based policies. To address this, we propose a system level acceleration strategy that reduces computation in both perception and action generation. On the perception side, we incrementally update only tokens corresponding to dynamic scene regions instead…

---

## 📅 2026-07-14

### [From World Action Models to Embodied Brains: A Roadmap for Open-World Physical Intelligence](https://arxiv.org/abs/2607.11689v1)

- **arXiv**: `2607.11689v1`  |  **提交日期**: 2026-07-13
- **作者**: Yuanzhi Liang, Xufeng Zhan, Haibin Huang, Chi Zhang, Xuelong Li

Artificial general intelligence ultimately requires agents that can reason and act in the physical world. Action models, vision-language-action policies, and world models have advanced this goal, while World Action Models (WAMs) are particularly promising because they connect candidate interventions with predicted consequences. However, progress remains fragmented: models use incompatible action spaces and prediction targets, datasets and tasks follow different conventions, and runtime systems expose limited interfaces for reuse and evaluation. We review the evolution toward WAMs and organize…

---

### [See like a Robot: Robot-Centric Pointmaps for Vision-Language-Action Models](https://arxiv.org/abs/2607.11498v1)

- **arXiv**: `2607.11498v1`  |  **提交日期**: 2026-07-13
- **作者**: Byungkun Lee, Dongyoon Hwang, Dongjin Kim, Hojoon Lee, Minho Park, Jaegul Choo

Vision-language-action (VLA) models predict robot actions from visual observations and language instructions. These actions are defined in the robot's own 3D coordinate frame, yet most VLAs observe the scene in the camera frame, creating a frame mismatch between where the scene is observed and where actions are defined. The mismatch is benign under a fixed viewpoint, where the policy can memorize a single observation-to-action mapping, but grows harder as large-scale datasets aggregate demonstrations across diverse camera setups and the policy must generalize this mapping across viewpoints.…

---

### [Towards Predictive, Aligned, and Scalable Robot Learning](https://arxiv.org/abs/2607.11270v1)

- **arXiv**: `2607.11270v1`  |  **提交日期**: 2026-07-13
- **作者**: Peijun Tang, Shangjin Xie, Baifu Huang, Binyan Sun, Haotian Yang, Kuncheng Luo et al.

Learning, at its core, extends beyond memorization to the ability to reason and solve novel problems by navigating a space of possibilities. We introduce Lumo-2, a latent world-action model that generates actions by reasoning over world dynamics in latent space. The learned latent world dynamics capture physically grounded visual transitions, naturally encoding future possibilities and providing a unified substrate for cross-modal alignment. This formulation enables predictive reasoning akin to world modelling while remaining lightweight and focused on physical dynamics relevant to control.…

---

### [VIA: Visual Interface Agent for Robot Control](https://arxiv.org/abs/2607.11119v1)

- **arXiv**: `2607.11119v1`  |  **提交日期**: 2026-07-13
- **作者**: Hengyuan Hu, Priya Sundaresan, Jensen Gao, Dorsa Sadigh

Robot manipulation is a complex task that requires visual understanding, physical reasoning, planning, and closed-loop control. General-purpose foundation models (FMs) have grown remarkably capable of some of these, especially vision and reasoning. To leverage this for generalist robot policies, current methods typically involve converting existing FMs into vision-language-action (VLA) models by fine-tuning on robot data to output low-level actions. However, VLAs are often orders of magnitude smaller than frontier FMs given the limited data and compute available for fine-tuning, which in turn…

---

### [Artificial Foveated Perception for Mitigating Shortcut Learning in Robotic Foundation Models](https://arxiv.org/abs/2607.10655v1)

- **arXiv**: `2607.10655v1`  |  **提交日期**: 2026-07-12
- **作者**: Xiatao Sun, Yuan Zhuang, Mateo Sanchez Lopez Negrete, Matei-Victor Coldea, Chen Liang, Haoyang Zhang et al.

Robotic foundation models have recently made substantial progress in multi-task capability, cross-embodiment transfer, and language-conditioned control. Yet robust deployment across diverse real-world settings remains difficult, in part because policies often fail to distinguish causally relevant visual structure from spurious scene-level correlations. We identify this failure mode as shortcut learning: the tendency to exploit predictive but non-causal correlations in the training distribution rather than the task-relevant visual evidence that determines successful action. Although shortcut…

---

### [SUREFlow: State-space Uncertainty-aware REsidual Flow Matching for Robust Robot Manipulation](https://arxiv.org/abs/2607.10504v1)

- **arXiv**: `2607.10504v1`  |  **提交日期**: 2026-07-11
- **作者**: Md Tanvir Islam, Sai Navaneet Peddapalli, Sangmoon Lee, Sangtae Ahn

Generative vision-language-action policies have advanced robot manipulation, but they often exhibit instability under noise, partial observability, and stochastic initial conditions. During extended rollouts, small velocity errors accumulate, degrading execution reliability. Existing diffusion and flow-based policies typically assume homoscedastic residuals and lack explicit uncertainty modeling within action generation, limiting robustness during iterative rollout. We propose SUREFlow, a state-space uncertainty-aware residual flow matching framework built on a Mamba backbone. The method…

---

### [ActiveFly-Bench: Aligning Embodied Question Answering with Vision-Language-Action for Aerial Embodied Perception](https://arxiv.org/abs/2607.10180v1)

- **arXiv**: `2607.10180v1`  |  **提交日期**: 2026-07-11
- **作者**: Weichen Zhang, Shiquan Yu, Yinan Zhu, Peizhi Tang, Shilong Ji, Zhiyuan Deng et al.

We introduce ActiveFly-Bench, the first benchmark to bridge cyberspace reasoning and physical-world interaction for UAV embodied perception. The benchmark decomposes active perception into three hierarchical tasks: Aerial Embodied Question Answering (Air-EQA), Observation Behavior Planning (OBP), and Fine-grained Language-guided UAV Control (FLUC), explicitly connecting high-level task understanding, behavior planning, and low-level control. The datasets are collected from both real-world and simulated outdoor environments for training and evaluation. We further develop ActiveFly, a…

---

### [On the Efficiency of LoRA Fine-Tuning for Vision-Language-Action Models in Industrial Robotic Manipulation](https://arxiv.org/abs/2607.10172v1)

- **arXiv**: `2607.10172v1`  |  **提交日期**: 2026-07-11
- **作者**: Finn Ferchau, Daniel Pommer, Cristian Axenie

Deploying billion-parameter Vision-Language-Action (VLA) models on industrial hardware requires fine-tuning to bridge the embodiment gap. Full Fine-Tuning (FFT) provides maximal plasticity but requires data centre-grade GPUs. We present a systematic study of Low-Rank Adaptation (LoRA) for $π_0$, a flow-matching VLA, evaluated on four precision assembly tasks with a UR5e robotic manipulator. Across a sweep of LoRA ranks (r=8 to 256), allocation strategies, and component-freezing ablations, we find no statistically significant advantage of FFT over certain LoRA configurations. Performance…

---

## 📅 2026-07-13

### [B-spline Policy: Accelerating Manipulation Policies via B-spline Action Representations](https://arxiv.org/abs/2607.09648v1)

- **arXiv**: `2607.09648v1`  |  **提交日期**: 2026-07-10
- **作者**: Xiaoshen Han, Haoyu Xiong, Haonan Chen, Chaoqi Liu, Antonio Torralba, Yuke Zhu et al.

In this work, we present B-spline Policy (BSP), an action representation designed for accelerating robot manipulation policies. Rather than predicting discrete-time action chunks, BSP parameterizes actions as continuous B-spline curves defined by a set of knots and control points. This representation yields smooth, time-continuous trajectories that can be temporally scaled and executed by low-level controllers at higher frequencies and speeds. We show that B-spline-parameterized actions can be seamlessly integrated into standard policy learning pipelines by directly predicting B-spline…

---

### [PAC-ACT: Post-training Actor-Critic for Action Chunking Transformers](https://arxiv.org/abs/2607.09590v1)

- **arXiv**: `2607.09590v1`  |  **提交日期**: 2026-07-10
- **作者**: Yujie Pang, Zudong Li

Precision industrial contact manipulation requires reliable robot policies under pose perturbations and contact-force constraints. Vision-language-action models offer broad generalization but often introduce high inference latency and GPU-memory cost, while vision-action chunking policies are more suitable for real-time industrial control. However, these policies are usually trained by behavior cloning and suffer from distribution shift in contact-rich tasks. This paper proposes PAC-ACT, a reinforcement-learning post-training framework for pretrained Action Chunking Transformer policies.…

---

### [Can the Cloud Drive? Infrastructure Feasibility of Offloading Autonomous Driving Across 5G and 6G](https://arxiv.org/abs/2607.09045v1)

- **arXiv**: `2607.09045v1`  |  **提交日期**: 2026-07-10
- **作者**: Pouya Parsa, Kawon Han, Seongjin Choi

Frontier autonomous-driving models -- especially vision-language-action (VLA) models, whose forward pass approaches $\sim$60~TFLOPs -- are outgrowing economical onboard deployment, since peak hardware sits idle most of the day. Cloud inference can instead share GPUs across active vehicles, but the vehicle must upload through a capacity-limited uplink, reach a GPU without queueing, and return a decision within the closed-loop budget. This paper asks: can the cloud drive? We answer with an analytical framework coupling communication limits, a roofline GPU service model, stochastic latency, and…

---

### [Learning More from Less: Reinforcement Learning from Hindsight](https://arxiv.org/abs/2607.09042v1)

- **arXiv**: `2607.09042v1`  |  **提交日期**: 2026-07-10
- **作者**: Iris Xu, Sunshine Jiang, John Marangola, Nitish Dashora, Richard Li, Thomas Liu et al.

Reinforcement learning (RL) is increasingly used to post-train vision-language-action (VLA) models, but every update consumes robot rollouts that are slow and costly to collect, making sample efficiency a central concern. Manipulation tasks typically provide only sparse rewards, so a weak policy fails almost every rollout early in training and has little to learn from, even when those failures execute coherent behavior. Such a failure, however, is a success at a different task. We present Learning from Hindsight (LfH), which brings hindsight relabeling to RL post-training of VLAs by scoring…

---

## 📅 2026-07-10

### [FabriVLA: A Lightweight Vision-Language-Action Model for Precise Multi-Task Manipulation](https://arxiv.org/abs/2607.08575v1)

- **arXiv**: `2607.08575v1`  |  **提交日期**: 2026-07-09
- **作者**: Shiyuan Yang, Borong Zhang, Jizheng Zhang, Zhijia Tao, Junfei Guo, Donglai Ran et al.

We present FabriVLA, a lightweight Vision-Language-Action model for Precise Multi-Task Manipulation. FabriVLA combines an InternVL3.5 vision-language backbone with a flow-matching action head featuring gated self-attention across action tokens and shallow VLM layer fusion for enriched spatial context. The model is trained via single stage joint optimization from a pretrained VLM and randomly initialized action head. On the Meta-World MT50 benchmark spanning 50 diverse manipulation tasks, FabriVLA achieves a tier-average success rate of 90.0%, demonstrating that a compact VLA built on a 1B…

---

### [Harness VLA: Steering Frozen VLAs into Reliable Manipulation Primitives via Memory-Guided Agents](https://arxiv.org/abs/2607.08448v1)

- **arXiv**: `2607.08448v1`  |  **提交日期**: 2026-07-09
- **作者**: Yixian Zhang, Huanming Zhang, Feng Gao, Xiao Li, Zhihao Liu, Chunyang Zhu et al.

Language-conditioned manipulation requires both precise contact-rich control and robust reasoning over language, scenes, and long horizons. End-to-end Vision-Language-Action (VLA) models provide strong local visuomotor skills, but they are trained on in-distribution task trajectories and often fail under deployment perturbations such as semantic retargeting, goal re-binding, spatial-layout shifts, and unstable local contacts. LLM coding agents provide complementary semantic and compositional reasoning, but purely analytic primitives struggle with irregular grasping, constrained placement, and…

---

### [WCog-VLA: A Dual-Level World-Cognitive Vision-Language-Action Model for End-to-End Autonomous Driving](https://arxiv.org/abs/2607.08375v1)

- **arXiv**: `2607.08375v1`  |  **提交日期**: 2026-07-09
- **作者**: Xuerun Yan, Zhexi Lian, Nuoheng Zhang, Shiyu Fang, Haoran Wang, Chen Lv et al.

Vision-Language-Action (VLA) models have advanced end-to-end autonomous driving. However, existing methods either lack comprehensive world cognition or suffer from fragmented world foresight, inherently confining these models to reactive driving. To address this limitation, we propose WCog-VLA, a novel dual-level World-Cognitive VLA framework that successfully bridges semantic world forecasting with generative world evolution to achieve proactive autonomous driving. At the semantic level, WCog-VLA unifies world cognition and reasoning by incorporating 3D spatial perception and injecting agent…

---

### [TFP: Temporally Conditioned Memory-Fusion Policies for Visuomotor Learning](https://arxiv.org/abs/2607.08283v1)

- **arXiv**: `2607.08283v1`  |  **提交日期**: 2026-07-09
- **作者**: Yushen Liang, Yue Peng, Baosheng Jin, Tianluo Zhang, Xinyu Zhang, Shuyi Zhou et al.

Vision--Language--Action (VLA) policies such as $π_{0.5}$ and OpenVLA perform well on many manipulation tasks, but they are often reactive: the next action is predicted from the current observation, instruction, and proprioceptive state. This assumption breaks down in stage-dependent manipulation, where visually similar states may require different actions depending on latent task progress and previous interaction outcomes. We argue that such tasks require not only memory, but dynamics-aware belief updates: the policy should preserve task progress during stable or occluded phases and revise…

---

### [LEEVLA: Seeing What Matters in Latent Environment Evolution for Vision-Language-Action](https://arxiv.org/abs/2607.08182v1)

- **arXiv**: `2607.08182v1`  |  **提交日期**: 2026-07-09
- **作者**: Qi Lyu, Baicheng Liu, Xudong Wang, Jiahua Dong, Lianqing Liu, Zhi Han

Vision-language-action (VLA) models aim to map multimodal inputs to robot actions. However, most existing approaches struggle to cover complex dynamic scenarios due to treating all visual tokens uniformly and reasoning with human-selected factors, which lack mechanisms to emphasize task-critical evidence and ignore underlying factors. To address this issue, we propose LEEVLA, a VLA architecture for seeing what matters in Latent Environment Evolution that explicitly guides the model toward informative regions while preserving the structured evolution of latent world representations. To…

---

### [Post-Training in End-to-End Autonomous Driving](https://arxiv.org/abs/2607.08072v1)

- **arXiv**: `2607.08072v1`  |  **提交日期**: 2026-07-09
- **作者**: Ruining Yang, Muxing Wang, Yixiao Chen, Tongfei Guo, Yi Xu, Can Cui et al.

End-to-end models that map multimodal inputs directly to future trajectories/maneuvers have emerged as an increasingly prominent research paradigm in autonomous driving. This class of models includes both Vision-Language-Action models and trajectory-generative planners. Unlike classic machine learning applications, autonomous vehicles operate in safety-critical and interaction-intensive environments where traditional open-loop imitation of expert demonstrations is not sufficient to ensure reliability. In particular, small execution errors can accumulate over time, while recovery behaviors are…

---

### [TouchWorld: A Predictive and Reactive Tactile Foundation Model for Dexterous Manipulation](https://arxiv.org/abs/2607.07287v2)

- **arXiv**: `2607.07287v2`  |  **提交日期**: 2026-07-08
- **作者**: Jianyi Zhou, Feiyang Hong, Yunhao Li, Yicheng Zhao, Yongjue Cen, Zirui Liu et al.

Dexterous manipulation in everyday environments requires both anticipation and reaction: a robot must predict how contact should evolve while rapidly correcting local errors caused by slip, misalignment, unstable grasping, or force mismatch. Vision and language provide semantic and geometric guidance, but they cannot reliably reveal hidden contact states such as force, slip, and contact stability. Although tactile sensing exposes these physical cues, most existing policies treat touch as a low-frequency observation stream within a monolithic action model, coupling slow task reasoning, action…

---

### [Pelican-VLA 0.5: Attending Before Acting Benefits Generalization](https://arxiv.org/abs/2607.06655v2)

- **arXiv**: `2607.06655v2`  |  **提交日期**: 2026-07-07
- **作者**: Zeyuan Ding, Wenhai Liu, Yang Xu, Jiayu Hu, Yinda Chen, Yi Zhang et al.

In this report, we present Pelican-VLA 0.5, a unified VLA model that integrates vision-language understanding, future-frame generation, and action prediction within a single architecture. Pelican-VLA 0.5 achieves attention-level generalization: without object annotations, segmentation masks, attention supervision, or task-specific fine-tuning, its action pathway already focuses on the manipulation-relevant object and contact region. This behavior persists across unseen scenes and unseen robot embodiments, and is substantially stronger than in other open-source VLA baselines. We verify that…

---

## 📅 2026-07-09

### [Dual Latent Memory in Vision-Language-Action Models for Robotic Manipulation](https://arxiv.org/abs/2607.07608v1)

- **arXiv**: `2607.07608v1`  |  **提交日期**: 2026-07-08
- **作者**: Hongyu Qu, Jianzhe Gao, Xiaobin Hu, Shaohuan Yang, Xinlei Yu, Rui Yan et al.

Mainstream Vision-Language-Action (VLA) models predict actions primarily from the current observation under a Markovian assumption, thus struggling with long-horizon, temporally dependent tasks. Existing memory-augmented VLAs either expand the observation window or retrieve history from the memory bank as auxiliary policy-side context. However, they leave memory outside the native latent embedding space of VLA reasoning, preventing historical experience from being fluidly interleaved with multimodal reasoning and action formation. To this end, we introduce LaMem-VLA, a latent-memory-native…

---

### [Smooth Operator: A Real-Time Sampling-Based Algorithm for Kinematic Hand Retargeting](https://arxiv.org/abs/2607.07491v1)

- **arXiv**: `2607.07491v1`  |  **提交日期**: 2026-07-08
- **作者**: Robert Jomar Malate, Erik Bauer, Norica Bacuieti, Stefanos Charalambous, Elvis Nava, Robert K. Katzschmann et al.

Advances in learning-based robotic manipulation, such as Vision-Language-Action (VLA) models and Video Action Models (VAMs), heavily rely on high-quality teleoperation data. Their capabilities are strictly upper-bounded by the quality of the underlying human demonstrations. Current gradient-based retargeting algorithms often converge to different local minima, resulting in jitter that affects data quality and teleoperation experience. To address this, we introduce the Sampling-Based Retargeter (SBR), a novel gradient-free retargeting method drawn from the rich literature of sampling-based…

---

### [Multi-Agent Robotic Control with Onboard Vision-Language Models](https://arxiv.org/abs/2607.07403v1)

- **arXiv**: `2607.07403v1`  |  **提交日期**: 2026-07-08
- **作者**: Kajetan Rachwał, Maciej Majek, Bartłomiej Boczek, Jakub Matejczyk, Dominik Matejkowski, Adam Dąbrowski et al.

Vision Language Models (VLMs) and Vision Language Action (VLA) models have shown promise in robotic control. Yet, they face significant challenges regarding explainability, generalization, and compute requirements. This paper presents a Multi-Agent System (MAS) architecture that addresses these limitations by deploying specialized agents on onboard hardware - eliminating dependence on external compute. The system controls a multi-purpose autonomous mobile manipulator in a simulated industrial warehouse, fulfilling five task categories: safety inspection, warehouse maintenance, warehouse…

---

### [TouchWorld: A Predictive and Reactive Tactile Foundation Model for Dexterous Manipulation](https://arxiv.org/abs/2607.07287v1)

- **arXiv**: `2607.07287v1`  |  **提交日期**: 2026-07-08
- **作者**: Jianyi Zhou, Feiyang Hong, Yunhao Li, Yicheng Zhao, Yongjue Cen, Zirui Liu et al.

Dexterous manipulation in everyday environments requires both anticipation and reaction: a robot must predict how contact should evolve while rapidly correcting local errors caused by slip, misalignment, unstable grasping, or force mismatch. Vision and language provide semantic and geometric guidance, but they cannot reliably reveal hidden contact states such as force, slip, and contact stability. Although tactile sensing exposes these physical cues, most existing policies treat touch as a low-frequency observation stream within a monolithic action model, coupling slow task reasoning, action…

---

### [Vision Language Action (VLA) Models for Unmanned Aerial Robotics and Bimanual Manipulation: A Review](https://arxiv.org/abs/2607.06706v1)

- **arXiv**: `2607.06706v1`  |  **提交日期**: 2026-07-07
- **作者**: Inkyu Sa, Chanoh Park, Hea-Min Lee, Donghee Noh, Ho Seok Ahn

Vision Language Action (VLA) models unify visual perception, natural-language understanding, and action generation within a single foundation model, allowing a robot to follow instructions such as fold the towel or fly to the red building directly from camera images. Because VLAs inherit world knowledge from internet-scale pre-training, they have become the dominant framework for learning-based manipulation, with bimanual coordination serving as the most demanding testbed: two arms with 7 degrees of freedom each must move in concert to fold, assemble, and reorient objects. Unmanned aerial…

---

### [NativeMEM: Native Memory Compression for Long-Horizon Robotic Manipulation](https://arxiv.org/abs/2607.06678v1)

- **arXiv**: `2607.06678v1`  |  **提交日期**: 2026-07-07
- **作者**: Ziye Wang, Modi Shi, Chaojun Ni, Jiazhi Yang, Mengdi Li, Zhizhong Su et al.

How can pretrained Vision-Language-Action (VLA) models retain long-horizon visual histories with high-frequency updates without sacrificing efficiency? Existing approaches rely on external memory management, which restrains either the memory horizon or the reactiveness of pretrained policies. To this end, we present NativeMEM, a VLA policy that features long-term and real-time updated memory. At its core is an efficient memory encoding scheme, Native Memory Compression, which repurposes the VLA's own vision encoder to compress each historical frame from each camera view into a single token.…

---

### [Pelican-VLA 0.5: Attending Before Acting Benefits Generalization](https://arxiv.org/abs/2607.06655v1)

- **arXiv**: `2607.06655v1`  |  **提交日期**: 2026-07-07
- **作者**: Zeyuan Ding, Wenhai Liu, Yang Xu, Jiayu Hu, Yinda Chen, Yi Zhang et al.

In this report, we present Pelican-VLA 0.5, a unified VLA model that integrates vision-language understanding, future-frame generation, and action prediction within a single architecture. Pelican-VLA 0.5 achieves attention-level generalization: without object annotations, segmentation masks, attention supervision, or task-specific fine-tuning, its action pathway already focuses on the instruction-relevant object and contact region. This behavior persists across unseen scenes and unseen robot embodiments, and is substantially stronger than in other open-source VLA baselines. We verify that…

---

## 📅 2026-07-08

### [Lift3D-VLA: Lifting VLA Models to 3D Geometry and Dynamics-Aware Manipulation](https://arxiv.org/abs/2607.06564v1)

- **arXiv**: `2607.06564v1`  |  **提交日期**: 2026-07-07
- **作者**: Jiaming Liu, Qingpo Wuwu, Nuowei Han, Hao Chen, Zhuoyang Liu, Fan Fei et al.

Recently, Vision-Language-Action (VLA) models have demonstrated strong generalization across diverse tasks. However, effective robotic manipulation in physical environments fundamentally requires geometric understanding and spatial reasoning. While some VLA approaches attempt to incorporate 3D information, they are constrained by limited data availability and geometric information loss in current 3D encoding pipelines, and fail to jointly capture 3D geometry and temporally structured actions in dynamic environments. To address these limitations, we introduce Lift3D-VLA, a unified VLA…

---

### [SIEVE: Structure-Aware Data Selection for Imitation Learning with VLA Models](https://arxiv.org/abs/2607.06442v1)

- **arXiv**: `2607.06442v1`  |  **提交日期**: 2026-07-07
- **作者**: Changti Wu, Bin Yu, Zhaolong Shen, Shijie Lian, Xiaopeng Lin, Cong Huang et al.

Vision-Language-Action (VLA) models are typically trained by imitation learning on large-scale robot demonstration datasets, but more data does not necessarily yield better policies due to redundancy, noise, and uneven coverage. Existing data selection methods often assess demonstrations at either the trajectory or state-action level, missing the reusable structures that compose long-horizon behaviors. In this paper, we propose SIEVE, a structure-aware data selection method for VLA imitation learning. SIEVE views demonstrations as compositions of reusable primitives and transition interfaces.…

---

### [From Foundation to Application: Improving VLA Models in Practice](https://arxiv.org/abs/2607.06403v1)

- **arXiv**: `2607.06403v1`  |  **提交日期**: 2026-07-07
- **作者**: Wei Wu, Fangjing Wang, Fan Lu, He Sun, Shi Liu, Yunnan Wang et al.

Despite recent progress of VLA foundation models, the disparity between laboratory conditions and real-world applications continues to impede their practical implementation. To bridge this gap, we present LingBot-VLA 2.0, which advances LingBot-VLA through improvements in three functional domains. (1) Generalization across tasks and embodiments. Compared to the previous version, we revamp the data processing pipeline and curate around 60,000 hours of data for pretraining, including 50,000 hours of robot trajectories spanning 20 robot configurations and 10,000 hours of egocentric human videos.…

---

### [Training-Free Acceleration for Vision-Language-Action Models with Action Caching and Refinement](https://arxiv.org/abs/2607.06370v1)

- **arXiv**: `2607.06370v1`  |  **提交日期**: 2026-07-07
- **作者**: Ryuji Oi, Hikari Otsuka, Kosuke Matsushima, Yuki Ichikawa, Masato Motomura, Tatsuya Kaneko et al.

Vision-Language-Action (VLA) models have emerged as a promising approach for generalizable robotic manipulations. In particular, flow matching-based VLA models have shown remarkable success due to their capability to generate precise and smooth action sequences and capture multimodal distributions. However, the iterative denoising process in the action head acts as a major computational bottleneck, posing a critical challenge for real-time deployment. To address this challenge, we propose ActionCache, a plug-and-play external cache that opportunistically reuses past intermediate actions to…

---

### [Optimal Transport Q-Learning for Flow Policy Steering and Acceleration](https://arxiv.org/abs/2607.06262v1)

- **arXiv**: `2607.06262v1`  |  **提交日期**: 2026-07-07
- **作者**: Andreas Sochopoulos, Esmeralda S. Whitammer, Nikolaos Tsagkas, João Moura, Michael Gienger, Sethu Vijayakumar

Diffusion and flow policies have recently demonstrated remarkable performance in robotic applications by accurately capturing multimodal robot trajectory distributions, especially in the context of vision language action (VLA) models. However, high quality policy performance also requires fast inference and high quality demonstrations, which are often hard to get. Lack of these leads to suboptimal policy behaviors and failure under distribution shifts. In this work we address the problem of fine-tuning and accelerating suboptimal flow-based policies using the robot's experience through RL…

---

### [Diagnosing Semantic Handoff Failures in Agent-Orchestrated Vision-Language-Action Skill Composition](https://arxiv.org/abs/2607.06256v1)

- **arXiv**: `2607.06256v1`  |  **提交日期**: 2026-07-07
- **作者**: Ke Rui, Yushen Zuo, Jiawei Wang, Haoran Jia, Jinming Ma, Weitao Zhou et al.

Long-horizon household tasks require robots to compose many language-conditioned skills, yet the boundary between consecutive skills is rarely explicit. A skill may satisfy its own postcondition while leaving the robot, objects, or camera views in a state from which the next skill cannot reliably start. We study this semantic handoff problem in BEHAVIOR-1K through an agent-orchestrated vision-language-action execution harness. The harness invokes $π_{0.5}$-based skill checkpoints trained from cleaned BEHAVIOR-1K demonstrations, assigns each skill typed arguments and a step budget, and uses…

---

## 📅 2026-07-07

### [From Fixed to Free Cameras: Calibration-Free View-Robust Vision-Language-Action Model](https://arxiv.org/abs/2607.05396v1)

- **arXiv**: `2607.05396v1`  |  **提交日期**: 2026-07-06
- **作者**: Wenhao Li, Xueying Jiang, Quanhao Qian, Deli Zhao, Shijian Lu, Gongjie Zhang et al.

Real-world robot deployment rarely maintains the training-stage camera setup, where cameras often experience repositioning or remounting depending on actual scenarios. Existing view-robust Vision-Language-Action (VLA) policies tolerate such camera variations only when the camera extrinsics are explicitly provided, making them fragile and hard to use especially when view robustness is critical. We argue that the policy should not be told where the camera is, but rather figure it out by itself. To this end, we introduce Camera-Centric VLA (CamVLA), a new VLA model that decouples manipulation…

---

### [Cortex: A Bidirectionally Aligned Embodied Agent Framework for Long-horizon Manipulation](https://arxiv.org/abs/2607.05377v1)

- **arXiv**: `2607.05377v1`  |  **提交日期**: 2026-07-06
- **作者**: Jiaqi Peng, Xiqian Yu, Delin Feng, Yuqiang Yang, Wenzhe Cai, Jing Xiong et al.

While recent Vision-Language-Action (VLA) models show promise toward generalist manipulation policies, they struggle with long-horizon tasks due to their Markovian nature-relying solely on current observations. Hierarchical dual-system methods address this but suffer from a gap between high-level planning semantics and low-level execution kinematics. We introduce Cortex, a bidirectionally aligned embodied agent framework with a customized planning interface that conveys executable and tractable subtask plans from high-level VLM to low-level VLA. Specifically, we standardize manipulation…

---

### [Green for Go, Red for No: Visual Grounding via Semantic Segmentation for VLA Navigation Policies](https://arxiv.org/abs/2607.05122v1)

- **arXiv**: `2607.05122v1`  |  **提交日期**: 2026-07-06
- **作者**: Adrian Szvoren, Dimitrios Kanoulas, Nilufer Tuptuk

Vision-language-action (VLA) models enable robot navigation from natural language and visual goals, but remain susceptible to perceptual distractions and ambiguous scene interpretations. This paper presents the first empirical evaluation of visual grounding for VLA navigation policies. We propose a real-time segmentation-based grounding method that highlights traversable areas in green and non-traversable areas in red using SegFormer. Two variants are evaluated: observation-only segmentation and joint observation-goal augmentation. Using OmniVLA on the Grand Tour dataset, we show that visual…

---

### [DSWAM: A Dual-System World Action Foundation Model for Fine-Grained Robot Manipulation](https://arxiv.org/abs/2607.04927v1)

- **arXiv**: `2607.04927v1`  |  **提交日期**: 2026-07-06
- **作者**: Jian Zhu, Jianjun Zhang, Taiyi Su, Tianbin Liu, Zhangyuan Wang, Kai Xie et al.

World Action Models (WAMs) provide a promising alternative to Vision-Language-Action (VLA) policies by using video-based world modeling as dense supervision for robot action learning. Existing WAMs excel at physically grounded execution, but typically lack the explicit language-level planning interface in VLM-based VLAs for decomposing coarse instructions. Such decomposition becomes important when household tasks involve complex multi-step goals, where coarse user commands need to be converted into sequences of fine-grained executable subtasks. Meanwhile, the field still lacks a fair…

---

### [PRISM: Personalized Robotic Dataset Generation via Image-based Scene and Motion Synthesis](https://arxiv.org/abs/2607.04880v1)

- **arXiv**: `2607.04880v1`  |  **提交日期**: 2026-07-06
- **作者**: Dogyu Ko, Haneul Kim, Chanyoung Yeo, Dowoon Lee, Taeho Park, Hyoseok Hwang

Recent advances in large-scale pretrained vision-language-action models have improved robot policy learning, but directly deploying such policies in user-specific environments remains challenging due to limited generalization, which inevitably requires collecting a dataset tailored to the target environment. Teleoperation yields well-aligned data but is costly and difficult to scale, whereas simulation scales easily but struggles to resemble the target environment and generate task-specific trajectories. To meet both simultaneously, we propose PRISM, an end-to-end pipeline that generates…

---

### [CAC-VLA: Context-Gated Action Conditioning for Vision-Language-Action Models](https://arxiv.org/abs/2607.04816v1)

- **arXiv**: `2607.04816v1`  |  **提交日期**: 2026-07-06
- **作者**: Yifu Xiong, Wenhao Yu, Jiaxuan Lin, Bojun Zou, Jiahao Li, Lu Zhang et al.

Vision-Language-Action (VLA) models have become a promising paradigm for generalist robot manipulation, where visual-language representations are used to condition continuous action generation. However, these representations are not explicitly optimized for action conditioning, leaving the action expert to bridge the gap between multimodal understanding and precise motor control. Recent action-reasoning methods introduce additional modules to generate explicit action plans or action-space reasoning signals, demonstrating the benefit of action-level guidance but often requiring separate…

---

### [Do Vision-Language-Action Models Mean What They Say? On the Role of Faithfulness in Embodied Reasoning](https://arxiv.org/abs/2607.04681v1)

- **arXiv**: `2607.04681v1`  |  **提交日期**: 2026-07-06
- **作者**: Matthew Foutter, Matteo Cercola, Lena Wild, Yunshan Wang, Michelle Li, Daniele Gammelli et al.

Embodied Chain-of-Thought has emerged as a promising mechanism to enhance robot decision-making and interpretability in black-box Vision-Language Action (VLA) models. However, whether this verbalized Chain-of-Thought truthfully reflects the policy's underlying decision process remains poorly understood. We distinguish between functional reasoning, in which reasoning improves task performance, and faithful reasoning, in which reasoning truly reflects the policy's internal decision process. We argue that SoTA alignment strategies offer a necessary but insufficient notion of faithfulness,…

---

### [PixelPilot: Scalable Vision-Language-Action Models for End-to-End Autonomous Driving](https://arxiv.org/abs/2607.04637v1)

- **arXiv**: `2607.04637v1`  |  **提交日期**: 2026-07-06
- **作者**: Pin Tang, Guoqing Wang, Xiangxuan Ren, Zhongdao Wang, Guodongfang Zhao,  Bailan et al.

Vision-Language-Action Models (VLAs), which leverage the advanced reasoning capabilities of Vision-Language Models (VLMs), show promising generalization in complex autonomous driving scenarios. Existing VLAs typically predict and optimize 3D trajectories from 2D images. While intuitive, this 2D-to-3D prediction is inherently entangled with camera parameters, leading to limited data scalability across heterogeneous driving datasets. Moreover, directly optimizing in 3D space induces severe convergence to trivial solutions, where VLAs rely on ego-status rather than visual scene understanding. To…

---

### [SEAM: Smooth Execution of Action-Chunked Motion for Vision-Language-Action Policies](https://arxiv.org/abs/2607.04609v1)

- **arXiv**: `2607.04609v1`  |  **提交日期**: 2026-07-06
- **作者**: Dijia Zhan, Xuemiao Xu, Jinyi Li, Jie Tang

Vision-Language-Action (VLA) policies that execute fixed-length action chunks can exhibit multimodal bifurcation: a cross-chunk inconsistency in which adjacent chunks generated from independent Gaussian latents can converge to incompatible trajectory modes, producing abrupt discontinuities at chunk boundaries. Existing remedies either require backpropagation through the policy at each denoising step, rely on rejection sampling, or require retraining, each trading computational cost or task reliability for smoother transitions. We propose SEAM (Smooth Execution of Action-Chunked Motion), a…

---

### [Simple-to-Complex Structured Demonstrations for Vision-Language-Action Learning](https://arxiv.org/abs/2607.04591v1)

- **arXiv**: `2607.04591v1`  |  **提交日期**: 2026-07-06
- **作者**: Xinchuan Qiu, Yi Yu

Vision-Language-Action (VLA) models have demonstrated strong capabilities in robotic manipulation by integrating visual perception, language understanding, and robot action generation. Existing research has primarily focused on improving model architectures, training strategies, and dataset scale, while little attention has been paid to how demonstrations are collected and organized. We identify demonstration organization as a fundamental yet overlooked aspect of imitation learning, as it directly affects policy learning efficiency, training stability, and policy generalization. To address…

---

### [VLA Grounder: Language-Conditioning Space Optimization for Black-Box VLA Models](https://arxiv.org/abs/2607.04517v1)

- **arXiv**: `2607.04517v1`  |  **提交日期**: 2026-07-05
- **作者**: Damir Shodiev, Aleksei Staroverov, Nikita Kachaev, Alexey K. Kovalev, Aleksandr I. Panov

Vision-Language-Action (VLA) models are commonly treated as end-to-end action policies conditioned on natural-language task descriptions. In practice, however, their behavior often depends sharply on how the instruction is phrased, suggesting that language is not merely a task label but an optimizable conditioning input. We study whether frozen VLA policies can be improved by optimizing language space rather than updating action weights. Our method introduces a language-conditioning space policy that translates a human instruction into a short VLA-grounded command using object appearance,…

---

### [XS-VLA: Coupling Coarse-grained Spatial Distillation with Latent Flow Matching for Lightweight Robotic Control](https://arxiv.org/abs/2607.04171v1)

- **arXiv**: `2607.04171v1`  |  **提交日期**: 2026-07-05
- **作者**: Lei Iok Tong, Qingchen Xie, Wei Huang, Ying Jie Yap, Yujie Zhang, Qianzhi Li et al.

Large Vision-Language Models (LVLMs) have shown strong multimodal understanding and spatial grounding, but their computational cost limits real-time robotic control. In contrast, lightweight models are suitable for edge deployment but often suffer from "spatial blindness", namely weak native spatial prediction ability. Training Vision-Language-Action (VLA) models on mixed human demonstrations can also degrade policy performance due to highly diverse behaviors. To address these limitations, we propose XS-VLA, a two-stage framework for efficient and spatially grounded robotic manipulation.…

---

### [!Imperio, smolVLA: The Implications of Data Poisoning on Open Source Robotics](https://arxiv.org/abs/2607.04146v1)

- **arXiv**: `2607.04146v1`  |  **提交日期**: 2026-07-05
- **作者**: Stefan Bühler, Mark Schutera

This work establishes that trigger-word data poisoning of vision language action models is practical, while at the same time the open-source robotics ecosystem holds trust assumptions about community contributions. A few poisoned samples can silently embed a backdoor that disables a robot on command. We evaluate this threat against smolVLA on a real-world pick-and-place task, training on three poison ratios and evaluating across different prompts on the LeRobot platform. Three poisoned episodes in 320 clean episodes suffice for a complete denial of service. Success rate drops to 0.0 plus…

---

### [Look Before You Leap: Distilling Tree Search into Action Evaluation for Frozen VLA Models](https://arxiv.org/abs/2607.03751v1)

- **arXiv**: `2607.03751v1`  |  **提交日期**: 2026-07-04
- **作者**: Xinyi Xie, Zican Hu, Zhanyu Liu, Yicheng Dong, Wenhao Wu, Zhenhong Sun et al.

Vision-Language-Action (VLA) models acquire broad embodied capabilities through large-scale pretraining, yet their generalization remains far more fragile than that of LLMs and VLMs. The prevailing remedy, post-training via supervised fine-tuning or reinforcement learning, improves task-specific performance but narrows the generalist capability that makes pretraining valuable. We identify a key bottleneck: VLA failures stem not only from action generation but also from action evaluation. A diagnostic pass@k study confirms that frozen VLAs already contain competent behaviors in their output…

---

### [CoRE-VLA: Towards Scalable and Robust Vision-Language-Action Modeling via Conditional Routing of Experts](https://arxiv.org/abs/2607.03693v1)

- **arXiv**: `2607.03693v1`  |  **提交日期**: 2026-07-04
- **作者**: Haozhe Zhang, Sixian Li, Yifei Zhang, Zezheng Huai, Hao Chen, Chunhua Shen et al.

Vision-language-action (VLA) models have advanced generalist robotic manipulation, yet real-world deployment reveals a fundamental challenge: robots are equipped with diverse and heterogeneous sensor configurations, auxiliary sensors can fail unexpectedly during operation, and different robot embodiments often lack certain sensors by design. A unified policy that can exploit auxiliary perceptual inputs when available while remaining reliable under sensor absence, whether incidental or by design, is therefore essential for practical deployment. However, existing VLA policies couple action…

---

## 📅 2026-07-03

### [Embodied.cpp: A Portable Inference Runtime of Embodied AI Models on Heterogeneous Robots](https://arxiv.org/abs/2607.02501v1)

- **arXiv**: `2607.02501v1`  |  **提交日期**: 2026-07-02
- **作者**: Ling Xu, Chuyu Han, Borui Li, Hao Wu, Shiqi Jiang, Ting Cao et al.

Embodied AI models now span vision-language-action (VLA) models and world-action models (WAMs), but practical deployment remains fragmented across model-specific Python stacks, backend assumptions, and robot-side glue code, especially on heterogeneous edge devices. Existing inference runtimes are designed mainly for request-response serving and therefore do not satisfy the runtime contract of embodied deployment: multi-rate execution inside closed-loop control, latency-first batch-1 inference on heterogeneous hardware, and extensible embodied interfaces beyond fixed token I/O. We present…

---

### [Learning to Move Before Learning to Do: Task-Agnostic pretraining for VLAs](https://arxiv.org/abs/2607.02466v1)

- **arXiv**: `2607.02466v1`  |  **提交日期**: 2026-07-02
- **作者**: Junhao Shi, Siyin Wang, Xiaopeng Yu, Li Ji, Jingjing Gong, Xipeng Qiu

Vision-Language-Action (VLA) models are fundamentally bottlenecked by the scarcity of expert demonstrations -- triplets of observations, instructions, and actions that are costly to collect at scale. We argue that this bottleneck stems from conflating two distinct learning objectives: acquiring physical competence (how to move) and acquiring semantic alignment (what to do). Crucially, only the latter requires language supervision. Building on this Decomposition Hypothesis, we propose Task-Agnostic Pretraining (TAP), a two-stage framework that first learns transferable motor priors from cheap,…

---

### [LIME: Learning Intent-aware Camera Motion from Egocentric Video](https://arxiv.org/abs/2607.02417v1)

- **arXiv**: `2607.02417v1`  |  **提交日期**: 2026-07-02
- **作者**: Boyang Sun, Jiajie Li, Yung-Hsu Yang, Chenyangguang Zhang, Tim Engelbracht, Sunghwan Hong et al.

Autonomous robots often need to move their camera before they can act: to inspect an object, reveal an occluded region, or obtain a view that responds to a user's intent. While vision-language navigation translates instructions to base motion and vision-language-action policies map instructions to manipulation actions, language-conditioned camera motion remains comparatively underexplored as a first-class action. We formulate language-conditioned camera motion generation: given a current RGB observation and a free-form natural-language intent, predict a relative target camera pose for the…

---

### [The Moving Eye: Enhancing VLA Spatial Generalization via Hybrid Dynamic Data Collection](https://arxiv.org/abs/2607.02322v1)

- **arXiv**: `2607.02322v1`  |  **提交日期**: 2026-07-02
- **作者**: Jincheng Tang, Yilong Zhu, Zhengyuan Xie, Jiang-Jiang Liu, Jiaxing Zhang

Vision-Language-Action (VLA) models have shown remarkable promise in generalized robotic manipulation. However, their spatial generalization remains fragile. We argue that simply increasing the number of viewpoints is insufficient. Models often fall into the trap of Shortcut Learning, latching onto spurious correlations (e.g., fixed relative poses between objects or between the camera and robot base) rather than learning true spatial relationships. In this work, we propose a data-centric solution to enhance VLA spatial generalization. We utilize a dual-arm setup where one arm performs…

---

### [CoFL-S: Spatially Queryable Sector Flow Fields for Local Language-Conditioned Navigation](https://arxiv.org/abs/2607.02222v1)

- **arXiv**: `2607.02222v1`  |  **提交日期**: 2026-07-02
- **作者**: Haokun Liu, Zhaoqi Ma, Yicheng Chen, Wentao Zhang, Masaki Kitagawa, Zicen Xiong et al.

Vision-Language Navigation has increasingly emphasized high-level instruction reasoning, memory, global map construction, and instruction decomposition, while the low-level action representation remains comparatively underexplored. We propose CoFL-S, a low-level vision-language-action framework that predicts a language-conditioned flow field over the robot's local visible sector and generates continuous trajectories by rolling out the predicted field. To train this low-level representation, we convert each VLN-CE episode, originally a whole-episode instruction paired with an action sequence,…

---

### [Bridge-WA: Predicting Where and How the World Changes for Robotic Action](https://arxiv.org/abs/2607.02195v1)

- **arXiv**: `2607.02195v1`  |  **提交日期**: 2026-07-02
- **作者**: Yongjie Bai, Hanting Wang, Mingtong Dai, Qijun Zhong, Yang Liu, Liang Lin

General-purpose vision-language-action models benefit from large vision-language priors, but effective manipulation also requires anticipating action-relevant scene changes. Existing world-action models often rely on large generative world models or dense future rollouts, which are expensive and spend capacity on visual details weakly coupled to control. We present Bridge-WA, a lightweight world-action framework that distills a frozen future-change teacher into three compact priors: future tokens for intended outcomes, change maps for intervention support, and motion-flow maps for local…

---

### [Guided Action Flow: Q-Guided Inference for Flow-Matching Vision-Language-Action Policies](https://arxiv.org/abs/2607.02092v1)

- **arXiv**: `2607.02092v1`  |  **提交日期**: 2026-07-02
- **作者**: Liuhaichen Yang, Zhuang Jiang, Chenchao Sheng, Zezhi Tang

Flow-matching vision-language-action policies generate robot action chunks through an iterative transport process, creating an opportunity for test-time guidance without retraining the base policy. We study this opportunity in Guided Action Flow, an inference-time framework that keeps a pretrained SmolVLA policy frozen and uses a learned action-chunk critic to guide its reverse-time flow sampler. The critic is trained from real success and failure rollouts, can condition on task-description features from the frozen SmolVLA language pathway, and is used only through action gradients during…

---

### [VLA-Corrector: Lightweight Detect-and-Correct Inference for Adaptive Action Horizon](https://arxiv.org/abs/2607.01804v1)

- **arXiv**: `2607.01804v1`  |  **提交日期**: 2026-07-02
- **作者**: Yi Pan, Miao Pan, Qi Lu, Jiaming Huang, Man Zhang, Siteng Huang et al.

Vision-Language-Action (VLA) foundation models have recently achieved strong progress in embodied intelligence. To reduce policy-call frequency while preserving temporal coherence, most generative policies adopt an action chunk mechanism, executing multiple future actions in an open-loop manner under a fixed action horizon. However, this "predict-then-blindly-execute" paradigm sacrifices closed-loop reactivity: in contact-rich physical interactions, even small local perturbations can rapidly amplify within the open-loop blind spot, leading to compounding errors and ultimately task failure. To…

---

### [Teaching Vision-Language-Action Models What to See and Where to Look](https://arxiv.org/abs/2607.01658v1)

- **arXiv**: `2607.01658v1`  |  **提交日期**: 2026-07-02
- **作者**: Yuguang Yang, Canyu Chen, Zhewen Tan, Yizhi Wang, Zichao Feng, Chunyang Liu et al.

Vision-Language-Action (VLA) models have emerged as a promising paradigm for end-to-end autonomous driving. However, existing VLAs' training relies heavily on text-centric visual question answering and chain-of-thought reasoning data, which emphasizes linguistic reasoning rather than action-grounded planning. As a result, the learned representations capture semantic knowledge but lack spatial dependencies crucial for reliable trajectory prediction. We propose DriveTeach-VLA, a framework that explicitly teaches VLAs what to see and where to look. Driving-aware Vision Distillation (DVD) injects…

---

### [VLAFlow: A Unified Training Framework for Vision-Language-Action Models via Co-training and Future Latent Alignment](https://arxiv.org/abs/2607.01586v1)

- **arXiv**: `2607.01586v1`  |  **提交日期**: 2026-07-02
- **作者**: Guoyang Xia, Fengfa Li, Hongjin Ji, Lei Ren, Fangxiang Feng, Kun Zhan et al.

Vision-language-action models (VLAs) have recently advanced robotic manipulation, yet the effects of different robot-data pre-training paradigms remain difficult to compare because existing models often differ in architecture, data, action space, and evaluation protocol. We present VLAFlow (Vision-Language-Action Flow), a unified flow-matching framework for controlled comparison of VLA training objectives. Using a heterogeneous robot corpus, OXEMix, containing approximately 5,000 hours of data from DROID, OpenX-Embodiment, OpenX-Augmented, and RoboCOIN, we evaluate four paradigms under the…

---

### [Neuro-Symbolic Safety Guidance for Vision-Language-Action Models via Constrained Flow Matching](https://arxiv.org/abs/2607.01378v1)

- **arXiv**: `2607.01378v1`  |  **提交日期**: 2026-07-01
- **作者**: William English, Hao Zheng, Rickard Ewetz

Vision-Language-Action (VLA) models have demonstrated promising generalization capabilities across robotic manipulation tasks, yet their real-world deployment remains limited by the lack of effective safety measures. Specifically, existing safety measures only prevent collisions caused by the robot's next action. In this paper, we propose a neuro-symbolic safety guidance mechanism for flow matching based VLAs that enables predictive collision avoidance. Flow matching based VLAs determine the next actions by predicting a trajectory (a sequence of actions) through an iterative neural flow…

---

## 📅 2026-07-02

### [FurnitureVLA: Learning Long-Horizon Bimanual Furniture Assembly with Vision-Language-Action Model](https://arxiv.org/abs/2607.01212v1)

- **arXiv**: `2607.01212v1`  |  **提交日期**: 2026-07-01
- **作者**: Chenyang Ma, Yue Yang, Radu Corcodel, Siddarth Jain, Andrew Wu, Chiori Hori et al.

Current work on robot furniture assembly mostly focuses on toy-scale settings or single-arm manipulation. We introduce FurnitureVLA, the first systematic study of real-scale bimanual furniture assembly using Vision-Language-Action models (VLAs). We formalize the task, develop a scalable simulation pipeline for expert data generation and evaluation, and build a VR teleoperation system for single-operator bimanual control to collect high-quality real-world demonstrations. To address extreme long-horizon assembly with up to 7 subtasks and 1550 control steps, we propose a progress-enhanced VLA,…

---

### [Human-Centric Transferable Tactile Pre-Training for Dexterous Robotic Manipulation](https://arxiv.org/abs/2607.01067v1)

- **arXiv**: `2607.01067v1`  |  **提交日期**: 2026-07-01
- **作者**: Chi Zhang, Penglin Cai, Ziheng Xi, Haoqi Yuan, Hao Luo, Wanpeng Zhang et al.

As an essential modality for dexterous and contact-rich tasks, tactile sensing provides precise force feedback that cannot be reliably inferred from vision. However, limited by hardware and data collection systems, existing datasets with tactility remain small in scale and narrow in contact coverage. Meanwhile, Vision-Language-Action (VLA) models with tactile modality are constrained on dynamics-agnostic post-training, which limits the performance ceiling on downstream tasks. In this paper, we present H-Tac, a large-scale tactile-action dataset with 160-hour egocentric human videos containing…

---

### [Domain Arithmetic: One-Shot VLA Adaptation under Environmental Shifts](https://arxiv.org/abs/2607.00666v1)

- **arXiv**: `2607.00666v1`  |  **提交日期**: 2026-07-01
- **作者**: Taewook Kang, Taeheon Kim, Donghyun Shin, Jonghyun Choi

Vision-Language-Action (VLA) models often fail to perform the same learned tasks under environmental shifts, such as changes in camera pose and shifts to a different but similar robot (e.g., from Panda to UR5e). Adapting these models to the shifted environment (i.e., target domain) often requires training on multiple demonstrations for each task, which are costly to collect. To reduce the burden of data curation and training, we propose an analogy-based method that adapts VLA models under environmental shifts through weight vector arithmetic with domain-specific information addition, named…

---

### [Unleashing More Actions via Action Compositional Training for VLA Models](https://arxiv.org/abs/2607.00351v1)

- **arXiv**: `2607.00351v1`  |  **提交日期**: 2026-07-01
- **作者**: Kai Peng, Jie Lu, Xiaojiang Peng

Vision-Language-Action models excel at robotic manipulation, driven by the scale and diversity of demonstration data. However, standard training paradigms often cause VLA models to severely overfit to specific behavioral patterns, rendering them unable to generalize to out-of-distribution scenarios even when those scenarios merely require novel combinations of identical sub-skills. While expanding datasets can mitigate this overfitting, acquiring high-quality robot data remains notoriously labor-intensive and cost-prohibitive. To resolve this impasse without expensive human teleoperation and…

---

### [3D HAMSTER: Bridging Planning and Control in Hierarchical Vision Language Action Models through 3D Trajectory Guidance](https://arxiv.org/abs/2606.31329v2)

- **arXiv**: `2606.31329v2`  |  **提交日期**: 2026-06-30
- **作者**: Dongyoon Hwang, Byungkun Lee, Dongjin Kim, Hyojin Jang, Hoiyeong Jin, Jueun Mun et al.

Hierarchical Vision-Language-Action (VLA) models decouple high-level planning from low-level control to improve generalization in robot manipulation. Recent work in this paradigm uses 2D end-effector trajectories predicted by a Vision-Language Model (VLM) as explicit guidance for a downstream policy. However, state-of-the-art low-level policies operate in 3D metric space on point clouds, and feeding them 2D guidance that lacks depth forces each waypoint to be assigned the depth of whatever scene surface lies beneath it, producing geometrically distorted trajectories. We propose 3D HAMSTER, a…

---

### [Training Vision-Language-Action Models with Dense Embodied Chain-of-Thought Supervision](https://arxiv.org/abs/2606.30552v2)

- **arXiv**: `2606.30552v2`  |  **提交日期**: 2026-06-29
- **作者**: Haoyang Li, Guanlin Li, Youhe Feng, Chen Zhao, Zhuoran Wang, Yang Li et al.

Cross-embodiment transfer in vision-language-action (VLA) models remains challenging because low-level state and action spaces differ fundamentally across robot platforms. We observe that the high-level cognitive process underlying manipulation, including scene perception, object identification, task planning, and sub-task decomposition, is largely shared across embodiments. Based on this observation, we present ZR-0, a 2.6 billion parameter end-to-end VLA model that uses dense Embodied Chain-of-Thought (ECoT) supervision to align cross-embodiment representations within the vision-language…

---

## 📅 2026-07-01

### [Human-as-Humanoid: Enabling Zero-Shot Humanoid Learning from Ego-Exo Human Videos with Human-Aligned Embodiments](https://arxiv.org/abs/2606.32009v1)

- **arXiv**: `2606.32009v1`  |  **提交日期**: 2026-06-30
- **作者**: Xiaopeng Lin, Ruoqi Yang, Shijie Lian, Zhaolong Shen, Bin Yu, Changti Wu et al.

Vision-language-action (VLA) models across robot embodiments require high-quality observation--action supervision to learn deployable action distributions, yet scaling such robot data remains difficult, especially for high-DoF humanoids. Teleoperation provides controller-aligned supervision, while human egocentric videos capture diverse bimanual manipulation but do not directly provide executable robot actions. We introduce Human-as-Humanoid, a human-to-humanoid supervision framework that enables near-real-time human-centric action generation, making human demonstrations usable for high-DoF…

---

### [Z-1: Efficient Reinforcement Learning for Vision-Language-Action Models](https://arxiv.org/abs/2606.31846v1)

- **arXiv**: `2606.31846v1`  |  **提交日期**: 2026-06-30
- **作者**: Lang Cao, Renhong Chen, Luyi Li, Peng Wang, Mofan Peng, Yitong Li

Vision-Language-Action (VLA) models offer a promising framework for robotic manipulation by connecting language instructions, visual observations, and continuous control. However, most existing policies remain limited by behavior cloning or supervised fine-tuning (SFT) from fixed demonstrations, which provides limited opportunity to improve from the policy's own failures. In this paper, we present Z-1, a reinforcement learning (RL) post-training framework for flow-based VLA models. Built on top of $π_{0.5}$, Z-1 uses only publicly released RoboCasa demonstrations for SFT and then applies a…

---

### [UniTacVLA: Unified Tactile Understanding and Prediction in Vision Language Action Models](https://arxiv.org/abs/2606.31723v1)

- **arXiv**: `2606.31723v1`  |  **提交日期**: 2026-06-30
- **作者**: Xidong Zhang, Yichi Zhang, Jiaxin Shi, Fucai Zhu, Siyu Zhu, Michael Yu Wang et al.

Vision-language-action (VLA) models have achieved strong performance in many robotic manipulation tasks, yet remain limited in contact-rich dexterous manipulation. To overcome this limitation, recent vision-tactile-language-action (VTLA) methods incorporate tactile sensing into VLA models to provide direct contact information. However, they typically treat tactile signals as passive auxiliary inputs, making it difficult to model tactile semantics and future physical interactions. To this end, we propose a unified tactile learning framework for contact-rich manipulation that models tactile…

---

### [Revisiting Parameter Redundancy in Vision-Language-Action Models: Insights from VLM-to-VLA Adaptation](https://arxiv.org/abs/2606.31382v1)

- **arXiv**: `2606.31382v1`  |  **提交日期**: 2026-06-30
- **作者**: Fengnian Zhang, Tao Huang, Siyu Xu, Zhong Jin, Chang Xu

Vision-Language-Action (VLA) models have made significant strides in embodied intelligence by integrating the powerful representations of pre-trained Vision-Language Models (VLMs). However, the massive parameter scale of VLAs imposes a heavy computational burden, and these models exhibit extreme sensitivity to parameter pruning. Current paradigms often treat the resulting performance degradation as inevitable, relying on fine-tuning or low-rank corrections to recover efficacy. We challenge this convention by questioning whether the removed parameters are truly redundant if VLA pruning…

---

### [3D HAMSTER: Bridging Planning and Control in Hierarchical Vision Language Action Models through 3D Trajectory Guidance](https://arxiv.org/abs/2606.31329v1)

- **arXiv**: `2606.31329v1`  |  **提交日期**: 2026-06-30
- **作者**: Dongyoon Hwang, Byungkun Lee, Dongjin Kim, Hyojin Jang, Hoiyeong Jin, Jueun Mun et al.

Hierarchical Vision-Language-Action (VLA) models decouple high-level planning from low-level control to improve generalization in robot manipulation. Recent work in this paradigm uses 2D end-effector trajectories predicted by a Vision-Language Model (VLM) as explicit guidance for a downstream policy. However, state-of-the-art low-level policies operate in 3D metric space on point clouds, and feeding them 2D guidance that lacks depth forces each waypoint to be assigned the depth of whatever scene surface lies beneath it, producing geometrically distorted trajectories. We propose 3D HAMSTER, a…

---

### [MIRTH: Mutual-Information Reasoning with Temporal Hubs for Vision-Language-Action Agents](https://arxiv.org/abs/2606.31167v1)

- **arXiv**: `2606.31167v1`  |  **提交日期**: 2026-06-30
- **作者**: Hao Sun, Yu Song, Shiyu Teng, Ziwei Niu, Yen-Wei Chen

VLA models have emerged as a powerful paradigm for transferring semantic knowledge from web-scale data to physical robotic control. However, current single-frame architectures suffer from intrinsic limitations: temporal myopia that discards historical dynamics, reasoning gaps between high-level instructions and low-level motor commands, and inference inefficiency due to autoregressive scalar decoding. In this work, we propose MIRTH, a unified framework designed to address these challenges. MIRTH augments a pretrained VLA backbone with three key innovations: (1) dual-scale temporal memory hubs…

---

### [Reasoning-aware Speculative Decoding for Efficient Vision-Language-Action Models in Autonomous Driving](https://arxiv.org/abs/2606.31160v1)

- **arXiv**: `2606.31160v1`  |  **提交日期**: 2026-06-30
- **作者**: Anh Dung Dinh, Simon Khan, Flora Salim

Modern Vision-Language-Action (VLA) planners for autonomous driving emit a chain-of-causation (CoC) reasoning step \emph{before} producing a trajectory. The reasoning is autoregressive and dominates inference latency, while the trajectory head is parallel and cheap. Latency is an operational constraint in autonomous driving, so accelerating the reasoning step is the central problem we address. We observe that CoC reasoning has two qualitatively different needs: most tokens continue routine setup that follows naturally from the ego-trajectory history, and a small fraction encode commitments…

---

### [A Modular Vision-Language-Action Robotics Framework for Indoor Environments](https://arxiv.org/abs/2606.31144v1)

- **arXiv**: `2606.31144v1`  |  **提交日期**: 2026-06-30
- **作者**: Anindya Jana, Snehasis Banerjee, Arup Sadhu, Ranjan Dasgupta

This paper presents an integrated system for the CMU Vision-Language-Action (VLA) Challenge, designed to enable an autonomous agent to perform complex tasks based on natural language instructions. Our framework employs a modular architecture that orchestrates environment mapping, question processing, and navigation. The system operates in two parallel streams: a perception pipeline that constructs a semantic voxel map from real-time camera feeds using OwlViT embeddings, and a language pipeline that classifies user commands with a Vision-Language Model. The mapping is time-constrained; the…

---

### [ELASTIC: Efficiently Learning to Adaptively Scale Test-Time Compute for Generative Control Policies](https://arxiv.org/abs/2606.31132v1)

- **arXiv**: `2606.31132v1`  |  **提交日期**: 2026-06-30
- **作者**: Andrew Zou Li, Gokul Swamy, Yonatan Bisk, Andrea Bajcsy

Generative control policies (GCPs), such as diffusion policies and flow-based vision-language-action models, enable test-time scaling in robot control. Test-time compute can be allocated along two axes: sequential scaling, which increases denoising steps to refine actions, and parallel scaling, which samples multiple candidate actions to search across modes of the policy distribution. However, the optimal allocation of sequential and parallel compute is hard to know a priori as it is state-, task-, and policy-dependent. For example, early stages of a grasp may benefit from broader parallel…

---

### [Position: Vision-Language-Action Models Cannot Be Verified to Perform Physical Reasoning](https://arxiv.org/abs/2606.30686v1)

- **arXiv**: `2606.30686v1`  |  **提交日期**: 2026-06-28
- **作者**: Taozhao Chen, Ian Manchester, Huaming Chen

Vision-Language-Action (VLA) systems, built on pretrained vision-language models (VLMs), have shown rapidly improving performance on robot manipulation benchmarks. These gains are commonly interpreted as evidence that semantic representations learned from internet-scale data transfer to physical execution generalization. This position paper argues that the assumption underlying this interpretation -- that semantic generalization is sufficient to support physical action decisions -- has not been independently verified and cannot be tested under current evaluation protocols. We support this…

---

## 📅 2026-06-30

### [Sequential Planning via Anchored Robotic Keypoints](https://arxiv.org/abs/2606.30613v1)

- **arXiv**: `2606.30613v1`  |  **提交日期**: 2026-06-29
- **作者**: Bryce Grant, Aryeh Rothenberg, Logan Senning, Zonghe Chua, Zach Patterson, Peng Wang

We present Sequential Planning via Anchored Robotic Keypoints, SPARK, a training-free neurosymbolic manipulation system that reaches 43.7% on six LIBERO-PRO position \& task cells, more than doubling CaP-Agent0 and Vision-Language-Action (VLA) baselines. CaP-Agent0, a multi-turn code-generation agent, achieves 18.2% by re-querying an LLM at every turn, but its restart-from-scratch solution proves costly against minor policy failures. Perception is the layer that fails most under position and task changes so SPARK spends its computation there. A single Gemini call composes the plan as a typed…

---

### [Training Vision-Language-Action Models with Dense Embodied Chain-of-Thought Supervision](https://arxiv.org/abs/2606.30552v1)

- **arXiv**: `2606.30552v1`  |  **提交日期**: 2026-06-29
- **作者**: Haoyang Li, Guanlin Li, Youhe Feng, Chen Zhao, Zhuoran Wang, Yang Li et al.

Cross-embodiment transfer in vision-language-action (VLA) models remains challenging because low-level state and action spaces differ fundamentally across robot platforms. We observe that the high-level cognitive process underlying manipulation, including scene perception, object identification, task planning, and sub-task decomposition, is largely shared across embodiments. Based on this observation, we present ZR-0, a 2.6 billion parameter end-to-end VLA model that uses dense Embodied Chain-of-Thought (ECoT) supervision to align cross-embodiment representations within the vision-language…

---

### [Vision-Language-Action Models: Experimental Insights from a Real-World UR5 Platform](https://arxiv.org/abs/2606.30456v1)

- **arXiv**: `2606.30456v1`  |  **提交日期**: 2026-06-29
- **作者**: Mathilde Hochedel, Marc Lalonde

This project investigates whether recent Vision-Language-Action (VLA) models can be transferred from controlled research benchmarks to a real-world robotic platform, specifically a UR5e manipulator, in a reproducible and operationally meaningful manner. The work integrates real-robot data acquisition, dataset engineering (compatible with the RLDS format), and the fine-tuning and deployment of OpenVLA and OpenVLA-OFT models, with systematic validation of action representations and control interfaces. The project resulted in several foundational assets: (i) a complete real-robot data…

---

### [Automating the Design of Embodied AgentArchitectures](https://arxiv.org/abs/2606.30111v1)

- **arXiv**: `2606.30111v1`  |  **提交日期**: 2026-06-29
- **作者**: Jian Zhou, Sihao Lin, Jin Li, Shuai Fu, Gengze Zhou, Qi Wu

Embodied agents are typically built as hand-designed compositions of perception, memory, planning, and action modules. This modularity exposes a large architectural design space, but current systems still rely on researcher intuition to choose where information is stored, how observations are processed, and how model calls are connected. Agent Architecture Search (AAS) automates such design for text-domain agents, but has not been systematically evaluated on perceptual embodied agents through simulator rollouts. We study this transfer. We introduce AgentCanvas, a typed-graph runtime that…

---

### [OpenSPM: An Environment-Transferable Robotic Key Spatial Pose Memory and Closed-Loop High-Frequency Flow-Matching Action Generation Model](https://arxiv.org/abs/2606.29936v1)

- **arXiv**: `2606.29936v1`  |  **提交日期**: 2026-06-29
- **作者**: Iok Tong Lei, Qingchen Xie, Yifan Wang, Yap Ying Jie, Zhidong Deng

Open-environment tabletop robotic manipulation requires systems to possess semantic understanding, precise geometric pose estimation, and high-frequency action generation. While end-to-end vision-language-action (VLA) models excel at semantic generalization, they often lack explicit geometric constraints for fine-grained tasks and require costly training. To bridge the gap between high-level semantics and low-level physical execution, we propose OpenSPM, an open environment spatial persistent memory framework consisting of spatial pose memory and flow-matching action generation model. OpenSPM…

---

### [Critical Interval MSE: Toward Reliable Offline Validation for Robot Manipulation Policies](https://arxiv.org/abs/2606.29898v1)

- **arXiv**: `2606.29898v1`  |  **提交日期**: 2026-06-29
- **作者**: Haoxu Huang, Tongsam Zheng, Yifan Chen, Jiacheng You, Yang Gao

Real-world evaluation is the gold standard for robot policies because it tests them against the physical conditions and deployment challenges they are ultimately designed to handle. However, real-world evaluation is also the bottleneck for iterating on robot policies: it is costly, difficult to reproduce, and often too sparse to reliably compare nearby model variants. A straightforward proxy for performance is validation loss on expert demonstrations, but this proxy is often poorly correlated with real-world performance. In this paper, we introduce Critical Interval MSE (CI-MSE), an…

---

### [Trust Your Instincts: Confidence-Driven Test-Time RL for Vision-Language-Action Models](https://arxiv.org/abs/2606.29892v1)

- **arXiv**: `2606.29892v1`  |  **提交日期**: 2026-06-29
- **作者**: Siyao Chen, Jiakang Yuan, Jiaxin Wang, Tao Chen

Reinforcement learning (RL) has become indispensable for pushing Vision-Language-Action Models (VLAs) beyond static imitation learning. However, existing RL methods typically require external environmental feedback, relying on predefined success signals to guide policy updates. In this work, we show that VLA models possess useful internal evaluative capabilities: in discrete-action VLAs, trajectories with higher generation confidence are significantly more likely to succeed. Based on this observation, we introduce T^2VLA (Test-time VLA), an architecture-agnostic test-time RL framework that…

---

### [Early Warning Signals for OpenVLA Failure under Visual Distribution Shift](https://arxiv.org/abs/2606.29699v1)

- **arXiv**: `2606.29699v1`  |  **提交日期**: 2026-06-29
- **作者**: Dipesh Tharu Mahato, Rachel Ren

Vision Language Action models combine perception, language grounding, and control in a single policy, but their failures are hard to diagnose once visual conditions shift. We test whether OpenVLA feedforward activations contain linearly decodable information about near term task failure in LIBERO manipulation rollouts. The policy is fixed throughout. We log internal activations during execution and fit lightweight monitors after the rollouts are collected. Occlusion is the main controlled stress test. It reduces OpenVLA success from $57\%$ to $17\%$ over $100$ episodes per condition. Under…

---

### [Event-VLA: Action-Conditioned Event Fusion for Robust Vision-Language-Action Model](https://arxiv.org/abs/2606.29384v1)

- **arXiv**: `2606.29384v1`  |  **提交日期**: 2026-06-28
- **作者**: Jiaxin Liu, Xun Xu, Zhenhao Zhang, Hanqing Wang, Ruiqi Chen, Shi Chang et al.

Vision-Language-Action (VLA) models have become an important paradigm of embodied AI. However, existing VLA models typically assume well-lit and stable indoor settings, while real-world embodied manipulation may involve degraded RGB observations caused by illumination shifts, posing critical challenges for robust robotic manipulation. To address this gap, we propose \textbf{Event-VLA}, an event-enhanced VLA framework for generalizable manipulation across varying illumination conditions. We formulate VLA-based manipulation under degraded visibility as a practical robustness problem for…

---

### [Fast Enough to Act: Spatio-Temporal Visual Token Merging for Low-Latency Robotic VLMs and VLAs](https://arxiv.org/abs/2606.29350v1)

- **arXiv**: `2606.29350v1`  |  **提交日期**: 2026-06-28
- **作者**: Junzhou Chen, Jindong Wang, Gang Zhou

Vision-language models and vision-language action models endow the robot with unprecedented capabilities. However, the input of video and high-resolution images yields a massive number of visual tokens, leading to extremely high inference latency and severely hindering the robot's real-time control. To break through this computational bottleneck, we propose ST-Merge, a plug-and-play, training-free framework that efficiently fuses redundant tokens directly during the visual encoding phase. By explicitly constructing 3D spatiotemporal coordinates, it employs a multi-queue parallel matching and…

---

### [SurgVLA-Bench: Towards Evaluating Vision-Language-Action Models for Laparoscopic Surgical Robotics](https://arxiv.org/abs/2606.29247v1)

- **arXiv**: `2606.29247v1`  |  **提交日期**: 2026-06-28
- **作者**: Jiashuo Sun, Yue He, Wenxuan Liu, Tao Mao, Jiazheng Wang, Xiang Chen et al.

Vision-Language-Action (VLA) models represent a promising direction for embodied intelligence in surgical robotics. Despite the prevalence of VLA benchmarks for general robotics, standardized evaluation platforms specifically designed for surgical contexts remain absent. To address this limitation, we present SurgVLA-Bench, the first comprehensive benchmark for evaluating VLA models in laparoscopic surgical robotics. Leveraging the SurRoL simulation platform, we construct a hierarchical task taxonomy ranging from atomic actions to complete surgical procedures, complemented by a…

---

### [TAP-VLA: Tactile Annotation Prompting for Vision Language Action Models](https://arxiv.org/abs/2606.29089v1)

- **arXiv**: `2606.29089v1`  |  **提交日期**: 2026-06-27
- **作者**: Mark Van der Merwe, Mohamad Louai Shehab, Jayjun Lee, Youngsun Wi, Yinpei Dai, Dmitry Berenson et al.

Vision-Language-Action (VLA) models demonstrate impressive reasoning over visual, semantic, and spatial task variations by leveraging large-scale vision and language pre-training. They remain, however, largely blind to contact forces, which seldom manifest clearly in visual feedback but are central to contact-rich manipulation. Tactile sensing measures these forces directly, but integrating it into VLAs is difficult: tactile data is absent from the large-scale corpora used to pre-train VLAs, so adding it as a new input modality induces a distribution shift that erodes the very pre-training…

---

### [ViPSim: Collaborating Visual and Parameter Spaces for Consistent Long-Horizon Embodied World Models](https://arxiv.org/abs/2606.28804v1)

- **arXiv**: `2606.28804v1`  |  **提交日期**: 2026-06-27
- **作者**: Longyu Chen, Heng Li, Wei Yang, Manqi Zhao, Dongsheng Jiang

Embodied World Models (EWMs) have emerged as a scalable and risk-free paradigm for advancing embodied intelligence, enabling the safety-critical evaluation of Vision-Language-Action systems. However, their reliability as evaluation benchmarks and foundational simulators is often hindered by the representation gap between low-dimensional actions and high-dimensional video synthesis. This gap results in a lack of geometric correspondence, manifesting as accumulated trajectory drift and inconsistent robot-object interactions during long-horizon rollouts. To bridge this gap, we propose ViPSim, a…

---

### [X-Mind: Efficient Visual Chain-of-Thought via Predictive World Model for End-to-End Driving](https://arxiv.org/abs/2606.28758v1)

- **arXiv**: `2606.28758v1`  |  **提交日期**: 2026-06-27
- **作者**: Bohao Zhao, Chengrui Wei, Guangfeng Jiang, Ruixin Liu, Xuejie Lv, Liu Liang et al.

Predicting future states is essential for autonomous agents, yet current Vision-Language-Action (VLA) models fundamentally lack this capability, relying instead on reactive perception-action mapping. While integrating Predictive World Models (PWMs) addresses this gap, existing approaches either incur prohibitive cascaded latency or act as shallow terminal tasks that fail to deeply embed forward-looking reasoning. To endow VLA models with this reasoning capability, we propose X-Mind. Rather than treating PWMs as an external auxiliary module, this framework internalizes them as the Visual…

---

## 📅 2026-06-29

### [Translation as a Bridging Action: Transferring Manipulation Skills from Humans to Robots](https://arxiv.org/abs/2606.28133v1)

- **arXiv**: `2606.28133v1`  |  **提交日期**: 2026-06-26
- **作者**: Sijin Chen, Kaixuan Jiang, Haixin Shi, Yanhui Wang, Weiheng Zhong, Haosheng Li et al.

We study whether we can learn novel manipulation skills from human actions to a bi-manual robot with parallel grippers. Human action data is cheap, abundant, and diverse, making it one of the most promising resources for scaling up robot learning. Yet transferring skills from humans to robots remains hard: most prior work treats humans as just another bi-manual 6DoF embodiment, where hand-pose estimates are noisy and the contact patterns of human fingers differ fundamentally from those of a parallel gripper. We argue that learning rotation-inclusive action signals from human data is therefore…

---

### [S$^2$-VLA: State-Space Guided Vision-Language-Action Models for Long-Horizon Manipulation](https://arxiv.org/abs/2606.27872v1)

- **arXiv**: `2606.27872v1`  |  **提交日期**: 2026-06-26
- **作者**: Zhipeng Xie, Zongyi Han, Xiangyi Wei, Shiliang Sun, Yang Li, Jing Zhao

Vision-Language-Action (VLA) models have demonstrated strong capabilities in robotic manipulation, but their performance degrades significantly in long-horizon tasks due to cumulative error propagation. This limitation largely arises from static feature fusion mechanisms that rely on fixed weights to combine visual, language, and action representations, preventing the model from adapting to different phases of task execution. To address this limitation, we propose S$^2$-VLA, a framework that introduces a State-Space Guided Adaptive Attention (SSGAA) mechanism. SSGAA maintains a belief state…

---

### [SpikeVLA: Vision-Language-Action Models with Spiking Neural Networks](https://arxiv.org/abs/2606.27807v1)

- **arXiv**: `2606.27807v1`  |  **提交日期**: 2026-06-26
- **作者**: Ruiqi Song, Dujun Nie, Siyu Teng, Baiyong Ding, Xiaotong Zhang, Dong Li et al.

Vision-Language-Action (VLA) models have become a dominant paradigm for embodied intelligence. However, most existing approaches are built on large-scale transformers, resulting in substantial inference latency and energy consumption that limit their practical deployment in low-power, real-time scenarios. We propose SpikeVLA, a spiking VLA architecture for embodied navigation with energy-efficient inference, consisting of three key components. (i) A spiking vision encoder, Spike-V, that replaces dense continuous layers with event-driven spiking layers to reduce the energy consumption of…

---

### [Drop-Then-Recovery: How Redundant Are Vision-Language-Action Models?](https://arxiv.org/abs/2606.27755v1)

- **arXiv**: `2606.27755v1`  |  **提交日期**: 2026-06-26
- **作者**: Guoheng Sun, Kaixi Feng, Shwai He, Xiaochuan Gong, Yexiao He, Ziyao Wang et al.

Vision-Language-Action (VLA) models enable instruction-driven robotic manipulation, but they inherit oversized language backbones from pretrained VLMs whose capacity far exceeds what is needed for short robotic instructions. This raises a basic question: how much of a VLA model is actually necessary for closed-loop control? In this work, we study architectural redundancy in VLA models by using transformer block removal as a controlled intervention. We introduce \textbf{Drop-Then-Recovery (DTR)}, an analysis protocol that removes selected blocks from a pretrained VLA model and then fine-tunes…

---

### [Direct Action-Head Injection of A Grounded 3D Point Unlocks Spatial and Task Generalization](https://arxiv.org/abs/2606.27663v1)

- **arXiv**: `2606.27663v1`  |  **提交日期**: 2026-06-26
- **作者**: Shiang-Feng Tsai, Jin-Cheng Jhang, Yen-Ling Tai, Jia-Hong Lai, Shih-Yun Wong,  KangTung-Hsu et al.

Vision-Language-Action (VLA) models leverage large-scale vision-language pretraining for flexible robot manipulation, yet at test time they remain brittle along two axes: spatial generalization, when object positions differ from those seen during training, and task generalization, when a familiar scene is paired with a different language instruction than the one seen in training. A growing family of methods addresses this brittleness by endowing a policy with the spatial and task-aware information such as 2D pixel-coordinate for object localization and placement. However, we find that…

---

## 📅 2026-06-27

### [Scalable Behavior Cloning with Open Data, Training, and Evaluation](https://arxiv.org/abs/2606.27375v1)

- **arXiv**: `2606.27375v1`  |  **提交日期**: 2026-06-25
- **作者**: Arthur Allshire, Himanshu Gaurav Singh, Ritvik Singh, Adam Rashid, Hongsuk Choi, David McAllister et al.

We introduce ABC, a fully open-source stack for manipulation with behavior cloning. At its core is ABC-130K: the largest open-source teleoperation dataset to date, featuring 3,500 hours of data spanning over 130K episodes across 195 diverse tasks. Furthermore, we open-source our accessible hardware setup, training infrastructure, and simulation pipeline. We also release 400 hours of sim-teleop data and provide a co-training recipe that produces correlated simulation and real-world evaluation, offering a reliable proxy for ablating model-design and training decisions before costly real-world…

---

### [RouterVLA: Turning Smoke Tests into Supervision for Heterogeneous VLA Selection](https://arxiv.org/abs/2606.27355v1)

- **arXiv**: `2606.27355v1`  |  **提交日期**: 2026-06-25
- **作者**: Xingyu Ren, Chugang Yi, Ge Ma, Youran Sun

We study whether pre-deployment evaluation rollouts can be reused to supervise policy selection. Robot teams routinely smoke test candidate vision-language-action (VLA) policies, then compress those trials into a global winner. RouterVLA evaluates this idea with outcome-disjoint cross-fitting: recorded probes build a profile for each frozen expert, and a separate trial scores the selected expert without entering its profile. Across 34,752 LIBERO-Plus rollout records, a transparent probe-success rule raises held-out success from 0.4686 to 0.6149, a +14.64pp gain. Under the scalar-only profiles…

---

### [LA4VLA: Learning to Act without Seeing via Language-Action Pretraining](https://arxiv.org/abs/2606.27295v1)

- **arXiv**: `2606.27295v1`  |  **提交日期**: 2026-06-25
- **作者**: Tao Lin, Yuxin Du, Yiran Mao, Zewei Ye, Yilei Zhong, Bing Cheng et al.

Vision-Language-Action (VLA) models are commonly pretrained on robot demonstrations by jointly mapping visual observations and language instructions to actions. However, dense visual-action supervision can dominate the comparatively sparse language-action signal. As a result, policies may rely on visual shortcuts rather than learn how language conditions action execution, making them sensitive to visual variations. To address this limitation, we propose LA4VLA, a language-action pretraining framework that enables policies to acquire language-conditioned action priors without visual…

---

### [E-TTS: A New Embodied Test-Time Scaling Framework for Robotic Manipulation](https://arxiv.org/abs/2606.27268v1)

- **arXiv**: `2606.27268v1`  |  **提交日期**: 2026-06-25
- **作者**: Wen Ye, Peiyan Li, Tingyu Yuan, Yuan Xu, Xiangnan Wu, Chaoyang Zhao et al.

Recently, a few works have made early attempts to study test-time scaling for embodied tasks. However, two major challenges remain unsolved: (1) reasoning can effectively improve the performance of the policy, but its scaling mechanism has seldom been studied; (2) historical information is essential, as embodied tasks are inherently long-horizon and sequential, making sole reliance on current observations for action scaling inadequate due to the lack of historical context utilization. To address these challenges, we introduce E-TTS, a modular and plug-and-play Embodied Test-Time Scaling…

---

### [PhysReflect-VLA: Physical Feasibility and Self-Reflective Regulation for Reliable Vision-Language-Action Policies](https://arxiv.org/abs/2606.27146v1)

- **arXiv**: `2606.27146v1`  |  **提交日期**: 2026-06-25
- **作者**: Jiayu Yang, Tao Yang, Weijun Li, Xiang Chang, Fei Chao, Changjing Shang et al.

Long-horizon robotic manipulation is highly sensitive to physically infeasible transitions, contact-induced disturbances, and the lack of effective self-correction during execution. Although Vision-Language-Action (VLA) models provide strong task grounding through multimodal learning, they typically generate actions in a feed-forward manner without explicitly checking physical feasibility or diagnosing execution errors online. We present PhysReflect-VLA, a plug-and-play execution-time reliability framework that augments VLA policies with physical feasibility evaluation and structured…

---

### [PAMAE: Phase-Aware-MoE Action Experts Towards Reliable Flow-Matching Vision-Language-Action Policies](https://arxiv.org/abs/2606.27144v1)

- **arXiv**: `2606.27144v1`  |  **提交日期**: 2026-06-25
- **作者**: Jiayu Yang, Tao Yang, Xiang Chang, Fei Chao, Changjing Shang, Qiang Shen

Reliable action generation for multi-stage robotic manipulation remains challenging for Vision-Language-Action (VLA) models. While existing flow-matching VLA policies offer strong multimodal grounding and generalization, they typically employ a single shared action expert, limiting their ability to capture phase-specific control patterns across distinct execution stages. We propose a plug-and-play Phase-Aware Mixture-of-Experts Action Module (PAMAE), as a step towards more reliable phase-consistent action generation. PAMAE replaces the original flow-matching action expert with a sparse expert…

---

### [Improving Vision-Language-Action Model Fine-Tuning with Structured Stage and Keyframe Supervision](https://arxiv.org/abs/2606.26801v1)

- **arXiv**: `2606.26801v1`  |  **提交日期**: 2026-06-25
- **作者**: Yuan Xu, Yixiang Chen, Kai Wang, Jiabing Yang, Peiyan Li, Qisen Ma et al.

Vision-Language-Action (VLA) models have shown strong potential for generalizable robotic manipulation. During fine-tuning, however, action supervision applies equally across all timesteps, without structured supervision on which manipulation stage the robot is in or what the next gripper-event target should be. This causes failures to concentrate around challenging gripper-event transitions. To address this, we propose StaKe, a plug-in auxiliary supervision framework that automatically derives two complementary signals from demonstration gripper states without manual annotation: a stage…

---

### [Inference-Time Robot Behavior Steering through Physically-Aware Reconfiguration of Task-Structure](https://arxiv.org/abs/2606.26588v1)

- **arXiv**: `2606.26588v1`  |  **提交日期**: 2026-06-25
- **作者**: Yiyuan Pan, Hanjiang Hu, Shangtao Li, Xusheng Luo, Changliu Liu

A central challenge in deploying learned robot policies is inference-time behavior steering: redirecting a policy at test time to satisfy user preferences not anticipated during training, without retraining. Existing methods fail in two modes: end-to-end methods require fine-tuning or expert-level guidance, while neuro-symbolic methods rely on predefined symbols whose edits can result in logically reasonable but physically infeasible plans. To address this challenge, we propose ReStruct, which builds upon a neural automaton policy that decomposes a visuomotor policy into a high-level…

---

### [Learning Action Priors for Cross-embodiment Robot Manipulation](https://arxiv.org/abs/2606.26095v1)

- **arXiv**: `2606.26095v1`  |  **提交日期**: 2026-06-24
- **作者**: Dong Jing, Tianqi Zhang, Jiaqi Liu, Jinman Zhao, Zelong Sun, Li Erran Li et al.

Most Vision-Language-Action (VLA) models build on a Vision-Language Model (VLM) backbone by attaching an action module and optimizing the full policy jointly. This design inherits strong visual and linguistic priors from the VLM, but leaves the action module to learn physical motion almost from scratch. As a result, the policy lacks an explicit motion prior, forcing early optimization to simultaneously discover temporal action dynamics and cross-modal alignment, a challenge further amplified in cross-embodiment settings. In this work, we propose to pretrain the action module with motion…

---

### [ForceBand: Learning Forceful Manipulation with sEMG](https://arxiv.org/abs/2606.26093v1)

- **arXiv**: `2606.26093v1`  |  **提交日期**: 2026-06-24
- **作者**: Botao He, Zhi Wang, Linna Kuang, Ishaan Ghosh, Jitendra Malik, Cornelia Fermuller et al.

Human demonstrations are a scalable data source for learning robot manipulation policies. However, common sources of human demonstration data, such as motion-capture trajectories and internet videos, capture mostly motion and appearance while missing the contact forces that are critical for force-sensitive manipulation. In this paper, we introduce ForceBand, a low-cost wrist-worn sEMG system that turns human muscle activity into force-enriched demonstrations. We first collect a 10-hour multimodal dataset containing egocentric video, sEMG, IMU, and fingertip force measurements across diverse…

---

### [FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation](https://arxiv.org/abs/2606.26006v1)

- **arXiv**: `2606.26006v1`  |  **提交日期**: 2026-06-24
- **作者**: Shuyi Zhang, Yunfan Lou, Hongyang Cheng, Yichen Guo, Chuyao Fu, Yaoxu Lyu et al.

Vision-Language-Action (VLA) models are often constrained by the imitation ceiling imposed by sub-optimal data. While Reinforcement Learning (RL) fine-tuning can surpass this limit, it is notoriously sample inefficient. This challenge arises from two core issues: (1) catastrophic initial unlearning due to an unstable Q-function and (2) inefficient policy updates caused by low-quality exploration data, often forcing a reliance on costly human interventions. We introduce FORCE, a 3-stage framework that stabilizes fine-tuning by tackling both issues. FORCE first incorporates a Value-Calibrated…

---

### [Action ControlNet: A Lightweight Delay-Aware Adapter for Smooth Asynchronous Control in Vision-Language-Action Models](https://arxiv.org/abs/2606.25985v1)

- **arXiv**: `2606.25985v1`  |  **提交日期**: 2026-06-24
- **作者**: Tiecheng Guo, Meng Guo

Vision-language-action (VLA) models have shown strong potential for general-purpose robot manipulation, but their inference latency remains a major obstacle to stable high-frequency control. Asynchronous execution mitigates this bottleneck by overlapping policy inference with action execution, yet the next action chunk is still predicted from stale observations while the robot continues to move. Direct chunk stitching therefore introduces handoff discontinuities, action jitter, and failures in contact-rich manipulation. Existing remedies typically require either full-policy retraining or…

---

### [ROAD-VLA: Robust Online Adaptation via Self-Distillation for Vision-Language-Action Models](https://arxiv.org/abs/2606.25800v1)

- **arXiv**: `2606.25800v1`  |  **提交日期**: 2026-06-24
- **作者**: Kejing Wang, Toan Nguyen, Minh Hoang Nguyen, Simon Khan, Flora D. Salim

Effective online adaptation of vision-language-action (VLA) models remains challenging, as sparse rewards provide weak supervision for high-dimensional autoregressive action policies. Although self-distillation can in principle provide denser training signals, we find that text-based privileged teachers conditioned on demonstrations, retrieved experiences, or high-level plans are ineffective for VLA adaptation, exposing a modality gap between symbolic guidance and low-level robot actions. We propose ROAD-VLA, an advantage-guided self-distillation framework that constructs a proximal teacher…

---

### [Decoupling Semantics and Geometric Grounding: Spatial Visual Prompts for Language-Conditioned Imitation Learning](https://arxiv.org/abs/2606.25360v1)

- **arXiv**: `2606.25360v1`  |  **提交日期**: 2026-06-24
- **作者**: Yanzhe Tang, Xinyu Shao, Yuxuan Hu, Siyu Chen, Bowen Yang, Yajun Gao et al.

While end-to-end Vision-Language-Action (VLA) models show promise in robotic manipulation, their monolithic paradigm inherently couples semantic reasoning and spatial control. This creates a severe alignment bottleneck, limiting precise target disambiguation in data-constrained imitation learning. To overcome this, we propose SVP-IL, a decoupled architecture that explicitly extracts spatial visual grounding from the action generation loop. By leveraging vision-language foundation models, we parse instructions into zero-shot geometric masks, translating language into explicit Spatial Visual…

---

