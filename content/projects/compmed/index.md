---
title: Comprehend Medical
summary: Amazon Comprehend Medical is a HIPAA-eligible natural language processing (NLP) service that uses machine learning that has been pre-trained to understand and extract health data from medical text, such as prescriptions, procedures, or diagnoses.
tags:
  - Clinical NLP
  - Deep Learning

date: '2018-01-11T00:00:00Z'

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - type: site
    url: https://aws.amazon.com/comprehend/medical/
  - type: paper
    url: https://ieeexplore.ieee.org/abstract/document/8999113/
  - type: paper
    url: https://aclanthology.org/P19-1091/
  - type: patent
    url: https://patents.google.com/patent/US11487942B1
    
profile: false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Amazon Comprehend Medical is a HIPAA-eligible natural language processing (NLP) service that uses machine learning that 
has been pre-trained to understand and extract health data from medical text, such as prescriptions, procedures, or diagnoses, medication brand and generic names, dosage, strength, duration, date/time and other traits such as negation.
The service also extracts private health information (PHI) including medical record numbers, patient names, age, address, location, race and ethnicity, etc.

#### Example

Input is clinical text that includes patient private information and clinical notes.
![alt](example_text.png)

The output includes the entities, relationships between entities and attributes.
![alt](example_entities.png)
