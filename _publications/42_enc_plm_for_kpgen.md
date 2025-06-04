---
title: "On Leveraging Encoder-only Pre-trained Language Models for Effective Keyphrase Generation"
collection: publications
Authors: 'Di Wu, <b>Wasi Uddin Ahmad</b>, and Kai-Wei Chang.'
date: 02/2024
venue: 'LREC-COLING'
paperurl: 'https://arxiv.org/abs/2402.14052'
codeurl: 'https://github.com/uclanlp/DeepKPG'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2402.14052.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/uclanlp/DeepKPG' target="_blank">[Source Code]</a>

<p align="justify">
This study addresses the application of encoder-only Pre-trained Language Models (PLMs) in keyphrase generation (KPG) amidst the broader availability of domain-tailored encoder-only models compared to encoder-decoder models. We investigate three core inquiries: (1) the efficacy of encoder-only PLMs in KPG, (2) optimal architectural decisions for employing encoder-only PLMs in KPG, and (3) a performance comparison between in-domain encoder-only and encoder-decoder PLMs across varied resource settings. Our findings, derived from extensive experimentation in two domains reveal that with encoder-only PLMs, although KPE with Conditional Random Fields slightly excels in identifying present keyphrases, the KPG formulation renders a broader spectrum of keyphrase predictions. Additionally, prefix-LM fine-tuning of encoder-only PLMs emerges as a strong and data-efficient strategy for KPG, outperforming general-domain seq2seq PLMs. We also identify a favorable parameter allocation towards model depth rather than width when employing encoder-decoder architectures initialized with encoder-only PLMs. The study sheds light on the potential of utilizing encoder-only PLMs for advancing KPG systems and provides a groundwork for future KPG methods.
</p>
