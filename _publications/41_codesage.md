---
title: "Code Representation Learning At Scale"
collection: publications
Authors: 'Dejiao Zhang<sup>*</sup>, <b>Wasi Uddin Ahmad</b><sup>*</sup>, Ming Tan, Hantian Ding, Ramesh Nallapati, Dan Roth, Xiaofei Ma, and Bing Xiang.'
date: 05/2024
venue: 'ICLR'
paperurl: 'https://arxiv.org/abs/2402.01935'
codeurl: 'https://github.com/amazon-science/CodeSage'
excerpt: ''
webpage: 'https://code-representation-learning.github.io'
---
---
<a href='https://openreview.net/forum?id=vfzRRjumpX' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
Recent studies have shown that code language models at scale demonstrate significant performance gains on downstream tasks, i.e., code generation. However, most of the existing works on code representation 
  learning train models at a hundred million parameter scale using very limited pretraining corpora. In this work, we fuel code representation learning with a vast amount of code data via a two-stage 
  pretraining scheme. We first train the encoders via a mix that leverages both randomness in masking language modeling and the structure aspect of programming language. We then enhance the representations 
  via contrastive learning with hard negative and hard positive constructed in an unsupervised manner. We establish an off-the-shelf encoder model that persistently outperforms the existing models on a 
  wide variety of downstream tasks by large margins. To comprehend the factors contributing to successful code representation learning, we conduct detailed ablations and share our findings on (i) a 
  customized and effective token-level denoising scheme for source code; (ii) the importance of hard negatives and hard positives; (iii) how the proposed bimodal contrastive learning boost the cross-lingual 
  semantic search performance; and (iv) how the pretraining schemes decide the downstream task performance scales with the model size.
</p>
