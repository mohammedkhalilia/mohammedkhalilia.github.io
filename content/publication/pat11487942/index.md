---
title: 'Service architecture for entity and relationship detection in unstructured text'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Thiruvarul Selvan Senthivel
  - Varun Sembium Varadarajan
  - Borui Zhang
  - Tiberiu Mircea Doman
  - Parminder Bhatia- Arun Kumar Ravi
  - Mohammed Khalilia
  - Emine Busra Celikkaya

date: '2022'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['8']

# Publication name and optional abbreviated publication name.
publication: United States Patent
publication_short: United States Patent

abstract: Techniques for entity and relationship detect from unstructured text as a service are described. A service may receive a request to identify entities within a provided unstructured text element, and the service may segment and tokenize the unstructured text and send the result to multiple services implementing multiple deep machine learning models trained to identify particular entities. The service may send additional requests to an additional service or services implementing additional deep machine learning models to identify relationships between detected attributes and ones of the detected entities. The outputs from all services can be analyzed and consolidated into a single result that identifies the entities, any attributes of the entities, and confidence scores indicating the confidence in each detected entity.

# Summary. An optional shortened abstract.
summary: 
tags: [NLP]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
  - name: Google Patents
    url: https://patents.google.com/patent/US11487942B1

url_pdf: 'https://patentimages.storage.googleapis.com/f7/53/b3/129d041cb6aefb/US11487942.pdf'
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
