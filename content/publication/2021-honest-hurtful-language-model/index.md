---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "HONEST: Measuring Hurtful Sentence Completion in Language Models"
authors: ["Debora Nozza","Federico Bianchi","Dirk Hovy"]
date: 2021-06-06
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-29T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics](https://2021.naacl.org/)"
publication_short: "2021 Annual Conference of the North American Chapter of the Association for Computational Linguistics"

abstract: "Language models have revolutionized the field of NLP. However, language models capture and proliferate hurtful stereotypes, especially in text generation. Our results show that **4.3% of the time, language models complete a sentence with a hurtful word**. These cases are not random, but follow language and gender-specific patterns. We propose a score to measure hurtful sentence completions in language models (HONEST). It uses a systematic template- and lexicon-based bias evaluation methodology for six languages. Our findings suggest that these models replicate and amplify deep-seated societal stereotypes about gender roles. Sentence completions refer to sexual promiscuity when the target is female in 9% of the time, and in 4% to homosexuality when the target is male.  The results raise questions about the use of these models in production settings."

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

url_pdf: https://www.aclweb.org/anthology/2021.naacl-main.191.pdf
url_code:
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
  caption: 'Examples of hurtful sentence completions'
  focal_point: "Center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [hate_speech_misogyny_detection]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
