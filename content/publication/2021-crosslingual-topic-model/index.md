---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Cross-lingual Contextualized Topic Models with Zero-shot Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Federico Bianchi
- Silvia Terragni
- Dirk Hovy
- Debora Nozza
- Elisabetta Fersini

# Author notes (optional)
#author_notes:


date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Proceedings of *The 16th Conference of the European Chapter of the Association for Computational Linguistics*
publication_short: In *EACL*

abstract: Many data sets (e.g., reviews, forums, news, etc.) exist parallelly in multiple languages. They all cover the same content, but the linguistic differences make it impossible to use traditional, bag-of-word-based topic models. Models have to be either single-language or suffer from a huge, but extremely sparse vocabulary. Both issues can be addressed by transfer learning. In this paper, we introduce a zero-shot cross-lingual topic model. Our model learns topics on one language (here, English), and predicts them for unseen documents in different languages (here, Italian, French, German, and Portuguese). We evaluate the quality of the topic predictions for the same document in different languages. Our results show that the transferred topics are coherent and stable across languages, which suggests exciting future research directions.

# Summary. An optional shortened abstract.
summary: We introduce a novel topic modeling method that can make use of contextulized embeddings (e.g., BERT) to do zero-shot cross-lingual topic modeling.

tags: ["NLP", "Topic Modeling", "BERT", "Language Models"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
 - name: Blog Post
   url: https://fbvinid.medium.com/contextualized-topic-modeling-with-python-eacl2021-eacf6dfa576

url_pdf: 'https://www.aclweb.org/anthology/2021.eacl-main.143.pdf'
url_code: 'https://github.com/MilaNLProc/contextualized-topic-models'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://docs.google.com/presentation/d/11Yb8n3BwQAAGhnIwKCI2n9DNYmVCcec-JRFAwQVvwK8/edit?usp=sharing'
url_source: ''
url_video: ''



# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Our Model, ZeroShotTM'
  focal_point: ""
  preview_only: false

---
