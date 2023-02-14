---
title: Preoperative prediction of colorectal liver metastases aggressiveness using pathomics
summary: Develop deep learning methods to predict histopathological growth patterns on primary tumor histopathology
tags:
- Deep Learning
- Clinical
- Pathomics
- Technical
date: "2023-02-13"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: HGPs on pathology
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

**Background**

The prognosis of colorectal liver metastases (CRLM) is highly influenced by the so-called histopathological growth pattern (HGP), i.e. the interaction between the liver and tumor tissue. Patients with more aggressive growth patterns have a far worse prognosis and may benefit from preoperative neo-adjuvant chemotherapy. Unfortunately, the HGP can currently only be determined based on surgery and thus post-operatively. Our clinicians are therefore looking for a pre-operative alternative. Previously, we have already shown that histopathological characteristic of the primary tumor relate to the HGP (link 1 below).

**Aim**

The aim of this research is to create a deep learning model based on histopathology slides of the primary tumor to predict the CRLM HGP. We will take a two-fold approach: 1) automate the scoring of the characteristics that were previously found to be predictive. This will result in a highly explainable model, but performance might nog be ideal. 2) Take an agnostic approach, where you will use recent advances in AI models for whole slide image representation to train end-to-end models that determines CRLM HGPs directly from the primary tumour image. This project will be conducted in close collaboration with the Department of Surgery, Department of Pathology, TU Eindhoven, and GZA Antwerp.

**Related research:**
- https://doi.org/10.1186/s12885-022-09994-3
- https://doi.org/10.1038/s41416-022-01859-7
- https://doi.org/10.1016/j.semcancer.2020.07.002
- https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Scaling_Vision_Transformers_to_Gigapixel_Images_via_Hierarchical_Self-Supervised_Learning_CVPR_2022_paper.pdf 


**Supervisors**
- Martijn Starmans
- Zhen Qian (Department of Surgery)
- Mitko Veta (TU Eindhoven)
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
