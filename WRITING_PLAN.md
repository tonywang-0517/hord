# HoRD GitHub 页面写作计划

## 一、页面定位
- 对应论文：**HoRD: Robust Humanoid Control via History-Conditioned Reinforcement Learning and Online Distillation**
- 叙事与命名以 HoRD 为准；实验数据与 eval 视频沿用现有项目（与论文一致）
- 仅保留 GitHub 项目页需要的部分，符合学术项目页惯例

---

## 二、大纲（仅 GitHub 页需要的部分）

### 1. Hero 区
- **标题**：HoRD — Robust Humanoid Control via History-Conditioned RL and Online Distillation
- **作者**：Puyue Wang, Jiawei Hu, Yan Gao, Junyan Wang, Yu Zhang, Gillian Dobbie, Tao Gu, Wafa Johal, Ting Dang, Hong Jia
- **单位**：University of Auckland, UNSW, Cambridge, Adelaide, Macquarie University, University of Melbourne
- **链接**：Paper | Code | Video

### 2. Abstract
- 论文 Abstract：两阶段（history-conditioned RL teacher + online distillation）、稀疏根相对 3D 关键点、HCDR、SSJR、跨域与 zero-shot、90.7% / 86.0%

### 3. 核心指标
- 四卡片：IsaacLab 90.7%、IsaacLab+DR 88.4%、Genesis 86.0%、Genesis+DR 84.4%

### 4. Framework Overview
- 两阶段 teacher–student、HCDR、SSJR、episode-level domain randomization

### 5. 核心组件
- **SSJR**：Standardized Sparse-Joint Representation
- **HCDR**：History-Conditioned Dynamics Representation

### 6. Training Methodology
- Stage 1 专家 PPO / Stage 2 学生蒸馏、Episode-Level DR、实验设置

### 7. Experimental Results
- Table 1、三列对比视频（MaskedMimic / ExBody2 / HoRD）

### 8. Ablation
- HoRD / w/o D / w/o H（Table 2）

### 9. 方法对比表
- Appendix Table 5：Unified / Sparse-Command / Online Dynamics Adaptation

### 10. 代表动作 + 地形 + 扰动 + BibTeX
- 六类动作、地形、扰动恢复、BibTeX 更新为 HoRD

### 11. 命名统一
- MIRAGE→HoRD, SCHEMA→SSJR, MIRROR→HCDR；精简 RISE 块
