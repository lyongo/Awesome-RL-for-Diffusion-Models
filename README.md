![logo](./img/logo.png)

# Reward-driven Diffusion Models：A Comprehensive Review 
<!-- [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) -->
> A curated list of resources and papers on **Reinforcement Learning (RL) for Diffusion Models** — covering reward-driven training, preference optimization, RLHF, and domain-specific applications in **LLMs, Vision, Multimodal Learning, VLA/Robotics, and Science**.

---

## 📖 Contents

1. [📝 RL-dLLM](#-rl-dllm)
2. [👁️ RL-dVision](#️-rl-dvision)
3. [🎨 RL-dMM (Multimodal)](#-rl-dmm)
4. [🤖 RL-dVLA / dRobotics](#-rl-dvla--drobotics)
5. [🔬 RL-dScience](#-rl-dscience)
6. [📌 Contributing](#-contributing)
---
<!-- Paper 列使用 arXiv 徽章：https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white
<!-- [![Blog](https://img.shields.io/badge/blog-111111?style=for-the-badge&logo=hashnode&logoColor=white)](https://example.com/blog-post) -->
<!-- [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/XXXX.XXXXX) -->
<!-- Code 列使用 GitHub Star 徽章：https://img.shields.io/github/stars/{owner}/{repo}?style=for-the-badge&logo=github&label=GitHub&color=black --> 


## 📄 Paper List

### 📝 RL-dLLM 
RL-driven diffusion models applied to **large language models (LLMs)**.

| Date   | Name    | Title                           | Paper | Code |
|:------:|:-------:|---------------------------------|-------|------|
| 2025-08 | `LLaDA` | Large Language Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2502.09992) | [![GitHub Stars](https://img.shields.io/github/stars/ML-GSAI/LLaDA?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/ML-GSAI/LLaDA) |

---

### 👁️ RL-dVision

RL for **vision diffusion models** (image/vidoe/3D generation, editing, controllability).

| Date   | Name        | Title                                                                 | Paper | Code |
|:------:|:-----------:|-----------------------------------------------------------------------|-------|------|
| 2025-05 | `DanceGRPO` | DanceGRPO: Unleashing GRPO on Visual Generation                      | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.07818) | [![GitHub Stars](https://img.shields.io/github/stars/XueZeyue/DanceGRPO?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/XueZeyue/DanceGRPO) |
| 2025-05 | `Flow-GRPO` | Flow-GRPO: Training Flow Matching Models via Online RL               | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.05470) | [![GitHub Stars](https://img.shields.io/github/stars/yifan123/flow_grpo?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/yifan123/flow_grpo) |
| 2025-05 | `Pref-GRPO` | Pref-GRPO: Pairwise Preference Reward-based GRPO for Stable Text-to-Image RL | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.05470) |[![GitHub Stars](https://img.shields.io/github/stars/CodeGoat24/Pref-GRPO?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/CodeGoat24/Pref-GRPO) |
| 2024-12 | `Video-DPO` | VideoDPO: Omni-Preference Alignment for Video Diffusion Generation   | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2412.14167) | [![GitHub Stars](https://img.shields.io/github/stars/CIntellifusion/VideoDPO?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/CIntellifusion/VideoDPO) |
| 2024-10 | `T2V-Turbo-v2` | T2V-Turbo-v2: Enhancing Video Generation Model Post-Training through Data, Reward, and Conditional Guidance Design | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2410.05677) |[![GitHub Stars](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/Ji4chenLi/t2v-turbo)  |
| 2024-02 | `Dense-Reward-T2I` | A Dense Reward View on Aligning Text-to-Image Diffusion with Preference | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.02835) | [![GitHub Stars](https://img.shields.io/github/stars/Shentao-YANG/Dense_Reward_T2I?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/Shentao-YANG/Dense_Reward_T2I) |
| 2023-11 | `Diffusion-DPO` | Diffusion Model Alignment Using Direct Preference Optimization | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2311.12908) | [![GitHub Stars](https://img.shields.io/github/stars/THUDM/ImageReward?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/THUDM/ImageReward) |
| 2023-05 | `DPOK`     | DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2305.16381) | [![GitHub Stars](https://img.shields.io/github/stars/google-research/google-research?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/google-research/google-research/tree/master/dpok) |
| 2023-04 | `ImageReward` | ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/html/2304.05977v4) | [![GitHub Stars](https://img.shields.io/github/stars/THUDM/ImageReward?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/THUDM/ImageReward) |

---

### 🎨 RL-dMM

RL for **multimodal diffusion models** (multimodal understanding and generation).

| Date   | Name            | Title                                                              | Paper | Code |
|:------:|:---------------:|--------------------------------------------------------------------|-------|------|
| 2025-08 | `MMaDA`         | MMaDA: Multimodal Large Diffusion Language Models                 | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.15763v1) | [![GitHub Stars](https://img.shields.io/github/stars/Gen-Verse/MMaDA?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/Gen-Verse/MMaDA) |
| 2025-08 | `LLaDA-V`       | LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.16933) | [![GitHub Stars](https://img.shields.io/github/stars/ML-GSAI/LLaDA-V?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/ML-GSAI/LLaDA-V) |
| 2025-05 | `R1-Reward`     | R1-Reward: Training Multimodal Reward Model Through Stable RL      | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.02835) | [![GitHub Stars](https://img.shields.io/github/stars/yfzhang114/r1_reward?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/yfzhang114/r1_reward) |
| 2025-05 | `UnifiedReward-Think` | Unified Multimodal Chain-of-Thought Reward Model through Reinforcement Fine-Tuning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/pdf/2505.03318) | [![GitHub Stars](https://img.shields.io/github/stars/CodeGoat24/UnifiedReward?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/CodeGoat24/UnifiedReward) |
| 2025-03 | `UnifiedReward` | Unified Reward Model for Multimodal Understanding and Generation   | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2503.05236) | [![GitHub Stars](https://img.shields.io/github/stars/CodeGoat24/UnifiedReward?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/CodeGoat24/UnifiedReward) |

---

### 🤖 RL-dVLA / dRobotics

RL-diffusion in **vision-language-action (VLA)** systems and **robotics applications**.

| Date   | Name   | Title                                                               | Paper | Code |
|:------:|:------:|---------------------------------------------------------------------|-------|------|
| 2025-08 | `π0`   | π0: A Vision-Language-Action Flow Model for General Robot Control  | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2508.15763v1) ||
| 2023-03 | `DP`| Diffusion Policy: Visuomotor Policy Learning via Action Diffusion | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2303.04137) | [![GitHub Stars](https://img.shields.io/github/stars/real-stanford/diffusion_policy?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/real-stanford/diffusion_policy) |
| 2024-09 | `DP3`| 3D Diffusion Policy:  Generalizable Visuomotor Policy Learning via Simple 3D Representations | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2403.03954) | [![GitHub Stars](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/YanjieZe/3D-Diffusion-Policy) |
| 2024-09 | `DPPO`| Diffusion Policy Policy Optimization| [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2409.00588) | [![GitHub Stars](https://img.shields.io/github/stars/irom-princeton/dppo?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/irom-princeton/dppo) |
| 2025-08 | `DP-RRL`| A Hybrid Framework Using Diffusion Policy and Residual RL for Force-Sensitive Robotic Manipulation| [ Paper ](https://ieeexplore.ieee.org/document/11114901) | |
| 2025-08 | `D3P`| D3P: Dynamic Denoising Diffusion Policy via Reinforcement Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2508.06804) | |
| 2024-02 | `SRDP`| Diffusion Policies for Out-of-Distribution Generalization in Offline Reinforcement Learning| [ Paper ](https://ieeexplore.ieee.org/abstract/document/10423845) | |
| 2025-05 | `DiffusionRL`| DiffusionRL: Efficient Training of Diffusion Policies for Robotic Grasping Using RL-Adapted Large-Scale Datasets | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2505.18876) | |
| 2025-08 | `DiWA`| DiWA: Diffusion Policy Adaptation with World Models | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2508.03645) | [![GitHub Stars](https://img.shields.io/github/stars/acl21/diwa?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/acl21/diwa) |
| 2025-09 | `DreamControl`| DreamControl: Human-Inspired Whole-Body Humanoid Control for Scene Interaction via Guided Diffusion| [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2509.14353)  | |
| 2025-01 | `FDPP`| FDPP: Fine-tune Diffusion Policy with Human Preference| [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2501.08259)  | |
| 2025-03 | `TrajHF`| Finetuning Generative Trajectory Model with Reinforcement Learning from Human Feedback | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2503.10434)  | |
| 2025-05 | `FQL`| Flow Q-Learning | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2502.02538)  |[![GitHub Stars](https://img.shields.io/github/stars/seohongpark/fql?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/seohongpark/fql) |
| 2025-07 | `DMLoco`| Integrating Diffusion-based Multi-task Learning with Online Reinforcement Learning for Robust Quadruped Robot Control | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2507.05674)  |[![GitHub Stars](https://img.shields.io/github/stars/queenxy/DMLoco?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/queenxy/DMLoco) |
| 2025-08 | `IRL-VLA`| IRL-VLA: Training an Vision-Language-Action Policy via Reward World Model | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2508.06571)  |[![GitHub Stars](https://img.shields.io/github/stars/IRL-VLA/IRL-VLA?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/IRL-VLA/IRL-VLA) |
| 2024-07 | `ResiP`| From Imitation to Refinement Residual RL for Precise Visual Assembly | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.16677)  |[![GitHub Stars](https://img.shields.io/github/stars/ankile/robust-rearrangement?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/ankile/robust-rearrangement) |
| 2024-12 | `Policy Decorator`| Policy Decorator: Model-Agnostic Online Refinement for Large Policy Model | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2412.13630)  |[![GitHub Stars](https://img.shields.io/github/stars/tongzhoumu/policy_decorator?style=for-the-badge&logo=github&label=GitHub&color=black)](https://github.com/tongzhoumu/policy_decorator) |
| 2025-09 | | Beyond Human Demonstrations: Diffusion-Based Reinforcement Learning to Generate Data for VLA Training | [![Paper](https://img.shields.io/badge/paper-A42C25?style=for-the-badge&logo=arxiv&logoColor=white)](http://arxiv.org/abs/2509.19752)  | |

---
### 🔬 RL-dScience

RL-driven diffusion in **scientific domains** (molecule, protein, physics, material science).

| Date   | Name       | Title | Paper | Code |
|:------:|:----------:|-------|-------|------|
| 2025-08 | `AlphaFold` |       | [![Blog](https://img.shields.io/badge/blog-111111?style=for-the-badge&logo=hashnode&logoColor=white)](https://deepmind.google/science/alphafold/) | |

---

## 📌 Contributing

Contributions are welcome! 🎉
If you want to add a new paper, dataset, or resource:

1. Fork this repository
2. Add your entry in the appropriate section
3. Submit a Pull Request
