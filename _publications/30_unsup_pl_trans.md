---
title: "Summarize and Generate to Back-translate: Unsupervised Translation of Programming Languages"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Saikat Chakraborty, Baishakhi Ray, and Kai-Wei Chang.'
date: 01/2023
venue: 'EACL'
paperurl: 'https://arxiv.org/abs/2205.11116'
codeurl: 'https://github.com/wasiahmad/SumGenToBT'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2205.11116.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/wasiahmad/SumGenToBT' target="_blank">[Source Code]</a>

<p align="justify">
Back-translation is widely known for its effectiveness for neural machine translation when little to no parallel data is available. In this approach, 
  a source-to-target model is coupled with a target-to-source model trained in parallel. The target-to-source model generates noisy sources, while the 
  source-to-target model is trained to reconstruct the targets and vice versa. Recent developments of multilingual pre-trained sequence-to-sequence models 
  for programming languages have been very effective for a broad spectrum of downstream software engineering tasks. Hence, it is compelling to train them 
  to build programming language translation systems via back-translation. However, these models cannot be further trained via back-translation since they 
  learn to output sequences in the same language as the inputs during pre-training. As an alternative, we propose performing back-translation via code 
  summarization and generation. In code summarization, a model learns to generate natural language (NL) summaries given code snippets. In code generation, 
  the model learns to do the opposite. Therefore, target-to-source generation in back-translation can be viewed as target-to-NL-to-source generation. We 
  show that our proposed approach performs competitively with state-of-the-art methods.
</p>

