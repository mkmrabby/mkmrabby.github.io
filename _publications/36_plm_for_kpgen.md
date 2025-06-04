---
title: "Pre-trained Language Models for Keyphrase Generation: A Thorough Empirical Study"
collection: publications
Authors: 'Di Wu, <b>Wasi Uddin Ahmad</b>, and Kai-Wei Chang.'
date: 12/2022
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2212.10233'
codeurl: 'https://github.com/uclanlp/DeepKPG'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2212.10233.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/uclanlp/DeepKPG' target="_blank">[Source Code]</a>

<p align="justify">
Neural models not relying on pre-training have excelled in the keyphrase generation task with large annotated datasets. Meanwhile, new approaches have 
  incorporated pre-trained language models (PLMs) for data efficiency. However, there is a lack of systematic study of how the two types of approaches compare 
  and how different design choices can affect the performance of PLM-based models. We present an in-depth empirical study to fill this knowledge gap and 
  facilitate a more informed use of PLMs for keyphrase extraction and generation. We perform extensive experiments in three domains by formulating 
  keyphrase extraction as sequence labeling and keyphrase generation as sequence-to-sequence generation. After showing that PLMs have competitive 
  high-resource performance and state-of-the-art low-resource performance, we investigate important design choices, including in-domain PLMs, PLMs with 
  different pre-training objectives, using PLMs with a parameter budget, and different formulations for present keyphrases. Further results show that 
  (1) in-domain BERT-like PLMs can be used to build strong and data-efficient keyphrase generation models; (2) with a fixed parameter budget, prioritizing 
  model depth over width and allocating more layers in the encoder leads to better encoder-decoder models; and (3) introducing four in-domain PLMs, we 
  achieve a competitive performance in the news domain and the state-of-the-art performance in the scientific domain.
</p>
