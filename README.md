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

| Title | Venue | Year |
|-------|-------|------|
| [Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review](https://doi.org/10.3389/frai.2024.1430984) | Frontiers in Artificial Intelligence | 2024 |
| [A Survey of Medical Vision-and-Language Applications and Their Techniques](https://arxiv.org/abs/2411.12195) | arXiv:2411.12195 | 2024 |
| [Vision-Language Models in Medicine](https://arxiv.org/abs/2503.01863) | arXiv:2503.01863 | 2025 |
| [Vision-Language Models in Medical Image Analysis: From Simple Fusion to General Large Models](https://doi.org/10.1016/j.inffus.2025.102995) | Information Fusion, Elsevier Q1 | 2025 |
| [Vision-Language Foundation Model for 3D Medical Imaging](https://www.nature.com/articles/s44387-025-00015-9) | npj Artificial Intelligence, Nature Portfolio | 2025 |
| [Large Language Model for Medical Images: A Survey of Taxonomy](https://doi.org/10.26599/BDMA.2024.9020090) | Big Data Mining and Analytics | 2025 |
| [Vision-Language Foundation Models for Medical Imaging (2022–2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12411343/) | PMC / NIH | 2024 |
| [LViT: Language Meets Vision Transformer in Medical Image Segmentation](https://arxiv.org/abs/2206.14718) | IEEE Transactions on Medical Imaging, Vol.43(1) | 2024 |

---

## 🧠 Medical VQA

### Closed-Ended VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [Prompting Medical Large Vision-Language Models to Diagnose Pathologies by Visual Question Answering](https://arxiv.org/abs/2407.21368) | arXiv:2407.21368 | 2024 | Chest X-Ray |
| [GeMeX: A Large-Scale, Groundable, Explainable Medical VQA Benchmark](https://arxiv.org/abs/2411.16778) | arXiv:2411.16778 | 2024 | Chest X-Ray |
| [SLAKE: A Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering](https://arxiv.org/abs/2102.09542) | IEEE 18th Int. Symposium on Biomedical Imaging (ISBI 2021), pp.1650–1654 | 2021 | Multi-modal |

### Open-Ended / Generative VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [Targeted Visual Prompting for Medical Visual Question Answering](https://arxiv.org/abs/2408.03043) | arXiv:2408.03043 | 2024 | Radiology |
| [AMANDA: Agentic Medical Knowledge Augmentation for Visual Question Answering](https://aclanthology.org/2025.findings-emnlp.1350.pdf) | Findings of EMNLP 2025 | 2025 | Multi-modal |
| [PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering](https://arxiv.org/abs/2305.10415) | arXiv:2305.10415 | 2023 | Multi-modal |

### Region-Grounded VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [HEAL-MedVQA: Hallucination Evaluation via Localization in Medical VQA](https://arxiv.org/abs/2505.00744) | arXiv:2505.00744 | 2025 | Radiology |
| [MIMO: A Medical Vision Language Model with Visual Referring Multimodal Input and Pixel Grounding Output](https://arxiv.org/abs/2510.10011) | IEEE/CVF CVPR 2025, pp.24732–24741 | 2025 | Multi-organ |
| [Dual Modality Prompt Learning for Visual Question Answering in Robotic Surgery](https://doi.org/10.1007/s42979-024-02705-4) | SN Computer Science (Springer), 2024 | 2024 | Surgical |

### Hallucination & Robustness

| Title | Venue | Year |
|-------|-------|------|
| [Prompting Strategies to Reduce Hallucination in Multimodal Large Vision-Language Models](https://arxiv.org/abs/2407.21368) | arXiv:2407.21368 | 2025 |
| [How Easy Is It to Fool Your Multimodal LLMs? An Empirical Analysis on Deceptive Prompts](https://arxiv.org/abs/2402.13220) | arXiv:2402.13220 | 2024 |

---

## 📝 Report Generation

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [R2GenGPT: Radiology Report Generation with Frozen Large Language Models](https://arxiv.org/abs/2309.09812) | Meta-Radiology, Vol.1(3):100033, Elsevier | 2023 | Chest X-ray |
| [BioViL-T: Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing](https://arxiv.org/abs/2301.04558) | IEEE/CVF CVPR 2023, pp.15016–15027 | 2023 | Chest X-ray |
| [CheXagent: Towards a Foundation Model for Chest X-Ray Analysis](https://arxiv.org/abs/2401.12208) | arXiv:2401.12208 | 2024 | Chest X-ray |
| [Enhancing Vision-Language Models for Medical Imaging (BrainMD + Vote-MI)](https://proceedings.neurips.cc/paper_files/paper/2024/file/b53513b83232116ae25f57a174a7c993-Paper-Datasets_and_Benchmarks_Track.pdf) | NeurIPS 2024 Datasets & Benchmarks Track | 2024 | Brain MRI |
| [SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding](https://arxiv.org/abs/2410.11761) | IEEE/CVF CVPR 2025, pp.5134–5143 | 2025 | Pathology WSI |
| [CheXWorld: Exploring Image World Modeling for Radiograph Representation Learning](https://arxiv.org/abs/2504.13820) | IEEE/CVF CVPR 2025 | 2025 | Chest X-ray |

---

## 🏗️ Foundation Models

### Pre-training Strategies

| Title | Venue | Year |
|-------|-------|------|
| [BioMedCLIP: A Multimodal Biomedical Foundation Model Pretrained from Fifteen Million Scientific Image-Text Pairs](https://arxiv.org/abs/2303.00915) | arXiv:2303.00915 | 2023 |
| [PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents](https://arxiv.org/abs/2303.07240) | MICCAI 2023 | 2023 |
| [PubMedCLIP: How Much Does CLIP Benefit Visual Question Answering in the Medical Domain?](https://arxiv.org/abs/2112.13906) | Findings of EACL 2023, pp.1151–1163 | 2023 |
| [LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day](https://arxiv.org/abs/2306.00890) | NeurIPS 2023 Datasets & Benchmarks Track (Spotlight) | 2023 |
| [VILA-M3: Enhancing Vision-Language Models with Medical Expert Knowledge](https://arxiv.org/abs/2411.12915) 🏆 | IEEE/CVF CVPR 2025 Highlight, pp.14788–14798 | 2025 |

### Fine-tuning & PEFT

| Title | Venue | Year |
|-------|-------|------|
| [PeFoMed: Parameter Efficient Fine-Tuning on Multimodal Large Language Models for Medical VQA](https://arxiv.org/abs/2401.02797) | arXiv:2401.02797 | 2024 |
| [Med-MoE: Mixture of Domain-Specific Experts for Medical Image Understanding](https://arxiv.org/abs/2404.10237) | arXiv:2404.10237 | 2024 |
| [BioMedGPT: Open Multimodal Generative Pre-trained Transformer for BioMedicine](https://arxiv.org/abs/2308.09442) | arXiv:2308.09442 | 2023 |

### Zero/Few-Shot

| Title | Venue | Year |
|-------|-------|------|
| [Med-Flamingo: A Multimodal Medical Few-shot Learner](https://arxiv.org/abs/2307.15189) | arXiv:2307.15189 | 2023 |
| [T3D: Towards 3D Medical Image Understanding through Vision-Language Pre-training](https://arxiv.org/abs/2312.01529) | arXiv:2312.01529 | 2023 |

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
2023  →  Foundation models established: LLaVA-Med (NeurIPS), BioViL-T (CVPR), BioMedCLIP
2024  →  Instruction tuning, PEFT, grounded VQA, hallucination research, IEEE TMI VLP
2025  →  CVPR highlights (VILA-M3, MIMO, SlideChat, CheXWorld), agentic VQA, 3D VLMs
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
2. Add paper in existing table format: **[Title](arxiv or doi link)** | Venue | Year
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
