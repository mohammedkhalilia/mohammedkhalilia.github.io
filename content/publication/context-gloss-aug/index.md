---
title: 'Context-Gloss Augmentation for Improving Arabic Target Sense Verification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sanad Malaysha
  - Mustafa Jarrar
  - Mohammed Khalilia

# Author notes (optional)
author_notes:
  - 'Data annotation'
  - 'Model design, training, annotation, publication'

date: '2023'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-02-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: The 12th International Global Wordnet Conference (GWC2023), Global Wordnet Association. (pp. ). San Sebastian, Spain, 2023
publication_short: The 12th International Global Wordnet Conference (GWC2023), Global Wordnet Association. (pp. ). San Sebastian, Spain, 2023

abstract: Arabic language lacks semantic datasets and sense inventories. The most common semantically-labeled dataset for Arabic is the ArabGlossBERT, a relatively small dataset that consists of 167K context-gloss pairs (about 60K positive and 107K negative pairs), collected from Arabic dictionaries. This paper presents an enrichment to the ArabGlossBERT dataset, by augmenting it using (Arabic-English-Arabic) machine back-translation. Augmentation increased the dataset size to 352K pairs (149K positive and 203K negative pairs). We measure the impact of augmentation using different data configurations to fine-tune BERT on target sense verification (TSV) task. Overall, the accuracy ranges between 78% to 84% for different data configurations. Although our approach performed at par with the baseline, we did observe some improvements for some POS tags in some experiments. Furthermore, our fine-tuned models are trained on a larger dataset covering larger vocabulary and contexts. We provide an in-depth analysis of the accuracy for each part-of-speech (POS).

# Summary. An optional shortened abstract.
summary: 
tags: [Deep Learning, Arabic NLP, Target Sense Verification]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2302.03126'
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
slides: ""
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
