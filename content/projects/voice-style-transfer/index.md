---
title: Voice Style Transfer
summary: Amazon Comprehend Medical is a HIPAA-eligible natural language processing (NLP) service that uses machine learning that has been pre-trained to understand and extract health data from medical text, such as prescriptions, procedures, or diagnoses.
tags:
  - Speech and Signal Processing
  - Deep Learning

date: '2021-01-11T00:00:00Z'

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
  - type: AutoVC
    url: https://arxiv.org/abs/1905.05879

profile: false

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Voice style transfer, also known as voice cloning, create the same voice characteristics as of the original speaker while uttering different words in different languages.
To do that, a variational auto-encoder model was trained on two datasets:

##### Voice Conversion Toolkit (VCTK)
- 44 hours 
- 109 speakers

##### VoxCeleb1 and VoxCeleb2
- 2,000+ hours
- 7,000 speakers

The above data, which contains waveforms is converted to mel spectrograms using Short-Time Fourier Transform.
![alt](fft.png)

Then a variational auto-encoder called AutoVC, is trained on the data.

