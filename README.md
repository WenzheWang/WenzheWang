# Hi there, I'm Wenzhe Wang! 👋

I'm a **PhD graduate from Zhejiang University**, working at the intersection of **AI infrastructure** and **computer vision**. I contribute to large-scale training frameworks ([VeOmni](https://github.com/ByteDance-Seed/VeOmni), [verl](https://github.com/verl-project/verl), [verl-omni](https://github.com/verl-project/verl-omni)) and kernel DSLs ([tilelang](https://github.com/tile-ai/tilelang)), while publishing research at top-tier venues (EMNLP, NeurIPS, ICCV, IJCAI, ECAI, IEEE TMI).

## 🔬 Research

My research spans distributed training systems, vision-language models, and computational imaging.

**Selected Publications:**

- **[Dig into Multi-modal Cues for Video Retrieval with Hierarchical Alignment](https://doi.org/10.24963/ijcai.2021/154)** — *IJCAI 2021* (first author)
- **[FlowTrain: Flow-Based Decoupled Training for Industrial-Grade Vision-Language Models](https://arxiv.org/abs/2606.23087)** — *EMNLP 2026* (co-author)
- **[A Siamese Transformer with Hierarchical Refinement for Lane Detection](https://doi.org/10.52202/079017-1293)** — *NeurIPS 2024*
- **[SinLane: Siamese Visual Transformer via Pyramid Feature Integration for Lane Detection](https://doi.org/10.3233/FAIA240481)** — *ECAI 2024*
- **[PR-Net: Preference Reasoning for Personalized Video Highlight Detection](https://arxiv.org/abs/2109.01799)** — *ICCV 2021*
- **[Interactive Few-Shot Learning: Limited Supervision, Better Medical Image Segmentation](https://doi.org/10.1109/TMI.2021.3060551)** — *IEEE TMI 2021*
- **[IFPNet: Integrated Feature Pyramid Network with Fusion Factor for Lane Detection](https://doi.org/10.1109/ICCVW60793.2023.00203)** — *ICCV Workshop 2023*
- **[Temporal Structured Illumination and Vision-Transformer Enables Large Field-of-View Binary Snapshot Ptychography](https://doi.org/10.1364/OE.504721)** — *Optics Express 2024*
- **[Propagation Dynamics of a Spatiotemporal Vortex Pulse in the Spatial Fractional System](https://doi.org/10.1364/PRJ.529463)** — *Photonics Research 2024*

📖 Full publication list: [Google Scholar](https://scholar.google.com/citations?user=J4b99-cAAAAJ)

## 💻 Open Source

🔧 **Active Committer**, [verl-project/verl-omni](https://github.com/verl-project/verl-omni) — listed in [official governance](https://github.com/verl-project/verl-omni/blob/main/docs/community/governance.md#active-committers) and co-owner of the `verl_omni/trainer/` module.

I'm an **active committer** to [verl-omni](https://github.com/verl-project/verl-omni) (multimodal RL post-training frameworks) and a contributor to [VeOmni](https://github.com/ByteDance-Seed/VeOmni) (model-centric distributed training recipe zoo), [verl](https://github.com/verl-project/verl), and [tilelang](https://github.com/tile-ai/tilelang) (high-performance kernel DSL).

**Selected Contributions:**

- **verl-omni:** [Qwen3-Omni Thinker DAPO phase one](https://github.com/verl-project/verl-omni/pull/456), [batched CLAP reward inference](https://github.com/verl-project/verl-omni/pull/367), [strip responses from worker batches](https://github.com/verl-project/verl-omni/pull/430), [reject silent fallbacks](https://github.com/verl-project/verl-omni/pull/429), and [batched PickScore inference](https://github.com/verl-project/verl-omni/pull/346)
- **VeOmni:** [Ascend Triton clamped SwiGLU](https://github.com/ByteDance-Seed/VeOmni/pull/1104), [packed ChunkMBS support](https://github.com/ByteDance-Seed/VeOmni/pull/898), [Qwen3-VL FSDP2 torch compile](https://github.com/ByteDance-Seed/VeOmni/pull/1009), [HSDP all-reduce control](https://github.com/ByteDance-Seed/VeOmni/pull/1026), and [deterministic mapping cycles](https://github.com/ByteDance-Seed/VeOmni/pull/1045)
- **verl:** [refresh FSDP and SkyPilot guides](https://github.com/verl-project/verl/pull/7185)
- **tilelang:** [validate T.gemm k_pack arguments](https://github.com/tile-ai/tilelang/pull/3094)

Research directions:
- **Parallelism & memory optimization** — packed sequence packing, ChunkMBS, FSDP2/hsdp integration
- **Training-time validation** — distributed metric aggregation and evaluation pipeline
- **Hardware portability** — NPU/Ascend enablement and cross-platform validation
- **Kernel & operator development** — Triton kernels for NPU, GEMM argument validation
- **Multimodal reward engineering** — batched reward inference and reward model integration
- **Rollout & training pipeline** — async semantics, rollout-train consistency, group management
- **Efficient post-training** — LoRA/FSDP for VLMs, distributed reward handling

## 🛠️ Tech Stack

```
Languages      Python · C++ · CUDA · Triton · Shell
Frameworks     PyTorch · VeOmni · verl · FSDP/FSDP2 · DeepSpeed
Kernels        tilelang · Triton · Ascend/NPU
Distributed    DDP · HSDP · FSDP · Tensor Parallel · Expert Parallel · ChunkMBS
Infrastructure Slurm · Ray · wandb · Docker
Vision/RL       Diffusion Models · VLMs · Video Retrieval · Medical Imaging
```

## 📫 Connect

- 📧 Email: w_wenzhe[AT]163.com
- 🏠 Location: Hangzhou, China

---

<sub>💫 "From research papers to production training frameworks — bridging the gap between algorithms and infrastructure."</sub>
