---
title: Benchmarking AutoML and Meta-Learning on Medical Image Classification
summary: Create a publicly available benchmark for medical image classification
tags:
- Deep Learning
- AutoML
- Radiomics
- Technical
date: "2025-06-02"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Overview of the proposed benchmarking framework for evaluating AutoML and meta-learning methods in medical image classification.
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
authors:
  - natalia
  - admin
---

**Background**

Medical image classification has advanced rapidly due to the availability of large pretrained models and foundation models. However, most model development workflows in medical imaging are still highly customized and dataset-specific, making it difficult to compare methods or reproduce results. This lack of standardization is especially limiting for techniques like automated machine learning (AutoML) and meta-learning, which aim to generalize across tasks and reduce manual effort. While generic AutoML benchmarks exist for natural images or tabular data, there is no established benchmark tailored to the unique characteristics of medical image data particularly in oncology. Creating such a benchmark would enable fair, systematic evaluation of AutoML and meta-learning approaches.

**Aim**

This project aims to build a comprehensive and extensible benchmark for evaluating AutoML and meta-learning methods in medical image classification, with a particular emphasis on oncological tasks. It involves curating a diverse collection of publicly available medical imaging datasets, prioritizing cancer-related classification problems across modalities such as CT and MRI. In parallel, a portfolio of pretrained and foundation models—including resources such as SAM-Med3D [1], MONAI Model Zoo, and others—will be collected and structured into a unified, reusable model hub. Based on these components, the benchmark will support the systematic evaluation of AutoML and meta-learning frameworks, including methods like Quick-Tune [2] and DEHB [3]. Evaluations will focus on metrics such as classification accuracy, cross-dataset generalization, and computational efficiency. Note that this project is quite technical.

**Related research:**
- Wang, S., Zhu, C., Lu, M. Y., Qian, Z., Chen, R. J., & Mahmood, F. (2023). SAM-Med3D: Segment Anything in 3D Images with Med3D Adapter. arXiv preprint arXiv:2308.16184.
- Arango, S. P., Ferreira, F., Kadra, A., Hutter, F., & Grabocka, J. (2023). Quick-tune: Quickly learning which pretrained model to finetune and how. arXiv preprint arXiv:2306.03828.
- Awad, N., Doerr, F., Müller, S., Benjamins, C., & Hutter, F. (2021). DEHB: Evolutionary Hyperband for Scalable, Robust and Efficient Hyperparameter Optimization. In Proceedings of the 25th International Conference on Artificial Intelligence and Statistics (AISTATS), PMLR 130: 1344–1352.  https://proceedings.mlr.press/v130/awad21a.html


**Supervisors**
- Natalia Oviedo Acosta
- Stefan Klein
- Martijn Starmans

*Feel free to mail me if you are interested in this project or want more information!*
