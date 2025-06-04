---
title: "Improving Zero-Shot Cross-Lingual Transfer Learning via Robust Training"
collection: publications
Authors: 'Kuan-Hao Huang, <b>Wasi Uddin Ahmad</b>, Nanyun Peng, and Kai-Wei Chang.'
date: 08/2021
venue: 'EMNLP'
paperurl: 'https://aclanthology.org/2021.emnlp-main.126/'
presentationurl: 'https://aclanthology.org/2021.emnlp-main.126.mp4'
codeurl: 'https://github.com/uclanlp/Robust-XLT'
excerpt: ''
---
---
<a href='https://aclanthology.org/2021.emnlp-main.126.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/uclanlp/Robust-XLT' target="_blank">[Source Code]</a>

<p align="justify">
In recent years, pre-trained multilingual language models, such as multilingual BERT and XLM-R, exhibit good performance on zeroshot cross-lingual transfer  learning. However, since their multilingual contextual embedding spaces for different languages are not perfectly aligned, the difference between representations of different languages might cause zero-shot cross-lingual transfer failed in some cases. In this work, we draw connections between those failed cases and adversarial examples. We then propose to use robust training methods to train a robust model that can tolerate some noise in input embeddings. We study two widely used robust training methods: adversarial training and randomized smoothing. The experimental results demonstrate that robust training can improve zero-shot crosslingual transfer for text classification. The performance improvements become significant when the distance between the source language and the target language increases.
</p>
