---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "What the [MASK]? Making Sense of Language-Specific BERT Models"
authors: ["Debora Nozza","Federico Bianchi","Dirk Hovy"]
date: 2020-03-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-29T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint arXiv:2003.02912"
publication_short: ""

abstract: "Recently, Natural Language Processing (NLP) has witnessed an impressive progress in many areas, due to the advent of novel, pretrained contextual representation models. In particular, Devlin et al. (2019) proposed a model, called BERT (Bidirectional Encoder Representations from Transformers), which enables researchers to obtain state-of-the art performance on numerous NLP tasks by fine-tuning the representations on their data set and task, without the need for developing and training highly-specific architectures. The authors also released multilingual BERT (mBERT), a model trained on a corpus of 104 languages, which can serve as a universal language model. This model obtained impressive results on a zero-shot cross-lingual natural inference task. Driven by the potential of BERT models, the NLP community has started to investigate and generate an abundant number of BERT models that are trained on a particular language, and tested on a specific data domain and task. This allows us to evaluate the true potential of mBERT as a universal language model, by comparing it to the performance of these more specific models. This paper presents the current state of the art in language-specific BERT models, providing an overall picture with respect to different dimensions (i.e. architectures, data domains, and tasks). Our aim is to provide an immediate and straightforward overview of the commonalities and differences between Language-Specific (language-specific) BERT models and mBERT. We also provide an interactive and constantly updated website that can be used to explore the information we have collected, at [https://bertlang.unibocconi.it](https://bertlang.unibocconi.it/)."

# Summary. An optional shortened abstract.
summary: ""


tags: ["multilingual","BERT","Representation learning","NLP"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code: "https://github.com/MilaNLProc/bertlang"
url_dataset:
url_poster:
url_project: "https://bertlang.unibocconi.it/"
url_slides: 
url_source: "https://arxiv.org/abs/2003.02912"
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "https://bertlang.unibocconi.it/"
  focal_point: "Left"
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
