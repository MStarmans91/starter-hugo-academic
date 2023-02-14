---
title: Diagnosis of solid appearing lesions based on MRI and deep learning 
summary: Develop deep learning methods for comprehensive MRI-based liver lesion phenotyping
tags:
- Deep Learning
- Clinical
- Radiomics
- Technical
date: "2023-02-13"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Liver tumor MRI and phenotypes
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

Differential diagnosis of solid appearing liver lesions (groups of abnormal cells in the liver, either malignant or benign) based on magnetic resonance imaging (MRI) is one of the most important challenges for abdominal radiologists. Based on their interpretation, patients are referred back with no need for follow-up or they may undergo further analysis with subsequent treatments including surgery or chemotherapy. In current practice, the differential diagnosis of liver lesions is based on subjective and qualitative assessment, relying vastly on the experience of the local radiologist. More objective and quantitative approaches are therefore urgently needed.

**Aim**

The aim of this research is to create a deep learning model for comprehensive liver tumor phenotyping based on MRI. We already have a database of 500 patients from various centers for you to start with four different liver tumors. You first task will be to extend this database by including more patients from the EMC with other liver lesion phenotypes. Using this dataset, you main task is to develop a multi-parametric MRI (e.g. T1, T2, DWI, contrast enhanced T1) deep learning model for the classification of these liver lesions. The main challenge is how to optimally combine the information from the different MRI sequences, while dealing with missing data and substantial heterogeneity. Optionally, we might also want to create a segmentation model, as this is something the radiologists would like to use in the clinic as well to quantify therapy response. You can focus on the more clinical aspects of the project in close collaboration with the radiologists, or the more technical aspects on how to construct such a model.

**Related research:**
- https://doi.org/10.1101/2021.08.10.21261827
- https://doi.org/10.48550/arXiv.2108.08618

**Supervisors**
- Martijn Starmans
- Maarten Thomeer (Abdominal radiologist)
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
