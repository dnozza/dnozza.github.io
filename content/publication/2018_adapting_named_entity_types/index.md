---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Adapting Named Entity Types to New Ontologies in a Microblogging Environment"
authors: ["Elisabetta Fersini","Pikakshi Manchanda","Enza Messina","Debora Nozza","Matteo Palmonari"]
date: 2018-05-01
doi: "https://doi.org/10.1007/978-3-319-92058-0_76"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-02-29T14:48:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "[International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems (IEA-AIE 2018)](http://ieaaie2018.encs.concordia.ca/)"
publication_short: "International Conference on Industrial, Engineering and Other Applications of Applied Intelligent Systems"

abstract: "Given the potential rise in the amount of user-generated content on social network, research efforts towards Information Extraction have significantly increased, giving leeway to the emergence of numerous *Named Entity Recognition* (NER) systems. Based on varying application scenarios and/or requirements, different NER systems use different entity classification schemas/ontologies to classify the discovered entity mentions into entity types. Indeed, comparisons and integrations among NER systems become complex. The situation is further worsened due to varying granularity levels of such ontologies used to train the NER systems. This problem has been approached in the state of the art by developing a deterministic manual mapping between concepts belonging to different ontologies. In this paper, we discuss the limitations of these methods and, inspired by a transfer learning paradigm, we propose a novel approach named LearningToAdapt (L2A) to mitigate them. L2A learns to transfer an input probability distribution over a set of ontology types defined in a source domain, into a probability distribution over the types of a new ontology in a target domain. By using the inferred probability distribution, we are able to re-classify the entity mentions using the most probable type in the target domain. Experiments conducted with benchmark data show remarkable performance, suggesting L2A as a promising approach for domain adaptation of NER systems."

# Summary. An optional shortened abstract.
summary: ""


tags: ["Named Entity Recognition","Domain Adaptation","Social Media","NLP"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://link.springer.com/chapter/10.1007/978-3-319-92058-0_76"
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
  caption: "Photo by [IEA-AIE](http://ieaaie2018.encs.concordia.ca/gallery.html)"
  focal_point: "BottomLeft"
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
