---
title: Optimizing the Fairness-performance trade-off of oncological radiomics biomarkers
summary: Research how we can optimally trade off algorithmic Fairness and performance using automated machine learning
tags:
- AutoML
- Radiomics
- Technical
date: "2023-02-13"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: AI Fairness
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

AI has revolutionized the development of predictive models in oncology based on medical imaging. However, only a small fraction is actually used in clinical practice. This may be attributed to development focussing on  performance only, which is not sufficient for healthcare. To overcome this gap, I recently worked on the FUTURE-AI guidelines for trustworthy and deployable AI in healthcare (see link 1 below). The first principle of the guidelines, Fairness, currently a hot topic, means that medical AI algorithms should maintain the same performance when applied to similarly situated individuals and subgroups, independent of e.g., sex, ethnicity, and age. While methods have been proposed to ensure algorithmic Fairness, this usually hurts performance.


**Aim**

The aim of this project is to develop a method to optimize the Fairness-performance trade-of of AI classification methods in medical imaging. You will develop generalizable methods, but we will focus on sarcoma on this project. The first step will be to evaluate the Fairness of current biomarkers in sarcoma. Second, you will have to implement various Fairness methods (see link 3 below) in our existing radiomics framework (see link 2 below) to evaluate how these impact Fairness and performance. Third, you will study how automated machine learning can be used to optimize the Fairness-performance trade-off of radiomics biomarkers, and which type of biomarkers are most suitable for this. In this project, we will collaborate with the BCN-AIM lab of the University of Barcelona.


**Related research:**
- https://doi.org/10.48550/arXiv.2109.09658
- https://doi.org/10.48550/arXiv.2108.08618
- https://doi.org/10.48550/arXiv.1810.01943
- https://doi.org/10.1002/bjs.11410

**Supervisors**
- Martijn Starmans
- Douwe Spaanderman
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
