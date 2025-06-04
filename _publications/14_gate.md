---
title: "GATE: Graph Attention Transformer Encoder for Cross-lingual Relation and Event Extraction"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Nanyun Peng, and Kai-Wei Chang.'
date: 2/2021
venue: 'AAAI'
paperurl: 'https://arxiv.org/abs/2010.03009'
presentationurl: 'https://wasiahmad.github.io/files/publications/2021/presentation_gate.pdf'
codeurl: 'https://github.com/wasiahmad/GATE'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2010.03009.pdf' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'>
  <img src='https://wasiahmad.github.io/files/publications/2021/Poster_GATE.png' alt='Image not Loading' style='width:800px;' align='middle'>
</div>
<br>

<p align="justify">
Prevalent approaches in cross-lingual relation and event extraction use graph convolutional networks (GCNs) with universal dependency parses to learn 
language-agnostic representations such that models trained on one language can be applied to other languages. However, GCNs lack in modeling long-range 
dependencies or disconnected words in the dependency tree. To address this challenge, we propose to utilize the self-attention mechanism where we explicitly 
fuse structural information to learn the dependencies between words at different syntactic distances. We introduce GATE, 
a <b>G</b>raph <b>A</b>ttention <b>T</b>ransformer <b>E</b>ncoder, and test its cross-lingual transferability on relation and event extraction tasks. 
We perform rigorous experiments on the widely used ACE05 dataset that includes three typologically different languages: English, Chinese, and Arabic. 
The evaluation results show that GATE outperforms three recently proposed methods by a large margin. Our detailed analysis reveals that due to the reliance 
on syntactic dependencies, GATE produces robust representations that facilitate transfer across languages.
</p>

