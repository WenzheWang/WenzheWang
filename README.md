# Hi, I'm Wenzhe Wang 👋

I work on **AI systems and multimodal RL post-training**, with a research background in computer vision and computational imaging and a PhD from Zhejiang University.

I'm an **Active Committer of [verl-omni](https://github.com/verl-project/verl-omni)** and a co-owner of its `verl_omni/trainer/` module, as listed in the [official governance](https://github.com/verl-project/verl-omni/blob/main/docs/community/governance.md#active-committers). I also contribute to [VeOmni](https://github.com/ByteDance-Seed/VeOmni), [TileLang](https://github.com/tile-ai/tilelang), and [verl](https://github.com/verl-project/verl).

## Open-source work

My engineering focus spans three connected areas:

- **Multimodal RL systems** — reward scheduling, batched reward inference, and rollout–training integration.
- **Distributed training and reliability** — FSDP2/HSDP, packing and memory management, failure propagation, and reproducible validation.
- **Accelerator and kernel tooling** — Ascend/NPU enablement, Triton operators, and TileLang autotuning observability.

### Selected merged contributions

| Project | Contribution |
| --- | --- |
| verl-omni | [Native reward replica scheduling #677](https://github.com/verl-project/verl-omni/pull/677) |
| verl-omni | [Retain PickScore weights on CPU during sleep #708](https://github.com/verl-project/verl-omni/pull/708) |
| verl-omni | [Propagate IPC weight-update failures #735](https://github.com/verl-project/verl-omni/pull/735) and [preserve inherited adapter transport checks #758](https://github.com/verl-project/verl-omni/pull/758) |
| verl-omni | [Qwen3-Omni Thinker DAPO phase one #456](https://github.com/verl-project/verl-omni/pull/456) |
| VeOmni | [Ascend Triton clamped SwiGLU #1104](https://github.com/ByteDance-Seed/VeOmni/pull/1104) and [packed ChunkMBS support #898](https://github.com/ByteDance-Seed/VeOmni/pull/898) |
| TileLang | [Structured autotuning trial reporting #3393](https://github.com/tile-ai/tilelang/pull/3393) |

<details>
<summary>Earlier contributions</summary>

- **verl-omni:** [Batched CLAP reward inference #367](https://github.com/verl-project/verl-omni/pull/367), [strip responses from worker batches #430](https://github.com/verl-project/verl-omni/pull/430), [reject silent fallbacks #429](https://github.com/verl-project/verl-omni/pull/429), and [batched PickScore inference #346](https://github.com/verl-project/verl-omni/pull/346).
- **VeOmni:** [Qwen3-VL FSDP2 torch compile #1009](https://github.com/ByteDance-Seed/VeOmni/pull/1009), [HSDP all-reduce control #1026](https://github.com/ByteDance-Seed/VeOmni/pull/1026), and [deterministic mapping cycles #1045](https://github.com/ByteDance-Seed/VeOmni/pull/1045).
- **verl:** [FSDP and SkyPilot guide updates #7185](https://github.com/verl-project/verl/pull/7185).
- **TileLang:** [Validate T.gemm k_pack arguments #3094](https://github.com/tile-ai/tilelang/pull/3094).

</details>

## Research

My research interests include distributed training systems, vision-language models, and computational imaging.

### Selected publications

- **[Dig into Multi-modal Cues for Video Retrieval with Hierarchical Alignment](https://doi.org/10.24963/ijcai.2021/154)** — *IJCAI 2021* (first author)
- **[FlowTrain: Flow-Based Decoupled Training for Industrial-Grade Vision-Language Models](https://arxiv.org/abs/2606.23087)** — *EMNLP 2026* (co-author)
- **[A Siamese Transformer with Hierarchical Refinement for Lane Detection](https://doi.org/10.52202/079017-1293)** — *NeurIPS 2024*
- **[PR-Net: Preference Reasoning for Personalized Video Highlight Detection](https://arxiv.org/abs/2109.01799)** — *ICCV 2021*
- **[Interactive Few-Shot Learning: Limited Supervision, Better Medical Image Segmentation](https://doi.org/10.1109/TMI.2021.3060551)** — *IEEE TMI 2021*

<details>
<summary>More publications</summary>

- **[SinLane: Siamese Visual Transformer via Pyramid Feature Integration for Lane Detection](https://doi.org/10.3233/FAIA240481)** — *ECAI 2024*
- **[IFPNet: Integrated Feature Pyramid Network with Fusion Factor for Lane Detection](https://doi.org/10.1109/ICCVW60793.2023.00203)** — *ICCV Workshop 2023*
- **[Temporal Structured Illumination and Vision-Transformer Enables Large Field-of-View Binary Snapshot Ptychography](https://doi.org/10.1364/OE.504721)** — *Optics Express 2024*
- **[Propagation Dynamics of a Spatiotemporal Vortex Pulse in the Spatial Fractional System](https://doi.org/10.1364/PRJ.529463)** — *Photonics Research 2024*

</details>

[Full publication list on Google Scholar](https://scholar.google.com/citations?user=J4b99-cAAAAJ)

## Tools I work with

Python · C++ · CUDA · PyTorch · FSDP2/HSDP · Ray · Triton · TileLang · Ascend/NPU · Slurm · Docker

## Connect

- Email: w_wenzhe[AT]163.com
- Location: Hangzhou, China
