---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Multilingual HateCheck: Functional Tests for Multilingual Hate Speech Detection Models"
authors: ["Paul Röttger", "Haitham Seelawi", "Debora Nozza", "Zeerak Talat", "Bertie Vidgen"]
date: 2022-07-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-07-12T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[Sixth Workshop on Online Abuse and Harms (WOAH) at NAACL 2022](https://www.workshopononlineabuse.com/)"
publication_short: "Sixth Workshop on Online Abuse and Harms (WOAH) at NAACL 2022"

abstract: "Hate speech detection models are typically evaluated on held-out test sets. However, this risks painting an incomplete and potentially misleading picture of model performance because of increasingly well-documented systematic gaps and biases in hate speech datasets. To enable more targeted diagnostic insights, recent research has thus introduced functional tests for hate speech detection models. However, these tests currently only exist for English-language content, which means that they cannot support the development of more effective models in other languages spoken by billions across the world. To help address this issue, we introduce Multilingual HateCheck (MHC), a suite of functional tests for multilingual hate speech detection models. MHC covers 34 functionalities across ten languages, which is more languages than any other hate speech dataset. To illustrate MHC’s utility, we train and test a high-performing multilingual hate speech detection model, and reveal critical model weaknesses for monolingual and cross-lingual applications."

# Summary. An optional shortened abstract.
summary: ""


tags: ["Hate Speech","BERT","NLP"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Custom links (uncomment lines below)

url_pdf: https://aclanthology.org/2022.woah-1.15.pdf
url_code: https://github.com/rewire-online/multilingual-hatecheck
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Functional Tests Examples'
  focal_point: "Center"
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
