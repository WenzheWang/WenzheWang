# Hi there, I'm Wenzhe Wang! 👋

I'm a researcher and engineer working at the intersection of **AI infrastructure** and **computer vision**. Currently at **Zhejiang University**, I contribute to large-scale training frameworks ([VeOmni](https://github.com/ByteDance-Seed/VeOmni), [verl](https://github.com/verl-project/verl)) while publishing research at top-tier venues (ICCV, IJCAI, ECAI, IEEE TMI).

## 🔬 Research

My research spans distributed training systems, vision-language models, and computational imaging.

**Selected Publications:**

- **Dig into Multi-modal Cues for Video Retrieval with Hierarchical Alignment** — *IJCAI 2021* (first author)
- **SinLane: Siamese Visual Transformer via Pyramid Feature Integration for Lane Detection** — *ECAI 2024*
- **IFPNet: Integrated Feature Pyramid Network with Fusion Factor for Lane Detection** — *ICCV Workshop 2023*
- **PR-Net: Preference Reasoning for Personalized Video Highlight Detection** — *ICCV 2021*
- **Interactive Few-Shot Learning: Limited Supervision, Better Medical Image Segmentation** — *IEEE TMI 2021*
- **Temporal Structured Illumination and Vision-Transformer for Binary Snapshot Ptychography** — *Optics Express 2023*
- **Propagation Dynamics of a Spatiotemporal Vortex Pulse in the Spatial Fractional System** — *Photonics Research 2024*
- **FlowTrain: Flow-Based Decoupled Training for Industrial-Grade Vision-Language Models** — *arXiv 2026*

📖 Full publication list: [Google Scholar](https://scholar.google.com/citations?user=J4b99-cAAAAJ)

## 💻 Open Source

I'm an active contributor to several open-source AI training frameworks:

### VeOmni — Scaling Any Modality Model Training
Part of the core development team for [ByteDance-Seed/VeOmni](https://github.com/ByteDance-Seed/VeOmni), a model-centric distributed training recipe zoo.

Key contributions:
- **Packed ChunkMBS support** with sequence & expert parallelism
- **Qwen3-VL FSDP2** with torch.compile integration
- **Qwen3.5 dense & ChunkMBS** training support
- **HSDP all-reduce** control for custom trainers
- **Training-time validation** with distributed metric aggregation
- **NPU training** validation pipeline

### verl / verl-omni — RL Post-Training
Contributing to [verl-project/verl](https://github.com/verl-project/verl) and [verl-project/verl-omni](https://github.com/verl-project/verl-omni), multimodal RL training frameworks.

Key contributions:
- **Batched reward inference** (CLAP, PickScore) for diffusion models
- **Diffusion rollout** async semantics preservation & group refilling
- **Rollout-train consistency** monitoring
- **VLM LoRA** support with FSDP for full-rank modules
- **DisRM** reward score extra info handling

## 🛠️ Tech Stack

```
Languages      Python · C++ · CUDA · Shell
Frameworks     PyTorch · VeOmni · verl · FSDP/FSDP2 · DeepSpeed
Distributed    DDP · HSDP · FSDP · Tensor Parallel · Expert Parallel · ChunkMBS
Infrastructure Slurm · Ray · wandb · Docker
Vision/RL       Diffusion Models · VLMs · Video Retrieval · Medical Imaging
```

## 📊 GitHub Stats

<p>
  <a href="https://github.com/WenZheWang?tab=overview&from=2026-01-01&to=2026-12-31">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=WenZheWang&show_icons=true&theme=default&count_private=true&hide_title=true" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/WenZheWang?tab=overview&from=2026-01-01&to=2026-12-31">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=WenZheWang&layout=compact&theme=default&hide_title=true" alt="Top Languages" />
  </a>
</p>

## 📫 Connect

- 📧 Email: w_wenzhe@163.com
- 🎓 Google Scholar: [profile](https://scholar.google.com/citations?user=J4b99-cAAAAJ)
- 🏠 Location: Hangzhou, China

---

<sub>💫 "From research papers to production training frameworks — bridging the gap between algorithms and infrastructure."</sub>
