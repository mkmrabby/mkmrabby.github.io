---
title: "On Difficulties of Cross-Lingual Transfer with Order Differences: A Case Study on Dependency Parsing"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b><sup>*</sup>, Zhisong Zhang<sup>*</sup>, Xuezhe Ma, Eduard Hovy, Kai-Wei Chang, and Nanyun Peng.'
date: 03/2019
venue: 'NAACL'
paperurl: 'https://aclanthology.org/N19-1253/'
presentationurl: 'https://www.youtube.com/watch?v=YuFI0DOw8N0'
codeurl: 'https://github.com/uclanlp/CrossLingualDepParser'
excerpt: ''
---
---
<a href='https://aclanthology.org/N19-1253.pdf' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'>
  <img src='https://wasiahmad.github.io/files/publications/2019/word_order-2.png' alt='Image not Loading' style='width:700px;' align='middle'>
</div>
<br>

<p align="justify">
Different languages might have different word orders. In this paper, we investigate crosslingual transfer and posit that an orderagnostic model will perform better when transferring to distant foreign languages. To test our hypothesis, we train dependency parsers on an English corpus and evaluate their transfer performance on 30 other languages. Specifically, we compare encoders and decoders based on Recurrent Neural Networks (RNNs) and modified self-attentive architectures. The former relies on sequential information while the latter is more flexible at modeling word order. Rigorous experiments and detailed analysis shows that RNN-based architectures transfer well to languages that are close to English, while self-attentive models have better overall cross-lingual transferability and perform especially well on distant languages.
</p>
