---
title: 'Comprehend Medical: A Named Entity Recognition and Relationship Extraction Web Service'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Parminder Bhatia
  - Busra Celikkaya
  - Mohammed Khalilia
  - Selvan Senthivel

date: '2019'
doi: '10.1109/ICMLA.2019.00297'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 18th IEEE International Conference On Machine Learning And Applications (ICMLA)
publication_short: 18th IEEE International Conference On Machine Learning And Applications (ICMLA)

abstract: Comprehend Medical is a stateless and Health Insurance Portability and Accountability Act (HIPAA) eligible Named Entity Recognition (NER) and Relationship Extraction (RE) service launched under Amazon Web Services (AWS) trained using state-of-the-art deep learning models. Contrary to many existing open source tools, Comprehend Medical is scalable and does not require steep learning curve, dependencies, pipeline configurations, or installations. Currently, Comprehend Medical performs NER in five medical categories Anatomy, Medical Condition, Medications, Protected Health Information (PHI) and Treatment, Test and Procedure (TTP). Additionally, the service provides relationship extraction for the detected entities as well as contextual information such as negation and temporality in the form of traits. Comprehend Medical provides two Application Programming Interfaces (API) 1) the NERe API which returns all the extracted named entities, their traits and the relationships between them and 2) the PHId API which returns just the protected health information contained in the text. Furthermore, Comprehend Medical is accessible through AWS Console, Java and Python Software Development Kit (SDK), making it easier for non-developers and developers to use.

# Summary. An optional shortened abstract.
summary: 
tags: [Deep Learning, Named Entity Recognition, Clinical]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8999113'
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
