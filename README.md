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


## 📄 Paper List

### 📝 RL-dLLM 
RL-driven diffusion models applied to **large language models (LLMs)**.

| Date   | Name    | Title                           | Paper | Code |
|:------:|:-------:|---------------------------------|-------|------|
| 2025-08 | `LLaDA` | Large Language Diffusion Models | [Paper](https://github.com/ML-GSAI/LLaDA) | [Code](https://github.com/ML-GSAI/LLaDA) |

---

### 👁️ RL-dVision

RL for **vision diffusion models** (image/vidoe/3D generation, editing, controllability).

| Date   | Name        | Title                                                                 | Paper | Code |
|:------:|:-----------:|-----------------------------------------------------------------------|-------|------|
| 2025-05 | `DanceGRPO` | DanceGRPO: Unleashing GRPO on Visual Generation                      | [Paper](https://arxiv.org/abs/2505.07818) | [Code](https://github.com/XueZeyue/DanceGRPO) |
| 2025-05 | `Flow-GRPO` | Flow-GRPO: Training Flow Matching Models via Online RL               | [Paper](https://arxiv.org/abs/2505.05470) | [Code](https://github.com/yifan123/flow_grpo) |
| 2025-05 | `Pref-GRPO` | Pref-GRPO: Pairwise Preference Reward-based GRPO for Stable Text-to-Image RL | [Paper](https://arxiv.org/abs/2505.05470) | [Code](https://codegoat24.github.io/UnifiedReward/Pref-GRPO) |
| 2024-12 | `Video-DPO` | VideoDPO: Omni-Preference Alignment for Video Diffusion Generation   | [Paper](https://arxiv.org/pdf/2412.14167) | [Code](https://github.com/CIntellifusion/VideoDPO) |
| 2024-10 | `T2V-Turbo-v2` | T2V-Turbo-v2: Enhancing Video Generation Model Post-Training through Data, Reward, and Conditional Guidance Design | [Paper](https://arxiv.org/abs/2410.05677) |[Code](https://github.com/Ji4chenLi/t2v-turbo)  |
| 2024-02 | `Dense-Reward-T2I` | A Dense Reward View on Aligning Text-to-Image Diffusion with Preference | [Paper](https://arxiv.org/abs/2505.02835) | [Code](https://github.com/Shentao-YANG/Dense_Reward_T2I) |
| 2023-11 | `Diffusion-DPO` | Diffusion Model Alignment Using Direct Preference Optimization | [Paper](https://arxiv.org/abs/2311.12908) | [Code](https://github.com/THUDM/ImageReward) |
| 2023-05 | `DPOK`     | DPOK: Reinforcement Learning for Fine-tuning Text-to-Image Diffusion Models | [Paper](https://arxiv.org/abs/2305.16381) | [Code](https://github.com/google-research/google-research/tree/master/dpok) |
| 2023-04 | `ImageReward` | ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation | [Paper](https://arxiv.org/html/2304.05977v4) | [Code](https://github.com/THUDM/ImageReward) |


---

### 🎨 RL-dMM

RL for **multimodal diffusion models** (multimodal understanding and generation).

| Date   | Name            | Title                                                              | Paper | Code |
|:------:|:---------------:|--------------------------------------------------------------------|-------|------|
| 2025-08 | `MMaDA`         | MMaDA: Multimodal Large Diffusion Language Models                 | [Paper](https://arxiv.org/abs/2508.15763v1) | [Code](https://github.com/Gen-Verse/MMaDA) |
| 2025-08 | `LLaDA-V`       | LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning | [Paper](https://arxiv.org/abs/2505.16933) | [Code](https://github.com/ML-GSAI/LLaDA-V) |
| 2025-05 | `R1-Reward`     | R1-Reward: Training Multimodal Reward Model Through Stable RL      | [Paper](https://arxiv.org/abs/2505.02835) | [Code](https://github.com/yfzhang114/r1_reward) |
| 2025-05 | `UnifiedReward-Think` | Unified Multimodal Chain-of-Thought Reward Model through Reinforcement Fine-Tuning | [Paper](https://arxiv.org/pdf/2505.03318) | [Code](https://github.com/CodeGoat24/UnifiedReward) |
| 2025-03 | `UnifiedReward` | Unified Reward Model for Multimodal Understanding and Generation   | [Paper](https://arxiv.org/abs/2503.05236) | [Code](https://codegoat24.github.io/UnifiedReward/) |

---

### 🤖 RL-dVLA / dRobotics

RL-diffusion in **vision-language-action (VLA)** systems and **robotics applications**.

| Date   | Name   | Title                                                               | Paper | Code |
|:------:|:------:|---------------------------------------------------------------------|-------|------|
| 2025-08 | `π0`   | π0: A Vision-Language-Action Flow Model for General Robot Control  | [Paper](https://arxiv.org/abs/2508.15763v1) | |

---

### 🔬 RL-dScience

RL-driven diffusion in **scientific domains** (molecule, protein, physics, material science).

| Date   | Name       | Title | Paper | Code |
|:------:|:----------:|-------|-------|------|
| 2025-08 | `AlphaFold` |       | [Paper](https://deepmind.google/science/alphafold/) | |

---

## 📌 Contributing

Contributions are welcome! 🎉
If you want to add a new paper, dataset, or resource:

1. Fork this repository
2. Add your entry in the appropriate section
3. Submit a Pull Request
