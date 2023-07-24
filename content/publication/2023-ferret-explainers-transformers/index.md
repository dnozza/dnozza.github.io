---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "ferret: a Framework for Benchmarking Explainers on Transformers"
authors: ["Giuseppe Attanasio", "Eliana Pastor", "Chiara Di Bonaventura", "Debora Nozza"]
date: 2023-05-02
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-02T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[17th Conference of the European Chapter of the Association for Computational Linguistics: System Demonstrations (EACL 2023)](https://2023.eacl.org/)"
publication_short: "17th Conference of the European Chapter of the Association for Computational Linguistics: System Demonstrations"

abstract: "As Transformers are increasingly relied upon to solve complex NLP problems, there is an increased need for their decisions to be humanly interpretable. While several explainable AI (XAI) techniques for interpreting the outputs of transformer-based models have been proposed, there is still a lack of easy access to using and comparing them.We introduce ferret, a Python library to simplify the use and comparisons of XAI methods on transformer-based classifiers.With ferret, users can visualize and compare transformers-based models output explanations using state-of-the-art XAI methods on any free-text or existing XAI corpora. Moreover, users can also evaluate ad-hoc XAI metrics to select the most faithful and plausible explanations. To align with the recently consolidated process of sharing and using transformers-based models from Hugging Face, ferret interfaces directly with its Python library.In this paper, we showcase ferret to benchmark XAI methods used on transformers for sentiment analysis and hate speech detection. We show how specific methods provide consistently better explanations and are preferable in the context of transformer models."

# Summary. An optional shortened abstract.
summary: ""


tags: ["BERT","NLP","interpretability"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2023.eacl-demo.29.pdf
url_code: "https://github.com/g8a9/ferret"
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
  caption: 'Logo'
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
