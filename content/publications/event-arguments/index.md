---
title: 'Event-Arguments Extraction Corpus and Modeling using BERT for Arabic'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Alaa Aljabari
  - Lina Duaibes
  - Mustafa Jarrar
  - Mohammed Khalilia

date: '2024-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: Association for Computational Linguistics
publication_short: Association for Computational Linguistics, Proceedings of the Second Arabic Natural Language Processing Conference

abstract: Event-argument extraction is a challenging task, particularly in Arabic due to sparse linguistic resources. To fill this gap, we introduce the corpus (550k tokens) as an extension of Wojood, enriched with event-argument annotations. We used three types of event arguments, agent, location, and date, which we annotated as relation types. Our inter-annotator agreement evaluation resulted in 82.23% Kappa score and 87.2% F1-score. Additionally, we propose a novel method for event relation extraction using BERT, in which we treat the task as text entailment. This method achieves an $F_1$-score of 94.01{\%}.To further evaluate the generalization of our proposed method, we collected and annotated another out-of-domain corpus (about 80k tokens) called and used it as a second test set, on which our approach achieved promising results (83.59{\%} $F_1$-score). Last but not least, we propose an end-to-end system for event-arguments extraction. This system is implemented as part of SinaTools, and both corpora are publicly available at https://sina.birzeit.edu/wojood.

# Summary. An optional shortened abstract.
summary: 
tags: 
  - ArabicNLP

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
  - type: pdf
    url: https://aclanthology.org/2024.arabicnlp-1.26/

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
slides: ""
----

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
