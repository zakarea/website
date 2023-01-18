---
title: "PI-Link: A Ground-Truth Dataset of Links Between Pull-Requests and Issues in GitHub"
authors:
- admin
- A. Shatnawi
- H. Eyal-Salman
- A. -D. Seriai
- M. Shatnawi

date: "2023-01-03T00:00:00Z"
doi: "10.1109/ACCESS.2022.3232982"

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

abstract: GitHub hosts Git repositories and provides issues-tracking services to provide a better collaboration environment for software developers. Issues and Pull-Requests are frequently used in GitHub to discuss and review the software requirements (new features, bugs, etc.) and software solutions (source code, test cases, etc.) respectively. The links between Issues and their corresponding Pull-Requests comprise valuable information to keep tracking current development as well as documenting knowledge for future development. Considering a large number of links, such information can be used to train machine learning models for several purposes such as feature location, bug prediction and localization, recommendation systems and documentation generation. To the best of our knowledge, no dataset has been proposed as a ground-truth of links between Issues and Pull-Requests. In this paper, we propose, PI-Link, a new significant and reliable ground-truth dataset composed of 50369 links that explicitly connect 34732 Issues with 50369 Pull-Requests. These links are automatically extracted from all (907,139) Android projects in GitHub created between January 1, 2011 and January 1, 2021. To better organize and store the collected data, we propose a metamodel based on the concepts of Issues and Pull Requests. Moreover, we analyze the relationships between Issues and their linked Pull Requests based on four features related to their titles, bodies, labels and comments. The selected features are analyzed in terms of their lengths and similarities based on three lexical and one semantic similarity metrics. The results showed promising similarities between Issues and their linked PRs at the lexical and semantic levels. In addition, some feature similarities are sensitive to the text length, whereas other feature similarities are sensitive to the term frequency.

# Summary. An optional shortened abstract.
summary: In this paper, we propose, PI-Link, a new significant and reliable ground-truth dataset composed of 50369 links that explicitly connect 34732 Issues with 50369 Pull-Requests. These links are automatically extracted from all (907,139) Android projects in GitHub created between January 1, 2011 and January 1, 2021. To better organize and store the collected data, we propose a metamodel based on the concepts of Issues and Pull Requests. Moreover, we analyze the relationships between Issues and their linked Pull Requests based on four features related to their titles, bodies, labels and comments.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10002372
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

