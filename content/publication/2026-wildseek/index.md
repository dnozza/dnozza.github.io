---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "WildSEEK: Evaluating Language Models for Information-Seeking"
authors:
- Tanise Ceron
- Joachim Baumann
- Elisa Bassignana
- Berat Cabuk
- Dirk Hovy
- Debora Nozza
date: "2026-10-01"
doi: "10.18653/2026.emnlp-main.763"
publishDate: "2026-10-01"
publication_types:
- "1"
publication: "Conference on Empirical Methods in Natural Language Processing"
publication_short: "EMNLP 2026"
abstract: "Language models are increasingly mediating information access to end users, urging a systematic evaluation of their responses for a fair and reliable information ecosystem. Existing evaluations, however, are often topic-specific or synthetic, limiting their ability to capture the complexity of \"in the wild\" information-seeking queries and the risks present in model responses. To address this gap, we introduce WildSEEK, a manually annotated dataset of 3k information-seeking queries from real user interactions, and an evaluation framework for LLM-generated responses. WildSEEK includes annotations for risk-sensitive domains (e.g. health and financial information), and distinguishes factoid queries from analytical queries which seek responses beyond facts. We train classifiers on WildSEEK to analyze more than 1.8M realistic user queries. We find that over a third of information-seeking queries are high-risk and more often analytical. Our findings show that LLM responses fail more often in four criteria: sycophantic behavior, overreliance, a default US-centric perspective, and poor handling of vulnerable populations—with failure rates being mostly higher for analytical queries. By providing methods to monitor the reliability, safety, and fairness of LLM behavior, our dataset and evaluation framework offer an empirical foundation for the broader question of how these systems should behave as they take on a growing role in information access."
summary: "WildSEEK introduces real-world information-seeking queries and an evaluation framework for assessing the reliability, safety, and fairness of language-model responses."
tags:
- information seeking
- LLM evaluation
- safety
- fairness
categories: []
featured: false
url_pdf: "https://aclanthology.org/2026.emnlp-main.763.pdf"
url_code: ""
url_dataset: "https://huggingface.co/datasets/tceron/wildseek"
url_poster: ""
url_project: ""
url_slides: ""
url_source: "https://github.com/tceron/wildseek-eval"
url_video: ""
socialmedia_post: '''WildSeek'' by @tanise et al. (2026) ask how often people ask information-seeking queries, what risks they face, and what challenges the evaluation of LLMs in the context of information seeking.'
image:
  caption: ''
  focal_point: Center
  preview_only: false
projects:
- integrator
- personae
slides: ""
---
