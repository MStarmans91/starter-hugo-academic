---
title: Dynamic Preprocessing Pipeline for Soft Tissue Tumor Classification
summary: Developing learnable and efficient preprocessing layers
tags:
- Deep Learning
- AutoML
- Radiomics
- Technical
date: "2025-06-02"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Overview of OBELISK-Net, which replaces standard dense convolutional layers with sparse, deformable sampling operations that learn optimal spatial locations for feature extraction.
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

In medical imaging, preprocessing steps like normalization, resampling, and cropping are often applied using fixed heuristics. While standard, these static methods can limit performance in complex settings such as soft tissue tumors (STTs), where anatomical variation and acquisition inconsistencies are common.  nnU-Net [1] has shown that task-specific, well-chosen preprocessing can strongly influence performance by adapting settings to the dataset characteristics. Building on this idea, and inspired by OBELISK-Net [2], which integrates preprocessing within the network as a learnable module, this project explores a dynamic alternative: making preprocessing fully differentiable and trainable alongside the model. 

**Aim**

The aim of this project is to build an adaptive preprocessing pipeline for medical imaging with a focus on STTs. Instead of using fixed rules for intensity normalization, voxel spacing resampling, or spatial cropping, the project will implement these steps as learnable layers in a deep neural network. These layers will be differentiable and trained end-to-end with the downstream model, allowing them to discover the most effective image transformations in a data-driven, task-specific way. The proposed pipeline will be compared with conventional preprocessing strategies and evaluated on public medical imaging datasets, especially for rare cancers such as STTs. Note that this project is quite technical.

**Related research:**
- Isensee, F., Jaeger, P.F., Full, P.M., Vollmuth, P., Maier-Hein, K.H.: nnU-Net: A self-configuring method for deep learning-based biomedical image segmentation. Nature Methods 18, 203–211 (2021)
- Heinrich, M. P., Oktay, O., & Bouteldja, N. (2019). OBELISK-Net: Fewer layers to solve 3D multi-organ segmentation with sparse deformable convolutions. Medical image analysis, 54, 1-9.


**Supervisors**
- Natalia Oviedo Acosta
- Stefan Klein
- Martijn Starmans

*Feel free to mail me if you are interested in this project or want more information!*
