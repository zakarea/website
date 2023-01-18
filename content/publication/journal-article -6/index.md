---
title: "CoMe4ACloud: An end-to-end framework for autonomic Cloud systems"
authors:
- admin
- Frederico Alvares
- Hugo Bruneliere
- Jonathan Lejeune
- Charles PrudHomme
- Thomas Ledoux
date: "2018-09-01T00:00:00Z"
doi: "10.1016/j.future.2018.03.039"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Future Generation Computer Systems"
publication_short: ""

abstract: Autonomic Computing has largely contributed to the development of self-manageable Cloud services. It notably allows freeing Cloud administrators of the burden of manually managing varying-demand services, while still enforcing Service-Level Agreements (SLAs). All Cloud artifacts, regardless of the layer carrying them, share many common characteristics. Thus, it should be possible to specify, (re)configure and monitor any XaaS (Anything-as-a-Service) layer in an homogeneous way. To this end, the CoMe4ACloud approach proposes a generic model-based architecture for autonomic management of Cloud systems. We derive a generic unique Autonomic Manager (AM) capable of managing any Cloud service, regardless of the layer. This AM is based on a constraint solver which aims at finding the optimal configuration for the modeled XaaS, i.e. the best balance between costs and revenues while meeting the constraints established by the SLA. We evaluate our approach in two different ways. Firstly, we analyze qualitatively the impact of the AM behavior on the system configuration when a given series of events occurs. We show that the AM takes decisions in less than 10 s for several hundred nodes simulating virtual/physical machines. Secondly, we demonstrate the feasibility of the integration with real Cloud systems, such as Openstack, while still remaining generic. Finally, we discuss our approach according to the current state-of-the-art.

# Summary. An optional shortened abstract.
summary: The CoMe4ACloud approach proposes a generic model-based architecture for autonomic management of Cloud systems. We derive a generic unique Autonomic Manager (AM) capable of managing any Cloud service, regardless of the layer. This AM is based on a constraint solver which aims at finding the optimal configuration for the modeled XaaS, i.e. the best balance between costs and revenues while meeting the constraints established by the SLA.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/sdfe/reader/pii/S0167739X17320605/pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://come4acloud.github.io/'
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

