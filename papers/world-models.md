# 世界模型 (World Models)

_自动追踪 arXiv 最新论文，最新更新在最上方。_

## 📅 2026-10-08

### [RoboJEPA: Scaling Robotic Latent World Models](https://arxiv.org/abs/2610.10515v1)

- **arXiv**: `2610.10515v1`  |  **提交日期**: 2026-10-07
- **作者**: Artem Zholus, Nicolas Beltran-Velez, Jianhao Yuan, Sarath Chandar, Tushar Nagarajan, Daniel Severo et al.

Latent world models have shown a remarkable ability to predict future states and to plan in the real world. In practice, however, we lack a principled way to estimate how their capabilities scale with model size, data, and compute, an open problem that slows progress in the field. In this work we present RoboJEPA, a world model based on the Joint Embedding Predictive Architecture (JEPA) and trained on a large-scale dataset spanning 12 robotic embodiments. We show that RoboJEPA's imagination error, the error of its latent rollouts, follows a second-order power law in compute, allowing us to…

---

### [Sparse Planning in Visual World Models via Cost Gradients](https://arxiv.org/abs/2610.10274v1)

- **arXiv**: `2610.10274v1`  |  **提交日期**: 2026-10-07
- **作者**: Yingchen Xu, Edward Grefenstette

Token-based world models enable fine-grained latent planning, but repeatedly processing large spatial token grids makes action search expensive. We introduce COSTGRAD, a training-free, goal-conditioned selector that ranks spatial tokens by the gradient norm of the planning cost with respect to each input token. By deriving importance from the downstream control objective, COSTGRAD targets tokens that matter for planning rather than merely for prediction. On AdaLN-conditioned predictors at $50\%$ sparsity, COSTGRAD matches or exceeds full-token planning on three of four continuous-control…

---

### [UltraWorld: Learning Interactive Ultrasound World Models from Untracked Clinical Videos with Acoustic Sampling Map](https://arxiv.org/abs/2610.09785v1)

- **arXiv**: `2610.09785v1`  |  **提交日期**: 2026-10-07
- **作者**: Keke Yang, Erqi Wang, Sainan Guan, Hongliang Ren

World models can enable autonomous ultrasound scanning by predicting the outcomes of probe motions from local observations. Learning this action--observation relationship typically relies on synchronized video--pose pairs, which are costly to collect at scale and largely unavailable in routine clinical recordings. Reliable action following further requires modeling ultrasound's cross-sectional sampling geometry. We present UltraWorld, a self-distillation recipe that transfers priors from clinical ultrasound videos into interactive world models without real action annotations. Starting from…

---

### [Beyond Policy Support: Interaction Constrained Offline Reinforcement Learning for Autonomous Driving](https://arxiv.org/abs/2610.09763v1)

- **arXiv**: `2610.09763v1`  |  **提交日期**: 2026-10-07
- **作者**: Mahmoud Selim, Cristina Cipriani, Karl Henrik Johansson

Offline reinforcement learning enables reward-driven policy improvement from fixed datasets without requiring online exploration, making it particularly attractive in safety-critical domains. A central challenge, however, is distribution shift: policy optimization may favor actions that are weakly supported by the offline data, rendering value estimates unreliable. Existing approaches primarily control this shift in the policy's own action space. In interactive environments such as autonomous driving, this can be insufficient: a candidate ego trajectory may remain well supported under the…

---

### [ΔWAM: Distilling Action Tangent Fields into World Action Models](https://arxiv.org/abs/2610.09734v1)

- **arXiv**: `2610.09734v1`  |  **提交日期**: 2026-10-07
- **作者**: Ke Wu, Hanwen Huang, Bo Gu, Kaizhao Zhang, Xiangting Meng, Yupeng Zheng et al.

World Action Models (WAM) improve robot policies by augmenting sparse action supervision with dense future prediction. However, much of the predictable future is dominated by appearance and scene persistence rather than action-dependent dynamics. We observe that several recent WAM designs, including optical flow, motion-centric representations, and latent actions, can be understood from a common perspective in which world supervision becomes more efficient as it contains a higher proportion of action-relevant variation. Based on this insight, we introduce Action Tangent Fields, which…

---

### [STRIKE: Learning Visual State Transitions for Physical World Modeling](https://arxiv.org/abs/2610.09514v1)

- **arXiv**: `2610.09514v1`  |  **提交日期**: 2026-10-07
- **作者**: Wenbin Teng, Tianshuo Xu, Depu Meng, Yuelei Li, Quentin Herau, Yihan Hu et al.

Physical world modeling requires predicting how interactions change a scene, not merely generating coherent motion. We propose STRIKE, a framework that separates visual state transition learning from dense video generation. We construct event-aligned supervision by extracting observed states from training videos and pairing them with transition descriptions and temporal offsets. An image-based transition model learns to predict the next scene configuration from the current image, a local transition specification, and elapsed time. At inference, a pretrained vision-language planner predicts…

---

### [DSReg: Provably Recovering Individual World Latents without Reconstruction](https://arxiv.org/abs/2610.09457v1)

- **arXiv**: `2610.09457v1`  |  **提交日期**: 2026-10-07
- **作者**: Yujia Zheng, David Klindt, Randall Balestriero, Bernhard Schölkopf

Methods that recover individual latent variables of the world, from nonlinear ICA to dictionary learning and causal representation learning, anchor the latents to observations through reconstruction, auxiliary supervision, or distributional asymmetries such as non-Gaussianity. Methods without these anchors, including joint-embedding predictive architectures (JEPAs), identify the latent state only up to a linear transformation, so individual latents remain mixed. We close this gap: individual world latents can be provably recovered with no reconstruction, no decoder, and no labels. The key…

---

### [Controllable Crowd Generation through World-Model Planning](https://arxiv.org/abs/2610.09438v1)

- **arXiv**: `2610.09438v1`  |  **提交日期**: 2026-10-07
- **作者**: JunGyu Lee, Jisu Shin, Seunghyun Shin, Hae-Gon Jeon

Crowd simulation plays a central role in robot navigation, autonomous driving, and urban planning. For these applications, realistic simulation requires crowds to adapt their behavior to environmental changes and user objectives. However, existing methods that rely on predefined control settings have limited flexibility in accommodating new user-specified objectives. To address this limitation, we propose Ctrl-CWM, a multi-agent Controllable Crowd World Model that integrates crowd generation and run-time control. Our key idea is to adapt the world-model principle of planning using imagined…

---

### [SearchWorld: Spatial Value-Grounded Imagination for UAV Object Search via World Models](https://arxiv.org/abs/2610.09335v1)

- **arXiv**: `2610.09335v1`  |  **提交日期**: 2026-10-07
- **作者**: Yatai Ji, Zhengqiu Zhu, Yong Zhao, Yue Hu, Fanglong Yao, Chen Gao et al.

Autonomous unmanned aerial vehicle (UAV) object search involves a closed loop of perception, decision-making, and action under partial observability. Urban environments pose several challenges: large search areas and narrow egocentric views limit coverage, dense 3D geometry constrains safe motion, and open-world instructions require identifying a specific target among distractors. Many existing methods mitigate partial observability through explicit maps or memory representations, yet remain largely reactive, reasoning over past observations without explicitly predicting future states. World…

---

### [Predicted Futures Are Not Enough: Learning Executable Goals for Robot Manipulation](https://arxiv.org/abs/2610.09309v1)

- **arXiv**: `2610.09309v1`  |  **提交日期**: 2026-10-07
- **作者**: Tzu-Yu Chuang, Ching-Hsiang Chang, Yi-Hsiu Lee, Yi-Ting Chen, Min Sun, YuanFu Yang

Generative world models provide rich predictions of how manipulation scenes may evolve toward task objectives, yet those futures do not directly expose the compact task variables required by control. When training supervises future prediction alone, terminal goal accuracy is not an explicit learning objective, even when geometric recovery is available. We present Entity-Level Goal Readout, a learned prediction-to-execution interface that makes the executable terminal goal an explicit output of a 3D trace world model. It combines object-centric pose prediction with translation grounded in…

---

### [Kuration SDK: Addressing the Virtual2Real Gap via Data Curation](https://arxiv.org/abs/2610.09305v1)

- **arXiv**: `2610.09305v1`  |  **提交日期**: 2026-10-07
- **作者**: Nirmit Desai, Eric Song, Mayank Sengupta, Tejal Bedmutha, Siri Reddy, Sahiti Dharmavaram et al.

Benchmarks for measuring the quality of action-conditioned world models are still evolving and shifting away from visual similarity-based metrics to action-semantic and physically-grounded metrics. However, for domain and task-agnostic action-conditioned world model training, existing benchmarks provide a limited signal. By training and evaluating diffusion world models on CounterStrike gameplay data, we confirm that qualitative playability does not correspond with metrics such as FVD, LPIPS, and JEDi. We term this the Virtual2Real gap. We posit that, in lieu of reliable benchmarks, curating…

---

### [LeCuration: A Tiny World Model as a Data Curation Multi-Tool](https://arxiv.org/abs/2610.09285v1)

- **arXiv**: `2610.09285v1`  |  **提交日期**: 2026-10-07
- **作者**: Mayank Sengupta, Nirmit Desai, Eric Song, Kunal Sawarkar

Many applications of physical AI run within finite or closed physical worlds with a limited set of physical laws governing object behavior. Examples include robots working in a warehouse and agents moving around in a video game. In order to better organize, filter, and curate data for physical AI applications, we propose a new approach centered on the unique settings and physical laws of individual datasets. We train LeCuration, a small world model intended to serve as a data curation tool for a separate, larger downstream model. To build this model, we choose LeWorldModel (LeWM)as our latent…

---

### [Patient, Place, Prior (P$^3$): What Counts as Personalization in Medical World Models?](https://arxiv.org/abs/2610.09194v1)

- **arXiv**: `2610.09194v1`  |  **提交日期**: 2026-10-06
- **作者**: Xingrui Gu, Hanxue Gu, Yuxiang Zhang, Yang Yang

Longitudinal models forecast how a patient's imaging state evolves, but accuracy does not show whether the patient's observed trajectory drives the prediction. A population-average forecast may be useful but cannot establish a patient-specific world-model claim. We introduce Patient, Place, Prior (P$^3$), an audit asking whether a forecast benefits from the patient's longitudinal imaging history (Patient), benefits from patient-matched externally supplied spatial support (Place), and gains predictive value beyond a population-average prediction under matched support and context (Prior). We…

---

### [World Models Dream of Success: Diagnosing and Repairing Failure Insensitivity in Robot World Models](https://arxiv.org/abs/2610.09134v1)

- **arXiv**: `2610.09134v1`  |  **提交日期**: 2026-10-06
- **作者**: Jiuyi Xu, Xiao Hu, Meida Chen, Peng Gao, Yang Ye, Yangming Shi

Robot world models support policy evaluation, planning, and synthetic data generation, but these applications require predictions that distinguish successful actions from failures. Across four released checkpoints from two architecture families, we observe weak sensitivity to action changes and success-like predictions on verified failures. Although recent work incorporates failures into model training, which data can repair released checkpoints without changing their architecture or training objective still remains underexplored. To this end, we introduce CureWM, which constructs alternative…

---

### [Towards Financial World Modeling](https://arxiv.org/abs/2610.09048v1)

- **arXiv**: `2610.09048v1`  |  **提交日期**: 2026-10-06
- **作者**: Humzah Merchant, Alec Guthrie, Simon Mahns, Randall Balestriero, Bradford Levy

Building a world model requires a state representation useful for planning and decision-making---potentially over tasks unknown at training time. In the context of financial markets, planning and decision-making may require a model to reason about market-wide conditions, asset-specific expected returns, liquidity, volatility, and cross-asset relationships. Yet financial representation learning has largely been evaluated on individual predictive tasks, oftentimes on a single time period using comparatively narrow datasets. We address this through three primary contributions. First, we…

---

### [Directed Temporal Representations for Offline Visual Control](https://arxiv.org/abs/2610.08960v1)

- **arXiv**: `2610.08960v1`  |  **提交日期**: 2026-10-06
- **作者**: Chenyang Yuan, Haoyu Wang, Zhuo Sun, Xiaoyuan Cheng

Predictive world models provide compact visual representations for control. Control requires a latent geometry aligned with temporal reachability rather than predictive similarity alone. We introduce Directed Temporal Representations for Control (DTRC), which learns such a geometry from offline visual trajectories on top of frozen LeWorldModel (LeWM) features. DTRC constructs a directed temporal quasimetric over the learned control representation. Short-range temporal offsets calibrate the distance scale. Bootstrapped targets extend temporal reachability across longer horizons.…

---

### [SPW-Nav: A Streaming Panoramic World Model for Language-Guided Navigation](https://arxiv.org/abs/2610.08941v1)

- **arXiv**: `2610.08941v1`  |  **提交日期**: 2026-10-06
- **作者**: Yunheng Liu, Ziqi Cai, Siqi Yang, Yimu Wang, Minggui Teng, Jiaming Tan et al.

Language-guided panoramic video generation benefits various downstream applications, such as interactive 3D scene exploration, virtual reality experiences, and embodied agent training. Existing panoramic generators follow predefined trajectories, and interactive world models act through low-level actions in perspective views. We propose SPW-Nav, a streaming panoramic world model that understands movement instructions and streams one minute of 2K 360-degree video in real time from a single panorama. SPW-Nav interprets each instruction in the previously generated panorama as camera motion.…

---

## 📅 2026-10-07

### [World Models' Last Exam in Physics](https://arxiv.org/abs/2610.08791v1)

- **arXiv**: `2610.08791v1`  |  **提交日期**: 2026-10-06
- **作者**: Mingju Gao, Qingle Liu, Yuzhao Peng, Xinjie Lin, Ziming Qin, Zheng Jiang et al.

Video world models can produce visually convincing yet physically inconsistent sequences, raising concerns about their reliability for prediction and planning in embodied AI systems. Existing evaluations often rely on model-based judgments or reference videos, while direct physical tests largely focus on mechanics. We introduce World Models' Last Exam in Physics, a measurement-based benchmark for evaluating physical consistency in video world models. The benchmark comprises 40 controlled tasks spanning mechanics, optics, fluids, thermal and phase-change phenomena, electromagnetism, and…

---

### [DepthWorld: 3D World Model for Robot Manipulation](https://arxiv.org/abs/2610.08780v1)

- **arXiv**: `2610.08780v1`  |  **提交日期**: 2026-10-06
- **作者**: Jai Bardhan, Josef Sivic, Vladimir Petrik

World models offer a data-driven alternative to traditional simulators for robotics, with applications spanning policy evaluation, improvement, and planning. All of these uses depend on faithful 3D geometry, yet current video-based world models are trained on RGB alone and produce rollouts that look correct frame-by-frame but do not compose into a consistent 3D world. Closing this gap requires progress on two fronts: large-scale 3D supervision for manipulation, and an architecture that can absorb it without disturbing strong pretrained video priors. We introduce a calibration pipeline that…

---

### [CtrlCache: Accelerating Interactive Video World Models with Control-Aware Caching](https://arxiv.org/abs/2610.08777v1)

- **arXiv**: `2610.08777v1`  |  **提交日期**: 2026-10-06
- **作者**: Shangye Song, Dong Gong, Hong Jia, Yun Sing Koh, Xinyu Zhang

Interactive video world models need to generate each video chunk efficiently while responding faithfully to user controls. Many systems use chunk-wise autoregressive generation with few-step denoising, but each chunk still requires several costly denoising iterations. Training-free caching can reduce this cost, yet existing policies make reuse decisions primarily from model-internal denoising dynamics and do not explicitly account for control transitions. Actually, interactive generation explicitly exposes a signal they do not use: the controls for a chunk arrive before it is denoised, so a…

---

### [AdvSim2Real : Training Web Agents Against Adaptive Prompt Injection in a Web World Model](https://arxiv.org/abs/2610.08773v1)

- **arXiv**: `2610.08773v1`  |  **提交日期**: 2026-10-06
- **作者**: Sarim Hashmi, Mukul Ranjan, Kshitij Mishra, Mikhail Kuznetsov, Praneeth Vepakomma, Nils Lukas

Web agents complete user requests by reading and acting on pages that third parties write, so an instruction planted on a page can redirect the agent away from the user's goal. The agent cannot simply ignore the page, because the page also holds the values and controls the task requires. Current defenses fine-tune the agent on injections fixed before training, and attackers that adapt to the trained model bypass them. Adversarial training lets the attacker adapt but keeps the tasks fixed, so a task stops teaching once the agent solves it. We introduce AdvSim2Real, which co-evolves a task…

---

### [WorldSonus: Bringing Sound to Worlds](https://arxiv.org/abs/2610.08760v1)

- **arXiv**: `2610.08760v1`  |  **提交日期**: 2026-10-06
- **作者**: Pengjun Fang, Jingyi Fa, Kam Man Wu, Jiaming Wang, Haoyuan Huang, Yaguang Wu et al.

Recent advances in world models have enabled increasingly realistic visual synthesis. However, these generated environments remain largely silent. Bringing sound to world models poses three core challenges: real-time generation to keep pace with interactive video streams, interactive control to respond to mid-stream sound instructions, and spatially aligned stereo to reflect scene geometry and camera motion. To address these demands, we introduce WorldSonus, an interactive video-to-audio framework designed for real-time spatial sound synthesis in world models. For real-time generation,…

---

### [RIWANav: Recursive World-Action Models with Self-Improvement for Urban Navigation](https://arxiv.org/abs/2610.08640v1)

- **arXiv**: `2610.08640v1`  |  **提交日期**: 2026-10-06
- **作者**: Jing Xie, Shouwei Ruan, Yubin Wang, Yuxiang Zhang, Haitao Yang, Songchang Jin et al.

Long-horizon urban navigation requires sequential local decisions whose errors can compound over time. Imitation learning (IL) rarely learns from failures, while physical trial-and-error reinforcement learning (RL) is costly. Action-conditioned world models can provide imagined feedback by predicting visual consequences for candidate actions. However, a frozen world model may become less reliable as the policy evolves. In this paper, we introduce RIWANAV, a post-training framework that casts the coupled adaptation of a world model and an action model (policy) as task-specific recursive…

---

### [Parallel Predictive World Models for Accurate and Efficient Long-Horizon Planning](https://arxiv.org/abs/2610.08627v1)

- **arXiv**: `2610.08627v1`  |  **提交日期**: 2026-10-06
- **作者**: Wanjin Feng, Baobin Zhang, Ao Yu, Shibo Feng, Xi Wang, Xingyu Gao

Long-horizon world-model planning typically relies on autoregressive rollouts, where predicted states are repeatedly fed back into the model. This preserves temporal structure but creates a horizon-length sequential path and exposes later predictions to recursive decoded-state feedback. We introduce Parallel Predictive World Models (PPWM), which predict a finite-horizon trajectory in parallel while retaining causal interaction among future representations. Each horizon is conditioned on its causal action prefix, and future representations interact before decoding, separating temporal…

---

### [A Belief-State World Model for Catheter Navigation under Sparse Fluoroscopy: A Planar Proof of Concept](https://arxiv.org/abs/2610.08469v1)

- **arXiv**: `2610.08469v1`  |  **提交日期**: 2026-10-06
- **作者**: Damini Rijhwani

Endovascular catheter navigation relies on continuous fluoroscopy, exposing patients and clinical staff to ionizing radiation throughout the procedure. We investigate whether a physics-based world model can sustain the navigation task between deliberately sparse X-ray acquisitions, and whether the model can signal when its internal state estimate is no longer reliable. We formulate sparse-fluoroscopy navigation as a partially observable Markov decision process where a Cosserat rod simulator supplies transition dynamics, sparse noisy projections provide observations, and a particle filter…

---

### [Federated Bayesian Surveillance of Mechanical Thrombectomy Adverse Events: A Population Risk Layer for Surgical Digital Twins](https://arxiv.org/abs/2610.08464v1)

- **arXiv**: `2610.08464v1`  |  **提交日期**: 2026-10-06
- **作者**: Damini Rijhwani

Learned surgical simulators and world models can roll out plausible procedural futures, but they carry no grounded estimate of how often interventional devices actually harm patients. We propose treating population-scale adverse-event surveillance as a distinct belief layer of the surgical digital twin, and we evaluate a federated Bayesian protocol for learning it under formal privacy guarantees. Each site holds per-class Gamma-Poisson posteriors over adverse-event rates and exchanges only Rényi-differentially-private natural-parameter updates. We benchmark on the complete FDA MAUDE cohort…

---

### [How Much Planning Is Enough? Reducing Search and Computation in World-Model Planning](https://arxiv.org/abs/2610.08350v1)

- **arXiv**: `2610.08350v1`  |  **提交日期**: 2026-10-06
- **作者**: Changbai Li, Sirui Li, Yichen Yang, Tongfei Chen, Zichao Feng, Shuwei Shao et al.

Visual world models enable goal-directed control through decision-time action search, but their deployment efficiency is often limited by conservatively large planning budgets. We show that competitive task performance can be achieved without agreement with the Full-budget action, that sufficient budgets vary across model--task pairs, and that iterative planners repeatedly encode solve-invariant context. To address these inefficiencies, we propose {SufficientPlan}, a simple deployment framework that requires no modification to pretrained world models or planner updates. Its {Paired Sequential…

---

### [Learning in Dreams, Winning in Reality: A Continuous Dyna Loop for a Ten-Hero MOBA](https://arxiv.org/abs/2610.08033v1)

- **arXiv**: `2610.08033v1`  |  **提交日期**: 2026-10-06
- **作者**: Jordy Kieto

World models are usually judged from the inside: by prediction loss, by the return a policy earns in imagination, or by how convincing their frames look. We judge one from the outside. We learn a structured, multi-agent world model of a complete ten-hero MOBA (206 units, every hero acting every tick, games of up to 6,000 ticks), train a policy only inside it with 1,400-tick free-running imagined episodes, and measure that policy in the real game against the opponent the game ships with. The real game never provides a gradient; it provides the policy's own games as training data for the world…

---

### [Commit While Futures Agree: Consequence-Aware Adaptive Action Chunking for Robot Manipulation](https://arxiv.org/abs/2610.07949v1)

- **arXiv**: `2610.07949v1`  |  **提交日期**: 2026-10-06
- **作者**: Yuyan Li, Yujia Wang, Yusong Huang, Junjie Yang, Yanggang Sheng, Ziyi Shi et al.

Action-chunking policies predict multi-step control sequences, but a fundamental question remains: how much of a predicted action chunk should be committed before replanning? Existing systems typically execute a fixed-length prefix, implicitly assuming that the same execution horizon remains trustworthy across states. Some adaptive methods estimate this horizon from the similarity or stability of predicted actions. However, different actions may lead to the same successful outcome, whereas similar actions can produce different futures, suggesting that commitment should be determined by…

---

### [Independent Multi-Agent Reinforcement Learning with Counterfactual Semantic-Social World Models](https://arxiv.org/abs/2610.07704v1)

- **arXiv**: `2610.07704v1`  |  **提交日期**: 2026-10-06
- **作者**: Fernando Martinez, Tao Li, Yingdong Lu, Juntao Chen

Fully decentralized multi-agent reinforcement learning (MARL), also referred to as independent learning, requires each agent to learn and act using only its local information and experience, without a centralized critic or inter-agent communication. Such a stringent information structure renders the conventional reward signal ambiguous. A poor return may result from an ineffective ego action, an incompatible teammate response, or an effective opponent response, yet scalar rewards alone do not reveal which explanation is responsible. We argue that agents can learn more effectively by…

---

### [Modeling Latent Disturbances for Robust Decision-Making in World Models](https://arxiv.org/abs/2610.07599v1)

- **arXiv**: `2610.07599v1`  |  **提交日期**: 2026-10-06
- **作者**: Junwon Seo, Andrea Bajcsy

In this paper, we study robust decision-making in the latent space of world models (WMs). Robust optimization is a mathematical framework where, given explicitly specified dynamics and physically meaningful disturbances, a robot can select actions that remain effective even under worst-case disturbances. However, applying this principle to the learned latent space of WMs introduces a fundamental challenge: because WMs have fully learned state spaces and dynamics inferred from high-dimensional observations, it is unclear how to define latent-space disturbances that faithfully represent…

---

### [Preserving Unstable Modes Through Inverse Dynamics in JEPA World Models](https://arxiv.org/abs/2610.07540v1)

- **arXiv**: `2610.07540v1`  |  **提交日期**: 2026-10-06
- **作者**: Leonardo F. Toso, Yann LeCun, James Anderson, Oumayma Bounou

Robotic systems often exhibit unstable modes, along which small perturbations and disturbances can cause unbounded growth unless corrected through feedback. Controlling such systems from high-dimensional visual observations requires representations that preserve these modes. Joint-embedding predictive architectures (JEPAs) provide a natural framework for learning such representations and their dynamics from visual data. However, we demonstrate that next step prediction combined with anti-collapse regularization does not guarantee that controllable unstable modes are preserved: the training…

---

### [GeoWM: Efficient Direct World Modeling in Explicit Geometry](https://arxiv.org/abs/2610.07381v1)

- **arXiv**: `2610.07381v1`  |  **提交日期**: 2026-10-05
- **作者**: Mehrdad Noori, Guile Wu, Sam Hosseini, Dongfeng Bai

Modeling 3D scene geometry and its evolution over time is essential for autonomous driving and robotics. A common paradigm is to use world models to predict future images or latent representations of the environment and subsequently recover geometry from these predictions. However, this paradigm does not explicitly model geometric structure and typically relies on recursive rollouts to reach longer prediction horizons, leading to error accumulation and increasing computational cost. To address these limitations, we present GeoWM, a geometry world model that directly forecasts future scene…

---

### [Tracking Is Not Permanence: What Video World Models Keep of a Hidden Object](https://arxiv.org/abs/2610.07355v1)

- **arXiv**: `2610.07355v1`  |  **提交日期**: 2026-10-05
- **作者**: Peng Xie, Amr Alanwar

Video world models track objects they can see; we ask what they keep of objects they cannot. We hide an object from a frozen V-JEPA 2 predictor and compare its prediction for the hidden region with the encoder's representation of two worlds that differ only inside that region. The predictor's decision keeps a stationary object in part and one carried inside a container not at all, and loses a moving one within 0.3 s (0.5 s under V-JEPA's own tube mask; ViT-H keeps it to 1.1 s at pretraining's 90% masking ratio); in projection a trace remains, below the midpoint, at 14-60% of what a baseline…

---

### [TAPDreamer: Transferable Adversarial Patches for World Action Models](https://arxiv.org/abs/2610.06814v2)

- **arXiv**: `2610.06814v2`  |  **提交日期**: 2026-10-05
- **作者**: Xuanyu Lu, Fengqing Jiang, Kaiyuan Zheng, Yichen Feng, Yaorui Ding, Yuetai Li et al.

World models learn to predict how their environment will evolve, making them an important foundation for general-purpose robotic control. Yet world action models depend on camera inputs whose manipulation can corrupt the visual representations used across tasks and action policies. Existing attacks on these models optimize against the victim's actions or predicted futures and therefore require access to target-model outputs. In this paper, we propose an attack, TAPDreamer, against world action models that instead uses a public encoder alone to construct a fixed local perturbation that…

---

### [H-JEPA: End-to-End Learning of Hierarchical World Models for Visual Planning](https://arxiv.org/abs/2610.06805v1)

- **arXiv**: `2610.06805v1`  |  **提交日期**: 2026-10-05
- **作者**: Wancong Zhang, Basile Terver, Michael Rabbat, Yann LeCun, Randall Balestriero

Long-horizon planning with latent world models requires reasoning across timescales and levels of abstraction. Existing task-agnostic JEPA world models predict and plan at a single timescale or with multiple horizons in one shared latent space. We introduce H-JEPA, an end-to-end recipe for training a hierarchy of action-conditioned JEPAs in which each level predicts farther ahead in its own learned latent space. Planning proceeds top-down: the top level optimizes progress toward the goal, and each level's predictions become subgoals for the planner below it. When factors in the data evolve at…

---

### [Considering Context: When World Models Need Context Encoders](https://arxiv.org/abs/2610.06651v1)

- **arXiv**: `2610.06651v1`  |  **提交日期**: 2026-10-05
- **作者**: Oleg Smirnov, Sofiane Ennadir, John Pertoft, Bjartur Hjaltason, Sara Karimi

Methods for generalization in model-based reinforcement learning typically assume that an agent cannot recover the latent context governing the environment dynamics from its own experience, and therefore supplies it externally. We formalize and test this assumption with \emph{predictive sufficiency}, which quantifies what access to the context adds to next-step prediction under the visitation distribution an agent induces, and separates that quantity into a history-recoverable part, a residual requiring the true context, and the deficit added by a finite model. We classify context-aware…

---

### [Mind the Execution Gap: Action-Semantic Mismatch in World-Model Control](https://arxiv.org/abs/2610.06582v1)

- **arXiv**: `2610.06582v1`  |  **提交日期**: 2026-10-05
- **作者**: Shengtao Wen, Xiang Chen, Yu Tian, Lingbing Guo, Lina Gong, Sheng-Jun Huang

World-model controllers rely on action-conditioned dynamics for prediction and planning, yet real control systems often execute commands asynchronously due to communication delay, packet loss, reordering, and actuator buffering. We study how asynchronous execution changes the action semantics assumed within world-model controllers, rather than treating it only as an external control disturbance. Through controlled interventions, we identify two architecture-dependent failure modes: planning-based controllers such as TD-MPC2 suffer from a future-action timeline mismatch between imagined and…

---

### [KineWorld: Action-Induced Transport Fields for Embodied World Modeling](https://arxiv.org/abs/2610.06349v1)

- **arXiv**: `2610.06349v1`  |  **提交日期**: 2026-10-05
- **作者**: Ziying Song, Yuchen Liu, Zhuoran Xu, Ziyang Liu, Jian Jin, Jiangtao Su et al.

Embodied world models predict the visual consequences of candidate actions before execution. However, existing action-conditioned world models often adopt uniformly weighted visual generation objectives that can be misaligned with embodied prediction needs. Even with explicit motion conditioning, these objectives can underemphasize spatially sparse changes that are critical to interaction. We propose KineWorld, a transport-aware world-modeling framework that extends robot kinematics from motion conditioning to the spatial allocation of generative supervision. Kinematic Transport Lifting (KTL)…

---

### [Generative World Models Enable Predictive Control of Laser Melt Pool Dynamics](https://arxiv.org/abs/2610.06250v1)

- **arXiv**: `2610.06250v1`  |  **提交日期**: 2026-10-05
- **作者**: Yiyang Yan, Markus Bambach, Mohamadreza Afrasiabi

World models, which learn how environments respond to actions, are emerging as a powerful paradigm for planning through imagined futures, transforming decision-making across games, robotics and autonomous driving. Bringing this capability to manufacturing could enable process decisions on timescales inaccessible to high-fidelity simulation. Here we introduce a generative world model for localized highly dynamic laser melt pool that predicts evolution from histories of temperature and phase morphology under candidate actions. Its generative latent dynamics capture the effects of unresolved…

---

### [Ultrasound Operator Guidance Using World Modeling and Retrieval Based Action Planning](https://arxiv.org/abs/2610.06008v1)

- **arXiv**: `2610.06008v1`  |  **提交日期**: 2026-10-05
- **作者**: Noortje I. P. Schueler, Hans van Gorp, Ruud J. G. van Sloun

Ultrasound is widely used, but acquisition quality is heavily dependent on the operator's knowledge and expertise. With demand for examinations outpacing the supply of trained sonographers, operator-guidance systems aim to close this gap by instructing a less trained user how to move the probe toward a target view. In this paper, we propose a retrieval-induced latent transition model for ultrasound acquisition dynamics, formulating ultrasound operator guidance as multi-step planning and retrieval in a world model. Using a V-JEPA 2.1 backbone, observations are first encoded into a latent space…

---

### [EpicWorldModel: Exploration-driven Planning with Latent World Models](https://arxiv.org/abs/2610.05996v1)

- **arXiv**: `2610.05996v1`  |  **提交日期**: 2026-10-05
- **作者**: Bowen Feng, Julian Ost, May Mei, Anirudha Majumdar, Felix Heide

Latent world models based on Joint-Embedding Predictive Architecture (JEPA) are deterministic by design. While successful in fully observable scenarios, this paradigm breaks down when past observations and actions lead to multiple plausible future possibilities, e.g., due to occlusion. We introduce EpicWorldModel, a framework to train stochastic JEPAs for environments and tasks with inherent uncertainty under partially observability. We jointly train the EpicWorldModel predictor with its latent representation space to directly predict multiple potential future states using a flow-matching…

---

### [MiniCorp: The Last Mile of the AI Agent Firm](https://arxiv.org/abs/2610.05912v1)

- **arXiv**: `2610.05912v1`  |  **提交日期**: 2026-10-05
- **作者**: Jingying Zeng, Zhenwei Dai, Jinning Li, Changho Shin, Dylan Zhang, Yuxuan Lu et al.

The last mile toward enterprise AGI is a company that runs itself. Training and adapting such agents require longitudinal enterprise data, which remain scarce, costly to acquire, and often restricted by privacy constraints. Historical archives are also frequently incomplete and record only what actually happened. They cannot show the outcomes of alternative decisions. We introduce MiniCorp, an office simulator for studying how agents can collectively run a company while generating enterprise data at scale. Using an e-commerce company as a demonstration, MiniCorp connects two interacting…

---

### [Imagine to Act: High-Fidelity Data Synthesis via Image Editing World Model for Scalable GUI Agent Training](https://arxiv.org/abs/2610.05861v1)

- **arXiv**: `2610.05861v1`  |  **提交日期**: 2026-10-05
- **作者**: Yongxin Ning, Runliang Niu, Qianli Xing, Zhiyi Duan, Qingzu He, Pan Wang et al.

Graphical User Interface (GUI) agents have emerged as a promising paradigm for automating complex digital workflows across diverse applications. However, training highly capable and generalizable agents fundamentally relies on massive, high-fidelity visual-action trajectories, which are notoriously difficult to acquire. While human demonstrations are unscalable, existing GUI world models rely on text descriptions or HTML rendering, discarding crucial pixel-level visual details like icons and layout styles. To address this issue, we introduce Infinite-Dreamer, a simulation-free data synthesis…

---

### [HLA-WM: Hybrid Linear Attention for Long-Horizon Video World Models](https://arxiv.org/abs/2610.05739v1)

- **arXiv**: `2610.05739v1`  |  **提交日期**: 2026-10-05
- **作者**: Zhuokun Chen, Feng Chen, Xi Lin, Xiyu Wu, Jiahao He, Jianfei Cai et al.

Long-horizon video world models require persistent memory to preserve scene consistency over extended rollouts. Softmax attention retains the full generation history through a growing KV cache, whereas recurrent linear attention compresses history into fixed-size states with substantially lower memory cost. However, we identify severe long-range forgetting in Gated DeltaNet (GDN), where information from distant but relevant scenes is progressively attenuated by subsequent state updates. To address this limitation, we propose HLA-WM, a training-free hybrid linear-attention framework that…

---

### [When Low Prediction Error Misleads Planning: Diagnosing Representation, Dynamics, and Decision Failures in Latent World Models](https://arxiv.org/abs/2610.05550v1)

- **arXiv**: `2610.05550v1`  |  **提交日期**: 2026-10-04
- **作者**: Rui Min, Xianyao Li, Fang Xu, Jing Du

The component that dominates a latent world model's prediction error need not be the one whose repair most improves action selection. We show this by comparing action sequences from identical physical starts and separating endpoint error into a candidate-pool center and action-relative responses. Across four model families and four tasks, a confirmation pool of 256 new starts per task and 300 shared candidates per start shows that center error dominates MSE in 14/16 model-task cells. Yet in six of these cells, an oracle that corrects only the action-relative responses yields better physical…

---

### [FLEX-WAM: Flexible Block-Causal World-Action Models for Long-Horizon Imagination and Planning](https://arxiv.org/abs/2610.05483v1)

- **arXiv**: `2610.05483v1`  |  **提交日期**: 2026-10-04
- **作者**: R. Khorrambakht, Joseph Amigo, Félix Lebel, Leon Seetoo, Jean Ponce, Zhenzhen Li et al.

World--action models (WAMs) promise a unified model that predicts action-conditioned futures, generates feasible actions, and supports planning in imagination. However, existing joint video--action models often use computationally heavy, fixed-horizon backbones ill-suited to streaming inference and stable long-horizon open-loop rollouts. We introduce FLEX-WAM, a Flexible and Efficient Block-Causal World--Action Model for unified simulation and policy inference. FLEX-WAM supports variable-length contexts and non-causal prediction horizons, as well as infinite autoregressive generation frame by…

---

### [Artemis: Geometry-Grounded Multi-Agent Driving World Models with Shared 3D State and Progressive Memory Update](https://arxiv.org/abs/2610.07031v1)

- **arXiv**: `2610.07031v1`  |  **提交日期**: 2026-10-04
- **作者**: Sitian Shen, Jiuming Liu, Mengmeng Liu, Yian Wang, Michael Ying Yang, Francesco Nex et al.

Recent video world models have witnessed the paradigm shift from single-agent to multi-agent involvements, which can reveal more complicated dynamics and cross-agent interaction in the real world. However, existing approaches commonly adopt implicit inter-agent communications via cross attention, which lack explicit geometry constraints and unified 3D state, thereby leading to poor multi-view consistency and struggling with recovering out-of-sight agents. In addition, most of them assume a static background, failing to represent uncontrolled background dynamics. To address these problems, we…

---

### [BeliefGraph-JEPA: Structured Latent World Models for Action-Conditioned Time Series](https://arxiv.org/abs/2610.05409v1)

- **arXiv**: `2610.05409v1`  |  **提交日期**: 2026-10-04
- **作者**: Yue Li, Kangqi Ni, Zhen Tan, Tianlong Chen

Action-conditioned time-series forecasting requires accounting for how future actions and exogenous forcings influence multiple targets through partially observed effects with different delays and persistence. Direct conditioning leaves the evolution and target-specific influence of these effects implicit in the predictor, while static relational graphs specify connections without tracking evolving effects. This motivates representing future-driver influence through structured latent states that evolve over the forecast horizon and route information to individual targets. We introduce…

---

### [Optimal Control with Learned Critics under Unmodeled State Dependencies](https://arxiv.org/abs/2610.05359v1)

- **arXiv**: `2610.05359v1`  |  **提交日期**: 2026-10-04
- **作者**: Philipp Schoch, Markus Ryll

Model Predictive Control (MPC) provides a structured and constraint-aware mechanism for decision-making, but its reliance on optimization-friendly analytical dynamics models limits its use in tasks with contacts and other hard-to-model state dependencies. Model-free reinforcement learning avoids explicit modeling assumptions but typically requires large amounts of interaction data. We present a learning-based MPC framework that combines the data efficiency and structure of local model-based planning with learned components that compensate for incomplete dynamics and finite-horizon myopia. The…

---

### [Pythia: Toward Foundation World Models for Multimodal Time Series](https://arxiv.org/abs/2610.05240v1)

- **arXiv**: `2610.05240v1`  |  **提交日期**: 2026-10-04
- **作者**: Xilin Dai, Hongzhou Chen, Yifan Hu, Yiding Liu, Zewei Dong, Jiang-Ming Yang

Time-series foundation models offer a unified approach to forecasting across heterogeneous domains. Textual context and auxiliary observations provide complementary information about temporal dynamics, yet reusable multimodal predictive representations remain underexplored. We introduce Pythia, a foundation world model that learns context-conditioned latent dynamics across datasets through a joint-embedding predictive architecture. A stop-gradient numerical reference guides contextual corrections to predicted future states. A separate probabilistic decoder then adapts to the frozen predictive…

---

### [Same Predictions, Different Harms: Causal Auditing of Patient World Models](https://arxiv.org/abs/2610.05198v1)

- **arXiv**: `2610.05198v1`  |  **提交日期**: 2026-10-04
- **作者**: Yicheng Qi, Xiyi Xiong

Patient world models used for clinical trial simulation can agree on transition kernels and arm-specific risks, yet disagree on the fraction of patients harmed by switching treatment---the counterfactual quantity that matters for intervention-aware reasoning. We audit this reliability gap in a two-stage shared-response SCM: a categorical intermediate health state is followed by common terminal care. Under independent stages, the sharp harm interval has closed-form endpoints for at most three intermediate states, with an exactness boundary at four states. Declared dependence and…

---

### [How Long, Not How Close: A Learned Temporal Metric for Planning in Latent World Models](https://arxiv.org/abs/2610.04988v1)

- **arXiv**: `2610.04988v1`  |  **提交日期**: 2026-10-04
- **作者**: Lama Moukheiber, Haotian Xue, Yongxin Chen

Latent world models plan by rolling a frozen predictor forward under candidate action sequences and ranking the candidates by the latent distance between their imagined end state and the goal. However, this ranking breaks down when the goal lies several plans away, because the latent distance measures how closely an end state resembles the goal rather than how far it remains from reaching it. To address this, we propose TEMPO, a temporal-distance planning objective that leaves the world model untouched, learns only from the demonstrations already used to train it, and adds negligible cost to…

---

### [Software World Models: From Consequence Prediction to Decision Value](https://arxiv.org/abs/2610.04940v1)

- **arXiv**: `2610.04940v1`  |  **提交日期**: 2026-10-04
- **作者**: Tongli Su, Yuntong Hu, Liang Zhao, Bowen Zhu, JayaSai Somasundaram, Hasibul Haque

A coding agent may safely modify one repository while silently breaking downstream services, libraries, or datastores that depend on it. Exhaustively running integration tests after every agent action is impractical, so the agent must predict these failures before executing them. Existing software world models predict the agent's own observations, while static change-impact analysis only identifies where a change may propagate. We instead introduce the Software World Model (SWM), which models the broader system affected by a code change and predicts its blast set: the components that the…

---

## 📅 2026-10-05

### [What Should World Models Forget? Stratified Retention for Continual Adaptation](https://arxiv.org/abs/2610.03713v1)

- **arXiv**: `2610.03713v1`  |  **提交日期**: 2026-10-02
- **作者**: Nishit Anand, Ramani Duraiswami, Dinesh Manocha

Continual learning treats degradation on previously seen data as evidence of failure, a convention inherited from settings with a stationary prediction target, where a correct label remains correct indefinitely. World models do not satisfy this condition. Their prediction target is the environment, which changes, so knowledge that was accurate when acquired may later become false, and discarding it is required behavior rather than a defect. Non-stationary ground truth is well studied in the concept drift literature and in the temporal factuality of language models, but has not been formulated…

---

### [World Embedding Benchmark](https://arxiv.org/abs/2610.03632v1)

- **arXiv**: `2610.03632v1`  |  **提交日期**: 2026-10-02
- **作者**: Yiqi Liu, Ruifeng Yuan, Yang Wang, Long Li, Fengyu Cai, Hou Pong Chan et al.

Physical fidelity has received increasing attention in world models and video generation, yet how video representations encode physical information remains less understood. We introduce the World Embedding Benchmark, comprising 8,000 controlled simulation cases from 80 families spanning fluid mechanics, solid mechanics, dynamics, and optics & electromagnetism. Each case pairs a rendered video with simulation-derived physical annotations, supporting three complementary tasks: text-video retrieval, physical-property regression, and multiple-choice video-description pair classification. We use…

---

### [AVL-JEPA: Preventing Causal Dynamics Information Collapse In Joint Embedding Predictive Architecture World Models](https://arxiv.org/abs/2610.03587v1)

- **arXiv**: `2610.03587v1`  |  **提交日期**: 2026-10-02
- **作者**: Yikang Qiao, Ling Zhang, Ziying Song, Duan Huang

Joint embedding predictive architectures (JEPAs) predict future latent representations without reconstructing observations, enabling world models to focus on high-level semantic dynamics. However, a JEPA can preserve high dimensional visual information while discarding information about the physical consequences of actions. We call this failure mode causal dynamics information collapse and propose action-grounded vision-invariance latent (AVL) to prevent this collapse. We first use the executed action as an auxiliary dynamics anchor that encourages the model to preserve dynamics information,…

---

### [EVEWorld: Physical Evolution Supervision for Embodied World Models](https://arxiv.org/abs/2610.03374v1)

- **arXiv**: `2610.03374v1`  |  **提交日期**: 2026-10-02
- **作者**: Kaiqi Wang, Songxin Zhang, Zejian Xie, Xiao Xiong, Zhuoyang Song, Ziwei Wu et al.

Embodied world models enable scalable simulation of embodied interactions for robot learning. However, existing models are prone to Model Laziness, as they focus on visual fidelity at the expense of physical reasoning and lack process-level supervision over the temporal dynamics of manipulated objects. In this work, we propose EVEWorld, a physical evolution-supervision framework for physically consistent target evolution. EVEWorld consists of two components: Instance-Guided Restoration (IGR) and Temporal Instance Alignment (TIA). First, IGR promotes instance consistency through restoration…

---

### [ReFract: Benchmarking Perspective Awareness in Language Model Agents with Text World Models](https://arxiv.org/abs/2610.03356v1)

- **arXiv**: `2610.03356v1`  |  **提交日期**: 2026-10-02
- **作者**: Hainiu Xu, Vítor N. Lourenço, Mohnish Dubey, Yunfei Bai, Yulan He, Caroline Catmur et al.

Large Language Model (LLM) agents are increasingly deployed in high-stakes settings such as industrial maintenance and equipment fault troubleshooting, where workers occupy a variety of roles. A capable agent must therefore act in a way that is calibrated to user's role: taking actions and providing information that respect the role's knowledge and capability boundaries. Unlike coding, where mistakes are usually recoverable, agent responses in these settings are enacted on physical equipment, and can therefore cause irreversible equipment damage, production loss, or personnel harm. Existing…

---

### [Does Physics Live in the Activations? Localizing Physical Quantities in Video Diffusion Models](https://arxiv.org/abs/2610.03154v1)

- **arXiv**: `2610.03154v1`  |  **提交日期**: 2026-10-02
- **作者**: Jonas Kneifl, Jakub Skalski, Bartłomiej Twardowski, Kamil Deja

Video generation models produce strikingly realistic sequences and are increasingly proposed as world models, yet recent benchmarks reveal pronounced deficits in their physical reasoning. This raises the question of whether these models internalize physical principles or merely reproduce familiar motion patterns. We address this by probing internal representations of video Diffusion Transformers (DiTs) for simulator-derived ground-truth physical quantities spanning kinematic motion and rigid-body dynamics under gravity and contact. We find that these quantities are linearly decodable with…

---

### [Keeping JEPA World Models Plannable When Little of the Frame Moves](https://arxiv.org/abs/2610.03137v1)

- **arXiv**: `2610.03137v1`  |  **提交日期**: 2026-10-02
- **作者**: Florian Strohm, Patrick Wagner, Jannik Schwab, Marco Huber

Specifying a goal in language rather than as a goal frame is a natural interface for planning with a latent world model, but testing it needs scenes in which language must discriminate between several objects. We build SLIM, a pushing benchmark with several small objects and paired visual and language goals on identical scenes. On SLIM a LeWM world model that solves PushT succeeds on under 1% of trials, although a scripted controller with simulator state solves every tier. Probes locate the failure in the encoder: its latent is nearly action-insensitive, neither pusher nor object positions…

---

### [Learning Transferable Policies from Action-free Time Series Through Dynamical Embeddings](https://arxiv.org/abs/2610.03065v1)

- **arXiv**: `2610.03065v1`  |  **提交日期**: 2026-10-02
- **作者**: Niklas Emonds, Georgia Koppe

Learning control from action-free recordings is challenging because intervention effects are unobserved and policies may exploit errors in reconstructed dynamics. We present a hierarchical model-based reinforcement learning framework that uses shared structure across related systems to learn system-specific control policies from action-free recordings. A hierarchical dynamical system reconstruction model captures shared dynamics and individual variation through low-dimensional embeddings. These embeddings are then reused to parameterize shared policy and value networks, linking differences in…

---

### [Understanding Trajectory Heterogeneity in Federated World Model Learning](https://arxiv.org/abs/2610.02957v1)

- **arXiv**: `2610.02957v1`  |  **提交日期**: 2026-10-02
- **作者**: Yipan Wei, Zhaokun Yan, Ziming Hong, Jiaqi Wu, Lixu Wang

World models learn state evolution from trajectories, making access to temporal context a central training requirement. Federated learning can use distributed records, while ownership boundaries within a trajectory restrict the examples each client can construct. Our study benchmarks this cross-time setting through hourly action-conditioned clinical prediction on eight MIMIC-IV disease cohorts, comprising 40.87 million transition memberships. We specify severity-based client ownership, patient-separated construction, local history and future-window rules, and paired rollout evaluation from…

---

### [Counterfactual Action Evaluation, Observation Bottlenecks, and Representation Geometry in Joint-Embedding Predictive World Models](https://arxiv.org/abs/2610.02860v1)

- **arXiv**: `2610.02860v1`  |  **提交日期**: 2026-10-02
- **作者**: Arjun Subramanian

Low latent prediction error does not establish that a world model distinguishes the consequences of its actions. We introduce an evaluation protocol that traces the same intervention through simulator state, raster observations, target embeddings, and predictor outputs. Exact simulator-state forks in a controlled deformable-physics testbed reveal distinct bottlenecks. Changed commands alter particle motion, yet 41.5% of one-step raster pairs are identical. Observation loss is not the whole explanation: among 579 high-visibility counterfactuals, median predictor-to-target response is 0.0051…

---

### [VIGOR: Zero-Shot Visual Generalization via Latent-Space Consistency in Model-Based Reinforcement Learning](https://arxiv.org/abs/2610.02801v1)

- **arXiv**: `2610.02801v1`  |  **提交日期**: 2026-10-02
- **作者**: Mingyu Park, Samyeul Noh, Hyun Myung, Donghwan Lee

Model-based reinforcement learning (MBRL) achieves strong sample efficiency by planning within learned latent dynamics, yet its performance degrades substantially under unseen visual distractions such as background variations, lighting changes, or camera shifts. Unlike model-free RL, where encoder perturbations affect only single-step predictions, MBRL suffers from a two-level vulnerability: visual distractions first push encoder outputs out of distribution, and these errors then compound through recursive latent rollouts over the planning horizon. We propose visual generalization via…

---

### [SymRegFlow: Symmetry-Regularized Flow Matching for Video World Models](https://arxiv.org/abs/2610.02726v1)

- **arXiv**: `2610.02726v1`  |  **提交日期**: 2026-10-02
- **作者**: Xi Ye, Yuzhu Wang, Xiaoyang Liu, Jiayi Wang, Yangyang Xu, Ruyu Wang et al.

Flow-matching-based multi-view world models generate realistic videos, but are commonly restricted to fixed camera rigs. Extending them to continuously varying camera poses requires paired pose--video observations with dense pose coverage, which are costly to acquire. We introduce \emph{SymRegFlow}, a symmetry-regularized flow-matching framework for multi-view-consistent video generation across continuous viewpoints without ground-truth novel-view RGB supervision. For each target pose, SymRegFlow geometrically warps source views into noisy anchors and combines masked dual-anchor supervision…

---

### [DeltaWorld: Physically Consistent Interactive World Simulators via Action-Conditioned Latent Increment Learning](https://arxiv.org/abs/2610.02691v1)

- **arXiv**: `2610.02691v1`  |  **提交日期**: 2026-10-02
- **作者**: Boyuan Hou, Xiaoge Cao, Chaofan Zhang, Shuo Wang, Shaowei Cui

Interactive world simulators can provide scalable environments for robot planning, policy training, and evaluation by predicting action consequences while reducing reliance on repeated physical rollouts. To serve these applications, they must generate future image sequences that respond faithfully to robot actions and preserve the dynamics of robot-object interactions over long horizons. However, existing world models typically predict the entire next latent state and often fail to capture subtle changes induced by robot actions. Such omissions can produce physically implausible outcomes,…

---

### [SpectralCache: Accelerating Diffusion-Based World Models via Spectral Feature Caching](https://arxiv.org/abs/2610.02660v1)

- **arXiv**: `2610.02660v1`  |  **提交日期**: 2026-10-02
- **作者**: Zhendong Mi, Pu Zhao, Ziyu Hu, Xiaodong Yu, Yanzhi Wang, Grace Li Zhang et al.

Diffusion-based world models enable high-quality interactive environment generation but suffer from substantial inference overhead due to repeated Transformer evaluations during denoising. Existing caching methods mainly exploit temporal redundancy at the feature or token level, leaving the underlying mathematical structure of diffusion features largely unexplored. In this work, we reveal that world-model features exhibit highly stable singular subspaces across nearby denoising steps, while their singular values follow predictable evolution patterns. Building on this observation, we propose…

---

### [CuBEs: Culturally-Situated Behavioral Evaluations and the Limitations of Culture-Blind LLM Judges](https://arxiv.org/abs/2610.02622v1)

- **arXiv**: `2610.02622v1`  |  **提交日期**: 2026-10-02
- **作者**: Hoda Ayad, Tanu Mitra, Abhishek Mukherji

Evaluating the occurrence and triggers of large language model (LLM) behaviors - such as sycophancy, self-preference, or over-confidence - is critical for predicting real-world model deployment risks. However, existing situated behavioral evaluations typically ignore cultural context, limiting their generalizability across an increasingly global user base. To address this gap, we propose CuBEs - Culturally-situated Behavior Evaluations that probe for response patterns across diverse user cultures. We first extend an automated testing pipeline to inject cultural context into behavioral test…

---

## 📅 2026-10-02

### [ROWBench: Do Video Models Render What the Program Specifies?](https://arxiv.org/abs/2610.02205v1)

- **arXiv**: `2610.02205v1`  |  **提交日期**: 2026-10-01
- **作者**: Zheng-Hui Huang, Guixu Lin, Yu-Ju Tsai, Jian-Kai Zhu, Fengbo Lan, Yu-Lun Liu et al.

Programmable world models separate executable dynamics from visual generation, offering a promising foundation for next-generation game engines. However, their visual adherence to explicit rules and interactions remains insufficiently evaluated. Existing benchmarks assess visual quality, controllability, and instruction or physical adherence, but rarely test fidelity to fine-grained, program-specified world events. We introduce PROWBench, comprising 170 programmatically constructed episodes and 600 proxy videos covering diverse scenes and interactions. PROWBench logs entity states and…

---

### [World Observer: Joint Actor-Observer Generation for Persistent World Modeling](https://arxiv.org/abs/2610.02162v1)

- **arXiv**: `2610.02162v1`  |  **提交日期**: 2026-10-01
- **作者**: Hyunwook Choi, Dahyun Chung, Hyunsung Kim, Siyoon Jin, Jinhyeok Choi, Junyoung Seo et al.

How can a world model continuously observe regions beyond the actor's current view? Video world models simulate how an environment evolves from an agent's actions, yet remain actor-centric. Once an object leaves the actor's view, they lose direct evidence of its evolution, often failing to preserve its state and dynamics upon re-entry. To address this, we introduce World Observer, which decouples observing from acting by jointly generating a perspective actor for the agent-centric view with one or more panoramic observers that watch selected world regions. This allows objects that leave the…

---

### [4Director: Controlling Video World Models with Rigid 3D Geometry](https://arxiv.org/abs/2610.02160v1)

- **arXiv**: `2610.02160v1`  |  **提交日期**: 2026-10-01
- **作者**: Wei Cao, Hao Zhang, Vikram Voleti, Yuqun Wu, Mallikarjun B R, Shimon Vainer et al.

Precise control over camera and object motion is essential for professional video production. Existing methods control objects only coarsely, through image-plane cues that are ambiguous in depth and rotation or through 3D tracks and blobs that lack complete geometry and lose consistency across viewpoint changes. We introduce 4Director, a video world model conditioned on an explicit 4D scene representation: each object is reconstructed once from the input image as a canonical mesh and moved by one prescribed rigid transformation per frame. This representation provides an intuitive 3D control…

---

### [Latent-Foresight: End-to-End Learning Predictable Representations for Latent World Models](https://arxiv.org/abs/2610.01942v1)

- **arXiv**: `2610.01942v1`  |  **提交日期**: 2026-10-01
- **作者**: Efstathios Karypidis, Spyros Gidaris, Nikos Komodakis

Predicting the future evolution of a scene is a fundamental capability for world modeling. Recent work has shown that operating in the feature space of Vision Foundation Models (VFMs) yields semantically rich representations that support diverse future scene understanding tasks. However, existing approaches rely on two-stage pipelines, where VFM features are first compressed using fixed dimensionality reduction (e.g., PCA) or independently trained autoencoders, and a separate predictor is trained on top of the resulting frozen latent space. This decoupling between representation learning and…

---

### [On the Divergence of Accuracy and Mechanism Consistency in Time Series World Models](https://arxiv.org/abs/2610.01842v1)

- **arXiv**: `2610.01842v1`  |  **提交日期**: 2026-10-01
- **作者**: Haochen Zhang, Jiaheng Guo, Zhen Xu, Zachary Plotkin, Nicholas Konz, Zhen Tan et al.

A time series world model (TSWM) predicts a controlled system's state from its observed history and planned actions and exogenous inputs. Current approaches build forecasters with actions as covariates, trained and evaluated on prediction error under the executed plan. Yet world models compare unexecuted plans, but their responses to changed plans remain untested. We ask which design choices matter and whether accurate forecasters respond to changed plans as real systems do. We address both with a formalization and benchmark. The formalization separates state, actions and exogenous inputs,…

---

### [Oneira: From Open-Ended Generation to Open-World Interaction in Video World Models](https://arxiv.org/abs/2610.01614v1)

- **arXiv**: `2610.01614v1`  |  **提交日期**: 2026-10-01
- **作者**: Xindi Yang, Baolu Li, Liam Lee, Zhenfei Yin, Songxin Zhang, Zhuoyang Song et al.

Generative video world models can now synthesize open-ended environments that agents can navigate and interact with in simple ways. Yet open-ended generation does not imply full interaction: as a generated world expands, newly created content through navigation should expand what the agent can act upon, and as the agent changes the world, those changes should become persistent parts of the environment rather than transient visual effects. We characterize these two requirements as Open-World Interactivity, where newly generated or encountered entities are incorporated into the actionable…

---

### [Completion Aware Guidance for World Action Models](https://arxiv.org/abs/2610.01559v1)

- **arXiv**: `2610.01559v1`  |  **提交日期**: 2026-10-01
- **作者**: Seungyeon Kim, Junhoo Lee, Baekseung Kim, Minkyu Kim, Nojun Kwak

World Action Models (WAMs) predict visual futures and robot actions, yet they remain susceptible to task-incomplete imagination, where plausible, action-consistent predictions omit the transition needed for task completion. In this paper, we show that this failure is not inherent to the world model backbone, but emerges when adapted for short-chunk control, which can repeatedly favor plausible local continuations over task-completing transitions. To address this, we introduce Completion Aware Guidance (CAG), a training-free sampling method that guides generation toward task completion. Across…

---

### [Learning Commute-Time-Preserving World Models for Planning](https://arxiv.org/abs/2610.01373v1)

- **arXiv**: `2610.01373v1`  |  **提交日期**: 2026-10-01
- **作者**: Michael Hauri, Peter Buttaroni, Fabian A. Mikulasch, Friedemann Zenke

World models allow agents to plan in latent space by choosing a sequence of actions that most reduces the distance to a given goal state. Thus, planning can benefit from latent representations whose distances mirror commute-times in the environment. The spectral embedding space of the graph Laplacian provides such a representation, if it obeys a specific eigenvalue-dependent scaling. Unfortunately, instantiating the graph Laplacian is intractable in large, continuous environments. Self-supervised learning offers a natural route to such commute-time-preserving embeddings at scale. However,…

---

### [Cross-entropy optimization with prioritized constraints](https://arxiv.org/abs/2610.01319v1)

- **arXiv**: `2610.01319v1`  |  **提交日期**: 2026-10-01
- **作者**: Francisco Roldan Sanchez, Pau de las Heras Molins, David Fridovich-Keil, Georgios Bakirtzis

When constraints conflict, an optimizer must determine which requirements to preserve and which to relax. On the one hand, a priority ordering specifies which requirements take precedence. On the other hand, penalty-based formulations encode their relative importance through numerical weights. Depending on these weights, a solution can improve its weighted score while violating intended priorities. We introduce TierCEM, a variant of the cross-entropy method that incorporates strict constraint priorities directly into elite selection without requiring per-constraint importance weights. TierCEM…

---

### [Supervise What Decides Success: Criterion-Aligned Auxiliary Losses for Latent World-Model Planning](https://arxiv.org/abs/2610.01224v1)

- **arXiv**: `2610.01224v1`  |  **提交日期**: 2026-10-01
- **作者**: Takumi Hara, Kanata Suzuki

Latent world models plan by scoring candidate action sequences with distances in latent space. However, task success is judged by physical quantities, which we call the success-criterion quantities. In all four latent world models we examine, the end-effector position is encoded in the latent state with an error larger than the success criterion allows. Such a latent state cannot separate successful candidates from failing ones. We propose an auxiliary loss that uses success-criterion quantities as training targets, whereas existing latent world models take them only as inputs. During…

---

### [AutoGUIWorld: Image Generators as Visual World Models for GUI Agent](https://arxiv.org/abs/2610.01215v1)

- **arXiv**: `2610.01215v1`  |  **提交日期**: 2026-10-01
- **作者**: Cheng Yang, Yifan Wu, Yutao Huang, Zhaohua Zhang, Beiduo Chen, Muxi Chen et al.

GUI agents require high-quality interaction trajectories to learn how software environments respond to actions, maintain state, and support multi-step workflows. However, the diversity of available trajectories is constrained by the applications, interface states, and workflows accessible in the underlying environments. Expanding this coverage requires deploying increasingly diverse and complex software, with specialized applications imposing additional installation, configuration, and runtime costs. We introduce AutoGUIWorld, a data generation framework that combines the visual priors of…

---

### [iSEE: Object Permanence Through Self-Supervision](https://arxiv.org/abs/2610.01201v1)

- **arXiv**: `2610.01201v1`  |  **提交日期**: 2026-10-01
- **作者**: Pramish Paudel, Ajad Chhatkuli, Luc Van Gool, Danda Pani Paudel

Object permanence, keeping track of an object's identity and position while it is occluded, is central to video representations that track, predict and plan. Trackers that achieve it learn from boxes, track identities and visibility labels. On the other hand, self-supervised object-centric methods discover objects without labels: through slot attention, it represents a video as slots that bind to objects and follow them across frames. However, these slots are lost under occlusion, making the desired permanence impossible. Reasoning permanence is a hard problem because it requires to detect…

---

### [PhysicsLENS: Diagnosing Physical Property Blindness in Video Generation Models](https://arxiv.org/abs/2610.01162v1)

- **arXiv**: `2610.01162v1`  |  **提交日期**: 2026-10-01
- **作者**: Isaiah Milkey, Som Sagar, Aditya Taparia, Xinyuan Liu, Jiqing Wen, Ransalu Senanayake

Reliable video world models could provide scalable predictive environments for robot learning, planning, and evaluation. However, generated robot videos can violate physical principles and complete tasks through physically implausible behavior, limiting their reliability for robot learning and planning. Current video-generation benchmarks exclude physics that are inherently hidden by visuals (e.g., weight, viscosity, friction). Due to this, video models are evaluated on the fidelity of physics, not the underlying accuracy of physics. We introduce PhysicsLENS, a dataset and benchmark for…

---

### [Ego2Act: Evaluating Goal-Directed Manipulation in Egocentric Video Generation](https://arxiv.org/abs/2610.01092v1)

- **arXiv**: `2610.01092v1`  |  **提交日期**: 2026-10-01
- **作者**: Patrick Amadeus Irawan, Iskandar Muda Rizky Parlambang, Rava Maulana, Qinrong Cui, Erland Hilman Fuadi, Zayd M. K. Zuhri et al.

Video generation models are increasingly being explored as world simulators for embodied planning and learning. To do so effectively, these models must not only generate visually appealing frames, but also predict how environments dynamically evolve when executing goal-directed actions. While evaluating these capabilities is crucial, existing benchmarks focus mainly on single short actions or step-by-step instructions. This leaves multi-step physical reasoning underexplored, especially in egocentric video generation that requires planning to simulate proper execution to accomplish high-level…

---

### [Network World Models as Environments for Algorithm Design on Complex Systems](https://arxiv.org/abs/2610.01048v1)

- **arXiv**: `2610.01048v1`  |  **提交日期**: 2026-10-01
- **作者**: Rishab Alagharu, Hongji Pu, Zeeshan Memon, Xinyuan Song, Yuntong Hu, Liang Zhao

World models, which simulate an environment and predict how it changes under actions, are increasingly used in real-world applications such as robotics. Complex systems call for the same tool because the effect of an action is not immediate. Seeding nodes for a campaign, or immunizing nodes against an epidemic, changes little on its own; what matters is the outcome that unfolds over the steps that follow. Designing an algorithm that selects such actions to maximize expected performance on a task is inherently iterative, and every candidate must be scored by the outcome it produces. Obtaining…

---

### [FutureWorlds: Learning Robotic World Models from Alternative Futures](https://arxiv.org/abs/2610.01019v1)

- **arXiv**: `2610.01019v1`  |  **提交日期**: 2026-10-01
- **作者**: Hao Wu, Shengju Qian, Weiyan Wang, Fan Xu, Fan Zhang, Yuanpeng He et al.

Robotic world models predict action-conditioned future scenes, providing a foundation for understanding action outcomes. However, turning alternative predictions into useful learning signals remains challenging: similar candidates limit informative quality comparisons, while diverging trajectories require persistent maintenance of their individual histories. We introduce FutureWorlds, a framework that unifies candidate construction, history maintenance, and learning from relative quality. Built on a multimodal discrete autoregressive model, FutureWorlds uses diverse beam search during…

---

### [Calibration-risk routing for controlled world-model adaptation](https://arxiv.org/abs/2610.01001v1)

- **arXiv**: `2610.01001v1`  |  **提交日期**: 2026-10-01
- **作者**: Yifan Zhang, Liang Zheng

Model-based reinforcement learning (MBRL) can exploit simulated experience, but a simulator-to-target shift creates a model-selection problem: correcting the simulator and fitting the target directly can each fail under limited target data. We introduce the Model-Corrected World Model (MC-WM), which separates initial target data into disjoint fit, selection, and calibration partitions and deploys the family with lower standardized calibration risk. A learned confidence signal and deterministic validity predicates weight one-step imagined policy updates without rewriting physical rewards. We…

---

### [Variational Streaming Flow: Probabilistic Forecasting in Physical Time](https://arxiv.org/abs/2610.00976v1)

- **arXiv**: `2610.00976v1`  |  **提交日期**: 2026-10-01
- **作者**: Hans Hao-Hsun Hsu, Minseon Gwak, Soon Hoe Lim, Pan Li, N. Benjamin Erichson

Probabilistic forecasting is important for predicting complex dynamical systems because intrinsic randomness and incomplete observations can cause the same observed state to evolve into multiple plausible futures. While flow matching is a flexible approach for probabilistic forecasting, it is computationally expensive. Streaming flow (SF) reformulates this approach to model temporal evolution efficiently by learning a continuous velocity field directly in physical time. However, SF learns a deterministic velocity field. Thus, it provides only a single future trajectory for a given fixed…

---

### [In CEM, a World Model Is Also a Proposal Mechanism](https://arxiv.org/abs/2610.00921v1)

- **arXiv**: `2610.00921v1`  |  **提交日期**: 2026-10-01
- **作者**: Oliver Obst, Frieder Stolzenburg

The cross-entropy method (CEM) uses world-model scores to select action sequences and fit the distribution sampled in its next iteration. A scoring error can therefore change both the present decision and the candidates considered later. We evaluate these two roles separately. Four types of predictive model generate CEM traces, and every model rescores every saved candidate pool. Executing the same candidates in the environment provides a reference elite set and proposal update. Across twelve independently trained task-seed units on Walker and Cheetah, the pre-specified proposal distance…

---

### [Kepler: Auditable World Models for ARC-AGI-3](https://arxiv.org/abs/2610.00834v1)

- **arXiv**: `2610.00834v1`  |  **提交日期**: 2026-09-30
- **作者**: Wensen Wu

ARC-AGI-3 evaluates agents in interactive environments whose rules and objectives must be inferred from observation. We present Kepler, an open-source harness that represents hypotheses as executable world models and validates them through retrospective transition checks and conditional prediction checks. Under one frozen Claude Opus 5 configuration, Kepler obtained a server-verified 100.00 RHAE on all 25 public games, with no per-game model selection or score-conditioned reruns. On 181 of 183 completed levels, the final Opus attempt used no more actions than the corresponding median-human…

---

### [CF-JEPA: Improving Robustness of JEPA World Models via Controllability Factorization](https://arxiv.org/abs/2610.00727v1)

- **arXiv**: `2610.00727v1`  |  **提交日期**: 2026-09-30
- **作者**: Morgan Byrd, Robert Wright, Sehoon Ha

Controlling an agent with vision requires being able to separate useful information from irrelevant background information. JEPA-style latent world models seem like a natural approach for this, as they do not perform pixel-level reconstruction; however, they are still sensitive to these distractor signals and experience latent collapse. In this work, we introduce Controllability Factorized JEPA (CF-JEPA), a JEPA-style world model which splits the latent space into controllable and uncontrollable subspaces. This factorization allows us to capture all the distractor information into the…

---

### [JEPA-TTT: Persistent Test-Time Training of Latent World Models for Planning under Dynamics Shifts](https://arxiv.org/abs/2610.00722v1)

- **arXiv**: `2610.00722v1`  |  **提交日期**: 2026-09-30
- **作者**: Zheyuan Zhang, Suyu Ye, Nakul Agarwal, Hossein Nourkhiz Mahjoub, Ehsan Moradi Pari, Daniel Khashabi et al.

World models enable agents to plan by predicting future states of the environment, but their predictions can become unreliable when test-time dynamics differ from those seen during training. We present JEPA-TTT, which adapts the latent dynamics predictor of a pretrained action-conditioned Joint-Embedding Predictive Architecture world model throughout test time. Self-supervised updates accumulate across episodes, while the visual encoder and reward head remain fixed, preserving the pretrained representation and task objective. Planning requires neither a goal image nor online environment…

---

### [SemanTok: Predictable Semantic Tokens for Efficient Autoregressive Video Generation](https://arxiv.org/abs/2610.00686v1)

- **arXiv**: `2610.00686v1`  |  **提交日期**: 2026-09-30
- **作者**: Mikhail Dereviannykh, Vikram Voleti, Simon Donne, Mallikarjun Byrasandra Ramalinga Reddy, Shimon Vainer, Mark Boss

Recent video-based world models pair the scalability of autoregressive (AR) prediction with the visual quality of diffusion models. The choice of scene tokenizer is paramount for the optimal performance of each of these, both in terms of fidelity and semantics. Flexible-length, coarse-to-fine tokenizers yield exactly that: the first coarse tokens carry the clip's global semantics while later tokens further specify details. Existing flexible tokenizers only apply a representation-alignment (REPA) loss on early decoder hidden states, a target the decoder can partly meet from its noised input…

---

### [Memorizon: Training World Models Beyond Their Context Window](https://arxiv.org/abs/2610.00544v1)

- **arXiv**: `2610.00544v1`  |  **提交日期**: 2026-09-30
- **作者**: Tingting Liao, Xuezhi Liang, Hao Li, Guangyi Liu

Streaming world models should render a place consistently across repeated visits. Directly supervising such revisits requires training samples that capture both visits, often spanning minutes. Yet dense attention over the full span incurs quadratic costs, making long-span supervision expensive. Memorizon breaks this coupling: long spans are needed for supervision, but not for attention, since the two visits can share a forward pass without including every intervening frame. A training sample covers a span of any length but is scored only on its last $k$ chunks. Instead of tokenizing the…

---

### [Social-WM: Safety-Aware Latent World Models for Robot Social Navigation](https://arxiv.org/abs/2609.40177v2)

- **arXiv**: `2609.40177v2`  |  **提交日期**: 2026-09-30
- **作者**: Zhihao Zheng, Mooi Choo Chuah

Safe social navigation requires a robot to anticipate not only the future consequences of its actions, but also whether a nominal action can actually be executed under surrounding physical and social constraints. We present Social-WM, an efficient latent world-model planning framework trained from egocentric RGB video sequences. Our key observation is that social-navigation experience contains a systematic discrepancy between the nominal action and the realizable action: a nominal forward action may be fully executed in free space, but needs to be constrained when heading towards a pedestrian…

---

## 📅 2026-10-01

### [Physis-Lang: Self-Evolving Language as a Physical Representation for Video World Model](https://arxiv.org/abs/2609.40358v1)

- **arXiv**: `2609.40358v1`  |  **提交日期**: 2026-09-30
- **作者**: Liming Lu, Xianzheng Ma, Wenkun He, Guanqi Zhan, Yilin Zhao, Junyu Chen et al.

Video world models are expected to predict how the physical world evolves, yet they often produce visually plausible videos that violate basic physical principles. Existing approaches commonly assume that natural language is insufficient to represent the physical knowledge required for reliable generation, and therefore introduce additional visual, latent, numerical, or planning-based signals. We revisit this assumption and introduce Physis-Lang, a self-evolving framework that treats physical language as a shared and optimizable representation across data curation, model training, and video…

---

### [LOCI: Spatial Linear Memory for Streaming World Models](https://arxiv.org/abs/2609.40222v1)

- **arXiv**: `2609.40222v1`  |  **提交日期**: 2026-09-30
- **作者**: Ji Xia, Tingting Liao, Xuezhi Liang, Hao Li, Guangyi Liu

When a camera revisits a previously observed region, a video world model should reproduce what was there before. This requires both remembering past observations and retrieving the right one for the current viewpoint. Key-value caches preserve visual detail but grow with video length; recurrent memory is compact but compresses history into a fixed-size state, so individual past observations are no longer directly accessible. We introduce LOCI, a hybrid spatial-memory architecture that keeps both representations. In half of the transformer blocks, main attention keeps a key-value cache of past…

---

### [Social-WM: Safety-Aware Latent World Models for Robot Social Navigation](https://arxiv.org/abs/2609.40177v1)

- **arXiv**: `2609.40177v1`  |  **提交日期**: 2026-09-30
- **作者**: Zhihao Zheng, Mooi Choo Chuah

Safe social navigation requires a robot to anticipate not only the future consequences of its actions, but also whether a nominal action can actually be executed under surrounding physical and social constraints. We present Social-WM, an efficient latent world-model planning framework trained from egocentric RGB video sequences. Our key observation is that social-navigation experience contains a systematic discrepancy between the nominal action and the realizable action: a nominal forward action may be fully executed in free space, but needs to be constrained when heading towards a pedestrian…

---

### [Dream4ACT: A Shared Visual Action Interface for Multi-Embodiment Video-Action Modeling](https://arxiv.org/abs/2609.40153v1)

- **arXiv**: `2609.40153v1`  |  **提交日期**: 2026-09-30
- **作者**: Xiangyu Zhu, Jin Xu, Yue Guo, Xin Wu, Yifan Sun, Xiancong Ren et al.

Video generation models (VGMs) offer strong spatiotemporal priors for embodied observation--action modeling. However, joint-space action vectors lack explicit image-space structure and vary in dimensionality and semantics across embodiments, making it challenging to directly leverage the rich spatiotemporal priors of VGMs. End-effector visualizations provide an alternative but do not specify the full articulated configuration needed for robot execution. We present Dream4ACT, a world model built for joint video-action modeling across embodiments. To unify action representations across…

---

### [DashVMC: Real-Time Discrete World Model Control in Geometry Dash](https://arxiv.org/abs/2609.40003v1)

- **arXiv**: `2609.40003v1`  |  **提交日期**: 2026-09-30
- **作者**: Florent Tariolle, Florian Yger

World-model agents are usually evaluated in simulators that can wait for the policy; live games impose the opposite constraint, requiring capture, prediction, and action before the next frame. We present DashVMC, which learns a compact, action-conditioned world model from approximately two hours of recorded Geometry Dash gameplay. To test whether the learned dynamics are actionable, a controller is initialized by behavioural cloning (BC) and refined with Proximal Policy Optimization (PPO) entirely in frozen-model rollouts, without further interaction with the live game. Across three…

---

### [OverForge: Reasoning Through Strategies and Tactics Helps Cooperative Lifelong Adaptation](https://arxiv.org/abs/2609.39727v1)

- **arXiv**: `2609.39727v1`  |  **提交日期**: 2026-09-30
- **作者**: Oana Madalina Fron, Ojas Shirekar, Chirag Raman

Cooperative language-model agents must coordinate over long horizons and adapt to changing environments and to partners with unfamiliar conventions, yet existing agents map observations to actions without separating persistent coordination strategies from their tactical execution. We introduce OverForge, a training-free hierarchical architecture that separates strategic reasoning over roles and divisions of labour from tactical reasoning over actions within each agent's private, partner-conditioned world model. A metacognitive Prefrontal Cortex Module couples the two levels by forming…

---

### [RoboCoach: World Models as Active Coaches for Compositional Robot Skills](https://arxiv.org/abs/2609.39685v1)

- **arXiv**: `2609.39685v1`  |  **提交日期**: 2026-09-30
- **作者**: Jiajun Liu, Yifan Chen, Yichao Liu, Jiayi Zhang, Ruoqu Chen, Shaoxuan Xie et al.

Long-horizon robot manipulation reuses skills across many task compositions, but improving these compositions with additional end-to-end demonstrations is costly. A practical self-improving system must decide both what to teach next and where to apply that supervision. We present ROBOCOACH, a world-model-guided coaching framework that uses imagined failures to guide demonstration requests and expert updates. Its Route-Imagine-Diagnose-Improve (RIDI) loop executes reusable skill experts inside COACHWORLD, our shared action-conditioned world model, and uses a progress judge to record the first…

---

### [Why Do Conventional World Models Fail to Learn Cellular Automata?](https://arxiv.org/abs/2609.39604v1)

- **arXiv**: `2609.39604v1`  |  **提交日期**: 2026-09-30
- **作者**: Shaoyang Guo, Ziming Liu

Although conventional world models - auto-regressive or diffusion models based on transformers or convolutional networks - may learn surface statistics of world dynamics, can they learn the exact world dynamics from its observed history? Leveraging cellular automata as a simple testbed, we find the answer to be no in many cases. Conventional architectures predict most pixels correctly yet rarely complete a rollout: a CNN predicts 96.3% of cells but completes 18.9% of rollouts; a joint diffusion model completes none. We trace the gap to three failure modes of these world models - namely, they…

---

### [ReWAM: Reciprocal World Action Models for Interactive Autonomous Driving](https://arxiv.org/abs/2609.39245v1)

- **arXiv**: `2609.39245v1`  |  **提交日期**: 2026-09-30
- **作者**: Benshan Ma, Pei Liu, Ruiguo Zhong, Lang Zhang, Mingyue Feng, Yaonong Wang et al.

In interactive scenarios, an autonomous driving system is required to generate ego actions under the influence of other agents' behaviors. Existing World Action Models (WAMs) typically model other agents as components of the world model rather than as decision-makers that fundamentally shape the action of the ego agent, which impairs their performance in dense interaction scenarios. We introduce Reciprocal World Action Models (ReWAM), a game-theoretic world action modeling framework that captures the reciprocal influence between the ego agent and other agents by representing them as…

---

### [MEND: Label-Free Detection, Localisation, and Correction of Latent Hallucination in World Models](https://arxiv.org/abs/2609.39182v1)

- **arXiv**: `2609.39182v1`  |  **提交日期**: 2026-09-30
- **作者**: Ali J Alrasheed, Aryan Yazdan Parast, Basim Azam, James Bailey, Naveed Akhtar

World Models are appearing as the next major frontier in computer vision. However, their robustness is currently largely unexplored. We identify the phenomenon of hallucination in latent World Models: given a state and an action, the predicted next latent can decode to a scene that never occurs. Because the prediction is statistically ordinary and is fed back autoregressively by the model, the error is both silent and compounding. We study whether such latent hallucination can be detected, localised, and corrected at inference time, on a frozen self-supervised world model in the absence of…

---

### [LocoWM: High-Precision Locomotion through World-Model-Guided Residual Adaptation](https://arxiv.org/abs/2609.39179v1)

- **arXiv**: `2609.39179v1`  |  **提交日期**: 2026-09-30
- **作者**: Zijie Zhao, Shengqian Chen, Xiaoxu Wang, Han Jiang, Yuanheng Zhu, Dongbin Zhao

High-precision locomotion combines motion-command tracking with precise regulation of task-relevant physical states, enabling robots to interact reliably with their surroundings during motion. Joint end-to-end optimization can leave precision objectives insufficiently optimized, while reactive residual control adjusts actions only after deviations become observable. We present \textbf{LocoWM}, a world-model-guided preactive residual adaptation framework for high-precision locomotion. A base policy provides command-following locomotion, while an action-conditioned world model predicts a…

---

### [Linear Recurrent Memory Suffices to Distil a World-Model Policy for Robot Air Hockey](https://arxiv.org/abs/2609.39151v1)

- **arXiv**: `2609.39151v1`  |  **提交日期**: 2026-09-30
- **作者**: F. Olivia Fan, Oliver Obst

Does memory-dependent control need nonlinear recurrent dynamics? We study simulated air-hockey defence under temporary loss of puck tracking. A DreamerV3 teacher outperforms a memoryless policy under tracking loss, while resetting the teacher's recurrent state sharply reduces performance, which demonstrates that the task requires memory. We distil this teacher into compact recurrent policies with a 64 dimensional state, with a combination of a diagonal linear recurrence and an optional rank-$k$ nonlinear innovation while retaining nonlinear observation encoders and action heads. Across five…

---

### [Asking the World: Generalist Physical Reasoning through Agentic World Modeling and Probing](https://arxiv.org/abs/2609.39135v1)

- **arXiv**: `2609.39135v1`  |  **提交日期**: 2026-09-30
- **作者**: Shenxiang Zeng, Chen Yang, Peiyao Chen, Guohui Zhang, Jiansheng Fan, Chen Wang

Physical reasoning from video requires inferring latent physical properties and dynamics beyond direct observation. Direct VLM inference remains unreliable on complex physical tasks without explicit modeling and validation, while predefined tool pipelines rely on task- and domain-specific priors that limit generalization across materials, dynamics, and reasoning tasks. We introduce Asking the World (ATW), a generalist agent that constructs and interrogates task-relevant executable worlds through two adaptive stages: World Modeling calibrates a world from video, while World Probing queries,…

---

### [Beyond Prediction: Steering VLM Agents with Retrospective World Modeling](https://arxiv.org/abs/2609.39101v1)

- **arXiv**: `2609.39101v1`  |  **提交日期**: 2026-09-30
- **作者**: Yongjiang Liu, Jie Zhang, Haoyue Zhang, Jingcai Guo, Deze Zeng, Song Guo

Equipping VLM agents with world modeling capabilities has shown strong potential for complex reasoning and long-horizon planning, while reducing the dependence of policy learning on costly real-world interactions. Existing methods mainly rely on prospective simulation to predict the consequences of candidate actions. However, this forward-only paradigm focuses on what will happen next and provides limited constraints for verifying whether an action is causally consistent with the observed state transition, which can lead to plausible-looking but physically incoherent behaviors. In this paper,…

---

### [World-as-Graph: Relational World Modeling Through Latent Space Graphs](https://arxiv.org/abs/2609.38927v1)

- **arXiv**: `2609.38927v1`  |  **提交日期**: 2026-09-30
- **作者**: Yaqi Yang, Shuo Huang, Yujin Huang, Fucai Ke, Jiatong Han, Xin Zheng

World models aim to learn representations of real-world environments and predict their future evolution. Recent object-centric world models have made expressive progress by representing visual scenes as sets of object-level latent states, but object-object relations are often captured only implicitly, which limits explicit relational and temporal structure modeling and object-centric dynamic memory modeling. To address such challenges, we propose World-As-Graph (WAG), a graph-based object-centric world model that introduces relational inductive bias into JEPA-style predictive representation…

---

### [FrameMorrow: Future-guided Frame Selection with Prospective Tokens for Long-Horizon Video Generation](https://arxiv.org/abs/2609.38839v1)

- **arXiv**: `2609.38839v1`  |  **提交日期**: 2026-09-30
- **作者**: Bo Yin, Xiaobin Hu, Jiaqi Zhao, Shuicheng Yan

Long-horizon video generation requires models to effectively leverage an increasingly long generation history. As the generated history grows, retaining all previous content becomes increasingly expensive and redundant, making effective historical selection essential. Existing approaches often determine historical relevance based on the current content. However, information relevant to the present is not necessarily useful for future generation, while seemingly less relevant history may become important later. Our key insight is that historical information should be selected according to its…

---

### [Code to Control: Synthesizing Parameterized Reactive Controllers](https://arxiv.org/abs/2609.38733v1)

- **arXiv**: `2609.38733v1`  |  **提交日期**: 2026-09-30
- **作者**: Zergham Ahmed, Joshua B. Tenenbaum, Chris Bates, Samuel J. Gershman

Recent LLM-based approaches to control either invoke a language model to select actions or synthesize world models that require planning at every decision, introducing latency that can limit real-time use. We introduce Code to Control, an approach that synthesizes Python controllers which execute directly as policies. Code to Control separates program structure from parameters. An LLM synthesizes the controller structure, while derivative-free search fits its parameters for continuous control using feedback from the environment. Once learned, the resulting controllers require neither LLM…

---

### [After a Decade: Bringing Shadow Removal into the Real World with Agentic Training Data](https://arxiv.org/abs/2609.38607v1)

- **arXiv**: `2609.38607v1`  |  **提交日期**: 2026-09-29
- **作者**: Shilin Hu, Jingyi Xu, Dimitris Samaras, Hieu Le

Shadow removal looks nearly solved on established benchmarks, yet remains brittle in the real world. Models have advanced; the paired training data they rely on have barely changed in nearly a decade. The reason is simple: obtaining a shadow-free target requires removing the occluder while keeping the scene, camera, and illumination otherwise unchanged, making diverse paired data difficult to capture. Meanwhile, large shadow detection datasets already contain diverse real-world images and masks, but no shadow-free targets. To turn this abundant but incomplete data into paired supervision, we…

---

### [LongTake: Learning to Sustain Dynamics in Long-Horizon Video Generation](https://arxiv.org/abs/2609.38562v1)

- **arXiv**: `2609.38562v1`  |  **提交日期**: 2026-09-29
- **作者**: Byoungwoo Park, Jaemoo Choi, Juho Lee, Yongxin Chen

World models, game simulators, and long-take video creation require coherent scene evolution and sustained dynamics over extended durations. Autoregressive (AR) video diffusion provides a natural framework for long-horizon generation, yet extended rollouts often become near-static or lose visual quality. We hypothesize that these failures reflect the limited guidance provided by short-video supervision on how ongoing scene dynamics develops over longer durations. This motivates us to introduce LongTake, a two-stage training pipeline built around Long-Horizon Teacher Forcing (TF) on curated…

---

### [An Empirical Study of Architectural Shift from Traditional to AI-Enabled Simulink Controllers](https://arxiv.org/abs/2609.38504v1)

- **arXiv**: `2609.38504v1`  |  **提交日期**: 2026-09-29
- **作者**: Hadiza Umar Yusuf, Khouloud Gaaloul

Effective AI adoption in cyber-physical systems (CPS) depends on embedding design knowledge into engineering practice. Yet as AI-enabled components increasingly replace analytically derived control laws, this occurs without a systematic understanding of how controller architectures differ or remain similar across paradigms. We address this gap with an empirical study of traditional and AI-enabled Simulink controllers, guided by a literature-derived taxonomy of ten structural categories and nine functional roles. The study analyzes 62 real-world models spanning 8 controller types and 10…

---

### [Audible World Models: Spatially Aware Sound Generation for 3D Worlds](https://arxiv.org/abs/2609.38444v1)

- **arXiv**: `2609.38444v1`  |  **提交日期**: 2026-09-29
- **作者**: Duowen Chen, Jinjin He, Gouthaman KV, Sandeep Bangalore Venkatesh, Bo Zhu

Text- and image-conditioned world generators can create visually rich 3D environments, yet these worlds often remain silent or rely on soundtracks synthesized solely from text or rendered video. Although such audio can convey what should be heard, it lacks an explicit representation of where sound sources are located and how their perceived sound should vary with listener movement. We introduce Audible World Models, a training-free framework that incorporates sound into the generated world state. Starting from a text prompt, our system constructs a panoramic 3D proxy, separates it into…

---

### [Masked Swingers: Harnessing Data Augmentation to Advance Autoencoders for Self-Supervised Learning](https://arxiv.org/abs/2609.38278v1)

- **arXiv**: `2609.38278v1`  |  **提交日期**: 2026-09-29
- **作者**: Anthony Fuller, Scott C. Lowe, Daniel G. Kyrollos, Graham W. Taylor, Evan Shelhamer, James R. Green

Self-supervised learning (SSL) removes the need for annotations and makes models that are capable across more domains than supervised learning. The autoencoder SSL framework learns by reconstructing its own input after information loss through a bottleneck or noise injection. Masked autoencoders (MAE) are the most successful instantiation of this framework: they encode a random subset of patches, then decode the masked-out patches. In this work, we introduce key modifications to improve MAEs. Our method augments an image in two different ways, then masks and encodes each view separately. It…

---

### [Waypoint-1.5: A Real-Time Video World Model for Consumer Hardware](https://arxiv.org/abs/2609.37107v2)

- **arXiv**: `2609.37107v2`  |  **提交日期**: 2026-09-29
- **作者**: Rajit Rajpal, Shahbuland Matiana, Liew Wei Pyn, Anmol Agarwal, Ryan Craig, Andrew Lapp et al.

We present Waypoint 1.5, a real-time diffusion world model for interactive video generation on consumer-grade hardware. Unlike general video diffusion models, interactive world models (iWMs) must respond to dense user controls under strict latency and throughput constraints. Waypoint 1.5 is pre-trained on 100,000 hours of diverse, control-aligned video game data across hundreds of games, and generates playable video conditioned on full keyboard and mouse input. The model includes two resolution variants that run across a wide spectrum of consumer hardware. To characterize this unique setting,…

---

### [World2Motion: Turning Video World Models into 3D Human Motion Generators](https://arxiv.org/abs/2609.37004v2)

- **arXiv**: `2609.37004v2`  |  **提交日期**: 2026-09-29
- **作者**: Fangyuan Tu, Xiangyue Zhang, Yiyi Cai, Yichen Peng, Kunhang Li, Bo Zheng et al.

We present World2Motion, a framework that generates scene-aware 3D human motion and corresponding video from a single image and a text prompt. While existing 3D motion generators learn from motion datasets, their generalization is constrained by limited coverage of environments. In contrast, video world models such as Cosmos 3 offer broader environmental priors but are not designed for full-body motion generation; recovering motion from their generated videos requires costly two-stage inference. To address these, we turn Cosmos 3 into a single-stage 3D motion generator. This adaptation has…

---

## 📅 2026-09-30

### [Rethinking Representations for World-Action Modeling](https://arxiv.org/abs/2609.38163v1)

- **arXiv**: `2609.38163v1`  |  **提交日期**: 2026-09-29
- **作者**: Haoyi Jiang, Liu Liu, Xinjiang Wang, Zhihao Sun, Zequn Chen, Sen Wang et al.

World-action models jointly learn robot policies and predict future observations, making the representation space an interface between control and prediction. We study the design of this space through controlled comparisons, finding that neither reconstruction fidelity nor pre-trained perceptual features alone ensure effective policy learning. These findings motivate ReWAM, a representation-centric world-action model built on pre-trained DINO features. Feature Calibration and a Temporal Representation Bottleneck organize these features into compact world states suited to dynamics modeling.…

---

### [LongLive-Plug: Once-for-All Distillation for Video Generation](https://arxiv.org/abs/2609.38154v1)

- **arXiv**: `2609.38154v1`  |  **提交日期**: 2026-09-29
- **作者**: Shuai Yang, Luozhou Wang, Wei Huang, ZhiFei Chen, Bohan Zhang, Xiao Fu et al.

Video diffusion models are increasingly developed into specialized models for diverse downstream tasks, and this development often includes a distillation stage, for example to accelerate sampling or to improve long-video generation. This stage is typically repeated for every specialized model. We introduce LongLive-Plug, a once-for-all distillation framework that learns reusable capabilities as LoRAs on a base model for training-free, plug-and-play deployment to compatible downstream models. These capabilities include single-pass classifier-free guidance, few-step sampling, and long-context…

---

### [Breaking the Uniformity Trap: Scaling Video Diffusion Model via SplitMoE](https://arxiv.org/abs/2609.38140v1)

- **arXiv**: `2609.38140v1`  |  **提交日期**: 2026-09-29
- **作者**: Yu Xu, Yuxin Zhang, Xiao Yang, Haotian Yang, Yizhi Wang, Xinwei Huang et al.

Mixture-of-Experts (MoE), popularized by large language models, is a promising paradigm for scaling visual generative models. However, conventional token-wise MoE routes tokens independently within a homogeneous expert pool and regularizes expert usage toward uniformity, making it poorly matched to video data that is spatiotemporally redundant and semantically long-tailed. We show that existing visual MoEs fall into a uniformity trap: semantically under-organized routing, compounded by uniform expert-usage regularization, scatters coherent patches across disparate experts, causing routing…

---

### [HelixWorld: A Real-time Interactive Audio-Visual World Model](https://arxiv.org/abs/2609.38123v1)

- **arXiv**: `2609.38123v1`  |  **提交日期**: 2026-09-29
- **作者**: Lei Ke, Jiahao Pan, Zeyue Tian, Jiaming Wang, Haoyuan Huang, Kam Man Wu et al.

World simulation is inherently multisensory, demanding synchronized visual and acoustic dynamics in real time. Yet prevailing interactive world models remain strictly silent, focusing exclusively on visual rendering and control while overlooking the acoustic dimension. We present HelixWorld, a real-time interactive audio-visual world model where visual scenes and camera-grounded spatial stereo sound co-evolve natively under user interaction. We curate a high-fidelity spatial audio-visual dataset with true stereo acoustics and metric camera poses, upon which we pre-train a bidirectional…

---

### [Stochastic World Models for Verifying Vision-Based Neural Feedback Systems](https://arxiv.org/abs/2609.38120v1)

- **arXiv**: `2609.38120v1`  |  **提交日期**: 2026-09-29
- **作者**: I. Samuel Akinwande, Mykel J. Kochenderfer, Clark Barrett

Verifying a vision-based neural feedback system requires a model of the observations its controller acts upon. Such a model must capture the variation the sensor produces, while remaining tractable for closed-loop analysis. Generative adversarial networks (GANs) have served as perception surrogates, but they are large, reproduce complex scenes poorly, and are hard to verify. We explore stochastic world models as a richer class of perception surrogates. We train a world model with physically grounded latents, built from operations that standard verifiers bound. It reproduces held-out frames…

---

### [Honeycomb: Constant-Size Scene Memory Representation for Video World Models](https://arxiv.org/abs/2609.37690v1)

- **arXiv**: `2609.37690v1`  |  **提交日期**: 2026-09-29
- **作者**: Jack Wei Lun Shi, Kaichen Zhou, Haoyu Chen, Yufeng Weng, Keane Ong, Ruojin Cai et al.

Video world models require persistent scene memory to maintain consistency during long-horizon video generation. Existing spatial memory systems accumulate RGB observations or latent features, causing storage requirements to grow as generation proceeds. We introduce **Honeycomb**, a video world model built on **HexMemory**, a compact low-rank representation that stores scene features in a fixed-size memory comprising six spatial and spatiotemporal planes. A feed-forward writer maps each newly generated video chunk to plane features. As the spatial coverage or temporal range expands, HexMemory…

---

### [Beyond a single latent space: a dual-latent world model for long-horizon planning](https://arxiv.org/abs/2609.37644v1)

- **arXiv**: `2609.37644v1`  |  **提交日期**: 2026-09-29
- **作者**: Delin Zhao, Zhengrong Yue, Shaobin Zhuang, Junlin He, Xiaoyu Chen, Zikang Wang et al.

Latent world models often struggle with long-horizon planning despite accurate short-term predictions. Recursive rollouts accumulate errors, while distance concentration in high-dimensional latent spaces can weaken goal discrimination. We introduce the Dual-Latent World Model (Dual-WM), which separates local execution and long-range planning through distinct state representations and dynamics models. The low-level model predicts action-conditioned transitions, while the high-level model uses learned macro-actions to plan over longer temporal spans. We also propose Long-Horizon Representation…

---

### [Anisotropic Representations Improve Planning in JEPA World Models](https://arxiv.org/abs/2609.37441v1)

- **arXiv**: `2609.37441v1`  |  **提交日期**: 2026-09-29
- **作者**: Mingu Kang, Yoori Oh, Sookyung Kim, Joonseok Lee

Latent world models learn action-conditioned dynamics in representation space and often score candidate actions by Euclidean distance to a goal representation. Joint training typically regularizes the representation to prevent collapse, but the resulting representation geometry also determines how terminal errors are weighted during planning. We show that accurate prediction and noncollapsed representations do not guarantee a task-aligned latent planning cost: isotropic Gaussian regularization can induce a geometry that ranks feasible outcomes differently from the task cost. To address this…

---

### [Direct Experience World-Model Optimization: Learning the World Beyond Action Imitation](https://arxiv.org/abs/2609.37398v1)

- **arXiv**: `2609.37398v1`  |  **提交日期**: 2026-09-29
- **作者**: Xiangcheng Zhan, Zirui Chen, Yicheng Zhao, Ziteng Gao, Shuo Yang

World-Action Models (WAMs) couple action generation with predictions of how physical interactions unfold. However, current post-deployment learning paradigms typically improve behavior without requiring better world predictions. Especially in dexterous manipulation, small execution errors can compound in high-dimensional action spaces, hindering policy improvement and pushing interactions beyond the world model's training distribution. Motivated by this, we propose Direct Experience World-Model Optimization (DEWO), a post-deployment learning paradigm for WAMs that, alongside action imitation,…

---

### [Do-JEPA: From Masking to Intervention in Latent World Models](https://arxiv.org/abs/2609.37378v1)

- **arXiv**: `2609.37378v1`  |  **提交日期**: 2026-09-29
- **作者**: Hossein Resani, Javen Qinfeng Shi

Latent world models are trained to predict what happens next, so nothing in their objective separates what an action caused from what merely co-occurred with it. Object-masking models such as C-JEPA intervene on what the predictor can see; we intervene on what physically happens. From one saved simulator state we run the dynamics under an action $a$ and under a reference action $a_{\varnothing}$, and train the model to predict the difference $Δz=z^{a}-z^{a_{\varnothing}}$ between the two latent futures. The resulting objective, Do-JEPA, has an effect loss, a support loss (where the action…

---

### [Lucid Dreaming for World Models: Learning to Doubt Imagination and Decide by Trust](https://arxiv.org/abs/2609.37156v1)

- **arXiv**: `2609.37156v1`  |  **提交日期**: 2026-09-29
- **作者**: Ziqi Wen, Ting Xu, Lianyu Wang, Xian Lin, Yanda Meng, Huazhu Fu et al.

World models enable agents to learn and plan in imagination, but predictions beyond their experience can become unreliable and mislead decisions. Existing uncertainty estimates derived from predictions can remain overconfident on unfamiliar state-action pairs. We propose the Lucid World Model (LucidWM), which learns doubt from experience and propagates trust through imagination. By integrating Subjective Logic into categorical latent transitions, LucidWM distinguishes predicted outcomes from their evidential support and assigns each transition a degree of doubt. The complement of this doubt…

---

### [Waypoint-1.5: A Real-Time Video World Model for Consumer Hardware](https://arxiv.org/abs/2609.37107v1)

- **arXiv**: `2609.37107v1`  |  **提交日期**: 2026-09-29
- **作者**: Rajit Rajpal, Shahbuland Matiana, Liew Wei Pyn, Anmol Agarwal, Ryan Craig, Andrew Lapp et al.

We present Waypoint 1.5, a real-time diffusion world model for interactive video generation on consumer-grade hardware. Unlike general video diffusion models, interactive world models (iWMs) must respond to dense user controls under strict latency and throughput constraints. Waypoint 1.5 is pre-trained on 100,000 hours of diverse, control-aligned video game data across hundreds of games, and generates playable video conditioned on full keyboard and mouse input. The model includes two resolution variants that run across a wide spectrum of consumer hardware. To characterize this unique setting,…

---

### [World2Motion: Turning Video World Models into 3D Human Motion Generators](https://arxiv.org/abs/2609.37004v1)

- **arXiv**: `2609.37004v1`  |  **提交日期**: 2026-09-29
- **作者**: Tu Fangyuan, Xiangyue Zhang, Yiyi Cai, Yichen Peng, Kunhang Li, Bo Zheng et al.

We present World2Motion, a framework that generates scene-aware 3D human motion and corresponding video from a single image and a text prompt. While existing 3D motion generators learn from motion datasets, their generalization is constrained by limited coverage of environments. In contrast, video world models such as Cosmos 3 offer broader environmental priors but are not designed for full-body motion generation; recovering motion from their generated videos requires costly two-stage inference. To address these, we turn Cosmos 3 into a single-stage 3D motion generator. This adaptation has…

---

### [Abductive World Modeling via Causal Representation Learning](https://arxiv.org/abs/2609.36985v1)

- **arXiv**: `2609.36985v1`  |  **提交日期**: 2026-09-29
- **作者**: Ziqi Liu, Songhan Yang, Linfan Zhou, Jiatong Liu, Lijun Peng, Long Wan et al.

The central challenge of world modeling is to learn representations that capture how the world evolves. However, existing world models predominantly represent future states without explicitly capturing the latent causes underlying their evolution, limiting their ability to reason about why and how the world changes. To address this limitation, we propose Abductive World Modeling (AWM), a framework that learns structured causal representations by abductively inferring latent causes from predicted futures. Specifically, we realize AWM through the Hierarchical Abductive State Pyramid (HASP),…

---

### [DSWM: Decomposed Spatio-Temporal World Model for Demand-Driven UAV Base Station Repositioning](https://arxiv.org/abs/2609.36845v1)

- **arXiv**: `2609.36845v1`  |  **提交日期**: 2026-09-29
- **作者**: Shengjie Zhong, Zhongliang Zhao, Jingxuan Chen, Xianbin Cao, Xinmei Qiang, Dapeng O. Wu et al.

Uncrewed aerial vehicle base stations (UAV-BSs) are expected to cover traffic demand that shifts across space and time, yet most repositioning schemes either re-solve an optimization problem per slot or learn reactive policies without an explicit demand model. We cast demand-driven fleet repositioning as latent-space decision-time planning and propose DSWM, a decomposed spatio-temporal world model: an agentic controller that perceives the demand field through a rolling observation window, retains operational context in a latent recurrent state, reasons about candidate motions by imagined…

---

### [RolloutFaith: Auditing Persistent Internal Interventions in Visual World Model](https://arxiv.org/abs/2609.36843v1)

- **arXiv**: `2609.36843v1`  |  **提交日期**: 2026-09-29
- **作者**: Junchi Yao, Ziyi Wang, Youling Huang, Lijie Hu

Interpretability methods such as probes, activation patches and learned editors are designed to reveal or modify a model's current computation. World models pose a harder requirement: because their predictions become inputs to later predictions, a useful internal correction must survive after editing stops. We therefore propose RolloutFaith, a framework that measures semantic improvement both in the prediction produced at intervention time and over later autonomous predictions under fixed events, actions, noise, and information budgets. We evaluate ten fitted editors on three world models…

---

### [MeteoVerse: Unified Weather-Controllable Video World Model](https://arxiv.org/abs/2609.36810v1)

- **arXiv**: `2609.36810v1`  |  **提交日期**: 2026-09-29
- **作者**: Renlong Wu, Guanqiao Wang, Xuan Shang, Yin Hanming, Xiaoxiao Sheng, Tianyu Huang et al.

Video world models aim to predict future content from an observed scene while following prescribed camera motion. Real-world scene evolution is determined not only by changes in viewpoint and object dynamics, but also by environmental conditions such as weather, which can substantially alter scene appearance and visibility. Modeling such realistic weather evolution is challenging because the required weather modification depends jointly on the observed and desired weather states. Depending on their relation, the model may need to preserve, introduce, or remove a weather effect. Existing video…

---

### [ReWorld-Track: A Recursive Event World Model for Language-Guided Multi-Camera Tracking](https://arxiv.org/abs/2609.36677v1)

- **arXiv**: `2609.36677v1`  |  **提交日期**: 2026-09-29
- **作者**: Haoyang Wu, Shoudong Han, Chaoyue Li, Sijia Chen, Zhenyang Xie, Wang sihan

Language-guided multi-camera tracking must preserve a target identity across unobserved gaps, where similar candidates and uncertain returns can make early associations unreliable. A wrong match can corrupt the history used to predict later observations and propagate identity errors across subsequent camera handoffs. We propose ReWorld-Track, a recursive event world model that carries association uncertainty into future predictions. Candidate matches and continued waiting define alternative target states, whose posterior probabilities are used to update a persistent recurrent belief. This…

---

### [Foresight at the Event Boundary: Evaluating Physical Prediction in Video World Models](https://arxiv.org/abs/2609.36531v1)

- **arXiv**: `2609.36531v1`  |  **提交日期**: 2026-09-29
- **作者**: Estela Monserrat Arriaga Santana, Julian Rosas Scull, Ehécatl Sacamch'en Núñez Rico, Hugo Jair Escalante

Video world models are largely regarded as predictive models of the physical world and are therefore expected to anticipate the consequences of observed events. However, evaluation has mainly focused on reference similarity, physical-law consistency, or judgment plausibility, estimating anticipation only indirectly. We address this directly: when a release or impact has just occurred but its consequence is withheld, can a world model anticipate what should happen next? We introduce an event-anchored evaluation based on 62 controlled real-world free-fall recordings and 124 clips spanning three…

---

### [DynamicHOI: Coupled Dynamics for Physics-aware HOI Reconstruction](https://arxiv.org/abs/2609.36454v1)

- **arXiv**: `2609.36454v1`  |  **提交日期**: 2026-09-29
- **作者**: Wenliang Guo, Zhanbo Huang, Yu Kong

We study hand-object interaction (HOI) reconstruction from monocular RGB videos, where partial observations can produce visually plausible yet mechanically inconsistent trajectories. Existing methods mainly enforce visual and geometric agreement, leaving the underlying interaction dynamics insufficiently constrained. We propose DynamicHOI, a physics-aware HOI reconstruction framework combining geometry-grounded diffusion refinement with coupled hand-object dynamics. Geometry spatially grounds visual evidence for trajectory refinement, while articulated inverse dynamics and Newton-Euler…

---

### [World4Scorer: Outcome-Grounded World Modeling for Autonomous Driving](https://arxiv.org/abs/2609.36438v1)

- **arXiv**: `2609.36438v1`  |  **提交日期**: 2026-09-29
- **作者**: Jieyuan Pei, Meiyi Lu, Sining Ang, Yubo Zhao, Zhangyi Hu, Mingwei Xu et al.

Autonomous driving requires choosing a safe and efficient plan as surrounding traffic evolves. Generate-and-select planners propose multiple trajectories and score them for execution, and they have outperformed representative direct-prediction baselines on NAVSIM. Their scorer must compare plans that were never executed. Driving logs record the future of only the executed trajectory, so matching the logged future can leave predictions for the alternatives unconstrained; a simulator, in contrast, can label the outcome of every candidate. We introduce World4Scorer, which builds the scorer as a…

---

### [One from Infinity: Actualizing Futures from Pretrained World Models into Robot Actions](https://arxiv.org/abs/2609.36413v1)

- **arXiv**: `2609.36413v1`  |  **提交日期**: 2026-09-29
- **作者**: Bang Du, Yichen Xie, Shuqi Zhao, Yuxin Chen, Menglin Wu, Masayoshi Tomizuka

A pretrained video world model admits many plausible futures for a scene, but a robot must realize the exact task-conditioned one. To turn world models into executable robot policies, existing methods fine-tune the heavy world model backbone using large-scale robot data and computational resources. Challenging this status quo, we argue that the expensive part has already been paid in the world model pretraining since the representation space of a video world model lays out the diverse potential futures. In this case, what remains is to select the future that accomplishes the task and to read…

---

### [ATLAS: Aligned Transport of Latent Structure for Reliable World Model Planning](https://arxiv.org/abs/2609.36333v1)

- **arXiv**: `2609.36333v1`  |  **提交日期**: 2026-09-28
- **作者**: Ke Fang, Yupu Yao, Lu Cheng

Latent world models rely on representation geometry for planning, yet regularizing the latent marginal alone does not determine the state-to-state relationships used for action selection. We show that this can cause planning-relevant novelty structure to be weakened as representations are transformed into the final latent used by the planner. We introduce Aligned Transport of Latent Structure (ATLAS), a training objective that explicitly preserves relational geometry while calibrating the global latent distribution. ATLAS transfers normalized pairwise structure from an informative encoder…

---

### [Towards an AI Software Factory for Data Systems](https://arxiv.org/abs/2609.36323v1)

- **arXiv**: `2609.36323v1`  |  **提交日期**: 2026-09-28
- **作者**: Anna Pavlenko, Bogdan Crivat, Brandon Haynes, Carlo Curino, Fotis Psallidas, Jaro Slawinski et al.

AI-assisted coding tools deliver significant acceleration of coding, but only limited impact across the end-to-end software development lifecycle (SDLC)--an Amdahl's law effect! In this paper, we discuss our progress towards building an AI SW Factory that accelerates all the stages of SDLC-Targeting, Coding, Reviewing, and Ops. The AI SW Factory produces a metadata exhaust that enables self-improvement by fine-tuning model weights and updating our World Model (a rich data substrate). We focus on Data Systems and the important class of Evolutionary Coding Tasks (i.e., those with a measurable…

---

### [Bilinear World Models: Learning Representations with Structured Dynamics for Efficient Control](https://arxiv.org/abs/2609.36305v1)

- **arXiv**: `2609.36305v1`  |  **提交日期**: 2026-09-28
- **作者**: Antonio Pariente, Ignacio Boero, Nikolai Matni, Alejandro Ribeiro

World models jointly learn latent representations and dynamics that predict how high-dimensional observations evolve under actions. In this work, we propose a JEPA-style world model in which, rather than learning arbitrary latent dynamics, we restrict them to follow a bilinear parameterization. This structure enables efficient planning and control while shifting the modeling burden onto the encoder, encouraging richer representations that expose the controllable geometry of the system. In particular, this structured parameterization allows us to structurally enforce action recoverability,…

---

### [One-Step Next-Latent Prediction Is Not a World Model](https://arxiv.org/abs/2609.36227v1)

- **arXiv**: `2609.36227v1`  |  **提交日期**: 2026-09-28
- **作者**: Shitong Wang, Zhongang Cai, Yuzhou Hong

Next-latent prediction fits a map from the current embedding to the next one. LeNEPA carries this objective to time series, replacing the stop-gradient of next-embedding prediction with the isotropy penalty of LeJEPA. A world model is a transition kernel that can be rolled out. The one-step regression identifies a conditional mean, and a mean is a kernel only in special cases. For a linear-Gaussian Markov latent, the mean transition and the innovation covariance are fixed by the one-step problem, and the open-loop squared error at horizon $K$ equals the trace of the sum of the pushed-forward…

---

### [In-Context Learning for Robots: Methods and Applications](https://arxiv.org/abs/2609.36012v1)

- **arXiv**: `2609.36012v1`  |  **提交日期**: 2026-09-28
- **作者**: Haojian Huang, Zexi Li, Junhao Guo, Yehang Zhang, Wenxuan Peng, Bohan Zhou et al.

General-purpose robots must infer what a new task requires and translate that understanding into appropriate physical action. In-context learning (ICL) for robots supports this process by using demonstrations and interaction to direct existing competence with neural parameters held fixed during deployment. We organize this literature review around the interfaces connecting contextual evidence to execution, distinguishing four families: context-conditioned policies, geometric demonstration transfer, world-model-based control, and skill- and agent-based execution. Comparing these interfaces…

---

### [Embodied Semantic Communication for Collective Autonomous Agents: A Tutorial on Representation, Wireless Delivery, and Closed-Loop Coordination](https://arxiv.org/abs/2609.35936v1)

- **arXiv**: `2609.35936v1`  |  **提交日期**: 2026-09-28
- **作者**: Yizheng Huang, Wensheng Lin, Lixin Li, Qinghe Du, Wenchi Cheng, Zhu Han

As autonomous systems and embodied intelligence enter the dynamic physical world, multi-agent collaboration calls for a paradigm shift in communication design. However, existing communication paradigms overlook that agents form action understanding from their own states, environmental observations, and collaboration relations through a process that evolves as a task unfolds. Consequently, reliable bit delivery, general semantic recovery, or single-task utility optimization alone cannot ensure that heterogeneous agents form coordinated actions compatible with their own conditions from shared…

---

### [FlexiWorld: Learning and Planning via Flexible Action Chunks Across Multiple Time Scales](https://arxiv.org/abs/2609.35138v2)

- **arXiv**: `2609.35138v2`  |  **提交日期**: 2026-09-28
- **作者**: Shidu Ren, Qilin Gu, Zhenghao Ni, Junhan Sun, Jiaqi Wang, Damien Scieur et al.

Latent world models predict future states for goal-directed planning using action chunks spanning multiple primitive steps. Existing methods typically use fixed-length chunks and either omit goal-conditioned action generation or limit their supervision to short goal spans. We introduce FlexiWorld, a JEPA-based world model that combines mixed-span goal supervision with variable-length action chunks to improve long-horizon control. During training, we sample varying goal spans and randomly partition the actions into variable-length chunks. We jointly train the world model with a causal action…

---

## 📅 2026-09-29

### [DynaTokens: Teaching Dynamics to Camera-Controlled Video Models at Test Time](https://arxiv.org/abs/2609.35704v1)

- **arXiv**: `2609.35704v1`  |  **提交日期**: 2026-09-28
- **作者**: Ma Ziqi, Chen Hongqiao, Gkioxari Georgia

Video generation must account for two sources of motion, one induced by the observer's camera path and the other caused by scene dynamics. An ideal camera-controlled video model should account for both motions: let users move the camera while evolving the scene dynamics. While current models handle camera-induced motion well in static settings, they struggle for dynamic scenes: objects are static, move incorrectly, or degrade in generation quality. We introduce DynaTokens, a lightweight set of learnable scene-specific tokens that teach dynamics to an existing camera-controlled world model.…

---

### [MM-ABC: Towards Generalist Mobile Manipulation via Seeing, Coordinating and Imagining](https://arxiv.org/abs/2609.35652v1)

- **arXiv**: `2609.35652v1`  |  **提交日期**: 2026-09-28
- **作者**: Qiwei Liang, Guangyu Chen, Shaolong Zhu, Zikuan Xiao, Jinxuan Lu, Yifan Xie et al.

Mobile manipulation extends robot interaction beyond a fixed kinematic workspace by making the reachable region itself controllable. This flexibility introduces two central challenges: spatially grounded perception under continuous ego-motion and coordinated control of heterogeneous arm and base actions. Existing approaches strengthen geometry through explicit 3D representations or predictive world models, and often decouple mobility and manipulation into separate action streams. We argue that effective mobile manipulation requires not only decoupling, but also representations that support…

---

### [Control-Geometry Straightening for Sampling-Based Latent Planning](https://arxiv.org/abs/2609.35603v1)

- **arXiv**: `2609.35603v1`  |  **提交日期**: 2026-09-28
- **作者**: Ziang Fu, Ning Ning

Joint-embedding predictive architectures enable planning with latent world models, but accurate transition prediction alone does not ensure that the planning objective is easy to optimize. We introduce Control-Geometry Straightening (CGS), a single auxiliary loss that learns planner-friendly representations by directly straightening control geometry for sampling-efficient planning. CGS matches pairwise cosine similarities among actions to those among corresponding latent differences only using local transitions from pixel-action pairs. The loss can be applied across world-model architectures…

---

### [WorldPlay2: Extending Real-Time Interactive World Models in Control and Horizon](https://arxiv.org/abs/2609.35560v1)

- **arXiv**: `2609.35560v1`  |  **提交日期**: 2026-09-28
- **作者**: Haiyu Zhang, Wenqiang Sun, Tengfei Wang, Junta Wu, Jun Zhang, Yunhong Wang et al.

Interactive world models require responding in real time to versatile controls and maintaining long-horizon consistency. However, modeling heterogeneous controls remains difficult, while explosive contexts and unstable distillation impede achieving both long-horizon consistency and real-time responsiveness. In this paper, we present WorldPlay2, an interactive world model that couples a factorized hybrid control interface with a co-design of compressed memory and stable distillation. 1) Our factorized hybrid control interface integrates frame-aligned action control with structured semantic…

---

### [Graph World Models for Constrained Epidemic Policy Planning](https://arxiv.org/abs/2609.35545v1)

- **arXiv**: `2609.35545v1`  |  **提交日期**: 2026-09-28
- **作者**: Yiqi Su, Rashed Shelim, Lingyi Wang, Walid Saad, Naren Ramakrishnan

Epidemic policy planning often requires coordination between geographical regions, taking into account mobility-driven spillovers and how to make use of limited resources. Existing methods either lack action-conditioned models of coupled dynamics or cannot guarantee per-period feasibility. We present EpiMind, a graph world model framework for constrained epidemic policy planning across regions. A graph-factored recurrent state-space model generates joint policy-conditioned rollouts from regional latent beliefs, while graph-temporal ADMM optimizes regional interventions, enforces…

---

### [A.D.A.M.O. (Agent for language-Driven Actions with Multimodal Observations): A Visual-Symbolic Framework for Virtual Humans](https://arxiv.org/abs/2609.35463v1)

- **arXiv**: `2609.35463v1`  |  **提交日期**: 2026-09-28
- **作者**: Alessandro Emmanuel Pecora, Stefano Calzolari, Francesco Strada, Andrea Bottino

Creating believable vh requires the coherent integration of perception, reasoning, and action mediated by language. A central challenge is to combine these components into a control loop grounded in interactive 3D environments. To this end, we present A.D.A.M.O. (Agent for language-Driven Actions with Multimodal Observations), a visual-symbolic framework for language-driven vh that leverages a pretrained vlm with tool calling to unify perception, reasoning, and action within a single control loop. A.D.A.M.O. maintains a dual visual-symbolic world model that combines egocentric visual input…

---

### [From Pixel to Poses: Object-centric Tool Manipulation Learning from Human Demonstrations](https://arxiv.org/abs/2609.35375v1)

- **arXiv**: `2609.35375v1`  |  **提交日期**: 2026-09-28
- **作者**: Bangjun Wang, Longyan Wu, Yukun Wei, Shenghe Shao, Chaoyi Huang, Wenze Cui et al.

Scaling up robotic manipulation is primarily bottlenecked by the scarcity of real-world robot data. While recent approaches leverage human video demonstrations to mitigate this shortage, they remain computationally expensive and still rely on paired human-robot data for domain alignment. Although current state-of-the-arts excel at long-horizon tasks, they struggle with the delicate and precise control required for complex tool manipulation. To overcome these limitations, we introduce P2P-T, from Pixel to Poses for Tool Manipulation, a data-efficient, object-centric framework that learns tool…

---

### [RoGSW4RLD: Feed-Forward 4D Gaussian Lifting for Robot World Model Rollouts](https://arxiv.org/abs/2609.35311v1)

- **arXiv**: `2609.35311v1`  |  **提交日期**: 2026-09-28
- **作者**: Jin Hyun Kim, Min Young Kim, Soohwan Song, Daekyum Kim

Action-conditioned video world models predict future robot interactions from multiple cameras, yet their outputs remain disparate video collections rather than a shared metric scene queryable across viewpoints and time. While existing 4D reconstruction methods offer a path to spatialize these predictions, independently reconstructing and merging each camera stream fails to enforce cross-view consistency. This limitation is particularly detrimental when combining moving robot-mounted cameras with fixed external views. To address this, we introduce RoGSW4RLD, a feed-forward framework that lifts…

---

### [FlexiWorld: Learning and Planning via Flexible Action Chunks Across Multiple Time Scales](https://arxiv.org/abs/2609.35138v1)

- **arXiv**: `2609.35138v1`  |  **提交日期**: 2026-09-28
- **作者**: Shidu Ren, Qilin Gu, Zhenghao Ni, Junhan Sun, Jiaqi Wang, Damien Scieur et al.

Latent world models predict future states for goal-directed planning using action chunks spanning multiple primitive steps. Existing methods typically use fixed-length chunks and either omit goal-conditioned action generation or limit their supervision to short goal spans. We introduce FlexiWorld, a JEPA-based world model that combines mixed-span goal supervision with variable-length action chunks to improve long-horizon control. During training, we sample varying goal spans and randomly partition the actions into variable-length chunks. We jointly train the world model with a causal action…

---

### [OPIS: An Input-Grounded Benchmark for Multi-Object Memory in Video World Models](https://arxiv.org/abs/2609.35052v1)

- **arXiv**: `2609.35052v1`  |  **提交日期**: 2026-09-28
- **作者**: Hao Wang, Tao Yu, Liuzhou Zhang, HeXin Wang, Haopeng Jin, Yuxuan Zhou et al.

Video world models must preserve the visual state of the world over time, but existing evaluation protocols often rely on generated histories, video reference, or selected revisit viewpoints that can confound the assessment of a model's true memory capability. To address this, we introduce OPIS, an input-grounded benchmark that strictly anchors the assessment to a fixed set of object instances from the initial observation for evaluating multi-object memory in video world models. The OPIS dataset comprises 500 cases across real-world, embodied-robotic, and game-world domains, providing dense…

---

### [EMPIRIC: Experiment-Driven Learning of Residual World Models for Robot Planning](https://arxiv.org/abs/2609.35047v1)

- **arXiv**: `2609.35047v1`  |  **提交日期**: 2026-09-28
- **作者**: Yichao Liang, Amber Li, Dat Nguyen, Emily Bunnapradist, Michelangelo Naim, Sreela Kodali et al.

A robot should be able to learn through experiments how unfamiliar objects behave and interact, then plan with that knowledge. It need not start from scratch: physics engines supply knowledge of motion and contact, but can omit entire mechanisms, such as glue curing, water heating, or wind. We present EMPIRIC, an agent that learns a residual world model: a physics engine extended with code for the missing mechanisms. The learned programs can introduce new forces, constraints, and hidden state, and Bayesian inference estimates their parameters and states from noisy observations. The resulting…

---

### [JRDB-AVR: An Active Visual Reasoning Benchmark for Embodied Agents in Real-World Environments](https://arxiv.org/abs/2609.35032v1)

- **arXiv**: `2609.35032v1`  |  **提交日期**: 2026-09-28
- **作者**: Zhixi Cai, Fucai Ke, Sukai Huang, Maria Garcia de la Banda, Peter J. Stuckey, Gholamreza Haffari et al.

In complex embodied visual reasoning scenarios, an agent often has only a limited field of view, and the evidence needed to answer a question may be distributed across time, viewpoint, and interacting objects. A model may therefore give a plausible answer without ever observing the relevant object, time, or view that supports it. Current visual reasoning benchmarks largely evaluate passive observations and final answers, overlooking settings that require active reasoning and evidence acquisition. We introduce JRDB-AVR, a benchmark derived from existing real-world JRDB robotics data through a…

---

### [Proxy2World: Learning to Generate Worlds From Lightweight Proxies without Seeing Them](https://arxiv.org/abs/2609.35023v1)

- **arXiv**: `2609.35023v1`  |  **提交日期**: 2026-09-28
- **作者**: Hongli Xu, Weilong Yan, Anbang Wang, Chunyu Zou, Siyu Hong, Jingwei Huang

Lightweight scene proxies let creators control scene layout and motion while leaving room for imagination in appearance, lighting, and visual effects. However, a suitable proxy is not uniquely defined, making paired proxy-video data difficult to construct automatically at scale. We present Proxy2World, a controllable world model that learns these complementary capabilities from ordinary posed RGBD videos, without training on authored proxy-video pairs. The model jointly learns depth-conditioned RGB generation and joint RGBD generation through cross-modal flow matching. Learning both tasks…

---

### [WM-VLM: Probing Internal World Models for Interleaved Visual-Textual Reasoning](https://arxiv.org/abs/2609.34826v1)

- **arXiv**: `2609.34826v1`  |  **提交日期**: 2026-09-28
- **作者**: Yuheng Zha, Yilei Wang, Qiyue Gao, Junrong Chen, Yujia Wu, Zhengfeng Lai et al.

Humans often solve spatial problems by mentally simulating visual transformations. In contrast, conventional vision-language models (VLMs) reason primarily through language. We investigate whether VLMs can solve spatial problems by reasoning with both text and generated visual states. To this end, we introduce WM-VLM, which equips a pretrained VLM with a lightweight world model branch for generating intermediate visual states. Our two-stage training first teaches the model to generate the next visual state and then to use that state for reasoning. We programmatically construct spatial…

---

### [CoDrive: Cross-Vehicle World-Consistent Video Generation with Precise Trajectory Control for Cooperative Driving](https://arxiv.org/abs/2609.34749v1)

- **arXiv**: `2609.34749v1`  |  **提交日期**: 2026-09-28
- **作者**: Yu Meng, Baining Zhao, Junta Wu, Tengfei Wang, Rongze Tang, Haiyu Zhang et al.

Real-world driving is inherently multi-agent, yet most existing driving world models generate observations from a single ego vehicle. Independently extending them to multiple vehicles does not ensure that different agents observe a consistent shared world. We present CoDrive, a cross-vehicle, multi-view driving video generation framework that jointly generates observations of vehicles sharing the same dynamic scene with precise camera-trajectory control. CoDrive interleaves local self-attention, which models spatiotemporal dependencies among the views of each vehicle, with global…

---

### [Learning What to Recall: Adaptive Multi-Cue Episodic Memory for World Models](https://arxiv.org/abs/2609.34677v1)

- **arXiv**: `2609.34677v1`  |  **提交日期**: 2026-09-28
- **作者**: Beomsu Kim, Chieh-Hsin Lai, Bac Nguyen, Amir Bar, Jong Chul Ye, Yuki Mitsufuji

World models predict future observations from current experience and actions, yet prediction can depend on observations seen far in the past. Episodic memory preserves past observations for later recall; however, as memory accumulates, it raises a fundamental question: which memories are useful for the current prediction, and which available retrieval cues should be trusted to find them? This is challenging because fixed criteria based on recency, pose overlap, or visual similarity can be unreliable across environments and queries. We propose Future-Aware Recall (FAR), a framework that learns…

---

### [WorldAttention: An Efficient Attention Architecture for Interactive Video World Models](https://arxiv.org/abs/2609.34606v1)

- **arXiv**: `2609.34606v1`  |  **提交日期**: 2026-09-28
- **作者**: Zeyu Zhang, Jinyuan Mao, Dakai An, Wangbo Zhao, Hanfeng Lu, Jiasheng Tang et al.

Leveraging the paradigm of autoregressive diffusion, text-conditioned interactive video world models aim to simulate temporally coherent environments guided by textual instructions. While enabling low-latency, long-duration generation is pivotal for embodied AI and simulation-based planning, current frameworks primarily rely on sliding-window mechanisms to bound computational complexity. However, this approach inherently sacrifices historical context, undermining the long-range interactive capabilities. Conversely, maintaining a full-history cache remains computationally prohibitive and…

---

### [Shaping Persistent Representations from Independent Interactions](https://arxiv.org/abs/2609.34604v1)

- **arXiv**: `2609.34604v1`  |  **提交日期**: 2026-09-28
- **作者**: Ji Dai, Quan Fang, Junyu Gao, Rongfeng Guo, Haoyan Rong,  YipingHuang et al.

World models learn environment dynamics from interaction experience. These dynamics depend on the current state and actions, as well as on properties that persist across interactions. Yet standard predictive training can reduce error using local evidence alone, without organizing persistent information into reusable context. We introduce SPRII, a training principle that uses relations between interactions as weak supervision for persistent context while retaining the learner's native objective. For example, different trajectories of the same system share persistent properties even when their…

---

### [Precise Editing and Flexible Referencing for Interactable Worlds](https://arxiv.org/abs/2609.34470v1)

- **arXiv**: `2609.34470v1`  |  **提交日期**: 2026-09-28
- **作者**: Xinyao Liao, Xianfang Zeng, Zhu Liang, Zhoujie Fu, Qianxun Xu, Jiachi Liu et al.

We present EditWorld, a video world model for precise editing and flexible referencing in interactable worlds. Existing video world models primarily focus on navigation, letting users explore generated worlds but offering limited control over how existing world content is modified. EditWorld extends world modeling from exploration to precise modification by streaming editing instructions and reference images during autoregressive generation. To support these capabilities, EditWorld introduces Gated Causal Attention for temporally varying editing conditions and reference images, together with…

---

### [From World Models to World Action Models: Rethinking Next-State Prediction](https://arxiv.org/abs/2609.34414v1)

- **arXiv**: `2609.34414v1`  |  **提交日期**: 2026-09-28
- **作者**: Tingyu Yuan, Ziming Ji, Biaoliang Guan, Wen Ye, Wenrui Tian, Zhaopeng Gu et al.

Predicting the next state is a core paradigm of World Models for modeling physical dynamics, emphasizing prediction fidelity. As World Models evolve into World-Action Models (WAMs), existing methods still fix the next state before training as RGB, a single latent feature, or a static combination of predefined targets, thereby constraining action learning to the inductive biases preserved by a particular representation. To address this limitation, we propose CF-WAM, a dynamic next-state prediction framework that samples visual, semantic, geometric, and interaction projections of the same…

---

### [P2P: Cross-View Population Denoising for Unpaired Single-Cell Perturbation Response Prediction](https://arxiv.org/abs/2609.34391v1)

- **arXiv**: `2609.34391v1`  |  **提交日期**: 2026-09-28
- **作者**: Haojie Yang, Ran Su

AIVC (AI Virtual Cell) is a learned simulator of cellular behavior across conditions. Predicting how a cell population responds transcriptionally to a genetic perturbation is a core task. Perturb-seq records that response by destructive sequencing, so a control cell and a perturbed cell are never observed as a pair, and cells under one condition remain heterogeneous and noisy. Regression on individual cells absorbs sampling variation into the estimated effect, whereas interpretation requires the reproducible population effect. P2P (Perturbation-to-Perturbation) takes a stochastic cell-set…

---

### [LRC-JEPA: Disentangling Dynamics and Residual Context for Efficient World Models](https://arxiv.org/abs/2609.34375v1)

- **arXiv**: `2609.34375v1`  |  **提交日期**: 2026-09-28
- **作者**: Luzhe Huang, Lei Chu, Jingyi Liang, Yuhuan Zhao

Compact JEPA world models enable efficient latent-space planning, but low-dimensional representation trained under reward-free self-supervision must encode both action-conditioned dynamics and predictable visual context. This competition can entangle controllable state with high-rank nuisance appearance and degrade planning as scenes become more complex. We introduce LRC-JEPA, a lightweight end-to-end world model that routes information into a compact predictive latent $\mathbf{z}$ and learned-query residual-context embeddings $\mathbf{u}$. Only $\mathbf{z}$ is propagated by the dynamics…

---

### [When World Models Lie: Adaptive Safety Analysis Under Wrong Imaginations](https://arxiv.org/abs/2609.34300v1)

- **arXiv**: `2609.34300v1`  |  **提交日期**: 2026-09-28
- **作者**: John Cao, Somil Bansal

World models offer a powerful substrate for safety reasoning in high-dimensional robotic systems, but they are also fallible: their predictions can be biased, miscalibrated, or confidently wrong. This creates a central challenge for latent-space safety filters, which often learn Hamilton-Jacobi safety value functions on the dynamics of a world model. If the world model is incorrect, the resulting value function can inherit its errors and produce overconfident safety estimates. Existing latent safety filters often rely on auxiliary signals such as ensemble disagreement or value-target…

---

### [Dexterous Tactile World Model](https://arxiv.org/abs/2609.34286v1)

- **arXiv**: `2609.34286v1`  |  **提交日期**: 2026-09-28
- **作者**: Ziyao Zeng, Xiatao Sun, Hao Wang, Yueyang Pan, Zhengxiang Yu, Fengyu Yang et al.

World models for manipulation are typically trained from video, yet the events that determine how manipulation unfolds, such as making and releasing contact, are difficult to observe visually and are often easier to sense through touch. We present the Dexterous Tactile World Model (DTWM), a video world model for future-frame prediction of egocentric manipulation from both observed video and tactile signals from a glove worn on each hand. We condition a pretrained video diffusion transformer on each hand's tactile signal through a zero-initialized residual at the corresponding hand location in…

---

### [WorldWeave: Growing Persistent Geometric Worlds for Video Generation](https://arxiv.org/abs/2609.34221v1)

- **arXiv**: `2609.34221v1`  |  **提交日期**: 2026-09-28
- **作者**: Yifan Huang, Lifan Jiang, Qingyue Hao, Cheng Chen, Boxi Wu, Xiaoxue Ren et al.

Despite rapid progress, world models still lack explicit, persistent structural memory, making it difficult to preserve consistent world structure during continual scene expansion and cross-view revisits. To address this limitation, we present WorldWeave, a world generation framework that decouples world-state maintenance from visual rendering. Specifically, WorldWeave combines continual elevation-map generation with agent-guided scene organization and stitching to build an expandable explicit 3D world that incrementally extends structural memory while preserving existing structure. First,…

---

### [WorldGraph: Graph-Native World Modeling](https://arxiv.org/abs/2609.34159v1)

- **arXiv**: `2609.34159v1`  |  **提交日期**: 2026-09-28
- **作者**: Zezhong Ding, Yipeng Li, Xike Xie

World models infer latent states of an environment to capture its underlying dynamics and predict future evolution. Many real-world environments, however, are inherently relational and observed as evolving graphs, where entities, relations, and their properties change over time. Prior graph-related world models use graph structures to organize internal states or support task-specific reasoning, rather than treating an evolving graph itself as the modeled world. We instead study graph world modeling (GWM), where graph evolution itself constitutes the world dynamics. We formulate graph world…

---

### [CAST: Reconstruction-Coupled Acceleration of Interactive World Models](https://arxiv.org/abs/2609.34144v1)

- **arXiv**: `2609.34144v1`  |  **提交日期**: 2026-09-28
- **作者**: Leyang Chen, Junyi Wu, Fanqing Kong, Shaoqiu Zhang, Yulun Zhang

Interactive world models must respond quickly to controls while preserving scene consistency. Existing acceleration methods can miss heterogeneous control responses and spatial transport when recovering skipped features. We observe that interaction-induced feature changes correlate with approximation error, while low-frequency interpolation errors are phase-sensitive and show more predictable phase progression. These findings motivate CAST, a reconstruction-coupled inference framework. CAST selects anchors by interaction sensitivity and cross-layer coverage, reconstructs skipped residuals…

---

### [AD-E2E-JEPA: A Joint-Embedding Predictive Architecture For End-to-End Autonomous Driving](https://arxiv.org/abs/2609.34085v1)

- **arXiv**: `2609.34085v1`  |  **提交日期**: 2026-09-28
- **作者**: Haoran Zhu, Wancong Zhang, Yann LeCun, Anna Choromanska

Autonomous driving requires \textit{world models} that can understand the physical world, reason and plan, and operate safely. In this paper, we first systematically evaluate existing action-conditioned joint-embedding predictive architecture (JEPA) world models, including LeWM, DINO-WM, and JEPA-WM for end-to-end autonomous driving (E2EAD). To isolate world-model quality from policy learning, we employ a goal-conditioned zero-shot planning setting that evaluates these models using ground-truth future observations as goals, without training any driving policy. We find that existing JEPA-based…

---

### [Do World Models Learn Global Understanding?](https://arxiv.org/abs/2609.34058v1)

- **arXiv**: `2609.34058v1`  |  **提交日期**: 2026-09-28
- **作者**: Alexander Detkov, Matt Thomson

AI systems often feel brittle and fragmented. A large language model (LLM) may correctly explain a concept but fail to apply it, or follow safety instructions in one context but not another. This behavior suggests a general failure to lift local information to a global understanding. To gain fundamental insight, we frame "understanding" as learning constraints and propagating their consequences. We construct learning tasks on monoid worlds, sets of states connected by action transitions, where observed training transitions and an unseen constraint jointly determine held-out transitions.…

---

### [Behavioral Monitoring of JEPA World Models with Jacobian Centroids](https://arxiv.org/abs/2609.33940v1)

- **arXiv**: `2609.33940v1`  |  **提交日期**: 2026-09-27
- **作者**: Thomas Walker, Randall Balestriero, Richard Baraniuk

Detecting failures in World Model (WM)-based planning requires monitoring whether the model is behaviorally aligned with the current task, which in turn requires studying its internal representations. Here, we show that centroids---sub-component Jacobian row-sums---effectively identify the behavioral properties of WMs, complementing traditional activation-based knowledge signals. The centroids of a model are easily computed through Jacobian vector products and characterize how the model organizes the geometry of its input space, yielding an efficient perspective on internal representations,…

---

### [ReDrive: Shaping Representations with World Modeling for End-to-End Driving](https://arxiv.org/abs/2609.33854v1)

- **arXiv**: `2609.33854v1`  |  **提交日期**: 2026-09-27
- **作者**: Yueting Zhu, Shaoyu Chen, Yuehao Song, Hui Sun, Qian Zhang, Wenyu Liu et al.

Driving policies require capabilities of scene understanding and future evolution prediction. To achieve this goal, current end-to-end models typically construct complex perception-planning pipelines or introduce world models that explicitly predict future states, resulting in a complex system architecture. Inspired by the transferability of general-purpose visual representations, we argue that combining sufficiently strong visual representations with representation world modeling can support effective planning without relying on complex inference-time auxiliary modules. Based on this…

---

### [ViBR-WM: Visual Bayesian Regression for World Modeling](https://arxiv.org/abs/2609.33844v1)

- **arXiv**: `2609.33844v1`  |  **提交日期**: 2026-09-27
- **作者**: Jifan Li, Ning Ning

Modeling temporal dependence and uncertainty is central to forecasting with world models. The Visual Bayesian Regression World Model combines visual features, physical histories and known covariates through interpretable regression, within a modular architecture supporting trend, seasonal and cycle dynamics. Visual compression reduces representation dimension, while Bayesian variable selection reduces active regression dimension. Posterior prediction combines forecasts across predictor subsets using their posterior probabilities as weights and accounts for parameter uncertainty and future…

---

### [Achieve What You Imagined: Learning to Align Actions with Visual Plans](https://arxiv.org/abs/2609.33832v1)

- **arXiv**: `2609.33832v1`  |  **提交日期**: 2026-09-27
- **作者**: Yuheng Qiao, Ziran Wei, Xiaohan Wang, Daqiang Guo, Yichen Luo, Zhibo Pang et al.

World-action models can jointly predict future visual observations and robot actions. However, discrepancies may exist between their visual predictions and the consequences implied by generated actions. We observe that WAMs can often generate visually plausible task-completion outcomes before producing action sequences that reliably achieve them. Consequently, we treat the WAM-generated visual prediction as a goal-conditioned visual proposal rather than a directly executable plan. We use a frozen action-conditioned world model to predict action-conditioned consequences and construct feedback…

---

### [MomWorld: Momentum-Aware Latent World Model for Long-Horizon Autonomous Driving](https://arxiv.org/abs/2609.33737v1)

- **arXiv**: `2609.33737v1`  |  **提交日期**: 2026-09-27
- **作者**: Ziying Song, Shengkai Zhang, Lei Yang, Haozhuang Chi, Yuchen Liu, Jiangtao Su et al.

Long-horizon planning enables autonomous vehicles to anticipate scene evolution and potential risks, supporting safe and stable decisions in complex interactions. However, existing methods struggle to propagate motion trends from observed history into the future. Long rollouts based on a single latent state may further attenuate useful dynamics, retain stale motion patterns, and disrupt reliable near-term plans. We introduce MomWorld, a momentum-aware latent world model for long-horizon planning. MomWorld extracts scene motion trends from historical-to-current observations and propagates…

---

### [ALDER: Discovering the Laws of a World by Acting in It](https://arxiv.org/abs/2609.33728v1)

- **arXiv**: `2609.33728v1`  |  **提交日期**: 2026-09-27
- **作者**: Teng Cao, Yu Deng, Quentin Delfosse, Kristian Kersting

Reliable world models should not only predict future states but express how actions change the world in an explicit, transparent and testable form, such as equations. Yet methods that rely on a fixed set of trajectories cannot distinguish equally good competing hypotheses, while searches over a fixed set of predefined candidates cannot discover equations outside the initial hypothesis space. We introduce ALDER (Action-guided Law Discovery, Evaluation, and Revision), a method that actively proposes novel experiments to test and revise models. Specifically, ALDER proposes parametric equations;…

---

### [CompoWorld: Compositional Environment Scaling for General Agents](https://arxiv.org/abs/2609.33665v1)

- **arXiv**: `2609.33665v1`  |  **提交日期**: 2026-09-27
- **作者**: Xiao-Wen Yang, Weiyi Xu, Wen Da, Hang Xu, Canwei Li, Hong-Jie You et al.

Automatically generated environments provide a scalable source of interaction data for training general agents. However, existing approaches mainly generate tasks within a single environment, while real-world workflows require agents to connect information and actions across multiple services. We introduce Compositional Environment Scaling (\textbf{CompoWorld}), which expands the task space by composing a finite library of reusable services. Coding agents turn tool specifications into verified services with typed states and shared interfaces, while a world model handles tools that cannot be…

---

### [Beyond One-Step Accuracy: State-Affine Latent Transition for Reliable Visual Planning](https://arxiv.org/abs/2609.33595v1)

- **arXiv**: `2609.33595v1`  |  **提交日期**: 2026-09-27
- **作者**: Boyuan Zhang, Yingjun Du, Xiantong Zhen, Ling Shao

Joint-embedding world models enable visual planning by learning action-conditioned dynamics in latent space. Yet they are commonly trained for one-step prediction on encoded states, while planning recursively applies the learned transition to its own predictions. One-step accuracy therefore does not capture how prediction errors propagate under recursive rollout. We decompose multi-step rollout error into the errors introduced at individual steps and their propagation through subsequent transitions. We show that state-affine dynamics are precisely the differentiable transitions with…

---

## 📅 2026-09-16

### [Intrinsic Motivation in Reinforcement Learning: A Research Agenda for Adaptive Self-Organisation](https://arxiv.org/abs/2609.17325v1)

- **arXiv**: `2609.17325v1`  |  **提交日期**: 2026-09-15
- **作者**: Anatoly Belikov

Biological cells can be viewed as individual, interacting agents whose collective dynamics give rise to adaptive behaviour at multiple levels of organisation, from individual cells through tissues to whole multicellular organisms. In this perspective and tutorial article we discuss whether intrinsic rewards in artificial neural systems can support adaptation, functional specialisation and higher-level self-organisation without a shared external objective. We review empowerment, curiosity, learning progress, information gain, unsupervised skill discovery, mutual information estimation and the…

---

### [Unifying Semantic Priors and High-Frequency Traces: Enhancing V-JEPA with Mixture-of-Experts for Robust Synthetic Image Forensics](https://arxiv.org/abs/2609.16778v1)

- **arXiv**: `2609.16778v1`  |  **提交日期**: 2026-09-15
- **作者**: Simone Teglia, Irene Amerini

The unchecked proliferation of manipulated images on social media platforms has increased the spread of misinformation, posing a severe threat to public trust and information integrity. Modern deepfake detectors typically rely on Vision Transformers (ViTs) to capture the low-level inconsistencies that characterize fully synthetic or locally tampered images. However, the global understanding of such foundation models is not enough to discriminate alone between real and fake multimedia content, especially in challenging scenarios where images are compressed or transmitted through social media.…

---

### [CorrRisk-WM: Corridor-Conditioned Risk World Modeling for Safety-Critical Trajectory Planning](https://arxiv.org/abs/2609.16724v1)

- **arXiv**: `2609.16724v1`  |  **提交日期**: 2026-09-15
- **作者**: Tingyu Guo, Reza Langari

Safe local planning requires forecasting surrounding-agent motion and evaluating candidate-specific risks, since identical agent motion can pose different risks to different ego trajectories. We present CorrRisk-WM, a planning-oriented partial world model coupling environment evolution with supervised intrusion and near-miss prediction over bounded candidate-trajectory corridors. A latent environment model recursively predicts agent states and updates agent-agent and agent-map interactions. Each candidate queries the evolving environment through footprint- aware geometry and learned…

---

### [World Models for Embodied Intelligence: From Plausible to Controllable to Actionable](https://arxiv.org/abs/2609.16697v1)

- **arXiv**: `2609.16697v1`  |  **提交日期**: 2026-09-15
- **作者**: Nanjie Yao, Hao Wang, Chong Cheng, Zhikang Chen, Wenzhe Li, Jiafei Lyu et al.

World models connect perception and decision-making in embodied intelligence by maintaining hidden state, anticipating consequences, comparing interventions, and adapting when execution departs from expectations. Although progress is often measured by visual fidelity, their value lies in improving behavior. Before reaching for a cup, a person anticipates its weight and resistance to grasping, shaping the hand before contact. Such anticipation is coarse and rarely pictorial, yet it guides action. This raises a central question: which predictive capabilities improve behavior? Existing surveys,…

---

### [AI for Games in the Foundation Model Era](https://arxiv.org/abs/2609.16679v1)

- **arXiv**: `2609.16679v1`  |  **提交日期**: 2026-09-15
- **作者**: Meng Luo, Yanlin Li, Hao Li, Hongzhan Lin, Pengfei Zhou, Tianjie Ju et al.

Foundation models, alongside advances in learned game-world models, are reshaping AI across the game lifecycle. Beyond playing games, recent systems model players and game dynamics, support design and development, adapt player-facing experiences at runtime, and evaluate resulting artifacts. Yet these directions have evolved largely separately, obscuring which capabilities transfer across settings and which remain tied to particular games, engines, interfaces, or player populations. We organize the literature into six roles according to the immediate use of AI output: playing and acting;…

---

### [Autonomous Droplet Navigation via Model-Based Reinforcement Learning](https://arxiv.org/abs/2609.16369v1)

- **arXiv**: `2609.16369v1`  |  **提交日期**: 2026-09-14
- **作者**: Rajneesh Anand, Mayuresh V. Kothare

Precise manipulation of liquid droplets underpins lab-on-a-chip platforms for diagnostics, chemical synthesis, and biological assays. Yet autonomous droplet transport through confined geometries of varying complexity remains an open challenge. Droplets exhibit contact-angle hysteresis, deformability, and capillary pinning, which make their response to actuation nonlinear and history dependent, that classical controllers and pre-programmed trajectories cannot cope in multi-turn environments. Here we demonstrate autonomous navigation of a liquid droplet through geometries of increasing…

---

### [When Should a World Model Move? Loss-Conditioned State Execution](https://arxiv.org/abs/2609.15801v1)

- **arXiv**: `2609.15801v1`  |  **提交日期**: 2026-09-14
- **作者**: Jintao Xu, Zhengyu Chen, Ben Zhang, Yongzhi Qi, Jianshen Zhang

We introduce loss-conditioned state execution, a model-agnostic method that decides whether to execute a world model's fixed feasible proposal or retain the current state. Predictive informativeness alone, however, does not establish whether an update will reduce downstream loss. Occurrence ranking can approach perfection while persistence remains the unique absolute-loss Bayes action. Two transition laws can also share occurrence information and conditional variance yet require opposite absolute-loss decisions. We formalize state movability as the existence of a loss-reducing feasible…

---

### [When the World Lies: Backdoor Attacks on Latent World Models for Downstream Control](https://arxiv.org/abs/2609.15781v1)

- **arXiv**: `2609.15781v1`  |  **提交日期**: 2026-09-14
- **作者**: Roberto Riaño, Gorka Abad, Stjepan Picek, Aitor Urbieta

Pretrained world models, learned simulators that encode an observation into a latent state and predict how it evolves under actions, are beginning to be reused as off-the-shelf dynamics backbones for control, like pretrained encoders and language models are reused today. We show that this reuse opens a supply-chain backdoor: an adversary who controls only a released checkpoint can hijack the downstream controller, even though the victim trains and evaluates entirely on clean data and never sees the trigger. The attack encodes no explicit trigger-to-action rule. Instead, the poisoned model…

---

### [From Prediction to Decision: World-Model-Guided Action Selection for Continuous Pile Excavation](https://arxiv.org/abs/2609.15382v1)

- **arXiv**: `2609.15382v1`  |  **提交日期**: 2026-09-14
- **作者**: Ailing Zhang, Fan Gao, Song Zhang, Kawa Leong, Ziyu Wu, Yafei Wang

Wheel-loader excavation is a sequential decision problem in which every scoop changes the terrain available to subsequent actions. A practical world model must predict action consequences accurately, rank candidates in real time, and operate inside the closed loop of a full-size machine. We present the World-Action Model (WAM), which proposes multiple scoops, rejects geometrically inadmissible candidates, jointly predicts signed terrain change and loaded volume, executes the candidate with the largest predicted load, and replans from the newly observed terrain. On 32 geometry-disjoint…

---

### [Math for AI safety: an invitation for mathematicians](https://arxiv.org/abs/2609.15289v1)

- **arXiv**: `2609.15289v1`  |  **提交日期**: 2026-09-14
- **作者**: Lionel Levine

Artificial intelligence threatens to outrun human understanding and control. New mathematics is needed to design AI that is legible, steerable, and cooperative with humanity. I organize this invitation by mathematical field, so you can turn straight to your own: logic and game theory for cooperation; probability for agency and world-models; algebra and representation theory for learned features; analysis and geometry for generalization and training dynamics. Each section ends with an open problem that is accessible to a working mathematician with no prior experience in AI safety.

---

### [Legislating World-Model-Based Planning with Legal Reasoning](https://arxiv.org/abs/2609.15113v1)

- **arXiv**: `2609.15113v1`  |  **提交日期**: 2026-09-14
- **作者**: Dylan Waldner, Yiannis Kantaros, Guido Governatori, Risto Miikkulainen, Amir Banifatemi

As robotic systems grow more general, legal norms are needed to integrate them into society. This paper extends the isomorphism problem of aligning legal source texts with their encodings, and measures two key challenges to robot normative control: (1) the \textit{grounding isomorphism gap}, where perception error grounds false atoms for legal reasoning, and (2) the \textit{ontological isomorphism gap}, where one legal conclusion admits many faithful translations into planning constraints. The paper introduces a legal planning stack that employs Defeasible Deontic Logic (DDL) to constrain a…

---

### [One Model, Two Physical Stories: Auditing Misalignment in Multi-Modal World Modeling](https://arxiv.org/abs/2609.14833v1)

- **arXiv**: `2609.14833v1`  |  **提交日期**: 2026-09-13
- **作者**: Geigh Zollicoffer, Minh Vu, Rajiv Ranasinghe, Manish Bhattarai

World models, systems that generate what happens next given current environmental conditions, are increasingly being implemented with multi-modal generation in mind. However, generating multiple modalities simultaneously, such as visual simulations alongside physical state predictions in the form of text, introduces the risk of cross-modal inconsistency. Tested separately, both outputs may look convincing while still disagreeing: a model can calculate that a ball should rebound in one modality, then generate no rebound in another modality, to say nothing of diverging from real-world dynamics…

---

### [An immune world model for multiscale forecasting and therapeutic hypothesis generation](https://arxiv.org/abs/2609.14709v1)

- **arXiv**: `2609.14709v1`  |  **提交日期**: 2026-09-13
- **作者**: Taoyong Cui, Xi Wang, Zonghang Li, Jinchao Ding, Lingsen You, Yuzhi Xu et al.

Immune therapies act across cell-intrinsic programs, tissue ecosystems, and patient-specific immune states, yet most predictors address these scales separately. We used a governed evolutionary AI Scientist to construct the Immune World Model, an action-conditioned model that learns how interventions move immune states across cellular, tissue, and individual levels. The Immune World Model--building Scientist searched candidate architectures and workflows, and the resulting world model was frozen before independent confirmation. The frozen model generalized to unseen interventions and…

---

### [Schema-Adaptive Action-Conditioned JEPA for Cross-Machine CNC Transfer under Partial Sensor Overlap](https://arxiv.org/abs/2609.16071v1)

- **arXiv**: `2609.16071v1`  |  **提交日期**: 2026-09-13
- **作者**: Ayoub Louaye Bouaziz, Matthieu Ostertag, Anton Demasles

Cross-machine deployment of industrial world models requires transfer across changes in dynamics, sensing interfaces, sampling regimes, and control units. We study a schema-adaptive action-conditioned Joint-Embedding Predictive Architecture (SAAC-JEPA) for CNC dynamics, where the source machine has 17 canonical sensor channels and the target shares only 10. Evaluation uses group-disjoint source splits, source-only normalization, held-out self-supervised validation, unit audits, and a sealed target test after model locking. Across five seeds, JEPA pretraining gives no clean-source forecasting…

---

### [GLAM: Training a latent world model over global spatiotemporal memory for active exploration and navigation](https://arxiv.org/abs/2609.14561v1)

- **arXiv**: `2609.14561v1`  |  **提交日期**: 2026-09-13
- **作者**: I-Tak Ieong, Ruizhi Feng, Zhaoyang Lu, Yifei Cao, Jiayao Zhao, Leon Li et al.

Active exploration and semantic navigation require an embodied agent to build memory from partial observations, predict how the evolution of observed spatial memory may support future motion, and convert that prediction into actionable plans. We present GLAM, a goal-conditioned latent world model trained over global spatiotemporal memory, and GLAM NAV, the complete navigation system built around it. Given historical map tokens, a navigation goal, and the current robot pose, GLAM jointly predicts future map representations and robot-centric waypoint latents, allowing future spatial context and…

---

### [AlayaVista: Streaming World Modeling from Panoramic States to Perspective Video](https://arxiv.org/abs/2609.14462v1)

- **arXiv**: `2609.14462v1`  |  **提交日期**: 2026-09-13
- **作者**: Jiaming Tan, Mingliang Zhai, Zhen Li, Yuwei Wu, Chuanhao Li, Kaipeng Zhang

Interactive video world models must maintain broad scene context under camera motion while producing high-fidelity observations with low latency. Existing approaches face a representation trade-off: perspective models operate on local views and must preserve off-screen content over long rollouts, whereas broader spatial coverage is typically obtained by synthesizing full-sphere videos or constructing explicit 3D representations. Motivated by the complementary roles of global context and selective local acuity in visual perception, we present AlayaVista, a camera-controllable streaming video…

---

## 📅 2026-09-11

### [Distributed Optimization of Modular Production Systems using Model-based Reinforcement Learning with Inverse Models](https://arxiv.org/abs/2609.11615v1)

- **arXiv**: `2609.11615v1`  |  **提交日期**: 2026-09-10
- **作者**: Andreas Schwung, Steve Yuwono, Sofiene Lassoued, Dorothea Schwung

This paper presents a novel approach for data-driven self-learning control of highly flexible, modular manufacturing systems. Specifically, we employ a novel framework for model-based reinforcement learning which introduces approximate inverse process models within the training of reinforcement policies. This approach disentangles the learning of actuation dynamics and the dynamics in state space, resulting in RL-based training solely within the task space. We propose a lightweight feedforward architecture for approximate inverse models and integrate them within the policy network of standard…

---

### [World in World: Explore the World with World Models](https://arxiv.org/abs/2609.11548v1)

- **arXiv**: `2609.11548v1`  |  **提交日期**: 2026-09-10
- **作者**: Chenxi Song, Yanming Yang, Chi Zhang

Autoregressive video world models enable interactive, long-horizon exploration, but flexible control remains challenging. Exploring a source video from new viewpoints requires the generated rollout to remain synchronised with the recorded event, place observed content in the requested view, plausibly complete newly exposed regions, and recover previously generated appearance on revisits. Existing methods typically address these requirements through task-specific modules or additional training. We present World in World, a training-free inference-time interface that converts heterogeneous…

---

### [Recursive Code World Models: Building Complex Worlds through Recursive Scene Programs](https://arxiv.org/abs/2609.11499v1)

- **arXiv**: `2609.11499v1`  |  **提交日期**: 2026-09-10
- **作者**: Zhiqi Li, Yuxuan Liao, Bo Zhu

Code world models represent worlds as executable programs, but this representation alone does not determine how to construct a complex world. We introduce Recursive Code World Models (RCWM), a framework for reconstructing complex 3D worlds in code from a single reference image. RCWM couples a Recursive Scene Program (RSP) representation with a construction solver that recursively calls itself. An RSP represents the executable world as compositional scene code, while each solver call follows the same complete process: establish the whole, recursively reconstruct unresolved parts, and revisit…

---

### [FARM: Reading Failure Signals from the Internal Predictive States of a Frozen Robotic World Model](https://arxiv.org/abs/2609.11445v1)

- **arXiv**: `2609.11445v1`  |  **提交日期**: 2026-09-10
- **作者**: Haoran Pei, Mingrui Luo, Senbao Wang, Haoran Lv, Jie Guo, Sheng Zhong et al.

Reliable robot deployment requires online failure monitoring, yet existing monitors mainly derive risk from proxy signals or train dedicated monitoring components. We ask whether the internal predictive states of a frozen pretrained robotic world model already contain directly decodable failure information. Failure-Aware Readout from World Models (FARM) trains only a 33,985-parameter supervised readout over frozen VLA-JEPA predictive states, producing step-wise failure scores and causal trajectory risk. Five-fold out-of-fold evaluation across seven source tasks reaches 85.68/88.59 pooled…

---

### [Measuring the Value of World-Model Updates: A Counterfactual Utility Protocol for Continual Adaptation](https://arxiv.org/abs/2609.10954v1)

- **arXiv**: `2609.10954v1`  |  **提交日期**: 2026-09-10
- **作者**: Anqi Peter Li, Kaden Kim

Continual world models must decide whether new data justify changing the model. Fixed replay schedules and prediction-error triggers specify when to update, but neither reveals the value of an individual update: one deployment run cannot show how the same model would have performed at that moment had it held its parameters. We introduce the fork ledger, which branches a deployment stream at pre-registered decision points into matched update and hold continuations under common random numbers. It evaluates both continuations on the same episodes and records $ΔR = R_{\mathrm{update}} -…

---

### [Compact Visuotactile World Models for Lifting: Prediction, Reward Alignment, and Force Constraints](https://arxiv.org/abs/2609.09597v2)

- **arXiv**: `2609.09597v2`  |  **提交日期**: 2026-09-09
- **作者**: Qinzhen Ma

Accurate tactile forecasts need not improve force-constrained control. We study a 652,157-parameter action-conditioned visuotactile world model with matched behavior cloning, policy learning in imagination, independent reactive implicit Q-learning, and model-assisted force feedback. A fixed protocol executes 34 policies on 120 fresh MuJoCo environments spanning geometry and physical-parameter shifts, plus 324 independently replayed action branches on 12 additional ID environments. Visuotactile dynamics reduce force action-effect MAE from 0.413 N for persistence to 0.338 N. Model-assisted…

---

## 📅 2026-09-10

### [Programmable World Model](https://arxiv.org/abs/2609.10540v1)

- **arXiv**: `2609.10540v1`  |  **提交日期**: 2026-09-09
- **作者**: Zheng-Hui Huang, Guixu Lin, Jiacheng Lin, Yi-Chuan Huang, Ruihan Yu, Muyao Niu et al.

Recent video world models generate increasingly realistic and interactive visual experiences, yet lack reliable mechanisms for maintaining persistent world state and enforcing programmable rules over extended interactions. We introduce Programmable World Model, a framework that decouples world-state evolution from visual observation generation. An agent translates natural-language instructions into executable programs that specify entity states and state-transition rules, enabling direct control over individual entities and their interactions. A lightweight engine executes these programs to…

---

### [DUET-DINO: Simultaneous Cross-View World Modeling for Latent Planning in Robot Manipulation](https://arxiv.org/abs/2609.10506v1)

- **arXiv**: `2609.10506v1`  |  **提交日期**: 2026-09-09
- **作者**: Nisarga Nilavadi, Ralf Römer, Moritz Reuss, Michael Krawez, Tobias Jülg, Angela P. Schoellig et al.

Action-conditioned latent world models predict future visual representations, enabling zero-shot goal-conditioned robot planning and control. However, their predictions for fine-grained spatial and rotational actions are unreliable for full 7-DoF end-effector control. To address this gap, we introduce DUET-DINO, a simultaneous cross-view latent world model that jointly learns action-conditioned predictions from static side- and wrist-camera observations through cross-view conditioning. By exploiting complementary global scene and gripper-centric information, DUET-DINO enables latent planning…

---

### [Semigroup-JEPA: Latent Dynamics Consistency for Zero-Shot Physics Generalization](https://arxiv.org/abs/2609.10464v1)

- **arXiv**: `2609.10464v1`  |  **提交日期**: 2026-09-09
- **作者**: Andy Zeyi Liu, Haoran Sun, Lucas Baker, Randall Balestriero, John Sous

Joint-Embedding Predictive Architecture (JEPA) world models learn a compact latent representation of the world that supports prediction and planning, but their capability to learn physics and generate physically realistic dynamics remains hitherto untested. In this work, we introduce SemiGroup-JEPA (SG-JEPA), which extends the LeWorldModel framework by supplying the parameter governing the physics to the temporal model via action-conditioning and jointly training an encoder and predictor through an autoregressive latent rollout. To evaluate the model's ability to generalize out of…

---

### [HaWMPO: Hallucination-Aware World Model-based Policy Optimization for Generalist Robot Policy](https://arxiv.org/abs/2609.09941v1)

- **arXiv**: `2609.09941v1`  |  **提交日期**: 2026-09-09
- **作者**: Zengjue Chen, Peidong Liu, Jiawei Li, Qi Wang

Generalist robot policies have demonstrated strong generalization across robotic manipulation tasks, yet their success rates remain limited in com- plex long-horizon scenarios. Recent methods improve Visual-Language-Action (VLA) policies through online reinforcement learning on real robots, but such training relies on costly physical interactions, suffers from low sample efficiency, and may introduce hardware and safety risks. World models offer a promising alternative by enabling policy optimization with imagined rollouts. However, long-horizon rollouts generated by world models often suffer…

---

### [Proof-Carrying Cognition: Closing the Verification Gap with Reality-Settled Reward](https://arxiv.org/abs/2609.09776v1)

- **arXiv**: `2609.09776v1`  |  **提交日期**: 2026-09-09
- **作者**: Eshwar Reddy M, Sourav Karmakar

Frontier gains in language-model reasoning come from reinforcement learning on reasoning traces and are concentrated in domains with a cheap, sound verifier. We argue the field's binding constraint is the verification gap: no scalable, incorruptible reward for reasoning outside formal domains. We make four contributions. (1) Theory: in a joint-Gaussian model of best-of-N selection, verifier-gold correlation rho is the exact exchange rate between test-time compute and capability, and an unsound verifier pays a polynomial penalty N^(1/rho^2); a margin-free copula form predicts realized…

---

### [Arti-JEPA: Adapting Video World Model to Real-Time MRI of the Vocal Tract for Speech-Production Analysis](https://arxiv.org/abs/2609.09757v1)

- **arXiv**: `2609.09757v1`  |  **提交日期**: 2026-09-09
- **作者**: Hong Nguyen, Sean Foley, Christina Hagedorn, Yijing Lu, Sudarsana Reddy Kadiri, Dani Byrd et al.

Real-time MRI (rtMRI) captures the dynamics of the entire vocal tract during speech, but labeled data are scarce and the modality - single-slice, grayscale, low-resolution - differs substantially from the natural videos that video foundation models are trained on. We introduce Arti-JEPA, a joint embedding predictive architecture to model vocal tract rtMRI by continuing its self-supervised objective on about 62h of unlabelled vocal-tract videos, and evaluate the frozen representation on three tasks: cross-domain phoneme prediction (on typical speakers), fluent-vs-disfluent classification (a…

---

### [Seven Sources of Physical AI Capability Formation](https://arxiv.org/abs/2609.09627v1)

- **arXiv**: `2609.09627v1`  |  **提交日期**: 2026-09-09
- **作者**: Gang Chen

Capabilities relevant to Physical AI can arise from materially different formation histories, yet existing taxonomies organized by morphology, architecture, learning algorithm, task, or domain do not directly answer what gives rise to a capability. We define a capability-formation source as a factor materially contributing to capability formation, distinct from components or construction steps. We identify seven non-exclusive sources: Recorded-Experience (RE), Predictive-Modeling (PM), Evaluative-Interaction (EI), Surrogate-Environment (SE), Mechanism-Grounded (MG), Embodied-Coupling (EC),…

---

### [Compact Visuotactile World Models for Lifting: Prediction, Reward Alignment, and Force Constraints](https://arxiv.org/abs/2609.09597v1)

- **arXiv**: `2609.09597v1`  |  **提交日期**: 2026-09-09
- **作者**: Qinzhen Ma, Sida Peng

Accurate contact prediction is useful for robotic manipulation only if it supports effective decisions. We investigate this connection using a compact, randomly initialized visuotactile world model, trajectory-level uncertainty calibration, and behavior-initialized actor-critic learning in imagination. On 160 MuJoCo Lift episodes, adding touch reduces endpoint-force prediction error from 1.058 to 0.228 N and interval-peak error from 2.724 to 0.523 N across three training seeds. However, tactile persistence achieves lower errors of 0.095 and 0.498 N, respectively. Two exploratory control…

---

### [MotionBlind: Probing the Illusion of Motion Understanding in Video-LLMs](https://arxiv.org/abs/2609.09528v1)

- **arXiv**: `2609.09528v1`  |  **提交日期**: 2026-09-08
- **作者**: Dhairya Bhatia, Bishoy Galoaa, Oliver Fritsche, Shahid Kamal, Muhammad Obaidullah Abdul Salam, Umer Saleem et al.

Video large language models (Video-LLMs) are increasingly used as the perceptual front end of world models, a role that assumes they can read motion: how fast something moves, which way it travels, how hard it is pushed. We show they cannot. A Video-LLM can watch two clips of the same person in the same room, name every object in both, and still fail to say which clip moves faster. We introduce MotionBlind, a contrastive benchmark of self-recorded video for physically grounded motion(speed, magnitude, and direction), the variables a world model must predict. Each instance is a pair of…

---

### [Valerant: An Automatic Navigable Game Map Generator via Action-Conditioned World Model Exploration](https://arxiv.org/abs/2609.09418v1)

- **arXiv**: `2609.09418v1`  |  **提交日期**: 2026-09-08
- **作者**: Yiran Qiao, Feng Wang, Jing Ma

World Action Models (WAMs) couple predictive world modeling with action generation, allowing anticipated future states to guide agent behavior. Although WAMs are rapidly advancing embodied AI, general-purpose counterparts remain largely unexplored in games. Existing game-oriented approaches often combine action-conditioned world models with external policies and reward functions to realize WAM-like decision-making, yet they operate mainly in 2D visual observation space and do not instantiate persistent 3D geometry. Extending this paradigm to 3D games introduces a distinct challenge. In…

---

### [Hi-FLoop: Hierarchical State-Feedback Loops for Multi-Timescale World Modeling](https://arxiv.org/abs/2609.08796v2)

- **arXiv**: `2609.08796v2`  |  **提交日期**: 2026-09-08
- **作者**: Rx Fan, Z Han

Multi-agent traffic simulation seeks diverse, coordinated, and physically realistic futures from maps and observed history. Long-horizon closed-loop generation must reconcile multiple decision time scales while its context evolves with generated states. Existing methods often unfold long futures from an initial scene and resolve intent, interaction, and motion monolithically, weakening cross-scale consistency and adaptation. Multimodal rollout poses a further consistency problem: independently reselecting modes across agents or commits can stitch together incompatible futures instead of…

---

## 📅 2026-09-09

### [SyncWorld: Visual Calibration Enables World Models as Zero-Shot Simulators](https://arxiv.org/abs/2609.09155v1)

- **arXiv**: `2609.09155v1`  |  **提交日期**: 2026-09-08
- **作者**: Yuncong Yang, Zhengtao Han, Furkan Ozyurt, Zeyuan Yang, Han Yang, Junyi Cao et al.

World models are increasingly used as policy-in-the-loop imagination environments, where reliable rollouts require fine-grained controllability with respect to low-level robot actions. A key obstacle to scaling such models in robotics is that actions are not a universal language in pixel space: changes in visual environment, camera view, robot placement, or embodiment alter how the same numerical action manifests visually, leading to conflicting supervision under mixed training and brittle generalization at deployment. We introduce SyncWorld, an action-conditioned world model that serves as a…

---

### [Earth System World Model for What-If Simulations: A Case Study for Terrestrial Ecosystems](https://arxiv.org/abs/2609.08855v1)

- **arXiv**: `2609.08855v1`  |  **提交日期**: 2026-09-08
- **作者**: Zhihao Wang, Ruichen Wang, Ruohan Li, Lei Ma, George Hurtt, Xiaowei Jia et al.

Machine learning emulators have become essential for accelerating expensive Earth-system simulations, but most existing approaches remain passive forecasters: they reproduce simulator trajectories under prescribed forcings without an explicit interaction mechanism for user-specified interventions. This limits their use in interactive scientific workflows and Earth-system digital twins, where users often need to explore how a system would respond if selected state components were changed. We propose an action-conditioned world-modeling framework for Earth-system emulation that reformulates…

---

### [Hi-FLoop: Hierarchical State-Feedback Loops for Multi-Timescale World Modeling](https://arxiv.org/abs/2609.08796v1)

- **arXiv**: `2609.08796v1`  |  **提交日期**: 2026-09-08
- **作者**: Rx Fan, Zhan H

Multi-agent traffic simulation seeks diverse, coordinated, and physically realistic futures from maps and observed history. Long-horizon closed-loop generation must reconcile multiple decision time scales while its context evolves with generated states. Existing methods often unfold long futures from the initial scene and resolve intent, interaction, and motion monolithically, weakening cross-scale consistency and adaptation. We present HI-FLOOP, a branch-consistent multi-timescale state-feedback framework. Eight scene-level Worlds represent joint hypotheses, and all agents share the selected…

---

### [A Two-Stage, Model-Based Reinforcement Learning Approach for Active Flow Control of Bluff Body Wakes](https://arxiv.org/abs/2609.08436v1)

- **arXiv**: `2609.08436v1`  |  **提交日期**: 2026-09-08
- **作者**: Aayushman Sharma, Suman Chakravorty

This paper develops a data-driven, output-feedback approach to the infinite-horizon optimal control of high-dimensional nonlinear systems with unknown and unstable equilibria, using sparse partial observations. The approach builds on the transfer-plus-regulation decomposition of the infinite-horizon problem: a finite-horizon nonlinear transfer drives the system into a region where the dynamics are well-approximated by a linear model about the unknown operating point, and an infinite-horizon linear regulator identified within that region completes stabilization. We extend this framework to the…

---

### [VeriScene: Reconstructing Crime Scenes from Legal Evidence via World-Model Agent](https://arxiv.org/abs/2609.08342v1)

- **arXiv**: `2609.08342v1`  |  **提交日期**: 2026-09-08
- **作者**: Kevin Chuanpu Fu, Yongsen Zheng, Zee Kin Yeong, Kwok-Yan Lam

World models take multimodal inputs like text, photos, and diagrams to generate dynamic scenes in accordance with the laws of physics, thus opening a compelling application: fusing multimodal legal evidence to re-create a crime scene and re-enact how an offence could have been committed. However, feeding the raw, unorganized evidence into a world model fails in forensic use: it silently drops evidence, glosses over contradictory testimony, and produces motion that violates the evidentiary record. This paper presents VeriScene, an agent that orchestrates the world model: it reconstructs crime…

---

### [CALIPER: Clean Scenes Cannot Rank Physical Inference in Pretrained Visual Representations](https://arxiv.org/abs/2609.08250v1)

- **arXiv**: `2609.08250v1`  |  **提交日期**: 2026-09-08
- **作者**: Aman Mehta, Riya Baviskar

How far a pushed object slides depends on its mass and friction, which no single image reveals. Pretrained visual encoders are increasingly used as the perception front end of world models for manipulation, and their physical competence is assessed with perturbation benchmarks and linear probes, almost always in a clean, fixed-camera scene. We show that these assessments cannot distinguish an encoder that infers physics from one that does not. CALIPER (calibrate, then predict) is a direct test: an object of unknown mass and friction is struck twice at known speeds, a third strike is shown…

---

### [ActionSplice: In-Flight Action Editing for Interactive World Models](https://arxiv.org/abs/2609.08230v1)

- **arXiv**: `2609.08230v1`  |  **提交日期**: 2026-09-08
- **作者**: Pardis Taghavi, Tingyu Guo, Jonas Lossner, Gaurav Pandey, Reza Langari

Chunk-autoregressive video world models typically condition each generated chunk on one action. An action received during sampling must therefore wait for the next chunk, condition future solver evaluations on a state produced under the previous action, or trigger rollback that repeats completed evaluations. We introduce ActionSplice, an inference framework that formulates this problem as Counterfactual State Transport (CST). A lightweight corrector transports the interrupted backbone-native representation toward the matched state induced by the revised action at the same solver step. The…

---

### [InfluenceField: A Differentiable Field with Interventionally Identifiable Causal Structure for Multimodal World Modeling](https://arxiv.org/abs/2609.07874v1)

- **arXiv**: `2609.07874v1`  |  **提交日期**: 2026-09-07
- **作者**: Zihao Yang, Zijia Wang, Zhiqiu Huang

Multimodal large language models often capture visual-linguistic correlations but struggle to predict how local visual interventions propagate and affect downstream answers. We introduce InfluenceField, an intervention-aware latent field inserted between the visual encoder and language decoder. It lifts patch features into a continuous spatial representation, propagates directed influence over multiple steps, and predicts local intervention effects through a shared transition operator. Training jointly optimizes language modeling, cross-environment invariance, counterfactual rollout…

---

### [A radiographic world model for clinical reasoning and evidence generation](https://arxiv.org/abs/2609.07719v1)

- **arXiv**: `2609.07719v1`  |  **提交日期**: 2026-09-07
- **作者**: Suyang Xi, Songtao Hu, Shansong Wang, Mojtaba Safari, Luke del Balzo, Ehsan Ul Karim et al.

Medical imaging artificial intelligence (AI) is commonly developed as separate mappings from radiographs to diagnostic outputs or from clinical descriptions to generated images, although both arise from the same underlying radiographic state. A world-model formulation instead seeks to learn an internal representation of this state that can support both clinical readout and conditional simulation of radiographic observations. Here we introduce MedDream, a radiographic world model that learns a shared continuous latent state from paired chest radiograph-text observations for diagnostic…

---

### [AgentIdeaBench: Benchmarking Scientific Ideation in the Agent Era](https://arxiv.org/abs/2609.07611v1)

- **arXiv**: `2609.07611v1`  |  **提交日期**: 2026-09-07
- **作者**: Yunxiang Mo, Tianshi Zheng, Yisen Gao, Rui Wang, Newt Nguyen Kim Hue Nam, Kelvin Kiu Wai Tam et al.

Scientific ideation is the capacity to formulate novel and testable hypotheses from scientific evidence, and autonomous AI scientists depend on it. Existing evaluations largely assess it by asking models to generate ideas from a static, curated set of reference papers. That passive setup departs from the retrieval-and-reasoning workflow of modern AI scientists, and it becomes less discriminative as models improve. We introduce AgentIdeaBench, a multidisciplinary benchmark that evaluates scientific ideation under two matched settings, static observation and active exploration. We report…

---

### [PhysReal: Learning Real-World Deformable Object Physics via Hybrid Constitutive Modeling](https://arxiv.org/abs/2609.07532v1)

- **arXiv**: `2609.07532v1`  |  **提交日期**: 2026-09-07
- **作者**: Yinan Deng, Jianqiao Song, Yisi Zhang, Yuhan Wang, Jiahui Wang, Yufeng Yue

Learning physically plausible dynamics from visual observations is essential for interactive world models and embodied agents. However, modeling real-world deformable objects remains challenging because their dynamics often arise from complex, spatially heterogeneous material responses. To address this challenge, we propose PhysReal, a video-driven framework for learning and simulating the underlying physics of real deformable objects. PhysReal integrates a spatially varying hybrid expert-neural constitutive model with a differentiable MPM simulator and 3DGS renderer. Analytical expert models…

---

### [PV-WM: A Heterogeneous Micro-Macro World Model for Articulated Pedestrian-Vehicle Co-Rollout](https://arxiv.org/abs/2609.07328v1)

- **arXiv**: `2609.07328v1`  |  **提交日期**: 2026-09-07
- **作者**: Haozhuang Chi, Jingsong Liang, Ziying Song, Lei Yang, Shihao Li, Haoruo Zhang et al.

Local pedestrian-vehicle forecasting spans heterogeneous physical scales: pedestrians combine root locomotion with articulated motion, whereas vehicles are rigid bodies described by kinematic state and oriented extent. Existing road-agent forecasters typically omit pedestrian articulation, while pose forecasters leave vehicle futures outside the learned rollout. We introduce PV-WM, a history-only world model over structured post-perception tracks. It recurrently advances pedestrian root motion, 15-joint articulation, and learned vehicle states within a synchronized heterogeneous state. The…

---

### [World Models Under Asynchronous Sensor Observations](https://arxiv.org/abs/2609.07299v1)

- **arXiv**: `2609.07299v1`  |  **提交日期**: 2026-09-07
- **作者**: Akash Anand, Abhay Anand, Yash Vishe

Learned world models typically assume that observations arrive synchronously, an abstraction inherited from simulators that return a complete state vector at each environment step. Physical sensing instead operates at heterogeneous rates, leaving most observation channels stale at any given instant. Interpolating stale channels introduces measurements that were never observed, while downsampling to the slowest sensor discards valid measurements. A natural alternative is to zero-order-hold the most recent reading and provide the known sampling schedule to the model through two features,…

---

### [Beyond Task Success: Stage-Wise Reliability of World Model Planning under Sensing Degradation](https://arxiv.org/abs/2609.07126v1)

- **arXiv**: `2609.07126v1`  |  **提交日期**: 2026-09-07
- **作者**: Geonmyeong Lee, Byoung-Tak Zhang

In world model planning, sensing inputs pass through an encoder and predictor before affecting planner decisions, so final task success alone cannot reveal where sensing disturbances attenuate or persist in the pipeline. We apply 10 visual and temporal sensing degradations to a world model planner and track their effects across representation, future prediction, planner preference, and physical outcome using paired evaluation on the same 50 tasks. The relative impact of degradations was not preserved across stages: large representation shifts could attenuate downstream, while smaller initial…

---

### [TrojanWorld: Backdooring World-Model Agents via Imagination Steering](https://arxiv.org/abs/2609.07051v1)

- **arXiv**: `2609.07051v1`  |  **提交日期**: 2026-09-07
- **作者**: Wenkai Huang, Siyuan Liang, Gaolei Li, Yiming Li, Tianhao Peng, Jianhua Li et al.

World models increasingly serve as the predictive core of model-based reinforcement learning agents, enabling them to simulate future dynamics and reason over imagined trajectories before acting. Their substantial training demands make pretrained world models attractive for distribution and reuse, exposing downstream systems to model supply chain threats. Backdoor attacks offer a targeted and stealthy means of exploiting such supply chains, yet their threat to interactive world-model agents remains largely unexplored. To fill this gap, we present TrojanWorld, a backdoor framework for…

---

### [BinauralVAE: Spatial Audio Reconstruction For World Models](https://arxiv.org/abs/2609.06837v1)

- **arXiv**: `2609.06837v1`  |  **提交日期**: 2026-09-06
- **作者**: Luis Vitor Zerkowski, Luiz Velho

Embodied artificial intelligence has historically very much relied on visual perception, leading to a proliferation of multiple vision-centric world models. However, this reliance fails to capture spatial understanding in its entirety and can even present vulnerabilities in environments with visual occlusions, low-light conditions, or blackouts-scenarios, where acoustic information becomes a critical alternative for spatial awareness and navigation. Despite its potential, research into realistic spatial audio and particularly the development of audio-centric world models remains sparse. In…

---

### [Generalist Open-World Temporal Perception](https://arxiv.org/abs/2609.06823v1)

- **arXiv**: `2609.06823v1`  |  **提交日期**: 2026-09-06
- **作者**: Cristian Sminchisescu

The next generation of artificial intelligence systems will likely be natively temporal and multimodal in both inputs and outputs: able to converse, perceive, predict, reason, and synthesize through a shared world representation. Realizing this requires a temporal perceptual substrate integrating sensory streams, language, and structured outputs within a multimodal world model. We seek a generalist open-world perceptual system that represents biological forms, natural physical structures, and artifacts, and their interactions, as a coherent, temporally persistent process. The model should…

---

### [Diagnosing and Dynamically Filtering Occupancy World Models for Active Mapping](https://arxiv.org/abs/2609.06820v1)

- **arXiv**: `2609.06820v1`  |  **提交日期**: 2026-09-06
- **作者**: Jiahui Zhang, Gongbo Liang, Yu Zhang

Active mapping requires a robot to select camera viewpoints that efficiently reconstruct an unknown 3D scene. To reason about unobserved regions, recent systems use pretrained occupancy networks as world models that complete missing geometry. The predicted structure contributes to expected coverage gain and constrains feasible robot motion. Consequently, occupancy errors can change both what the robot chooses to explore and where it is able to move. We diagnose these effects by holding the planner fixed and varying only the occupancy representation provided to it. We consider planning without…

---

### [SerenAI: State-transition system inspired by text-based world AI models](https://arxiv.org/abs/2609.06647v1)

- **arXiv**: `2609.06647v1`  |  **提交日期**: 2026-09-06
- **作者**: Elvin Babayev, Artem Sinitsa, Arash Hajisharifi, Kabir Bakhshaei

Although professional workflows leverage large language models widely, the interpretation for auditing unconstrained free-text generation is usually intractable if such generation demands legal, operational or financial workflow. We hereby demonstrate a text based system called SerenAI - inspired by world-models, it is a state transition system that outputs verifiable predictions rather than merely text: Provided with a description of the environment, state, and actions, the generated output contains 4 items: causal deltas that causally effect the given state, a next state that can logically…

---

## 📅 2026-09-07

### [TourPhysics: Bringing Physics to World Models for Exploration and Manipulation from a Single Image](https://arxiv.org/abs/2609.04911v1)

- **arXiv**: `2609.04911v1`  |  **提交日期**: 2026-09-04
- **作者**: Xin Zhang, Yabo Chen, Zixuan Duan, Haibin Huang, Chi Zhang, Feng Xu et al.

Interactive visual world models must distinguish observation from physical intervention. Camera motion reveals new surfaces, whereas intervention changes object motion, contact, and deformation. Current video world models are largely driven by appearance priors and often lose physical or spatial consistency over long horizons. We present TourPhysics, an online framework initialized from a single image and a declarative physical configuration. TourPhysics extends PhysOmni, our ACM Multimedia 2026 work, from finite physics-grounded video synthesis to persistent exploration and manipulation.…

---

### [From Language Models to World-Acting Systems: Progress and Limits of Agentic AI across Digital, Social, Virtual, and Physical Environments](https://arxiv.org/abs/2609.04894v1)

- **arXiv**: `2609.04894v1`  |  **提交日期**: 2026-09-04
- **作者**: Linsen Zhu, Mengqing Cai

Large language models become consequential agents when surrounding systems let outputs change external state. Models now call tools, operate interfaces, delegate work, retain state, inhabit generated worlds, and control robots or laboratory equipment. Such advances are often narrated as one march toward autonomy, conflating model competence, system integration, persistence, and safe authority. This critical review synthesizes primary research and official technical specifications available by 31 August 2026. We organize the evidence along delegated authority, temporal persistence, and…

---

### [Coupled Control and Wireless World Models for Resilient Remote Robotic Control](https://arxiv.org/abs/2609.04851v1)

- **arXiv**: `2609.04851v1`  |  **提交日期**: 2026-09-04
- **作者**: H. P. Madushanka, Sumudu Samarakoon, Mehdi Bennis

Remote robotic systems operating over wireless networks must maintain reliable control despite limited communication resources, changing channel conditions, and environmental disturbances.However, continuously transmitting high-dimensional sensory observations, such as camera images, increases communication overhead and energy consumption while reducing robustness under unreliable connectivity.To address these challenges, this paper proposes a resilient communication-aware remote robotic control framework based on coupled control and wireless Joint Embedding Predictive Architecture (JEPA)…

---

## 📅 2026-09-04

### [WorldReward: Reward Modeling for Camera-Conditioned World Models](https://arxiv.org/abs/2609.03952v1)

- **arXiv**: `2609.03952v1`  |  **提交日期**: 2026-09-03
- **作者**: Yibin Wang, Zehan Wang, Junshu Tang, Zhimin Li, Yujie Zhou, Jiazi Bu et al.

Camera-conditioned world models generate interactive videos in which commanded actions should induce the expected scene changes while appearance, geometry, and temporal dynamics remain coherent. Existing rewards assess these requirements separately: geometry-based rewards estimate trajectory execution but cannot judge the visual quality of the executed motion, whereas image-based rewards measure frame quality without capturing action execution or temporal dynamics. We posit that a vision-language model (VLM) offers a shared reasoning space for relating actions to their visual outcomes.…

---

### [A hybrid pipeline for dynamic ontology-based semantic mapping](https://arxiv.org/abs/2609.03891v1)

- **arXiv**: `2609.03891v1`  |  **提交日期**: 2026-09-03
- **作者**: Konstantinos Dimitropoulos, Ioannis Hatzilygeroudis

Semantic mapping plays a crucial role in the ability of a robot to interact with objects, operate and navigate a complex environment. The most common pipeline for semantic mapping consists of geometric mapping and localization (SLAM), perception, semantic fusion and semantic representation. However, more recent works also integrate a form of prior knowledge in their application, most notably knowledge graphs or semantic scene graphs, to improve contextual understanding of the environment. In this paper, we present a hybrid pipeline for semantic mapping. Our system incorporates an external…

---

### [Semantic Bayesian World Models](https://arxiv.org/abs/2609.03834v1)

- **arXiv**: `2609.03834v1`  |  **提交日期**: 2026-09-03
- **作者**: Tommaso Soru

Knowledge graphs describe reality in crisp assertions, while the systems now consuming them, foundation models and autonomous agents, reason natively in probabilities. We argue that this mismatch is why the integration of language models and knowledge graphs remains a data-feeding pipeline rather than a unified reasoning architecture. We envision Semantic Bayesian World Models (SBWMs): a Web that describes the world not as a database of facts but as a shared, evolving fabric of beliefs over knowledge graphs, where ontological axioms constrain priors, observations update beliefs by Bayesian…

---

### [Rethinking World Models for Safety-Critical Embodied Systems](https://arxiv.org/abs/2609.03774v1)

- **arXiv**: `2609.03774v1`  |  **提交日期**: 2026-09-03
- **作者**: Kailang Ma, Heye Huang, Inhi Kim, Kitae Jang

World models have progressed from compact latent dynamics to generative, controllable, and interactive simulators of embodied environments. However, high predictive likelihood and visual fidelity do not necessarily ensure that a model preserves the evidence required for safe decision-making. This perspective identifies three structural mismatches in current world modeling: likelihood versus risk, prediction versus intervention, and finite-horizon prediction versus accumulated consequences. We propose the Risk-Informed World Model (RIWM) as a decision-centric research direction for…

---

### [Symmetries and Causality: Causal Effect Identification Beyond IID Data](https://arxiv.org/abs/2609.03697v1)

- **arXiv**: `2609.03697v1`  |  **提交日期**: 2026-09-03
- **作者**: Martin Rabel, Jakob Runge

In the natural sciences, symmetries and cause-effect relationships are ubiquitous. Yet for complex machine-learning tasks, like world-modeling in reinforcement learning, they appear difficult to harness. We propose a formal description of statistical systems based on symmetries in data leaving causal mechanisms invariant. The result is an abstract, simple and general mathematical language for causal reasoning. This paper provides formal descriptions of models and queries, setting up this language, and the formal infrastructure and strategies for their mathematically rigorous identification…

---

### [SV-WAM: An Efficient Surround-View World-Action Model for End-to-End Autonomous Driving](https://arxiv.org/abs/2609.03602v1)

- **arXiv**: `2609.03602v1`  |  **提交日期**: 2026-09-03
- **作者**: Jinyang Wang, Shiwei Li, Junjian Wang, Zhiqiang Deng, Jianbin Gao, Yihang Zhao et al.

World models (WMs) have demonstrated strong potential for end-to-end autonomous driving by learning predictive representations of future scene dynamics. However, generating future videos during inference introduces substantial computational overhead, leading many recent driving WMs to adopt a single front camera as input for efficient deployment. This design restricts spatial coverage in safety-critical maneuvers such as lane changes, merges, and turns. To address this limitation, we propose SV-WAM, a surround-view world-action model (WAM) that preserves full six-camera observations while…

---

### [Drive-HWM: Hierarchical World Models for Dynamic-Latent Guided Autonomous Driving](https://arxiv.org/abs/2609.03572v1)

- **arXiv**: `2609.03572v1`  |  **提交日期**: 2026-09-03
- **作者**: Zhaoxin Fan, Tianbao Zhang, Wenjun Wu, Xiaofeng Wang, Yeying Jin, Jian Zhao et al.

World models offer a promising paradigm for autonomous driving by predicting how traffic scenes may evolve and using such predictions to support action generation. However, existing approaches either separate future prediction from action generation or jointly predict them at the same temporal scale, making it difficult to simultaneously achieve long-horizon anticipation and responsive, observation-grounded decision making. We present Drive-HWM, a hierarchical slow--fast world modeling framework that organizes future representation prediction and action generation at complementary temporal…

---

### [Toward Physically Grounded JEPA World Models for Goal-Conditioned Robotic Planning](https://arxiv.org/abs/2609.03565v1)

- **arXiv**: `2609.03565v1`  |  **提交日期**: 2026-09-03
- **作者**: Muyuan Liu, Yue Huang, Zheng Liang, Xiang Gao

Action-conditioned JEPA world models enable planning toward visually specified goals without reconstructing future pixels, yet latent prediction alone does not explicitly encourage the learned representations to retain information relevant to robotic control. We introduce an end-to-end JEPA world model that augments latent prediction with inverse dynamics (IDM) and state alignment (SA). While inverse dynamics discourages latent collapse and makes latent transitions informative of the actions that produced them, state alignment grounds consecutive representations in their associated physical…

---

### [Building Pretraining Data for World Models: An Unreal Engine-Based Pipeline for Action-Conditioned Video Generation](https://arxiv.org/abs/2609.03557v1)

- **arXiv**: `2609.03557v1`  |  **提交日期**: 2026-09-03
- **作者**: Haoyu Wang, Songchun Zhang, Haoran Li, Haoyang Huang, Zeyue Xue, Nan Duan

Action-conditioned video models require large-scale visual data paired with control signals that are temporally aligned with the resulting scene transitions. Such supervision is difficult to obtain from ordinary real-world video because the actions that caused each visual change are typically unknown. We present a large-scale synthetic data production pipeline built on Unreal Engine for generating action-conditioned, multi-view video. To accommodate the different execution requirements of real-time physics and high-quality offline rendering, the pipeline executes trajectory generation and…

---

### [Latent Energy Action Planning with World Models](https://arxiv.org/abs/2609.03294v1)

- **arXiv**: `2609.03294v1`  |  **提交日期**: 2026-09-03
- **作者**: Phu Pham, Aniket Bera

Latent world models support efficient model predictive control from high-dimensional observations, yet optimizing a single learned latent objective can favor action sequences whose decoder-predicted terminal descriptor does not match the goal descriptor. We introduce Latent Energy Action Planning (LEAP), which treats the complete action horizon as a differentiable variable and optimizes it through a frozen LeWorldModel (LeWM). LEAP couples terminal latent goal matching with a terminal-window state energy. Low energy requires the predicted terminal latent to agree with the goal latent and the…

---

### [VeriPhy: Agentic Physical Reasoning for World Model Evaluation and Refinement](https://arxiv.org/abs/2609.03153v1)

- **arXiv**: `2609.03153v1`  |  **提交日期**: 2026-09-02
- **作者**: Wenzhuo Xu, Yuchen Zhu, Chongjian Ge, Xuan Shen, Jing Shi, Jason Kuen et al.

Visual fluency in generated video does not imply physical reliability, and a scalar quality score alone is incapable of indicating the obligation a clip violates or the moment it fails. We present VeriPhy, an auditable physical-verification system in which a text-only planner compiles the prompt into typed physical obligations and a statically validated execution plan before any frame is observed. During execution, observations gate and scope only declared calls to frozen low-level experts (e.g., segmentation and tracking, counting, eleven typed physical measurements over the resulting…

---

### [GPU-Accelerated Astrodynamics World Models for Spacecraft Rendezvous and Proximity Operations](https://arxiv.org/abs/2609.03067v1)

- **arXiv**: `2609.03067v1`  |  **提交日期**: 2026-09-02
- **作者**: Duncan Eddy, Isaac R. Ward, Grace Ra Kim, Mykel J. Kochenderfer

World models are an emerging paradigm in representation learning in which an agent jointly learns state-action dynamics and observation models from offline trajectory data, enabling multi-step planning and trajectory prediction with uncertainty estimates. They have shown strong results in robotics and game environments, but, to the best of our knowledge, have not previously been applied to the space domain. This paper introduces a world model-based approach to cooperative and non-cooperative spacecraft rendezvous and proximity operations. First, we introduce an open-source, JAX-based…

---

## 📅 2026-09-03

### [SolarWM: Open Data and Scalable Training for Long-Horizon Video World Models](https://arxiv.org/abs/2609.02886v1)

- **arXiv**: `2609.02886v1`  |  **提交日期**: 2026-09-02
- **作者**: Junchao Huang, Guian Fang, Shengju Qian, Xianghao Kong, Zhuoran Zhao, Wei Huang et al.

We introduce SolarWM, a fully open foundation for building interactive video world models from data preparation through long-horizon inference. Training across heterogeneous data sources and video backbones is challenging: datasets differ in temporal scale, camera geometry, visual quality, motion, and captioning styles, while video generators use distinct representations and architectures. Naive data mixing and model-specific implementations therefore produce inconsistent supervision and make results difficult to reproduce and compare. SolarWM addresses this coupling with a reconfigurable…

---

### [Discriminative World Models for Web Agents](https://arxiv.org/abs/2609.02885v1)

- **arXiv**: `2609.02885v1`  |  **提交日期**: 2026-09-02
- **作者**: Kelvin Li, Dhruv Pendharkar, Anish Pahilajani, Chuyi Shang, Leon Oks, Leonid Karlinsky et al.

Recent web agents use world models for test-time action selection by sampling candidate actions, predicting the resulting web states, and ranking them with a ranker model or a Process Reward Model (PRM). These world models are typically trained via supervised next-state prediction to generate fixed representations like HTML or AXTree snapshots. However, this objective is misaligned with the downstream ranker, which relies on predicted states being discriminative across candidates to accurately score them. To address this, we introduce predicted-state matching, a training objective where the…

---

### [Do Better Imagined Rollouts Mean Better Robot Control? A Controlled Study of World-Model Evaluation Under Feedback](https://arxiv.org/abs/2609.02811v1)

- **arXiv**: `2609.02811v1`  |  **提交日期**: 2026-09-02
- **作者**: Dharini Raghavan, Amritpal Singh

Predictive models are increasingly used in robotics for state estimation, planning, control, and policy evaluation, yet they are often judged by open-loop prediction accuracy over a fixed horizon. In closed-loop operation, a robot repeatedly acts, receives new measurements, updates its state estimate, and recomputes control. We study this difference in a differential-drive path-tracking task with biased odometry and intermittent landmark sensing. Six state estimators are evaluated across 24 sensing conditions using trajectory replay, a 20-step measurement-free rollout, and closed-loop…

---

### [Dutch Books for Language Models](https://arxiv.org/abs/2609.02797v1)

- **arXiv**: `2609.02797v1`  |  **提交日期**: 2026-09-02
- **作者**: Isaiah Andrews, Suproteem Sarkar

People increasingly use language models to support life decisions. Many such decisions involve a probabilistic forecast: How likely is a major life event, a natural disaster, or an economic outcome? Users of language models may implicitly trust that these forecasts fall out of a coherent world model. In this paper, we evaluate the coherence of language model probabilistic forecasts through a procedure that builds on a theorem due to de Finetti. We elicit forecasts from language models across events generated from stock returns data. We then use linear programs to compute the largest…

---

### [From Proxy Learning to Driving Decisions: A Transfer-Based Framework for Evaluating Future-Aware Autonomous Driving Planners](https://arxiv.org/abs/2609.02688v1)

- **arXiv**: `2609.02688v1`  |  **提交日期**: 2026-09-02
- **作者**: Yikai Wu

Future-aware representations and world models are increasingly used in proposal-based autonomous-driving planners to improve trajectory selection. However, improvements in proxy objectives or restricted subsets are often interpreted as planning gains without verifying proposal ordering, selected trajectories, full-scale utility, and critical driving components. We propose the Proxy-to-Decision Transfer (PDT) Framework, an analysis framework that evaluates when learned future information supports a reliable driving-performance improvement claim. Its Decision-Transfer Decomposition Module…

---

### [World-Model-Augmented Visual Locomotion for Humanoids on Foothold-Constrained Terrain](https://arxiv.org/abs/2609.02542v1)

- **arXiv**: `2609.02542v1`  |  **提交日期**: 2026-09-02
- **作者**: Yuxi Liu, Lijun Han, Ziming Wang, Ao Zhang, Cong Yang, Wei Sui

Foothold-constrained terrain is characterized by sparse, discontinuous, or geometrically restricted feasible foot contacts, as encountered on stepping stones, across gaps, and on narrow stair treads. On such terrain, a single misstep often leaves little room to recover, so policies that base foot-placement decisions primarily on the immediately visible terrain are prone to failure. We ask whether a learned predictive summary of near-future observations and rewards can provide the anticipatory information required in such settings. We present World-Model-Augmented Visual Locomotion (WM-LOCO),…

---

### [Spatially Aware World Action Model via Geometric Latent Diffusion](https://arxiv.org/abs/2609.02531v1)

- **arXiv**: `2609.02531v1`  |  **提交日期**: 2026-09-02
- **作者**: Javier Alejandro Lopetegui Gonzalez, Paul Pacaud, Cordelia Schmid

World Action Models (WAMs) leverage the capabilities of large-scale pretrained video diffusion models to jointly predict future observations and actions, inheriting rich visual and physical priors from internet-scale video. This has made them a promising paradigm for robot policy learning, yet the prevailing models operate exclusively on RGB observations and do not leverage 3D information. To bridge this gap, we introduce a Spatially Aware World Action Model (SA-WAM), which repurposes a pretrained video model for joint action, RGB, and depth prediction, enabling 3D-aware world modeling and…

---

### [AGI Maze Prediction Datasets: A Compact Benchmark for Learning World Dynamics with Transformers](https://arxiv.org/abs/2609.02339v1)

- **arXiv**: `2609.02339v1`  |  **提交日期**: 2026-09-02
- **作者**: Alexey Potapov

World modeling requires a predictive model to maintain and update an internal state adequate for reasoning about the consequences of actions. We introduce the AGI Maze Prediction Datasets and Benchmark, a lightweight controlled testbed for studying this capability in Transformers and other predictive models. Derived from procedurally generated, stateful grid worlds, the benchmark comprises per-step transition prediction, fixed-horizon state prediction, and sequential textual-observation prediction. Source-maze-disjoint training and validation splits, together with greedy exact-match…

---

### [Modeling What Changes: Sparse, Residual World Models for Object-Centric Manipulation](https://arxiv.org/abs/2609.02046v1)

- **arXiv**: `2609.02046v1`  |  **提交日期**: 2026-09-02
- **作者**: Param Thakkar, Parsika Paresh Shah, Manisha Sushant Gote

Monolithic world models predict the entire next state at every step, spending capacity re-predicting the static majority of a scene and injecting error into it. We ask whether explicitly modeling change (a per-object change gate plus a residual delta head that perturbs only the objects the gate flags) is a more effective and interpretable bias for physical prediction and control. On a MuJoCo tabletop pushing benchmark scaling from 3 to 8 objects, the sparse/residual model predicts next-state poses 2.5 to 4.6 times more accurately than a dense multilayer perceptron at 8.6 to 11.1 times fewer…

---

### [Belief-Calibrated Optimization: An Explicit World Model for Agentic Optimization](https://arxiv.org/abs/2609.01861v1)

- **arXiv**: `2609.01861v1`  |  **提交日期**: 2026-09-01
- **作者**: Yuhan Chen, Zhihua Tian, Mahavir Dabas, Charith Peris, Rahul Gupta, Ming Jin et al.

The performance of an LLM agent depends on the scaffold around a frozen model. A common way to improve that scaffold is to use a coding agent as an optimizer: it reads current scores and traces and iteratively edits the source, producing a new candidate each round. Each edit is chosen according to a belief about how the environment will respond: what went wrong, and which change should help. That belief is typically implicit. It lives in the coding agent's reasoning on the current call, or remains latent in its parameters, rather than as something written down. Later calls therefore see…

---

## 📅 2026-09-02

### [H3-World: Turning Language Understanding into World Control](https://arxiv.org/abs/2609.01560v1)

- **arXiv**: `2609.01560v1`  |  **提交日期**: 2026-09-01
- **作者**: Danze Chen, Zeqing Wang, Ziyue Lin, Xingyi Yang, Yeying Jin

We present H3-World, an efficient framework that turns the 33B MiniMax-H3 video generator into an interactive world model. Our key finding is that, as large video generators become more capable, language is emerging as a natural interface for control. MiniMax-H3, for example, already supports zero-shot control of character behavior and camera motion through natural-language instructions. Building on this, H3-World turns this coarse language interface into precise, temporally grounded world control, without introducing dedicated action modules. Specifically, we represent each action as a…

---

### [NashDreamer: Model-Based Reinforcement Learning for Zero-Sum Imperfect-Information Games](https://arxiv.org/abs/2609.01549v1)

- **arXiv**: `2609.01549v1`  |  **提交日期**: 2026-09-01
- **作者**: Tomáš Holeček, Viliam Lisý

Model-based reinforcement learning (MBRL) has achieved remarkable results in single-agent domains, yet its extension to competitive imperfect information games (IIGs) remains underexplored. In multi-agent settings, opponent-induced non-stationarity complicates the learning process, and decentralized model learning faces severe identifiability barriers, which we argue make centralized model learning a mathematical necessity. Building on this analysis, we propose NashDreamer, a principled MBRL framework for two-player zero-sum IIGs. It introduces a centralized Multi-Agent Recurrent State-Space…

---

### [Solaris: Towards Interfaces That Are Generated, Not Coded](https://arxiv.org/abs/2609.00776v1)

- **arXiv**: `2609.00776v1`  |  **提交日期**: 2026-09-01
- **作者**: Yuval Alaluf, Omri Avrahami, Guy Bukchin Leshem, Michal Geyer, Kfir Goldberg, Elad Richardson et al.

Digital interfaces are traditionally implemented through intermediate representations such as code, requiring their appearance and behavior to be specified in advance. We introduce Solaris, an interface world model that instead generates an interactive UI directly, frame by frame, in response to user actions. Solaris treats mouse interactions as conditioning signals and autoregressively synthesizes the resulting visual state at interactive speeds. To enable real-time generation while maintaining visual coherence over extended interactions, we combine autoregressive frame generation with…

---

### [Streaming4D: Accelerate 4D World Models via Block-wise Video Generation and Incremental Reconstruction](https://arxiv.org/abs/2609.00610v1)

- **arXiv**: `2609.00610v1`  |  **提交日期**: 2026-09-01
- **作者**: Xiaoyan Liu, Jiaxin Liu, Kangrui Li, Sifan Zhou

Current 4D generation paradigms are often bottlenecked by a sequential decoupling design: video is generated first, followed by 3D reconstruction, leading to high interaction latency. This limits applications in interactive real-time scenarios. To this end, we propose \textbf{Streaming4D}, a tightly coupled synchronous pipeline that integrates block-wise autoregressive video generation with incremental 3D reconstruction. Unlike traditional frame-by-frame emission and delayed geometry recovery, Streaming4D generates temporal video blocks and immediately triggers reconstruction for each…

---

### [Towards a Belief-Based World Model for LLM Agents](https://arxiv.org/abs/2609.00455v1)

- **arXiv**: `2609.00455v1`  |  **提交日期**: 2026-08-31
- **作者**: Shubham Kumar, Harshit Kumar, Narendra Ahuja, Saurabh Jha

Large language models (LLMs) are being used as policies for autonomous decision-making and planning in many domains. Despite their strong reasoning capabilities, LLMs struggle with long-horizon tasks, especially under partial observability. World models are a promising way to enhance policy performance, both during training and inference. During inference, agents currently use world models to simulate the consequences of candidate actions before committing to an action, which can improve decision-making. However, we argue that simulation alone is an incomplete interface for decision-making…

---

### [ZimaBlue: Evolving Generalizable World Action Models through Scalable Video Pre-training](https://arxiv.org/abs/2609.00188v1)

- **arXiv**: `2609.00188v1`  |  **提交日期**: 2026-08-31
- **作者**: Xionghao Wu, Yijun Yang, Shiyang Zhou, Haoze Sun, Jianhui Liu, Songsong Yu et al.

Robotic manipulation faces a fundamental scaling challenge: robust generalization demands broad physical experience, yet action-labeled robot trajectories are expensive to collect and inherently limited in diversity. Egocentric videos offer a far more scalable source of embodied experience, capturing object interactions, contact dynamics, tool use, and long-horizon behaviors across diverse environments. The central challenge is how to convert this abundant but action-free experience into effective robot control. We introduce ZimaBlue, a scalable framework for learning generalizable World…

---

### [IMPACT: Attention Is the Interaction Map for Scalable Interaction-Aware World Model Training](https://arxiv.org/abs/2609.00161v1)

- **arXiv**: `2609.00161v1`  |  **提交日期**: 2026-08-31
- **作者**: Rongze Tang, Jianjie Fang, Zhaolu Wang, Ziyou Wang, Xvyuan Liu, Haisheng Su et al.

World models have made remarkable progress in action-conditioned future prediction for embodied agents, yet still struggle to model physically plausible interactions. Existing approaches address this limitation by constraining the generation process with external representations encoding motion, geometry, or semantics. Obtaining these spatiotemporally dense representations typically requires auxiliary estimators or manual annotations, limiting training scalability. We instead revisit the training objective and identify a supervision-allocation mismatch under the globally averaged mean squared…

---

### [Deploying and Evaluating a Smart-Agriculture Agentic Engine for Full-Season Soybean Farm Operations](https://arxiv.org/abs/2609.00106v1)

- **arXiv**: `2609.00106v1`  |  **提交日期**: 2026-08-31
- **作者**: Ao Qu, Panagiotis Michelakis, Linyuan Han, Yiannis Hadjiyianni, Kun Ouyang, Konstantinos Siskos et al.

This paper presents FAIRY, a full-stack smart-agriculture agent system developed for and deployed to an operating soybean research farm at Harbin Institute of Technology's smart-agriculture site. We develop FAIRY to execute and evaluate agentic agronomic operations on full-season spatiotemporal workflows that span ridge preparation, planting, irrigation, fertilization, pest and disease treatment, harvest, grain handling, drying, and storage. FAIRY integrates APIs and infrastructure across production-grade machinery, fixed soil and canopy sensors, multispectral and thermal drones, satellite…

---

### [GUI-CC: Benchmarking Contextual Consistency of GUI World Models as Agent Environments](https://arxiv.org/abs/2609.00048v1)

- **arXiv**: `2609.00048v1`  |  **提交日期**: 2026-08-30
- **作者**: Lin Fu, Zheyuan Yang, Tianhui Zhang, Jinbiao Wei, Guo Gan, Boxu Liu et al.

GUI world models are increasingly evaluated as one-step next-screen predictors, yet their intended use is often as multi-step environments for GUI agents. This mismatch leaves a key requirement under-tested: generated states must remain contextually consistent when they are repeatedly reused for future interaction. We introduce GUI-CC, a benchmark that evaluates contextual consistency of GUI world models as agent environments rather than isolated next-screen predictors. GUI-CC contains two complementary tracks: an offline reference-action track that rolls models along real mobile GUI…

---

## 📅 2026-09-01

### [CAER: Causal Action Effect Reweighting for World Model Training](https://arxiv.org/abs/2608.30897v1)

- **arXiv**: `2608.30897v1`  |  **提交日期**: 2026-08-31
- **作者**: Jianjie Fang, Xvyuan Liu, Ziyou Wang, Rongze Tang, Zhaolu Wang, Zhuohang Li et al.

World models are becoming core infrastructure for embodied intelligence, with action-conditioned video generation providing controllable predictions of how scenes evolve after agent interventions. Yet existing models are commonly trained with space-time-uniform mean squared error, allowing abundant background tokens to dominate the gradient while sparse interaction dynamics remain under-optimized; such uniform fitting rewards reconstructing appearance rather than learning how actions change the world. We introduce Causal Action Effect Reweighting (CAER), a general training paradigm that…

---

### [Can Video World Models Track Unobserved World States?](https://arxiv.org/abs/2608.30692v1)

- **arXiv**: `2608.30692v1`  |  **提交日期**: 2026-08-31
- **作者**: Joonghyuk Shin, Yicong Hong, Jaesik Park, Xun Huang

Video world models are increasingly used as simulators, yet visual fidelity alone does not show that a model maintains the hidden state of the world. We examine this gap with an action-conditioned video Shell Game, a visual analog of $S_5$ state tracking that decouples visual rendering from compositing the hidden state underneath. Bidirectional and autoregressive Transformers, Mamba, and linear attention restricted to nonnegative transition eigenvalues all fit the training horizon of 5 swaps and then fall toward chance on longer swap chains (extrapolation) while still rendering plausible…

---

### [Motus2: A Self-Evolving General World Model for Dexterous Manipulation](https://arxiv.org/abs/2608.30237v1)

- **arXiv**: `2608.30237v1`  |  **提交日期**: 2026-08-31
- **作者**: Hongzhe Bi, Zihao Zhou, Yihang Tang, Jingrui Pang, Shuhe Huang, Haitian Liu et al.

General embodied agents should perceive, predict, act, evaluate, and improve within a unified system. World models have shown great promise in building such agents, yet existing models typically append an action output head to a world simulator, without coupling them into a closed decision-and-learning loop for policy improvement. We present Motus2, a self-evolving general world model for dexterous manipulation. Motus2 advances world modeling through model scaling and data scaling. For model scaling, a single model with shared weights exposes three control interfaces: a policy (world-action…

---

### [How do World Models and Policies Compose in LLM Agents? A Joint Spectral and Behavioral Account](https://arxiv.org/abs/2608.30067v1)

- **arXiv**: `2608.30067v1`  |  **提交日期**: 2026-08-30
- **作者**: Ruize Xu, Xiao Yu, Yujin Tang, Chenming Shang, Nikhil Singh

How do LLM agents come to both understand environments they act in and master tasks set within them? Through controlled experiments combining world-model training (next-state prediction) and policy training (reward maximization), we investigate this question. We dissect the resulting models through their additive parameter updates. Geometrically, we find effective world-model updates are low-rank and share an input-feature subspace with policy updates while writing to nearly orthogonal output directions, whether trained separately or sequentially. However, we find that, in projection…

---

### [The Intervention Gap in Latent World Models](https://arxiv.org/abs/2608.29998v1)

- **arXiv**: `2608.29998v1`  |  **提交日期**: 2026-08-30
- **作者**: Donna Vakalis

Planning-time intervention fidelity is a distinct, measurable property of a learned world model: whether the model's own open-loop transitions move task variables the way matched environment interventions do. In the settings we test, it is neither revealed by reward fit nor ensured by task-anchored training. Across released TD-MPC2 checkpoint sizes, episode return falls as an operator-error diagnostic on task observables grows, while reward-prediction error stays small and nearly flat, and a self-supervised world model trained without task signal preserves the same operator substantially…

---

### [AcrossWAM1.0:A Modular Latent World-Action Stack for Compact Robot Policies](https://arxiv.org/abs/2608.29937v1)

- **arXiv**: `2608.29937v1`  |  **提交日期**: 2026-08-30
- **作者**: Yafei Zhang, Nan Wu

Latent world-action models avoid rendering future pixels by predicting an action-relevant visual subgoal in feature space. LaWAM established this formulation, but its original presentation left the world model, multimodal backbone, and deployment checkpoint tightly coupled. We introduce AcrossWAM1.0, a modularization and scaling study of this latent world-action stack. Rather than presenting latent subgoals as a new algorithm, we make the module boundary explicit: a policy adapter produces latent-action and action-generation contexts; a retained latent world decoder grounds the predicted…

---

### [Matrix-Game 3.5: Enhancing Real-Time Streaming Interactive World Models with Patch Memory](https://arxiv.org/abs/2608.29910v1)

- **arXiv**: `2608.29910v1`  |  **提交日期**: 2026-08-30
- **作者**: Runjia Qian, Zile Wang, Jihai Zhang, Kai Zou, Wei Yu, Jiaxing Li et al.

Interactive world models extend video generation from offline clip synthesis toward persistent simulation of interactive virtual worlds, enabling applications in games, robotics, embodied agents, and XR. Achieving stable long-horizon interactive generation, however, remains challenging, as the model must simultaneously preserve scene geometry, dynamic consistency, and camera control while supporting real-time autoregressive generation. Building upon Matrix-Game 3.0, we present Matrix-Game 3.5, as shown in Figure 1, which advances real-time interactive world generation toward geometry-aware…

---

### [Off-Manifold Refinement: Guiding Video Generators with a Frozen World Model](https://arxiv.org/abs/2608.29904v1)

- **arXiv**: `2608.29904v1`  |  **提交日期**: 2026-08-30
- **作者**: Hai Nguyen-Truong, Tuan-Anh Vu, Dang Huynh

Modern video generators routinely fail at physical dynamics: objects float, trajectories violate gravity, contacts vanish. Standard denoising and flow-matching objectives fit visual data distributions but do not explicitly penalize such physical violations. Existing remedies can improve physical consistency, but typically add substantial inference or training cost. Candidate-selection methods generate and score multiple videos, while gradient-based world-model guidance repeatedly decodes and re-encodes intermediate estimates. Generator-internal refinement adds perturbation and re-denoising…

---

### [Self-Aware Active Learning Enables Continual Improvement in Autonomous Driving](https://arxiv.org/abs/2608.29772v1)

- **arXiv**: `2608.29772v1`  |  **提交日期**: 2026-08-30
- **作者**: Dong Hu, Chao Huang, Carman K. M. Lee, Dimitrios Kanoulas

Learning-based autonomous driving (AD) systems can perform reliably in familiar conditions, yet rare distribution shifts and long-tail events remain a major source of abrupt failure. A central limitation is that most agents learn primarily from passive experience and lack mechanisms to estimate when their competence is insufficient, seek timely assistance, and convert safety-critical encounters into targeted improvement. Here we present self-aware guided exploration (SAGE), an active learning framework for post-training adaptation in AD. SAGE learns a predictive world model that generates two…

---

### [Does Latent Planning Survive Point Clouds? Action-Conditioned JEPA World Models for Geometric Observations](https://arxiv.org/abs/2608.29434v1)

- **arXiv**: `2608.29434v1`  |  **提交日期**: 2026-08-29
- **作者**: Fabio F. Oberweger, Michael Schwingshackl

JEPA world models make latent-space planning a practical route to control, but they are built almost exclusively on images. Whether latent prediction survives geometric observations is unclear: point clouds are sparse, unordered, and self-occluded, and with 0.3-15% of scene points moving, the slow-feature optimum of latent prediction compounds with the geometric shortcut of 3D self-supervision. We lift three canonical JEPA designs to point clouds, frozen-encoder, distribution-prior, and action-sensitive, and re-sense the stable-worldmodel benchmark so that only the observation differs from…

---

### [Flow-JEPA: Flow Matching for Robust Latent Dynamics in JEPA World Models](https://arxiv.org/abs/2608.29029v1)

- **arXiv**: `2608.29029v1`  |  **提交日期**: 2026-08-29
- **作者**: Yanchen Huo, Ziying Song, Yadan Luo

Joint-Embedding Predictive Architectures (JEPAs) have shown strong potential for learning compact predictive representations, and LeWorldModel (LeWM) extends this paradigm to reconstruction-free latent world modeling from pixels. However, its deterministic autoregressive predictor generates future states through repeated one-step transitions, which can accumulate errors and remain sensitive to task-irrelevant visual perturbations. In this work, we propose Flow-JEPA (F-JEPA), a conditional flow matching dynamics model that jointly generates a sequence of future latent states conditioned on the…

---

### [Hydra: A Navigation World Action Model with Discrete Latent Planning and Continuous Flow-Matching Execution](https://arxiv.org/abs/2608.28995v1)

- **arXiv**: `2608.28995v1`  |  **提交日期**: 2026-08-29
- **作者**: Mohammad Nazeri, Alexandyr Card, Samira Huber, Anuj Pokhrel, Yujun Wang, Ruben Hammele et al.

World models let robots imagine possible futures, but exploiting this capability for real-time control is bottlenecked by a representation misalignment: the generative model and the planner operate on decoupled manifolds, so the planner has no shared structure to search over and must instead decode every candidate back into high-dimensional pixel space to evaluate it. This decoding step is a major obstacle to real-time control on physical hardware. In this paper, we present Hydra, a discrete World Action Model that closes this gap by moving the planner, both the sampler and the evaluator,…

---

## 📅 2026-08-31

### [An Enclosed Mode Is a Gauge Choice: Topology Relative to Reach in Certified Code World Models](https://arxiv.org/abs/2608.28541v1)

- **arXiv**: `2608.28541v1`  |  **提交日期**: 2026-08-28
- **作者**: Javier Aguilar Martín

A code world model accepted by a sampling gate can be exactly right on everything the gate can see and arbitrarily wrong beyond it. We characterize what a certified model can know, and what its errors can cost, when the omission is an annular freeze mode enclosing an unreachable interior. The gate quotient makes the question precise: acceptance-with-certainty determines the model exactly on the reachable query set; beyond reach is gauge. On a minimal ring instrument we prove the extreme case (a wrong-topology filled-disc artifact unfalsifiable by any sampling gate and bitwise harmless at…

---

### [AcrossVAM1.0: Particle World Modeling for Text-Assisted Robot Video Prediction](https://arxiv.org/abs/2608.28491v1)

- **arXiv**: `2608.28491v1`  |  **提交日期**: 2026-08-28
- **作者**: Yafei Zhang, Nan Wu

Predicting robot videos requires both precise motion reasoning and preservation of high-frequency appearance, yet monolithic pixel models entangle these objectives and often conceal their progress behind a strong last-frame baseline. We present AcrossVAM1.0, a lightweight, text-assisted video action model that factorizes future prediction into object-centric motion and dense appearance. A frozen SAM3-DLP codec decomposes four context frames into semantic particles for the robot, arm, and gripper, together with a background latent. A 0.28M-parameter spatio-temporal Transformer aligns particle…

---

### [WALDO: One-Shot Exemplar-Conditioned Object Detection in Cluttered Scenes](https://arxiv.org/abs/2608.28216v1)

- **arXiv**: `2608.28216v1`  |  **提交日期**: 2026-08-28
- **作者**: Kishor Datta Gupta, Ahmed Rafi Hasan, Md. Mahfuzur Rahman, Md. Sadman Haque, Mohd Ariful Haque

Locating a specific object instance in a cluttered scene using a single reference image and a short description, and reporting when that instance is absent, large vision-language models usually address this task. We ask whether the same capability is available far more cheaply, from representations already learned by a world-model pretraining objective. We present WALDO, a one-shot exemplar- and language-conditioned detection head with 3.4M trainable parameters that reads frozen V-JEPA 2.1 features to jointly predict object localization and target presence, with no gradient on the backbone.…

---

### [Learning to Allocate Incentives for Incentivized Advertising via Offline Model-Based Reinforcement Learning](https://arxiv.org/abs/2608.28065v1)

- **arXiv**: `2608.28065v1`  |  **提交日期**: 2026-08-28
- **作者**: Zilin Zhao, Han Yang, Tianpei Yang, Fangsheng Huang, Yanfei Cui, Kan Peng et al.

Complete your ad view and grab a 5-cent bonus! In incentivized advertising, a platform promises users a bonus before observing downstream ad revenue, encouraging them to click and complete ads. It must balance the incentive promised in advance against the revenue realized afterward: insufficient incentives forfeit monetization opportunities, whereas excessive incentives reduce net profit. Because current incentives may also shape user expectations and future engagement, incentive allocation is a sequential decision problem with delayed revenue, cost sensitivity, and carryover effects.…

---

## 📅 2026-08-28

### [CLAP: Cross-Embodiment Video World Models are Zero-Shot Physical Simulators](https://arxiv.org/abs/2608.27406v1)

- **arXiv**: `2608.27406v1`  |  **提交日期**: 2026-08-27
- **作者**: Kechen Liu, Ola Shorinwa

State-of-the-art action-conditioned video models are typically restricted to a single robot embodiment, preventing them from leveraging the vast corpus of heterogeneous video data that contains rich signals for learning generalizable physics. To bridge this gap, we introduce CLAP, a framework for cross-embodiment action-conditioned video generation capable of being trained on diverse, internet-scale videos across human and robotic agents. CLAP is grounded in the insight that universal physical laws govern spatiotemporal dynamics regardless of the actor. However, cross-embodiment learning is…

---

### [Successive Capacity Growth: Task-Complexity-Driven Width and Depth Expansion for Vision Transformer Encoders in JEPA World Models](https://arxiv.org/abs/2608.27367v1)

- **arXiv**: `2608.27367v1`  |  **提交日期**: 2026-08-27
- **作者**: Frederik Berenz

Joint-Embedding Predictive Architectures (JEPAs) for world modeling typically employ fixed-size Vision Transformer encoders that are over-provisioned for simple tasks and under-provisioned for complex ones, with significant redundancy across attention heads. We propose Successive Capacity Growth (SCG), a method that starts from a minimal encoder (1 head, 2 layers, 283K parameters) and grows incrementally in width (adding attention heads for low-level semantic capacity) or depth (adding transformer blocks for higher-order semantic abstraction), driven by a task-agnostic test-and-verify…

---

### [PAWBench: How Far Are We from Probabilistically Aligned World Modeling?](https://arxiv.org/abs/2608.27345v1)

- **arXiv**: `2608.27345v1`  |  **提交日期**: 2026-08-27
- **作者**: Yuandong Pu, Le Zhuo, Sayak Paul, Gabriel Jorge Menezes, Avram Đorđević, Shiyang Li et al.

Recent video generation models are increasingly framed as world models. Many physical processes can unfold in more than one valid way. Therefore, a world model should reproduce not only a plausible trajectory, but also the distribution of possible behaviors under the same initial observation and action. We call this distribution-level requirement probabilistic alignment. However, existing evaluations largely assess individual-video plausibility and do not test whether repeated generations recover the correct distribution. This raises a central question: how far are current video generators…

---

### [R2M-Bench: Evaluating Revisit Memory via Relative Consistency in Interactive Video World Models](https://arxiv.org/abs/2608.27328v1)

- **arXiv**: `2608.27328v1`  |  **提交日期**: 2026-08-27
- **作者**: Qiwen Gu, Bingjie Gao, Rui Chen, Geng Li, Jifan Li, Qishuai Wen et al.

High similarity between first-visit and return frames does not necessarily show that a video world model remembered the scene; the intervening rollout may simply have changed very little. This ambiguity makes absolute revisit scores sensitive to rendering stability, repetitive content, and failed motion. We introduce \emph{R2M-Bench} (\textbf{R}elative \textbf{R}evisit \textbf{M}emory Benchmark), a benchmark of observable revisit-selective consistency. For every detected return, R2M-Bench compares the revisit pair with two controls from the same rollout: a gap-matched non-revisit pair that…

---

### [SpatialCrafter: Single Image World Modeling with Generative 3D Proxies](https://arxiv.org/abs/2608.27073v1)

- **arXiv**: `2608.27073v1`  |  **提交日期**: 2026-08-27
- **作者**: Chuan Fang, Lingteng Qiu, Yixun Liang, Rui Chen, Kunming Luo, Zhaohua Zheng et al.

Explorable image-to-scene generation is essential for applications in gaming, robotics, and virtual reality. Existing methods based on video diffusion model (VDM) commonly rely on incomplete conditioning signals such as sparse point clouds or 2D panoramas, leading to stochastic hallucinations, long-term drifts and suboptimal 3D consistency. We present SpatialCrafter, a novel two-stage framework that addresses these issues by introducing a global 3D proxy for high-fidelity image-to-scene generation. Specifically, we decompose the generation process into global proxy generation and appearance…

---

### [WALL-SS: Scaling Long-horizon World Models via Next-Scale Autoregression](https://arxiv.org/abs/2608.26239v1)

- **arXiv**: `2608.26239v1`  |  **提交日期**: 2026-08-26
- **作者**: Maeve Zhang, Rain Sun, Xiang Wang, Cyril Zhang, Shalfun Li, Meng Cao et al.

Generative world models provide robots with predictive models of how the world evolves under interaction, with growing potential for simulation, planning, policy evaluation, and robot learning. Beyond clip-level future prediction, a unified generative formulation should relate actions to consequences, support flexible horizons and continuous interaction, and enable reward-driven optimization. We introduce WALL-SS, a world model that generates visual futures through Scale-wise autoregressive Scaling, enabling action-controllable and long-horizon robotic simulation. WALL-SS represents embodied…

---

### [Surgical Video Generation From Diffusion to World Models: A Survey](https://arxiv.org/abs/2608.26214v1)

- **arXiv**: `2608.26214v1`  |  **提交日期**: 2026-08-26
- **作者**: Fuxiang Huang, Chenxu Zhang, Liang Han, Lei Zhang

Surgical video data provides the primary training resource for models of intraoperative perception, surgical workflow understanding, and robotic decision-making. However, clinical data acquisition remains constrained by privacy, cost, and class imbalance. Surgical video generation has emerged as a transformative approach to addressing data scarcity and as a foundation for surgical simulation, training, and robotic policy learning. The field has developed rapidly without a clear conceptual framework. This survey organizes the 2024-2026 literature into three categories: unconditional…

---

### [4DStreamCtrl: Interactive Video Generation with Online 4D Control](https://arxiv.org/abs/2608.25479v2)

- **arXiv**: `2608.25479v2`  |  **提交日期**: 2026-08-26
- **作者**: Shiqian Li, Chenguo Lin, Zhiguang Liu, Yu Tang, Jiarong Ou, Rui Chen et al.

Generative video models now synthesize footage nearly indistinguishable from reality. Their promise as interactive tools hinges on fine-grained control of how objects and the camera move over time, yet each existing approach captures only part of this: camera-parameter methods steer the viewpoint but cannot move objects, 2D-trajectory methods act in the image plane and ignore depth and occlusion, and recent 3D methods add geometry but run only offline at a fixed length. In particular, none combines 3D-consistent control of both camera and objects with real-time, streaming generation. Here we…

---

### [GameWAM: A World Action Model for Video Games](https://arxiv.org/abs/2608.26200v1)

- **arXiv**: `2608.26200v1`  |  **提交日期**: 2026-08-25
- **作者**: Yuncheng Guo, Zhanqiu Zhang, Yiwen Guo, Weijia Li

Modern video games combine first-person perception, rapid visual changes, persistent world state, and heterogeneous native controls. Existing game agents map visual and task context directly to actions but lack explicit world dynamics modeling, whereas interactive game world models predict visual futures from supplied actions but do not serve as task policies. World-Action Models (WAMs) unify these objectives, but remain largely unexplored under the dynamics and open-ended interaction of video games. We introduce GameWAM, to our knowledge the first WAM for native closed-loop gameplay and GUI…

---

### [NVIDIA Cosmos-H-Dreams: Real-Time Generative Physics Simulation for Surgical Robotics](https://arxiv.org/abs/2608.24199v2)

- **arXiv**: `2608.24199v2`  |  **提交日期**: 2026-08-25
- **作者**: Javier Gamazo Tejero, Lukas Zbinden, Keyur Sheth, Raghavendra K M, Nadim Daher, Diego Granero Maraña et al.

Generative simulation for surgical robotics still lacks real-time interaction. Physical-robot experiments, often involving animal or cadaver labs, are time-consuming, costly, and difficult to reproduce, while classical simulators struggle to capture photorealistic appearance and deformable-tissue dynamics. We address this gap with Cosmos-H-Dreams, an integrated real-time surgical world-model system combining an action-conditioned generative model, a teacher-to-student distillation recipe, and a deployment stack built on the NVIDIA FlashDreams streaming-inference library. Starting from…

---

## 📅 2026-08-27

### [4DGS-WAM: Bridging Past and Future with an Object-Centric World Action Model based on 4D Gaussian Splatting](https://arxiv.org/abs/2608.25956v1)

- **arXiv**: `2608.25956v1`  |  **提交日期**: 2026-08-26
- **作者**: Yueen Ma, Zenglin Xu, Irwin King

Current world action models (WAMs) typically operate on 2D visual data. These models can achieve exceptional visual quality, but they lack explicit spatial structure for individual objects and repeatedly process redundant background content. Although point clouds can represent the world in 3D space, they can be difficult to align and accumulate across viewpoints. In this paper, we leverage an explicit 4D Gaussian Splatting (4DGS) representation that separately models dynamic objects and the static background of a scene. For dynamic objects, we use a policy model to predict future actor…

---

### [Code World Model: Coding Agent as World Brain](https://arxiv.org/abs/2608.25927v1)

- **arXiv**: `2608.25927v1`  |  **提交日期**: 2026-08-26
- **作者**: Yiwen Chen, Guosheng Lin, Chi Zhang

World models aim to simulate how complex environments evolve under actions and events, yet existing video-based world models primarily learn dynamics from visual observations, which reveal outcomes rather than the underlying knowledge, rules, and mechanisms governing world evolution. This makes it difficult to maintain persistent consequences and support coherent, open-ended evolution. We introduce Code World Model, a framework that separates world evolution from visual realization by combining the reasoning and coding capabilities of language models with the generative priors of video…

---

### [ConfAL-WM: Confidence-Guided Active Learning for Action-Conditioned World Models](https://arxiv.org/abs/2608.25572v1)

- **arXiv**: `2608.25572v1`  |  **提交日期**: 2026-08-26
- **作者**: Xiang Liu, Sen Cui, Changshui Zhang

Action-conditioned world models have become an important foundation for embodied prediction, planning, and synthetic data generation, but their errors under new task and scene distributions are often concentrated in localized spatiotemporal regions such as robot arms, manipulated objects, contact areas, and occluded objects. This paper presents ConfAL-WM, a confidence-guided active learning framework for post-training embodied world models. Built upon EVAC, we attach a lightweight confidence probe to UNet decoder features and predict dense confidence maps in the latent space. These maps are…

---

### [Agentic Game Development as a Verifiable Trajectory Data Engine for Scaling World Models](https://arxiv.org/abs/2608.25518v1)

- **arXiv**: `2608.25518v1`  |  **提交日期**: 2026-08-26
- **作者**: Pengfei Zhou, Hexin Wang, Zhengfeiyang Zhang, Yixing Ma, Zhenglin Wan, Kaipeng Zhang et al.

A common strategy for scaling world models is to train on more crawled video with more compute. We argue that this strategy is inefficient: scaling world models also requires a recursive data engine that offers grounded reward signals. The success of code agents illustrates why this matters. As code is executable, compilers and runtimes can provide high-quality rewards for Reinforcement Learning (RL) post-training of LLMs. By contrast, spatial generation still relies largely on fuzzy proxies such as CLIP scores. These signals are fuzzy and biased, making them hard to support RL post-training.…

---

### [4DStreamCtrl: Interactive Video Generation with Online 4D Control](https://arxiv.org/abs/2608.25479v1)

- **arXiv**: `2608.25479v1`  |  **提交日期**: 2026-08-26
- **作者**: Shiqian Li, Chenguo Lin, Zhiguang Liu, Yu Tang, Jiarong Ou, Rui Chen et al.

Generative video models now synthesize footage nearly indistinguishable from reality. Their promise as interactive tools hinges on fine-grained control of how objects and the camera move over time, yet each existing approach captures only part of this: camera-parameter methods steer the viewpoint but cannot move objects, 2D-trajectory methods act in the image plane and ignore depth and occlusion, and recent 3D methods add geometry but run only offline at a fixed length. In particular, none combines 3D-consistent control of both camera and objects with real-time, streaming generation. Here we…

---

### [Rollout-Decoded Reconstruction for Long-Horizon Prediction in Latent World Models](https://arxiv.org/abs/2608.25017v1)

- **arXiv**: `2608.25017v1`  |  **提交日期**: 2026-08-25
- **作者**: Rishi Shah, Rishav Shrestha

A latent world model trains its decoder on latents anchored to observations, then deploys it on the model's own free-running rollout, hundreds of steps past the last observation. Rollout-Decoded Reconstruction (RDR) closes this gap with a single loss term that free-runs the model during training exactly as evaluation will, decodes every rollout latent, and penalizes reconstruction error against ground truth. The term adds no parameters, costs training-time compute only, and reduces to the standard objective at weight zero, so every comparison in this paper is a one-flag A/B. On the chaotic…

---

### [JEPA-x: Cross-Predictive Physics Grounding for Forecastable Latent Dynamics](https://arxiv.org/abs/2608.24044v2)

- **arXiv**: `2608.24044v2`  |  **提交日期**: 2026-08-25
- **作者**: Kehan Wen, Ziming Li, Siyuan Luo, Fan Shi

Latent world models plan by predicting how candidate actions advance learned latent dynamics. In self-predictive models, however, the encoder and predictor are optimized jointly and can co-adapt to latent transitions that are easy to predict but weakly constrained by the physical evolution of the scene. We introduce the cross-predictive JEPA (JEPA-x), which grounds visual latent dynamics in privileged physical trajectories. JEPA-x treats visual observations and physical states as corresponding views of the same action-conditioned trajectory, advances both through a shared predictor, and…

---

### [Platonic Representation Hypothesis on World Models](https://arxiv.org/abs/2608.23720v2)

- **arXiv**: `2608.23720v2`  |  **提交日期**: 2026-08-24
- **作者**: Wenhow Li, Chengwei MA, Hui Xiong, Ying-Cong Chen, Lei Zhang

World models have demonstrated significant potential for perceiving and simulating complex environments. Despite their strong performance, the fundamental nature of their learned representations remains poorly understood. In this paper, we investigate the Platonic Representation Hypothesis within this domain by proposing the Predictive Consistency Assumption: we posit that the optimization of a shared state transition objective acts as a selective pressure that encourages heterogeneous models to converge toward a shared latent structure. Through systematic experiments with the DINO World…

---

## 📅 2026-08-26

### [Do Robotic World Models Really Follow Actions? Diagnosing and Aligning Action-Conditioned Generation for Policy Learning](https://arxiv.org/abs/2608.24885v1)

- **arXiv**: `2608.24885v1`  |  **提交日期**: 2026-08-25
- **作者**: Sixiang Chen, Jiaming Liu, Jixian Wu, Yichen Guo, Tinghao Wang, Siyuan Qian et al.

Action-conditioned world models are increasingly used as learned simulators for policy evaluation and improvement, yet their effectiveness rests on an unverified assumption: generated futures faithfully reflect arbitrary valid actions. Existing benchmarks are typically confined to expert demonstrations, leaving off-expert action following inadequately evaluated. To address this gap, we introduce WorldEcho, which probes action following over a broader action distribution using visual integrity and SE(3) trajectory alignment. Our diagnosis shows that current world models reasonably execute…

---

### [LeFlow: Generative Latent Flow Planning for World Models](https://arxiv.org/abs/2608.24855v1)

- **arXiv**: `2608.24855v1`  |  **提交日期**: 2026-08-25
- **作者**: Hsiang-Wei Huang, Jianxu Shangguan, Junbin Lu, Jenq-Neng Hwang

Latent world models are inherently strong encoders that transform image pixel to latent embedding, yet existing world models still rely on online trajectory optimization for action planning: for every state-goal pair, an iterative optimizer is run from scratch to search for optimal action sequences, treating the world model as a black-box simulator. This approach pays the full iterative optimization cost anew at every replanning step and reuses no planning experience across queries. In this work, we ask whether planning itself can be amortized once a latent world model has been learned. We…

---

### [Game2World Engine: Unlocking In-the-Wild Gameplay Videos for World Model Training](https://arxiv.org/abs/2608.24680v1)

- **arXiv**: `2608.24680v1`  |  **提交日期**: 2026-08-25
- **作者**: Wenxuan Shen, Dongna Jin, Dongping Chen

Video games provide a scalable source of training data for video world models, offering diverse environments, complex interactions, and abundant in-the-wild gameplay videos. However, raw gameplay footage entangles the game world with screen-space interfaces, introducing game-specific biases and irrelevant dynamics that hinder world-model training. To address this problem, we introduce GameUI-Taxonomy and G2WEngine, a full-stack framework that formalizes gameplay UI grounding and removal. G2WEngine automatically extracts reusable UI assets from real gameplay videos and synthesizes temporally…

---

### [Neurosymbolic Alignment for Physiologically-Safe Clinical Language Models](https://arxiv.org/abs/2608.24534v1)

- **arXiv**: `2608.24534v1`  |  **提交日期**: 2026-08-25
- **作者**: Abdulhady Abas Abdullah, Erik Cambria, Milena Zivkovic

Clinical LLMs can generate recommendations that are factually plausible yet physiologically unsafe. We investigate whether safety alignment can be improved by grounding preference optimization in structured physiological knowledge rather than text-only supervision. Methods: We propose Neurosymbolic Alignment, a training-time framework that couples a 7B clinical LLM with an HGNN-based Physiological World Model over an 847K-node biomedical knowledge graph. Candidate responses are scored using homeostatic constraints, multi-hop path plausibility, and drug-interaction penalties, and the resulting…

---

### [NVIDIA Cosmos-H-Dreams: Real-Time Generative Physics Simulation for Surgical Robotics](https://arxiv.org/abs/2608.24199v1)

- **arXiv**: `2608.24199v1`  |  **提交日期**: 2026-08-25
- **作者**: Javier Gamazo Tejero, Lukas Zbinden, Keyur Sheth, Raghavendra K M, Nadim Daher, Diego Granero Maraña et al.

Generative simulation for surgical robotics still lacks real-time interaction. Physical-robot experiments, often involving animal or cadaver labs, are time-consuming, costly, and difficult to reproduce, while classical simulators struggle to capture photorealistic appearance and deformable-tissue dynamics. We address this gap with Cosmos-H-Dreams, an integrated real-time surgical world-model system combining an action-conditioned generative model, a teacher-to-student distillation recipe, and a deployment stack built on the NVIDIA FlashDreams streaming-inference library. Starting from…

---

### [XP-JEPA: Cross-Predictive Physics Grounding for Forecastable Latent Dynamics](https://arxiv.org/abs/2608.24044v1)

- **arXiv**: `2608.24044v1`  |  **提交日期**: 2026-08-25
- **作者**: Kehan Wen, Ziming Li, Siyuan Luo, Fan Shi

Latent world models plan by predicting how candidate actions transform learned representations. In self-predictive models, however, the encoder and predictor are optimized jointly and can co-adapt to latent transitions that are easy to predict but only weakly constrained by the physical evolution of the scene. We introduce the cross-predictive JEPA (XP-JEPA), which grounds visual latent dynamics in privileged physical trajectories. XP-JEPA separately encodes visual observations and physical states, advances both through a shared action-conditioned predictor, and matches each prediction to…

---

### [DreamLedger: Execution-Settled Credit Files for World-Model Imagination in Robot Decision Loops](https://arxiv.org/abs/2608.23863v1)

- **arXiv**: `2608.23863v1`  |  **提交日期**: 2026-08-24
- **作者**: Xianyao Li, Ruitong Tian, Rui Min, Fang Xu, Jing Du

Robots are beginning to act on world-model predictions, yet reliability is still expressed through instantaneous, model-internal signals. DreamLedger instead treats reliability as a persistent deployment object: an execution-settled credit file recording how often consumed predictions are borne out, indexed by operating condition, region, and prediction horizon, and consulted before each use. Each consumed prediction is registered as a claim; attributable outcomes are settled against arriving reality at zero labeling cost, an attribution stage excludes measurement-contaminated outcomes, and a…

---

### [Primate vision reveals a missing principle for robust dynamic AI](https://arxiv.org/abs/2608.23790v1)

- **arXiv**: `2608.23790v1`  |  **提交日期**: 2026-08-24
- **作者**: Matteo Dunnhofer, Christian Micheloni, Kohitij Kar

How does an intelligent visual system combine what objects look like with how they move while remaining robust as appearance changes? We addressed this question by comparing human perception and neural activity in macaque inferior temporal cortex with representations from image- and video-based neural networks spanning recognition, segmentation, optic-flow processing and predictive world modeling. Temporal integration improved object representations, but most video recognition models generalized poorly when appearance was disrupted while motion structure was preserved. Humans and macaque IT…

---

### [Platonic Representation Hypothesis on World Models](https://arxiv.org/abs/2608.23720v1)

- **arXiv**: `2608.23720v1`  |  **提交日期**: 2026-08-24
- **作者**: Wenhow Li, Chengwei MA, Hui Xiong, Ying-Cong Chen, Lei Zhang

World models have demonstrated significant potential for perceiving and simulating complex environments. Despite their strong performance, the fundamental nature of their learned representations remains poorly understood. In this paper, we investigate the Platonic Representation Hypothesis within this domain by proposing the Predictive Consistency Assumption: we posit that the optimization of a shared state transition objective acts as a selective pressure that encourages heterogeneous models to converge toward a shared latent structure. Through systematic experiments with the DINO World…

---

### [Do LLMs Understand Limit Order Book Dynamics?](https://arxiv.org/abs/2608.23706v1)

- **arXiv**: `2608.23706v1`  |  **提交日期**: 2026-08-24
- **作者**: Junxiao Chen, Paul Glasserman

A large language model (LLM) trained on synthetic limit order book (LOB) data achieves near perfect scores in generating valid sequences of LOB events. However, the LLM's implicit world model fails to learn the state of the LOB. This deficiency leads to biased estimates and spurious predictability in using the LLM to forecast future LOB events. Our analysis uses novel tests of an LLM's world model, extending prior work from deterministic settings to the stochastic dynamics needed for the LOB.

---

### [GeoWAM: Visual Geometry World Action Models for Autonomous Driving](https://arxiv.org/abs/2608.23486v2)

- **arXiv**: `2608.23486v2`  |  **提交日期**: 2026-08-24
- **作者**: Yiren Lu, Xin Ye, Jiaming Liu, Philip Jacobson, Jin Yao, Yi-chung Chen et al.

World action models (WAMs) have recently gained increasing attention as a framework for jointly modeling scene evolution and ego actions in autonomous driving. Most existing WAMs learn scene dynamics in pixel space by combining a video-generation backbone for future-observation prediction with an action head for ego-trajectory prediction. Pixels, however, provide only an indirect representation of these dynamics: they entangle geometry and motion with appearance, texture, and illumination, forcing the model to infer three-dimensional transformations from two-dimensional observations. We argue…

---

### [Long-Horizon Audio-Visual Generation for Persistent Stories and Interactive Worlds](https://arxiv.org/abs/2608.23383v2)

- **arXiv**: `2608.23383v2`  |  **提交日期**: 2026-08-24
- **作者**: Nan Duan, Haoyang Huang, Weiyang Jin, Haoran Li, Yaowei Li, Yuming Li et al.

Video generation is progressing beyond isolated clips toward long-form narratives and interactive worlds, requiring models to preserve identities, follow user controls, and remain stable over extended rollouts. We present JoyAI-Echo-1.5, a unified audio-visual generation system with two purpose-built variants. The long-video variant introduces composable cross-shot memory that aggregates visual evidence across multiple prior shots and speaker cues derived from speech-filtered full-shot audio, enabling persistent character appearance and voice identity across flexible combinations of text,…

---

## 📅 2026-08-25

### [ReWorld: An Interactive World Model with Long-Horizon Memory](https://arxiv.org/abs/2608.23565v1)

- **arXiv**: `2608.23565v1`  |  **提交日期**: 2026-08-24
- **作者**: Zhifei Chen, Luozhou Wang, Guibao Shen, Dongyu Yan, Shuai Yang, Tianshuo Xu et al.

An interactive world model must follow the user's actions, remember the places it has shown, and stream in real time. The tension is structural: control wants a short horizon, memory wants an unbounded one. ReWorld separates the two during training and bounds them at inference. Mixed per-head attention windows confine most heads to the recent past while a small set of global heads attends over the entire history, and random head routing keeps either capability from binding to particular heads; random chunk dropping makes sparse histories in-distribution. At inference the whole past lives…

---

### [Correcting a learned physical invariant improves world-model rollouts](https://arxiv.org/abs/2608.23526v1)

- **arXiv**: `2608.23526v1`  |  **提交日期**: 2026-08-24
- **作者**: Richard Bao

World models can predict video without learning dynamics that they reliably preserve. We test whether a frozen DreamerV3 trained only on pendulum video learns a scalar that its own latent transition treats as approximately conserved. A label-free search recovers the same energy-like invariant across independently trained conservative models, while the same procedure finds no comparable invariant in matched damped models. During autonomous rollouts, this quantity drifts. Projecting the latent state back toward its initial level set reduces rollout error in all three conservative models,…

---

### [GeoWAM: Visual Geometry World Action Models for Autonomous Driving](https://arxiv.org/abs/2608.23486v1)

- **arXiv**: `2608.23486v1`  |  **提交日期**: 2026-08-24
- **作者**: Yiren Lu, Xin Ye, Jiaming Liu, Jin Yao, Yi-chung Chen, Liam Merino et al.

World action models (WAMs) have recently gained increasing attention as a framework for jointly modeling scene evolution and ego actions in autonomous driving. Most existing WAMs learn scene dynamics in pixel space by combining a video-generation backbone for future-observation prediction with an action head for ego-trajectory prediction. Pixels, however, provide only an indirect representation of these dynamics: they entangle geometry and motion with appearance, texture, and illumination, forcing the model to infer three-dimensional transformations from two-dimensional observations. We argue…

---

### [Reward-Free Continual Adaptation for Resilient Space Robots](https://arxiv.org/abs/2608.23452v1)

- **arXiv**: `2608.23452v1`  |  **提交日期**: 2026-08-24
- **作者**: Andrej Orsula, Miguel Olivares-Mendez, Carol Martinez

Space robots operate in extreme environments where hardware degradation can critically compromise traditional control strategies. While continual reinforcement learning offers a promising mechanism for online adaptation, it inherently requires access to a reward signal during deployment. However, precise reward computation in space is often infeasible due to the lack of external tracking systems and the overall complexity of the environment. To address the challenge of unobservable rewards, we introduce a reward-free continual learning framework that leverages latent-state world models. By…

---

### [Long-Horizon Audio-Visual Generation for Persistent Stories and Interactive Worlds](https://arxiv.org/abs/2608.23383v1)

- **arXiv**: `2608.23383v1`  |  **提交日期**: 2026-08-24
- **作者**: Nan Duan, Haoyang Huang, Weiyang Jin, Haoran Li, Yaowei Li, Yuming Li et al.

Video generation is progressing beyond isolated clips toward long-form narratives and interactive worlds, requiring models to preserve identities, follow user controls, and remain stable over extended rollouts. We present JoyAI-Echo-1.5, a unified audio-visual generation system with two purpose-built variants. The long-video variant introduces composable cross-shot memory that aggregates visual evidence across multiple prior shots and speaker cues derived from speech-filtered full-shot audio, enabling persistent character appearance and voice identity across flexible combinations of text,…

---

### [Future Querying: Can LLMs Serve as Implicit Medical World Models?](https://arxiv.org/abs/2608.23248v1)

- **arXiv**: `2608.23248v1`  |  **提交日期**: 2026-08-24
- **作者**: Siri Willems, James Butterworth, Lore Goetschalckx, Peter Vrancx, Philippe Modard, Elke Giets et al.

Traditional clinical prediction models rely on task-specific pipelines and curated, structured data, which scale poorly and underutilize unstructured text. To address this, we introduce future querying, a paradigm that probes whether large language models (LLMs) can function as implicit medical world models by evaluating their ability to answer time-indexed clinical queries about a patient's future. Our framework operates on unstructured clinical documentation using endpoint-agnostic training, enabling a single model to answer diverse clinical queries over patient trajectories without manual…

---

### [EchoWM: Open and Enterable Omnimodal World Models](https://arxiv.org/abs/2608.23189v1)

- **arXiv**: `2608.23189v1`  |  **提交日期**: 2026-08-24
- **作者**: Songchun Zhang, Yaowei Li, Junhao Zhuang, Weiyang Jin, Haoyu Wang, Xin Lu et al.

We present EchoWM, an omnimodal world model for enterable generative media that responds to continuous navigation while jointly generating 720p video, environmental sound, music and speech. We organize interaction around camera intent: in first-person scenes, it specifies observer motion, while in third-person scenes, camera--character dynamics are learned from data without view-specific controllers. Discrete commands and continuous poses are mapped to a shared metric-scale relative 6-DoF trajectory, with dataset-level calibration preserving motion magnitude across heterogeneous data. To…

---

### [From Generation to Simulation: How Far Are World Models from Being True Simulators?](https://arxiv.org/abs/2608.23070v1)

- **arXiv**: `2608.23070v1`  |  **提交日期**: 2026-08-24
- **作者**: Tong Wang, Huan Deng, Mucheng Yang, Yang He, Xiaohui Kuang, Gang Zhao

With the rapid progress of diffusion models and large-scale video generation, generative world models are increasingly expected to replace traditional simulators, including physics engines, game engines, and reinforcement-learning environments. Yet the remaining distance from generation to simulation lacks a systematic assessment. We present a capability-based study using an external yardstick: eight capabilities of a traditional simulator, namely asset construction, physics engine, interaction, controllability, stability, state feedback, diversity, and evaluation metrics. We trace three main…

---

### [LpWM: A Case for Sparse Representations in World Models](https://arxiv.org/abs/2608.22764v1)

- **arXiv**: `2608.22764v1`  |  **提交日期**: 2026-08-24
- **作者**: Yilun Kuang, Yash Dagade, Quentin Le Lidec, Lucas Maes, Randall Balestriero, Yann LeCun

Joint-embedding predictive architectures (JEPAs) learn latent dynamics for planning and avoid representation collapse by matching features to maximum-entropy distributions such as isotropic Gaussians, yielding dense representations. However, it is unclear whether dense representations are the most favorable geometry for modeling dynamics. In this work, we ask whether a different geometry, sparse representations, can make action-conditioned latent dynamics easier to model, and what dynamical structure emerges from such representations. We first show that nonlinear Lipschitz dynamics can be…

---

### [MOSH-WM: Mask-Grounded Soft-Hamiltonian Dynamics for Object-Centric World Models](https://arxiv.org/abs/2608.22750v1)

- **arXiv**: `2608.22750v1`  |  **提交日期**: 2026-08-24
- **作者**: Zhekai Wang, Haoxiang Huang, Xiang Liu, Zhikang Chen, Yueqing Sun, Qi Gu et al.

Object-centric world models forecast future videos by evolving a set of entity slots, but the variables receiving dynamics supervision are often unconstrained visual features. We introduce \method{}, a mask-grounded soft-Hamiltonian world model that makes its position-like state explicitly depend on slot-owned image support. A frozen video-slot encoder produces slots and masks; spatial moments of mask-owned support form a canonical state $Q$, temporal differences form $P$, and a learned energy supplies a soft directional bias to a bounded learned increment. Decoder-relevant appearance and…

---

### [Mol-JEPA: A multimodal Joint Embedding Predictive Architecture for Molecules](https://arxiv.org/abs/2608.22642v1)

- **arXiv**: `2608.22642v1`  |  **提交日期**: 2026-08-23
- **作者**: Florian Rottach, Sebastian Schieferdecker, William Rudman, Randall Balestriero, Carsten Eickhoff

Despite recent advances in molecular foundation models, several limitations remain, such as chemically invalid augmentations, modality collapse, and incomplete representation of biochemical environments. To address these challenges, we present \textbf{Mol-JEPA}, a scalable framework for learning molecular world models. Rather than relying on suboptimal molecular perturbations, our model uses modality masking to exploit information from molecular structures, cellular phenotypes, binding affinities, ADMET profiles, quantum chemistry simulations and other drug discovery data. Across various…

---

### [Where World Models Break: Natural-Input Failure Discovery](https://arxiv.org/abs/2608.22421v1)

- **arXiv**: `2608.22421v1`  |  **提交日期**: 2026-08-23
- **作者**: Zhanpeng Shi, Zi Liang, Rong Feng, Shiqin Tang, Xuyang Chen, Hongzong Li

World models predict action-conditioned futures and serve as critical internal simulators for downstream planning and control. However, catastrophic prediction failures of world models could dangerously propagate through the control pipeline, as subsequent agent or model training and decision-making depend heavily on the continuous environment evolution forecasted by these world models. Existing evaluations overlook this systemic risk: by aggregating average errors over benign generations from general queries, they fail to stress-test the model against catastrophic collapses under rare or…

---

### [Tracing the Unlabeled Storm: Cross-Variable Transfer in a Lagrangian Atmospheric JEPA Framework](https://arxiv.org/abs/2608.22358v1)

- **arXiv**: `2608.22358v1`  |  **提交日期**: 2026-08-23
- **作者**: K M Anirudh, S Sandeep, Hariprasad Kodamana

Deep atmospheric convection governs South Asian monsoon variability, yet attempting to learn its latent world model directly from zero-inflated, heavy-tailed precipitation yields suboptimal predictive representations. Continuous atmospheric proxies, such as outgoing longwave radiation (OLR), express this convective organization far more coherently. We address this mismatch with \emph{cross-variable proxy learning}: M-JEPA, a multiscale Monsoon Joint-Embedding Predictive Architecture, is pretrained on five continuous proxy fields over Lagrangian patches tracking moving convective…

---

### [Beyond Instance Slots: Semantically Rich World Models for Physical Interaction Planning](https://arxiv.org/abs/2608.22294v1)

- **arXiv**: `2608.22294v1`  |  **提交日期**: 2026-08-23
- **作者**: Juntao Cheng, Jingkai Wang, Yijun Shen, Xiansheng Chen, Zhiwei Yu

World models for physical interaction are typically trained to predict future observations or latent features; however, a planning-oriented model must answer a fundamentally different question: whether a candidate action produces a task-consistent future while preserving essential relations.Monolithic state representations obscure the underlying entities, while standard instance-level object slots merely identify \emph{what} is present without specifying \emph{what role} each entity plays in the task context. To bridge this gap, we present the Semantically Rich World Model (SR-WM), a…

---

### [On the Capability Separation Between World-Model Policy Learning and Imitated World-Action Models](https://arxiv.org/abs/2608.22197v1)

- **arXiv**: `2608.22197v1`  |  **提交日期**: 2026-08-23
- **作者**: Yang Yu

World-action models predict a future outcome and then infer an associated action. Although this factorization can improve representation learning and data efficiency, it is unclear whether it provides stronger control capability than direct behavior cloning when both are trained from the same observational demonstrations. We compare a direct behavior-cloning policy, an imitation-trained world-action policy, and a policy optimized with an action-conditioned world model. At the controller-class level, every world-action policy can be flattened into a direct stochastic policy with the same…

---

### [Inferring Action from Future Latent State for Robotic Manipulation](https://arxiv.org/abs/2608.22067v1)

- **arXiv**: `2608.22067v1`  |  **提交日期**: 2026-08-22
- **作者**: Fenghao Lei, Zhixiong Huang, Long Yang, Jiabao Chen, Jie Cheng, Peilin Huang et al.

World-Action Models (WAMs) build robot control on video-generation backbones, which jointly predict dense future visual trajectories and robot actions. We argue that video generation is an unnecessary intermediate objective for world-action modeling. For robotic manipulation, the goal of a world model is not to reproduce how the world looks at every intermediate moment, but to predict the state that the world will reach after an action is executed. The intermediate frames only describe the visual transition between physical states, which consumes substantial model capacity and computation,…

---

## 📅 2026-08-24

### [CIVA: Critic-Induced Value-Subspace Attacks on Visual World-Model Agents](https://arxiv.org/abs/2608.21114v1)

- **arXiv**: `2608.21114v1`  |  **提交日期**: 2026-08-21
- **作者**: Jiancheng Wang, Mingli Zhu, Tong Zhang, Jiaqi Ruan, Wei Wang, Siyuan Liang et al.

Visual world-model agents such as DreamerV3 act through a recurrent latent state rather than a single observation, which weakens frame-wise observation attacks and makes their perturbations vary sharply over time under a strict per-frame perturbation constraint. We study white-box, causal, online attacks on such agents and propose Critic-Induced Value-Subspace Attacks (\textbf{CIVA}). Our key observation is that, along a rollout, critic-guided perturbations concentrate in a low-dimensional subspace induced by the victim's own critic. Based on this observation, CIVA first probes the frozen…

---

### [AudioWorldSim: Realistic Binaural Audio Datasets For World Models](https://arxiv.org/abs/2608.21075v1)

- **arXiv**: `2608.21075v1`  |  **提交日期**: 2026-08-21
- **作者**: Luis Vitor Zerkowski, Luiz Velho

This technical report presents AudioWorldSim, an open-source platform designed to generate realistic binaural audio datasets and advance research in audio-based machine learning, particularly world models. Built as a custom extension of Meta's SoundSpaces 2.0 platform, AudioWorldSim leverages their comprehensive acoustics framework, but focuses on the automatic rollout of random agent navigations, as well as implements crucial fixes to how continuous sound is composed. AudioWorldSim is made publicly available to the research community at https://github.com/Luizerko/AudioWorldSim to facilitate…

---

### [Graph-Operator World Models for Morphology-Parameter Generalization in Continuous Control](https://arxiv.org/abs/2608.20936v1)

- **arXiv**: `2608.20936v1`  |  **提交日期**: 2026-08-21
- **作者**: Xu Yang, Yiqin Yang, Qianchuan Zhao

World models for continuous control are commonly trained for a fixed physical system and can degrade when known morphology parameters such as link lengths, masses, damping, and actuation change. Existing approaches often provide these parameters as conditioning information, but leave unspecified which part of the learned transition should remain reusable and which part should change with morphology. We propose Graph-Operator World Models (GraphOp-WM), a structured world model for generalization across unseen morphology parameters within related articulated robot families. GraphOp-WM…

---

### [IMU-Free Body-Frame State Estimation with Sparse Scene Flow for Quadcopters](https://arxiv.org/abs/2608.20891v1)

- **arXiv**: `2608.20891v1`  |  **提交日期**: 2026-08-21
- **作者**: Daniel Grønhaug, Sofie Markeset, Mathias Kolberg

We present a vision-only state estimation system for X-configuration quadcopters equipped with a canonical stereo camera pair and no inertial sensors. The system operates entirely in the body frame, requiring only synchronised stereo images and motor thrust commands. A continuous-discrete extended Kalman filter on a composite manifold state $\langle SE(3), \mathbb{R}^3, \ldots \rangle$ maintains estimates of body-frame pose, velocity, angular velocity, gravity, and disturbances, using stationary scene points as implicit inertial references. Feature points are detected (FAST, Shi-Tomasi),…

---

## 📅 2026-08-21

### [Orthogonal JEPA: Factorized Predictive States for Latent World Models](https://arxiv.org/abs/2608.20065v1)

- **arXiv**: `2608.20065v1`  |  **提交日期**: 2026-08-20
- **作者**: Taoyong Cui, Pheng Ann Heng, Wanli Ouyang

World models construct latent states that support prediction, planning, and reasoning about an underlying system. Joint-embedding predictive architectures (JEPAs) offer a direct way to learn such states by predicting targets in representation space instead of reconstructing every detail of the observation. Standard JEPAs, however, organize all predictable content through one target embedding and one prediction pathway. In complex systems, this monolithic state can allocate redundant capacity to dominant signals while providing weak or conflicting gradients to less dominant predictive…

---

### [ADAPT: Physics-Aware Diffusion-based World Models for Adaptive Predictive Transferable HVAC Control](https://arxiv.org/abs/2608.19804v1)

- **arXiv**: `2608.19804v1`  |  **提交日期**: 2026-08-20
- **作者**: Xu Yang, Kailai Sun, Dianyu Zhong, Qianchuan Zhao

Buildings account for roughly one-third of global energy consumption and CO$_2$ emissions. Optimizing indoor climate systems plays a critical role for urban climate mitigation aligned with UN Sustainable Development Goals 11 and 13. However, indoor delayed thermodynamic responses and partial observability severely hinder existing methods, which are primarily limited by implicit thermal inertia, occupancy dynamic prediction, and cumulative prediction errors, especially for out-of-distribution environments. In practice, these challenges are further exacerbated by the high cost and privacy…

---

### [An Irreducible Quantum Advantage in Aligning World Models with Reality](https://arxiv.org/abs/2608.19779v1)

- **arXiv**: `2608.19779v1`  |  **提交日期**: 2026-08-20
- **作者**: Josep Lumbreras, Hailan Ma, Jayne Thompson, Mile Gu

World models provide digital simulacra of the true world, allowing agents to be trained and tested before costly real-world deployment. At each time step, they receive an action and generate an observation and reward matching the statistics of the true world. In complex environments where present outcomes depend on events far in the past, this requires memory. One might expect that, by increasing memory, we can always build a model accurately enough to align the optimal agent policies of the real and virtual worlds. We show that this is false for classical world models, even when the true…

---

### [World-Model-Grounded LLM Planning for AUV and ASV Navigation Near Offshore Wind Farms](https://arxiv.org/abs/2608.19661v1)

- **arXiv**: `2608.19661v1`  |  **提交日期**: 2026-08-20
- **作者**: Markus Buchholz, Ignacio Carlucho, Yvan R. Petillot

Large language models can turn a natural-language mission into a sequence of robot actions, but they do not have a sense of physics: they cannot judge how long a command should run, or whether it will make the robot drift into an obstacle. We proposed the use of a world model to expand the capabilities of Large Language model-based planners. Our method has three components: a physics-grounded neural world model, a three-phase gradient-based trajectory optimizer, and a Model Predictive Controller (MPC)-style closed-loop replanner with a trust-region guard. The language model decides what to…

---

### [Beyond Multimodal Alignment: Certifying Physical Language through Response Substitution and Ordered Execution](https://arxiv.org/abs/2608.19492v1)

- **arXiv**: `2608.19492v1`  |  **提交日期**: 2026-08-19
- **作者**: Kaizhen Tan, Xin Xu, Siru Tao, Yixiao Li, Hanzhe Hong, Yang Feng et al.

World models increasingly treat compact multimodal representations as interfaces between perception and physical interaction, yet existing probes do not establish whether different sensors carry the same executable meaning or whether that meaning survives a new action composition. We introduce an operational capability hierarchy and the Disjoint-Bridge Operator-Substitution Certificate (DBOSC), which asks whether independently trained modality compilers enter a frozen response chart interchangeably on evidence outside their training panels. On Cluster Haptic, audio and acceleration…

---

### [DA-WAM: Decision-Aligned Future Latents for Driving World Models](https://arxiv.org/abs/2608.19085v2)

- **arXiv**: `2608.19085v2`  |  **提交日期**: 2026-08-19
- **作者**: Ruiguo Zhong, Benshan Ma, Xiaolong Chen, Lang Zhang, Mingyue Feng, Yaonong Wang et al.

Anticipating how scenes evolve under ego actions is fundamental to safe autonomous driving, yet the full potential of world models for decision-making remains unrealized. The critical challenge lies in ensuring that future modeling is not merely predictive, but decision-informative: the predicted future must directly shape which trajectory is selected. Existing approaches decouple future representation learning from planning optimization, or share predicted states across trajectory candidates, thereby diluting the action-specific consequences that ought to guide selection. To bridge this gap,…

---

## 📅 2026-08-20

### [DA-WAM: Decision-Aligned Future Latents for Driving World Models](https://arxiv.org/abs/2608.19085v1)

- **arXiv**: `2608.19085v1`  |  **提交日期**: 2026-08-19
- **作者**: Ruiguo Zhong, Benshan Ma, Xiaolong Chen, Lang Zhang, Mingyue Feng, Yaonong Wang et al.

Anticipating how scenes evolve under ego actions is fundamental to safe autonomous driving, yet the full potential of world models for decision-making remains unrealized. The critical challenge lies in ensuring that future modeling is not merely predictive, but decision-informative: the predicted future must directly shape which trajectory is selected. Existing approaches decouple future representation learning from planning optimization, or share predicted states across trajectory candidates, thereby diluting the action-specific consequences that ought to guide selection. To bridge this gap,…

---

### [AlphaClifford: Efficient Clifford Synthesis and Transpilation with Model-based RL](https://arxiv.org/abs/2608.18946v1)

- **arXiv**: `2608.18946v1`  |  **提交日期**: 2026-08-19
- **作者**: Daniele Lizzio Bosco, Jacopo Cossio, Carla Piazza, Giuseppe Serra

Clifford circuits play a foundational role in quantum computing, particularly due to their importance in quantum error correction and fault-tolerant logical synthesis. While these circuits can be efficiently simulated and represented as symplectic matrices, standard synthesis methods-such as the Aaronson-Gottesman algorithm-often yield sub-optimal circuits with excessively high gate counts. In this work, we introduce AlphaClifford, a model-based Reinforcement Learning framework powered by Monte Carlo Tree Search, designed to efficiently synthesize Clifford circuits from the fundamental gate…

---

### [Decision-Metric Alignment in Latent World Models: Diagnostics and Action-Conditioned Objectives for MPC Planning](https://arxiv.org/abs/2608.18746v1)

- **arXiv**: `2608.18746v1`  |  **提交日期**: 2026-08-19
- **作者**: Jiawei Wang, Ke Rui, Yushen Zuo, Yichun Feng, Minglei Li

JEPA-style latent world models can use Euclidean distance to a goal latent as the cost for model-predictive control (MPC). Strong decoding of task variables, however, does not guarantee that this particular cost ranks candidate action sequences by real task progress. We call the latter property \emph{decision-metric alignment}. We introduce Plan-Real Spearman, which measures latent--real rank agreement on random plans, and CEM-stage Spearman, which measures the same agreement as cross-entropy-method (CEM) search concentrates its proposal. We analyze sufficient conditions under which latent…

---

### [Reinforced Planning with Latent World Models](https://arxiv.org/abs/2608.18669v1)

- **arXiv**: `2608.18669v1`  |  **提交日期**: 2026-08-19
- **作者**: Armin Sommer, Jannik Schilling

Humans solve complex problems by constructing plans and mentally simulating their outcomes with an internal model of the world. Machine learning has produced world models that similarly predict the outcomes of action sequences, but the improvement of candidate plans still isn't fully learned. Current planners are either hand-designed, distilled from a hand-designed optimizer, or learned only to inform an amortized policy rather than to revise the plan itself. We introduce the Reinforced Planning, a method based on the idea that search can be learned by reinforcing good search rules into a…

---

### [Progressive Experience Fusion for Multi-Task World Model Control in Endovascular Navigation](https://arxiv.org/abs/2608.18647v1)

- **arXiv**: `2608.18647v1`  |  **提交日期**: 2026-08-19
- **作者**: Harry Robertshaw, Maxence Boels, Nikola Fischer, Sebastien Ourselin, Christos Bergeles, Alejandro Granados et al.

Autonomous endovascular navigation could support the delivery of mechanical thrombectomy to underserved areas, but controllers must navigate long, multi-stage paths across varying vascular anatomies. This study investigates Progressive Experience Fusion (PEF) to train a multi-task TD-MPC2 controller. We additionally evaluate a heuristic that changes the Model Predictive Path Integral planning horizon using residual action-sequence dispersion, and fine-tuning in a patient-specific simulation. Across five subtasks in ten known training anatomies with held-out targets, PEF achieved a mean…

---

### [Partition the Support, Reconstruct the Residual: Training-Free Sparse Attention for Video Generation and World Models](https://arxiv.org/abs/2608.18484v1)

- **arXiv**: `2608.18484v1`  |  **提交日期**: 2026-08-19
- **作者**: Pardis Taghavi, Reza Langari, Gaurav Pandey

Training-free block-sparse attention can accelerate video transformers, but row-wise attention concentration does not by itself specify an executable sparse operator. Queries sharing a block route may have poorly overlapping supports, while retained attention mass alone does not determine the post-softmax error from skipped interactions. We show that partition geometry affects both pooled support and the predictability of the remaining residual from the sparse output. We introduce SparsePR, which combines Response-Coupled Partitioning with Probe-Fitted Residual Reconstruction. Sampled-query…

---

## 📅 2026-08-19

### [Hydra-0: Action Flow for Generalist World Modeling and Control](https://arxiv.org/abs/2608.18077v1)

- **arXiv**: `2608.18077v1`  |  **提交日期**: 2026-08-18
- **作者**: Hongyu Li, Bowen Wen, Xinghao Zhu, Yixuan Wang, Yilun Du, Yunzhu Li et al.

We introduce Hydra-0, a generalist world model conditioned on action flow, which represents robot actions as pixel motion. This shared visual interface enables generalist world modeling and control by learning action consequences across embodiments, tasks, environments, and video-generation backbones. Our best configuration achieves 90.4% lower robot-motion error and 60.2% lower object-motion error than our action-conditioned baseline, while supporting zero-shot composition and data-efficient adaptation. On the RoboLab benchmark, Hydra-0 achieves a Pearson correlation of r=0.96 between…

---

### [Towards Zero-Shot Task Transfer with Neurosymbolic World Models](https://arxiv.org/abs/2608.17959v1)

- **arXiv**: `2608.17959v1`  |  **提交日期**: 2026-08-18
- **作者**: Isidoro Tamassia, Lennert De Smet, Giuseppe Marra

State-of-the-art model-based reinforcement learning methods learn neural world models that allow policy improvement by planning in a latent space, without assumptions on the structure of the underlying environment. While expressive, these models are generally task-dependent: they learn uninterpretable latent representations that are tied to the training task and thus hard to generalize to new tasks. In this work, we present a novel world model formulation where the reward prediction only depends on a subset of structured, symbolic components of the whole latent state. Decoupling observation…

---

### [An Omitted Mode Is a Rare Rule: The Sampling-Verification Danger Law in Continuous Code World Models](https://arxiv.org/abs/2608.17956v1)

- **arXiv**: `2608.17956v1`  |  **提交日期**: 2026-08-18
- **作者**: Javier Aguilar Martín

In the Code World Model paradigm an LLM synthesizes an executable world model that a classical planner searches, and the model is accepted when it reproduces sampled transitions. We ask what that acceptance certifies in continuous control. We define the pipeline's danger as an expected risk and isolate its exact factor: the probability that N i.i.d. gate rollouts all miss a critical event of probability r is exactly (1-r)^N; an independent acceptance sample adds its budget to the exponent. On three hybrid instruments the accepted mode-blind model is exploited: the planner is pinned at the…

---

### [No Gaussian Required: Contrastive Inverse Dynamics for JEPA World Models](https://arxiv.org/abs/2608.17542v1)

- **arXiv**: `2608.17542v1`  |  **提交日期**: 2026-08-18
- **作者**: Jack Boylan, Chris Hokamp

Joint-Embedding Predictive Architectures (JEPAs) learn world models by predicting future embeddings, but the objective admits a trivial solution of a constant encoder, so every practical system adds an anti-collapse mechanism (LeCun, 2022; Assran et al., 2023; Bardes et al., 2022; 2024). LeWorldModel (LeWM) prevents collapse with SIGReg, a regularizer that forces the latent distribution to match an isotropic Gaussian: the representation is stabilized by prescribing what it must look like, independently of the environment it models. We argue that the anti-collapse pressure can instead come…

---

### [WONDER: A Radio World Model-based Negotiation Framework for Multi-Agent UAV Coverage Optimization](https://arxiv.org/abs/2608.16955v1)

- **arXiv**: `2608.16955v1`  |  **提交日期**: 2026-08-16
- **作者**: Jiahao Huang, Rongpeng Li, Zhifeng Zhao, Guoru Ding, Honggang Zhang

Post-disaster damage to terrestrial infrastructure can disrupt wireless coverage,while Uncrewed Aerial Vehicle (UAV) swarms provide a promising solution for rapid restoration.However, due to the limitations in local geometry observations hidden radio impact,and inter-UAV communication,there exists a significant gap between locally visible movement choices and swarm-level coverage outcomes.To combat this gap,we propose a raido World-model-based Optimized Negotiation framework for Distributed UAV covERage (WONDER).Particularly, to tackle the unavailability of the future radio field from onboard…

---

## 📅 2026-08-18

### [HarnessEval-W: Agentifying the Evaluation of Visual Worlds](https://arxiv.org/abs/2608.16859v1)

- **arXiv**: `2608.16859v1`  |  **提交日期**: 2026-08-17
- **作者**: Weiliang Chen, Haowen Sun, Jun Gao, Jiawei Chi, Hanyang Wang, Qiyu Dai et al.

A benchmark should deliver more than a scalar score: what makes an evaluation trustworthy is the reasoning that justifies the score. This is especially critical for world models, where judging a rollout requires understanding whether physics, causality, and world state evolve correctly. Humans spot such violations naturally, yet no existing benchmark automates this capability: metrics are computed brute-force, leaving no reasoning chain that can be examined or verified. We introduce HarnessEval-W, an agentified evaluation pipeline that brings the harness paradigm from the LLM ecosystem to…

---

### [CaliBench: Are the Stochastic Dynamics of Video World Models Physically Calibrated?](https://arxiv.org/abs/2608.16829v1)

- **arXiv**: `2608.16829v1`  |  **提交日期**: 2026-08-17
- **作者**: Jonathan Sadeghi, Jenny Seidenschwarz, Jesse Allardice, Sirish Srinivasan, Benjamin Graham, Jeffrey Hawke

Video world models approximate the stochastic distribution of physical outcomes through generative sampling, but existing benchmarks score individual generations or compare distributions coarsely over a whole dataset, leaving the fine-grained aleatoric uncertainty of specific phenomena untested. We introduce CaliBench, which scores outcomes in a physically interpretable discrete space - a bin index, a die face, a suit, a colour - rather than a learned feature space such as in FID, so the distance from a known reference distribution is measured directly. We curate outcome spaces whose…

---

### [Orbit-Planner: Towards Latent World Models for On-Orbit Obstacle Avoidance of Satellite Agents](https://arxiv.org/abs/2608.16651v1)

- **arXiv**: `2608.16651v1`  |  **提交日期**: 2026-08-17
- **作者**: Zhijian Li, Chao Ren, Peijin Wang, Xian Sun

Satellite agents for on-orbit navigation tasks need to predict collision risks using limited onboard observations. However, conventional planners often rely on predefined maps and fixed environmental assumptions, limiting their adaptability in dynamic on-orbit scenarios. In this paper, we propose Orbit-Planner, a two-stage latent world model for on-orbit obstacle avoidance. Orbit-Planner learns action-conditioned spacecraft dynamics to perform future-state rollouts in latent space, and introduces a Physics Probe to decode physical state changes from imagined latent trajectories. Experiments…

---

### [Stable Multi-Step Rollouts via Uncertainty-Guided Hybrid Dynamics](https://arxiv.org/abs/2608.16431v1)

- **arXiv**: `2608.16431v1`  |  **提交日期**: 2026-08-17
- **作者**: Andrei Maalberg, Axel Neumann, Jens Knobloch

Multi-step rollouts are essential for model-based reinforcement learning (RL) and predictive control, yet learned dynamics models often become unstable when recursively applied, leading to divergence and unreliable policy updates. This paper proposes a model-agnostic hybrid dynamics framework that blends a provably contracting nominal model with a flexible excursion model through an uncertainty-guided switching law. The switching signal is derived from calibrated epistemic uncertainty and activates only when the system leaves the nominal region, ensuring that each model operates within its…

---

### [DriveCache: Action-Aware Caching for Driving World Model Inference](https://arxiv.org/abs/2608.16354v1)

- **arXiv**: `2608.16354v1`  |  **提交日期**: 2026-08-17
- **作者**: Jianchun Yang, Jian Liang, Xianda Guo, Pinhan Fu, Yanlun Peng, Conglang Zhang et al.

Driving video generation models support autonomous-driving development by predicting controllable future scenes for simulation, planning evaluation, and offline data generation. Diffusion-based driving generators repeatedly evaluate large backbones across denoising steps, which limits generation throughput. Existing diffusion acceleration methods reduce this cost, but general-purpose designs omit driving signals available before generation, such as ego speed and planned trajectories. Experiments across driving motions show that cache tolerance varies with ego translation and rotation,…

---

### [SCALE: State-Calibrated Latent Embeddings for JEPA Planning in the Right Geometry](https://arxiv.org/abs/2608.16287v1)

- **arXiv**: `2608.16287v1`  |  **提交日期**: 2026-08-17
- **作者**: Jiaming Hu, Yan Zheng, Tian Wang

Joint-embedding predictive world models plan by scoring predicted terminal embeddings against a goal embedding using a cost defined on the representation itself. Two prominent strategies for obtaining non-collapsed representations are to inherit a pretrained feature space, as in DINO-WM, and to learn an embedding end to end with anti-collapse regularization, as in LeWorldModel (LeWM) with SIGReg. These strategies show complementary strengths across tasks. Although task-relevant state is decodable from the full embeddings of both models, DINO-WM's leading principal components usually retain…

---

### [GaussianDWM++: Language-Grounded 3D Gaussian Driving World Model for Unified Scene Understanding, Editing, and Multi-Modal Generation](https://arxiv.org/abs/2608.16234v1)

- **arXiv**: `2608.16234v1`  |  **提交日期**: 2026-08-17
- **作者**: Tianchen Deng, Xuefeng Chen, Shuang Wu, Qu Chen, Jiajun Zhu, Bo Dai et al.

Driving World Models (DWMs) have recently advanced rapidly with generative models, yet most existing methods mainly focus on conditional scene generation and lack explicit 3D scene understanding, language-grounded reasoning, and controllable 4D editing capabilities. Moreover, commonly used point cloud, occupancy, or BEV representations make it difficult to achieve fine-grained alignment between textual information and the underlying 3D scene structure. To address these limitations, we propose a foundation-feature Gaussian driving world model that unifies scene understanding, language-grounded…

---

### [Beyond Visual CoT: Internalized Visual Thinking for Proactive Video Reasoning](https://arxiv.org/abs/2608.15869v1)

- **arXiv**: `2608.15869v1`  |  **提交日期**: 2026-08-16
- **作者**: Xiaoyu Zhu, Xinke Deng, Suresh Taddewadikar, Arnab Kumar Mondal, Zhongyu Jiang, Ian Fasel et al.

Multimodal large language models increasingly use visual chain-of-thought (Visual CoT) to reason about spatial, temporal, and embodied environments. By generating intermediate reasoning images, Visual CoT provides an intuitive mechanism for visual foresight but introduces substantial inference overhead, which is particularly problematic for proactive video reasoning. We ask whether models can learn to think visually during training while reasoning directly at inference. We introduce Internalized Visual Thinking (IVT), a post-training framework that jointly optimizes textual prediction and…

---

### [Physiological World Models for Human State Transitions](https://arxiv.org/abs/2608.15309v1)

- **arXiv**: `2608.15309v1`  |  **提交日期**: 2026-08-15
- **作者**: Chongyang Zhang, Rendong Wang, Hao Zheng, Hanwen Zhang, Yang Liu, Xiaolong Wei et al.

Continuous multimodal sensing now allows human physiology to be observed throughout daily life rather than only during occasional clinical visits. However, most health artificial intelligence systems are designed to recognize current states, estimate risks or analyse individual biomarkers. They do not directly model how physiological states change in response to real-world events, behaviours, contexts and interventions. Here we propose the Physiological World Model (PWM), an event-conditioned framework for learning these changes at the level of the whole person. We introduce the HumanState…

---

### [Low-Rank Dynamics-Effective Latent Carriers for Counterfactual Rollout in Learned World Models](https://arxiv.org/abs/2608.15156v1)

- **arXiv**: `2608.15156v1`  |  **提交日期**: 2026-08-15
- **作者**: Yang Liu, Yuming Chen

World models may predict the future without making clear which parts of their hidden state actually drive those predictions. We ask whether a small, directly addressable hidden-state change can place a learned world model on the intended counterfactual trajectory and then let the model continue that future on its own. We study a recurrent world model with a 192-dimensional hidden state in a controlled two-object, two-dimensional collision environment. For a bounded family of local velocity edits, we first verify that the model can natively represent and roll out the edited future. We then…

---

### [SCOPE: Score-Isolated Agentic Optimization for Video World Models](https://arxiv.org/abs/2608.15043v1)

- **arXiv**: `2608.15043v1`  |  **提交日期**: 2026-08-15
- **作者**: Yuhua Jiang, Jiaming Wang, Qingbin Liu, Feifei Gao

Video world models are increasingly used as simulators for planning and embodied decision making, yet improving them at inference time introduces a subtle evaluation problem: prompts, samplers, verifiers, and selectors may evolve together, making it difficult to attribute gains or prevent held-out feedback from shaping the final policy. We introduce \scope (\emph{\scopefullname}), a framework for auditable inference-time adaptation of frozen video world models. \scope represents external controls as a typed state, updates this state only through bounded changes supported by development…

---

### [Evidence of Absence: Cross-Modal Abductive Risk Perception to Sustain World Models When Vision Fails](https://arxiv.org/abs/2608.14952v1)

- **arXiv**: `2608.14952v1`  |  **提交日期**: 2026-08-15
- **作者**: Cong Xu, Ravi Sankar

A structured world-state (entities, relations, context, and predictive cues) is designed to preserve prediction-critical content when perception degrades, but it presumes observations to populate it; when the primary visual modality is occluded or degraded, those observations may be missing. We address how to sustain the world model from a complementary modality by treating the absence of expected co-evidence as evidence of a hidden cause. The abductive framework is modality-agnostic; this article instantiates it acoustically. A microphone-array front-end estimates the bearing of engine and…

---

## 📅 2026-08-17

### [Marionette: Predicting World States, Rendering Geometry, Painting Appearance](https://arxiv.org/abs/2608.14530v1)

- **arXiv**: `2608.14530v1`  |  **提交日期**: 2026-08-14
- **作者**: Zian Meng, Zhen Li, Chuanhao Li, Qiang Li, Kaipeng Zhang

Interactive game world models typically autoregress visual observations directly in pixel or latent space, forcing structured properties such as pose, geometry, and occlusion to be implicitly maintained by the same generative sequence. Over long horizons, errors in these latent world properties accumulate, making consistency and controllability fragile. We explicitly model the evolving world state, delegate exact geometric computation to a fixed, zero-parameter renderer, and leave the neural model to synthesize appearance. We instantiate this idea as Marionette, a world model for interactive…

---

### [Twin: Playing an Unknown Game with a Test-Time Digital Twin](https://arxiv.org/abs/2608.14490v1)

- **arXiv**: `2608.14490v1`  |  **提交日期**: 2026-08-14
- **作者**: Alexy Skoutnev, Kirill Acharya, Gaston Longhitano, Madeleine Udell, Kevin Ellis, Iddo Drori

We present a Test-time World-model Inference (Twin) system, in which a frontier coding agent writes an executable world model for completing continual learning tasks, such as ARC-AGI-3 games. Traditional approaches hand-engineer such models, one custom design per task. Each game hides its rules and goal, and our system constructs them from simulation and interaction alone. Its inductive prior over grid games is strong enough to recover the true transitions of the game and the goal on nearly all levels. Replay validation happens in a twin world model. The harness enforces that an action is not…

---

### [Ensuring Safe Physical AI in Urban Mobility via Hazard-Informed Synthesized Envelopes](https://arxiv.org/abs/2608.14481v1)

- **arXiv**: `2608.14481v1`  |  **提交日期**: 2026-08-14
- **作者**: Alexei Odinokov, Rostislav Yavorskiy

As heterogeneous robotic systems deploy across diverse urban zones, maintaining safety amid complex human-robot interactions remains a critical challenge. We present a unified framework that bridges systematic hazard analysis and runtime enforcement using hazard-informed safety envelopes. Rather than treating safety as a static constraint isolated within individual software modules, we introduce a cross-layer safety transformation process spanning symbolic, spatial, and dynamic world models. We show how this representation naturally interfaces with physical AI runtime harnesses to guarantee…

---

### [Traj-LeWM: Path-Aware World-Model Planning via Latent Trajectory Cost](https://arxiv.org/abs/2608.14125v1)

- **arXiv**: `2608.14125v1`  |  **提交日期**: 2026-08-14
- **作者**: Xiaodi Huang, Ziyi Ding, Jingtian Wan, Yuchen Liu, Yuan Zhang, Xiao-Ping Zhang et al.

LeWM is a lightweight visual world model that learns latent dynamics end-to-end from pixels and ranks candidate action sequences by the distance between their predicted endpoints and the goal. However, LeWM has two limitations. First, during training, it learns local next-step transitions without evaluating complete trajectories relative to the task goal. Second, during planning, it ranks candidates solely by predicted endpoint distance. Because model predictions may differ from actual execution outcomes, the candidate whose predicted endpoint is closest to the goal may not perform best when…

---

### [ForgeWM: Progressive Causal Training for Few-Step Action-Conditioned Video World Models](https://arxiv.org/abs/2608.14022v1)

- **arXiv**: `2608.14022v1`  |  **提交日期**: 2026-08-14
- **作者**: Xinye Li, Lingshuai Lin, Lei Wang, Liuzhou Zhang, Jialin Cui, Qingshan Li et al.

Action-conditioned video world models require low-latency causal generation and reliable responses to game-native controls. Although causal distillation enables one- or few-step video synthesis, extending it to interactive world models remains challenging, as discrete keyboard states and continuous mouse motion must remain aligned with temporally compressed latent chunks during causal training and autoregressive rollout. We introduce ForgeWM, a progressive framework that transforms a bidirectional action-conditioned video generator into efficient few-step world models through domain…

---

### [Ontology-Grounded World Models for Failure Diagnosis and Closed-Loop Repair in Physical AI Systems](https://arxiv.org/abs/2608.13901v1)

- **arXiv**: `2608.13901v1`  |  **提交日期**: 2026-08-14
- **作者**: Kailin Wang, Haoxiang Jie, Yaoyuan Yan, Jiacheng Zhou, Zhiyou Heng

EV-WM represents candidate quality with feature and event scores, but these scores do not explicitly record an unmet task predicate, a route label for an available correction mechanism, or a post-correction acceptance result. We present Onto-EV-WM, an ontology-grounded diagnosis and verification-gated correction interface layered above EV-WM rather than a replacement world-model architecture. The implemented task-local TBox defines entity types, predicate signatures, and constraints; source-specific grounding maps predicted or simulator-observed states to task ABoxes; and deterministic rules…

---

## 📅 2026-08-14

### [PlayWorld: Benchmarking World Models with Agent Players over Long-Horizon Objectives](https://arxiv.org/abs/2608.13552v1)

- **arXiv**: `2608.13552v1`  |  **提交日期**: 2026-08-13
- **作者**: Kaixin Ding, Xi Chen, Minghong Cai, Zhiyuan Xu, Yiyang Wang, Yuxiang Lu et al.

Video world models simulate future states conditioned on current observations and user actions. Recent systems have demonstrated impressive video consistency and action controllability over long sequences. However, fairly comparing these interactive models remains challenging. In practice, a human player typically evaluates a world model by pursuing long-horizon objectives through interaction. For example, a user may turn around 360 degrees to see whether the environment remains consistent, or walk into the water and inspect whether realistic water ripples are generated. The action sequence…

---

### [Alaya-EVOKE: From Linear-Scaling Supervision to Endless World](https://arxiv.org/abs/2608.13546v1)

- **arXiv**: `2608.13546v1`  |  **提交日期**: 2026-08-13
- **作者**: Yuanyang Yin, Gongxuan Wang, Yifan Zhan, Chuanhao Li, Kaipeng Zhang, Feng Zhao

Interactive world models must support persistent memory, responsive interaction, and long-horizon generation, yet these requirements place conflicting demands on the model. Maintaining history in the denoiser context or key-value cache incurs growing cost, forcing a trade-off between session length and retained memory, while low-latency interaction relies on few-step generation whose capabilities are bounded by its teacher. Evoke addresses both limitations by externalizing persistent world state and redesigning the teacher for long-horizon interactive generation. Scene geometry is maintained…

---

### [Intervention-Aware Clinical World Model for Post-Op Outcome Forecasting in Cardiology](https://arxiv.org/abs/2608.13518v1)

- **arXiv**: `2608.13518v1`  |  **提交日期**: 2026-08-13
- **作者**: Yunsung Chung, Yingshuo Liu, Abboud F. Hassan, Han Feng, Mary M. Maleckar, Nassir Marrouche et al.

Many clinical prediction models treat post-intervention outcomes as a one-step mapping from baseline measurements to a future endpoint. However, recovery after a procedure often unfolds as an irregular trajectory: clinical observations, medication changes, repeat interventions, and physiological measurements are recorded asynchronously and can change risk assessment over time. We propose an intervention-aware clinical world model that represents each patient with a structured latent state and evolves it through time-ordered post-intervention events. The model first encodes baseline imaging…

---

### [AlayaWorld: Interactive Long-Horizon World Modeling - Full Technical Report (v1.1)](https://arxiv.org/abs/2608.13492v1)

- **arXiv**: `2608.13492v1`  |  **提交日期**: 2026-08-13
- **作者**:  AlayaWorld Team, Kaipeng Zhang, Chuanhao Li, Yifan Zhan, Yongtao Ge, Yuanyang Yin et al.

This report presents an improved version of AlayaWorld. While the backbone architecture, chunk-wise autoregressive generation scheme, and training data remain unchanged from the previous release, we substantially revise how conditioning signals are represented and integrated into the model. The new design is guided by a simple principle: conditioning signals should match the generated content as closely as possible in both latent representation and temporal structure. To this end, we make two major changes. First, we replace the previous depth-warping-based spatial memory with a streaming 3D…

---

### [DreamX-Phi 1.0: Action-Conditioned Video World Model for Robotic Manipulation](https://arxiv.org/abs/2608.13489v1)

- **arXiv**: `2608.13489v1`  |  **提交日期**: 2026-08-13
- **作者**:  DreamX Team, Rui Chen, Xiangxiang Chu, Geng Li, Jifan Li, Qingfeng Shi et al.

We present \textbf{DreamX-Phi 1.0}, an action-conditioned video world model for robotic manipulation that, given an observed frame, a language instruction, and a prescribed action sequence comprising end-effector poses and gripper states, predicts the resulting future observations. Yet realism alone does not guarantee faithfulness: a convincing rollout can still move the wrong arm or lose the manipulated object. To ensure the prediction respects each arm's commanded path, we inject per-arm $\mathrm{SE}(3)$ transformations into attention via \textbf{PRoPE-style geometric encoding}, preserving…

---

### [A Unifying Perspective on Causal World Models: From Observations to Representations to Structure](https://arxiv.org/abs/2608.13456v1)

- **arXiv**: `2608.13456v1`  |  **提交日期**: 2026-08-13
- **作者**: Avinash Kori, Fabrizio Russo

World Models (WM) are increasingly seen as a foundation for intelligent agents that can predict, plan, and act beyond their training distribution. In this paper, we study WMs from a causal perspective across multiple levels of abstraction, ranging from perceptual observations to building a conceptual representation of the structure governing the environment dynamics. We argue that useful WMs must go beyond generative capabilities alone: they should also capture entity properties, entity-to-entity interactions, and entity-to-environment interactions that determine and explain the dynamics of a…

---

### [ContactGuard: Pre-Contact Execution Monitoring with Action-Conditioned Latent World Models](https://arxiv.org/abs/2608.13438v1)

- **arXiv**: `2608.13438v1`  |  **提交日期**: 2026-08-13
- **作者**: Gehan Zheng, Matthew Johnson-Roberson, Weiming Zhi

Contact-rich manipulation failures are often detected only after the robot has committed to contact. This is especially limiting in wrist-camera setups: close gripper--object views help observe contact, but a poor approach may already push, miss, slip, or disturb the object before conventional detectors react. We introduce \emph{ContactGuard}, a pre-contact execution monitor for chunked visuomotor policies. Given the policy's planned action chunk, ContactGuard predicts its short-horizon consequence in latent visual space and aborts if the predicted future latent indicates likely failure. Its…

---

### [S2-HWM: Sparse Event-Structured Hierarchical World Model for Long-Horizon Surgical Robot Manipulation](https://arxiv.org/abs/2608.13103v1)

- **arXiv**: `2608.13103v1`  |  **提交日期**: 2026-08-13
- **作者**: Shuzhe Zhang, Xin Zhu, Yinling Qian, Qiong Wang

Long-horizon surgical robot manipulation is challenging because task rewards are sparse, while meaningful interaction changes occur at irregular intervals. Existing world-model agents typically imagine at primitive-step resolution, leaving variable-duration task progress implicit. Manually specified stages can provide intermediate structure, but their task specific boundaries are difficult to align with state-dependent interaction transitions. We propose S2-HWM, a Sparse Event-Structured Hierarchical World Model that learns sparse event evidence from primitive latent trajectories to…

---

### [H2R-Bench: Benchmarking Human-to-Robot Manipulation Video Generation in World Models](https://arxiv.org/abs/2608.13049v1)

- **arXiv**: `2608.13049v1`  |  **提交日期**: 2026-08-13
- **作者**: Dingyi Rong, Yue Shi, Chaofan Ma, Jiezhang Cao, Zongrui Wang, Zeyu Zhang et al.

Large-scale manipulation data is essential for robot learning, yet collecting robot demonstrations remains expensive and difficult to scale. Meanwhile, abundant egocentric human manipulation videos provide rich behavioral experiences, but transferring them across embodiments remains challenging due to differences between human hands and robotic end-effectors. Recent advances in video world models offer a promising pathway to synthesize robot-centric manipulation videos from human observations, while their cross-embodiment transfer capability remains largely unexplored. Therefore, we introduce…

---

### [The Objective Is the Bottleneck: Latent World Models Encode What Their Planners Cannot Use](https://arxiv.org/abs/2608.12959v1)

- **arXiv**: `2608.12959v1`  |  **提交日期**: 2026-08-13
- **作者**: Joyjeet Singh

Latent world models are judged by how well they predict, so when planning fails at long horizons the natural reading is that the predictor degrades. On a reproduction of LeWorldModel on TwoRoom we show the binding constraint is the planner's objective instead. The predictor is not the limit: its imagined state seventy-five environment steps ahead is still only 0.189 as wrong as assuming the world froze, while the planner never imagines beyond twenty-five. The objective is. Cross-entropy-method planning minimises squared latent distance, which tracks true distance at r = 0.426, saturates by…

---

### [Diagnosing JEPA World Models with Action-Conditioned Predictive Consistency](https://arxiv.org/abs/2608.12939v1)

- **arXiv**: `2608.12939v1`  |  **提交日期**: 2026-08-13
- **作者**: Guo An, Zijing Wu, Honghua Dong, Yuhao Yan, Zixuan Gui, Haochong Chen et al.

Joint-embedding predictive architectures (JEPAs) learn world models that predict in a compact latent space rather than in pixels, reducing the pressure to model nuisance appearance. Yet this provides no guarantee against visual perturbations: they can still alter the encoded representation and affect subsequent action-conditioned predictions. Bisimulation captures this requirement precisely: two observations should be treated as the same state only when their action-conditioned consequences agree. Guided by this criterion, we introduce Action-Conditioned Predictive Consistency (ACPC), a…

---

### [HounsWorld: A Multimodal World Model for Hidden Patient-State Readout, Reconstruction, and Simulation](https://arxiv.org/abs/2608.12904v1)

- **arXiv**: `2608.12904v1`  |  **提交日期**: 2026-08-13
- **作者**: Yunhao Bai, Zhongwei Qiu, Guangyu Guo, Yiming Huang, Tony C. W. Mok, Qinji Yu et al.

Clinical intelligence requires estimating a patient's underlying condition from incomplete observations rather than learning isolated mappings from scans to answers. Volumetric medical images provide dense observations of anatomy, attenuation, and lesions, whereas clinical language provides sparse but complementary semantic observations. We formulate CT-centered intelligence as inference over a shared latent patient state, under which readout, reconstruction, and simulation all become state-dependent prediction problems. To operationalize this view, we introduce HounsBench, a computed…

---

### [Scaling Automatic Research Agents via World Models](https://arxiv.org/abs/2608.12564v1)

- **arXiv**: `2608.12564v1`  |  **提交日期**: 2026-08-12
- **作者**: Xiyuan Yang, Sheikh Sarwar, Jingru Cheng, Zhan Shi, Duanshun Li, Huiyuan Chen et al.

Automating empirical research is a long-standing direction of AI. Recent automatic research (AutoResearch) agents bring this goal within reach, as modern LLMs show the capability to independently implement solutions and learn from the execution outcomes. Behind these gains, post-training (especially RL) plays a central role. In this paper, we identify a fundamental tension when scaling RL for these agents: the two components of every AutoResearch trajectory (agent generation and environment execution) scale in very different manners, since all generation shares compute through batching, while…

---

### [Governed Persistent Memory: Source-Bound State Semantics and Fail-Closed Release for Long-Horizon Agents](https://arxiv.org/abs/2608.12476v1)

- **arXiv**: `2608.12476v1`  |  **提交日期**: 2026-08-12
- **作者**: Guodong Xu

Long-term agent memory is usually treated as select--store--retrieve, but retrieval does not decide whether contradictory, superseded, retracted, deleted, or stale records may support an outgoing claim. We introduce Governed Persistent Memory (GPM), an auditable bitemporal state-transition model with source-bound admission, derived lifecycle state, current public barriers, and fail-closed structured release. Five executable clauses cover ledger integrity, source binding, conflict isolation, non-revival after retraction or deletion, and exact claim closure over a fresh view at one verified…

---

## 📅 2026-08-13

### [Better Slots, Better Worlds: Representation Quality & Robustness in Object-Centric World Models](https://arxiv.org/abs/2608.12078v1)

- **arXiv**: `2608.12078v1`  |  **提交日期**: 2026-08-12
- **作者**: Shukrullo Nazirjonov, Sai Prasanna, Anna Manasyan, Georg Martius

Learning world models from offline trajectories enables agents to accomplish different tasks through planning. Object-centric (OC) representations, which decompose a scene into a set of slots that bind to its objects, have been proposed as an inductive bias for world models that are more sample-efficient and generalize better. Yet prior object-centric world models (OCWMs) take the slot encoder as given and evaluate only in-distribution, leaving open whether the object-centric bias actually delivers for planning and what within the OCWM drives it. We conduct a controlled study of OCWMs for…

---

### [How Can Driving World Models Do Counterfactual Prediction?](https://arxiv.org/abs/2608.11601v1)

- **arXiv**: `2608.11601v1`  |  **提交日期**: 2026-08-12
- **作者**: Jiaru Zhang, Can Cui, Yi Xu, Xin Ye, Ruqi Zhang, Ziran Wang

Driving world models are often interpreted as counterfactual simulators for observed driving episodes: given a factual driving log, they are asked what would have happened under an alternative ego action. In this paper, we identify a fundamental mismatch between this goal and direct action-conditioned prediction. The direct prediction uses the shared history and the alternative action but not the factual continuation observed after that history. It can therefore generate a plausible future without preserving what actually happened in this episode. We formalize this gap using the causal recipe…

---

### [VIScore: Diagnosing Planning-Relevant Quality in Latent World Models](https://arxiv.org/abs/2608.11174v2)

- **arXiv**: `2608.11174v2`  |  **提交日期**: 2026-08-11
- **作者**: Haiyu Wu, Randall Balestriero, Morgan Levine

Regulating the latent space to an isotropic Gaussian distribution provides a stable and information-maximized landscape for world model planning. However, the latent space property and successful planning remain disconnected. We first study this by comparing SIGReg and VISReg, two regularization loss functions with the same distribution target but different properties. Compared with SIGReg, VISReg has more flexibility in controlling the weights of center, scale, and shape regularization, and a larger batch size brings a finer distribution approximation. We find that the former, despite being…

---

### [ComBodied Agents: a New Paradigm of Human-Centric Agentic AI](https://arxiv.org/abs/2608.10915v2)

- **arXiv**: `2608.10915v2`  |  **提交日期**: 2026-08-11
- **作者**: Qianggang Ding, Xingyao Wang, Rui Feng, Zhibin Wang, Feixiang Yao, Kelong Mao et al.

After an older adult misses a medication dose, a software agent can send another reminder and an embodied agent can bring the medication. Yet neither explains whether the person forgot, is confused, has side effects, or deliberately refused, nor what support is appropriate. This reveals a structural gap in Agentic AI: Digital Agents primarily transform software states, while Embodied Agents transform physical states; neither makes a person's evolving state and agency the primary object of modeling, intervention, and evaluation. We introduce Combodied Agents, a human-centered paradigm that…

---

### [PBD-AG: Persistent Baseline-Delta Active Graphs with Uncertainty-Aware Inspection for Long-Horizon Service Robots](https://arxiv.org/abs/2608.10449v2)

- **arXiv**: `2608.10449v2`  |  **提交日期**: 2026-08-11
- **作者**: Shuo Bao, Wei Dong, Shuyue Zhang, Ming Shang, Yuchen Huang, Han Yu et al.

Long-horizon service robots require persistent world models that can be built autonomously in unseen environments and revised as task-relevant objects change. Existing methods rely on online mapping, which accumulates localization and observation errors, static scene representations that cannot capture persistent object changes, or holistic vision-language predictions that lack verifiable 3D geometric evidence. We present PBD-AG, a persistent baseline-delta active graph framework that decouples robot-verified stable fixtures from revisable dynamic object events. Under our framework, the robot…

---

## 📅 2026-08-12

### [Surgical WAM: A World-Action Model for Data-Efficient Surgical Robot Learning](https://arxiv.org/abs/2608.11204v1)

- **arXiv**: `2608.11204v1`  |  **提交日期**: 2026-08-11
- **作者**: Wenrui Bao, Tianyun Jiang, Zhiben Chen, Ser-Nam Lim, Peter D. Peng, Yuzhang Shang

Learning reliable surgical manipulation policies is bottlenecked by the scarcity of action-labeled demonstrations: teleoperated surgical robot (e.g., dVRK) trajectories with synchronized kinematics are costly to collect, while surgical tasks demand precise contact handling, long-horizon reasoning, and bimanual coordination. Endoscopic video is comparatively inexpensive and abundant relative to synchronized video--kinematics trajectories, and a natural way to exploit it is to learn world models of surgical scenes. However, existing surgical world models use video primarily for simulation or…

---

### [VIScore: Diagnosing Planning-Relevant Quality in Latent World Models](https://arxiv.org/abs/2608.11174v1)

- **arXiv**: `2608.11174v1`  |  **提交日期**: 2026-08-11
- **作者**: Haiyu Wu, Randall Balestriero, Morgan Levine

Regulating the latent space to an isotropic Gaussian distribution provides a stable and information-maximized landscape for world model planning. However, the latent space property and successful planning remain disconnected. We first study this by comparing SIGReg and VISReg, two regularization loss functions with the same distribution target but different properties. Compared with SIGReg, VISReg has more flexibility in controlling the weights of center, scale, and shape regularization, and a larger batch size brings a finer distribution approximation. We find that the former, despite being…

---

### [R4DSG: Relative 4D Scene Graph Memory for Object-Centric Question Answering in Long Egocentric Video](https://arxiv.org/abs/2608.11017v1)

- **arXiv**: `2608.11017v1`  |  **提交日期**: 2026-08-11
- **作者**: Ke Ma, Yamin Mao, Weiming Li, Shuai Tan, Yijie Zhong, Hao Chen et al.

Long-horizon egocentric video is a rich substrate for wearable AI assistants, but object-centric questions such as where an item was moved, when it last changed state, or why it was relocated remain difficult because caption- and transcript-based memories rarely preserve persistent object identity or structured spatial change. Existing long-video QA methods mainly emphasize temporal grounding and clip retrieval, while prior 3D scene-graph methods typically assume stronger geometry than free-motion wearable RGB video provides, including point clouds, RGB-D input, posed views, sparse…

---

### [ComBodied Agents: a New Paradigm of Human-Centric Agentic AI](https://arxiv.org/abs/2608.10915v1)

- **arXiv**: `2608.10915v1`  |  **提交日期**: 2026-08-11
- **作者**: Qianggang Ding, Xingyao Wang, Rui Feng, Zhibin Wang, Feixiang Wang, Kelong Mao et al.

After an older adult misses a medication dose, a software agent can send another reminder and an embodied agent can bring the medication. Yet neither explains whether the person forgot, is confused, has side effects, or deliberately refused, nor what support is appropriate. This reveals a structural gap in Agentic AI: Digital Agents primarily transform software states, while Embodied Agents transform physical states; neither makes a person's evolving state and agency the primary object of modeling, intervention, and evaluation. We introduce Combodied Agents, a human-centered paradigm that…

---

### [IADD-TR: Intervention-Aware Dynamics Decoupling with Targeted Regularization for Model-Based Reinforcement Learning](https://arxiv.org/abs/2608.10634v1)

- **arXiv**: `2608.10634v1`  |  **提交日期**: 2026-08-11
- **作者**: Zefeng Liang, Jie Qiao, Ruichu Cai, Weilin Chen, Zhifeng Hao

Model-based reinforcement learning (MBRL), which learns environment dynamics to generate synthetic experience, is a promising approach to sample-efficient decision making. Numerous methods have been developed to improve dynamics prediction and policy optimization for MBRL through uncertainty estimation, model regularization, and conservative value learning. However, these methods typically treat the transition model and critic as monolithic predictors, overlooking the policy-induced data bias. Consequently, action can become entangled with environmental evolution, while uneven action coverage…

---

### [Toward the Cognitive--Physical Limits of Embodied Intelligence through a World-Model-Centric Autonomous Racing Agent](https://arxiv.org/abs/2608.10618v1)

- **arXiv**: `2608.10618v1`  |  **提交日期**: 2026-08-11
- **作者**: Zitong Shan, Baichuan Lou, Yanxin Zhou, Shuge Wu, Xianqi He, Bolin Zhao et al.

Embodied artificial intelligence aims to develop agents that perceive, reason, and act through continuous interaction with the physical world. However, most embodied systems are still evaluated within conservative safety margins or moderate interaction regimes, leaving their capability boundaries under extreme conditions insufficiently understood. Autonomous racing provides a stringent testbed by combining high-frequency localization and perception, adversarial interaction, near-saturated vehicle dynamics, and strict safety constraints. Existing systems push high-speed performance but rarely…

---

### [PBD-AG: Persistent Baseline-Delta Active Graphs with Uncertainty-Aware Inspection for Long-Horizon Service Robots](https://arxiv.org/abs/2608.10449v1)

- **arXiv**: `2608.10449v1`  |  **提交日期**: 2026-08-11
- **作者**: Shuo Bao, Wei Dong, Shuyue Zhang, Ming Shang, Yuchen Huang, Han Yu et al.

Long-horizon service robots require persistent world models that can be built autonomously in unseen environments and revised as task-relevant objects change. Existing methods rely on online mapping, which accumulates localization and observation errors, static scene representations that cannot capture persistent object changes, or holistic vision-language predictions that lack verifiable 3D geometric evidence. We present PBD-AG, a persistent baseline-delta active graph framework that decouples robot-verified stable fixtures from revisable dynamic object events. Under our framework, the robot…

---

### [Stream Forcing: Constructing Unified Training Trajectory for Robust Streaming Video Generation](https://arxiv.org/abs/2608.10439v1)

- **arXiv**: `2608.10439v1`  |  **提交日期**: 2026-08-11
- **作者**: Yueting Zhu, Yuehao Song, Kaicheng Zhang, Bao Tang, Shaoyu Chen, Qian Zhang et al.

Streaming video generation holds strong potential for world modeling, where future frames must be inferred online sequentially to form a continuous video stream. However, streaming video diffusion models introduce a fundamental train-inference mismatch: inference follows a specialized denoising order, whereas advanced training strategies typically require diverse noise-level configurations. To address this trade-off between train-inference consistency and training coverage, we reformulate the video diffusion sampling as a frame-indexed stochastic process over noise levels. Within this…

---

### [Dreamer-SAC: Off-Policy Learning in Latent World Models for Sample-Efficient Autonomous Driving](https://arxiv.org/abs/2608.10386v1)

- **arXiv**: `2608.10386v1`  |  **提交日期**: 2026-08-11
- **作者**: Jiazhuo Li, Linjiang Cao, Qi Liu, Xi Xiong

Sample-efficient reinforcement learning for autonomous driving is often limited by the trade-off between data efficiency and model bias. While world models reduce the reliance on costly environment interactions, policy optimization over learned dynamics remains sensitive to prediction errors. This paper proposes the Dreamer-SAC framework, which integrates a recurrent state-space world model with an off-policy soft actor-critic algorithm trained directly in latent space. The framework uses a combination of real interactions and short-horizon generated trajectories with n-step target estimation…

---

### [FACT: Failure-Aware Causal Training for World-Action Models](https://arxiv.org/abs/2608.10232v1)

- **arXiv**: `2608.10232v1`  |  **提交日期**: 2026-08-10
- **作者**: Quanquan Peng, Yutong Liang, Rui Yan, Nicklas Hansen, Xiaolong Wang

Recent world-action models (WAMs) show that co-training policies with future prediction can provide physical priors for action generation. Building on the future-prediction ability of video models, many WAMs generate future videos and recover actions with inverse-dynamics models, or use these predicted videos as goal conditions for action generation. In both cases, the world model is trained mostly on successful demonstrations and has little reason to predict the consequences of bad actions. We introduce FACT, a causal World-Action Model that predicts future video and task progress…

---

### [The Evaluation Protocol Determines the Result: An Independent Reproduction of LeWorldModel on TwoRoom](https://arxiv.org/abs/2608.10145v1)

- **arXiv**: `2608.10145v1`  |  **提交日期**: 2026-08-10
- **作者**: Joyjeet Singh

LeWorldModel trains a latent world model with a prediction loss and a single anti-collapse regulariser, and reports approximately 87% of goals reached on TwoRoom, its simplest diagnostic environment. We reproduce that result by independent reimplementation on roughly $25 of rented compute, with all evaluation on one laptop CPU. We reach 94.0% at the repository's evaluation goal offset, against 84.0% for the authors' own released checkpoint measured under our protocol on identical episodes, and we reproduce the reported representation result directly (position probe Pearson r = 0.9988 against…

---

### [4D-WAM: 4D Consistent World Modeling for Autonomous Driving](https://arxiv.org/abs/2608.10107v1)

- **arXiv**: `2608.10107v1`  |  **提交日期**: 2026-08-10
- **作者**: Jiacheng Fu, Yibo Yuan, Meng Tian, Yue Li, Jiangtong Zhu, Jianhua Han et al.

Emerging World-Action Models (WAMs) have demonstrated promising performance in autonomous driving by jointly modeling future driving scene evolution and trajectory planning. However, existing WAMs are typically trained with video data, which is only 2D projections of the underlying 4D driving scene. Consequently, WAMs fail to understand and capture the structure of 4D scenes and thus generate visually plausible yet 4D inconsistent future predictions that mislead downstream planning. To alleviate this issue, we present 4D-WAM, a model that leverages geometric foundation models for…

---

### [Learning How the World Evolves: Extrapolative Video World Models via Latent Dynamics Reasoning](https://arxiv.org/abs/2608.09926v1)

- **arXiv**: `2608.09926v1`  |  **提交日期**: 2026-08-10
- **作者**: Haodong Li, Shaoteng Liu, Tianyu Wang, Chongjian Ge, Sihui Ji, Jiahan Zhang et al.

The world evolves following its dynamics, i.e., its laws of motion. However, leading video diffusion models largely fit the pixels without modeling how the pixels transit over time. Thus, they render visually plausible frames but may not accurately obey the laws. To capture the dynamics purely from pixels, we introduce Latent Dynamics Reasoning (LDR). LDR casts the latent transition as an explicit kinematic integration, where the lower-order dynamics are integrated numerically and the model regresses only the third- and higher-order residual that drives the rollout. For this integration to…

---

### [Energy-Structured Latent World Models with Neural Time Fields for Physically Constistent Open-World Motion Planning](https://arxiv.org/abs/2608.09876v1)

- **arXiv**: `2608.09876v1`  |  **提交日期**: 2026-08-10
- **作者**: Yapeng Liu, Yuanzhao Zhai, Bo Ding, Huaimin Wang, Lin Wang

Physically consistent motion planning remains a fundamental challenge in embodied AI, as generated trajectories must strictly conform to real-world execution dynamics. While latent world models offer a promising approach by predicting these dynamics, existing methods learn unconstrained future representations where absorbed physics remains implicit. Therefore, they fail to form reusable physical knowledge, which compromises reliability in unpredictable open-world navigation. To address this, we propose a novel Energy-Structured Latent World Model (ELWM). Our key idea is to structure the ELWM…

---

### [Model Discovery Agent: LLM-assisted Bayesian experiment design for data-efficient discovery of mechanistic world models](https://arxiv.org/abs/2608.09696v2)

- **arXiv**: `2608.09696v2`  |  **提交日期**: 2026-08-10
- **作者**: Kevin Murphy

Predicting the answer to interventional ``what if'' questions --- the outcome of an action never taken --- requires a \emph{mechanistic}, causal model, not a curve fit; and learning such a model requires \emph{experiments}, because passive data leaves its mechanisms unidentified. Experiments are expensive, so the central problem is \emph{data efficiency}. We present the Model Discovery Agent (MDA), which couples a large language model (LLM), used as a \emph{proposer} of candidate structures, with standard Bayesian machinery --- sequential Monte Carlo (SMC) for parameter and structure…

---

### [Sekai2: From World Exploration to Interactive World Modeling](https://arxiv.org/abs/2608.09449v2)

- **arXiv**: `2608.09449v2`  |  **提交日期**: 2026-08-10
- **作者**: Kang He, Wenshuo Peng, Zihui Gao, Jiaming Tan, Kaipeng Zhang, Yongtao Ge

Video world models must capture how scenes evolve over time and across viewpoints. Training them for long-horizon generation and camera control therefore benefits from long videos paired with camera trajectories and temporally grounded semantics. Existing corpora rarely offer the three together: large-scale web video provides broad visual diversity but no trajectories or time-aligned text, while pose-annotated datasets are typically short-range or reconstruction-oriented. We introduce Sekai2, a multi-source real-world video dataset that carries the world-exploration footage of Sekai toward…

---

## 📅 2026-08-11

### [Model Discovery Agent: LLM-assisted Bayesian experiment design for data-efficient discovery of mechanistic world models](https://arxiv.org/abs/2608.09696v1)

- **arXiv**: `2608.09696v1`  |  **提交日期**: 2026-08-10
- **作者**: Kevin Murphy

Predicting the answer to interventional ``what if'' questions --- the outcome of an action never taken --- requires a \emph{mechanistic}, causal model, not a curve fit; and learning such a model requires \emph{experiments}, because passive data leaves its mechanisms unidentified. Experiments are expensive, so the central problem is \emph{data efficiency}. We present the Model Discovery Agent (MDA), which couples a large language model (LLM), used as a \emph{proposer} of candidate structures, with standard Bayesian machinery --- sequential Monte Carlo (SMC) for parameter and structure…

---

### [verdi: retrieval is not transfer for continual world model optimization](https://arxiv.org/abs/2608.09537v1)

- **arXiv**: `2608.09537v1`  |  **提交日期**: 2026-08-10
- **作者**: Junyu Wu, Shiqin Nie, Youyi Kou, Baohua Yin, Guocai Yao, Qingyu Chen et al.

Foundation world models have made remarkable progress in planning, simulation, and embodied intelligence. However, optimizing a pretrained world model toward a user-specified objective remains difficult: each campaign typically rediscovers optimization strategies from scratch, and the resulting knowledge rarely transfers to the next model. Existing research agents automate the optimization loop but treat successful strategies as directly reusable recipes, without principled safeguards for when transfer is appropriate. We argue instead that retrieval is not transfer: a strategy validated on…

---

### [Sekai2: From World Exploration to Interactive World Modeling](https://arxiv.org/abs/2608.09449v1)

- **arXiv**: `2608.09449v1`  |  **提交日期**: 2026-08-10
- **作者**: Kang He, Wenshuo Peng, Zihui Gao, Jiaming Tan, Kaipeng Zhang, Yongtao Ge

Video world models must capture how scenes evolve over time and across viewpoints. Training them for long-horizon generation and camera control therefore benefits from long videos paired with camera trajectories and temporally grounded semantics. Existing corpora rarely offer the three together: large-scale web video provides broad visual diversity but no trajectories or time-aligned text, while pose-annotated datasets are typically short-range or reconstruction-oriented. We introduce Sekai2, a multi-source real-world video dataset that carries the world-exploration footage of Sekai toward…

---

### [WorldSimProbe: Diagnosing Simulator Faithfulness in Action-Conditioned World Models for Embodied Manipulation](https://arxiv.org/abs/2608.09298v1)

- **arXiv**: `2608.09298v1`  |  **提交日期**: 2026-08-10
- **作者**: Peterson Co, Sicheng Hu, Chunxuan Jiao, Hongyang Cheng, Yulin Luo, Yijie Xu et al.

Action-conditioned world models (ACWMs) promise to provide embodied AI with scalable predictive simulators for planning, policy evaluation, and data generation. Realizing this promise requires precise action-conditioned transitions rather than merely plausible outputs. Yet their applicability remains difficult to establish because prevailing evaluations emphasize visual quality, task outcomes, or coarse rollout-level responsiveness without directly testing simulator fidelity. To address this gap, we evaluate ACWMs through the observable capabilities expected of physical simulators.…

---

### [Did the Grid Erase the Event? EndoClock for Auditing Medical World-Model Pipelines](https://arxiv.org/abs/2608.09266v1)

- **arXiv**: `2608.09266v1`  |  **提交日期**: 2026-08-10
- **作者**: Yarin Udi, Tom Sharon-Shahak, Roee Masad, Dan Pri-Tal

Medical world models commonly learn from multimodal recordings synchronized onto a fixed-rate grid. This preprocessing resamples each native stream onto a shared time axis. Each stream has an observation clock that governs when observations are emitted or updated. When this clock depends on the latent or acquisition state, it is endogenous. In such settings, synchronization may not be neutral and can erase task-relevant evidence before the model sees the data. We introduce a four-regime taxonomy that characterizes where the evidence needed to distinguish a target event or state survives. The…

---

### [Latent World Models with Monotone Planning Costs for Image-Goal Navigation](https://arxiv.org/abs/2608.09073v1)

- **arXiv**: `2608.09073v1`  |  **提交日期**: 2026-08-10
- **作者**: Amirhosein Chahe, Siwei Cai, Lifeng Zhou

Image-goal navigation with latent world models requires not only accurate future prediction, but also a planning cost that reliably ranks candidate action sequences. We define the cost as the cosine distance between the predicted future embedding and the goal embedding, and show that poor cost ordering can mislead sampling-based planners such as Cross-Entropy Method (CEM). To address this, we propose a latent world model built on a frozen DINO-family encoder and train it with two complementary objectives. An autoregressive rollout loss reduces the gap between training and multi-step planning…

---

### [Twin Rollouts: Noise-Coupled Counterfactual Branching in Interactive Video World Models](https://arxiv.org/abs/2608.08982v1)

- **arXiv**: `2608.08982v1`  |  **提交日期**: 2026-08-10
- **作者**: Yu Ma, Hongli Shi, Xinran Xu

Interactive video world models generate rollouts autoregressively under an action stream, yet they are trained and evaluated almost exclusively on factual prediction. We study counterfactual generation inside the rollout: given a trajectory the model has itself generated, what would have happened had the actions differed from step t* onward? We formalize noise-coupled twin rollouts --- a factual and a counterfactual branch sharing the generated prefix and the future exogenous noise sequence, diverging only in the action stream at an intervention point. Because the factual branch is…

---

### [Hierarchical Topology-Aware Planning and Control of Underwater Vehicle-Manipulator Systems in Confined Environments](https://arxiv.org/abs/2608.08871v1)

- **arXiv**: `2608.08871v1`  |  **提交日期**: 2026-08-09
- **作者**: Mohamed Abdelwahab, Ruggero Carli, Damiano Varagnolo, Alberto Dalla Libera

This paper addresses autonomous intervention with an underwater vehicle--manipulator system (UVMS) in confined, cluttered, and partially known environments, where poor maneuverability, narrow passages, and uncertain execution may cause the robot to enter unrecoverable regions. We propose MANTA, a three-layer hierarchical planning-and-control framework that couples passage accessibility, manipulation feasibility, and closed-loop execution. The first layer performs global connectivity reasoning in a conservative reduced base space to extract traversable corridor candidates toward the task…

---

### [A Structural Dynamics Graph World Model: Unified Modeling, Constrained Rollout, and Interpretable Calibration](https://arxiv.org/abs/2608.08689v1)

- **arXiv**: `2608.08689v1`  |  **提交日期**: 2026-08-09
- **作者**: Wei Wang, Yaosen Chen, Han Yang, Yuegen Liu, Mingli Luo, Xinxin Jiao et al.

The state evolution of a complex system arises jointly from object laws, relational propagation, domain conservation, and unmodeled error. Forcing all sources into one black box makes mechanism attribution and constraint preservation unauditable; forcing every mechanism into one equation family discards mature domain solvers. We propose SD-GWM, a Structural Dynamics Graph World Model as an executable structural contract: nodes declare self-dynamics S, edges declare neighbor graph-coupled dynamics N---both fixed-form mechanism assets (rules, ODEs, solvers) calibrating only authorized…

---

### [Population-Scalable Multi-Agent World Modeling](https://arxiv.org/abs/2608.08600v1)

- **arXiv**: `2608.08600v1`  |  **提交日期**: 2026-08-09
- **作者**: Renjie Zhao, Yuxiang Wu, Mingyu Zhang, Jiaxin Li, Sisi Li, Yimin Sheng et al.

World models have recently achieved impressive progress in visual prediction and interactive generation, but extending them to multi-agent environments introduces a fundamental scalability challenge. Existing methods generally assume a fixed number of agents during training and inference, which ties the model to a pre-determined agent population and limits inference-time scalability. Our key insight is that cross-view consistency should arise from a shared world state whose evolution does not assume a predefined number of agents, while agent-specific observations should be generated by…

---

### [MotionCraft: Latent World Modeling with Sparse Attention for Visual Upscaling](https://arxiv.org/abs/2608.08553v1)

- **arXiv**: `2608.08553v1`  |  **提交日期**: 2026-08-09
- **作者**: Rong Fu, Chunlei Meng, Yangchen Zeng, Xiaowen Ma, Yongtai Liu, Wangyu Wu et al.

Video super-resolution (VSR) aims to recover high-fidelity high-resolution videos from low-resolution inputs and is central to applications ranging from mobile capture to streaming and archival restoration. Existing approaches trade off among local-detail fidelity, long-range spatio-temporal modeling, perceptual realism, and efficiency: convolutional alignment techniques preserve local structure but suffer when motion is large or degradations are complex; transformer-based methods capture long-range dependencies yet require architectural or algorithmic adaptations to remain computationally…

---

### [SurgWMBench: A Vision-Based Benchmark for World-Modeling Surgical Instrument Motion Planning](https://arxiv.org/abs/2608.08070v1)

- **arXiv**: `2608.08070v1`  |  **提交日期**: 2026-08-08
- **作者**: Huanrong Liu, Weiliang Huang, Bob Zhang, Weichao Cai, Chunlin Tian, Qingbiao Li

Reliable surgical planning requires models that move beyond recognizing the current surgical step or imitating expert demonstrations, and instead anticipate how instrument motion reshapes subsequent operative states. Most surgical video understanding methods focus on recognizing phases, actions, or workflow states, while providing limited support for explicitly modeling instrument motion. Conversely, existing tool motion prediction methods can forecast instrument trajectories, but they generally do not capture the coupled evolution of future surgical video states. World models offer a natural…

---

### [4D-WAM: Infusing Spatiotemporal Awareness into World Action Models through Trajectory Fields](https://arxiv.org/abs/2608.08023v1)

- **arXiv**: `2608.08023v1`  |  **提交日期**: 2026-08-08
- **作者**: Lishan Yang, Wenxuan Song, Xi Wang, Pingyue Sheng, Zheng Fang, Ziyang Zhou et al.

Building on recent advances in world models, World Action Models (WAMs) jointly model video prediction and action generation. However, they typically represent videos in 2D pixel space, creating a representation gap with 3D space in which robotic actions are executed. Recent 3D approaches introduce 3D information, but fail to fully exploit the dynamics of 3D structures. In this work, we propose 4D-WAM, a model-agnostic training strategy that injects spatiotemporal knowledge from 3D trajectory fields into WAMs through representation alignment. To this end, we introduce two complementary…

---

### [Distilling Physical Priors into Streaming World Models](https://arxiv.org/abs/2608.07981v1)

- **arXiv**: `2608.07981v1`  |  **提交日期**: 2026-08-08
- **作者**: Liangliang Zhao, Junying Wang, Danni Yang, Yifan Chang, Bin Fu, Yu Qiao et al.

Streaming world models predict future visual states online while maintaining physically coherent dynamics over long horizons. However, their rollouts often violate basic physical constraints. A common approach distills pretrained bidirectional DiTs into few-step causal generators. However, this paradigm suffers from two fundamental limitations: generic bidirectional teachers acquire limited physical priors from visually oriented pretraining, and the limited priors suffer further loss during bidirectional-to-causal distillation. We present PhyS, a three-stage framework for distilling physical…

---

## 📅 2026-08-10

### [Beyond Myopic World Models: Long-Horizon End-to-End Training for Direct Future Prediction](https://arxiv.org/abs/2608.07420v1)

- **arXiv**: `2608.07420v1`  |  **提交日期**: 2026-08-07
- **作者**: Xinyi Li, Zaishuo Xia, Chenjie Hao, Yubei Chen

World models are expected to support imagination over extended temporal horizons, yet most are still trained through local few-step prediction objectives and deployed by recursively rolling out their own predictions. This creates a fundamental mismatch: few-step losses optimize local transition fidelity, while long-horizon prediction depends on how errors and gradients propagate through the entire trajectory. As a result, transitions with different downstream influence on the endpoint are treated uniformly during training, and small local errors are amplified through recursive inference. We…

---

### [UniJEPA: A Unified Joint-Embedding Predictive Architecture for Task-Agnostic Visual World Modeling](https://arxiv.org/abs/2608.07409v1)

- **arXiv**: `2608.07409v1`  |  **提交日期**: 2026-08-07
- **作者**: An Lanji, Dawei Liu, Jin Li, Haoran Xu, Mei Chen, Yu Tian

Joint-Embedding Predictive Architectures (JEPAs) have emerged as a principled framework for self-supervised learning of world models in compact latent spaces, yet existing methods are fragmented: some predict masked parts of a single image in latent space (I-JEPA), others learn to predict global photometric transformations (Image World Models), while video-scale JEPAs predict future temporal states and are post-trained for action-conditioned planning (V-JEPA~2, DINO-World, DINO-WM). These objectives are treated as distinct recipes with separate encoders, predictors, and anti-collapse…

---

### [Addressable Memory for Video World Models](https://arxiv.org/abs/2608.07408v1)

- **arXiv**: `2608.07408v1`  |  **提交日期**: 2026-08-07
- **作者**: Xindi Wu, Sven Elflein, James Lucas, Olga Russakovsky, Laura Leal-Taixé, Despoina Paschalidou et al.

We study visual persistence in interactive video world models. These models rely on a Key-Value (KV) cache as a growing visual memory to carry forward previously generated frames. However, we find that models can no longer reliably address stored content once rollouts extend beyond the training horizon, because temporal Rotary Positional Embeddings (RoPE) offsets then fall outside the range seen during training and the model struggles to retrieve the relevant visual information through attention. Moreover, naively compressing the cache in the RoPE-rotated space corrupts memory by averaging…

---

### [From Optimal Actions to World Models: Identifiability of Transition Kernels in Discounted MDPs](https://arxiv.org/abs/2608.07301v1)

- **arXiv**: `2608.07301v1`  |  **提交日期**: 2026-08-07
- **作者**: Neal Batra

We study what can be recovered about the transition probabilities of a Markov decision process from optimal actions alone. This is closely related to the inverse problem considered by Letcher et al., who ask when the dynamics can be recovered from numerical \(Q\)-values. Here the numerical values themselves are not observed; only the optimal actions are known, for every reward in a given class. For state-action rewards \(r(s,a)\), knowing the optimal actions for every reward also tells us how much better one action is than another when each is followed by the same fixed policy. This is still…

---

### [MemWM: Memory-Augmented Text-Based World Model](https://arxiv.org/abs/2608.07107v1)

- **arXiv**: `2608.07107v1`  |  **提交日期**: 2026-08-07
- **作者**: Yujun Wang, Tao Zhang, Jinhe Bi,  Aniri, Wenxuan Ye, Boliang Liu et al.

World models are increasingly used to support planning in agents by predicting how environment states evolve in response to agent actions. Yet fluent next-state predictions can still omit task-critical facts, corrupt product attributes, or apply incorrect transition rules. To address such systematic prediction errors, we introduce MemWM, a memory-augmented text-based world model. MemWM uses world memory, a curated memory bank of transition rules, state caches, and hard-to-predict facts, to condition next-state imagination. We evaluate factual state preservation with Structured State Fidelity…

---

### [Transformers Struggle to Use Their Emergent World Models: Revisiting the Tower of Hanoi, and the Illusion of Thinking](https://arxiv.org/abs/2608.07077v1)

- **arXiv**: `2608.07077v1`  |  **提交日期**: 2026-08-07
- **作者**: Devin Pereira, Willem Zuidema

The Tower of Hanoi is a simple planning puzzle that in prior work has proven challenging for large reasoning models (LRMs). Current models solve the standard formulation of the puzzle, but still struggle with the flat-to-flat variant (where initial and goal states are not restricted to have all rings on a single peg). This paper presents an in-depth study of how both small, in-house Transformers and large, third-party LRMs solve this task. To understand the failures mechanistically, we first train small Transformers from scratch on precomputed solution traces. Using a variety of…

---

### [Is Forward Prediction Enough? Physical State Grounding for JEPA World Models](https://arxiv.org/abs/2608.06799v1)

- **arXiv**: `2608.06799v1`  |  **提交日期**: 2026-08-07
- **作者**: Haodong Yan, Jiaguan Zhu, Mingyuan Jia, Ruiqing Yin, Junjie He, Zhide Zhong et al.

Learning structured and control-relevant latent representations remains a key challenge for world models. Recent JEPA-based world models learn action-conditioned predictive latent dynamics from observation sequences. However, their forward-prediction objectives do not explicitly enforce reliable identifiability of robot-centric physical state from individual latents or state changes from latent pairs, which can limit downstream planning and policy performance. We propose PSG-JEPA, a physically grounded JEPA world model that shapes its latent space with two complementary grounding objectives…

---

### [Surg-UniWorld: A Unified Surgical World Model with Multimodal Control Experts](https://arxiv.org/abs/2608.06770v1)

- **arXiv**: `2608.06770v1`  |  **提交日期**: 2026-08-07
- **作者**: Rulin Zhou, Wanhao Liu, Guoheng Ma, Liangjin Shao, Qiujie Song, Yidu Wang et al.

Controllable surgical world models can provide a generative foundation for surgical artificial intelligence and simulation by synthesizing realistic instrument--tissue interactions. However, existing methods lack a unified multimodal control paradigm, while direct fusion of heterogeneous visual conditions often causes anatomical distortion, instrument appearance drift, and temporally inconsistent interactions. In this work, we propose {Surg-UniWorld}, a unified surgical world model with multimodal control experts. Surg-UniWorld first constructs a {Hierarchical Surgical Anchor} from…

---

### [Dueling World Models: Advantage-Style Action Channels for Common-Mode Distractor Rejection](https://arxiv.org/abs/2608.06706v1)

- **arXiv**: `2608.06706v1`  |  **提交日期**: 2026-08-07
- **作者**: Jiazhuo Li, Yiming Fei, Zhiruo Zhou, Heikichi Hayashi

Latent world models plan by predicting future states from an action, but when a scene contains motion the agent does not control, they quietly go action-blind: predictions for different actions become indistinguishable even as the training loss keeps improving. Existing remedies suppress this distraction with reconstruction, task reward, or auxiliary objectives, each adding machinery or assumptions. We show that a minimal alternative suffices, borrowed from the dueling decomposition of value into a state baseline and an action advantage: in latent dynamics, subtracting a prediction's mean…

---

## 📅 2026-08-07

### [GeniWorld: A Generalizable Interactive World Model for Robotic Manipulation via Visual Actions](https://arxiv.org/abs/2608.06332v1)

- **arXiv**: `2608.06332v1`  |  **提交日期**: 2026-08-06
- **作者**: Chenghao Gu, Hanyang Yu, Jingbo Zhang, Haitao Lin, Wenyao Zhang, Jinghe Wang et al.

Generalist robot policies exhibit strong capabilities, but their robustness in complex and unseen environments remains limited. Scaling robot learning and evaluation in diverse real-world environments remains costly and challenging. Action-conditioned world models offer a promising alternative, but they often suffer from limited action controllability and poor generalization to out-of-distribution (OOD) scenarios. To this end, we present GeniWorld, an interactive world model for robots that generalizes robustly across unseen scenarios. Building on pretrained video generative models, we use…

---

### [MASS: Multiplayer World Models with Authoritative Shared State](https://arxiv.org/abs/2608.06257v1)

- **arXiv**: `2608.06257v1`  |  **提交日期**: 2026-08-06
- **作者**: Ziqi Cai, Siqi Yang, Yimu Wang, Zixian Gao, Yunheng Liu, Shuchen Weng et al.

Current video world models struggle in multiplayer environments because they entangle world state with view-dependent visual latents, leading to redundant compute, view inconsistencies, and poor scalability. We propose MAS (Multiplayer world models with Authoritative Shared State) to resolve this limitation. Inspired by multiplayer game architectures, MAS disentangles world dynamics and view rendering. A learned Logic Engine advances a global, authoritative typed state from joint actions without any hand-written transition function, acting as the sole recurrent memory and synchronization…

---

### [From Passive Mirrors to Active Agents: Holonic Digital Twins for Physical AI over Networks](https://arxiv.org/abs/2608.06227v1)

- **arXiv**: `2608.06227v1`  |  **提交日期**: 2026-08-06
- **作者**: Christo Kurisummoottil Thomas, Omar Hashash, Walid Saad

Despite advances in artificial intelligence (AI) across multiple sectors, today's AI tools, including deep learning and generative AI, still fail when embedded into physical systems, such as robots and vehicles operating under real-world physical laws. This stems from their inability to maintain reliable world models for long-horizon planning under uncertainty and generalize to unseen scenarios. In this context, wireless networks, through pervasive sensing and communication, can orchestrate physical intelligence. However, current architectures optimize throughput, latency, and reliability and…

---

### [EnvACE: Internalizing Environment Dynamics via World Rehearsal for Agentic Reinforcement Learning](https://arxiv.org/abs/2608.06197v1)

- **arXiv**: `2608.06197v1`  |  **提交日期**: 2026-08-06
- **作者**: Zishan Xu, Zhiyuan Yao, Yuxin Chen, Yifu Guo, Zhengxi Lu, Yuquan Lu et al.

Training large language model agents for long-horizon tool use typically relies on interactions with real or synthesized executable environments, whose construction and verification are costly, or on external simulators that are difficult to ground. We introduce EnvACE, an agentic reinforcement learning method that replaces external environment interaction during training with world rehearsal. The policy alternates between acting and rehearsal: it first generates a tool call, then plays the role of the environment to produce the response induced by that action, and conditions subsequent…

---

### [Adaptive-WAM: Quality-Guided Early-Exit Planning from Intermediate Video-Diffusion Features](https://arxiv.org/abs/2608.06008v1)

- **arXiv**: `2608.06008v1`  |  **提交日期**: 2026-08-06
- **作者**: Sining Ang, Yuguang Yang, Yan Wang

Large video diffusion models provide rich spatiotemporal priors for autonomous driving, but existing world-action models often inherit the cost of iterative future-video generation even though deployment only requires an ego trajectory. We ask a more basic question: how much of a video diffusion model must be executed to make a reliable driving decision? Through a controlled study of video denoising timesteps and Diffusion Transformer (DiT) depth, we find that planning performance is largely insensitive to the tested video-noise levels, whereas strong trajectories can already be decoded from…

---

### [GAUGE: A Measurement-Grounded Benchmark for Physical Fidelity in Simulation Engines and Video World Models](https://arxiv.org/abs/2608.05948v1)

- **arXiv**: `2608.05948v1`  |  **提交日期**: 2026-08-06
- **作者**: Shuai Wang, Yaxin Feng, Xuekun Jiang, Shihan Tian, Ningyu Yan, Xing Shen et al.

Physics engines facilitate large-scale training and evaluation for embodied intelligence, while generative video world models are emerging as implicit simulators of future states and interactions. However, existing evaluations of physical fidelity are often conducted in isolation and rely heavily on perceptual similarity or human judgments, providing limited insight into which physical principles or parameters are violated. We introduce GAUGE, a real-world-grounded diagnostic benchmark for jointly evaluating how numerical simulators and generative video world models reproduce or deviate from…

---

### [AppDeltaWorld: Transition-Grounded Delta Code World Model for Mobile GUI Agents](https://arxiv.org/abs/2608.05891v1)

- **arXiv**: `2608.05891v1`  |  **提交日期**: 2026-08-06
- **作者**: Weikai Xu, Yunren Feng, Haoxiang Lei, Kun Huang, Yuxuan Liu, Kang Zhao et al.

Mobile GUI agents can operate apps through pixel perception and touch actions, making them a promising interface for collecting and improving long-horizon mobile interaction policies. However, real trajectories are difficult to obtain for sensitive apps and privacy-critical operations. At the same time, existing simulated environments are costly to scale up, and GUI world models still suffer from unstable generation, limited modality coverage, and inconsistent action-transition logic. To address these limitations, we propose AppDeltaWorld, a transition-grounded delta code world model that…

---

### [XEWorld: Can Action-Conditioned World Models Generalize to Unseen Robot Embodiments?](https://arxiv.org/abs/2608.05799v1)

- **arXiv**: `2608.05799v1`  |  **提交日期**: 2026-08-06
- **作者**: Yixiang Chen, Jiabing Yang, Yuan Xu, Qisen Ma, Keji He, Peiyan Li et al.

Action-conditioned world models are promising learned simulators for robotic manipulation, yet evaluating them exclusively on training robots fails to reveal whether they capture physical dynamics or merely memorize visual patterns. To answer whether a model can faithfully render a robot it has never seen, we introduce XEWorld, a controlled cross-embodiment testbed for world models that isolates embodiments by evaluating held-out robots within physically identical scenes. Our systematic analysis uncovers a shared architectural bottleneck: current models act primarily as 2D visual pattern…

---

### [When Agentic AI Meets Integrated Sensing and Communication](https://arxiv.org/abs/2608.05792v1)

- **arXiv**: `2608.05792v1`  |  **提交日期**: 2026-08-06
- **作者**: Kai Li, Conggai Li, Sarah Ali Siddiqui, Syed Sohail Ahmed, Xin Yuan, Shenghong Li et al.

Agentic artificial intelligence (AI) is transforming Integrated Sensing and Communication (ISAC) from a function-oriented physical-layer technology into a goal-driven, closed-loop intelligent system, a paradigm we term AISAC. Existing work on learning-based sensing, resource allocation, reconfigurable intelligent surfaces (RIS), edge intelligence, multi-agent coordination, and resilient networking has developed largely in isolation. This survey unifies the literature within a six-stage closed-loop framework comprising observation, contextualization, reasoning and prediction, planning and…

---

### [PhyLatent: Learning Dynamics-Relevant Representations for JEPA World Models](https://arxiv.org/abs/2608.05720v1)

- **arXiv**: `2608.05720v1`  |  **提交日期**: 2026-08-06
- **作者**: Xi Zeng, Haojie Ren, Ziying Song

We propose PhyLatent, a dynamics-relevant training objective for JointEmbedding Predictive Architecture (JEPA) world models. Our key observation is that preventing global latent collapse does not ensure that a representation preserves physical states and action consequences. We identify three failure modes in JEPA world models: physical invariance collapse, physical identifiability collapse, and counterfactual dynamics collapse. PhyLatent addresses them through three training pathways: physical invariance, physical identifiability, and counterfactual dynamics, implemented with physical state…

---

### [LAWM-3D: Learning 3D-Aware Latent Actions from Human Videos for Generalizable Robot World Models](https://arxiv.org/abs/2608.05706v1)

- **arXiv**: `2608.05706v1`  |  **提交日期**: 2026-08-06
- **作者**: Jiarui Yang, Jiale Zhange, Jiawei Li, Hang Guo, Wen Huang, Jinpeng Wang et al.

World models enable agents to perform forward rollout and planning without real-world interaction. However, their application in open-world embodied intelligence remains limited by the high cost of action annotations and the heterogeneity of action spaces across platforms. Recently, latent action models (LAMs) have alleviated this bottleneck by learning action representations directly from unlabeled human videos in a self-supervised manner. Nevertheless, most existing LAMs rely on single-view inputs and operate primarily in 2D pixel space, raising a fundamental question: can simply…

---

### [DreamGuard: Efficient Runtime Guardrail for LLM Agents via Risk-Aware World Model](https://arxiv.org/abs/2608.05695v1)

- **arXiv**: `2608.05695v1`  |  **提交日期**: 2026-08-06
- **作者**: Wenhao Lin, Chenyu Yu, Xingwei Lin, Sicong Cao, Xiang Chen, Lei Xue et al.

As large language model (LLM) agents increasingly invoke external tools and interact with real-world systems, unsafe actions may cause irreversible consequences on external states, user data, and downstream services. Recent runtime guardrails mitigate such risks by checking proposed actions before execution, but many remain reactive: they primarily assess the apparent safety of the current action, lacking an explicit model of how risk evolves across the trajectory. This limitation creates a critical blind spot for long-horizon risks, where individually benign-looking actions can gradually…

---

### [JoyAI-RA 0.5: Scaling Robot Manipulation Learning via Dual Action Alignment](https://arxiv.org/abs/2608.05674v1)

- **arXiv**: `2608.05674v1`  |  **提交日期**: 2026-08-06
- **作者**: JoyAI-RA Team

Robot data is scarce, so generalist policies need to learn from heterogeneous sources, including human egocentric video, simulation, and real robots, which differ in supervision and embodiment, with action labels missing or mutually incompatible. Human egocentric data scale best but sit farthest from robot data, and naive pooling causes negative transfer rather than knowledge sharing. We propose JoyAI-RA 0.5, a generalist Vision-Language-World-Action (VLWA) framework that couples physical world-dynamics priors with visual semantics and scales manipulation learning across such data via dual…

---

### [Uncertainty-Aware World Model for Aerial Image-Goal Navigation](https://arxiv.org/abs/2608.05597v1)

- **arXiv**: `2608.05597v1`  |  **提交日期**: 2026-08-06
- **作者**: Deyi Zhu, Haoyu Fan, Yinan Zhu, Weichen Zhang, Shilin Ma, Xinlei Chen et al.

Aerial image-goal navigation requires an unmanned aerial vehicle (UAV) to reach a target location specified by a goal image. Existing world-model-based methods rank candidate trajectories using predicted futures, but typically rely on only one or a few point predictions, which is inadequate for large-scale outdoor environments with substantial future-state uncertainty. To address this limitation, we propose the Uncertainty-Aware Navigation World Model (UA-NWM), an efficient latent world model for aerial image-goal navigation, which formulates trajectory scoring as conditional…

---

### [HERA: Historical Evidence Routing Adapter for Physical Prediction in Latent World Models](https://arxiv.org/abs/2608.05523v1)

- **arXiv**: `2608.05523v1`  |  **提交日期**: 2026-08-06
- **作者**:  Yuanruyi, Yue Cao, Haojia Gao, Guanqiu Guo,  Ziyuezhang,  Shangqin et al.

Predictive video models have emerged as promising world models by learning latent visual dynamics from large-scale video. Yet these models remain challenged by physical events under occlusion, where later predictions may depend on object evidence that is no longer available in the current view. Addressing this challenge requires historical evidence not only to be preserved but also to remain accessible when it becomes relevant to a subsequent prediction. Existing approaches mainly enlarge the temporal context, cache generic video features, or impose explicit object-centric states, thereby…

---

### [Quantum-Structured World Models (QSWMs) for Predictive Latent Dynamics](https://arxiv.org/abs/2608.05371v1)

- **arXiv**: `2608.05371v1`  |  **提交日期**: 2026-08-05
- **作者**: Hailong Jiang, Emran Hossain, Feng Yu, Jianfeng Zhu, Guilin Zhang, Wulan Guo

World models learn latent states that summarize interaction histories, evolve over time, and support prediction, simulation, or planning. Most existing world models represent these states using classical vectors, probability distributions, recurrent hidden states, or transformer activations. In this paper, we introduce Quantum-Structured World Models (QSWMs), a quantum-inspired framework for predictive world modeling with structured latent states, latent transition operators, and measurement-inspired decoding maps. We study whether mathematical structures inspired by quantum theory, such as…

---

## 📅 2026-08-06

### [HelloWorld: Enabling Socially Interactive Characters in Video World Models](https://arxiv.org/abs/2608.05070v1)

- **arXiv**: `2608.05070v1`  |  **提交日期**: 2026-08-05
- **作者**: Liangyang Ouyang, Ruicong Liu, Xuangeng Chu, Kaipeng Zhang, Yoichi Sato

Despite the remarkable recent progress of video world models, social interaction between users and the characters within these worlds remains unsupported. To fill this gap, we present HelloWorld, a video world model that enables social interaction with in-world characters. With a single button press, users can prompt the on-screen character to respond toward the camera, e.g., turning to the viewer, waving, nodding, or speaking a short greeting. To make these interactions natural, we propose a self-distillation pipeline that finetunes the video generation model on data synthesized by itself.…

---

### [DreamWAM: Beyond RGB Future Prediction for World Action Models](https://arxiv.org/abs/2608.04996v1)

- **arXiv**: `2608.04996v1`  |  **提交日期**: 2026-08-05
- **作者**: Shanglin Yuan, Weiheng Zhao, Xin Shi, Haoyi Jiang, Xianda Guo, Liu Liu et al.

World Action Models (WAMs) learn action-relevant representations by predicting how the observed world will evolve. Most existing WAMs define this future in RGB space, where task-relevant state transitions are entangled with nuisance variations in texture, illumination, background, and viewpoint. We argue that WAMs should explicitly predict action-relevant future state rather than relying on RGB prediction alone. We introduce DreamWAM, which reformulates future prediction as structured world modeling beyond RGB, representing future states through complementary views of appearance, motion,…

---

### [WorldCycle: Self-Verifiable Reinforcement Learning for Long-Horizon Video World Models](https://arxiv.org/abs/2608.04964v1)

- **arXiv**: `2608.04964v1`  |  **提交日期**: 2026-08-05
- **作者**: Bohai Gu, Yueyang Yuan, Taiyi Wu, Dazhao Du, Jian Liu, Xiaoyi Pang et al.

Interactive video world models are essential for long-horizon planning and exploration, yet they suffer from compounding errors. Post-training methods such as reinforcement learning (RL) can improve these models, but they hit a verification bottleneck: for arbitrary action sequences, no ground-truth future state exists to measure long-term drift. Our key insight is that reversible action cycles make this verification possible: a sequence composed with its inverse must analytically return to the initial state, yielding annotation-free supervision on long-horizon correctness. Building on this,…

---

### [Overcoming Statistical Bias in Action-Controllable World Models](https://arxiv.org/abs/2608.04653v1)

- **arXiv**: `2608.04653v1`  |  **提交日期**: 2026-08-05
- **作者**: Yuhong Shi, Zhenhao Chu, Jie Wei, Jun Hao, Jianyi Liu, Jingwen Fu

Action-conditioned world models aim to predict how visual environments evolve under an agent's actions. Yet future frames are often highly predictable from visual inertia and recurring motion patterns alone. This creates a shortcut: models can fit the data by exploiting statistical biases without making their visible dynamics meaningfully depend on the action. As a result, different actions may produce similar futures, while motion may persist even under zero action. The key question is how to reduce reliance on statistical shortcuts from dominating action-conditioned prediction. We argue…

---

### [muSync-GS: Physics-Synchronized Driving Video Synthesis for Weather and Geometric Road Hazards](https://arxiv.org/abs/2608.04412v1)

- **arXiv**: `2608.04412v1`  |  **提交日期**: 2026-08-05
- **作者**: Yang Chen, Yicheng Zhu, Tao Li, Zilin Bian

High-quality driving data are essential for autonomous-driving systems and generative world models. However, rare and safety-critical scenarios involving adverse weather, braking under low tire--road friction, and uneven road geometry are costly and risky to collect at scale. Existing video-generation and 3D Gaussian editing methods can modify weather appearance or road geometry, but typically do not couple these edits with tire--road interaction and vehicle dynamics. As a result, an edited video may retain its original trajectory even when the modified road condition should alter braking,…

---

### [Helping Music Co-Creation Agents 'Listen' Well: Hierarchical Self-Supervised World Models for Understanding and Generation](https://arxiv.org/abs/2608.04378v1)

- **arXiv**: `2608.04378v1`  |  **提交日期**: 2026-08-05
- **作者**: Scott H. Hawley

Collaborative music agents need internal representations rich enough to support both understanding and generation, yet flexible enough for a workflow where the human retains agency. We present a hierarchical self-supervised ``world model'' for symbolic music: a 2.55M-parameter Swin V2 encoder trained on MIDI piano-roll images with JEPA-style objectives (pitch- and time-shift equivariance, masked embedding prediction, and a distributional regularizer), using no labels and no music-theory vocabulary. Probing the frozen embeddings shows that the level at which a musical property becomes…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v3)

- **arXiv**: `2608.02150v3`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

## 📅 2026-08-05

### [Stochastic Multiple Shooting Trajectory Optimization via Sequential Local Policy Evaluation](https://arxiv.org/abs/2608.03978v1)

- **arXiv**: `2608.03978v1`  |  **提交日期**: 2026-08-04
- **作者**: Ashwin Gupta, Joseph Moore

Stochastic single shooting trajectory optimization methods such as Model Predictive Path Integral control (MPPI) have been widely adopted in robotics due to their ability to reason about probabilistic dynamics and provide solutions where model gradients are noisy, costly to evaluate, or unavailable. However, satisfaction of terminal constraints when shooting over long action sequences is often sample inefficient, requiring a large number of iterations for convergence. In this paper, we present a stochastic multiple shooting method that optimizes short control action sequences connected via…

---

### [Enactive Artificial Intelligence: A Decision-Centric Architecture for Complex Systems](https://arxiv.org/abs/2608.03413v1)

- **arXiv**: `2608.03413v1`  |  **提交日期**: 2026-08-04
- **作者**: Zuojun Max Shen, Yuan Qu, Pujun Zhang, Anbang Liu, Yunhao Liang

As artificial intelligence (AI) continues to evolve and mature, recent AI practices have moved beyond large language models (LLMs) and text or image generation tasks, increasingly integrating tools, agents, and harnesses to solve real business and industrial problems. However, the power of AI is not verified under these real-world complex systems for various reasons, considering reliability, feasibility, resilience, and responsibility requirements in real commercial and industrial operations. This study synthesizes adjacent research and introduces Enactive AI as a conceptual framework for…

---

### [UniNav: A Unified World-Action Diffusion Model for Visual Navigation](https://arxiv.org/abs/2608.03244v1)

- **arXiv**: `2608.03244v1`  |  **提交日期**: 2026-08-04
- **作者**: Changqing Zhou, Yueru Luo, Zeyu Jiang, Changhao Chen

Image-goal visual navigation is a fundamental capability for embodied agents. Existing navigation policies efficiently predict waypoint trajectories but lack visual foresight, while navigation world models can anticipate future observations but often require costly planning rollouts. We present UniNav, a unified world-action model that generates future visual observations and continuous waypoint trajectories through a single diffusion process. Given history frames and a goal image, UniNav jointly denoises visual and waypoint tokens within a single transformer, unifying future prediction and…

---

### [CrossScope: A Role-Asymmetric World Model for Joint Dual-Scope Surgical Video Prediction](https://arxiv.org/abs/2608.03211v1)

- **arXiv**: `2608.03211v1`  |  **提交日期**: 2026-08-04
- **作者**: Wanhao Liu, Jinsong Lin, Rulin Zhou, Chi Kit Ng, Wenbin Pan, Zhiqing Tang et al.

Visual world models typically learn future dynamics from a single observation stream, limiting their ability to model cooperative systems with multiple independently moving observers. We investigate this challenge in Mother--Child endoscopic retrograde cholangiopancreatography (ERCP), where two flexible scopes provide complementary yet role-dependent views without a calibrated stereo relationship. Unlike conventional multi-view fusion that assumes symmetric information exchange, we formulate \textbf{role-asymmetric dual-scope future prediction}, where cross-view evidence is selectively…

---

### [EmbodiedVAE: Disentangled Video VAE for Efficient and Controllable Embodied Manipulation](https://arxiv.org/abs/2608.02990v1)

- **arXiv**: `2608.02990v1`  |  **提交日期**: 2026-08-04
- **作者**: Jiayi Luo, Hanxin Zhu, Chen Gao, Jiankun Wang, Cong Wang, Tianyu He et al.

Latent diffusion models (LDMs) have recently significantly advanced embodied learning in constructing powerful embodied manipulation world models. However, despite the remarkable performance, existing LDMs predominantly rely on Variational Autoencoders (VAEs) optimized for natural scenes while failing to account for the unique characteristics of embodied manipulation scenarios, yielding latent representations that are neither compact nor controllable, thereby hindering efficient training of LDMs and precise robotic control. To solve this problem, we present EmbodiedVAE, a novel video VAE that…

---

### [RealWeather: Realistic and Scene-Faithful Weather Translation with Driving World Models](https://arxiv.org/abs/2608.02953v1)

- **arXiv**: `2608.02953v1`  |  **提交日期**: 2026-08-03
- **作者**: Yuwei Ning, Liangzhi Wang, Yi Xiao, Zhenhua Wu, Yun Pang, Mingkun Chan et al.

Realistic weather translation is valuable for developing and evaluating autonomous driving systems, yet collecting paired videos of the same scenes under different weather conditions at scale is impractical. Existing methods therefore rely on synthetic data, 3D weather editing, or geometry-conditioned generation, often compromising weather realism or scene fidelity. We propose RealWeather, a driving world model for both realistic and scene-faithful weather translation. Our key idea is to learn authentic weather dynamics directly from real-world videos. Specifically, RealWeather employs…

---

### [Quo Vadis, World Modeling?](https://arxiv.org/abs/2608.02713v1)

- **arXiv**: `2608.02713v1`  |  **提交日期**: 2026-08-03
- **作者**: Yu Yang, Xuemeng Yang, Licheng Wen, Lingdong Kong, Xiaobin Hu, Dongyue Lu et al.

Continually improving agents require dynamic interaction feedback beyond static supervision, yet direct real-environment interaction is costly, slow, unsafe, and hard to parallelize. World modeling offers a natural intermediate proxy that allows agents to query lower-cost, more controllable feedback before committing to real actions. Classical world models instantiate this proxy primarily through future physical-state prediction, a formulation useful yet narrow for agents that require actionable feedback beyond raw state transitions. In this work, we conceptualize Agent-Centric Interactive…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v2)

- **arXiv**: `2608.02150v2`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

### [MiniWorld: Democratizing the Training of Video World Models from Scratch](https://arxiv.org/abs/2608.01127v2)

- **arXiv**: `2608.01127v2`  |  **提交日期**: 2026-08-02
- **作者**: Yian Zhao, Ruochong Zheng, Hongcan Guo, Yu Yan, Jian Zhang, Jie Chen

Video world models predict future observations conditioned on historical observations and control signals, enabling long-horizon generation through autoregressive state transitions. Unlike conventional video generation models that primarily capture visual appearance and motion, video world models learn the underlying dynamics governing environment evolution under agent actions, providing a foundation for embodied AI and interactive simulation. Recent progress has largely relied on adapting pretrained video generation models through post-training or distillation. Although effective, these…

---

## 📅 2026-08-04

### [WorldExam: Benchmarking World Models from Apparent Appearance to Inherent Reactivity](https://arxiv.org/abs/2608.02603v1)

- **arXiv**: `2608.02603v1`  |  **提交日期**: 2026-08-03
- **作者**: Yuxue Yang, Shuyao Shang, Jiahe Wang, Zitong Zhou, Liang Tan, Junhan Zeng et al.

Controllable video generation models are increasingly being developed as world models. Accordingly, evaluating them in this role extends beyond the apparent appearance of generated videos to the inherent reactivity of the worlds they depict: the ability to infer from the scene state how the world should react and to generate plausible consequences not explicitly described in the input. Yet existing benchmarks mainly assess visual quality or explicit instruction fulfillment by checking whether requested actions and interaction outcomes are realized, leaving inherent reactivity underexamined.…

---

### [Analytic Planning under Uncertainty with Moment Closure](https://arxiv.org/abs/2608.02519v1)

- **arXiv**: `2608.02519v1`  |  **提交日期**: 2026-08-03
- **作者**: Shishir Sharma, Doina Precup

Effective model-based reinforcement learning in stochastic environments requires planning that accounts for predictive uncertainty. Propagating full state distributions analytically offers a principled way to do this, but has traditionally required restrictive policy or reward structures to remain tractable. Consequently, modern deep reinforcement learning has largely retreated to either stochastic sampling, which introduces significant target variance, or deterministic point estimates that ignore predictive covariance entirely. We investigate whether distribution-aware planning is possible…

---

### [DF$^3$: World Modeling via Decoder-Free Feature Forecasting in Autonomous Navigation](https://arxiv.org/abs/2608.02428v1)

- **arXiv**: `2608.02428v1`  |  **提交日期**: 2026-08-03
- **作者**: Jiaming Chen, Guoan Xu, Aoshen Huang, Haozhuo Zhang, Yang Li, Wei Pan

Forecasting future states from video sequences is a critical challenge for autonomous robotic systems and a fundamental objective of world modeling. Prior generative methods operating at the pixel level inevitably overemphasize task-irrelevant details, leading to prohibitive computational overhead. While latent-based approaches attempt to mitigate this by predicting features directly, the persistent reliance on heavy decoders for state-to-task mapping remains a computational bottleneck. In this work, we propose Decoder-Free Feature Forecasting (DF$^3$), a novel framework that models world…

---

### [Faster-WAM: Do World Action Models Need Deep Action Modules?](https://arxiv.org/abs/2608.02365v1)

- **arXiv**: `2608.02365v1`  |  **提交日期**: 2026-08-03
- **作者**: Liheng Ma, Rui Heng Yang, Zhanguang Zhang, Mateo Clemente, Ziwen Hu, Tongtong Cao et al.

World Action Models (WAMs) couple robot action prediction with video world models. Existing WAMs with shared-backbone and Mixture-of-Transformers designs generally tie the depth of the action module to that of the video backbone, resulting in substantial computational overhead and high inference latency. To address this limitation, we introduce Dock of Transformer (DoT), a video-centric design principle that treats a pretrained video Transformer as a representation hub and connects lightweight output-heads through docking interfaces. This enables flexible output-head design while providing…

---

### [PhyCheck: Fine-Grained Evidence-Grounded Dataset for Physical Law Understanding in Video-LLMs](https://arxiv.org/abs/2608.02150v1)

- **arXiv**: `2608.02150v1`  |  **提交日期**: 2026-08-03
- **作者**: Zhongjie Ba, Shengwang Xu, Peng Cheng, Jinyang Zou, Ting Yu, Zhibo Wang et al.

Embodied intelligence and world models require video understanding systems to go beyond recognizing objects and actions and develop an understanding of physical regularities. However, despite their strong performance on general video understanding tasks, current video-language models still struggle to reliably determine whether an observed event conforms to specific physical laws. Existing benchmarks primarily assess the physical quality of generated videos, providing limited support for systematically evaluating and improving the physical-law understanding of Video Large Language Models…

---

### [ProWorld: Progress-Aware Hyperbolic World Models for Long-Horizon Visual Goal Reaching](https://arxiv.org/abs/2608.01926v1)

- **arXiv**: `2608.01926v1`  |  **提交日期**: 2026-08-03
- **作者**: Zihan Liu, Yuzhe Zhuang, Yuanzu Li, Wanshuang Gou, Jiahong Liu, Min Zhou et al.

JEPA-style visual world models offer an effective paradigm for visual goal planning by predicting future latent representations. Existing methods typically learn local transition consistency through next-step representation prediction. However, in long-horizon tasks, accurate local prediction alone need not ensure sustained progress toward the goal. First, multi-step rollouts can remain locally plausible while drifting away from goal-relevant trajectories. Second, locally similar future states can correspond to substantially different long-term progress, making them difficult to distinguish…

---

### [WorldDynCache: Risk-Controlled Latent Dynamics Approximation for Diffusion World Model](https://arxiv.org/abs/2608.01845v1)

- **arXiv**: `2608.01845v1`  |  **提交日期**: 2026-08-03
- **作者**: Leyang Chen, Junyi Wu, Shaoqiu Zhang, Yulun Zhang

Diffusion world models generate high-quality futures, but re- peated transformer evaluations make inference prohibitively slow. Existing caches reuse intermediate features, selectively update tokens, or reuse and extrapolate denoising outputs ac- cording to local drift or short native-space histories. These criteria can miss both approximation-induced latent transition defects that accumulate across skipped steps and phase- or condition-dependent changes in the direction of latent evo- lution. We propose WorldDynCache, a risk-controlled latent dynamics approximation framework with two core…

---

### [SG-WAM: Self-Guided World Modeling in Geometry-Aware Policy Space](https://arxiv.org/abs/2608.01397v1)

- **arXiv**: `2608.01397v1`  |  **提交日期**: 2026-08-02
- **作者**: Ruiteng Zhao, Zhengshen Zhang, Yue Su, Wenshuo Wang, Jiahui Li, Zhiyuan Yang et al.

World Action Models (WAMs) couple action generation with prediction of future states. Their effectiveness depends on whether future dynamics are modeled in a space that is both aligned with action generation and sufficiently geometry-aware to capture where and how actions change the scene. Existing WAMs typically satisfy only part of this requirement, relying on either perceptually heavy observation-space targets or auxiliary latent spaces that are not jointly structured for action relevance and geometry. We propose SG-WAM, a self-guided framework that learns geometry-aware action-conditioned…

---

### [EndoWAM: A Grounded World-Action Model for Generalizable Endoscopic Navigation](https://arxiv.org/abs/2608.01221v1)

- **arXiv**: `2608.01221v1`  |  **提交日期**: 2026-08-02
- **作者**: Jinsong Lin, Zikang Pan, Wanhao Liu, Chi Kit Ng, Liangjing Shao, Zihang Yu et al.

Autonomous endoscopic navigation can reduce clinicians' operational burden, yet robust control remains challenging due to tissue deformation, transient occlusions, and rapidly changing viewpoints. Existing learning-based policies typically predict actions from current observations without explicitly modeling future dynamics, limiting their robustness and reliability in safety-critical settings. World Action Models (WAMs) offer a promising alternative by coupling predictive visual dynamics with action generation, but extending them to robotic endoscopy remains challenging due to limited…

---

### [Climate-Dyna Deep Hedging for XVAs: Model-Based Reinforcement Learning, Residual Climate HVA, and Hedge-Instrument Discovery](https://arxiv.org/abs/2608.01208v1)

- **arXiv**: `2608.01208v1`  |  **提交日期**: 2026-08-02
- **作者**: Xiaozhen Wang, Francois Buet-Golfouse

For a trading desk, residual climate hedging valuation adjustment (HVA) is the climate cost left after its inherited hedge and any admissible overlay have been taken into account; it therefore cannot be inferred from a stand-alone stress loss. We obtain this residual by comparing paired climate-on and baseline worlds and reoptimizing the overlay for each hedge universe, which also turns hedge-instrument discovery into a valuation problem: an instrument is useful to the extent that it lowers the optimized residual cost. The linear-Gaussian case has an exact finite-horizon Riccati solution;…

---

### [MiniWorld: Democratizing the Training of Video World Models from Scratch](https://arxiv.org/abs/2608.01127v1)

- **arXiv**: `2608.01127v1`  |  **提交日期**: 2026-08-02
- **作者**: Yian Zhao, Ruochong Zheng, Hongcan Guo, Yu Yan, Jian Zhang, Jie Chen

Video world models predict future observations conditioned on historical observations and control signals, enabling long-horizon generation through autoregressive state transitions. Unlike conventional video generation models that primarily capture visual appearance and motion, video world models learn the underlying dynamics governing environment evolution under agent actions, providing a foundation for embodied AI and interactive simulation. Recent progress has largely relied on adapting pretrained video generation models through post-training or distillation. Although effective, these…

---

### [FactorJEPA: Factorizing Monolithic Futures into Layout-Agent-Interaction Channels for Crowded and Chaotic Global South Urban Worlds](https://arxiv.org/abs/2608.01049v1)

- **arXiv**: `2608.01049v1`  |  **提交日期**: 2026-08-02
- **作者**: Kapil Wanaskar, Gaytri Jena, Aman Chadha, Vinija Jain, Vasu Sharma, Amitava Das

World models have attracted significant attention for their ability to capture and predict the structure and dynamics of the physical world. In this emerging landscape, Joint Embedding Predictive Architectures (JEPA) offer a particularly compelling direction. We study a largely unexplored regime: populous, crowded, and chaotic Global South urban environments, which we call DENSEWORLD. Unlike the lower-density, lane-structured settings that dominate existing evaluations, these scenes exhibit soft spatial boundaries, extreme agent heterogeneity, persistent occlusion, and rapid social…

---

### [Why Does the Future Branch? Identifiable Closure Tests for Stochastic Physical World Models](https://arxiv.org/abs/2608.00591v1)

- **arXiv**: `2608.00591v1`  |  **提交日期**: 2026-08-01
- **作者**: Yibin Dong

Stochastic world models are usually evaluated by the accuracy and calibration of their predicted futures. These criteria leave a decision-relevant ambiguity: the same conditional future distribution can arise because an observation aliases different physical states, or because the dynamics remain random after the declared full state is fixed. We prove that this attribution is not identifiable from ordinary transition data, even with an optimal probabilistic predictor. We introduce ClosurePairs, an interventional evaluation protocol that crosses compatible microstates with repeated exogenous…

---

## 📅 2026-08-03

### [DreamQAS: Learning a Decision-Useful World Model for VQE-Efficient Quantum Architecture Search](https://arxiv.org/abs/2607.29491v1)

- **arXiv**: `2607.29491v1`  |  **提交日期**: 2026-07-31
- **作者**: Jiayang Niu, Yan Wang, Jie Li, Ke Deng, Azadeh Alavi, Muhammad Usman et al.

Reinforcement-learning-based quantum architecture search (RL-QAS) repeatedly optimizes a variational quantum eigensolver (VQE) after extending a circuit, although circuit construction and action legality are deterministic and known. We introduce DreamQAS, a model-based RL framework that preserves these exact circuit dynamics and learns only the expensive post-VQE feedback. A recurrent randomized-prior ensemble predicts an oracle-free score relative to an empirical energy frontier and supports multi-step imagined policy learning over explicit legal circuits. Ranking-based activation,…

---

### [Analytical and Bootstrap Confidence Intervals of Double Machine Learning: Simulation studies and an application to rural-urban difference in obesity prevalence](https://arxiv.org/abs/2607.29456v1)

- **arXiv**: `2607.29456v1`  |  **提交日期**: 2026-07-31
- **作者**: Haozheng Xu, Siyuan Ma, Qingyan Xiang

Double Machine Learning (DML) is a popular approach for treatment effect estimation in various settings, which allows a wide range of flexible machine learning methods to be used for nuisance parameter estimation while preserving valid inference. In practice, however, applied researchers must choose among many machine learning algorithms for nuisance models, and the impact of this choice on the variance estimation of DML is not well characterized. We conduct a comprehensive simulation study to compare the coverage probability of DML confidence intervals across different machine learning…

---

### [AquaJEPA: Action-Conditioned Multimodal Predictive Representations for Underwater Robot Dynamics](https://arxiv.org/abs/2607.29393v1)

- **arXiv**: `2607.29393v1`  |  **提交日期**: 2026-07-31
- **作者**: Alan-Barsag Gazzaev, Alexey Gavrilov, Sergey Muravyov

Underwater robots combine complementary sensors whose reliability changes abruptly with water visibility, viewpoint, and vehicle motion. We introduce AquaJEPA, an action-conditioned joint-embedding predictive model that fuses an RGB camera, forward-looking sonar, and proprioception with explicit sensor validity. It predicts a future latent target conditioned on eight-thruster commands and supplies velocity and sonar-profile predictions to a shared receding-horizon planner. We study the method in Stonefish against reactive, state-only, ordinary multimodal, supervised dynamics, and recurrent…

---

### [Auto-JEPA: A Latent World Model of Continuous Intent for End-to-End Autonomous Driving](https://arxiv.org/abs/2607.29031v1)

- **arXiv**: `2607.29031v1`  |  **提交日期**: 2026-07-31
- **作者**: Jiwei Yang, Zhengxian Chen, Chaosheng Huang, Jun Li

Existing autonomous-driving world models typically perform dense prediction of future videos, occupancy states, BEV representations, or agent motion. We argue that planning need not reconstruct the complete future world, but only focus on scene features that affect future ego action. Based on this perspective, we propose Auto-JEPA, an action-oriented latent world model that learns continuous future driving intent through joint-embedding prediction. Given visual observations, egomotion history, and navigation commands, Auto-JEPA predicts an intent embedding aligned with the latent…

---

## 📅 2026-07-31

### [PhiZero: A World Model Built Around Physical Language](https://arxiv.org/abs/2607.28624v1)

- **arXiv**: `2607.28624v1`  |  **提交日期**: 2026-07-30
- **作者**: Shuyao Shang, Yuqi Wang, Ruopeng Gao, Xu Chen, Tieniu Tan, Lue Fan et al.

We introduce PhiZero, a physical world model built around physical language, a compact discrete representation of world-state transitions. Existing physical world models typically predict future videos directly in pixel space, leaving the underlying world dynamics implicit within high-dimensional visual predictors. Motivated by humans' ability to abstract predictive structure from visual experience and organize it in natural language for explicit reasoning, we learn physical language from in-the-wild videos through self-supervision and use it to explicitly reason about how the physical world…

---

### [AuricularWorld: Hierarchical Action-Guided World Modeling for Fine-Grained Auricular Structure Segmentation from CT Scans](https://arxiv.org/abs/2607.28487v1)

- **arXiv**: `2607.28487v1`  |  **提交日期**: 2026-07-30
- **作者**: Jingwen Yang, Senmao Wang, Luoyao Kang, Runmeng Cui, Keying Zhang, Yunjia Bao et al.

Fine-grained segmentation of auricular structures in CT is challenging because the ear occupies a small image region, cartilage boundaries are highly irregular, and interfaces between cartilage and surrounding soft tissues are often ambiguous. Clinical annotations may also include both composite structures containing cartilage and adjacent skin and their corresponding cartilage-only regions, producing nested and overlapping labels. We propose a world-model-based segmentation framework that enables iterative anatomical reasoning beyond conventional feed-forward prediction. Built on an…

---

### [QQWorld: Quantile-Quantile Matching for World Model Regularization](https://arxiv.org/abs/2607.28415v1)

- **arXiv**: `2607.28415v1`  |  **提交日期**: 2026-07-30
- **作者**: Zhoushun Yu, Xiaoyu Hu, Xiangyu Xu

Latent world models enable efficient planning by predicting future states in a compact representation space, but their performance depends critically on the quality of the learned latent distribution. LeWorldModel (LeWM) regularizes its latents toward an isotropic Gaussian using the Epps-Pulley (EP) objective. We show that the corrective gradients of EP rapidly vanish for isolated tail samples, leaving heavy-tailed deviations insufficiently controlled. To address this limitation, we propose QQWorld, which replaces EP with a quantile-quantile matching objective that directly aligns projected…

---

### [ShadowDancer: Teaching Video World Models Any Action by Learning Unified Dynamics Representations from a Video and Its Shadow](https://arxiv.org/abs/2607.28362v1)

- **arXiv**: `2607.28362v1`  |  **提交日期**: 2026-07-30
- **作者**: Jin Cao, Zian Meng, Kaipeng Zhang

We present ShadowDancer, a novel approach to any-action, frame-level control of interactive video world models. The obstacle is representational: existing interfaces either encode an action loosely, leaving how it unfolds for the model to improvise, or encode it exactly through structured signals that serve one family and are hard to acquire, so precise control across diverse dynamics remains impractical. Demonstration videos are the natural remedy, specifying any dynamics frame by frame; yet a video shows its dynamics only through one particular appearance, a single shadow of the underlying…

---

### [Tycho: Active Abstraction with Programmatic World Models for ARC-AGI-3](https://arxiv.org/abs/2607.28287v1)

- **arXiv**: `2607.28287v1`  |  **提交日期**: 2026-07-30
- **作者**: Jens Lehmann, Andrei Aioanei, Sahar Vahdati

ARC-AGI-3 turns abstraction into an interactive problem of skill acquisition. A player must infer an unfamiliar game's rules, hidden state, and goal while maintaining action efficiency because every move counts. We formalize these environments as parameterized rendered deterministic Moore machines and introduce Tycho, a coding-agent system that constructs and uses game-specific models during interaction. Tycho separates actionable observations from intermediate animation, level-completion, and game-over frames. From this structured history, an agent can model, test, plan with, repair, or…

---

### [Security of World-Model-Based Embodied AI: A Lifecycle of Threats, Defenses, and Evaluation](https://arxiv.org/abs/2607.28226v1)

- **arXiv**: `2607.28226v1`  |  **提交日期**: 2026-07-30
- **作者**: Fazhong Liu, Zhuoyan Chen, Haozhen Tan, Yan Meng, Guoxing Chen, Haojin Zhu

World models give embodied AI a predictive core: they compress observations into states, simulate action-conditioned futures, and enable planning beyond reactive control. This predictive layer, however, opens a new security boundary-compromise can propagate from data, sensors, prompts, or feedback into physical action. Rather than treating world models as an isolated component, this survey traces threats across their entire lifecycle-from data construction and representation learning, through state grounding and imagination, to trajectory evaluation, execution, and long-term adaptation via…

---

### [ODEWorld: A Continuous Predictive Architecture via Physical-Time Flow](https://arxiv.org/abs/2607.27924v1)

- **arXiv**: `2607.27924v1`  |  **提交日期**: 2026-07-30
- **作者**: Dongxiu Liu, Haoyi Niu, Peng Cheng, Yuan Gao, Xirui Kang, Sangli Teng et al.

In the physical world we inhabit, space and time are fundamentally continuous. However, existing machine learning paradigms for world modeling are largely confined to discrete-time prediction, thereby exhibiting significant inefficiency in capturing the dynamics of physical world. We introduce Physical-Time Flow (\textbf{PT-Flow}), a novel approach that learns a continuous latent velocity field operating in physical time. Crucially, the underlying dynamics of sequential data are parameterized by an ordinary differential equation (ODE) embedded in a well-structured representation space. Under…

---

### [Learning to Understand Body Language from Flight through Robust 3D Avatar Placing](https://arxiv.org/abs/2607.27865v1)

- **arXiv**: `2607.27865v1`  |  **提交日期**: 2026-07-30
- **作者**: Dragos Costea, Alina Marcu, Cristina Lazar, Marius Leordeanu

Perceiving human motion and intent at long range is a prerequisite for socially intelligent aerial robots, yet the data to learn it barely exists. We introduce Drones2BodyLanguage, a dataset grounding human motion in real UAV footage: avatars manifesting ten communicative intents are placed into unmodified 4K drone scenes with metrically correct position, scale and orientation, maintained over hundreds of frames of camera motion. Enabling it is a lightweight geometric world model of the local scene - semantically selected anchors lifted to 3D through streaming monocular depth - in which a…

---

### [World Action Planner: Generalizable Decision-Making with Action-Conditioned World Models](https://arxiv.org/abs/2607.27599v1)

- **arXiv**: `2607.27599v1`  |  **提交日期**: 2026-07-30
- **作者**: Xiangcheng Zhang, Yilun Du

Building generalizable agents for diverse applications remains a fundamental challenge. While imitation learning-based policies succeed in specific training environments, they often fail to generalize to novel scenes and tasks. In this work, we propose World Action Planner, a robot planning system that leverages the reasoning capabilities of Vision-Language Models (VLMs) and the physical grounding of a multi-task pose-image conditioned world model. Our system enables an agent to propose initial action plans and iteratively refine them via optimization and search, reasoning over imagined world…

---

### [Failure Detection for Surgical Robot Imitation Policies via Flow-Matching World Modeling](https://arxiv.org/abs/2607.27511v1)

- **arXiv**: `2607.27511v1`  |  **提交日期**: 2026-07-29
- **作者**: Zhefeng Huang, Yilin Cai, Ankit Patel, Mohammad Hajiha, Brendan Browne, Yue Chen

Imitation learning has shown increasing promise for autonomous robotic surgery, yet safe deployment remains challenging due to the safety-critical nature of surgical tasks and the complexity and variability of surgical environments. Failure detection is therefore an essential safeguard, but its development remains difficult due to the challenges of scarce failure data, highly variable manipulation dynamics, and the need to balance missed detections against disruptive false alarms. To address these challenges, we introduce FoMo-FD (Flow-Matching World Model for Failure Detection), a failure…

---

### [What Can Latent World Models Know? Physical Parameter Identifiability in Multimodal Predictive Representations](https://arxiv.org/abs/2607.27017v2)

- **arXiv**: `2607.27017v2`  |  **提交日期**: 2026-07-29
- **作者**: Kaizhen Tan, Xin Xu, Siru Tao, Hanzhe Hong, Yang Feng, Heqing Du

A central premise of latent world models is that predicting the future forces a representation to internalize the physics of its environment. Which physical quantities does a trained latent actually contain, and what decides this? We answer with controlled interventions in POKEWORLD, an interactive environment whose visually identical objects hide mass, drag, and contact stiffness. A certificate-gated protocol first certifies each parameter as recoverable from raw observations, then measures whether it enters the latent, so a null result can be attributed to the objective rather than to the…

---

## 📅 2026-07-30

### [Mitigating Compounding Error via Video Representation Regularization](https://arxiv.org/abs/2607.27036v1)

- **arXiv**: `2607.27036v1`  |  **提交日期**: 2026-07-29
- **作者**: Taiye Chen, Qi Zhang, Yisen Wang

Video diffusion-based world models enable long autoregressive video generation for robotics, autonomous driving and simulation tasks, yet sliding-window autoregressive inference suffers from severe error accumulation that degrades frame quality over time. Although this phenomenon has been widely observed, the underlying mechanism of compounding error and how to achieve stable long-horizon generation remain largely unresolved. In this paper, we investigate the internal representation dynamics of video world models and discover that compounding error is tightly coupled with dimensional collapse…

---

### [What Can Latent World Models Know? Physical Parameter Identifiability in Multimodal Predictive Representations](https://arxiv.org/abs/2607.27017v1)

- **arXiv**: `2607.27017v1`  |  **提交日期**: 2026-07-29
- **作者**: Kaizhen Tan, Xin Xu, Siru Tao, Hanzhe Hong, Yang Feng, Heqing Du

A central premise of latent world models is that predicting the future forces a representation to internalize the physics of its environment. Which physical quantities does a trained latent actually contain, and what decides this? We answer with controlled interventions in POKEWORLD, an interactive environment whose visually identical objects hide mass, drag, and contact stiffness. A certificate-gated protocol first certifies each parameter as recoverable from raw observations, then measures whether it enters the latent, so a null result can be attributed to the objective rather than to the…

---

### [Temporally Centered SIGReg Improves Multi-Task LeWorldModel Learning: From Analysis to Method](https://arxiv.org/abs/2607.26924v1)

- **arXiv**: `2607.26924v1`  |  **提交日期**: 2026-07-29
- **作者**: Chang Liu, Fei Suo, Yanzhou Jin, Yusuke Iwasawa, Yutaka Matsuo, Yaonan Zhu

Recent work on LeWorldModel (LeWM) has shown that the Sketched Isotropic Gaussian Regularizer (SIGReg) enables stable end-to-end world-model learning from pixels by regularizing the latent marginal distribution toward an isotropic Gaussian, thereby preventing representation collapse. While effective and elegant in single-task settings, this recipe does not extend reliably to multi-task training, leading to substantially worse downstream behavior-cloning performance. In this paper, we show that marginal Gaussianization compresses the separation between task-dependent latent clusters relative…

---

### [StatePlay: State-Aware Game World Models for Mechanics-Consistent Generation](https://arxiv.org/abs/2607.26754v1)

- **arXiv**: `2607.26754v1`  |  **提交日期**: 2026-07-29
- **作者**: Zijun Lin, Zeqing Wang, Cheston Tan, Bihan Wen, Yeying Jin

Recent game world models can generate visually realistic and interactive environments conditioned on player actions. However, games are not defined by pixels alone; they are governed by explicit mechanics, namely state-dependent rules that control health reduction, skill activation, and game termination. These mechanics depend on precise internal states, such as health points, skill meters, and timers, which are tightly coupled with visual observations and determine how gameplay evolves. Without modeling these state dynamics, existing game world models may generate visually plausible rollouts…

---

### [CalTwin: Towards Calibrated, Shift-Robust Medical World Models via Fisher-Information Regularisation](https://arxiv.org/abs/2607.26752v1)

- **arXiv**: `2607.26752v1`  |  **提交日期**: 2026-07-29
- **作者**: Behraj Khan, Shabir Ahmad, Syed Ahmad Chan Bukhari, Tahir Qasim Syed

Medical world models aim to learn a latent state of patient or organ physiology and a transition function that forecasts how that state evolves under interventions, supporting downstream tasks from imaging-based diagnosis to digital-twin treatment planning. Two failure modes threaten the reliability of such models in clinical deployment: (i)~\emph{covariate shift}, because training data are fragmented across hospitals, scanners, and time, so the feature distribution seen by the latent-dynamics predictor differs across fragments and from the distribution at deployment; and…

---

### [ActSWM: Action-Sensitive World Models for Long-Horizon Planning in Open-World Games](https://arxiv.org/abs/2607.26712v1)

- **arXiv**: `2607.26712v1`  |  **提交日期**: 2026-07-29
- **作者**: Zhenfeng Gan, ZiTong Zeng, Jiajun Cheng, Yeke Song, Yongyi Tang, Xueqian Wang

Latent world models support efficient model-predictive control by optimizing future control sequences in latent space and replanning in a receding-horizon manner. However, existing latent predictors often lack stable long-horizon rollout ability, and prediction accuracy alone does not ensure that rollouts remain responsive to the actions being planned. We identify Context Collapse, a failure mode in which autoregressive latent predictors maintain high similarity to future states while producing nearly indistinguishable futures under different action sequences. To address this issue, we…

---

### [ContactFlow: A video action conditioning that transfers across embodiments](https://arxiv.org/abs/2607.26579v1)

- **arXiv**: `2607.26579v1`  |  **提交日期**: 2026-07-29
- **作者**: Sami Azirar, Enrico Pallotta, Jan Nogga, Jürgen Gall, Sven Behnke, Hermann Blum

World models offer a promising route toward robot planning by enabling agents to imagine and verify the consequences of actions before execution. However, current video-based world models often struggle to capture the physical constraints that govern manipulation, particularly contact. Further, their action conditioning is often constrained to specific embodiments such as parallel grippers. We propose \emph{Contact Flow}, an embodiment-agnostic action representation that encodes manipulation through the trajectory of 3D contact points between an actor and a target object. By discarding…

---

### [Learning Implicit Causal World Models from Multi-Agent Demonstrations](https://arxiv.org/abs/2607.26336v1)

- **arXiv**: `2607.26336v1`  |  **提交日期**: 2026-07-28
- **作者**: Jasorsi Ghosh

In model-based reinforcement learning, world models exist as internal simulators, but their training often conflates statistical correlations with causal mechanisms. This problem is exacerbated in multi-agent systems where physical transitions are intertwined with strategic agent intents, causing world models to fail under distribution shift. We introduce Implicit Causal World Models to recover environmental dynamics from offline demonstrations without requiring pre-defined causal graphs. By incorporating policy variance, we render world models discoverable via the sequential backdoor…

---

### [Temporal-Distance JEPA: Plan-Aware Representation Learning for Latent World Model Predictive Control](https://arxiv.org/abs/2607.25337v2)

- **arXiv**: `2607.25337v2`  |  **提交日期**: 2026-07-28
- **作者**: Jiaxin Bai, Jiaxuan Xiong

Joint-Embedding Predictive Architectures (JEPAs) learn world models by predicting in representation space rather than reconstructing pixels, making them a natural backbone for latent model predictive control from offline demonstration logs. JEPA-style training optimizes short-horizon latent prediction, whereas planning requires a multi-step ranking of imagined futures by goal progress. Prior JEPA planners often inherit that ranking from embedding geometry, typically latent Euclidean distance, which arises as a byproduct of representation learning rather than as a progress cost mined from the…

---

## 📅 2026-07-29

### [INTACT: Isomorphic Intent-to-Action Learning for Search-Free World Models](https://arxiv.org/abs/2607.26056v1)

- **arXiv**: `2607.26056v1`  |  **提交日期**: 2026-07-28
- **作者**: Junhan Sun, Hao Zhao, Guofeng Zhang

Forward latent world models predict how actions change a scene, but recover actions for a desired change only through expensive test-time search. We introduce INTACT (INtent-To-ACTion), an end-to-end JEPA that turns action-labeled, reward-free trajectories into a deployable intent-to-action interface. Each transition supplies physical intent $z_{t+1}-z_t$, while a future goal supplies deployment intent $\operatorname{sg}(z_g)-z_t$. The architecture is isomorphic between the local and goal motion-intent backbone-input graphs through an identical four-slot grammar and shared parameters, and…

---

### [Reinformed Dreamer: An Asymmetric World Model Efficiently Trained through Latent Guidance](https://arxiv.org/abs/2607.26040v1)

- **arXiv**: `2607.26040v1`  |  **提交日期**: 2026-07-28
- **作者**: Gaspard Lambrechts, Adrien Bolland, Daniel Ebi, Damien Ernst

Much like humans benefit from guidance while learning, reinforcement learning algorithms may benefit from additional supervision beyond rewards. Leveraging additional information during training to learn better representations and behaviors has been the focus of asymmetric reinforcement learning. This learning paradigm has proven effective under partial observability when additional state information is available, but also under full observability when more refined state information is available. Focusing on model-based reinforcement learning, we study the effect of asymmetric learning on…

---

### [Wonder: Video World Model Done Better](https://arxiv.org/abs/2607.26037v1)

- **arXiv**: `2607.26037v1`  |  **提交日期**: 2026-07-28
- **作者**: Jiacong Xu, Hanwen Jiang, Zhixin Shu, Kalyan Sunkavalli, Vishal M. Patel, Yiqun Mei

We present Wonder, a general-purpose video world model for real-time, camera-controllable world exploration. Given an image or a conditional video, Wonder constructs a playable world where users can navigate interactively by moving the camera, discovering unseen regions, and revisiting previously observed areas in real time and over a long-term horizon. Achieving this capability requires a system-level co-design of control method, memory mechanism, and training strategy. We introduce a novel camera conditioning with a dense coordinate field whose renderings provide spatially aligned motion…

---

### [Temporal-Distance JEPA: Plan-Aware Representation Learning for Latent World Model Predictive Control](https://arxiv.org/abs/2607.25337v1)

- **arXiv**: `2607.25337v1`  |  **提交日期**: 2026-07-28
- **作者**: Jiaxin Bai, Jiaxuan Xiong

Joint-Embedding Predictive Architectures (JEPAs) learn world models by predicting in representation space rather than reconstructing pixels, making them a natural backbone for latent model predictive control from offline demonstration logs. JEPA-style training optimizes short-horizon latent prediction, whereas planning requires a multi-step ranking of imagined futures by goal progress. Prior JEPA planners often inherit that ranking from embedding geometry, typically latent Euclidean distance, which arises as a byproduct of representation learning rather than as a progress cost mined from the…

---

### [Medical world models in healthcare: foundations, applications, and challenges for trustworthy clinical translation](https://arxiv.org/abs/2607.25242v1)

- **arXiv**: `2607.25242v1`  |  **提交日期**: 2026-07-28
- **作者**: Zhaoyan Chen, Zhongxiu Cong, Zhuanfeng Jin, Wanshu Fan, Dongsheng Zhou, Qi Ai et al.

Medical world models offer a framework for extending medical artificial intelligence beyond static prediction by representing evolving patient states and modelling how they change over time and in response to clinical interventions. This Review defines the conceptual boundaries, technical foundations, application domains, and evidence requirements of the field through a structured narrative synthesis with reproducible evidence mapping.We screened 1,455 unique records and assembled a corpus of 98 sources, including 14 studies that met a strict empirical definition of a medical world model. The…

---

### [VisualPatchWorld: Code World Models as Latent Structured Representations for Planning](https://arxiv.org/abs/2607.25236v1)

- **arXiv**: `2607.25236v1`  |  **提交日期**: 2026-07-28
- **作者**: Jiaxin Bai, Jiaxuan Xiong

Different research lines use the term world model in different ways, yet they share a common aim: to capture how the world evolves under action in a form that supports perception, simulation, and planning. Two prominent realizations are neural predictors that learn dynamics in continuous vector spaces, and hand-built physics engines that expose explicit state and physical laws. Neural predictors scale from data but leave the form of the dynamics implicit; physics engines are inspectable and editable but difficult to construct at scale. We introduce VisualPatchWorld (VPW), which represents…

---

## 📅 2026-07-28

### [The Physics of Multi-Turn Long-Horizon Planning: From Pre-training to Post-training via Single- and Multi-Teacher On-Policy Agentic Distillation](https://arxiv.org/abs/2607.24720v1)

- **arXiv**: `2607.24720v1`  |  **提交日期**: 2026-07-27
- **作者**: Tianyi Men, Zhuoran Jin, Kang Liu, Jun Zhao

Multi-turn long-horizon planning is critical for foundation model agents, yet how to fundamentally improve it remains unclear. Existing models are trained on uncontrollable and opaque Internet data, making it difficult to identify how planning ability is acquired, shaped, and integrated. To address this challenge, we introduce a unified and controlled multi-turn environment that enables precise control. It allows systematically study long-horizon planning across three stages. (1) Planning ability acquisition during pre-training. We study data format, distribution, and quality. Explicit world…

---

### [Context Is King: How In-Context Specification Shapes the Geometry of Concepts](https://arxiv.org/abs/2607.24425v1)

- **arXiv**: `2607.24425v1`  |  **提交日期**: 2026-07-27
- **作者**: Elad David, Max Fomin

Large language models place structured concepts on geometrically faithful manifolds: weekdays lie on a circle, months on another, usually taken to be a fixed world-model the network stores and looks up. We show that context is king: the structure a model actually uses is set by the in-context specification. A declarative rule fixes not only which relations the geometry encodes but its topology type: the same tokens form a cycle or a branching tree on command, built even on arbitrary, meaning-free tokens with no prior to inherit, which a relabeled stored shape cannot do. When the specification…

---

### [FeelWorld: Visuo-Tactile World Model for Hierarchical Contact Prediction and Planning](https://arxiv.org/abs/2607.24267v1)

- **arXiv**: `2607.24267v1`  |  **提交日期**: 2026-07-27
- **作者**: Wenxuan Ma, Chaofan Zhang, Chao Xue, Yinghao Cai, Guocai Yao, Shaowei Cui et al.

Humans plan physical interactions by imagining the possible outcomes of candidate actions. However, existing visual world models primarily capture appearance dynamics while overlooking the tactile states that govern contact-rich interactions, potentially producing imagined futures that appear visually plausible but violate physical dynamics. We introduce FeelWorld, a hierarchical visuo-tactile world model that jointly predicts future visual latents and three tactile states. FeelWorld organizes these states hierarchically as contact state, a 3D tactile latent that encodes force-related…

---

### [Scaling GUI Agents with Visual State Transitions](https://arxiv.org/abs/2607.24112v1)

- **arXiv**: `2607.24112v1`  |  **提交日期**: 2026-07-27
- **作者**: Xiangyan Liu, Kaixin Li, Haonan Wang, Biao Wu, Meng Fang, Longxu Dou et al.

We introduce State Transition Pretraining (STP) as a new scaling axis for GUI agents. During the STP stage, we continually pretrain a unified multimodal model on visual state transitions by jointly optimizing inverse dynamics (predicting actions from state changes) and forward dynamics (predicting next states from current states and actions). This optimization equips the model with better action-grounded visual representations and an internal world model of GUI dynamics. When subsequently fine-tuned on trajectories with task instructions, our STP-trained models consistently outperform…

---

### [LeapBot-WA: World-Anchor Action Models via Predictive Latent Alignments](https://arxiv.org/abs/2607.23969v1)

- **arXiv**: `2607.23969v1`  |  **提交日期**: 2026-07-27
- **作者**: Pei Liu, Nan Zheng, Lang Zhang, Daojie Peng, Yanan Zhang, Feilong Kong et al.

World Action Models (WAMs) have emerged as a powerful paradigm for embodied intelligence, yet the prevailing reliance on pixel-level video generation creates a fundamental bottleneck. Forcing models to reconstruct task-irrelevant visual details dissipates representational capacity and renders policies vulnerable to visual distractors. In this paper, we propose LeapBot-WA, which establishes a novel Predictive-Latent paradigm for WAMs by operationalizing the Joint-Embedding Predictive Architecture (JEPA) as a World-Anchor. Departing from the traditional reliance on visual synthesis, LeapBot-WA…

---

### [WorldDiT: A Unified Diffusion Architecture for World and Action Modeling](https://arxiv.org/abs/2607.23909v1)

- **arXiv**: `2607.23909v1`  |  **提交日期**: 2026-07-27
- **作者**: Sen Wang, R. Gnana Praveen, Bidhan Roy, Marcos Villagra

Many recent robot policies pursue stronger control by using large pretrained vision-language models (VLMs) as the action backbone. We introduce WorldDiT, a unified diffusion transformer architecture that couples action generation with visual world modeling and achieves strong performance without a large pretrained VLM action backbone. During training, a single diffusion transformer generates continuous action chunks and predicts normalized RGB patch targets from future camera frames. Across four LIBERO simulation suites, WorldDiT lies on the reported Pareto frontier for total model parameters…

---

### [Embodied GPT-5.1: Evidence of a World Model?](https://arxiv.org/abs/2607.23899v1)

- **arXiv**: `2607.23899v1`  |  **提交日期**: 2026-07-27
- **作者**: Roberto Spinelli, Thiago C. Martins

This exploratory study examines whether a large multimodal language model, GPT-5.1, can serve as the high-level controller of a physical mobile robot despite having no prior embodiment, no training in simulated environments, and no exposure to sensorimotor experience. Using only low-resolution first-person images and a discrete action set, the model was tasked with navigation and object-directed behaviors such as locating and contacting a target toy. Across multiple trials, GPT-5.1 demonstrated emergent capabilities that suggest elements of spatial reasoning and physical understanding. These…

---

### [Action from Adjacent Set in Physical Space Outperforms the Best Prediction in World Models](https://arxiv.org/abs/2607.23602v1)

- **arXiv**: `2607.23602v1`  |  **提交日期**: 2026-07-26
- **作者**: Liangyu Li, Qingwen Liu, Mingqing Liu

Controllers based on sampling and latent world models assign a predicted terminal cost to each candidate action sequence, choose the minimum, execute its first action block, and replan. This rule can fail even when the terminal cost perfectly and accurately reflects the true task objective in the physical world. Residual prediction error can give an infeasible sequence an anomalously low cost, and a larger proposal pool gives such errors more chances to outrank feasible alternatives. We call this conditional failure proposal overgeneration. In Cube candidate execution audits, increasing the…

---

### [Real-Time Human-Centric World Modeling for Upper-Body Human-Object Interaction](https://arxiv.org/abs/2607.23517v1)

- **arXiv**: `2607.23517v1`  |  **提交日期**: 2026-07-26
- **作者**: Chaonan Ji, Jinwei Qi, Peng Zhang, Bang Zhang

We present a real-time human-centric world model for upper-body interactive generation, aiming to synthesize coherent local world dynamics centered on a person, where coordinated body, hand, and facial motions evolve jointly with controllable human-object discrete interaction. To this end, we adopt a continuous-discrete joint control scheme with two complementary components: a continuous human state and a discrete interaction state. For continuous human-state control, we introduce a unified implicit representation based on multi-scale motion encoding, in which motion latents from the upper…

---

### [Towards Dual-Brain Minimal Sufficient Representation for Vision-Language Navigation](https://arxiv.org/abs/2607.23181v1)

- **arXiv**: `2607.23181v1`  |  **提交日期**: 2026-07-25
- **作者**: Yihao Wu, Chenyi Xu, Liqi Yan, Chenhuan Cai, Geyong Min, Bin Lin et al.

Vision-and-Language Navigation in continuous environments (VLN-CE) requires an agent to ground language in egocentric observations and plan in unseen scenes. Although recent multimodal large models and world-model-based methods have improved navigation, they often preserve excessive task-irrelevant detail, weakening generalization and increasing computational burden. We propose BrainNav, a navigation framework grounded in the Principle of Minimal Sufficiency. BrainNav consists of three components: a Logical Anchor Model that implements instruction-aware selective perception to suppress…

---

### [False Prophets: On the Security of World Models in Agentic Systems](https://arxiv.org/abs/2607.23147v1)

- **arXiv**: `2607.23147v1`  |  **提交日期**: 2026-07-25
- **作者**: Erik Imgrund, Anna Wimbauer, Klim Kireev, Konrad Rieck

Large language models now power autonomous agents capable of complex, multi-step tasks in different environments. Accurate and reliable execution of these tasks requires the agent to predict the results of its actions. Recent research proposes to enhance predictive capabilities via specially trained environment simulators-world models. While world models can improve performance, they can also mislead agents into executing harmful actions, creating significant security and privacy risks. In this paper, we raise security concerns regarding the usage of world models in agentic systems. We…

---

### [mmSimPrior: Learning Simulation Priors for Data-Efficient Real-World Generalizable Radar-Based Human Motion Reconstruction](https://arxiv.org/abs/2607.22973v1)

- **arXiv**: `2607.22973v1`  |  **提交日期**: 2026-07-25
- **作者**: Cheng Guo, Qiming Cao, Shengkai Xu, Haoyu Xie, Kaixiang Su, Pu Wang et al.

Millimeter-wave (mmWave) radar offers privacy-preserving and lighting-robust sensing for human motion reconstruction, but learning models that generalize across real deployments require diverse paired radar-motion data that are costly to collect. Simulation provides scalable supervision, yet models trained on clean synthetic signals transfer poorly because of multipath, clutter, response statistics, and resolution degradation. We present mmSimPrior, a simulation-pretrained framework that factorizes transferable knowledge into signal, motion, and radar-to-motion mapping priors. A multi-modal…

---

## 📅 2026-07-27

### [Robot-Factored World Models via Robot Rendering](https://arxiv.org/abs/2607.22535v1)

- **arXiv**: `2607.22535v1`  |  **提交日期**: 2026-07-24
- **作者**: Byungjun Kim, Taeksoo Kim, Hyunsoo Cha, Hanbyul Joo

Action-conditioned video world models predict future observations from an initial observation and an action signal. In robotics, actions influence future observations through two distinct processes: they are first realized into robot motion by the robot body and controller, and the scene then responds through contact and object motion. Conditioning directly on action commands asks the world model to learn the realization process itself, while conditioning on logged future states leaks the interaction outcomes it is meant to predict. We propose robot-factored world models, which move two…

---

### [ViTacWorld: Scaling Visuo-Tactile World Models for Contact-Rich Robot Manipulation](https://arxiv.org/abs/2607.22530v1)

- **arXiv**: `2607.22530v1`  |  **提交日期**: 2026-07-24
- **作者**: Yunao Huang, Shiyu Sang, Haotao Lu, Suting Ni, Shijie Wu, Ziyang Guo et al.

Contact-rich robot manipulation requires physical interaction cues that are often invisible to cameras, making tactile sensing essential for robust control. However, scaling visuo-tactile robot learning remains difficult because real tactile interaction data are expensive to collect, hardware-dependent, and limited in task and scene diversity. We present ViTacWorld, an action-conditioned visuo-tactile world model for scalable contact-rich robot manipulation. ViTacWorld leverages public real tactile datasets and a constructed simulation environment to scale visuo-tactile-action data,…

---

### [On the Identifiability of Controlled World Models](https://arxiv.org/abs/2607.22430v1)

- **arXiv**: `2607.22430v1`  |  **提交日期**: 2026-07-24
- **作者**: Xiangteng Zhang, Yang Guan, Bo Zhang, Ya-Qin Zhang, Shengbo Eben Li

Learning world models that infer environment dynamics from high-dimensional observations and predict outcomes under candidate actions is central to planning and control. Joint-Embedding Predictive Architectures (JEPAs) provide a compelling framework for learning such models in representation space. Recent action-conditioned extensions perform promisingly in visual control and latent-space planning, but leave a fundamental question unresolved: when does controlled latent prediction identify both the underlying state and the controlled dynamics? This is challenging under nonlinear observations…

---

### [Action-Conditioned World Model for Goal Plane Probe Guidance in Robotic Ultrasound](https://arxiv.org/abs/2607.21918v1)

- **arXiv**: `2607.21918v1`  |  **提交日期**: 2026-07-24
- **作者**: Siqi Fan, Mingcong Chen, Ran Liu, Zixuan Yang, Xiaoyu Fu, Xiaoqing Gao et al.

We present an action-conditioned world model framework for goal plane probe guidance in robotic ultrasound, with a focus on neck ultrasound scanning. Autonomous ultrasound tasks often require large numbers of probe-motion trajectories for training, but collecting high-quality demonstrations is labor-intensive and explicit simulators are difficult to build because ultrasound appearance depends on contact, tissue deformation, and view-dependent acoustic artifacts. We address this problem with a two-stage model-based learning pipeline. First, a latent conditional diffusion world model predicts…

---

### [TRW: TRACE-RealWorld---An Auditable Consistency Contract for World Models as Materialized Views](https://arxiv.org/abs/2607.21910v1)

- **arXiv**: `2607.21910v1`  |  **提交日期**: 2026-07-24
- **作者**: Edward Y. Chang

TRACE-RealWorld addresses a core data-management problem: maintaining an actionable materialized view over a continuously changing physical world when reads of the base state are priced, delayed, heterogeneous, and fallible. Its data-management contributions are a commitment-level validity abstraction for materialized predictions; consequence-conditioned adaptive view maintenance; transaction-style, dependency-scoped compensation for commitments invalidated after authorization; and append-only provenance supporting exact replay. The work builds directly on materialized-view maintenance,…

---

## 📅 2026-07-24

### [Streaming Multi-Agent Autoregressive Diffusion Model with World State Registers](https://arxiv.org/abs/2607.21594v1)

- **arXiv**: `2607.21594v1`  |  **提交日期**: 2026-07-23
- **作者**: Sicheng Mo, Yuheng Li, Ziyang Leng, Krishna Kumar Singh, Bolei Zhou

Multi-agent interactive world models should not only generate consistent observations, but also maintain world states that persist across agents and evolve across views. Existing autoregressive video diffusion pipelines carry forward observation history as conditioning context, which makes shared state difficult to maintain in multi-agent and multi-view settings. We present WorldWeaver (W^2), a streaming multi-agent video diffusion model that augments rollout with cross-agent world state registers: learnable tokens that store shared world information, track individual agent status, and are…

---

### [PhysCoRe: Physics-Corrected Residual World Models for Material-Aware Deformable Dynamics](https://arxiv.org/abs/2607.20653v1)

- **arXiv**: `2607.20653v1`  |  **提交日期**: 2026-07-22
- **作者**: Haocheng Yin, Shuohan Tao, Yongsheng Chen, Lu Gan

Predicting how deformable objects evolve under robotic manipulation is a longstanding challenge. Existing approaches typically rely on per-object optimization to fit material parameters, which can be slow and cannot generalize, while end-to-end learned alternatives extrapolate poorly and often violate basic physical structure. We present PhysCoRe, a physics-corrected residual world model that couples a differentiable Material Point Method (MPM) simulator with two feed-forward neural networks. A material refinement module, Material from Motion (MfM), infers per-particle elasticity from visual…

---

## 📅 2026-07-23

### [Active Inference as a Convex Markov Decision Process](https://arxiv.org/abs/2607.20152v1)

- **arXiv**: `2607.20152v1`  |  **提交日期**: 2026-07-22
- **作者**: Nikola Milosevic, Nicolás Hinrichs, Nico Scherf

Active Inference (AIF) frames adaptive behavior as the minimization of expected free energy (EFE), combining epistemic and pragmatic objectives within a single variational principle. We frame AIF as policy optimization and show that, for closed-loop control policies, EFE minimization can be formulated as a convex Markov decision process (MDP). In this formulation, the pragmatic terms are linear in the predictive state marginals and therefore equivalent to reward maximization in a latent MDP, while the epistemic value introduces a nonlinear component that distinguishes EFE minimization from…

---

### [LAVIFT: Latent-Action-Guided Vision Fine-Tuning for Surgical Interaction Recognition](https://arxiv.org/abs/2607.19889v1)

- **arXiv**: `2607.19889v1`  |  **提交日期**: 2026-07-22
- **作者**: Jiajun Cheng, Subarna Tripathi, Sainan Liu, Xiaofan Yu, Shan Lin

Understanding instrument-tissue interactions is essential for context-aware surgical AI and autonomous robotic surgery. Pretrained vision-language models (VLMs) and vision encoders offer an alternative to conventional interaction classifiers by transferring broad visual and semantic knowledge. However, adapting them to fine-grained surgical interactions remains challenging: (1) freezing the vision encoder depends entirely on pretrained representations that may retain noise and provide weak spatial localization, while (2) full fine-tuning can improve global semantic alignment without ensuring…

---

### [KineBench: Benchmarking Embodied World Models via IDM-Free Kinematic Grounding](https://arxiv.org/abs/2607.19876v1)

- **arXiv**: `2607.19876v1`  |  **提交日期**: 2026-07-22
- **作者**: Zeyu Liu, Zhangzhe Zhu, Yang Zhang, Chenyou Fan, Chenjia Bai, Xuelong Li

Evaluating the physical consistency of embodied world models(EWMs) is a critical open challenge. While closed-loop evaluation via simulator rollouts offers a more faithful assessment of physical plausibility than open-loop alternatives, existing frameworks almost exclusively rely on Inverse Dynamics Models(IDMs) for action extraction. Due to the intricate mapping from 2D pixel space to 3D kinematic space, the learned IDMs can be brittle to data outside their training distribution, resulting in unreliable action extraction from the generated videos with novel objects and scenarios. This…

---

### [Dreamer-CPC: Message Learning with World Models for Decentralized Multi-agent Reinforcement Learning](https://arxiv.org/abs/2607.19809v1)

- **arXiv**: `2607.19809v1`  |  **提交日期**: 2026-07-22
- **作者**: Taisuke Takayama, Naoto Yoshida, Tadahiro Taniguchi

In multi-agent reinforcement learning (MARL), inter-agent communication is effective for improving performance under partial observability. Representation learning-based approaches enable decentralized agents to learn messages grounded in their own observations, but they rely only on current observations and cannot convey information accumulated over time. We propose Dreamer-CPC, a decentralized model-based MARL method that integrates message learning based on Collective Predictive Coding (CPC) into the world model of DreamerV3. Each agent independently maintains a world model and a message…

---

### [The World Model Remembers, the Actor Forgets: Dream Rehearsal for Continual Model-Based RL](https://arxiv.org/abs/2607.19749v1)

- **arXiv**: `2607.19749v1`  |  **提交日期**: 2026-07-22
- **作者**: Gurp Nijjer

Model-based reinforcement-learning agents of the DreamerV3 family forget catastrophically when trained on task sequences, even when an unbounded replay buffer preserves every earlier experience. We ask a question the continual-RL literature has assumed an answer to but never measured: which component forgets? Under never-clear replay, pre-registered component-level probes (n=3 seeds throughout) show that the world model retains essentially everything measurable about old tasks -- reward discrimination (retention ratio ~1.0), value estimates, and termination structure -- while the actor's…

---

### [Koopman Dreamer: Spectrally Constrained Latent Dynamics for Stable World-Model Imagination](https://arxiv.org/abs/2607.19719v1)

- **arXiv**: `2607.19719v1`  |  **提交日期**: 2026-07-22
- **作者**: Jiaqi Li, Xinglong Zhang, Haibin Xie, Yixing Lan, Wei Pan, Xin Xu

Latent world models improve sample efficiency in continuous control by optimizing policies over imagined latent trajectories, but common neural transitions offer limited direct control over modal persistence and error accumulation in long rollouts. We propose Koopman Dreamer, a Dreamer-style world model with a spectrally constrained deterministic latent dynamics core. Its Koopman-inspired backbone uses two-dimensional rotation--scaling blocks with bounded radii to represent damping, rotation, and near-periodic modes. Linear and low-rank bilinear action terms capture global and state-dependent…

---

### [Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents](https://arxiv.org/abs/2607.19190v2)

- **arXiv**: `2607.19190v2`  |  **提交日期**: 2026-07-21
- **作者**: Guanxiong Chen, Qianjun Xia, Jiawei Peng, Heng Zhang, Bole Ma, Justin Qian et al.

Real-to-sim conversion for robotic interaction with objects remains labor-intensive because it requires more than visual reconstruction: a streamlined real2sim process must recover scene geometries and object states, infer physical parameters, and assemble actors, objects, cameras, poses, and trajectories into a runnable physical simulation. Today this process still depends on manual tuning of visual foundation models, mesh cleanup, coordinate-frame alignment, and brittle workflow glue across visual perception tools and simulators. We introduce \textit{Agentic Real2Sim}, a framework for…

---

### [RoboInter1.5: A Holistic Intermediate Representation Suite for Embodied World Modeling and Robotic Manipulation](https://arxiv.org/abs/2607.18709v2)

- **arXiv**: `2607.18709v2`  |  **提交日期**: 2026-07-21
- **作者**: Ziqin Wang, Hao Li, Weijun Wang, Junhao Cai, Jia Zeng, Yilun Chen et al.

Existing robot datasets remain expensive to curate, embodiment-specific, and insufficiently annotated with the fine-grained structure required for generalizable reasoning, execution, or long-horizon environment dynamics simulation. Building on our prior work, RoboInter1.0, we present RoboInter1.5, an extended and holistic suite of intermediate representations for both robotic manipulation and embodied world modeling. RoboInter1.5 provides a unified resource of data, benchmarks, and models centered on dense manipulation-oriented intermediate representations. Specifically, RoboInter-Data…

---

## 📅 2026-07-22

### [Masked Visual Actions for Unified World Modeling](https://arxiv.org/abs/2607.19343v1)

- **arXiv**: `2607.19343v1`  |  **提交日期**: 2026-07-21
- **作者**: Hadi Alzayer, Wenlong Huang, Haonan Chen, Christopher Luey, Lvmin Zhang, Maneesh Agrawala et al.

Video models absorb rich priors over how the visual world moves, interacts, and responds to contact, making them promising substrates for robotic world modeling. The central challenge is how to communicate action to such models in a form aligned with the visual space in which they learned these interaction priors, yet still grounded in physical manipulation. We introduce Masked Visual Actions, a pixel-space control interface that expresses action as a partially revealed trajectory of an arbitrary entity in a video. Revealing robot motion makes the model act as a forward dynamics model that…

---

### [ABot-World-0: Infinite Interactive World Rollout on a Single Desktop GPU](https://arxiv.org/abs/2607.19191v1)

- **arXiv**: `2607.19191v1`  |  **提交日期**: 2026-07-21
- **作者**: Fan Jiang, Zhaoxu Sun, Mengchao Wang, Ziyu Zhu, Chiyu Wang, Yunpeng Zhang et al.

We present ABot-World-0, an action-conditioned video world model for real-time, long-horizon closed-loop interaction, supported by a multi-source data infrastructure spanning AAA games, simulation engines, and internet videos to learn controllable world dynamics. WorldExplorer performs agent-driven collection guided by training feedback, while a unified pipeline applies 14 deterministic quality checks, VLM-based assessment, and synchronized action and text annotation. We progressively distill a bidirectional action-conditioned teacher into a causal student through teacher forcing and ODE…

---

### [Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents](https://arxiv.org/abs/2607.19190v1)

- **arXiv**: `2607.19190v1`  |  **提交日期**: 2026-07-21
- **作者**: Guanxiong Chen, Qianjun Xia, Jiawei Peng, Heng Zhang, Bole Ma, Justin Qian et al.

Real-to-sim conversion for robotic interaction with objects remains labor-intensive because it requires more than visual reconstruction: a streamlined real2sim process must recover scene geometries and object states, infer physical parameters, and assemble actors, objects, cameras, poses, and trajectories into a runnable physical simulation. Today this process still depends on manual tuning of visual foundation models, mesh cleanup, coordinate-frame alignment, and brittle workflow glue across visual perception tools and simulators. We introduce \textit{Agentic Real2Sim}, a framework for…

---

### [FilmWorld: Agentic Novel-to-Film Generation through Dynamic Cinematic World Modeling](https://arxiv.org/abs/2607.19038v1)

- **arXiv**: `2607.19038v1`  |  **提交日期**: 2026-07-21
- **作者**: Jialong Zuo, Haotong Zuo, Shiwei Zhang, Xiang Wang, Chen Li, Nong Sang et al.

Translating novels into films poses a grand challenge for generative artificial intelligence, requiring conversion of abstract literary prose into long-form, multi-scene visual narratives. While current video generation models excel at short, single-scene clips within narrow temporal and spatial contexts, novel-to-film generation operates in a more complex regime, demanding long-duration content across diverse scenes with dynamically evolving entity states. To address this, we formalize novel-to-film generation as dynamic cinematic world modeling, decomposed into two phases: construction,…

---

### [NaviAIS: A Scenario-Level Vessel Trajectory Prediction Dataset withVectorized Lane Priors and the NaviLane Forecasting Framework](https://arxiv.org/abs/2607.18887v1)

- **arXiv**: `2607.18887v1`  |  **提交日期**: 2026-07-21
- **作者**: Yuan Gui, Hongchen Luo, Liqi Qu, Longyue Fu, Jiao Wang

Vessel trajectory prediction in complex maritime environments is essential for traffic management, collision warning, route planning, and autonomous navigation. Although AIS-based learning methods have progressed rapidly, existing datasets are often released as raw message streams or irregular time series, with inconsistent sampling rates, noisy observations, heterogeneous coordinate systems, and non-unified scenario protocols. Most public AIS resources also lack structured representations of navigational lanes, waterway geometry, and navigable-region constraints, limiting reproducible,…

---

### [DWM: Separating World Effects from Actions in Latent World Models](https://arxiv.org/abs/2607.18715v1)

- **arXiv**: `2607.18715v1`  |  **提交日期**: 2026-07-21
- **作者**: Yi-Ge Zhang, Tianqi Du, Qi Zhang, Yisen Wang

Latent world models underpin much of modern model-based control, yet current action-conditioned formulations supervise the next-latent transition with a single, undifferentiated target, forcing a monolithic learning signal to absorb every source of state change. In real world, however, transitions arise from two heterogeneous sources: an action-driven component induced by the agent, and an action-invariant world effect -- the change that would still occur under a null action, dictated by the environment's intrinsic dynamics (e.g., gravity-driven sliding, inertia, contact rebound, and…

---

### [RoboInter1.5: A Holistic Intermediate Representation Suite for Embodied World Modeling and Robotic Manipulation](https://arxiv.org/abs/2607.18709v1)

- **arXiv**: `2607.18709v1`  |  **提交日期**: 2026-07-21
- **作者**: Ziqin Wang, Hao Li, Weijun Wang, Junhao Cai, Jia Zeng, Yilun Chen et al.

Existing robot datasets remain expensive to curate, embodiment-specific, and insufficiently annotated with the fine-grained structure required for generalizable reasoning, execution, or long-horizon environment dynamics simulation. Building on our prior work, RoboInter1.0, we present RoboInter1.5, an extended and holistic suite of intermediate representations for both robotic manipulation and embodied world modeling. RoboInter1.5 provides a unified resource of data, benchmarks, and models centered on dense manipulation-oriented intermediate representations. Specifically, RoboInter-Data…

---

### [Generative World Renderer at the Speed of Play](https://arxiv.org/abs/2607.18703v1)

- **arXiv**: `2607.18703v1`  |  **提交日期**: 2026-07-21
- **作者**: Guixu Lin, Zheng-Hui Huang, Siqi Yang, Ming-Hsuan Yang, Kaipeng Zhang, Zhixiang Wang

Generative world renderer AlayaRenderer receives structured world states exported from physics engines and synthesizes RGB frames. Unlike models that generate frames from text/control-hints prompts, AlayaRenderer preserves scene structure without altering the underlying world dynamics. This demonstrates an alternative path toward interactive world modeling and user-controllable play. However, the original AlayaRenderer is too computationally expensive for real-time deployment. This technical report introduces AlayaRenderer-Flash, a real-time-oriented generative forward world renderer that…

---

### [Do AI-Native Biotechs Need Departments? Benchmarking Company World Models for AI-Driven Drug Development](https://arxiv.org/abs/2607.18696v1)

- **arXiv**: `2607.18696v1`  |  **提交日期**: 2026-07-21
- **作者**: Yinan Wang

AI-native biotechnology companies are often designed by copying human biotech org charts into agent roles. We argue for a different abstraction: a Company World Model, defined as a persistent asset-to-value state representation with transition models, explicit value functions, planning, and updating across scientific, regulatory, BD, commercial, financial, and execution constraints. We introduce a dry-lab benchmark for testing whether AI-agent organizations should mimic departments or operate around such a world model. The benchmark contains 45 retrospective public-information decision cases…

---

### [Planning as Emergent Behavior in Reinforcement Learning with Relational Hidden States](https://arxiv.org/abs/2607.18589v1)

- **arXiv**: `2607.18589v1`  |  **提交日期**: 2026-07-20
- **作者**: Armin Sommer

Reinforcement learning is conventionally divided into model-based and model-free methods. In this taxonomy, model-based methods perform lookahead planning over a learned world model, whereas model-free methods learn a reactive state-action mapping. Recent work, however, has shown that planning can emerge from model-free reinforcement learning alone. The conditions under which this behavior emerges from a pure reward-maximization objective have so far remained unclear. In this paper, we present evidence that, in the observed cases, the hidden-state structure of the neural architecture is the…

---

### [Integrity-Gated Eco-CACC: Epistemic Admissibility for Cooperative Driving at Signalized Intersections](https://arxiv.org/abs/2607.18565v1)

- **arXiv**: `2607.18565v1`  |  **提交日期**: 2026-07-20
- **作者**: Lyes Saad Saoud, Moussa Ayyash

Eco-Cooperative Adaptive Cruise Control (Eco-CACC) systems rely on accurate localization, signal timing, and interaction awareness to optimize energy consumption at signalized intersections. Existing approaches typically assume that the internal world model used for optimization remains valid, making them vulnerable when sensing outages or semantic inconsistencies invalidate planning premises. This letter proposes an Integrity-Gated Eco-CACC framework that explicitly monitors the consistency between internal vehicle beliefs and external sensing. A unified integrity metric is constructed by…

---

### [AlayaWorld: Interactive Long-Horizon World Modeling -- Full Technical Report](https://arxiv.org/abs/2607.18367v1)

- **arXiv**: `2607.18367v1`  |  **提交日期**: 2026-07-20
- **作者**:  AlayaWorld Team, Kaipeng Zhang, Chuanhao Li, Yifan Zhan, Yongtao Ge, Yuanyang Yin et al.

Unlike conventional video game development, which relies on labor-intensive pipelines for asset production, animation, physics, and programming, video world models generate interactive environments from user inputs instantly. It enable us to create customized, explorable, and continuously evolving virtual world from text, an image, or video. Realizing this vision requires four tightly coupled capabilities: interaction, persistent spatiotemporal consistency, stable long-horizon generation, and efficient response. We present AlayaWorld, an interactive long-horizon video world model that…

---

## 📅 2026-07-21

### [FlashRT: Agent Harness for Guiding Agents to Deploy Real-Time Multimodal Applications](https://arxiv.org/abs/2607.18171v1)

- **arXiv**: `2607.18171v1`  |  **提交日期**: 2026-07-20
- **作者**: Krish Agarwal, Zhuoming Chen, Yanyuan Qin, Zhenyu Gu, Atri Rudra, Beidi Chen

Real-time multimodal applications, including voice agents and interactive video generation, compose heterogeneous models into pipelines whose efficient deployment requires application-specific decisions about placement, streaming, and intra-model parallelism. Existing serving systems and auto-parallelism compilers commit to limited transformations and fixed workload assumptions, so achieving high performance on a new application requires hand-crafting an efficient implementation. We present FlashRT, an agent harness that guides coding agents to lift simple developer-written reference…

---

### [SAGE: Subgoal-Conditioned Action Generation for Latent World Model Planning](https://arxiv.org/abs/2607.17973v1)

- **arXiv**: `2607.17973v1`  |  **提交日期**: 2026-07-20
- **作者**: Letian Cheng, Qi Zhang, Yisen Wang

Latent world models have emerged as a powerful planning paradigm by learning action-conditioned predictive dynamics and using them as internal simulators to imagine and evaluate candidate action sequences. However, as the planning horizon grows, performance becomes increasingly constrained by proposal quality: a fixed candidate budget must search an exponentially larger action space, making it difficult to expose the world model to high-quality candidate futures for evaluation. In this paper, we introduce a prior-conditioned planner that replaces random proposal initialization with structured…

---

### [Mobile Network Control with a World Model](https://arxiv.org/abs/2607.17747v1)

- **arXiv**: `2607.17747v1`  |  **提交日期**: 2026-07-20
- **作者**: Maxime Bouton, Ioanna Mitsioni, Simon Lindståhl, Jaeseong Jeong

The increasing complexity of mobile networks necessitates intelligent and dynamic control strategies for efficient, energy-conserving management. We propose a world model-based approach for network control that enables adaptive configuration of crucial parameters. The world model is trained from historical data and predicts the impact of its actions on future network states. Our controller leverages the model's uncertainty estimate to robustly find optimal network configuration changes. Furthermore, the optimization objective can be changed dynamically without model retraining. We demonstrate…

---

### [Planning with Transformers: Chain of Computation and Structured Context Windows](https://arxiv.org/abs/2607.17710v1)

- **arXiv**: `2607.17710v1`  |  **提交日期**: 2026-07-20
- **作者**: Ehsan Futuhi, Nathan R. Sturtevant

Large Language Models (LLMs) have had a remarkable impact across many areas of machine learning. However, recent studies have shown that they struggle to reliably solve planning problems. At the same time, theoretical results have shown that transformers, the core architecture underlying modern LLMs, are Turing-complete. In this work, we investigate this apparent gap between the theoretical computational power of LLMs and their empirical planning performance. We propose Chain of Computation (COC), a computational architecture that places a transformer-based LM inside an iterative loop,…

---

### [Attention from Above: A Multimodal Model for Drone-Based Object Localization](https://arxiv.org/abs/2607.17669v1)

- **arXiv**: `2607.17669v1`  |  **提交日期**: 2026-07-20
- **作者**: Hyun-Ki Jung

Drone-based object detection technology has advanced rapidly, becoming increasingly sophisticated and efficient. Recently, research trends have expanded beyond the detection of predefined objects toward the identification of specified target objects. For example, desired targets can be specified through textual prompts, enabling accurate detection of objects of interest. To address this demand, this paper proposes an efficient multimodal-based object detection model aimed at improving small object detection performance. The proposed method is built upon the YOLO-World framework and replaces…

---

### [Reinforcement Learning: From Algorithms To Foundation Models](https://arxiv.org/abs/2607.17560v1)

- **arXiv**: `2607.17560v1`  |  **提交日期**: 2026-07-20
- **作者**: Zihan Ding

Reinforcement learning (RL) provides a framework for sequential decision making under explicit objectives. In its classical form, RL studies how an agent should act to maximise long-term reward in a dynamic environment. In richer settings, the problem extends beyond a single agent and fixed environment: intelligent behavior may require strategic interaction, adaptation to uncertainty, and reasoning over high-dimensional worlds. This thesis studies RL from two perspectives: algorithms in games and RL in the era of foundation models. The first part focuses on multi-agent RL in games. It…

---

### [Thinking in Video: Can Video Generators Really Reason About the Real World?](https://arxiv.org/abs/2607.17523v1)

- **arXiv**: `2607.17523v1`  |  **提交日期**: 2026-07-20
- **作者**: Yongheng Zhang, Guang Yang, Ruihan Hou, Qiguang Chen, Ziang Liu, Xiaolong Liu et al.

Recent advances in world models and video generation have given rise to an emerging reasoning paradigm that leverages video generative models to simulate, predict, and reason about real-world dynamics. We redefine this paradigm as Thinking in Video, where video is not merely an output artifact but a medium for constructing, extending, and verifying causal thought. However, this promise remains unverified: convincing rollouts may reflect memorized appearances rather than causal understanding, while existing metrics separate perceptual fidelity from semantic logic. To evaluate whether video…

---

### [GeoWorldAD: Geometry World Action Model for Autonomous Driving](https://arxiv.org/abs/2607.17521v1)

- **arXiv**: `2607.17521v1`  |  **提交日期**: 2026-07-20
- **作者**: Songyan Zhang, Jinyuan Tian, Hanbing Li, Daqi Liu, Hao Chen, Wenhui Huang et al.

Autonomous driving requires both safe and efficient planning decisions in dynamic 3D environments. Although recent Vision/Video-Action models learn policies directly from visual observations and scale well with advances in vision transformers and large-scale training data, they often lack explicit geometric grounding and future-aware spatial guidance, limiting their ability to balance collision avoidance and driving progress. In this work, we propose GeoWorldAD, a geometry world action model that grounds trajectory planning in ego-aligned 3D space and anticipates short-horizon scene evolution…

---

### [An Explicit World Model Based on Data-First Ontology: DaoQL Multimodal Storage Validation and Counterfactual Reasoning Evaluation](https://arxiv.org/abs/2607.17269v1)

- **arXiv**: `2607.17269v1`  |  **提交日期**: 2026-07-19
- **作者**: Zhanbo Li, Shifeng Wu, Xiangjin Meng, Wenjie Cai

Large language models encode world models implicitly in neural weights, which exposes four structural risks in high-precision domains such as medicine and finance: hallucination, frozen knowledge, poor explainability, and poor modifiability. This paper proposes data-first ontology: LLMs are treated as reasoning and language engines, while deterministic knowledge is moved into an explicit multimodal database, DaoQL. We formalize an explicit world model and show that, under rule independence, deterministic evaluation, and fixed conflict resolution, explicit models provide a sufficient condition…

---

### [Environment-free Synthetic Data Generation for API-Calling Agents](https://arxiv.org/abs/2607.16900v1)

- **arXiv**: `2607.16900v1`  |  **提交日期**: 2026-07-18
- **作者**: Seanie Lee, Sanjoy Chowdhury, Chao Jiang, Cheng-Yu Hsieh, Ting-Yao Hu, Alexander T Toshev et al.

Training API-calling large language model (LLM) agents demands massive amounts of high-quality trajectories. However, collecting such data at scale typically requires fully implemented environments with executable APIs and realistic, pre-populated backend databases, creating a major bottleneck for scalability. To overcome this, we propose an environment-free synthetic data generation approach that leverages LLMs as on-the-fly digital world models. Given only API specifications, our method generates trajectories mimicking interactions between an agent and a stateful environment. Specifically,…

---

### [PAVXploreRL: Physical-Action-Visual World Model Reinforcement Learning with Action Exploration](https://arxiv.org/abs/2607.16602v1)

- **arXiv**: `2607.16602v1`  |  **提交日期**: 2026-07-18
- **作者**: Han Wang, Zijun Wang, Shuoshuo Xue, Rui Cao, Fenjiao Cheng, Xiaodang Liang et al.

Action-conditioned world models are a key component of embodied AI, serving as scalable policy evaluators that reduce reliance on expensive real-world rollouts. To accurately capture diverse action-induced dynamics, such models should satisfy three key objectives-Physical Plausibility (P), Action Adherence (A), and Visual Fidelity (V), collectively referred to as PAV-while remaining robust to both in-distribution (ID) expert demonstrations and out-of-distribution (OOD) actions. However, existing methods primarily rely on ID action-video pairs and pixel-level reconstruction losses, which do…

---

### [Learning from World Feedback: Why Model Uncertainty Fails as a Risk Signal in Model-Based RL](https://arxiv.org/abs/2607.16591v1)

- **arXiv**: `2607.16591v1`  |  **提交日期**: 2026-07-18
- **作者**: Zhaohui Wang

The RLxF programme argues that learning signals should come from world feedback rather than from internal model proxies. We instantiate this position in safe model-based control and distil it into three concrete design principles. Empirically, across four world-model architectures spanning a 2x MSE range, MPC planning is statistically equivalent (TOST, n=200), and dynamics-based uncertainty penalties increase collision rates from 26% to 34%: the standard MBRL safety proxy is anti-correlated with safety in this regime. Replacing the model-internal proxy with three world-feedback signals (a…

---

## 📅 2026-07-20

### [MotionForesight: Re-purposing Video Models for Future 3D Scene-Flow Prediction](https://arxiv.org/abs/2607.16192v1)

- **arXiv**: `2607.16192v1`  |  **提交日期**: 2026-07-17
- **作者**: Homanga Bharadhwaj, Yash Jangir

Humans can infer how objects are likely to move from passive observation: a cup may be lifted, a drawer may slide, and a lid may rotate shut. Such predictions expose the physical consequences of interaction needed to act in the real world. We study how to learn this anticipation from ordinary monocular videos of human-object interaction. Given a short observed video context, MotionForesight predicts future 3D trajectories for points on the manipulated object. This casts interaction prediction as object-centered 3D motion forecasting without any assumptions on the object properties. Our key…

---

### [DSWorld: A Data Science World Model for Efficient Autonomous Agents](https://arxiv.org/abs/2607.15901v1)

- **arXiv**: `2607.15901v1`  |  **提交日期**: 2026-07-17
- **作者**: Zherui Yang, Fan Liu, Hao Liu

Despite strong capabilities in data understanding and decision-making, autonomous data science agents still heavily rely on trial-and-error workflows that involve expensive computation. This bottleneck motivates models that can anticipate the effects of data science operations before real execution. In this paper, we introduce the concept of Data Science World Model, which model the data science execution environment by predicting environment state transitions conditioned on current workflow states and candidate operations. We further propose DSWorld, a practical framework that combines…

---

### [Orbis 2: A Hierarchical World Model for Driving](https://arxiv.org/abs/2607.15898v1)

- **arXiv**: `2607.15898v1`  |  **提交日期**: 2026-07-17
- **作者**: Sudhanshu Mittal, Arian Mousakhan, Silvio Galesso, Karim Farid, Jonannes Dienert, Rajat Sahay et al.

Current world models operate at a single level of abstraction, with most prioritizing perceptual fidelity while lacking the spatial reasoning and semantic understanding required for real-world downstream tasks. We present a hierarchical driving world model that factorizes future prediction across two levels operating at distinct temporal and abstraction scales: a high-level predictor that forecasts coarse scene structure over extended temporal horizons, and a low-level generator that produces detailed predictions conditioned on the high-level output. This decomposition yields high perceptual…

---

### [ToolVerse: Unlocking Massive Environments and Long-Horizon Tasks for Agentic Reinforcement Learning](https://arxiv.org/abs/2607.15660v1)

- **arXiv**: `2607.15660v1`  |  **提交日期**: 2026-07-17
- **作者**: Shuaiyu Zhou, Fengpeng Yue, Zengjie Hu, Yuanzhe Shen, Chenyang Zhang, feng hong et al.

While LLM agents demonstrate strong reasoning abilities in compact and well-defined scenarios, they struggle to maintain robustness and effectiveness when faced with large-scale, diverse, and dynamic real-world environments that demand seamless tool integration. To address this gap, we introduce ToolVerse, a comprehensive framework that scales up agentic RL environments and enables agents to perform complex long-horizon reasoning in Tool-Integrated Reasoning (TIR) tasks. First, ToolVerse automatically builds the massive executable agent training environments from nearly 400 real-world Model…

---

### [AEGIS: Assay-Aware Protocol Validation and Runtime Monitoring for Open-Source Liquid Handling Robots](https://arxiv.org/abs/2607.15620v1)

- **arXiv**: `2607.15620v1`  |  **提交日期**: 2026-07-17
- **作者**: Priyanka V. Setty, Arvind Ramanathan, Ian Foster, Rick Stevens

Self-driving laboratories increasingly rely on low-cost liquid handlers such as the Opentrons OT-2, which ship without the pressure-based aspiration monitoring of Hamilton or Tecan systems and are typically run open-loop. Two failure modes go undetected: protocols that are syntactically valid but violate assay-specific invariants (e.g., tip reuse between a PCR template and a no-template control), and physical execution failures (partial dispense, air bubbles, missing tips) at runtime. We present AEGIS, a two-layer guardian for both. Layer 1 pairs a curated machine-readable assay rule database…

---

### [SeerGuard: A Safety Framework for Mobile GUI Agents via World Model Prediction](https://arxiv.org/abs/2607.15550v1)

- **arXiv**: `2607.15550v1`  |  **提交日期**: 2026-07-17
- **作者**: Xue Yu, Bo Yuan, Pengshuai Yang, Kailin Zhao, Hong Hu, Junlan Feng

Mobile graphical user interface (GUI) agents have demonstrated remarkable capabilities in automating complex tasks, yet they introduce critical safety risks where a single erroneous action can lead to irreversible consequences. Existing safety mechanisms are primarily reactive, lacking the ability to assess risks before execution. In this paper, we introduce SeerGuard, a consequence-aware safety framework designed to mitigate these risks through pre-execution instruction-level screening and action-level risk assessment. Specifically, the action-level assessment analyzes agent-proposed actions…

---

### [E3DGS: Unified Geometric-Photometric Equivariance for 3D Gaussian Splatting via Color-as-Geometry Embedding](https://arxiv.org/abs/2607.15536v1)

- **arXiv**: `2607.15536v1`  |  **提交日期**: 2026-07-17
- **作者**: Chankyo Kim, Maani Ghaffari

3D Gaussian Splatting (3DGS) captures scenes by coupling explicit geometry (position, covariance) with view-dependent photometry (Spherical Harmonics). However, building $\mathrm{SE}(3)$-equivariant architectures on these primitives presents a fundamental representation bottleneck. Color has been treated as a signal rather than a geometric entity, making it nontrivial to unify symmetry across geometry and appearance as the camera frame changes. While translations are handled by relative coordinates, rotations act heterogeneously across attributes: $μ\mapsto Rμ$, $Σ\mapsto RΣR^\top$, and…

---

## 📅 2026-07-17

### [Hierarchical Denoising For Multi-Step Visual Reasoning](https://arxiv.org/abs/2607.15278v1)

- **arXiv**: `2607.15278v1`  |  **提交日期**: 2026-07-16
- **作者**: Zezhong Qian, Xiaowei Chi, Chak-Wing Mak, Tianze Zhou, Ruibin Yuan, Yuhan Rui et al.

Video models are evolving into vision foundation models, yet they still lack human-like multi-step reasoning. Streaming autoregressive diffusion models are efficient but limited in reasoning, while bidirectional diffusion enables global revision with high inference costs due to dense frame-level denoising. Both paradigms struggle to achieve logical consistency and low-latency streaming for complex reasoning tasks. We propose HDR (Hierarchical Denoising for Visual Reasoning), a unified framework that integrates hierarchical latents into causal video generation for multi-step reasoning. HDR…

---

### [Concept-Guided Spatial Regularization for World Models in Atari Pong](https://arxiv.org/abs/2607.15142v1)

- **arXiv**: `2607.15142v1`  |  **提交日期**: 2026-07-16
- **作者**: Yukuan Lu, Zaishuo Xia, Weyl Lu, Yubei Chen

World models are usually evaluated as components of model-based reinforcement learning (MBRL) systems, while the world models themselves are rarely studied in isolation. We examine five representative visual world-model agents in Atari Pong: DreamerV3, DIAMOND, TWISTER, Simulus, and STORM. After reproducing their training pipelines and matching the reported agent performance, we freeze the learned world models and evaluate them with a closed-loop rollout diagnostic: a policy trained separately from the corresponding MBRL agent interacts with each frozen model, and the generated video…

---

### [DriftWorld: Fast World Modeling through Drifting](https://arxiv.org/abs/2607.15065v1)

- **arXiv**: `2607.15065v1`  |  **提交日期**: 2026-07-16
- **作者**: Susie Lu, Haonan Chen, Weirui Ye, Yilun Du

Predictive world models enable robots to plan by imagining the outcomes of their actions, but their value for control hinges on generating many rollouts quickly. This creates a bottleneck for diffusion-based world models: multistep sampling makes each rollout expensive, limiting large-scale action search at inference time. We introduce DriftWorld, an action-conditioned world model based on drifting generative models. Rather than denoising iteratively at inference, DriftWorld learns an action-conditioned drift during training, allowing it to generate future frames from the current observation…

---

### [GigaWorld-Policy-0.5: A Faster and Stronger WAM Empowered by AutoResearch](https://arxiv.org/abs/2607.13960v2)

- **arXiv**: `2607.13960v2`  |  **提交日期**: 2026-07-15
- **作者**:  GigaWorld Team, Angen Ye, Angyuan Ma, Boyuan Wang, Chaojun Ni, Fangzheng Ye et al.

World Action Models (WAMs) improve robot policy learning by jointly modeling actions and future visual observations, using future scene evolution as dense supervision for physically grounded action generation. However, a common design in existing WAMs is to explicitly generate future videos at inference time, incurring substantial computational overhead and hindering real-time closed-loop deployment. GigaWorld-Policy addresses this issue with an action-centered formulation, where future visual dynamics are used during training while action-only decoding is used at inference time. Building…

---

### [RxBrain: Embodied Cognition Foundation Model with Joint Language-Visual Reasoning and Imagination](https://arxiv.org/abs/2607.14187v1)

- **arXiv**: `2607.14187v1`  |  **提交日期**: 2026-07-15
- **作者**: Haotian Liang, Mingkang Chen, Yufei Huang, Yuchun Guo, Xiaomeng Zhu, Xiangli Shi et al.

Embodied cognition requires agents to connect high-level task reasoning with the physical states to be achieved. We introduce Hy-Embodied-RxBrain, an embodied cognition foundation model with joint language-visual reasoning and imagination. Unlike vision-language models that emphasize scene understanding and textual decision making, or generative world models that mainly predict future visual states, RxBrain represents embodied plans in a single planning sequence where language and visual imagination play complementary roles. Language provides the abstract structure of a plan, including task…

---

### [Open-AoE: An Open Egocentric Manipulation Dataset and Toolchain for Embodied Learning](https://arxiv.org/abs/2607.14183v1)

- **arXiv**: `2607.14183v1`  |  **提交日期**: 2026-07-15
- **作者**: Zishuo Li, Bowen Yang, Changtao Miao, Kai Zhu, Hao Chen, Qingze Guan et al.

Egocentric videos of human manipulation provide scalable supervision for embodied intelligence, yet existing resources rarely combine low-cost continuous capture, manipulation-level structured annotations, and reusable tools for robot learning. We present Open-AoE, an open, community-oriented egocentric manipulation dataset and toolchain spanning the full pipeline from smartphone capture to model training. Its first release contains approximately 2,000 hours of manipulation video collected in natural environments by 500+ contributors using 400+ smartphones. The dataset provides text…

---

### [RENEW: Towards Learning World Models and Repairing Model Exploitation from Preferences](https://arxiv.org/abs/2607.14180v1)

- **arXiv**: `2607.14180v1`  |  **提交日期**: 2026-07-15
- **作者**: Logan Mondal Bhamidipaty, Mykel Kochenderfer, Subramanian Ramamoorthy

World models are widely used in offline reinforcement learning (RL) to improve sample efficiency and generate experience beyond a fixed dataset. However, they are vulnerable to model exploitation where data coverage is thin. Prior work addresses this either by collecting more expert demonstrations, which is often expensive, unsafe, or unavailable, or by conservative algorithms that avoid uncertain regions, which limits generalization. We propose instead to repair exploitation directly using human preferences over imagined rollouts, leveraging the strong intuitive physics that allows humans to…

---

### [When a Verified World Model Still Loses: Play-Adequacy vs Prediction-Accuracy in LLM-Synthesized Code World Models](https://arxiv.org/abs/2607.14169v1)

- **arXiv**: `2607.14169v1`  |  **提交日期**: 2026-07-15
- **作者**: Javier Aguilar Martín

Large language models can synthesize a game's rules as executable code - a Code World Model (CWM) - which a classical planner then searches over. Such models are typically accepted when they reach high transition accuracy on sampled trajectories. We argue this is the wrong notion of adequacy for planning. We show four things. (1) An LLM-synthesized CWM can pass a sampling gate at 100% transition accuracy and be $\geq 98\%$ state-accurate on the planner's own search distribution, yet lose systematically at play, because the $<1\%$ it gets wrong is exactly the pivotal dynamics; the play cost of…

---

## 📅 2026-07-16

### [From Pixels to States: Rethinking Interactive World Models as Game Engines](https://arxiv.org/abs/2607.14076v1)

- **arXiv**: `2607.14076v1`  |  **提交日期**: 2026-07-15
- **作者**: Zhen Li, Zian Meng, Shuwei Shi, Mingliang Zhai, Jiaming Tan, Chuanhao Li et al.

Building interactive worlds that respond coherently to player actions has long been a shared goal of computer graphics, games, and artificial intelligence. Recent video generative models provide a data-driven route toward this goal by predicting future observations conditioned on user actions, and are increasingly regarded as potential next-generation game engines. Realizing a genuinely interactive game world, however, requires interaction outcomes that follow rules over evolving game conditions, consequences that persist over long horizons, and a generation loop that operates in real time.…

---

### [M$^\text{4}$World: A Multi-view Multimodal Driving World Model for Interactive Object Manipulation and Minute-long Streaming](https://arxiv.org/abs/2607.14005v1)

- **arXiv**: `2607.14005v1`  |  **提交日期**: 2026-07-15
- **作者**: Ke Cheng, Hanqiao Ye, Lei Shi, Yahui Liu, Yunhan Shen, Jingtao Dong et al.

Driving-world generation has emerged as a core capability for scalable autonomous-driving simulation, yet existing methods remain limited in object-level controllability and long-horizon stability. We present M$^\text{4}$World, a Multi-view and Multimodal generative driving world model that synthesizes future surround-view video streams and synchronized LiDAR scans while supporting interactive object Manipulation and stable Minute-long streaming. Fine-grained object manipulation is realized through a flexible conditioning interface that supports explicit control over both the spatial layout…

---

### [GigaWorld-Policy-0.5: A Faster and Stronger WAM Empowered by AutoResearch](https://arxiv.org/abs/2607.13960v1)

- **arXiv**: `2607.13960v1`  |  **提交日期**: 2026-07-15
- **作者**:  GigaWorld Team, Angen Ye, Angyuan Ma, Boyuan Wang, Chaojun Ni, Fangzheng Ye et al.

World Action Models (WAMs) improve robot policy learning by jointly modeling actions and future visual observations, using future scene evolution as dense supervision for physically grounded action generation. However, a common design in existing WAMs is to explicitly generate future videos at inference time, incurring substantial computational overhead and hindering real-time closed-loop deployment. GigaWorld-Policy addresses this issue with an action-centered formulation, where future visual dynamics are used during training while action-only decoding is used at inference time. Building…

---

### [Towards Spatial Supersensing in the Wild](https://arxiv.org/abs/2607.13681v1)

- **arXiv**: `2607.13681v1`  |  **提交日期**: 2026-07-15
- **作者**: Tianjun Gu, Tianyu Xin, Kuan Zhang, Bowen Yang, Kok-Chung Chua, Peize Li et al.

Humans can efficiently parse continuous sensory streams, from hours to years, scaffolding an internal world model that grounds spatial reasoning and prediction. To mimic this capacity, spatial supersensing challenges multimodal models to move beyond linguistic understanding toward true world modeling. However, their benchmark relies on synthetic long videos, formed by concatenating random short clips, and is mostly limited to household scenes, leaving real-world continuity and diversity underexplored. To address the gap, we introduce $\textbf{VSI-Super-Wild}$, a large-scale benchmark for…

---

### [From Surface Forecasting to Observability Forecasting: A Latent World Model for Cloud-Aware EO Monitoring](https://arxiv.org/abs/2607.13651v1)

- **arXiv**: `2607.13651v1`  |  **提交日期**: 2026-07-15
- **作者**: Mohanad Albughdadi

The bottleneck of Earth Observation processing chains is not the arrival of new imagery but whether the surface is actually visible when the image arrives. We study this as an observability forecasting problem on EarthNet2021. Given recent multispectral imagery and exogenous weather drivers, the goal is to predict whether the next acquisition will be usable and, if not, when a usable view is likely to return. To do this, we adapt LeWorldModel, a joint-embedding predictive architecture world model, to cloud-aware Earth Observation sequences. The final pipeline converts raw minicubes into…

---

### [The SIGReg Objective as Variational Free Energy: A Theoretical Active-Inference Account of JEPA World Models](https://arxiv.org/abs/2607.13612v1)

- **arXiv**: `2607.13612v1`  |  **提交日期**: 2026-07-15
- **作者**: Fabio Arnez, Alexandra Gomez-Villa

Joint-Embedding Predictive Architectures (JEPAs) are the dominant design for latent world models, yet they are usually justified by empirical performance rather than a normative principle. We show that the choice of anti-collapse regulariser determines whether a JEPA's training objective, a prediction loss plus a weighted embedding regulariser, is a valid Active Inference (AIF) variational free energy. We organise four non-contrastive regularisers (VICReg, LogDet, PairDist, and SIGReg) into an entropy-estimator hierarchy indexed by a prior-miscalibration gap, and show that the gap's sign,…

---

### [Grounded world models in biological organisms and future embodied AI](https://arxiv.org/abs/2607.13560v1)

- **arXiv**: `2607.13560v1`  |  **提交日期**: 2026-07-15
- **作者**: Giovanni Pezzulo, Davide Nuzzi, Marco D'Alessandro, Riccardo Proietti, Roberto Bottini, Paul Cisek

Recent advances in generative and embodied AI have been driven by large-scale predictive learning over multimodal data. However, the resulting systems remain largely based on passive training regimes where linguistic regularities create the scaffold onto which information from other modalities is attached. Conversely, neuroscience and cognitive science suggest that biological intelligence is organized in the opposite way, where grounded world models acquired through interaction with the environment provide the semantic scaffold to which language is attached. Here, we illustrate five examples…

---

### [Ego-Dynamics-Augmented World Model for Autonomous Driving with Zero-Shot Cross-Chassis Adaptation](https://arxiv.org/abs/2607.13410v1)

- **arXiv**: `2607.13410v1`  |  **提交日期**: 2026-07-15
- **作者**: Zhidong Wang, Jingsong Liang, Zirui Li, Zhan Chen, Han Yu, Chen Lv

World model (WM)-based reinforcement learning enables sample-efficient end-to-end autonomous driving learning by imagining long-horizon trajectories in latent space. However, most driving WMs operate on bird's-eye-view (BEV) representations that are inherently egocentric: the transition between consecutive frames entangles the ego vehicle's own motion with scene dynamics. As a result, the WM devotes significant capacity to recovering ego-motion from warped observations, at the cost of scene modeling fidelity and imagination accuracy. This work proposes DynaDreamer, a dynamics-augmented…

---

### [Learning Safe Agent Behaviour from Human Preferences and Justifications via World Models](https://arxiv.org/abs/2607.13172v1)

- **arXiv**: `2607.13172v1`  |  **提交日期**: 2026-07-14
- **作者**: Ilias Kazantzidis, Timothy J. Norman, Yali Du, Christopher T. Freeman

We address the problem of safely training an agent policy and deploying a good and safe policy, in settings where the environment dynamics are unknown and no suitable reward function is available. In the context of safety-critical environments, we consider traditional reinforcement learning impractical and resort to the resource of human input. We introduce DROPJ, a human-centred method for both safe training and deployment. We first learn a world model (a learned simulator) from a dataset of prior real-world trajectories. A human then plays the game in this learned simulator to extract…

---

### [From Observation to Insight: Mechanistic World Models and the Quest for Autonomous Discovery](https://arxiv.org/abs/2607.12474v2)

- **arXiv**: `2607.12474v2`  |  **提交日期**: 2026-07-14
- **作者**: Ingmar Posner, Anson Lei, Bernhard Schölkopf

Recent advances in foundation models have transformed AI for Science, enabling remarkably accurate predictive performance across domains ranging from protein folding to weather forecasting. Yet prediction alone does not constitute scientific discovery. Scientific understanding depends on uncovering the reusable explanatory mechanisms that generate observations, whereas contemporary machine learning remains fundamentally organised around predictive mappings rather than explanatory structure. In this paper, we argue that scientific discovery is fundamentally a problem of knowledge organisation.…

---

## 📅 2026-07-15

### [FlowWAM: Optical Flow as a Unified Action Representation for World Action Models](https://arxiv.org/abs/2607.13017v1)

- **arXiv**: `2607.13017v1`  |  **提交日期**: 2026-07-14
- **作者**: Yixiang Chen, Peiyan Li, Yuan Xu, Qisen Ma, Jiabing Yang, Kai Wang et al.

World Action Models (WAMs) are able to leverage pretrained video generators for both world modeling and action prediction. However, directly leveraging such video generators for control raises a new challenge: how to represent actions in a suitable form that aligns with pretrained video generators while carrying enough motion cues for accurate control. Existing numerical actions fail to satisfy the former, and prior visual action representations overlook the temporal motion structure across frames. We address this issue with FlowWAM, a dual-stream diffusion framework that adopts optical flow…

---

### [TRACE: An Operational Reasoning Schema for Auditable Agentic Commitments](https://arxiv.org/abs/2607.12480v1)

- **arXiv**: `2607.12480v1`  |  **提交日期**: 2026-07-14
- **作者**: Edward Y. Chang, Emily J. Chang

This paper defines TRACE (Typed Reasoning And Commitment Evidence): a typed, versioned schema for recording reasoning traces, a reference procedure for writing records against it, and one operating discipline, no durable state change without a record. The paper argues in three layers that reasoning is not in the language model: the autoregressive mechanism natively computes association; chain-of-thought and reinforcement learning inherit its limits; and the formal constructs of reasoning theory, from Socratic procedure to Pearl's ladder, are absent as machinery. The schema answers the absence…

---

### [From Observation to Insight: Mechanistic World Models and the Quest for Autonomous Discovery](https://arxiv.org/abs/2607.12474v1)

- **arXiv**: `2607.12474v1`  |  **提交日期**: 2026-07-14
- **作者**: Ingmar Posner, Anson Lei, Bernhard Schölkopf

Recent advances in foundation models have transformed AI for Science, enabling remarkably accurate predictive performance across domains ranging from protein folding to weather forecasting. Yet prediction alone does not constitute scientific discovery. Scientific understanding depends on uncovering the reusable explanatory mechanisms that generate observations, whereas contemporary machine learning remains fundamentally organised around predictive mappings rather than explanatory structure. In this paper, we argue that scientific discovery is fundamentally a problem of knowledge organisation.…

---

### [The GEST-Engine: From Event Graphs to Synthetic Video. A Full Technical Report](https://arxiv.org/abs/2607.12231v1)

- **arXiv**: `2607.12231v1`  |  **提交日期**: 2026-07-14
- **作者**: Nicolae Cudlenco, Mihai Masala, Marius Leordeanu

We present the GEST-Engine, a complete system that goes from natural-language text to fully-annotated multi-actor video. At its core is an explicit world model: rather than encoding state as a learned latent, the engine maintains a complete, inspectable representation of the world (which actors exist, where they are, what they are doing, which objects they hold, and how events relate in time and space), expressed as a formal Graph of Events in Space and Time (GEST) and realized deterministically inside the open world of a commercial game engine driven through an open-source multiplayer…

---

### [ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v2)

- **arXiv**: `2607.11673v2`  |  **提交日期**: 2026-07-13
- **作者**: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang et al.

We present ABot-3DWorld 0, a universal multimodal 3D world model that turns text, image, and video inputs into high-fidelity, explorable 3D worlds. At the heart of our framework is a unified Spatial Generative Primitive (SGP), a compact tuple of a high-quality panorama and a spatial point cloud that delivers an efficient description of any 3D space. Multimodal inputs are first lifted into this primitive; a 3D-consistent panoramic video generator then explores the primitive along a planned trajectory; finally, our panoramic video reconstruction engine converts the generated video into a clean,…

---

### [LIDAR-AD: A Decoder-Free Latent-Interaction Dreamer with Action-Residual Chains for Autonomous Driving](https://arxiv.org/abs/2607.11964v1)

- **arXiv**: `2607.11964v1`  |  **提交日期**: 2026-07-12
- **作者**: Yongzhi Liu, Yang Xiao, Zhong Cao, Zeng Kang, Sunan Zhang, Zhaozhi Dong et al.

Autonomous driving requires long-horizon closedloop decision making in dynamic traffic environments. Latent world models offer an effective framework for this problem by enabling imagination-based decision making in compact latent spaces. However, multi-source observations contain controlirrelevant redundancy, whereas reliable driving decisions rely on risk-relevant relations, future dynamics, and continuous action adjustments. This mismatch makes observation reconstruction and absolute action modeling suboptimal for learning decisionrelevant latent dynamics. We propose LIDAR-AD, a…

---

## 📅 2026-07-14

### [Cycle-World: Mitigating Error Accumulation in Long-term Video World Models via Reverse-Prediction Cycle Consistency](https://arxiv.org/abs/2607.11836v1)

- **arXiv**: `2607.11836v1`  |  **提交日期**: 2026-07-13
- **作者**: Zihan Su, Teng Hu, Jiangning Zhang, Ruiyan Wang, Ran Yi, Lizhuang Ma et al.

Autoregressive diffusion models have enabled high-quality video generation, yet their sequential nature inherently suffers from error accumulation. In long-horizon video synthesis, minor prediction deviations compound over time, inevitably leading to unconstrained generative drift, structural collapse, and severe visual degradation. To address this, we propose Cycle-World, a novel framework designed for stable and temporally consistent long-video generation. Our approach tackles error drift by enforcing strict temporal reversibility across both the training and inference phases.…

---

### [ABot-3DWorld 0: A Universal World Model to Explore Any 3D Space](https://arxiv.org/abs/2607.11673v1)

- **arXiv**: `2607.11673v1`  |  **提交日期**: 2026-07-13
- **作者**: Mingchao Sun, Luyang Tang, Yu Liu, Xu Yan, Zhan Li, Yunwei Zhang et al.

We present ABot-3DWorld 0, a universal multimodal 3D world model that turns text, image, and video inputs into high-fidelity, explorable 3D worlds. At the heart of our framework is a unified Spatial Generative Primitive (SGP), a compact tuple of a high-quality panorama and a spatial point cloud that delivers an efficient description of any 3D space. Multimodal inputs are first lifted into this primitive; a 3D-consistent panoramic video generator then explores the primitive along a planned trajectory; finally, our panoramic video reconstruction engine converts the generated video into a clean,…

---

### [Xiaomi-Robotics-U0: Unified Embodied Synthesis with World Foundation Model](https://arxiv.org/abs/2607.11643v1)

- **arXiv**: `2607.11643v1`  |  **提交日期**: 2026-07-13
- **作者**: Xinghang Li, Jun Guo, Qiwei Li, Long Qian, Hang Lai, Yueze Wang et al.

Recent foundation image and video generation models offer strong generalization and controllability, but their direct application to embodied scenarios is limited by requirements for multi-view consistency, geometric coherence, and robot embodiment constraints. Existing methods typically adapt foundation models with limited robot data, often sacrificing visual knowledge acquired during large-scale pre-training. We present Xiaomi-Robotics-U0, a 38-billion-parameter multimodal autoregressive model for unified embodied synthesis. It treats embodied generation as an extension of foundation image…

---

### [WALA Learning Executable Latent Actions from Action-Labeled Demonstrations and Action-Free Videos](https://arxiv.org/abs/2607.11397v1)

- **arXiv**: `2607.11397v1`  |  **提交日期**: 2026-07-13
- **作者**: Jiahao Liu, Zhongpu Xia, Shuai Tian, Huangrui Li, Yuhang Zheng, Ning Ma et al.

Generalizable robot policies typically rely on action-labeled robot demonstrations, which are expensive to collect and difficult to scale. In contrast, large-scale human and robot videos contain rich physical interactions but often lack executable robot action labels. We present WALA, a framework for learning executable latent actions from both action-labeled demonstrations and action-free videos. WALA first pretrains a semantic-geometric latent action model from videos by modeling the evolution between current observations and sparsely sampled future observations. Instead of reconstructing…

---

### [Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models](https://arxiv.org/abs/2607.10781v1)

- **arXiv**: `2607.10781v1`  |  **提交日期**: 2026-07-12
- **作者**: Xiyan Su, Frank Diermeyer, Markus Lienkamp

Driving world models built on large video-diffusion backbones generate realistic scenes but are hard to control: enforcing a traffic norm typically means retraining the backbone or conditioning it on hand-built layouts. We ask whether controllability requires training at all. Our experiment shows that a rectified-flow driving world model, which jointly generates future video and a planned ego trajectory, can have its planned trajectory steered entirely at sampling time by differentiable energy functions that encode driving norms, without knowledge-specific retraining of the diffusion…

---

### [World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning](https://arxiv.org/abs/2607.10630v1)

- **arXiv**: `2607.10630v1`  |  **提交日期**: 2026-07-12
- **作者**: Tong Nie, Yuewen Mei, Junlin He, Yihong Tang, Jian Sun, Wei Ma

Robust motion planning in dense traffic requires autonomous vehicles to interact in rare and safety-critical scenarios that are underrepresented in naturalistic driving data. Although adversarial training offers a feasible solution, existing methods often rely on external scenario generators, heuristic perturbations, or simulator-heavy rollouts, which makes them difficult to integrate with modern autoregressive planners. Here, we cast adversarially robust planner learning as a constrained min-max game and propose Adversarial World Modeling (AWM), a theoretically grounded multi-agent self-play…

---

### [Stateful Worlds, Stateless Elasticity: Exact-State Serving for Interactive World Models](https://arxiv.org/abs/2607.10389v1)

- **arXiv**: `2607.10389v1`  |  **提交日期**: 2026-07-11
- **作者**: Jin Li, Jiawei Chen

A persistent interactive world model keeps its running state resident on the GPU that serves it: a multi-gigabyte attention cache, almost all of it rewritten at every generation step. That state cannot be recomputed in interactive time or approximated without changing the world, so a live session pins its device. The pin is a scheduling problem. WorldMove moves a live session under one guarantee: the destination is bit-identical to the source, or nothing is installed. It relocates the cache in 18.8 ms same-node, 101x faster than save/load. It holds a checksum-verified 92.1-94.8 Gb/s on a 100…

---

### [A Control Theory of Predictability in Latent World Models](https://arxiv.org/abs/2607.10362v1)

- **arXiv**: `2607.10362v1`  |  **提交日期**: 2026-07-11
- **作者**: Hanzhe You, Yonggang Zhang, Maohao Ran, Zhiqin Yang, Zhenyuan Zhang, Wei Xue et al.

Latent world models are trained to predict future states in a learned representation and are then deployed inside a planner that selects actions by simulating them forward. Current practice adopts the prediction error, the single- or multi-step rollout loss on held-out data, as the training and model-selection objective, on the assumption that a lower prediction error yields better control. We show that this assumption is unreliable for a structural reason: a planner does not query the model on the training distribution but on the states that its candidate actions reach, which generally leave…

---

### [When Does Depth Survive Composition? Compute--Quality Regimes in Latent World Models](https://arxiv.org/abs/2607.10203v1)

- **arXiv**: `2607.10203v1`  |  **提交日期**: 2026-07-11
- **作者**: Achyuthan Sivasankar

Adaptive-compute world models -- early-exit or mixture-of-depths predictors that spend variable depth per step -- assume depth buys better predictions and can be routed adaptively. In autoregressive rollouts, the first assumption requires depth's per-step precision to survive composition. We test this with a pre-registered instrument, the shallow penalty $ρ=\mathrm{err}(\text{shallowest-exit rollout})/\mathrm{err}(\text{full-depth rollout})$, across nine DeepMind Control tasks under matched single-step ($K=1$) and multi-step ($K=4$) training, three seeds each. We find three regimes: on 6/9…

---

## 📅 2026-07-13

### [PanoWorld: Real-World Panoramic Generation](https://arxiv.org/abs/2607.09661v1)

- **arXiv**: `2607.09661v1`  |  **提交日期**: 2026-07-10
- **作者**: Haoyuan Li, Dizhe Zhang, Yuemei Zhou, Xiangkai Zhang, Haoran Feng, Xiaofan Lin et al.

In this work, we aim to address the challenge of long-range memory in panoramic world models by exploiting the rotation-equivariant property of omnidirectional representations, where rotation can be treated as an implicit geometric transformation.Building on this insight, we propose PanoWorld, which simplifies camera trajectories into translations via fixed headings for both current-action modeling and long-range memory through Dense Panoramic Ray-Conditioning (DPRC) and Geometry-aware Memory Augmentation (GMA).Then, a three-stage training pipeline is introduced to progressively optimize each…

---

### [Shortcut Trajectory Planning for Efficient Offline Reinforcement Learning](https://arxiv.org/abs/2607.09336v1)

- **arXiv**: `2607.09336v1`  |  **提交日期**: 2026-07-10
- **作者**: Guanquan Wang, Yoshimasa Tsuruoka

Diffusion-based trajectory planners have shown strong performance in offline reinforcement learning, but their iterative denoising process often incurs high inference cost. Consistency-based planners reduce the number of sampling steps, yet they typically rely on a two-stage teacher--student distillation pipeline that increases training cost and may introduce instability. We propose Shortcut Trajectory Planning (STP), an offline model-based reinforcement learning framework that incorporates shortcut models as efficient trajectory generators. STP trains a conditional shortcut trajectory model…

---

### [Causally Debiased Latent Action Model for Embodied Action Conditioned World Models](https://arxiv.org/abs/2607.09185v1)

- **arXiv**: `2607.09185v1`  |  **提交日期**: 2026-07-10
- **作者**: Yufan Wei, Kun Zhou, Lingjun Mao, Zijun Zhang, Ziming Xu, Ziqiao Xi et al.

Action-conditioned world models (ACWMs) aim to simulate future observations conditioned on embodied actions, offering a promising foundation for robot planning, policy evaluation, and data augmentation. However, learning controllable ACWMs requires large-scale action-labeled data, which remains costly to collect in the real world. Latent action models (LAMs) mitigate this bottleneck by inferring latent actions from unlabeled videos, but existing LAMs are typically trained with reconstruction-only objectives and therefore entangle action-relevant dynamics with action-irrelevant visual factors…

---

### [Toward Active Object Detection for UAVs in the Wild: A Large-Scale Dataset, Benchmark and Method](https://arxiv.org/abs/2607.09078v1)

- **arXiv**: `2607.09078v1`  |  **提交日期**: 2026-07-10
- **作者**: Tianpeng Liu, Xinhua Jiang, Li Liu, Qinmu Shen, Siwei Tang, Zhen Liu et al.

Object detection is a fundamental component in numerous Unmanned Aerial Vehicle (UAV) applications, yet it has long been plagued by hindrances like occlusion or target pixel scarcity. Active Object Detection (AOD) provides a novel paradigm to address these challenges via active vision, while UAV-based AOD research remains scarce due to the lack of high-quality datasets and benchmarks for algorithm development and evaluation. To fill this gap, this paper presents ATRNet-LUDO, the first large-scale real-world dataset for UAV-Ground Active Object Detection (UGAOD). It contains 121,000 multi-view…

---

## 📅 2026-07-10

### [Write-Protected Discrete Bottlenecks for Language-Grounded World Models: A Structural Limitation and Sufficient Fix](https://arxiv.org/abs/2607.08312v1)

- **arXiv**: `2607.08312v1`  |  **提交日期**: 2026-07-09
- **作者**: Jiayi Fang

How should language interface with a world model's discrete symbol system? The dominant paradigm -- end-to-end injection of LLM/VLM features into robot world models (RT-2, Octo, PaLM-E) -- implicitly assumes that language gradients can directly shape physical symbol representations. We ask whether this assumption is safe, find that it is not, and characterize the minimal architectural constraint that prevents the failure. Any language gradient entering a Gumbel-softmax-based discrete symbol bottleneck forces a structural trade-off: the vanilla estimator collapses to 2.2/64 symbols (4/5…

---

## 📅 2026-07-09

### [Infinite Worlds with Versatile Interactions](https://arxiv.org/abs/2607.07534v1)

- **arXiv**: `2607.07534v1`  |  **提交日期**: 2026-07-08
- **作者**: Zelin Gao, Qiuyu Wang, Jiapeng Zhu, Jingye Chen, Zichen Liu, Qingyan Bai et al.

We present LingBot-World 2.0 (also known as LingBot-World-Infinity), an advanced iteration of LingBot-World featuring four distinct upgrades. (1) Our model achieves an unbounded interaction horizon while maintaining consistent output quality, benefiting from a carefully crafted causal pretraining paradigm. (2) Through distilling a real-time variant from the base model, our system guarantees rapid response time, sufficient to drive 720p video streams at 60 fps. (3) Compared to the previous version, this update introduces highly diverse interactive elements, comprising a broader spectrum of…

---

### [Validate the Dream Before You Trust Its Verdict: Admissibility for World-Model Simulators](https://arxiv.org/abs/2607.07196v1)

- **arXiv**: `2607.07196v1`  |  **提交日期**: 2026-07-08
- **作者**: Christian Oefinger, Finn Rasmus Schäfer, Korbinian Moller, Mattia Piccinini, Johannes Betz

Across robotics, World Models (WMs) are increasingly used to evaluate action policies by simulating the consequences of actions in an imagined world, and returning a success or safety verdict. Yet a verdict is only as trustworthy as the WM that produced it, and the WM itself needs to be certified. In video-generation WMs, fidelity metrics such as Fréchet Video Distance (FVD) reward visual realism, but ignore whether the world responds correctly to the policy's actions, including those unseen in training. Classical simulation-based validation assumes a trusted simulator evaluating an untrusted…

---

### [Grounding Spatial Relations in a Compact World Model: Instruction Leakage and a Goal-Free Dynamics Fix](https://arxiv.org/abs/2607.06925v1)

- **arXiv**: `2607.06925v1`  |  **提交日期**: 2026-07-08
- **作者**: Yufeng Wang, Lu Wei, Haibin Ling

Compact world models that condition on a language goal promise to ground relations such as ``put the red block left of the blue block'' using a sparse set of explicit \emph{reference anchors}. We ask when such references actually ground a relation, and identify a trap: a goal-conditioned predictor reaches a striking $0.90$ relation-readout accuracy, yet this is \emph{instruction transcription}, not perception. Withholding the goal collapses it to chance ($0.90\!\to\!0.27$, three seeds) and a counterfactual instruction makes the predicted anchors follow the \emph{false} instruction $94.5\%$ of…

---

### [The Rank-One Corner: How Much Value Equivalence Does a Task Need from a World Model?](https://arxiv.org/abs/2607.06640v1)

- **arXiv**: `2607.06640v1`  |  **提交日期**: 2026-07-07
- **作者**: Donna Vakalis

A learned world model is usually judged by how faithfully it reconstructs its observations or predicts reward, as though quality were something the model simply has or lacks. But what a task actually needs from a model is narrower: the few predictive coordinates its queries depend on, which we call the closure. We show that how much of that closure a latent comes to represent is set not by the model's capacity or its observations but by the dimensionality of the objective it is trained against, and we measure this directly on a DreamerV3 stack in a controlled environment with known…

---

## 📅 2026-07-08

### [RynnWorld-4D: 4D Embodied World Models for Robotic Manipulation](https://arxiv.org/abs/2607.06559v1)

- **arXiv**: `2607.06559v1`  |  **提交日期**: 2026-07-07
- **作者**: Haoyu Zhao, Xingyue Zhao, Siteng Huang, Xin Li, Deli Zhao, Zhongyu Li

Robotic manipulation in the open world requires not only recognizing what a scene looks like, but also anticipating how its 3D structure moves under interaction. We argue that synchronized RGB, depth, and optical flow, namely RGB-DF, provide a physically grounded representation that captures the underlying 4D dynamics of a scene. Compared to 2D pixel videos, this multi-modal synergy aligns visual appearance with geometric structure and temporal motion, creating a representation space significantly closer to the low-level end-effector actions demanded by robotic systems, thereby narrowing the…

---

### [RynnWorld-Teleop: An Action-Conditioned World Model for Digital Teleoperation](https://arxiv.org/abs/2607.06558v1)

- **arXiv**: `2607.06558v1`  |  **提交日期**: 2026-07-07
- **作者**: Haoyu Zhao, Xingyue Zhao, Hangyu Li, Biao Gong, Kehan Li, Siteng Huang et al.

Scaling robot learning requires massive, diverse trajectory data, yet collection is currently bottlenecked by physical teleoperation, where every demonstration binds operator time to specific hardware and workspaces. We introduce digital teleoperation, a paradigm that decouples data collection from physical constraints by replacing the real robot with a generative world model. In this framework, an operator's hand-pose stream drives a robot-centric generative world model to synthesize high-fidelity egocentric videos from a single reference image. The recorded pose stream serves as an…

---

### [Hypothesis-driven Model Expansion under Uncertainty for Open-World Robot Planning](https://arxiv.org/abs/2607.06501v1)

- **arXiv**: `2607.06501v1`  |  **提交日期**: 2026-07-07
- **作者**: Anxing Xiao, Hanbo Zhang, Tianrun Hu, David Hsu

We consider an open-world planning setting in which service robots must operate in unknown environments with incomplete knowledge of objects and actions. Traditional closed-world approaches with pre-programmed knowledge bases fail when robots encounter unexpected situations and tasks, posing a fundamental challenge for autonomous knowledge expansion in human environments. In this work, we propose an open-world planning framework that enables robots to automatically generate, verify, and update hypotheses about their abstract world models. Our key insight is to explicitly maintain…

---

### [A Definition and Roadmap for World Models](https://arxiv.org/abs/2607.06401v1)

- **arXiv**: `2607.06401v1`  |  **提交日期**: 2026-07-07
- **作者**: Xinyuan Chen, Haoyu Guo, Shi Guo, Bingqi Jiang, Chunhua Shen, Xing Shen et al.

World models -- internal simulators that learn the structure and dynamics of an environment -- have become one of the most actively debated concepts in AI. From model-based reinforcement learning and video generation to embodied robotics and ultimately, physical AI, researchers across AI subfields are building systems that they call "world models", yet there is no consensus on what a world model fundamentally is, what it should predict, or how it should be built. This perspective article provides a scientific definition of world models, discussions of their key technical aspects, and a staged…

---

### [AlayaWorld: Long-Horizon and Playable Video World Generation](https://arxiv.org/abs/2607.06291v1)

- **arXiv**: `2607.06291v1`  |  **提交日期**: 2026-07-07
- **作者**:  AlayaWorld Team, Kaipeng Zhang, Chuanhao Li, Yifan Zhan, Yongtao Ge, Yuanyang Yin et al.

Game worlds have traditionally been built through labor-intensive production pipelines, making them costly to develop, difficult to customization, and expensive to modify after deployment. Recent advances in video world models offer a fundamentally different paradigm. Rather than explicitly authoring every component of a virtual environment, these models autoregressively synthesize future observations conditioned on the current world state and user interactions, enabling playable worlds to be generated online. Trained on both gameplay recordings and real-world videos, they can capture diverse…

---

### [MoWorld: A Flash World Model](https://arxiv.org/abs/2607.06216v1)

- **arXiv**: `2607.06216v1`  |  **提交日期**: 2026-07-07
- **作者**: Team Moxin, Deyi Ji, Tianrun Chen, Xin Zhang, Jiale Yang, Qi Zhu et al.

The future of World Models depends not only on scaling model capability, but also on scaling practicality and inference efficiency. High-frame-rate inference enables responsive perception, planning, and control in real-world autonomous systems. To this end, we present MoWorld, a cost-effective yet high-performance Flash World Model with an end-to-end framework spanning data generation, pre-training, distillation, and efficient inference, enabling up to 50 FPS real-time interaction with cinematic visual quality without the need of high-end GPUs. To enable large-scale real-world deployment,…

---

### [Imagined Rollouts are Kinematic, Not Dynamic: A Diagnosis of Long-Horizon World-Model Failure](https://arxiv.org/abs/2607.05966v1)

- **arXiv**: `2607.05966v1`  |  **提交日期**: 2026-07-07
- **作者**: Finn Rasmus Schäfer, Korbinian Moller, Yuan Gao, Christian Oefinger, Sebastian Schmidt, Johannes Betz

Long-horizon failure in world models is conventionally attributed to compounding error, a generic framing that does not distinguish what kind of error compounds. We propose a kinematic-vs-dynamic reframing: world models tend to imagine kinematically rather than dynamically. We operationalize this as the imagined Kinematic-Consistency Error, a per-step diagnostic that measures how far a rollout departs from a closed-form kinematic null, paired with a perturbation protocol that tests whether iKCE responds when physical conditions cross a regime boundary. We instantiate the diagnostic on a…

---

### [Narrative World Model: Narratology-Grounded Writer Memory for Long-Form Fiction](https://arxiv.org/abs/2607.05577v1)

- **arXiv**: `2607.05577v1`  |  **提交日期**: 2026-07-06
- **作者**: Mohammad Saifullah, Thomas Kornmaier, Taaha Kazi, Vasu Sharma, Aditya Sanjiv Kanade, Aanand Kumar Yadav

Long-form fiction writers need memory that answers multi-hop questions about evolving story state: who knows a secret and when they learned it, whether an event preceded the narration that revealed it, whether a setup paid off, and how a relationship shifted. General-purpose retrieval and agent-memory systems represent entities and facts but not the narratological structure these questions turn on, so they surface the wrong evidence or none at all. We introduce the Narrative World Model (NWM), a writer-memory system that pairs a narratology-grounded typed temporal-state graph with…

---

### [Multiplayer Interactive World Models with Representation Autoencoders](https://arxiv.org/abs/2607.05352v2)

- **arXiv**: `2607.05352v2`  |  **提交日期**: 2026-07-06
- **作者**: Anthony Hu, Václav Volhejn, Adrien Ramanana Rahary, Chris Mulder, Aditya Makkar, Alyx Liao et al.

We introduce the first multiplayer world model for highly dynamic environments governed by complex physical interactions. Whereas single-player world models treat the other agents as part of the environment, ours conditions on the action streams of multiple agents, learning to attribute changes in the scene to the correct player and to stay coherent under arbitrary combinations of their actions. We study this problem in the game of Rocket League, where players compete and cooperate under fast, tightly coupled dynamics. Trained on 10,000 hours of gameplay collected with publicly available…

---

## 📅 2026-07-07

### [Deform360: A Massive Multi-view Visuotactile Dataset for Deformable World Models](https://arxiv.org/abs/2607.05390v1)

- **arXiv**: `2607.05390v1`  |  **提交日期**: 2026-07-06
- **作者**: Hongyu Li, Wanjia Fu, Xiaoyan Cong, Zekun Li, Binghao Huang, Hanxiao Jiang et al.

Predicting object dynamics (i.e., world modeling) is a fundamental challenge for robotic manipulation, and modeling deformable objects presents a particularly difficult case due to their high-dimensional state spaces and complex material properties. While current world models approach this through two distinct paradigms: learning the dynamics over the 2D pixel space or more explicit 3D geometric space. A systematic understanding of their relative strengths and limitations remains elusive due to the lack of diverse, large-scale real-world data. To address this, we present Deform360, a…

---

### [Multiplayer Interactive World Models with Representation Autoencoders](https://arxiv.org/abs/2607.05352v1)

- **arXiv**: `2607.05352v1`  |  **提交日期**: 2026-07-06
- **作者**: Anthony Hu, Václav Volhejn, Adrien Ramanana Rahary, Chris Mulder, Aditya Makkar, Amélie Royer et al.

We introduce the first multiplayer world model for highly dynamic environments governed by complex physical interactions. Whereas single-player world models treat the other agents as part of the environment, ours conditions on the action streams of multiple agents, learning to attribute changes in the scene to the correct player and to stay coherent under arbitrary combinations of their actions. We study this problem in the game of Rocket League, where players compete and cooperate under fast, tightly coupled dynamics. Trained on 10,000 hours of gameplay collected with publicly available…

---

### [MoP-JEPA: Hard-Assigned Predictor Mixtures for Stochastic JEPA World Models](https://arxiv.org/abs/2607.05238v1)

- **arXiv**: `2607.05238v1`  |  **提交日期**: 2026-07-06
- **作者**: Zhi Song, Ximing Xing, Zhenchao Tang, hanbo Huang, Tianxu Lv, minghao Yang et al.

JEPA world models predict the next latent state with a single deterministic predictor trained by latent regression. We show that this fails structurally when the environment is stochastic: at a branching transition, the regression-optimal predictor outputs the conditional mean of the successor embeddings, a point between the true next states that corresponds to no state at all. We prove this collapse for deterministic and gated mixture-of-experts predictors, and prove that MoP-JEPA's hard-assigned predictors converge instead to a quantizer of the transition distribution: one head per…

---

### [InternVLA-A1.5: Unifying Understanding, Latent Foresight, and Action for Compositional Generalization](https://arxiv.org/abs/2607.04988v1)

- **arXiv**: `2607.04988v1`  |  **提交日期**: 2026-07-06
- **作者**: Haoxiang Ma, Junhao Cai, Xiaoxu Xu, Hao Li, Yuyin Yang, Yang Tian et al.

Unified models for robot manipulation aim to equip one policy with both the semantic priors of pretrained VLMs and the physical dynamics learned through future prediction. In practice, existing designs tend to erode the semantics of the pretrained backbone, suffer interference among heterogeneous objectives, and learn future prediction from scratch in pixel space, leaving the dynamics priors of pretrained video generators unexploited. We present InternVLA-A1.5, which builds the policy on a native VLM backbone that keeps training on VQA and subtask prediction, and attaches a lightweight…

---

### [Qantara: Bridge-Flow Training for Multi-Paradigm JEPA Control](https://arxiv.org/abs/2607.04978v1)

- **arXiv**: `2607.04978v1`  |  **提交日期**: 2026-07-06
- **作者**: Ruslan Rakhimov, George Bredis, Yuriy Maksyuta, Daniil Gavrilov

Joint-Embedding Predictive Architectures (JEPAs) underpin a growing family of latent world models for control from raw pixels, but every existing JEPA world model commits at training time to a single inference paradigm: either trajectory optimisation in a learned dynamics model, or direct behaviour cloning. A single checkpoint that serves both would defer this choice to inference, when deployment constraints (rollout cost, observation accessibility) determine which path wins. We present Qantara, an end-to-end JEPA whose joint training objective pairs a Brownian-bridge interpolant between…

---

### [KAM-WM: Kinematic Affordance Maps from Latent World Models for Robot Manipulation](https://arxiv.org/abs/2607.04652v1)

- **arXiv**: `2607.04652v1`  |  **提交日期**: 2026-07-06
- **作者**: Xinyu Shao, Keru Zhou, Guowei Huang, Yajun Gao, Tongtong Cao, Xiu Li

Learning manipulation from few demonstrations requires visual priors that capture not only where to interact, but also how the interaction should begin; static priors such as segmentation masks encode only the former. We present KAM-WM, a framework that extracts a coarse directional interaction cue from a frozen latent video world model without rollout or world-model fine-tuning. KAM-WM queries a Flow Matching image-to-video backbone once and interprets its single-step latent velocity as a Kinematic Affordance Map (KAM), which provides task-conditioned interaction regions and coarse motion…

---

### [CRISP: A Spatiotemporal Camera-Radar Backbone for Driving via Forecasting-Based World-Model Pretraining](https://arxiv.org/abs/2607.04541v1)

- **arXiv**: `2607.04541v1`  |  **提交日期**: 2026-07-05
- **作者**: Jingyu Song, Yi Liu, Katherine A. Skinner

Camera-radar (CR) fusion is a practical sensing configuration for autonomous driving, but existing models are typically trained with task-specific supervision, limiting reusable representation learning. We present CRISP, a spatiotemporal CR backbone pretrained through forecasting-based representation learning. Given historical multi-view images and radar sweeps, CRISP learns a unified bird's-eye-view (BEV) representation by predicting future LiDAR point clouds. LiDAR is used only as privileged supervision during pretraining; the deployed model requires only camera and radar. To make…

---

### [Geographic Diversity Beats Data Volume for Cross-Domain Generalization in Zero-Label JEPA Driving World Models](https://arxiv.org/abs/2607.04500v1)

- **arXiv**: `2607.04500v1`  |  **提交日期**: 2026-07-05
- **作者**: Santosh Jaiswal

Self-supervised latent world models can assign a surprise score to driving scenarios without any human labels. A natural follow-up question is whether such a model, trained on driving data from one geographic region, can generalize its notion of complexity to unseen cities and sensor configurations. We study this question through a controlled transfer experiment: we train JEPA-based world models on nuPlan data (Pittsburgh, Boston, Singapore) and evaluate zero-shot on held-out Argoverse 2 validation scenarios from Miami and Austin. We find that models trained on geographically diverse data…

---

### [Operator-on-F complements value-equivalence: a planning-time diagnostic for latent world models](https://arxiv.org/abs/2607.04464v1)

- **arXiv**: `2607.04464v1`  |  **提交日期**: 2026-07-05
- **作者**: Donna Vakalis

World-model evaluation for model-based reinforcement learning typically asks whether the learned model predicts reward and value well, which can leave planning-relevant errors in the model's latent rollouts unmeasured. We introduce a complementary diagnostic, operator-on-F, that compares a model's k-step latent pushforward to the environment's on an observable subset F, using the model's own predictor. On a TD-MPC2 size sweep over cheetah-run, reward-prediction error stays within [0.028, 0.091] for every model size - only about 3x variation - so an unnormalized reward-fit check has narrow…

---

### [Learning Task-Sufficient World Models by Synergizing Agentic Exploration and Structured Modeling](https://arxiv.org/abs/2607.04409v1)

- **arXiv**: `2607.04409v1`  |  **提交日期**: 2026-07-05
- **作者**: Fan Feng, Yujia Zheng, Minghao Fu, Yongqiang Chen, Guangyi Chen, Kevin Murphy et al.

Learning and planning in imagination using world models provides an effective paradigm for training agents for decision-making. However, existing approaches often rely on high-dimensional latent spaces or generic visual embeddings that retain many factors irrelevant to control, limiting efficiency and generalization across tasks. To this end, we study how agents can learn world models with representations that are task-specific, minimal, and sufficient for decision-making. We achieve this via a closed-loop synergy between the agent and the world model, in which structured world-model learning…

---

### [Last-Meter Precision Navigation for UAVs: A Diffusion-Refined Aerial Visual Servoing Approach](https://arxiv.org/abs/2607.04352v1)

- **arXiv**: `2607.04352v1`  |  **提交日期**: 2026-07-05
- **作者**: Yaxuan Li, Jiarui Zeng, Shaofei Huang, Zhedong Zheng

In this work, we study the last-meter precision navigation for UAVs, e.g., autonomously reaching a target within the final 10 meters using monocular vision. This task is challenging due to scale ambiguity, rotation discontinuities, and the need for fine-grained spatial reasoning. Existing methods often fail under large viewpoint changes or lack generalization to unseen environments. To this end, we propose DreamNav, a coarse-to-fine diffusion-refined aerial visual servoing framework. In the first coarse-estimation stage, a robust regression policy employs a trigonometric parameterization to…

---

### [DynaVieW: Schema-Guided World Modeling for Understanding Hierarchical Visual Dynamics](https://arxiv.org/abs/2607.04112v1)

- **arXiv**: `2607.04112v1`  |  **提交日期**: 2026-07-05
- **作者**: Silin Gao, Hao Zhao, Zeming Chen, Sepideh Mamooler, Antara Raaghavi Bhattacharya, Qiyu Wu et al.

Multimodal LLMs struggle to systematically model the temporal evolution of visual scenes in videos or multi-image sequences. Such inputs require models to predict or simulate multiple levels of dynamic constituents, such as actions taken in the visual sequence, and the associated changes to the visual environment that result. To address this challenge, we propose a dynamic schema-guided world model, DynaVieW, optimized for visual dynamic prediction and simulation. DynaVieW achieves an in-depth understanding of visual dynamics by learning interleaved state-transition sequences, where states…

---

### [Worldscape-MoE: A Unified Mixture-of-Experts World Model for Scalable Heterogeneous Action Control](https://arxiv.org/abs/2607.03964v1)

- **arXiv**: `2607.03964v1`  |  **提交日期**: 2026-07-04
- **作者**: Jianjie Fang, Yongyan Xu, Ziyou Wang, Chen Gao, Yuchao Huang, Zhaolu Wang et al.

World models are rapidly becoming a core infrastructure for embodied intelligence and interactive agents: they provide controllable simulators in which agents can perceive, act, forecast, and acquire scalable experience. Yet current video generation world models are still organized around isolated control interfaces, such as camera trajectories, robot actions, or hand-joint signals. This fragmentation is increasingly a scaling bottleneck. The central challenge is not the absence of controllable generators, but the lack of a unified and extensible learning framework that can absorb…

---

### [ThermoForce: A Physics-Structured Interventional World Model for Building HVAC Control](https://arxiv.org/abs/2607.03942v1)

- **arXiv**: `2607.03942v1`  |  **提交日期**: 2026-07-04
- **作者**: Yifan Wang

Model predictive control (MPC) of building HVAC systems needs thermal models that answer a causal question: what indoor temperature, energy use, and comfort will result if a control action is applied? Time-series foundation models (TSFMs) can forecast passive building trajectories with strong zero-shot skill, but high factual accuracy does not imply valid response to control interventions. We show that an observational grey-box model with the best passive accuracy predicts cooling effects with the wrong sign, and that adding control and weather covariates to a TSFM does not fix intervention…

---

## 📅 2026-07-03

### [WorldDirector: Building Controllable World Simulators with Persistent Dynamic Memory](https://arxiv.org/abs/2607.02517v1)

- **arXiv**: `2607.02517v1`  |  **提交日期**: 2026-07-02
- **作者**: Hanlin Wang, Hao Ouyang, Qiuyu Wang, Wen Wang, Qingyan Bai, Ka Leong Cheng et al.

We present WorldDirector, a highly controllable video world model framework designed for persistent dynamic object memory and unrestricted viewpoint exploration. Unlike existing world models that entangle physical dynamics with pixel rendering and rely on continuous visual observation to sustain motion, our framework explicitly decouples semantic motion orchestration from visual generation. By leveraging an LLM to coordinate 3D trajectories with camera movements and subsequently employing these orchestrated trajectories as control signals for video generation, our approach ensures strict…

---

### [WorldSample: Closed-loop Real-robot RL with World Modelling](https://arxiv.org/abs/2607.02431v1)

- **arXiv**: `2607.02431v1`  |  **提交日期**: 2026-07-02
- **作者**: Yuquan Xue, Le Xu, Zeyi Liu, Zhenyu Wu, Zhengyi Gu, Xinyang Song et al.

Reinforcement learning (RL) can overcome the demonstration-coverage limitation of imitation learning (IL) by allowing robots to improve through trial-and-error interaction beyond the states observed in demonstrations. However, deploying RL on real robots remains constrained by high interaction costs, since each physical rollout is costly and reflects only one realized action-outcome path. To address this challenge, we propose WorldSample, a physically grounded data augmentation framework for real-robot RL that closes a real-synthetic loop between physical rollouts, world-model generation, and…

---

### [ACID: Action Consistency via Inverse Dynamics for Planning with World Models](https://arxiv.org/abs/2607.02403v1)

- **arXiv**: `2607.02403v1`  |  **提交日期**: 2026-07-02
- **作者**: Gawon Seo, Dongwon Kim, Suha Kwak

Decision-time planning with action-conditioned world models has become a popular paradigm for embodied control. However, the standard planning cost judges a candidate solely by how close its predicted terminal state lies to the goal, leaving the realizability of the intermediate transitions unchecked -- a predicted trajectory can look convincing while the environment rollout drifts away from it. In this paper, we propose ACID, a decision-time planning framework that introduces cycle action consistency: the action inferred backward from a predicted transition by an inverse dynamics model…

---

### [DecompRL: Solving Harder Problems by Learning Modular Code Generation](https://arxiv.org/abs/2607.02390v1)

- **arXiv**: `2607.02390v1`  |  **提交日期**: 2026-07-02
- **作者**: Juliette Decugis, Fabian Gloeckle, Francis Bach, Taco Cohen, Gabriel Synnaeve

How can Large Language Models (LLMs) solve problems they currently cannot? Repeated sampling scales test-time compute but GPU cost grows linearly with attempts, while reinforcement learning (RL) with verifiable rewards improves single-attempt accuracy at the expense of sample diversity. Both strategies ultimately fail when the base policy has near-zero probability of producing a correct solution: no amount of sampling or gradient signal can overcome a search space that is simply too large. We take a different approach: rather than sampling harder, we make the task easier by decomposing…

---

### [Hardware-Enforced Semantic Coordination for Safety-Critical Real-Time Autonomous Systems](https://arxiv.org/abs/2607.02376v1)

- **arXiv**: `2607.02376v1`  |  **提交日期**: 2026-07-02
- **作者**: Uwe M. Borghoff, Paolo Bottoni, Remo Pareschi

Recent advances in agentic AI are producing increasingly complex autonomous systems that integrate large language models, world models, optimization engines, specialized neural architectures, autonomous platforms, and human operators. While much current research focuses on improving reasoning capabilities, safety-critical real-time deployment also requires bounded and verifiable coordination among heterogeneous components operating concurrently under uncertainty. Software-mediated coordination presents fundamental limitations in domains where bounded latency, deterministic coordination, and…

---

### [PWM-ArtGen: Part World Model for Articulated Object Generation](https://arxiv.org/abs/2607.02045v1)

- **arXiv**: `2607.02045v1`  |  **提交日期**: 2026-07-02
- **作者**: Wentao Zheng, Ancong Wu

The key challenge in articulated 3D object generation from a single image is accurately predicting the underlying kinematic structure. Existing methods either infer kinematic parameters directly from a static image that lacks dynamic part-level kinematic relationships, or estimate parameters from visual dynamics generated from a single image, which is prone to accumulated errors of two steps. Moreover, the limited scale and diversity of existing annotated datasets further hinder generalization to complex, real-world objects. To overcome these limitations, we propose to learn the joint…

---

### [Liquid Latent State Dynamics for Interpretable Turbofan Degradation Modeling](https://arxiv.org/abs/2607.01986v1)

- **arXiv**: `2607.01986v1`  |  **提交日期**: 2026-07-02
- **作者**: Weizhi Nie, Weijie Wang, Yuting Su

Multivariate time-series models for prognostics are often evaluated by point prediction accuracy, yet their internal states rarely expose a coherent degradation process. We study liquid neural networks as latent dynamics models for aircraft engine health monitoring on the C-MAPSS benchmark. The proposed model encodes a history window into a latent state, evolves that state with a liquid transition model, and decodes future sensor observations. To separate health evolution from operating-condition variation, the latent state is factorized into degradation and condition components. Remaining…

---

### [PhysMani: Physics-principled 3D World Model for Dynamic Object Manipulation](https://arxiv.org/abs/2607.01938v1)

- **arXiv**: `2607.01938v1`  |  **提交日期**: 2026-07-02
- **作者**: Peng Yun, Shouwang Huang, Hao Li, Jinxi Li, Jianan Wang, Bo Yang

Manipulating fast and dynamically moving targets in unstructured 3D environments remains challenging for embodied AI. Existing visual-language-action models and world models struggle with accurate 3D geometry and physically meaningful forecasting. We propose PhysMani, a framework that couples a physics-principled 3D Gaussian world model with a future-aware action policy model. The world model learns a divergence-free Gaussian velocity field via online optimization for fast and physically grounded future dynamics prediction. The policy model integrates the predicted 3D scene future dynamics…

---

### [Repair the Amplifier, Not the Symptom: Stable World-Model Correction for Agent Rollouts](https://arxiv.org/abs/2607.01767v1)

- **arXiv**: `2607.01767v1`  |  **提交日期**: 2026-07-02
- **作者**: Xinyuan Song, Zekun Cai

As agent planning moves from short tool chains toward persistent workflows with thousands or tens of thousands of steps, failures will occur inside large planning graphs rather than in isolated predictions. Replanning the entire graph after every mistake is neither computationally realistic nor desirable: full-graph replay consumes large context budgets, exposes the LLM to many irrelevant symptoms, and can degrade long-context retrieval. This paper studies the missing component in such systems: a world-model corrector that repairs the failed planning graph in place. We compare two families of…

---

### [Predicting Closed-Loop Performance of Latent World Models: Offline Checkpoint Selection for MPC and Model-Based RL Under Non-Markovian Rewards in LunarLander](https://arxiv.org/abs/2607.01736v1)

- **arXiv**: `2607.01736v1`  |  **提交日期**: 2026-07-02
- **作者**: Nikolai Smolyanskiy

We study how to predict the downstream closed-loop performance of a learned latent world model from validation-time diagnostics alone. Choosing the right checkpoint from a world-model training run is difficult: validation loss and multi-step prediction RMSE keep improving long after closed-loop performance has collapsed. We present a suite of structural validation-time diagnostics drawn from optimal-control theory and apply them to Gymnasium's LunarLander v3, which features shaped rewards. We train an RSSM [5, 4] world model on it and treat per checkpoint CEM-MPC return as the oracle for…

---

### [Safe and Adaptive Cloud Healing: Verifying LLM-Generated Recovery Plans with a Neural-Symbolic World Model](https://arxiv.org/abs/2607.01595v1)

- **arXiv**: `2607.01595v1`  |  **提交日期**: 2026-07-02
- **作者**: Junyan Tan, Haoran Lin, Siyuan Guo, Yichen Fang, Xinyue Luo, Tianyu Shen et al.

As the scale and complexity of cloud-based AI systems continue to escalate, ensuring service reliability through rapid fault detection and adaptive recovery has become a critical challenge. While existing approaches integrate Large Language Models (LLMs) for semantic understanding and Deep Reinforcement Learning (DRL) for policy optimization, they often rely on sequential, loosely coupled architectures that underutilize the generative and reasoning capabilities of LLMs. In this paper, we propose a paradigm shift with PASE, a Planning-Aware Semantic self-healing engine, a novel fault…

---

### [Certified World Models as Sensing Clocks: Drift-Aware Deadlines for Active Perception](https://arxiv.org/abs/2607.01537v1)

- **arXiv**: `2607.01537v1`  |  **提交日期**: 2026-07-01
- **作者**: Hongbo Wang

Certified world models estimate how long their predictions remain valid. We turn this validity horizon into an operational sensing clock: a rule for when an agent should stop coasting and re-sense. Starting from an audited equivariant world model, we derive a deadline for no-sensing intervals and show that deployable deadlines in learned world models must be drift-aware: on-manifold Lyapunov rates alone overestimate coasting validity, while calibrated native rollout-drift envelopes carry the deployed guarantee. On a frozen 3D VN-JEPA model, the resulting clock controls held-out…

---

### [OPINE-World: Programmatic World Modeling with Ontology-error-Prioritized Interactive Exploration](https://arxiv.org/abs/2607.01531v1)

- **arXiv**: `2607.01531v1`  |  **提交日期**: 2026-07-01
- **作者**: David Courtis, Wenhao Li, Scott Sanner

Learning how an environment behaves from interaction is central to building agents that adapt to unfamiliar tasks. World models learned with deep networks are flexible but data-hungry and transfer poorly beyond their training distribution. Program-synthesized world models, written as source code by LLMs and refined through counterexample-guided inductive synthesis (CEGIS), are instead data-efficient and reusable, yet they have been demonstrated mainly on structured-state worlds with a given object vocabulary, and a single program search does not scale to pixel-rendered environments whose…

---

### [From World Models to World Action Models: A Concise Tutorial for Robotics](https://arxiv.org/abs/2607.00836v2)

- **arXiv**: `2607.00836v2`  |  **提交日期**: 2026-07-01
- **作者**: Xiaoxiong Zhang, Xiong Zeng, Wei Zhang

World models are increasingly used in embodied intelligence and generative simulation, yet their scope remains ambiguous across communities. This tutorial presents a design-space view of world models as action-conditioned predictive models that estimate the future evolution of task-relevant observations or states. We categorize existing methods into observation-space and state-space world models, comparing their trade-offs in visual fidelity, spatial structure, physical interpretability, and control usability. We further introduce world action models, which connect predicted futures with…

---

### [DVG-WM: Disentangled Video Generation Enables Efficient Embodied World Model for Robotic Manipulation](https://arxiv.org/abs/2606.32028v2)

- **arXiv**: `2606.32028v2`  |  **提交日期**: 2026-06-30
- **作者**: Ziyu Shan, Zhenyu Wu, Xiaofeng Wang, Zheng Zhu, Ziwei Wang

Video-based embodied world models provide an appealing substrate for robotic manipulation by predicting future states, yet current approaches remain limited by a fundamental entanglement: accurately modeling dynamics typically requires low-level temporal reasoning, while producing high-resolution frames demands expansive visual synthesis according to high-level semantics. This entanglement results in slow inference speed for iterative planning or too coarse predictions to retain contact-rich details. To solve this dilemma, we present Disentangled Video Generation World Model (DVG-WM), an…

---

### [WorldOdysseyBench: An Open-World Benchmark for Long-Horizon Stability of Interactive World Models](https://arxiv.org/abs/2606.31672v2)

- **arXiv**: `2606.31672v2`  |  **提交日期**: 2026-06-30
- **作者**: Ting-Bing Xu, Jiacheng Sui, Zhe Gao, Kewei Shi, Wenjin Yang, Zhicheng Liu et al.

Despite rapid progress in interactive world models (IWMs), existing benchmarks evaluate action following only at trajectory level and ignore memory and interaction physics. We introduce WorldOdysseyBench, an open-world benchmark for long-horizon stability across four dimensions, each with tailored innovations: (i) Action: per-frame action metric bypassing cross-model semantic scale disparity and exposing failures hidden by trajectory; (ii) Vision: segment-based drift metric capturing non-monotonic mid-sequence collapse missed by start-vs-end comparisons; (iii) Physics: controllability-gated…

---

## 📅 2026-07-02

### [Structured 4D Latent Predictive Model for Robot Planning](https://arxiv.org/abs/2607.01166v1)

- **arXiv**: `2607.01166v1`  |  **提交日期**: 2026-07-01
- **作者**: Zhiyi Li, Peilin Wu, Xiaoshen Han, Ruojin Cai, Yilun Du

Video predictive models are emerging as a powerful paradigm in robotics, offering a promising path toward task generalization, long-horizon planning, and flexible decision-making. However, prevailing approaches often operate on 2D video sequences, inherently lacking the 3D geometric understanding necessary for precise spatial reasoning and physical consistency. We introduce a Structured 4D Latent Predictive Model, which predicts the evolution of a scene's 3D structure in a structured latent space conditioned on observations and textual instructions. Our representation encodes the scene…

---

### [RoboWorld: Fast and Reliable Neural Simulators for Generalist Robot Policy Evaluation](https://arxiv.org/abs/2607.01060v1)

- **arXiv**: `2607.01060v1`  |  **提交日期**: 2026-07-01
- **作者**: Byeongguk Jeon, Seonghyeon Ye, JaeHyeok Doo, Sungdong Kim, Minjoon Seo, Hyungmok Son et al.

Video world models are emerging as a scalable alternative for evaluating generalist robot policies, bypassing the physical constraints and engineering burdens of real-world deployment. However, evaluating policies with video world models remains challenging, as world-model errors can make generated rollouts unreliable and slow inference limits large-scale throughput. We introduce RoboWorld, an automated evaluation pipeline that pairs a fast autoregressive video world model with a task-progress-aware vision-language model scoring. To enable reliable long-horizon autoregressive world-model…

---

### [Valdi: Value Diffusion World Models](https://arxiv.org/abs/2607.00917v1)

- **arXiv**: `2607.00917v1`  |  **提交日期**: 2026-07-01
- **作者**: Christopher Lindenberg, Kashyap Chitta

World models can enable Model Predictive Control (MPC), but this requires dynamics prediction that is both fast enough for online use and expressive enough to represent uncertain futures. Diffusion models offer a natural mechanism for modeling uncertain dynamics, yet their iterative inference procedure makes them difficult to use for low-latency latent planning. We bridge this gap with Value Diffusion World Models (Valdi), combining end-to-end online training for MPC with a latent diffusion dynamics model. In preliminary experiments on the CarRacing environment, we show that Valdi, using a…

---

### [DeWorldSG: Depth-Aware 3D Semantic Scene Graph Generation via World-Model Priors](https://arxiv.org/abs/2607.00889v1)

- **arXiv**: `2607.00889v1`  |  **提交日期**: 2026-07-01
- **作者**: Seok-Young Kim, Abdelrahman Elskhawy, Taewook Ha, Dooyoung Kim, Eunjae Shin, Benjamin Busam et al.

We present DeWorldSG, a novel framework that generates spatio-temporally robust 3D Semantic Scene Graphs from RGB-D sequences. Existing methods often struggle to construct reliable 3D scene graphs due to unstable 3D object representations and missing relations caused by frame-wise inference. DeWorldSG addresses these issues by estimating instance-level geometric 3D Gaussian distributions through depth-guided filtering and representing each object as a probabilistic 3D node rather than a single projected point. To mitigate relational sparsity from frame-wise inference, our framework further…

---

### [From World Models to World Action Models: A Concise Tutorial for Robotics](https://arxiv.org/abs/2607.00836v1)

- **arXiv**: `2607.00836v1`  |  **提交日期**: 2026-07-01
- **作者**: Xiaoxiong Zhang, Xiong Zeng, Wei Zhang

World models are increasingly used in embodied intelligence and generative simulation, yet their scope remains ambiguous across communities. This tutorial presents a design-space view of world models as action-conditioned predictive models that estimate the future evolution of task-relevant observations or states. We categorize existing methods into observation-space and state-space world models, comparing their trade-offs in visual fidelity, spatial structure, physical interpretability, and control usability. We further introduce world action models, which connect predicted futures with…

---

### [ABot-M0.5: Unified Mobility-and-Manipulation World Action Model](https://arxiv.org/abs/2607.00678v1)

- **arXiv**: `2607.00678v1`  |  **提交日期**: 2026-07-01
- **作者**: Ronghan Chen, Yandan Yang, Zuojin Tang, Dongjie Huo, Tong Lin, Haoning Wu et al.

Mobile manipulation is a key capability for general-purpose robots, yet remains challenging for current embodied learning methods. VLA policies are typically reactive and lack explicit world modeling, while existing World Action Models (WAMs) are still poorly aligned with the structure of mobile manipulation: they operate on coarse video chunks, model entangled navigation-manipulation actions, and train inverse dynamics under supervision that does not match autoregressive inference. As a result, they often miss fine-grained contact dynamics, suffer from action-distribution conflicts, and…

---

### [Path Planning in Physically Viable World Models](https://arxiv.org/abs/2607.00673v1)

- **arXiv**: `2607.00673v1`  |  **提交日期**: 2026-07-01
- **作者**: Su Ann Low, Cheng-Hsi Hsiao, Xingjian Li, Adam J. Thorpe, Ufuk Topcu, Krishna Kumar

Robots deployed in unstructured outdoor environments often plan from scene reconstructions collected before deployment because operators cannot remap large or remote sites before every mission. As a result, robots must make long-horizon planning decisions using stale maps that assume the terrain remains unchanged, even though physical changes to the environment may render previously feasible routes unsafe or unreachable at execution time. We present a physically viable world model for evaluating what-if queries for robot navigation under future terrain change. The system augments…

---

### [AGI Maze as a Benchmark Framework for World-Modeling Agents](https://arxiv.org/abs/2607.00627v1)

- **arXiv**: `2607.00627v1`  |  **提交日期**: 2026-07-01
- **作者**: Alexey Potapov

Large language models (LLMs) are powerful pattern-completion systems, but their default operating mode - predicting the next token from a static context - does not reliably produce persistent, manipulable representations of an external world. Many tasks that look like "reasoning" in text become substantially harder once the environment is partially observable, stateful, and requires memory and structured hypotheses about hidden state. AGI Maze is a lightweight framework for building such environments without requiring high-dimensional sensory inputs. It provides a family of grid-based maze…

---

### [Multi-scale Mixture of World Models for Embodied Agents in Evolving Environments](https://arxiv.org/abs/2607.00457v1)

- **arXiv**: `2607.00457v1`  |  **提交日期**: 2026-07-01
- **作者**: Jinwoo Jang, Daniel J. Rho, Sihyung Yoon, Hyunsuk Cho, Honguk Woo

Embodied agents operating in the real world require multi-scale reasoning and knowledge adaptation as conditions change. We identify two challenges in applying Mixture of Experts (MoE) to this setting: routing lacks an explicit notion of scale, preventing targeted updates at specific scales, and a uniform update policy cannot accommodate the different rates at which knowledge at each scale becomes outdated. We present MuSix, a framework that addresses both challenges through scale-aware world model mixture and evolution. A two-stage routing mechanism grounds scale selection in experiential…

---

### [RetailSMV: Exocentric vs. Egocentric Adaptation of Foundation Video World Models in Retail](https://arxiv.org/abs/2607.00310v1)

- **arXiv**: `2607.00310v1`  |  **提交日期**: 2026-07-01
- **作者**: Amirreza Rouhi, Rajat Aggarwal, Parikshit Sakurikar, Anoop M. Namboodiri, Sashi P. Reddi

Foundation video diffusion models are increasingly viewed as world simulators for embodied agents, yet their pretraining on internet-scale generic video leaves them poorly aligned with real-world deployment domains. We study parameter-efficient adaptation of a pretrained foundation video world model to retail scenes: when synchronized egocentric and exocentric video of the same activity are available, which viewpoint of training data produces the strongest adapted model? We introduce RetailSMV (Retail Synchronized Multi-View), a corpus of 32,105 captioned retail clips from five supermarkets…

---

### [Testing Frontier Large Language Models' Physics Literacy in Parallel Physical Worlds](https://arxiv.org/abs/2607.00276v1)

- **arXiv**: `2607.00276v1`  |  **提交日期**: 2026-06-30
- **作者**: Dong Zhang

Current large-language-model (LLM) physics benchmarks are usually scored by answer accuracy, which cannot distinguish genuine reasoning from recall of familiar problem patterns and reveals little about where a model's reasoning breaks down. We introduce an auditable four-stage diagnostic that evaluates whether an LLM can reason inside an unfamiliar physics framework through induction, formulation, prediction, and review. The diagnostic combines locked pre-registrations, fresh sessions between stages, dual-LLM judging, and a human-audit pathway, and we apply it to three parallel physics…

---

### [VOCA: Visual Odometry with Codec Awareness](https://arxiv.org/abs/2607.00189v1)

- **arXiv**: `2607.00189v1`  |  **提交日期**: 2026-06-30
- **作者**: Nouri Alexander Hilscher, Mateo de Mayo, Dominik Muhle, Christoph Otten genannt Hermes, Daniel Cremers

Camera pose estimation from image streams is a critical component of spatial world models that integrate perception into planning and decision-making. Nearly all Visual Odometry (VO) and Simultaneous Localization and Mapping (V-SLAM) systems have focused on datasets containing raw, uncompressed videos. Many working systems instead use ubiquitous hardware units to efficiently compress and decode video streams, saving orders of magnitude in storage and bandwidth. However, this lossy compression introduces visual artifacts that hinder the performance of traditional tracking systems. We present…

---

## 📅 2026-07-01

### [DVG-WM: Disentangled Video Generation Enables Efficient Embodied World Model for Robotic Manipulation](https://arxiv.org/abs/2606.32028v1)

- **arXiv**: `2606.32028v1`  |  **提交日期**: 2026-06-30
- **作者**: Ziyu Shan, Zhenyu Wu, Xiaofeng Wang, Zheng Zhu, Ziwei Wang

Video-based embodied world models provide an appealing substrate for robotic manipulation by predicting future states, yet current approaches remain limited by a fundamental entanglement: accurately modeling dynamics typically requires low-level temporal reasoning, while producing high-resolution frames demands expansive visual synthesis according to high-level semantics. This entanglement results in slow inference speed for iterative planning or too coarse predictions to retain contact-rich details. To solve this dilemma, we present Disentangled Video Generation World Model (DVG-WM), an…

---

### [AdaJEPA: An Adaptive Latent World Model](https://arxiv.org/abs/2606.32026v1)

- **arXiv**: `2606.32026v1`  |  **提交日期**: 2026-06-30
- **作者**: Ying Wang, Oumayma Bounou, Yann LeCun, Mengye Ren

Latent world models enable planning from high-dimensional observations by predicting future states in a compact latent space. However, these models are typically kept frozen at test time: when their predictions become inaccurate, planning can fail, especially under test-time distribution shift. To address this, we propose AdaJEPA, an adaptive latent world model that performs test-time adaptation within the closed loop of model predictive control (MPC). After training, AdaJEPA plans and executes the first action chunk, uses the observed next-state transition as a self-supervised adaptation…

---

### [LeCropFollow: Latent Space Planning for Navigation in Unstructured Crop Fields](https://arxiv.org/abs/2606.31941v1)

- **arXiv**: `2606.31941v1`  |  **提交日期**: 2026-06-30
- **作者**: Felipe Tommaselli, Francisco Affonso, Arthur Pompeu, Gianluca Capezzuto, Arun Narenthiran Sivakumar, Girish Chowdhary et al.

Unstructured navigational features, such as irregular planting or discontinuities, remain the primary failure mode for under-canopy agricultural robots. Existing geometric approaches often fail in these scenarios because they compress high-dimensional visual data into deterministic spatial references, effectively discarding the uncertainty and semantic context required to navigate ambiguous terrain. To address this, we present LeCropFollow, a visual navigation framework that bypasses explicit geometric modeling in favor of a learned latent representation. By integrating a self-supervised…

---

### [MemLearner: Learning to Query Context memory for Video World Models](https://arxiv.org/abs/2606.31734v1)

- **arXiv**: `2606.31734v1`  |  **提交日期**: 2026-06-30
- **作者**: Jiwen Yu, Jianxiong Gao, Jianhong Bai, Yiran Qin, Kaiyi Huang, Quande Liu et al.

Video World Models are interactive video generation models that predict future world states based on user actions and history video frames. A critical challenge in video world models is the lack of memory, causing inconsistent generated scenes over extended durations. Previous methods explored rule-based context frame retrieval as memory, but they fail to generalize in scenarios with scene occlusions and dynamic objects. We propose MemLearner, a learning-based adaptive context query method using query tokens to bridge context and predicted tokens. By leveraging the video generation model…

---

### [WorldRoamBench: An Open-World Benchmark for Long-Horizon Stability of Interactive World Models](https://arxiv.org/abs/2606.31672v1)

- **arXiv**: `2606.31672v1`  |  **提交日期**: 2026-06-30
- **作者**: Ting-Bing Xu, Jiacheng Sui, Zhe Gao, Kewei Shi, Wenjin Yang, Zhicheng Liu et al.

Despite rapid progress in interactive world models (IWMs), existing benchmarks evaluate action following only at trajectory level and ignore memory and interaction physics. We introduce WorldRoamBench, an open-world benchmark for long-horizon stability across four dimensions, each with tailored innovations: (i) Action: per-frame action metric bypassing cross-model semantic scale disparity and exposing failures hidden by trajectory; (ii) Vision: segment-based drift metric capturing non-monotonic mid-sequence collapse missed by start-vs-end comparisons; (iii) Physics: controllability-gated…

---

### [Ask the World Before Acting: Budgeted Environment Probing for World-Model Calibration](https://arxiv.org/abs/2606.31422v1)

- **arXiv**: `2606.31422v1`  |  **提交日期**: 2026-06-30
- **作者**: Xinyuan Song, Zekun Cai

Long-horizon language agents do not only choose actions; they carry a private model of the world from one decision to the next. When that model drifts, a later failure can be decided before the failing action is ever taken. We study a direct repair mechanism: before committing to the next task action, an agent may ask the environment about one belief field and write the answer back into its world model. This makes environment interaction a scarce calibration resource, not merely a way to advance the task. We introduce \method, a budgeted probing operator for structured belief tables. The…

---

### [World-Model Collapse as a Phase Transition](https://arxiv.org/abs/2606.31399v1)

- **arXiv**: `2606.31399v1`  |  **提交日期**: 2026-06-30
- **作者**: Xinyuan Song, Zekun Cai

Water looks unchanged as it warms, then at a critical point it boils. We ask whether long-horizon language agents show an analogous transition in their implicit world models. In some parameter settings, changing state load by a small amount, or adding a single step of horizon, leaves behavior nearly unchanged; near a critical boundary, the same small change causes a sudden world collapse. We study this effect in a deterministic task family with exact per-step gold state. A large grid search over state cardinality, dependency density, horizon, branching, observation mode, and mutation rate…

---

### [One Video, One World: Turning Monocular Video into Physical 4D Scenes](https://arxiv.org/abs/2606.31388v1)

- **arXiv**: `2606.31388v1`  |  **提交日期**: 2026-06-30
- **作者**: Junhao Chen, Boran Zhang, Mingjin Chen, Henghaofan Zhang, Saining Zhang, Congcong Zhu et al.

We introduce \textbf{OVOW}, the first training-free system that reconstructs \emph{instance-level, simulation-ready} 4D mesh scenes from a single monocular video. Recent 4D reconstruction achieves impressive rendering quality, but its outputs (\eg, implicit fields, Gaussian primitives, or point clouds) lack the watertight topology, instance separation, and standardized physical interfaces required by physics simulators and embodied AI. OVOW closes this gap with a four-stage pipeline: a vision-language model discovers, labels, and motion-classifies all instances; category-aware reconstruction…

---

### [Delta-JEPA: Learning Action-Sensitive World Models via Latent Difference Decoding](https://arxiv.org/abs/2606.31232v1)

- **arXiv**: `2606.31232v1`  |  **提交日期**: 2026-06-30
- **作者**: Zhenghao Zhang, Yuanxiang Wang, Zhenyu Guan, Yujia Yang, Bingkang Shi, Tianyu Zong et al.

Learning visual world models for planning requires compact latent dynamics that remain sensitive to actions, yet reconstruction-free joint-embedding objectives can collapse to action-insensitive representations. We propose Delta-JEPA, an end-to-end reconstruction-free world model that augments latent forward prediction with a Latent Difference Action Decoder (LDAD). Unlike inverse decoders that infer actions from concatenated endpoint embeddings, LDAD reconstructs the executed action from the latent displacement between consecutive observations. This displacement-level supervision directly…

---

### [ForgeDrive: Bidirectional Cross-Conditioning for Unified Visual-Action Generation in Autonomous Driving](https://arxiv.org/abs/2606.31226v1)

- **arXiv**: `2606.31226v1`  |  **提交日期**: 2026-06-30
- **作者**: Xuchang Zhong, He Zheng, Chenxu Zhao, Tianxiong Lv, Hangqi Fan, Bohua Wang et al.

World-model-based autonomous driving endows the model with the ability to understand scene evolution. Yet this promise is undermined by the prevailing imagine-then-act paradigm, which allows errors from the more challenging visual generation stage to cascade into action planning. We introduce ForgeDrive, a unified autoregressive diffusion framework with visual-action cross-conditioning that closes this gap through act-then-imagine paradigm. ForgeDrive factorizes the future as a sequence of per-timestep frame-action pairs, intertwining each action with its corresponding visual observation.…

---

### [Long-term Traffic Simulation via Structured Autoregressive Modeling](https://arxiv.org/abs/2606.31209v1)

- **arXiv**: `2606.31209v1`  |  **提交日期**: 2026-06-30
- **作者**: Lingyu Xiao, Zexin Feng, Xintao Yan

Interactive traffic simulation is a vital world model for autonomous driving. A central challenge in long-horizon simulation is modeling sustained multi-agent interactions, which is further exacerbated by dynamic token cardinality as agents continuously enter and exit the scene. In this work, we propose that the solution lies in the synergy between the architectural inductive biases and statistical priors of large-scale sequence models, e.g., Large Language Models (LLMs). Our probing experiments reveal that the transferability of attention mechanisms and the distributional consistency between…

---

### [Learning Video Dynamics with Predictive Differentiable Rendering](https://arxiv.org/abs/2606.31050v1)

- **arXiv**: `2606.31050v1`  |  **提交日期**: 2026-06-30
- **作者**: Yujin Tang, Tian Zhou, Xin Lin, Cheng Tan, Yifan Hu, Rong Jin et al.

How to accurately predict a high-fidelity future world? While the visual world is inherently continuous, existing deterministic video prediction models operate in discrete pixel space and are mainly optimized with pixel-wise mean squared error (MSE), which often leads to over-smoothed predictions and a lack of fine-grained visual details. To address these limitations, we propose Predictive Differentiable Rendering (PDR), a novel end-to-end video prediction paradigm that bridges the gap between discrete and continuous representations. Inspired by recent progress in 3D reconstruction with 3D…

---

### [LWDrive: Layer-Wise World-Model-Guided Vision-Language Model Planning for Autonomous Driving](https://arxiv.org/abs/2606.29879v2)

- **arXiv**: `2606.29879v2`  |  **提交日期**: 2026-06-29
- **作者**: Chen Yang, Yuhao Wei, Ze Xu, Ziheng Zou, Shuang Liang, Delin Ouyang et al.

Vision-Language Models (VLMs) provide powerful semantic understanding and commonsense reasoning for End-to-End Autonomous Driving (E2E-AD) planning. However, trajectories directly generated by VLMs often encode only coarse driving intentions and remain insufficient for geometrically accurate, future-aware, and multi-view-grounded planning. To address these limitations, we develop the Layer-Wise World-Model-Guided Driving framework (LWDrive). LWDrive is a VLM planning framework that refines coarse trajectories through layer-wise world-model guidance. Instead of treating the VLM output as the…

---

## 📅 2026-06-30

### [Self-Evolving World Models for LLM Agent Planning](https://arxiv.org/abs/2606.30639v1)

- **arXiv**: `2606.30639v1`  |  **提交日期**: 2026-06-29
- **作者**: Xuan Zhang, Wenxuan Zhang, See-Kiong Ng, Yang Deng

World models offer a principled way to equip long-horizon LLM agents with foresight: predictions of action consequences before execution. However, unreliable foresight can be ignored, misused, or even degrade downstream decision-making. In this paper, we introduce WorldEvolver, a self-evolving world model framework that revises its deployment-time context while keeping the downstream agent and all model parameters frozen. WorldEvolver integrates three modules: (i) Episodic Memory, which exploits real action transitions through retrieval-based simulation; (ii) Semantic Memory, which extracts…

---

### [OWMDrive: Causality-Aware End-to-End Autonomous Driving via 4D Occupancy World Model](https://arxiv.org/abs/2606.30421v1)

- **arXiv**: `2606.30421v1`  |  **提交日期**: 2026-06-29
- **作者**: Junjie Cheng, Ruiqi Song, Ye Wu, Nanxing Zeng, Ximiao Li, Yunfeng Ai

Autonomous driving systems are steadily moving toward end-to-end paradigms to mitigate the limited adaptability of rule-based pipelines in complex traffic environments. However, most existing learning-based methods still make decisions from static representations of the current scene, without explicit future rollouts or modeling of the temporal causal dynamics in traffic interactions. This limitation often results in unstable or overly conservative planning under high-uncertainty conditions, such as occlusions and unexpected events. To overcome these challenges, we introduce OWMDrive, a…

---

### [DreamForge-World 0.1 Preview: A Low-Compute Real-Time Controllable World Model](https://arxiv.org/abs/2606.30292v1)

- **arXiv**: `2606.30292v1`  |  **提交日期**: 2026-06-29
- **作者**: Daniyel Ayupov, Artur Markov-Tsoy

We present DreamForge-World 0.1 Preview, a preview foundational world model for real-time interactive world simulation. The system adapts the LongLive 1 autoregressive video stack, itself derived from Wan2.1-T2V-1.3B, with a residual action pathway inspired by the Matrix-Game family. DreamForge-World 0.1 Preview focuses on a complementary axis to frontier-scale world simulators: low-compute adaptation, consumer-GPU runtime, and broad interactive capability coverage. It supports live keyboard and mouse control, multimodal initialization, mid-stream reprompting, dual-view operation, and…

---

### [Pondering the Way: Spatial-perceiving World Action Model for Embodied Navigation](https://arxiv.org/abs/2606.29908v1)

- **arXiv**: `2606.29908v1`  |  **提交日期**: 2026-06-29
- **作者**: Hong Chen, Daqi Liu, Zehan Zhang, Haiguang Wang, Tianhao Lu, Longfei Yan et al.

Existing world model-based planners for visual navigation typically follow a verification-centric paradigm, decoupling goal intent from trajectory synthesis. This approach suffers from candidate dependence, heavy computational overhead, and inconsistencies between sampled actions and predicted visuals. To address these issues, we propose SWAM (Spatial-perceiving World Action Model), a task-centric joint observation-action generation framework. Given start and goal RGB observations, SWAM performs single-pass inference to simultaneously generate intermediate RGB-D sequences and corresponding…

---

### [LWDrive: Layer-Wise World-Model-Guided Vision-Language Model Planning for Autonomous Driving](https://arxiv.org/abs/2606.29879v1)

- **arXiv**: `2606.29879v1`  |  **提交日期**: 2026-06-29
- **作者**: Chen Yang, Yuhao Wei, Ze Xu, Ziheng Zou, Shuang Liang, Delin Ouyang et al.

Vision-Language Models (VLMs) provide powerful semantic understanding and commonsense reasoning for End-to-End Autonomous Driving (E2E-AD) planning. However, trajectories directly generated by VLMs often encode only coarse driving intentions and remain insufficient for geometrically accurate, future-aware, and multi-view-grounded planning. To address these limitations, we develop the Layer-Wise World-Model-Guided Driving framework (LWDrive). LWDrive is a VLM planning framework that refines coarse trajectories through layer-wise world-model guidance. Instead of treating the VLM output as the…

---

### [The CRISTAL Method: Neurosymbolic analysis from AI-synthesized world models](https://arxiv.org/abs/2606.29799v1)

- **arXiv**: `2606.29799v1`  |  **提交日期**: 2026-06-29
- **作者**: Rafael Kaufmann, Felix Neubürger, Michael Walters, Thomas Kopinski, Dimitrije Marković

This project introduces the CRISTAL Method (Coherent Reliable Intentional Synthesis of Truthful Analysis Logic), a neurosymbolic framework for automating complex analysis workflows, with fundamental investment analysis as a primary use case. This domain poses major challenges: high structural uncertainty, noisy and subjective data, tight attention budgets, and the need for justified, reproducible decisions. Human analysts often struggle in this domain due to cognitive biases and limitations, suggesting significant value in automation. But while LLM-based agents have been proposed as…

---

### [HERO: Improving the Reliability and Sensitivity of Generative Model Evaluation Using Historical Data](https://arxiv.org/abs/2606.29784v1)

- **arXiv**: `2606.29784v1`  |  **提交日期**: 2026-06-29
- **作者**: Xinrui Ruan, Zhenyu Zhao, Waverly Wei, Yueshan Zhang, Zeyu Zheng, Sui Huang et al.

Reliable generative AI models critically rely on expert human annotations to evaluate output quality, yet these "gold" labels are expensive to collect and limited in quantity. Organizations thus often turn to collecting vast but noisy "silver" labels from crowdsourced workers or vendor annotators as proxies for gold labels. Because gold remains the evaluation target, naively aggregating noisy silver labels may introduce bias, and estimators built on sparsely observed gold labels may have high variance to resolve the model performance gaps that guide practical decisions. Model evaluation has…

---

### [Learning Transferable Dynamics Priors from Action to World Modeling](https://arxiv.org/abs/2606.29501v1)

- **arXiv**: `2606.29501v1`  |  **提交日期**: 2026-06-28
- **作者**: Ze Huang, Jiahui Zhang, Hairuo Liu, Chenxi Zhang, Ran Cheng, Li Zhang

We study action-conditioned world modeling as a scalable way to learn transferable dynamics priors for robot learning. By pretraining a model to predict how actions drive visual scene evolution, the resulting world model captures reusable interaction dynamics beyond appearance-level video generation. Concretely, we pretrain a multi-view interactive base diffusion world model, A2World, on large-scale robot manipulation data with real action annotations. We validate the learned dynamics priors from two complementary perspectives. First, we adapt A2World into a task- or scene-specialized…

---

### [Cognitive World Models for Process-Level Social Influence Evaluation](https://arxiv.org/abs/2606.29495v1)

- **arXiv**: `2606.29495v1`  |  **提交日期**: 2026-06-28
- **作者**: Minghui Ma, Bin Guo, Han Wang, Mengqi Chen, Jingqi Liu, Yan Liu et al.

Social influence dialogue changes user behavior by altering internal cognitive states. The central evaluation question is whether the user's beliefs, desires, intentions, and emotions measurably change over the course of conversation, a process-oriented criterion that neither surface-level text metrics (BLEU/ROUGE) nor single-score LLM judgments can capture. We propose the \textbf{Cog}nitive \textbf{W}orld \textbf{M}odel \textbf{(CogWM)}, an LLM-based user model that reframes multi-turn dialogue evaluation from ``what did the user say'' to ``how did the user's internal cognitive state…

---

### [Prototype Latent World Model Replay for Class-Incremental Learning](https://arxiv.org/abs/2606.29465v1)

- **arXiv**: `2606.29465v1`  |  **提交日期**: 2026-06-28
- **作者**: Weizhi Nie, Hui Wang, Weijie Wang, Yuting Su

Class-incremental learning requires a model to learn new classes while preserving decision regions for old ones. This is difficult when raw old samples are no longer available. We propose Prototype Latent World Model Replay, a memory-free framework that stores old classes as distributions over stable hidden states rather than as images. A frozen ImageNet-pretrained encoder maps each image into a latent state space. In this space, each class is summarized by several prototype-centered distributions with class-specific variances. When new classes arrive, the model samples old latent states from…

---

### [L2D2-GS: Learning to Densify for Feedforward Dynamic Gaussian Scene Reconstruction](https://arxiv.org/abs/2606.29374v1)

- **arXiv**: `2606.29374v1`  |  **提交日期**: 2026-06-28
- **作者**: Zetian Song, Chenming Wu, Junnan Liu, Chitian Sun, Liangliang He, Hangjun Ye et al.

High-fidelity reconstruction of dynamic urban environments is a cornerstone of autonomous driving simulation and large-scale world modeling. While 3D Gaussian Splatting (3DGS) has established a new standard for real-time rendering, its reliance on expensive per-scene optimization limits scalability. Conversely, recent feedforward methods that infer Gaussian parameters offer faster speed but face fundamental bottlenecks: they are memory-prohibitive at high resolutions and struggle to fuse dense multi-view observations consistently. This paper presents L2D2-GS, a unified framework that…

---

### [ASTAD: Asymmetric Style Transfer for Synthetic-to-Real Adaptation in Autonomous Driving](https://arxiv.org/abs/2606.29286v1)

- **arXiv**: `2606.29286v1`  |  **提交日期**: 2026-06-28
- **作者**: Dingyi Yao, Xinqi Zhang, Lihui Peng, Jianming Hu, Danya Yao, Yi Zhang

Synthetic data mitigates the data scarcity problem in autonomous driving perception. However, the synthetic-to-real gap leads to performance degradation, hindering real-world model generalization. Although current methods leverage diffusion models for photorealistic style transfer to bridge this gap, they critically ignore a practical asymmetry: while synthetic data possesses perfect pixel-level annotations, real-world style reference images generally lack corresponding labels. Consequently, existing methods relying on symmetric semantic guidance suffer from either prohibitive annotation…

---

### [Flow Matching in Feature Space for Stochastic World Modeling](https://arxiv.org/abs/2606.29059v1)

- **arXiv**: `2606.29059v1`  |  **提交日期**: 2026-06-27
- **作者**: Francois Porcher, Nicolas Carion, Karteek Alahari, Shizhe Chen

World modeling requires forecasting uncertain futures while preserving information useful for downstream perception. Existing visual world models often struggle to satisfy both goals: VAE-based stochastic models operate in low-dimensional reconstruction latents, which can limit perception performance, while deterministic predictors using strong pretrained features collapse multimodal futures into a single blurry mean. In this work, we propose FlowWM, a stochastic world model that performs flow matching directly within pretrained feature space (e.g., DINOv3). This is challenging because…

---

### [A Physics-Grounded Benchmark for Multi-Agent Dynamics in World Models](https://arxiv.org/abs/2606.28757v1)

- **arXiv**: `2606.28757v1`  |  **提交日期**: 2026-06-27
- **作者**: Nuo Chen, Lulin Liu, Zihao Li, Ziyao Zeng, Zihao Zhu, Wenyan Cong et al.

Generative world models hold immense promise as scalable simulators for autonomous systems, particularly for synthesizing rare but safety-critical multi-agent interactions, such as vehicle collisions. However, current evaluation paradigms index heavily on visual fidelity and semantic alignment, leaving a critical blind spot: they cannot reliably quantify whether generated dynamics actually obey the fundamental physical laws required for reliable simulation. Assessing this physical plausibility is inherently difficult due to a lack of physical metrics and the challenge of extracting…

---

### [A Path-Space Formulation of Prediction in World Models: From a Single Action to Prediction, Planning, and Irreversibility](https://arxiv.org/abs/2606.28751v1)

- **arXiv**: `2606.28751v1`  |  **提交日期**: 2026-06-27
- **作者**: Gunn Kim

We propose a path-space formulation of prediction in AI world models. Rather than sequences of one-step conditional distributions, we argue that a world model implicitly defines a probability measure over future trajectories. In the local regime where latent dynamics admit an effective Markovian description, this path measure takes the Onsager-Machlup form. Within this framework, prediction (most probable trajectory), planning (constrained optimization), and uncertainty (fluctuations) emerge as operations on a single action functional. We decompose the latent dynamics into reversible and…

---

### [J-LAW: Joint Localization and Actionable World Modeling via Coupled Latent Factor Graphs](https://arxiv.org/abs/2606.28712v1)

- **arXiv**: `2606.28712v1`  |  **提交日期**: 2026-06-27
- **作者**: Guanqun Cao, Liang Chen

Classical SLAM estimates metric poses and a geometric map but produces no actionable predictive model for planning. Action-conditioned world models learn compact latent dynamics for planning but ignore global metric consistency and accumulate drift under open-loop rollout. We argue these are two views of the same estimation problem and propose J-LAW (Joint Localization and Actionable World Modeling) in this letter: a coupled factor graph that jointly optimizes metric object poses, latent world states, and latent landmark embeddings. The bridge is a pose-conditioned latent encoder and a…

---

## 📅 2026-06-29

### [PhysisForcing: Physics Reinforced World Simulator for Robotic Manipulation](https://arxiv.org/abs/2606.28128v1)

- **arXiv**: `2606.28128v1`  |  **提交日期**: 2026-06-26
- **作者**: Peiwen Zhang, Yufan Deng, Shangkun Sun, Juncheng Ma, Duomin Wang, Jonas Du et al.

Video generation models have emerged as a promising paradigm for embodied world simulation. However, both general-domain video generators and robot-specific data fine-tuned models can still produce physically implausible manipulations, including discontinuous motion trajectories and inconsistent robot-object interactions, which limits their reliability as world simulators. Through extensive experiments, we find that such physical instability mainly arises from two factors: deformation of moving objects and implausible spatio-temporal correlations among interacting entities, particularly…

---

### [From Tokens to States: LLMs as a Special Case of World Models and the Continuous Path Beyond](https://arxiv.org/abs/2606.28127v1)

- **arXiv**: `2606.28127v1`  |  **提交日期**: 2026-06-26
- **作者**: Paul Dubois

The AI community has framed the relationship between large language models (LLMs) and world models as a dichotomy: LLMs predict tokens; world models simulate reality. Yann LeCun argues in 2022 that reaching general intelligence requires abandoning autoregressive token prediction in favour of latent-space architectures. This framing is unnecessarily binary. Two claims will be defended. First, LLMs are a degenerate special case of world models: the state space is the set of all token sequences, the only action is appending one token, and world models are therefore a strict generalisation of…

---

### [Directing the World: Fast Autoregressive Video Generation with Compositional Human-Camera Control](https://arxiv.org/abs/2606.27964v1)

- **arXiv**: `2606.27964v1`  |  **提交日期**: 2026-06-26
- **作者**: Haoyuan Wang, Yabo Chen, Haibin Huang, Chi Zhang, Xuelong Li

Building interactive world models requires generating realistic videos while maintaining controllable dynamics over long horizons. Autoregressive video generation offers a scalable foundation, but suffers from error accumulation and temporal degradation during extended rollouts. This issue is further amplified under heterogeneous controls such as human motion and camera trajectories, which may interfere and destabilize a pretrained video prior, while existing methods often trade off controllability and visual quality. We propose "Directing the World", a fast autoregressive framework for…

---

### [Grounded Iterative Language Planning: How Parameterized World Models Reduce Hallucination Propagation in LLM Agents](https://arxiv.org/abs/2606.27806v1)

- **arXiv**: `2606.27806v1`  |  **提交日期**: 2026-06-26
- **作者**: Xinyuan Song, Zekun Cai

World models for language agents come in two useful forms. An agent-based world model calls an LLM API and reasons flexibly in language, but its errors appear as hallucinated state changes that are hard to score with ordinary regression losses. A parameterized world model is a trained transition predictor; its errors are easier to measure with quantities such as NodeMSE, delta accuracy, and validity accuracy, but it is usually weaker as a standalone planner. We compare these two families on four graph-structured planning benchmarks and introduce operational hallucination metrics for the…

---

### [Understanding Rollout Error in Graph World Models](https://arxiv.org/abs/2606.27780v1)

- **arXiv**: `2606.27780v1`  |  **提交日期**: 2026-06-26
- **作者**: Xinyuan Song, Zekun Cai

World models are often used for planning by rolling learned dynamics forward. Many planning environments, however, are not vectors or images; they are graphs of agents, tools, skills, routes, and dependencies. In these settings, a local prediction error may stay local or spread through the graph, and the failure mode changes again when edges are predicted rather than fixed. This paper studies long-horizon rollout error in Graph World Models (GWMs). We formulate a unified fixed-edge and dynamic-edge GWM framework with action nodes for node-, edge-, and graph-level decisions. We develop…

---

### [Textual Belief States for World Models: Identifiable Representation Learning Under Strict Mediation](https://arxiv.org/abs/2606.27681v1)

- **arXiv**: `2606.27681v1`  |  **提交日期**: 2026-06-26
- **作者**: Xiang Gao, Kaiwen Dong, Yuguang Yao, Padmaja Jonnalagedda, Kamalika Das

World models in partially observed environments rely on latent representations that summarize interaction history, but in many modern LLM-based architectures predictive performance fails to reflect representation quality due to history bypass, rendering the latent state unidentifiable. Strict latent state mediation, requiring predictions to depend only on the latent state and action, is a classical principle that resolves this, but enforcing it in text-based settings is an open challenge: textual latent states are discrete and non-differentiable, precluding variational training, and…

---

### [CascadeOcc: Rethinking 3D Occupancy World Models with Cascaded VQ Representations](https://arxiv.org/abs/2606.27644v1)

- **arXiv**: `2606.27644v1`  |  **提交日期**: 2026-06-26
- **作者**: Kyumin Hwang, Wonhyeok Choi, Jaeyeul Kim, Jihun Park, Daehee Park, Sunghoon Im

This letter proposes CascadeOcc, a novel occupancy world model that prioritizes intrinsic structural hierarchy over extrinsic auxiliary modalities for autonomous driving. Occupancy world models -- forecasting the future driving environment and planning the driving trajectory -- effectively bridge perception and planning, but current approaches often heavily rely on external modalities or large language models, failing to fully exploit the inherent structural potential of occupancy representations themselves. To enhance representational capacity for complex 3D scenes, we integrate a cascaded…

---

## 📅 2026-06-27

### [PhysiFormer: Learning to Simulate Mechanics in World Space](https://arxiv.org/abs/2606.27364v1)

- **arXiv**: `2606.27364v1`  |  **提交日期**: 2026-06-25
- **作者**: Yiming Chen, Yushi Lan, Andrea Vedaldi

We present PhysiFormer, a diffusion transformer for physically-plausible 3D object motion. Unlike video world models that operate in view-dependent pixel space, PhysiFormer represents objects as 3D meshes expressed in world coordinates. Given the initial vertex positions and velocities, as well as object material type, rigid or elastic, the model samples future vertex trajectories. While related neural physics approaches build on ad-hoc latent spaces or explicitly enforce rigidity and causality, PhysiFormer shows that excellent results can be obtained without any such inductive biases, by…

---

### [Hallucination in World Models is Predictable and Preventable](https://arxiv.org/abs/2606.27326v1)

- **arXiv**: `2606.27326v1`  |  **提交日期**: 2026-06-25
- **作者**: Nicklas Hansen, Xiaolong Wang

Modern generative world models render increasingly realistic action-controllable futures, yet they frequently hallucinate: rollouts remain visually fluent while drifting from the ground-truth dynamics. We hypothesize that hallucination concentrates in low-coverage regions of the state-action space, where lightweight data-centric signals can both detect it and guide mitigation. To test this, we introduce MMBench2, a 427-hour, 210-task dataset for visual world modeling with ground-truth actions, rewards, and live simulators, and train a 350M-parameter world model on it. We identify three…

---

### [Not All Actions Are Equal: Rethinking Conditioning for Dexterous World Model](https://arxiv.org/abs/2606.27325v1)

- **arXiv**: `2606.27325v1`  |  **提交日期**: 2026-06-25
- **作者**: Zizhao Yuan, Zhengtu Liang, Taowen Wang, Qiwei Liang, Yichi Wang, Yunheng Wang et al.

Recent advances in action-conditioned world models show promising progress in modeling complex interactions and forecasting future states under diverse action sequences. While these models are often driven by stronger visual representations and model capacity, action conditioning itself remains underexplored. Most existing approaches compress the entire action sequence into a single representation, which works well for low-DoF control but becomes less reliable in high-DoF scenarios. We observe that high-DoF dexterous actions are inherently heterogeneous, spanning multiple orders of magnitude,…

---

### [EO-WM: A Physically Informed World Model for Probabilistic Earth Observation Forecasting](https://arxiv.org/abs/2606.27277v1)

- **arXiv**: `2606.27277v1`  |  **提交日期**: 2026-06-25
- **作者**: Junwei Luo, Shuai Yuan, Zhenya Yang, Yansheng Li, Zhe Liu, Hengshuang Zhao

Earth Observation (EO) forecasting aims to predict future Earth surface dynamics from satellite observations under changing meteorological conditions. In this paper, we view this task as a partially observed, weather-driven world modeling problem, in which weather acts as a conditioning signal, while forecasting remains uncertain due to sparse observations and unobserved land-surface states. However, existing methods do not fully capture this setting: deterministic models collapse uncertainty into a single future prediction, while diffusion-based methods typically treat weather variables as…

---

### [A Generalization Theory for JEPA-Based World Models](https://arxiv.org/abs/2606.27014v1)

- **arXiv**: `2606.27014v1`  |  **提交日期**: 2026-06-25
- **作者**: Jingyi Cui, Qi Zhang, Hongwei Wen, Yisen Wang

Joint Embedding Predictive Architectures (JEPAs) have recently emerged as a promising paradigm for world modeling by learning predictive dynamics in a latent space rather than generating future observations at the input level. Despite their empirical success, the theoretical understanding of JEPA-based world models remains limited. In this paper, we develop the first generalization theory for JEPA-based world models. We formulate JEPA pretraining as a conditional spectral graph learning problem and show that the JEPA objective is equivalent to a low-rank factorization of an action-conditioned…

---

### [Einstein World Models](https://arxiv.org/abs/2606.26969v1)

- **arXiv**: `2606.26969v1`  |  **提交日期**: 2026-06-25
- **作者**: Munachiso Samuel Nwadike, Zangir Iklassov, Ali Mekky, Zayd M. Kawakibi Zuhri, Kentaro Inui

Does intelligence require the ability to reason about phenomena beyond direct experience? It is natural to suspect that some complex thought cannot be captured through language alone. However, of particular concern to this work, is whether visualising counterfactual events can complement language as a mechanism for complex thought. We ask whether LLMs can be trained to utilise such visualisation mechanisms, in a way that benefits their reasoning abilities. Motivated by this question, we propose Einstein World Models. EWMs are a blueprint for LLM-based reasoning systems that place…

---

### [Look-Before-Move: Narrative-Grounded World Visual Attention in Dynamic 3D Story Worlds](https://arxiv.org/abs/2606.26964v1)

- **arXiv**: `2606.26964v1`  |  **提交日期**: 2026-06-25
- **作者**: Jiaming Bian, Bingliang Li, Yuehao Wu, Pichao Wang, Zhi Wang, Hailan Ma et al.

As embodied AI and world models increasingly operate in dynamic 3D environments, visual perception must move beyond passively interpreting given observations toward actively deciding what to observe. We study this problem through camera planning in dynamic 3D story worlds, where the camera must not only generate smooth motion, but also decide what visual evidence should be acquired before it moves. We formulate this capability as Narrative-Grounded World Visual Attention, where the camera acts as an embodied observer that determines what to observe, how to compose the observation, and how to…

---

### [Risk-Aware Selective Multimodal Driver Monitoring with Driver-State World Modeling](https://arxiv.org/abs/2606.26922v1)

- **arXiv**: `2606.26922v1`  |  **提交日期**: 2026-06-25
- **作者**: Daosheng Qiu, Haozhuang Chi, Hao Su, Shu Long, Xinyue Miao, Yongle Dong et al.

Continuous driver monitoring in automated vehicles requires low-latency inference while avoiding unsafe decisions under uncertain driver states. Large vision-language models provide broad multimodal priors, but their latency and limited reliability in this setting make them unsuitable as always-on in-cabin monitors. We propose a cost-aware selective inference framework for deployable multimodal driver monitoring. The core system is a lightweight RGB-physiological student that combines in-cabin visual observations with window-level HR/EDA signals, and a learned gate that decides when to accept…

---

### [LithoDreamer: A Physics-Informed World Model for Multi-Stage Computational Lithography](https://arxiv.org/abs/2606.26713v1)

- **arXiv**: `2606.26713v1`  |  **提交日期**: 2026-06-25
- **作者**: Yuqi Jiang, Yumeng Liu, Zimu Li, Jinyuan Deng, Qian Jin, Yucheng Cui et al.

As semiconductor technology nodes scale, computational lithography is essential for ensuring yield and performance. However, lithography is a continuous physical process involving mask optimization, optical imaging, resist exposure, and development, which existing models fail to capture. To overcome this limitation, we present LithoDreamer, the first physics-informed World Model (WM) framework for computational lithography, which formulates the ``Layout-Mask-Resist Image-After Development Image (ADI)'' pipeline as a decision-driven multi-step evolution system. LithoDreamer captures feature…

---

### [PhysEditWorld: A Large-Scale Dataset Toward Physics-Editable World Models](https://arxiv.org/abs/2606.26694v1)

- **arXiv**: `2606.26694v1`  |  **提交日期**: 2026-06-25
- **作者**: Bin Hu, Yanwen Ma, Jiehui Huang, Ziliang Zhang, Haoning Wu, Ruicheng Zhang et al.

Recent game world models can synthesize visually plausible, action-conditioned rollouts. However, their interaction behaviors often remain limited to exploratory or wandering trajectories, and physical dynamics are typically learned as implicit correlations from data rather than as controllable variables. This limitation hinders their applicability to authored game environments, where physical rules are deliberately designed and require explicit manipulation. We introduce PhysEditWorld, a multimodal dataset with physical parameters, with a primary focus on gravity in this initial version. At…

---

### [Neural Voxel Dynamics: Learning Implicit 3D Physics via Volumetric Feature Advection](https://arxiv.org/abs/2606.26410v1)

- **arXiv**: `2606.26410v1`  |  **提交日期**: 2026-06-24
- **作者**: Zican Wang, Niloy Mitra

We present a self-supervised framework for learning implicit 3D physical dynamics directly from video-derived supervisory signals. While current generative video models achieve high visual fidelity, they lack a 3D geometric foundation, often resulting in physical inconsistencies and a failure to maintain object permanence. We address this by shifting the predictive bottleneck from 2D image space to a `lifted' 3D Volumetric Latent Space. Our method unprojects semantic features from a Video Joint-Embedding Predictive Architecture (V-JEPA) into a voxelized grid, grounded by monocular depth…

---

### [KRVF: A Source-Aware Semantic Voxel World Representation for Edge Mobile Manipulation](https://arxiv.org/abs/2606.26321v1)

- **arXiv**: `2606.26321v1`  |  **提交日期**: 2026-06-24
- **作者**: Runfeng Ling

Mobile manipulators need world models that are current, queryable, semantically meaningful, and usable under edge-compute constraints. This technical report presents KRVF, a source-aware semantic voxel world representation for edge mobile manipulation. Unlike reconstruction-centric mapping pipelines that primarily optimize global geometric fidelity, KRVF represents local world state as task-oriented voxels that encode occupancy, color, semantic evidence, temporal freshness, and evidence source. The representation separates measured occupancy from semantic-prior hypotheses, enabling…

---

### [Fast LeWorldModel](https://arxiv.org/abs/2606.26217v1)

- **arXiv**: `2606.26217v1`  |  **提交日期**: 2026-06-24
- **作者**: Yuntian Gao, Xiangyu Xu

Joint-Embedding Predictive Architectures (JEPAs), including recent LeWorldModel (LeWM), have become a promising foundation for reconstruction-free visual world models. For visual planning, however, LeWM evaluates candidate action sequences by repeatedly applying a local one-step latent transition model. This autoregressive rollout makes planning computationally expensive and exposes the predicted trajectory to accumulated latent errors as the horizon grows. We propose Fast LeWorldModel (Fast-LeWM), a fast latent world model that replaces repeated local rollout with action-prefix prediction.…

---

### [The Unfireable Safety Kernel: Execution-Time AI Alignment for AI Agents and Other Escapable AI Systems](https://arxiv.org/abs/2606.26057v1)

- **arXiv**: `2606.26057v1`  |  **提交日期**: 2026-06-24
- **作者**: Seth Dobrin, Łukasz Chmiel

AI agents are granted access to tools, APIs, and other infrastructure, making them active principals in those systems. The dominant approach places controls inside the agent's own runtime: system prompts, output filters, and guardrail libraries. Any control in the agent's address space is reachable by inputs that influence it; this generalizes to any AI system with sufficient reach into its own runtime, a class we term escapable AI systems. We identify four properties that an authorization mechanism must satisfy for architectural control rather than for cooperative requests: process…

---

### [In-Context World Modeling for Robotic Control](https://arxiv.org/abs/2606.26025v2)

- **arXiv**: `2606.26025v2`  |  **提交日期**: 2026-06-24
- **作者**: Siyin Wang, Junhao Shi, Senyu Fei, Zhaoyang Fu, Li Ji, Jingjing Gong et al.

Modern Vision-Language-Action (VLA) models often fail to generalize to novel setups, such as altered camera viewpoints or robot morphologies, because they are typically conditioned only on current observations and language instructions. By ignoring the underlying system configuration as a variable, these models implicitly assume a fixed execution context encountered during training, necessitating data-intensive fine-tuning for any new environment. In this work, we introduce In-Context World Modeling (ICWM), a framework that treats system identification as an in-context adaptation problem.…

---

### [USS: Unified Spatial-Semantic Prompts for Embodied Visual Tracking with Latent Dynamics Learning](https://arxiv.org/abs/2606.25880v1)

- **arXiv**: `2606.25880v1`  |  **提交日期**: 2026-06-24
- **作者**: Yuchen Xie, Xinyu Zhou, Kuangji Zuo, Yanshuo Lu, Fengrui Huang, Boyu Ma et al.

Embodied Visual Tracking (EVT) requires an agent to continuously follow a specified target while actively moving through dynamic environments. However, prevailing EVT paradigms predominantly rely on language-based target indication. While language is expressive and convenient, cluttered scenes often contain multiple objects that satisfy the same semantic description, leading to ambiguous target grounding. We therefore propose a paradigm shift, reframing target indication in EVT from text-only specification to unified spatial-semantic prompting. Based on this paradigm, we introduce Unified…

---

### [Beyond One-Size-Fits-All: Diagnosis-Driven Online Reinforcement Learning with Offline Priors](https://arxiv.org/abs/2606.25527v1)

- **arXiv**: `2606.25527v1`  |  **提交日期**: 2026-06-24
- **作者**: Guozheng Ma, Lu Li, Zilin Wang, Pierre-Luc Bacon, Dacheng Tao

Online reinforcement learning (RL) agents increasingly depend on knowledge acquired offline to achieve practical efficiency. Originally studied in offline-to-online RL, this paradigm now spans foundation model post-training and embodied intelligence, with prior types expanding from offline datasets and pre-trained policies to increasingly diverse knowledge sources such as multimodal foundation models and generative world models. Offline priors have become central to how deep RL is developed and deployed. However, this reliance introduces a challenge that the prevailing benchmark-driven…

---

### [Causal-rCM: A Unified Teacher-Forcing and Self-Forcing Open Recipe for Autoregressive Diffusion Distillation in Streaming Video Generation and Interactive World Models](https://arxiv.org/abs/2606.25473v1)

- **arXiv**: `2606.25473v1`  |  **提交日期**: 2026-06-24
- **作者**: Kaiwen Zheng, Guande He, Min Zhao, Jintao Zhang, Huayu Chen, Jianfei Chen et al.

Autoregressive video diffusion with causal diffusion transformers has emerged as a major paradigm for real-time streaming video generation and action-conditioned interactive world models. In this work, we extend rCM, an advanced diffusion distillation framework, to autoregressive video diffusion. The core philosophy of rCM lies in the complementarity between forward and reverse divergences, represented by consistency models (CMs) and distribution matching distillation (DMD), respectively, in diffusion distillation. This philosophy naturally carries over to the autoregressive setting, where…

---

### [Hypergraph Normal World Models for Logical Visual Anomaly Detection](https://arxiv.org/abs/2606.25368v1)

- **arXiv**: `2606.25368v1`  |  **提交日期**: 2026-06-24
- **作者**: Weizhi Nie, Zibo Xu, Weijie Wang, Yuting Su

Visual anomaly detection is often deployed with only normal training images. Most one-class detectors map test patches or features to a normal reference distribution. This works well for local structural defects. Logical anomalies are different. Each visible part may look normal, while the whole image violates a normal count, co-occurrence, or spatial relation. This paper studies whether a model can learn such a category-specific normal world from nominal images alone. We propose the Hypergraph Normal World Model, a normal-only detector that distills frozen DINOv2 patch tokens into patch,…

---

