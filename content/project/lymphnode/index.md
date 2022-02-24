---
title: Lymph Node Staging
summary: Optimization of pre-operative lymph node staging in patients with muscle-invasive bladder cancer using radiomics on computed tomography
tags:
- Deep Learning
- Clinical
- Technical
- Radiomics
date: "2022-02-24"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Lymph nodes on CT
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

At present, clinical staging of lymph nodes (LN) in patients with muscle-invasive bladder cancer (MIBC) is usually performed on computed tomography (CT). In approximately 25% of the patients with MIBC and non-malignant locoregional small LNs prior to surgery, occult LN metastases are detected after radical cystectomy (RC) and pelvic LN dissection. Hence, there is an urgent clinical need to improve preoperative LN staging to better identify patients who may benefit from neoadjuvant chemotherapy (NAC).

**Aim**

The aim of this project is to evaluate the diagnostic accuracy of pre-operative CT-based radiomics and deep learning to differentiate between pN+ and pN0 patients with MIBC. A multicenter dataset of about 250 patients has already been acquired, and all LNs have been segmented. The main challenge is that patients usually have a lot of LNs (mean: 44), but in the pN+ patients, only a handful are actually metastases, and we don’t know which, only how many. A naive radiomics approach has already been tested and did not yield positive results. We therefore propose to use a novel CNN strategy, in which we process each LN separately, combine them per patient in one loss, and trace the predictions back to the individual LNs to identify the metastases. Your goal will be to design and implement such a strategy. The resulting model could be used both for LN staging, and additionally to identify the metastases to guide treatment planning.

**Related research:**
-	https://stichtingduos.nl/cirguidance/ (study from which the data originates)
-	https://doi.org/10.1158/1078-0432.CCR-17-1510

**Supervisors**
- Martijn Starmans
- [Astrid van der Veldt](https://www.erasmusmc.nl/nl-nl/kankerinstituut/patientenzorg/zorgverleners/veldt-astrid-van-der) (Department of Oncology)
- [Stefan Klein](https://www.erasmusmc.nl/en/research/researchers/klein-stefan)

*Feel free to mail me if you are interested in this project or want more information!*
