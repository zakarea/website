---
title: 'NIV-Detector: An Automated Approach for Detecting Next-Intent Security Vulnerability in Android Applications'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Anas Shatnawi
  - Yaser Jararweh


date: '2022-12-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *the Ninth International Conference on Software Defined Systems*
publication_short: In *SDS-2022*

abstract: In Android inter-process communication, any component can start another public component using an Intent messaging object nevertheless the components belong to different processes or applications. Besides, the private components should be protected and only be accessible by the same process. However, the malicious application can breach access and directly starts private components from another process, causing Next-Intent Vulnerability (NIV). The leading cause of NIV comes from lunching unsafe Nested Intent sent by the malicious application. In this paper, we propose a new approach and implement its tool to automatically inspect NIV code smells. We integrate our tool, named NIV-Detector, with Android Studio as a plugin to be available during development time. We use NIV-Detector to inspect 100 Android GitHub projects. As a result, we successfully confirmed ten vulnerable projects with 14 NIV smells.

# Summary. An optional shortened abstract.
summary: In this paper, we propose a new approach and implement its tool to automatically inspect NIV code smells. We integrate our tool, named NIV-Detector, with Android Studio as a plugin to be available during development time. We use NIV-Detector to inspect 100 Android GitHub projects. As a result, we successfully confirmed ten vulnerable projects with 14 NIV smells.


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://github.com/zakarea/NIV-Solver'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://emergingtechnet.org/SDS2022/'
url_video: 'https://www.youtube.com/watch?v=DdDnuL47Tes'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

---
