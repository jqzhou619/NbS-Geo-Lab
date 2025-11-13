---
title: "Spatio-temporal prediction of soil hydro-thermal response in embankmentto the varying climatic conditions using a Two-Step LSTM-ML approach"
authors:
- Ni An
- Enze Xie 
- Yang Yu
- Yongyong Yang
- Qing Lv
- Shuai Zhang
- Wei Zhan
- Yadong Wu 
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-11-01T00:00:00Z"
doi: "https://doi.org/10.1016/j.trgeo.2025.101648"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-11-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]  #期刊 article-journal，会议 paper-conference，书 book，章节 chapter，学位 thesis，报告 report，专利 patent

# Publication name and optional abbreviated publication name.
publication: "*Transportation Geotechnics, 55*(101648)"
publication_short: ""

abstract: Soil hydro-thermal response is vital in the assessment of embankment stability, especially considering the increasing extreme climate events along with global climate change. Machine learning has emerged as a promising approach to estimate soil hydro-thermal dynamics. Current spatio-temporal prediction methods of soil hydro-thermal response faces significant challenges when applied to embankments, including the employment of remote sensing data with large-scale resolution, extensive datasets and high computational costs requested by layered modeling approaches. To address these limitations, this study develops a Two-Step LSTM-ML approach to predict the spatio-temporal variations of soil temperature and volumetric water content in embankments. The method is conducted in two steps, a Long Short-Term Memory (LSTM) model for the prediction of surface soil hydro-thermal response in step 1 and then combined with machine learning algorithms, e.g., Support Vector Regression (SVR), Random Forest (RF), and Artificial Neural Networks (ANN), to estimate the soil hydro-thermal response at various depths in step 2. The developed approach is trained and validated using measured data from July 6, 2011 to October 7, 2011 at the Héricourt embankment in France. The results demonstrate that the LSTM model effectively captures temporal variations in surface soil temperature and volumetric water content, while spatial mapping using RF and ANN models provides reliable predictions of soil variables at different depths. Additionally, this study examines the effects of different time-step and an iterative computation approach for surface soil variable prediction, further refining the model’s performance. The proposed method offers a robust and efficient framework for predicting soil temperature and volumetric water content in embankments, with potential applications for transportation infrastructure management and climate change adaptation.

# Summary. An optional shortened abstract.
summary: None.

tags:
- Hydro-thermal
- Machine learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false  #true 表示仅在列表卡片显示，不在详情页顶部展示。

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []  #关联站内项目（写项目目录名，如 ["internal-project"]），用于在项目页联动展示。

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

