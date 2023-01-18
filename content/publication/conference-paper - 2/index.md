---
title: 'Identifying Software Components from Object-Oriented APIs Based on Dynamic Analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Anas Shatnawi
  - Hudhaifa Shatnawi
  - Mohamed Aymen Saied
  - admin
  - Houari Sahraoui
  - Abdelhak Seriai


date: '2018-03-28T00:00:00Z'
doi: '10.1145/3196321.3196349'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-03-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *26th Conference on Program Comprehension*
publication_short: In *ICPC '18*

abstract: The reuse at the component level is generally more effective than the one at the object-oriented class level. This is due to the granularity level where components expose their functionalities at an abstract level compared to the fine-grained object-oriented classes. Moreover, components clearly define their dependencies through their provided and required interfaces in an explicit way that facilitates the understanding of how to reuse these components. Therefore, several component identification approaches have been proposed to identify components based on the analysis object-oriented software applications. Nevertheless, most of the existing component identification approaches did not consider co-usage dependencies between API classes to identify classes/methods that can be reused to implement a specific scenario. In this paper, we propose an approach to identify reusable software components in object-oriented APIs, based on the interactions between client applications and the targeted API. As we are dealing with actual clients using the API, dynamic analysis allows to better capture the instances of API usage. Approaches using static analysis are usually limited by the difficulty of handling dynamic features such as polymorphism and class loading. We evaluate our approach by applying it to three Java APIs with eight client applications from the DaCapo benchmark. DaCapo provides a set of pre-defined usage scenarios. The results show that our component identification approach has a very high precision.

# Summary. An optional shortened abstract.
summary: We evaluate our approach by applying it to three Java APIs with eight client applications from the DaCapo benchmark. DaCapo provides a set of pre-defined usage scenarios. The results show that our component identification approach has a very high precision.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

