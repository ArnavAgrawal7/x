# Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange)](CONTRIBUTING.md)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202025-red)](https://github.com/yourusername/VLM-Medical-Imaging-Survey)

</div>

> A curated collection of papers on **Vision–Language Models (VLMs) for Medical Imaging**, covering Medical VQA, Report Generation, Foundation Models, and Segmentation. All papers post-2023 from top venues.

---

## 📌 Table of Contents

- [Survey Papers](#-survey-papers)
- [Medical VQA](#-medical-vqa)
  - [Closed-Ended VQA](#closed-ended-vqa)
  - [Open-Ended VQA](#open-ended--generative-vqa)
  - [Region-Grounded VQA](#region-grounded-vqa)
  - [Hallucination & Robustness](#hallucination--robustness)
- [Report Generation](#-report-generation)
- [Foundation Models](#-foundation-models)
  - [Pre-training](#pre-training-strategies)
  - [Fine-tuning & PEFT](#fine-tuning--peft)
  - [Zero/Few-Shot](#zerofew-shot)
- [Datasets & Benchmarks](#-datasets--benchmarks)
- [Evaluation Metrics](#-evaluation-metrics)
- [Open Challenges](#-open-challenges)
- [Citation](#-citation)

---

## 🗺️ Taxonomy

```
Vision–Language Models for Medical Imaging
│
├── 1. Survey & Review Papers
├── 2. Medical VQA
│   ├── 2.1 Closed-ended (Yes/No, Multiple Choice)
│   ├── 2.2 Open-ended (Generative)
│   ├── 2.3 Region/Grounded VQA
│   └── 2.4 Hallucination & Robustness
├── 3. Report Generation
│   ├── 3.1 Radiology (X-ray, CT, MRI)
│   └── 3.2 Pathology
├── 4. Foundation Models
│   ├── 4.1 Pre-training Strategies
│   ├── 4.2 Fine-tuning & PEFT
│   └── 4.3 Zero/Few-shot
└── 5. Datasets & Benchmarks
```

---

## 📄 Survey Papers

**[Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review](https://doi.org/10.3389/frai.2024.1430984)** [Frontiers in AI, 2024]  
Iryna Hartsock, Ghulam Rasool  
*Covers 18 public datasets and in-depth analysis of 16 recent medical VLMs*

---

**[A Survey of Medical Vision-and-Language Applications and Their Techniques](https://arxiv.org/abs/2411.12195)** [arXiv, 2024]  
Qi Chen et al.  
*Covers report generation, VQA, segmentation, diagnosis, and image-text retrieval*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com)

---

**[Vision-Language Models in Medicine](https://arxiv.org/abs/2503.01863)** [arXiv, 2025]  
Beria Chingnabe Kalpelbe, Angel Gabriel Adaambiik, Wei Peng  
*Reviews foundational technology, clinical applications, and key ethical challenges*

---

**[Vision-Language Models in Medical Image Analysis: From Simple Fusion to General Large Models](https://doi.org/10.1016/j.inffus.2025.102995)** [Information Fusion, Elsevier Q1, 2025]  
*Reviews 130+ papers spanning simple fusion to large-scale foundation models*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com)

---

**[Vision-Language Foundation Model for 3D Medical Imaging](https://www.nature.com/articles/s44387-025-00015-9)** [npj Artificial Intelligence, Nature Portfolio, 2025]  
*Reviews 23 studies on VLFMs for 3D medical imaging — CT and MRI*

---

**[Large Language Model for Medical Images: A Survey of Taxonomy, Systematic Review, and Future Trends](https://doi.org/10.26599/BDMA.2024.9020090)** [Big Data Mining and Analytics, 2025]  
*Introduces novel x-stage tuning paradigm: zero-stage, one-stage, and multi-stage*

---

**[Vision-Language Foundation Models for Medical Imaging: A Review (2022–2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12411343/)** [PMC / NIH, 2024]  
*Structured taxonomy across X-ray, MRI, CT, and pathology modalities*

---

**[LViT: Language Meets Vision Transformer in Medical Image Segmentation](https://arxiv.org/abs/2206.14718)** [IEEE Transactions on Medical Imaging, Vol.43(1), 2024]  
Zhuoran Li, Zhiyuan Li, Fenglong Ma, Luping Zhou, Jing Zhang  
*First work integrating text annotations with vision transformer for medical image segmentation*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/HUANGLIZI/LViT)

---

## 🧠 Medical VQA

### Closed-Ended VQA

**[Prompting Medical Large Vision-Language Models to Diagnose Pathologies by Visual Question Answering](https://arxiv.org/abs/2407.21368)** [arXiv, 2024]  
Danfeng Guo, Demetri Terzopoulos  
*Modality: Chest X-Ray | Prompting strategies for closed-ended diagnostic VQA*

---

**[GeMeX: A Large-Scale, Groundable, Explainable Medical VQA Benchmark](https://arxiv.org/abs/2411.16778)** [arXiv, 2024]  
*Modality: Chest X-Ray | Large-scale grounded and explainable Med-VQA benchmark*

---

**[SLAKE: Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering](https://arxiv.org/abs/2102.09542)** [IEEE ISBI, 2021]  
Bo Liu et al.  
*Modality: Multi-modal | 14,000 bilingual QA pairs with semantic labels*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/Med-VQA/SLAKE)

---

### Open-Ended / Generative VQA

**[Targeted Visual Prompting for Medical Visual Question Answering](https://arxiv.org/abs/2408.03043)** [arXiv, 2024]  
*Modality: Radiology | Region-targeted prompting strategy for open-ended clinical VQA*

---

**[AMANDA: Agentic Medical Knowledge Augmentation for Visual Question Answering](https://aclanthology.org/2025.findings-emnlp.1350.pdf)** [EMNLP Findings, 2025]  
*Modality: Multi-modal | Agentic reasoning with knowledge retrieval for Med-VQA*

---

**[PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering](https://arxiv.org/abs/2305.10415)** [arXiv, 2023]  
Xiaoman Zhang et al.  
*Modality: Multi-modal | 227K QA pairs constructed from PubMed Central*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/xiaoman-zhang/PMC-VQA)

---

### Region-Grounded VQA

**[HEAL-MedVQA: Hallucination Evaluation via Localization in Medical VQA](https://arxiv.org/abs/2505.00744)** [arXiv, 2025]  
*Modality: Radiology | 67K QA pairs with spatial grounding and hallucination evaluation*

---

**[MIMO: A Medical Vision Language Model with Visual Referring Multimodal Input and Pixel Grounding Output](https://arxiv.org/abs/2510.10011)** [CVPR 2025, pp.24732–24741]  
*Modality: Multi-organ | First model enabling pixel-level grounding output for medical VQA*

---

**[Dual Modality Prompt Learning for Visual Question Answering in Robotic Surgery](https://doi.org/10.1007/s42979-024-02705-4)** [Visual Computing, 2024]  
*Modality: Surgical endoscopy | Dual-branch prompt learning for surgical scene understanding*

---

### Hallucination & Robustness

**[Prompting Strategies to Reduce Hallucination in Multimodal Large Vision-Language Models](https://arxiv.org/abs/2407.21368)** [arXiv, 2025]  
*Systematic study on reducing hallucinated clinical findings in Med-VLMs*

---

**[How Easy Is It to Fool Your Multimodal LLMs? An Empirical Analysis on Deceptive Prompts](https://arxiv.org/abs/2402.13220)** [arXiv, 2024]  
*Robustness evaluation of multimodal LLMs under adversarial and deceptive prompting*

---

## 📝 Report Generation

**[R2GenGPT: Radiology Report Generation with Frozen Large Language Models](https://arxiv.org/abs/2309.09812)** [arXiv, 2023]  
Zhanyu Wang et al.  
*Modality: Chest X-ray | Frozen LLM with lightweight visual adapter for report generation*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/wang-zhanyu/R2GenGPT)

---

**[BioViL-T: Learning to Follow Instructions for Radiology Report Summarisation](https://arxiv.org/abs/2301.04558)** [MICCAI 2023]  
Bannur et al.  
*Modality: Chest X-ray | Temporal chest X-ray understanding with language grounding*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/microsoft/hi-ml/tree/main/hi-ml-multimodal)

---

**[CheXagent: Towards a Foundation Model for Chest X-Ray Analysis](https://arxiv.org/abs/2401.12208)** [arXiv, 2024]  
Zhihong Chen et al.  
*Modality: Chest X-ray | Instruction-following foundation model for radiology*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/Stanford-AIMI/CheXagent)

---

**[Enhancing Vision-Language Models for Medical Imaging (BrainMD + Vote-MI)](https://proceedings.neurips.cc/paper_files/paper/2024/file/b53513b83232116ae25f57a174a7c993-Paper-Datasets_and_Benchmarks_Track.pdf)** [NeurIPS 2024, Datasets & Benchmarks Track]  
*Modality: Brain MRI | Vote-MI slice selection + BrainMD dataset (2,453 annotated 3D MRI scans)*

---

**[SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding](https://arxiv.org/abs/2410.11761)** [CVPR 2025, pp.5134–5143]  
Ying Chen et al.  
*Modality: Pathology WSI | First conversational assistant for gigapixel whole-slide images*

---

**[CheXWorld: Exploring Image World Modeling for Radiograph Representation Learning](https://arxiv.org/abs/2504.13820)** [CVPR 2025]  
*Modality: Chest X-ray | World model-based self-supervised pre-training for radiology*

---

## 🏗️ Foundation Models

### Pre-training Strategies

**[BioMedCLIP: A Multimodal Biomedical Foundation Model Pretrained from Fifteen Million Scientific Image-Text Pairs](https://arxiv.org/abs/2303.00915)** [arXiv, 2023]  
Sheng Zhang et al.  
*PMC-15M dataset — 15M biomedical image-text pairs from 4.4M scientific articles*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/microsoft/BiomedCLIP)

---

**[PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents](https://arxiv.org/abs/2303.07240)** [MICCAI 2023]  
Weixiong Lin et al.  
*PMC-OA dataset — 1.65M image-caption pairs from PubMed Central*

---

**[PubMedCLIP: How Much Does CLIP Benefit Visual Question Answering in the Medical Domain?](https://arxiv.org/abs/2112.13906)** [EACL Findings, 2023]  
Sedigheh Eslami et al.  
*Fine-tuned CLIP on PubMed medical image-text data for Med-VQA improvement*

---

**[LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day](https://arxiv.org/abs/2306.00890)** [NeurIPS 2023]  
Chunyuan Li et al.  
*Self-instructed biomedical instruction-following data pipeline using GPT-4*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/microsoft/LLaVA-Med)

---

**[VILA-M3: Enhancing Vision-Language Models with Medical Expert Knowledge](https://arxiv.org/abs/2411.12915)** 🏆 [CVPR 2025 Highlight, pp.14788–14798]  
Vishwesh Nath et al.  
*Integrates structured medical expert knowledge into general VLMs for clinical tasks*

---

### Fine-tuning & PEFT

**[PeFoMed: Parameter Efficient Fine-Tuning on Multimodal Large Language Models for Medical Visual Question Answering](https://arxiv.org/abs/2401.02797)** [arXiv, 2024]  
Jinlong He et al.  
*Lightweight adapter tuning of LLaVA-style models for Med-VQA*

---

**[Med-MoE: Mixture of Domain-Specific Experts for Medical Image Understanding](https://arxiv.org/abs/2404.10237)** [arXiv, 2024]  
*Sparse mixture-of-experts architecture for multi-domain medical image understanding*

---

**[BioMedGPT: Open Multimodal Generative Pre-trained Transformer for BioMedicine](https://arxiv.org/abs/2308.09442)** [arXiv, 2023]  
Yizhen Luo et al.  
*Unified generative pre-training across biomedical text, molecules, and images*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/PharMolix/OpenBioMed)

---

### Zero/Few-Shot

**[Med-Flamingo: A Multimodal Medical Few-shot Learner](https://arxiv.org/abs/2307.15189)** [arXiv, 2023]  
Michael Moor et al.  
*Extends Flamingo to the medical domain with few-shot generalization across imaging tasks*

[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/snap-stanford/med-flamingo)

---

**[T3D: Towards 3D Medical Image Understanding through Vision-Language Pre-training](https://arxiv.org/abs/2312.01529)** [arXiv, 2023]  
Che Liu et al.  
*First VL pre-training framework designed for volumetric 3D medical images*

---

## 📊 Datasets & Benchmarks

| Dataset | Year | Size | Task | Modality |
|---------|------|------|------|----------|
| [VQA-RAD](https://osf.io/89kps/) | 2018 | 3,515 QA pairs | Closed/Open VQA | Radiology |
| [SLAKE](https://www.med-vqa.com/slake/) | 2021 | 14,000 QA pairs | Bilingual VQA | Multi-modal |
| [PathVQA](https://github.com/UCSD-AI4H/PathVQA) | 2020 | 32,799 QA pairs | VQA | Pathology |
| [PMC-VQA](https://arxiv.org/abs/2305.10415) | 2023 | 227K QA pairs | Open VQA | Multi-modal |
| [GeMeX](https://arxiv.org/abs/2411.16778) | 2024 | Large-scale | Grounded VQA | CXR |
| [HEAL-MedVQA](https://arxiv.org/abs/2505.00744) | 2025 | 67K QA pairs | Grounded + Hallucination | CXR/Radiology |
| [BrainMD](https://proceedings.neurips.cc/) | 2024 | 2,453 MRI scans | VQA + Reports | Brain MRI |
| [MIMIC-CXR-JPG](https://physionet.org/content/mimic-cxr-jpg/) | 2019 | 227K images | Report Gen + VQA | CXR |
| [CheXpert](https://stanfordmlgroup.github.io/competitions/chexpert/) | 2019 | 224K images | Classification + VQA | CXR |

---

## 📏 Evaluation Metrics

| Metric | Task | Description |
|--------|------|-------------|
| **BLEU** | Report Gen / VQA | N-gram overlap between generated and reference text |
| **ROUGE-L** | Report Gen | Longest common subsequence recall |
| **CIDEr** | Report Gen | Consensus-based image description evaluation |
| **Accuracy** | Closed VQA | Exact match for Yes/No and MCQ |
| **F1 Score** | Med-VQA | Harmonic mean of Precision & Recall |
| **AUC-ROC** | Classification | Area under ROC curve |
| **METEOR** | Report Gen | Alignment-based metric with synonym awareness |
| **RadGraph F1** | Radiology Reports | Clinical entity-based evaluation |

---

## 🔓 Open Challenges

1. **Hallucination** — Models generate plausible but clinically incorrect answers
2. **Data Scarcity** — Limited annotated medical VQA datasets
3. **Generalization** — Models fail to generalize across imaging modalities
4. **Interpretability** — Black-box predictions are not clinically trustworthy
5. **Privacy & Ethics** — Patient data compliance (HIPAA, GDPR)
6. **3D Understanding** — Most VLMs are 2D; 3D MRI/CT remains challenging
7. **Evaluation Gap** — Standard NLP metrics poorly reflect clinical quality

---

## 📈 Trend Summary (2023–2025)

```
2023  →  Foundation models established: LLaVA-Med, Med-Flamingo, BioMedCLIP, LViT
2024  →  Instruction tuning, PEFT, grounded VQA, hallucination research, IEEE TMI VLP
2025  →  CVPR highlights (VILA-M3, MIMO, SlideChat), agentic VQA, 3D imaging VLMs
```

---

## 📖 Citation

```bibtex
@article{yourlastname2025vlm_medical_survey,
  title   = {Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey},
  author  = {Your Name},
  journal = {arXiv preprint},
  year    = {2025},
  url     = {https://github.com/yourusername/VLM-Medical-Imaging-Survey}
}
```

---

## 🤝 Contributing

1. Fork this repo
2. Add paper in the existing style: **[Title](link)** [Venue, Year] — Authors — Description
3. Submit a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

## 📬 Contact

Maintained by **[Your Name]**  
📧 your.email@institution.edu  
🔗 [Google Scholar](https://scholar.google.com) | [ResearchGate](https://researchgate.net)

---

<div align="center">
⭐ <b>Star this repo</b> if you find it useful! ⭐
</div>
