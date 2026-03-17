# x

# Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Paper](https://img.shields.io/badge/Paper-Survey-blue)](https://arxiv.org/abs/2403.02469)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/yourusername/VLM-Medical-Imaging-Survey?style=social)](https://github.com/yourusername/VLM-Medical-Imaging-Survey)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2025-red)](https://github.com/yourusername/VLM-Medical-Imaging-Survey)

</div>

> A curated and structured collection of resources on **Vision–Language Models (VLMs) for Medical Imaging**, with a focus on Medical Visual Question Answering (Med-VQA), Report Generation, Segmentation, and Foundation Models.  
> Papers are sourced from top venues: **IEEE TMI, NeurIPS, CVPR, ECCV, MICCAI, Frontiers in AI, arXiv** (post-2023).

---

## 📌 Table of Contents

- [Survey Papers](#-survey-papers)
- [Medical VQA](#-medical-vqa)
- [Report Generation](#-report-generation)
- [Foundation Models](#-foundation-models)
- [Datasets & Benchmarks](#-datasets--benchmarks)
- [Evaluation Metrics](#-evaluation-metrics)
- [Open Challenges](#-open-challenges)
- [Citation](#-citation)
- [Contributing](#-contributing)

---

## 🗺️ Taxonomy Overview

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

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review | Frontiers in AI | 2024 | [Paper](https://doi.org/10.3389/frai.2024.1430984) |
| A Survey of Medical Vision-and-Language Applications and Their Techniques | arXiv:2411.12195 | 2024 | [Paper](https://arxiv.org/abs/2411.12195) |
| Vision-Language Models in Medicine | arXiv:2503.01863 | 2025 | [Paper](https://arxiv.org/abs/2503.01863) |
| Vision-Language Models in Medical Image Analysis: From Simple Fusion to General Large Models | Information Fusion (Elsevier Q1) | 2025 | [Paper](https://doi.org/10.1016/j.inffus.2025.102995) |
| Vision-Language Foundation Model for 3D Medical Imaging | npj AI (Nature) | 2025 | [Paper](https://www.nature.com/articles/s44387-025-00015-9) |
| Large Language Model for Medical Images: A Survey of Taxonomy | Big Data Mining and Analytics | 2025 | [Paper](https://doi.org/10.26599/BDMA.2024.9020090) |
| Vision-Language Foundation Models for Medical Imaging (2022–2024) | PMC/NIH | 2024 | [Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC12411343/) |

---

## 🧠 Medical VQA

### 2.1 Closed-Ended VQA (Classification-style)

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| Prompting Medical LVLMs to Diagnose Pathologies by VQA | arXiv:2407.21368 | 2024/2025 | CXR | [Paper](https://arxiv.org/abs/2407.21368) |
| GeMeX: A Large-Scale, Groundable, Explainable Med-VQA Benchmark | arXiv:2411.16778 | 2024 | Chest X-Ray | [Paper](https://arxiv.org/abs/2411.16778) |
| SLAKE: Semantically-Labeled Knowledge-Enhanced Dataset for Med-VQA | IEEE ISBI | 2021 | Multi-modal | [Paper](https://arxiv.org/abs/2102.09542) |

### 2.2 Open-Ended / Generative VQA

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| Targeted Visual Prompting for Medical VQA | arXiv:2408.03043 | 2024 | Radiology | [Paper](https://arxiv.org/abs/2408.03043) |
| AMANDA: Agentic Medical Knowledge Augmentation for VQA | EMNLP Findings | 2025 | Multi-modal | [Paper](https://aclanthology.org/2025.findings-emnlp.1350.pdf) |
| PMC-VQA: Visual Instruction Tuning for Medical VQA | arXiv | 2023 | Multi-modal | [Paper](https://arxiv.org/abs/2305.10415) |

### 2.3 Region-Grounded VQA

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| HEAL-MedVQA: Hallucination Evaluation via Localization | arXiv:2505.00744 | 2025 | Radiology | [Paper](https://arxiv.org/abs/2505.00744) |
| Localizing Before Answering: LobA Framework | arXiv | 2025 | CXR/Pathology | [Paper](https://arxiv.org/abs/2505.00744) |
| Dual Modality Prompt Learning for VQA in Robotic Surgery | Visual Computing | 2024 | Surgical | [Paper](https://doi.org/10.1007/s42979-024-02705-4) |

### 2.4 Hallucination & Robustness in Med-VQA

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| Prompting Strategies to Reduce Hallucination in MLVLMs | arXiv:2407.21368 | 2025 | [Paper](https://arxiv.org/abs/2407.21368) |
| How Easy Is It to Fool Your Multimodal LLMs? | arXiv:2402.13220 | 2024 | [Paper](https://arxiv.org/abs/2402.13220) |

---

## 📝 Report Generation

| Title | Venue | Year | Modality | Links |
|-------|-------|------|----------|-------|
| R2GenGPT: Radiology Report Generation with Frozen LLMs | arXiv | 2023 | X-ray | [Paper](https://arxiv.org/abs/2309.09812) |
| BioViL-T: Learning to Follow Instructions in Radiology | MICCAI | 2023 | CXR | [Paper](https://arxiv.org/abs/2301.04558) |
| CheXagent: Towards a Foundation Model for CXR Analysis | arXiv | 2024 | CXR | [Paper](https://arxiv.org/abs/2401.12208) |
| Enhancing VLMs for Medical Imaging (BrainMD + Vote-MI) | NeurIPS | 2024 | Brain MRI | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/b53513b83232116ae25f57a174a7c993-Paper-Datasets_and_Benchmarks_Track.pdf) |

---

## 🏗️ Foundation Models

### Pre-training Strategies

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| BioMedCLIP: Multimodal Biomedical Foundation Model | arXiv:2303.00915 | 2023 | [Paper](https://arxiv.org/abs/2303.00915) |
| PMC-CLIP: Contrastive Pre-training using Biomedical Documents | MICCAI | 2023 | [Paper](https://arxiv.org/abs/2303.07240) |
| PubMedCLIP: How Much Does CLIP Benefit Medical VQA? | EACL Findings | 2023 | [Paper](https://arxiv.org/abs/2112.13906) |
| LLaVA-Med: Training a Large Language-and-Vision Assistant | NeurIPS | 2023 | [Paper](https://arxiv.org/abs/2306.00890) |

### Fine-tuning & PEFT

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| PeFoMed: Parameter Efficient Fine-Tuning of Multimodal LLMs | arXiv | 2024 | [Paper](https://arxiv.org/abs/2401.02797) |
| Med-MoE: Mixture of Domain-Specific Experts | arXiv | 2024 | [Paper](https://arxiv.org/abs/2404.10237) |
| BioMedGPT: Open Multimodal Generative Pre-trained Transformer | arXiv | 2023 | [Paper](https://arxiv.org/abs/2308.09442) |

### Zero/Few-Shot

| Title | Venue | Year | Links |
|-------|-------|------|-------|
| Med-Flamingo: A Multimodal Medical Few-shot Learner | arXiv | 2023 | [Paper](https://arxiv.org/abs/2307.15189) |
| T3D: Towards 3D Medical Image Understanding via VL Pre-training | arXiv:2312.01529 | 2023 | [Paper](https://arxiv.org/abs/2312.01529) |

---

## 📊 Datasets & Benchmarks

| Dataset | Year | Size | Task | Modality | Link |
|---------|------|------|------|----------|------|
| VQA-RAD | 2018 | 3,515 QA pairs | Closed/Open VQA | Radiology | [Link](https://osf.io/89kps/) |
| SLAKE | 2021 | 14,000 QA pairs | Bilingual VQA | Multi-modal | [Link](https://www.med-vqa.com/slake/) |
| PathVQA | 2020 | 32,799 QA pairs | VQA | Pathology | [Link](https://github.com/UCSD-AI4H/PathVQA) |
| PMC-VQA | 2023 | 227K QA pairs | Open VQA | Multi-modal | [Link](https://arxiv.org/abs/2305.10415) |
| GeMeX | 2024 | Large-scale | Grounded VQA | CXR | [Link](https://arxiv.org/abs/2411.16778) |
| HEAL-MedVQA | 2025 | 67K QA pairs | Grounded + Hallucination | CXR/Radiology | [Link](https://arxiv.org/abs/2505.00744) |
| BrainMD | 2024 | 2,453 MRI scans | VQA + Reports | Brain MRI | [Link](https://proceedings.neurips.cc/) |
| MIMIC-CXR-JPG | 2019 | 227K images | Report Gen + VQA | CXR | [Link](https://physionet.org/content/mimic-cxr-jpg/) |
| CheXpert | 2019 | 224K images | Classification + VQA | CXR | [Link](https://stanfordmlgroup.github.io/competitions/chexpert/) |

---

## 📏 Evaluation Metrics

| Metric | Task | Description |
|--------|------|-------------|
| **BLEU** | Report Gen / VQA | N-gram overlap between generated and reference text |
| **ROUGE-L** | Report Gen | Longest common subsequence recall |
| **CIDEr** | Report Gen | Consensus-based image description evaluation |
| **Accuracy** | Closed VQA | Exact match accuracy for Yes/No and MCQ |
| **F1 Score** | Med-VQA | Harmonic mean of Precision & Recall (preferred in clinical VQA) |
| **Precision / Recall** | Diagnosis VQA | Per-pathology clinical accuracy |
| **AUC-ROC** | Classification | Area under ROC curve |
| **METEOR** | Report Gen | Alignment-based metric considering synonyms |
| **RadGraph F1** | Radiology Reports | Clinical entity-based evaluation |

---

## 🔓 Open Challenges

1. **Hallucination** — Models generate plausible but clinically incorrect answers
2. **Data Scarcity** — Limited annotated medical VQA datasets
3. **Generalization** — Models fail to generalize across imaging modalities
4. **Interpretability** — Black-box predictions are not clinically trustworthy
5. **Privacy & Ethics** — Patient data compliance (HIPAA, GDPR)
6. **3D Understanding** — Most VLMs are designed for 2D images; 3D MRI/CT remains challenging
7. **Evaluation Gap** — Standard NLP metrics (BLEU, ROUGE) poorly reflect clinical quality

---

## 📈 Trend Summary (2023–2025)

```
2023  →  Foundation models (LLaVA-Med, Med-Flamingo, BioMedCLIP) established
2024  →  Instruction tuning, PEFT, grounded VQA, hallucination research
2025  →  Agentic reasoning, 3D imaging VLMs, large-scale benchmarks (HEAL-MedVQA)
```

---

## 📖 Citation

If you find this repository useful, please cite:

```bibtex
@article{yourlastname2025vlm_medical_survey,
  title     = {Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey},
  author    = {Your Name},
  journal   = {arXiv preprint},
  year      = {2025},
  url       = {https://github.com/yourusername/VLM-Medical-Imaging-Survey}
}
```

### Key Papers to Cite

```bibtex
@article{hartsock2024vlm,
  title   = {Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review},
  author  = {Hartsock, Iryna and Rasool, Ghulam},
  journal = {Frontiers in Artificial Intelligence},
  volume  = {7},
  year    = {2024},
  doi     = {10.3389/frai.2024.1430984}
}

@article{guo2024prompting,
  title   = {Prompting Medical Large Vision-Language Models to Diagnose Pathologies by Visual Question Answering},
  author  = {Guo, Danfeng and Terzopoulos, Demetri},
  journal = {arXiv preprint arXiv:2407.21368},
  year    = {2024}
}

@inproceedings{neurips2024brainmd,
  title     = {Enhancing Vision-Language Models for Medical Imaging},
  booktitle = {NeurIPS 2024 Datasets and Benchmarks Track},
  year      = {2024}
}
```

---

## 🤝 Contributing

We welcome contributions! If you know of a paper that should be included:

1. Fork this repo
2. Add the paper to the relevant section in `README.md` following the existing format
3. Submit a Pull Request with a short description

Please see [CONTRIBUTING.md](CONTRIBUTING.md) for full guidelines.

---

## 📬 Contact

Maintained by **[Your Name]**  
📧 your.email@institution.edu  
🔗 [Google Scholar](https://scholar.google.com) | [ResearchGate](https://researchgate.net)

---

<div align="center">
⭐ <b>Star this repo</b> if you find it useful! It helps others discover this resource. ⭐
</div>
