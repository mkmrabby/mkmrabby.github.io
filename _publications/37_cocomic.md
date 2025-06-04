---
title: "CoCoMIC: Code Completion By Jointly Modeling In-file and Cross-file Context"
collection: publications
Authors: 'Yangruibo Ding<sup>*</sup>, Zijian Wang<sup>*</sup>, <b>Wasi Uddin Ahmad</b><sup>*</sup>, Murali Krishna Ramanathan, Ramesh Nallapati, Parminder Bhatia, Dan Roth, and Bing Xiang.'
date: 02/2024
venue: 'LREC-COLING'
paperurl: 'https://arxiv.org/abs/2212.10007'
codeurl: 'https://github.com/amazon-science/cocomic'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2212.10007.pdf' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
While pre-trained language models (LM) for code have achieved great success in code completion, they generate code conditioned only on the contents 
  within the file, i.e., in-file context, but ignore the rich semantics in other files within the same project, i.e., cross-file context, a critical source of information that is 
  especially useful in modern modular software development. Such overlooking constrains code language models’ capacity in code completion, leading to 
  unexpected behaviors such as generating hallucinated class member functions or function calls with unexpected arguments. In this work, we develop a 
  cross-file context finder tool, CCFinder, that effectively locates and retrieves the most relevant cross-file context. We propose CoCoMIC, a framework 
  that incorporates cross-file context to learn the in-file and cross-file context jointly on top of pretrained code LMs. CoCoMIC successfully improves the 
  existing code LM with a 19.30% relative increase in exact match and a 15.41% relative increase in identifier matching for code completion when the 
  cross-file context is provided. 
</p>
