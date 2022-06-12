---
title: 'Identifying Patients at Risk of High Healthcare Utilization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Lincoln Sheets
  - Lori Popejoy
  - Mohammed Khalilia
  - Greg Petroski
  - Jerry C. Parker

date: '2016'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2016-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: AMIA Annual Symposium Proceedings
publication_short: AMIA Annual Symposium Proceedings

abstract: Clinical predictive modeling involves two challenging tasks, model development and model deployment. In this paper we demonstrate a software architecture for developing and deploying clinical predictive models using web services via the Health Level 7 (HL7) Fast Healthcare Interoperability Resources (FHIR) standard. The services enable model development using electronic health records (EHRs) stored in OMOP CDM databases and model deployment for scoring individual patients through FHIR resources. The MIMIC2 ICU dataset and a synthetic outpatient dataset were transformed into OMOP CDM databases for predictive model development. The resulting predictive models are deployed as FHIR resources, which receive requests of patient information, perform prediction against the deployed predictive model and respond with prediction scores. To assess the practicality of this approach we evaluated the response and prediction time of the FHIR modeling web services. We found the system to be reasonably fast with one second total response time per patient prediction.

# Summary. An optional shortened abstract.
summary: 
tags: [Clinical]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5333327/'
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
