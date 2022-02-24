---
title: Scribble Segmentation
summary: Automatic segmentation of soft-tissue tumors on MRI with deep learning using scribble annotations and active learning
tags:
- Deep Learning
- Technical
- Clinical
date: "2022-02-24"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Soft tissue tumors (top) and scribble concept (bottom)
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

Soft tissue tumors (STT) are a rare and complex group of tumors with over 100 different STT subtypes. A first step in any STT study is the segmentation, hence our radiologists are very eager for such a solution. Moreover, we previously successfully created STT classification models, which depend currently on manual segmentations. Automatic segmentation is however challenging due the STT rarity and their heterogeneity. Moreover, STT can invade other organs and occur anywhere in the body, making it difficult for deep learning to detect them.

**Aim**

The aim of this project is to create a deep learning model for the segmentation of STT by keeping the radiologist in the loop. To this end, we will make use of user-provided scribbles, i.e. rough indications of the tumor outlines, which will serve as input for the network. Additionally, the output of the network can be refined by again requesting a scribble from the clinician. You will start with a literature search on how to optimally make use of scribbles in this context. Using this pragmatic approach, with limited input from the clinician, we can provide automatic annotations for all kinds of STT. Moreover, we hope to extend this approach to brain tumors, where often refinements from the clinicians are also required.

**Related research:**
-	https://doi.org/10.1109/TMI.2018.2791721
-	https://arxiv.org/abs/2007.01152
-	https://doi.org/10.1002/bjs.11410
-	https://doi.org/10.1016/j.ejrad.2020.109266


**Supervisors**
- Douwe Spaanderman (PhD student)
- Martijn Starmans
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
