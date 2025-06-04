---
title: "IllusionVQA: A Challenging Optical Illusion Dataset for Vision Language Models"
collection: publications
Authors: 'Haz Sameen Shahgir<sup>*</sup>, Khondker Salman Sayeed<sup>*</sup>, Abhik Bhattacharjee, <b>Wasi Uddin Ahmad</b>, Yue Dong, and Rifat Shahriyar.'
date: 07/2024
venue: 'COLM'
paperurl: 'https://arxiv.org/abs/2403.15952'
codeurl: 'https://github.com/csebuetnlp/IllusionVQA'
excerpt: ''
webpage: 'https://illusionvqa.github.io/'
---
---
<a href='https://arxiv.org/pdf/2403.15952.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/csebuetnlp/IllusionVQA' target="_blank">[Source Code]</a>

<p align="justify">
The advent of Vision Language Models (VLM) has allowed researchers to investigate the visual understanding of a neural network using natural language. Beyond object classification and detection, VLMs are capable of visual comprehension and common-sense reasoning. This naturally led to the question: How do VLMs respond when the image is inherently unreasonable? To this end, we present IllusionVQA: a diverse dataset of challenging optical illusions and hard-to-interpret scenes to test the capability of VLMs in two distinct multiple-choice VQA tasks - comprehension and soft localization. GPT4V, the best performing VLM, achieves 62.99% accuracy (4-shot) on the comprehension task and 49.7% on the localization task (4-shot and Chain-of-Thought). Human evaluation reveals that humans achieve 91.03% and 100% accuracy in comprehension and localization. We discover that In-Context Learning (ICL) and Chain-of-Thought reasoning substantially degrade the performance of GeminiPro on the localization task. Tangentially, we find out a potential weakness in the ICL capabilities of VLMs: they fail to locate optical illusions even when the correct answer is in the context window as a few-shot example.
</p>
