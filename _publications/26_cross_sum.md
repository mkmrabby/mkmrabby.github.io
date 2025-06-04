---
title: "CrossSum: Beyond English-Centric Cross-Lingual Abstractive Text Summarization for 1500+ Language Pairs"
collection: publications
Authors: 'Tahmid Hasan, Abhik Bhattacharjee, <b>Wasi Uddin Ahmad</b>, Yuan-Fang Li, Yong-Bin Kang, and Rifat Shahriyar.'
date: 05/2023
venue: 'ACL'
paperurl: 'https://aclanthology.org/2023.acl-long.143'
codeurl: 'https://github.com/csebuetnlp/CrossSum'
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.acl-long.143' target="_blank">[Download Paper]</a><a href='https://github.com/csebuetnlp/CrossSum' target="_blank">[Source Code]</a>

<p align="justify">
We present CrossSum, a large-scale dataset comprising 1.65 million cross-lingual article-summary samples in 1500+ language-pairs constituting 45 languages. 
  We use the multilingual XL-Sum dataset and align identical articles written in different languages via cross-lingual retrieval using a language-agnostic 
  representation model. We propose a multi-stage data sampling algorithm and fine-tune mT5, a multilingual pretrained model, with explicit cross-lingual 
  supervision with CrossSum and introduce a new metric for evaluating cross-lingual summarization. Results on established and our proposed metrics indicate that 
  models fine-tuned on CrossSum outperforms summarization+translation baselines, even when the source and target language pairs are linguistically distant. To 
  the best of our knowledge, CrossSum is the largest cross-lingual summarization dataset and also the first-ever that does not rely on English as the pivot 
  language. We are releasing the dataset, alignment and training scripts, and the models to spur future research on cross-lingual abstractive summarization. 
  The resources can be found at <a href='https://github.com/csebuetnlp/CrossSum'>this https URL</a>.
</p>
