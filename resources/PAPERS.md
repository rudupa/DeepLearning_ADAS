# 📄 Key Research Papers for Deep Learning in ADAS

Organized by topic with direct links. Start with ⭐ papers — they're the most important.

---

## 🏗️ CNN Architectures

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 1998 | ⭐ [LeNet-5](http://yann.lecun.com/exdb/lenet/) — LeCun et al. | First successful CNN |
| 2012 | ⭐ [AlexNet](https://papers.nips.cc/paper/2012/hash/c399862d3b9d6b76c8436e924a68c45b-Abstract.html) — Krizhevsky et al. | Deep CNN revolution, ImageNet |
| 2014 | [VGGNet](https://arxiv.org/abs/1409.1556) — Simonyan & Zisserman | Deeper is better (3×3 convolutions) |
| 2014 | ⭐ [GoogLeNet/Inception](https://arxiv.org/abs/1409.4842) — Szegedy et al. | Inception modules, efficient |
| 2015 | ⭐ [ResNet](https://arxiv.org/abs/1512.03385) — He et al. | Skip connections, very deep networks |
| 2017 | [DenseNet](https://arxiv.org/abs/1608.06993) — Huang et al. | Dense connections |
| 2019 | [EfficientNet](https://arxiv.org/abs/1905.11946) — Tan & Le | Compound scaling |

---

## 🎯 Object Detection

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2014 | [R-CNN](https://arxiv.org/abs/1311.2524) — Girshick et al. | Region-based detection |
| 2015 | ⭐ [Fast R-CNN](https://arxiv.org/abs/1504.08083) — Girshick | Shared computation |
| 2015 | ⭐ [Faster R-CNN](https://arxiv.org/abs/1506.01497) — Ren et al. | Region Proposal Networks |
| 2016 | ⭐ [SSD](https://arxiv.org/abs/1512.02325) — Liu et al. | Single-shot, multi-scale |
| 2016 | ⭐ [YOLO](https://arxiv.org/abs/1506.02640) — Redmon et al. | Real-time detection |
| 2017 | [Feature Pyramid Networks](https://arxiv.org/abs/1612.03144) — Lin et al. | Multi-scale features |
| 2020 | ⭐ [DETR](https://arxiv.org/abs/2005.12872) — Carion et al. | Transformer-based detection |
| 2022 | [DINO](https://arxiv.org/abs/2203.03605) — Zhang et al. | Deformable DETR improvements |
| 2023 | [Grounding DINO](https://arxiv.org/abs/2303.05499) | Open-vocabulary detection |

---

## 🔄 Sequence Models (RNN/LSTM)

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 1997 | ⭐ [LSTM](https://www.bioinf.jku.at/publications/older/2604.pdf) — Hochreiter & Schmidhuber | Long Short-Term Memory |
| 2014 | [GRU](https://arxiv.org/abs/1406.1078) — Cho et al. | Simplified gating mechanism |
| 2014 | ⭐ [Seq2Seq](https://arxiv.org/abs/1409.3215) — Sutskever et al. | Encoder-decoder architecture |

---

## ⚡ Transformers & Attention

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2015 | [Bahdanau Attention](https://arxiv.org/abs/1409.0473) — Bahdanau et al. | Attention mechanism |
| 2017 | ⭐ [Attention Is All You Need](https://arxiv.org/abs/1706.03762) — Vaswani et al. | The Transformer |
| 2018 | ⭐ [BERT](https://arxiv.org/abs/1810.04805) — Devlin et al. | Bidirectional pre-training |
| 2020 | ⭐ [ViT](https://arxiv.org/abs/2010.11929) — Dosovitskiy et al. | Vision Transformer |
| 2021 | [Swin Transformer](https://arxiv.org/abs/2103.14030) — Liu et al. | Hierarchical vision transformer |
| 2021 | [DeiT](https://arxiv.org/abs/2012.12877) — Touvron et al. | Data-efficient ViT training |

---

## 🗣️ Large Language Models

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2018 | [GPT](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf) — Radford et al. | Generative pre-training |
| 2019 | [GPT-2](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf) | Larger scale, zero-shot |
| 2020 | ⭐ [GPT-3](https://arxiv.org/abs/2005.14165) — Brown et al. | In-context learning, few-shot |
| 2022 | ⭐ [InstructGPT](https://arxiv.org/abs/2203.02155) — Ouyang et al. | RLHF, instruction following |
| 2023 | ⭐ [LLaMA](https://arxiv.org/abs/2302.13971) — Touvron et al. | Open-source foundation model |
| 2023 | [LLaMA 2](https://arxiv.org/abs/2307.09288) — Touvron et al. | Improved open-source LLM |
| 2024 | [LLaMA 3](https://arxiv.org/abs/2407.21783) — Meta | State-of-the-art open LLM |

### Efficient Fine-Tuning
| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2021 | ⭐ [LoRA](https://arxiv.org/abs/2106.09685) — Hu et al. | Low-rank adaptation |
| 2023 | [QLoRA](https://arxiv.org/abs/2305.14314) — Dettmers et al. | Quantized LoRA |

---

## 👁️ Vision-Language Models (VLMs)

| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2021 | ⭐ [CLIP](https://arxiv.org/abs/2103.00020) — Radford et al. | Contrastive image-text learning |
| 2022 | [BLIP](https://arxiv.org/abs/2201.12086) — Li et al. | Bootstrapping language-image |
| 2023 | ⭐ [BLIP-2](https://arxiv.org/abs/2301.12597) — Li et al. | Q-Former, efficient VLM |
| 2023 | ⭐ [LLaVA](https://arxiv.org/abs/2304.08485) — Liu et al. | Visual instruction tuning |
| 2023 | [LLaVA-1.5](https://arxiv.org/abs/2310.03744) — Liu et al. | Improved visual LLM |
| 2024 | [LLaVA-NeXT](https://arxiv.org/abs/2310.03744) — Liu et al. | High-res, multi-image |

---

## 🚗 Autonomous Driving & ADAS

### Perception
| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2017 | ⭐ [PointNet](https://arxiv.org/abs/1612.00593) — Qi et al. | Direct 3D point cloud processing |
| 2019 | [PointPillars](https://arxiv.org/abs/1812.05784) — Lang et al. | Fast 3D detection from LiDAR |
| 2020 | [CenterPoint](https://arxiv.org/abs/2006.11275) — Yin et al. | Center-based 3D detection |
| 2022 | ⭐ [BEVFormer](https://arxiv.org/abs/2203.17270) — Li et al. | BEV from multi-camera |
| 2022 | [BEVFusion](https://arxiv.org/abs/2205.13542) — Liu et al. | Multi-sensor BEV fusion |

### End-to-End Driving
| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2016 | ⭐ [NVIDIA PilotNet](https://arxiv.org/abs/1604.07316) | First E2E driving CNN |
| 2019 | [ChauffeurNet](https://arxiv.org/abs/1812.03079) — Waymo | Mid-level E2E approach |
| 2022 | [InterFuser](https://arxiv.org/abs/2207.14024) — Shao et al. | Multi-sensor transformer |
| 2023 | ⭐ [UniAD](https://arxiv.org/abs/2212.10156) — Hu et al. | Unified autonomous driving |
| 2024 | [VAD](https://arxiv.org/abs/2303.12077) — Jiang et al. | Vectorized scene representation |
| 2024 | ⭐ [EMMA](https://arxiv.org/abs/2410.23262) — Waymo | End-to-end multimodal model |

### VLAs for Driving
| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2023 | ⭐ [RT-2](https://arxiv.org/abs/2307.15818) — Google | Robotic transformer with VLM |
| 2023 | [DriveGPT4](https://arxiv.org/abs/2310.01415) | GPT-4 for driving |
| 2024 | [LMDrive](https://arxiv.org/abs/2312.07488) | Language-guided driving |
| 2024 | ⭐ [OpenVLA](https://arxiv.org/abs/2406.09246) — Stanford | Open-source VLA |
| 2024 | [DriveVLM](https://arxiv.org/abs/2402.12289) | VLM for driving planning |

### Lane Detection
| Year | Paper | Key Contribution |
|------|-------|-----------------|
| 2019 | [LaneNet](https://arxiv.org/abs/1802.05591) | Instance lane segmentation |
| 2020 | [Ultra-Fast Lane Detection](https://arxiv.org/abs/2004.11757) | Row-based formulation |
| 2022 | [CLRNet](https://arxiv.org/abs/2203.10350) | Cross-layer refinement |

---

## 📖 How to Read Research Papers

1. **First pass (5 min):** Read title, abstract, figures, and conclusion
2. **Second pass (30 min):** Read introduction, method overview, and results
3. **Third pass (2+ hours):** Read everything, reproduce key equations
4. **Implementation:** Try to code the key ideas in PyTorch

### Tips
- Start with ⭐ papers — they're the most influential
- Read survey papers first for topic overviews
- Use [Papers With Code](https://paperswithcode.com/) for implementations
- Use [Semantic Scholar](https://www.semanticscholar.org/) to find related work
- Follow top conferences: **CVPR, ICCV, ECCV, NeurIPS, ICML, ICLR**

---

*Last updated: 2025*
