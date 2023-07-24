---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MilaNLP at SemEval-2023 Task 10: Ensembling Domain-Adapted and Regularized Pretrained Language Models for Robust Sexism Detection"
authors: ["Amanda Cercas Curry", "Giuseppe Attanasio","Debora Nozza","Dirk Hovy"]
date: 2023-07-12
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-07-12T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[Proceedings of the The 17th International Workshop on Semantic Evaluation (SemEval-2023)](https://aclanthology.org/2023.semeval-1.285/)"
publication_short: "SemEval-2023"

abstract: "We present the system proposed by the MilaNLP team for the Explainable Detection of Online Sexism (EDOS) shared task. We propose an ensemble modeling approach to combine different classifiers trained with domain adaptation objectives and standard fine-tuning.Our results show that the ensemble is more robust than individual models and that regularized models generate more “conservative” predictions, mitigating the effects of lexical overfitting.However, our error analysis also finds that many of the misclassified instances are debatable, raising questions about the objective annotatability of hate speech data."

# Summary. An optional shortened abstract.
summary: ""


tags: ["Hate Speech","NLP","domain adaptation", "language models"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2023.semeval-1.285.pdf
url_code: https://github.com/MilaNLProc/milanlp-at-edos
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
  caption: 'Confidence scores for each example in the test set, color-coded according to the confusion matrix of our model'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [integrator,monica]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
