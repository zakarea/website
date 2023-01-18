---
title: "ML-Augmented Automation for Recovering Links between Pull-Requests and Issues on GitHub"
authors:
- admin
- H. Eyal-Salman
- A. Shatnawi
- A. -D. Seriai

date: "2023-01-03T00:00:00Z"
doi: "10.1109/ACCESS.2023.3236392"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: GitHub provides a distributed and collaborative platform to develop and maintain open-source projects. This social coding platform achieves this collaborative development, with or without coordination, using pull requests and issues artefacts. When the number of daily submitted issues rapidly grows up, especially in popular repositories, managing issues becomes more complicated. To help the repository’s developers in issues processing, there are external contributors who fix issues by submitting pull-requests. On GitHub, a pull-request is frequently linked with a submitted issue to show that a solution is in progress. Unfortunately, contributors might forget or be lazy to link the Pull-Requests with their corresponding Issues. Only a tiny share of these links are established, but a large portion of links are missed in the development history. However, manually recovering the links between Pull-Request and Issues from evolutionary development history is a challenging, time-consuming, and error-prone task, even for senior developers. In this article, we propose to build ML models to recover links between pull-requests and issues using two Machine Learning algorithms (KMeans and BIRCH) based on lexical and semantic weighting measurements. These models are evaluated using PI-Link ground-truth dataset. The obtained results show that pull-request and issue links can be recovered with an accuracy of 91.5% using BIRCH clustering algorithm.

# Summary. An optional shortened abstract.
summary: In this article, we propose to build ML models to recover links between pull-requests and issues using two Machine Learning algorithms (KMeans and BIRCH) based on lexical and semantic weighting measurements. These models are evaluated using PI-Link ground-truth dataset. The obtained results show that pull-request and issue links can be recovered with an accuracy of 91.5% using BIRCH clustering algorithm.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10015726
url_code: ''
url_dataset: 'https://www.kaggle.com/datasets/zakareaalshara/android-closed-issues-20110101-20210101-clean?select=android_closed_issues_2011-01-01_2021-01-01_all_clean_issues.json'
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
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

