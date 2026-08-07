# VLA 视觉-语言-动作 (Vision-Language-Action)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

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

