---
title: "Automatic Identification of Similar Pull-Requests in GitHubs Repositories Using Machine Learning"
authors:
- H. Eyal-Salman
- admin
- A. -D. Seriai

date: "2022-02-03T00:00:00Z"
doi: "10.3390/info13020073"

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

abstract: In a social coding platform such as GitHub, a pull-request mechanism is frequently used by contributors to submit their code changes to reviewers of a given repository. In general, these code changes are either to add a new feature or to fix an existing bug. However, this mechanism is distributed and allows different contributors to submit unintentionally similar pull-requests that perform similar development activities. Similar pull-requests may be submitted to review in parallel time by different reviewers. This will cause redundant reviewing time and efforts. Moreover, it will complicate the collaboration process. Objective: Therefore, it is useful to assign similar pull-requests to the same reviewer to be able to decide which pull-request to choose in effective time and effort. In this article, we propose to group similar pull-requests together into clusters so that each cluster is assigned to the same reviewer or the same reviewing team. This proposal allows saving reviewing efforts and time. Method: To do so, we first extract descriptive textual information from pull-requests content to link similar pull-requests together. Then, we employ the extracted information to find similarities among pull-requests. Finally, machine learning algorithms (K-Means clustering and agglomeration hierarchical clustering algorithms) are used to group similar pull-requests together. Results: To validate our proposal, we have applied it to twenty popular repositories from public dataset. The experimental results show that the proposed approach achieved promising results according to the well-known metrics in this subject: precision and recall. Furthermore, it helps to save the reviewer time and effort. Conclusion: According to the obtained results, the K-Means algorithm achieves 94% and 91% average precision and recall values over all considered repositories, respectively, while agglomeration hierarchical clustering performs 93% and 98% average precision and recall values over all considered repositories, respectively. Moreover, the proposed approach saves reviewing time and effort on average between (67% and 91%) by K-Means algorithm and between (67% and 83%) by agglomeration hierarchical clustering algorithm.

# Summary. An optional shortened abstract.
summary: We first extract descriptive textual information from pull-requests content to link similar pull-requests together. Then, we employ the extracted information to find similarities among pull-requests. Finally, machine learning algorithms (K-Means clustering and agglomeration hierarchical clustering algorithms) are used to group similar pull-requests together.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/2078-2489/13/2/73
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

