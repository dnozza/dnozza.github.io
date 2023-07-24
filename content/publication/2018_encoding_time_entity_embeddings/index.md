---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Towards encoding time in text-based entity embeddings"
authors: ["Federico Bianchi","Matteo Palmonari","Debora Nozza"]
date: 2018-09-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-29T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[International Semantic Web Conference (ISWC 2018)](http://iswc2018.semanticweb.org/)"
publication_short: "International Semantic Web Conference"

abstract: "Knowledge Graphs (KG) are widely used abstractions to represent entity-centric knowledge. Approaches to embed entities, entity types and relations represented in the graph into vector spaces - often referred to as KG embeddings - have become increasingly popular for their ability to capture the similarity between entities and support other reasoning tasks. However, representation of time has received little attention in these approaches. In this work, we make a first step to encode time into vector-based entity representations using a text-based KG embedding model named Typed Entity Embeddings (TEEs). In TEEs, each entity is represented by a vector that represents the entity and its type, which is learned from entity mentions found in a text corpus. Inspired by evidence from cognitive sciences and application-oriented concerns, we propose an approach to encode representations of years into TEEs by aggregating the representations of the entities that occur in event-based descriptions of the years. These representations are used to define two time-aware similarity measures to control the implicit effect of time on entity similarity. Experimental results show that the linear order of years obtained using our model is highly correlated with natural time flow and the effectiveness of the time-aware similarity measure proposed to flatten the time effect on entity similarity."

# Summary. An optional shortened abstract.
summary: ""


tags: ["Representation learning","Time","NLP"]
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
url_code:
url_dataset:
url_poster:
url_project:
url_slides: "http://videolectures.net/site/normal_dl/tag=1204252/iswc2018_bianchi_towards_encoding_time_01.pdf"
url_source: "https://link.springer.com/chapter/10.1007%2F978-3-030-00671-6_4"
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
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
