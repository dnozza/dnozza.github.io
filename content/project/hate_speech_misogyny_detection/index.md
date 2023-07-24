---
aliases: [hatespeech]
title: Hate Speech and Misogyny Detection
summary: How fair Machine Learning models could solve Hate Speech and Misogyny Detection?
abstract: ""
date: "2020-01-27T00:00:00Z"
image:
  caption: '[Photo by Kyle Glenn on Unsplash](https://unsplash.com/photos/kvIAk3J_A1c)'

  focal_point: Smart

categories:
- hate speech
tags:
- hate speech
- misogyny detection
- nlp
---



While the exponential growth of **Social Media** such as Twitter and Facebook has permit people to freely express themselves in various forms (text, video, images), these new sources of communication, where anonymity or pseudo-anonymity enables the possibility to afflict a target without being recognized or traced, has led to an increasing propagation of hate speech. Automatic Machine Learning models for the detection of **Hate Speech** could help in preventing or automatically reporting these misbehaviors and consequently reduce the episodes of misogyny, racism, homophobia and cyberbullying. This could be helpful both for protecting individuals’ health and also to monitor public reactions to events.

In order to provide a benchmark dataset for **Hate Speech** and **Misogyny Detection**, I have contributed to the organization of the [Automatic Misogyny Identification(AMI) shared task at Evalita 2018](https://dnozza.github.io/publication/2018_automatic_misogyny_identification/) and [2020](https://dnozza.github.io/publication/2020_automatic_misogyny_identification/) in Italian and English language and of the [HatEval task at SemEval 2019](https://dnozza.github.io/publication/2019_semeval_hateval/) about the detection of hate speech against immigrants and women in Spanish and English messages extracted from Twitter.

*These tasks permit to create and share the first labelled corpora for misogyny detection in Spanish and Italian. I firmly believe that we still have a long way to go: there are 3,909 written languages in the world, most without misogyny data sets. Moreover, we need to assure that data collection methodologies are the same across all languages in order for them to be valuable.* 🌎🌍🌏

In my paper at ACL 2021, I demonstrated that [zero-shot, cross-lingual transfer learning framework, in its traditional settings, is not a feasible solution for solving the lack of models and labeled corpora for hate speech detection](https://dnozza.github.io/publication/2021-zeroshot-crosslingual-hate-speech/). Limits are related to the high presence of language- and target-specific taboo interjections in non-hateful contexts, like porca puttana in Italian or puta in Spanish.
*I argue that hate speech is **language specific**, and NLP approaches to identifying hate speech must account for that specificity.* 🔍

Further limitations of creating hate speech detection models can be found on popularly employed pretrained language models. Indeed, in my paper presented at NAACL 2021, I show that [4.3% of the time language models complete a sentence with a hurtful word (sentence completions refer to sexual promiscuity when the target is female in 9% of the time, and in 4% to homosexuality when the target is male)](https://dnozza.github.io/publication/2021-honest-hurtful-language-model/)⚠️. When the subjects belong to the LGBTQIA+ community, the problem is even higher: [the most likely LLM-generated completion is an identity attack 13% of the time](https://dnozza.github.io/publication/2022-honest-hurtful-language-model-lgbtqia+/) (published at LT-EDI workshop at ACL 2022). For sistematicaly measure this issue, we propose [HONEST](https://github.com/MilaNLProc/honest) a score to measure hurtful sentence completions in any language models.

In my work presented at International Conference on Web Intelligence (WI '19), I made some additional investigation on the [presence of unintended bias in machine learning models for **Misogyny Detection**](https://dnozza.github.io/publication/2021-zeroshot-crosslingual-hate-speech/). This can lead the models to recognize positive or neutral texts as hate speech texts only because it contains certain terms (e.g. woman, girl), not guaranteeing **fairness**. *Can you imagine seeing "You're a smart woman" predicted as misogynous just because it's talking about women?* 🤦‍♀️ 
[Exploring post-hoc interpretability models for misogyny detection](https://dnozza.github.io/publication/2022-interpretability-transformer-mysogyny-detection/), further demonstrated this problem. Models (like BERT) are paying too much attention to words that do not carry misogynous meaning (e.g. woman) (published at NLP-Power workshop at ACL 2022).

In my recent paper at ACL 2022 findings, we introduce a novel technique to exactly counteract this issue of unintended bias. We propose [Entropy-based Attention Regularization (EAR 👂)](https://dnozza.github.io/publication/2022-entropy-attention-regularization-bias/) to discourage overfitting to training-specific terms of Transformer-based models (e.g., BERT). The resulting model matches or exceeds state-of-the-art performance for hate speech classification and bias metrics on three benchmark corpora in English and Italian


🎙️🎙️ Check out my latest **interview** on [Ethics and bias in Artificial Intelligence](https://www.youtube.com/watch?v=kU8zvmifyHE&t=3s)!!
