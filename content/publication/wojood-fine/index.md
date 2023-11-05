---
title: 'Arabic Fine-Grained Entity Recognition'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Haneen Liqreina
  - Mustafa Jarrar
  - Mohammed Khalilia
  - Ahmed El-Shangiti
  - Muhammad Abdul-Mageed

# Author notes (optional)
author_notes:
  - 'Data annotation'
  - 'Model design, training, annotation, publication'

date: '2023'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: Proceedings of The First Arabic Natural Language Processing Conference (ArabicNLP 2023, co-hosted with EMNLP 2023)
publication_short: Proceedings of The First Arabic Natural Language Processing Conference (ArabicNLP 2023, co-hosted with EMNLP 2023)

abstract: Traditional NER systems are typically trained to recognize coarse-grained entities, and less attention is given to classifying entities into a hierarchy of fine-grained lower-level subtypes. This article aims to advance Arabic NER with fine-grained entities. We chose to extend Wojood (an open-source Nested Arabic Named Entity Corpus) with subtypes. In particular, four main entity types in Wojood, geopolitical entity (GPE), location (LOC), organization (ORG), and facility (FAC), are extended with $31$ subtypes. To do this, we first revised Wojood's annotations of GPE, LOC, ORG, and FAC to be compatible with the LDC's ACE guidelines, which yielded $5,614$ changes. Second, all mentions of GPE, LOC, ORG and FAC (44K) in  Wojood are manually annotated with the LDC\'s ACE subtypes. We refer to this extended version of Wojood as Wojood-Fine. To evaluate our annotations, we measured the inter-annotator agreement (IAA) using both Cohen's Kappa and F1 score, resulting in 0.9861 and 0.9889, respectively. To compute the baselines of Wojood-Fine, we fine-tune three pre-trained Arabic BERT encoders in three settings flat NER, nested NER and nested NER with subtypes and achieved F1 score of 0.920, 0.866, and 0.885, respectively. Our corpus and models are open-source and available at https://sina.birzeit.edu/wojood/.

# Summary. An optional shortened abstract.
summary: 
tags: [Deep Learning, Arabic NLP, Nested Named Entity Recognition]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2205.09651'
url_code: 'https://github.com/SinaLab/ArabicNER'
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
projects:
  - wojood

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
