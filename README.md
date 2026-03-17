# Recent Progress in Vision–Language Models for Medical Imaging: A Comprehensive Survey

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)



[![Last Updated](https://img.shields.io/badge/Last%20Updated-March%202025-red)](https://github.com/yourusername/VLM-Medical-Imaging-Survey)
<img width="1408" height="768" alt="Firefly_GeminiFlash" src="https://github.com/user-attachments/assets/bfbad984-7ed0-48f6-a948-708aba16d7da" />



</div>

> A curated collection of **published** papers on **Vision–Language Models (VLMs) for Medical Imaging**, covering Medical VQA, Report Generation, and Foundation Models. Only peer-reviewed conference and journal papers are included.

---

## Table of Contents

- [Survey Papers](#-survey-papers)
- [Medical VQA](#-medical-vqa)
  - [Closed-Ended VQA](#closed-ended-vqa)
  - [Open-Ended VQA](#open-ended--generative-vqa)
  - [Region-Grounded VQA](#region-grounded-vqa)
- [Report Generation](#-report-generation)
- [Foundation Models](#-foundation-models)
  - [Pre-training](#pre-training-strategies)
  - [Fine-tuning & PEFT](#fine-tuning--peft)


- [Citation](#-citation)

---


## 📄 Survey Papers

| Title | Venue | Year |
|-------|-------|------|
| [Vision-Language Models for Medical Report Generation and Visual Question Answering: A Review](https://doi.org/10.3389/frai.2024.1430984) | Frontiers in Artificial Intelligence | 2024 |
| [Vision-Language Models in Medical Image Analysis: From Simple Fusion to General Large Models](https://doi.org/10.1016/j.inffus.2025.102995) | Information Fusion, Elsevier Q1 | 2025 |
| [Vision-Language Foundation Model for 3D Medical Imaging](https://www.nature.com/articles/s44387-025-00015-9) | npj Artificial Intelligence, Nature Portfolio | 2025 |
| [Large Language Model for Medical Images: A Survey of Taxonomy](https://doi.org/10.26599/BDMA.2024.9020090) | Big Data Mining and Analytics | 2025 |
| [Vision-Language Foundation Models for Medical Imaging (2022–2024)](https://pmc.ncbi.nlm.nih.gov/articles/PMC12411343/) | PMC / NIH | 2024 |
| [LViT: Language Meets Vision Transformer in Medical Image Segmentation](https://ieeexplore.ieee.org/document/10172039) | IEEE Transactions on Medical Imaging, Vol.43, pp.96–107 | 2023 |
| [Mammo-CLIP: A Vision Language Foundation Model to Enhance Data Efficiency and Robustness in Mammography](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_59) | MICCAI 2024, LNCS Vol.15012, pp.632–642, Springer | 2024 |
| [Few-Shot Adaptation of Medical Vision-Language Models](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_52) | MICCAI 2024, LNCS Vol.15012, pp.553–563, Springer | 2024 |
| [CAT-ViL: Co-Attention Gated Vision-Language Embedding for Visual Question Localized-Answering in Robotic Surgery](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_38) | MICCAI 2023, LNCS Vol.14228, pp.397–407, Springer | 2023 |

---

##  Medical VQA

### Closed-Ended VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [SLAKE: A Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering](https://ieeexplore.ieee.org/document/9434010) | IEEE 18th Int. Symposium on Biomedical Imaging (ISBI 2021), pp.1650–1654 | 2021 | Multi-modal |

### Open-Ended / Generative VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [AMANDA: Agentic Medical Knowledge Augmentation for Visual Question Answering](https://aclanthology.org/2025.findings-emnlp.1350.pdf) | Findings of EMNLP 2025 | 2025 | Multi-modal |

### Region-Grounded VQA

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [MIMO: A Medical Vision Language Model with Visual Referring Multimodal Input and Pixel Grounding Output](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_MIMO_A_Medical_Vision_Language_Model_with_Visual_Referring_Multimodal_CVPR_2025_paper.html) | IEEE/CVF CVPR 2025, pp.24732–24741 | 2025 | Multi-organ |
| [CAT-ViL: Co-Attention Gated Vision-Language Embedding for Visual Question Localized-Answering in Robotic Surgery](https://link.springer.com/chapter/10.1007/978-3-031-43996-4_38) | MICCAI 2023, LNCS Vol.14228, pp.397–407, Springer | 2023 | Surgical |

---

## Report Generation

| Title | Venue | Year | Modality |
|-------|-------|------|----------|
| [R2GenGPT: Radiology Report Generation with Frozen Large Language Models](https://www.sciencedirect.com/science/article/pii/S2950162823000620) | Meta-Radiology, Vol.1(3):100033, Elsevier | 2023 | Chest X-ray |
| [BioViL-T: Learning to Exploit Temporal Structure for Biomedical Vision-Language Processing](https://openaccess.thecvf.com/content/CVPR2023/html/Bannur_Learning_To_Exploit_Temporal_Structure_for_Biomedical_Vision-Language_Processing_CVPR_2023_paper.html) | IEEE/CVF CVPR 2023, pp.15016–15027 | 2023 | Chest X-ray |
| [Enhancing Vision-Language Models for Medical Imaging (BrainMD + Vote-MI)](https://proceedings.neurips.cc/paper_files/paper/2024/file/b53513b83232116ae25f57a174a7c993-Paper-Datasets_and_Benchmarks_Track.pdf) | NeurIPS 2024 Datasets & Benchmarks Track | 2024 | Brain MRI |
| [SlideChat: A Large Vision-Language Assistant for Whole-Slide Pathology Image Understanding](https://openaccess.thecvf.com/content/CVPR2025/html/Chen_SlideChat_A_Large_Vision-Language_Assistant_for_Whole-Slide_Pathology_Image_Understanding_CVPR_2025_paper.html) | IEEE/CVF CVPR 2025, pp.5134–5143 | 2025 | Pathology WSI |
| [CheXWorld: Exploring Image World Modeling for Radiograph Representation Learning](https://openaccess.thecvf.com/content/CVPR2025/html/Yue_CheXWorld_Exploring_Image_World_Modeling_for_Radiograph_Representation_Learning_CVPR_2025_paper.html) | IEEE/CVF CVPR 2025 | 2025 | Chest X-ray |

---

## Foundation Models

### Pre-training Strategies

| Title | Venue | Year |
|-------|-------|------|
| [PMC-CLIP: Contrastive Language-Image Pre-training using Biomedical Documents](https://link.springer.com/chapter/10.1007/978-3-031-43993-3_34) | MICCAI 2023, LNCS Vol.14221, pp.354–364, Springer | 2023 |
| [PubMedCLIP: How Much Does CLIP Benefit Visual Question Answering in the Medical Domain?](https://aclanthology.org/2023.findings-eacl.88/) | Findings of EACL 2023, pp.1151–1163 | 2023 |
| [LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day](https://proceedings.neurips.cc/paper_files/paper/2023/hash/5abcdf8ecdcacba028452e0fe94c9e84-Abstract-Datasets_and_Benchmarks.html) | NeurIPS 2023 Datasets & Benchmarks Track (Spotlight) | 2023 |
| [VILA-M3: Enhancing Vision-Language Models with Medical Expert Knowledge](https://openaccess.thecvf.com/content/CVPR2025/html/Nath_VILA-M3_Enhancing_Vision-Language_Models_with_Medical_Expert_Knowledge_CVPR_2025_paper.html) 🏆 | IEEE/CVF CVPR 2025 Highlight, pp.14788–14798 | 2025 |

### Fine-tuning & PEFT

| Title | Venue | Year |
|-------|-------|------|
| [PromptSmooth: Certifying Robustness of Medical Vision-Language Models via Prompt Learning](https://link.springer.com/chapter/10.1007/978-3-031-72390-2_65) | MICCAI 2024, LNCS Vol.15012, pp.699–709, Springer | 2024 |

---


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


## Contact

Maintained by **[YASH PRATAP SINGH]**  


---

<div align="center">
⭐ <b>Star this repo</b> if you find it useful! ⭐
</div>
