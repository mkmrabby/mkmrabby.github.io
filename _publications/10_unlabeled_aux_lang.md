---
title: "Cross-lingual Dependency Parsing with Unlabeled Auxiliary Languages"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Zhisong Zhang, Xuezhe Ma, Kai-Wei Chang, and Nanyun Peng.'
date: 08/2019
venue: 'ACL SIGNLL CoNLL'
paperurl: 'https://aclanthology.org/K19-1035/'
presentationurl: 'https://wasiahmad.github.io/files/publications/2019/presentation_conll19.pdf'
codeurl: 'https://github.com/wasiahmad/cross_lingual_parsing'
excerpt: ''
---
---
<a href='https://aclanthology.org/K19-1035.pdf' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'><img src='https://wasiahmad.github.io/files/publications/2019/auxlang-1.png' 
alt='Image not Loading' style='height:500px;' align='middle'></div><br>

<p align="justify">
Cross-lingual transfer learning has become an important weapon to battle the unavailability of annotated resources for 
low-resource languages. One of the fundamental techniques to transfer across languages is learning language-agnostic 
representations, in the form of word embeddings or contextual encodings. In this work, we propose to leverage unannotated 
sentences from auxiliary languages to help learning language-agnostic representations. Specifically, we explore adversarial 
training for learning contextual encoders that produce invariant representations across languages to facilitate cross-lingual
transfer. We conduct experiments on cross-lingual dependency parsing where we train a dependency parser on a source language
and transfer it to a wide range of target languages. Experiments on 28 target languages demonstrate that adversarial training 
significantly improves the overall transfer performances under several different settings. We conduct a careful analysis to 
evaluate the language-agnostic representations resulted from adversarial training.
</p>
