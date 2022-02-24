---
title: AutoML For Deep Learning
summary: Overcoming the limits of model optimization for deep learning through metalearning, ensembling, and Pareto optimization
tags:
- Deep Learning
- AutoML
- Technical
date: "2022-02-24"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Meta-learning (left) and Pareto front (right)
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

In recent years, a wide variety of deep learning methods for the classification of medical images have been proposed. On a new application, determining which method works best is tedious, challenging, and optimization generally leads to overfitting. Moreover, especially in rare diseases, the datasets are often simply too small for extensive optimization. Lastly, optimization is currently mostly done on the validation performance, while our goal is actually good generalization.

**Aim**

The aim of this project is to overcome the limits of optimization through two complementary approaches. First, we propose to learn from previous problems which solutions worked best instead of starting from scratch through meta-learning. Second, instead of optimizing for validation performance, we will create an ensemble of complementary solutions using Pareto front multi-objective optimization. To this end, we have collected twelve  datasets of in total 2.500 patients on twelve different clinical applications (e.g. sarcoma, liver, prostate, brain, head and neck, neuroendocrine tumors) on which we previously successfully created individual classification models. Note that this project is quite technical and challenging.

**Related research:**
-	https://ieeexplore.ieee.org/abstract/document/1599245
-	https://arxiv.org/abs/2004.05439

**Supervisors**
- Martijn Starmans
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
