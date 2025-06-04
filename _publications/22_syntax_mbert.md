---
title: "Syntax-augmented Multilingual BERT for Cross-lingual Transfer"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Haoran Li, Kai-Wei Chang, and Yashar Mehdad.'
date: 05/2021
venue: 'ACL'
paperurl: 'https://aclanthology.org/2021.acl-long.350/'
presentationurl: 'https://www.youtube.com/watch?v=G03p6oe_Lz0'
codeurl: 'https://github.com/wasiahmad/Syntax-MBERT'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2106.02134.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/wasiahmad/Syntax-MBERT' target="_blank">[Source Code]</a>

<p align="justify">
In recent years, we have seen a colossal effort in pre-training multilingual text encoders using large-scale corpora in many languages to facilitate cross-lingual transfer learning. However, due to typological differences across languages, the cross-lingual transfer is challenging. Nevertheless, language syntax, e.g., syntactic dependencies, can bridge the typological gap. Previous works have shown that pretrained multilingual encoders, such as mBERT capture language syntax, helping cross-lingual transfer. This work shows that explicitly providing language syntax and training mBERT using an auxiliary objective to encode the universal dependency tree structure helps cross-lingual transfer. We perform rigorous experiments on four NLP tasks, including text classification, question answering, named entity recognition, and task-oriented semantic parsing. The experiment results show that syntax-augmented mBERT improves cross-lingual transfer on popular benchmarks, such as PAWS-X and MLQA, by 1.4 and 1.6 points on average across all languages. The performance boosted significantly in the generalized transfer setting, with 3.9 and 3.1 points on average in PAWS-X and MLQA.
</p>
