---
title: "Rethinking Model Selection and Decoding for Keyphrase Generation with Pre-trained Sequence-to-Sequence Models"
collection: publications
Authors: 'Di Wu, <b>Wasi Uddin Ahmad</b>, and Kai-Wei Chang.'
date: 10/2023
venue: 'EMNLP'
paperurl: 'https://arxiv.org/abs/2310.06374'
codeurl: 'https://github.com/uclanlp/DeepKPG'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2310.06374.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/uclanlp/DeepKPG' target="_blank">[Source Code]</a>

<p align="justify">
Keyphrase Generation (KPG) is a longstanding task in NLP with broad applications. The advent of pre-trained language models (PLMs) has recently led to a significant improvement in KPG. 
Nonetheless, several design choices are arbitrary and have not been comprehensively studied. This paper presents a systematic study aimed at benchmarking the impact of model choice and 
decoding strategies on PLM-based KPG. Specifically, we first reflect on why sequence-to-sequence (seq2seq) PLMs are suitable for KPG via an attention-based hypothesis. Then, we reveal that 
the conventional wisdom for selecting seq2seq PLMs is incomplete: (1) scaling up model size or task adaptation alone is parameter inefficient; (2) while in-domain pre-training combined 
with task adaptation significantly benefits KPG, they also compromise generalization to some extent. For decoding, we show that although greedy search achieves strong F1 scores, its recall 
has large rooms for improvement compared to sampling-based approaches. Based on the findings, we introduce DeSel, a probability-based decode-select algorithm that improves greedy search by 
an average of 4.7% semantic F1 over five datasets. Together, our results set a solid foundation for future exploration and study of KPG.
</p>
