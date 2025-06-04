---
title: "Retrieval Enhanced Data Augmentation for Question Answering on Privacy Policies"
collection: publications
Authors: 'Md Rizwan Parvez, Jianfeng Chi, <b>Wasi Uddin Ahmad</b>, Yuan Tian, and Kai-Wei Chang.'
date: 01/2023
venue: 'EACL'
paperurl: 'https://arxiv.org/abs/2204.08952'
codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2204.08952.pdf' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
Prior studies in privacy policies frame the question answering (QA) tasks as identifying the most relevant text segment or a list of sentences from the 
  policy document for a user query. However, annotating such a dataset is challenging as it requires specific domain expertise (e.g., law academics). 
  Even if we manage a small-scale one, a bottleneck that remains is that the labeled data are heavily imbalanced (only a few segments are relevant) - 
  limiting the gain in this domain. Therefore, in this paper, we develop a novel data augmentation framework based on ensembling retriever models that 
  captures the relevant text segments from unlabeled policy documents and expand the positive examples in the training set. In addition, to improve the 
  diversity and quality of the augmented data, we leverage multiple pre-trained language models (LMs) and cascaded them with noise reduction oracles. 
  Using our augmented data on the PrivacyQA benchmark, we elevate the existing baseline by a large margin (10% F1) and achieve a new state-of-the-art 
  F1 score of 50%. Our ablation studies provide further insights into the effectiveness of our approach.
</p>
