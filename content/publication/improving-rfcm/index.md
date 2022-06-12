---
title: 'Improvements to the relational fuzzy c-means clustering algorithm'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Mohammed Khalilia
  - James Bezdek
  - Mihail Popescu
  - James Keller

date: '2014'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2014-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Pattern Recognition
publication_short: Pattern Recognition

abstract: Relational fuzzy c-means (RFCM) is an algorithm for clustering objects represented in a pairwise dissimilarity values in a dissimilarity data matrix D. RFCM is dual to the fuzzy c-means (FCM) object data algorithm when D is a Euclidean matrix. When D is not Euclidean, RFCM can fail to execute if it encounters negative relational distances. To overcome this problem we can Euclideanize the relation D prior to clustering. There are different ways to Euclideanize D such as the β-spread transformation. In this article we compare five methods for Euclideanizing D to View the MathML source. The quality of View the MathML source for our purpose is judged by the ability of RFCM to discover the apparent cluster structure of the objects underlying the data matrix D . The subdominant ultrametric transformation is a clear winner, producing much better partitions of View the MathML source than the other four methods. This leads to a new algorithm which we call the improved RFCM (iRFCM).

# Summary. An optional shortened abstract.
summary: 
tags: [Clustering]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.sciencedirect.com/science/article/abs/pii/S003132031400243X'
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
  caption: 'Demo screenshot'
  focal_point: ''
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
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
