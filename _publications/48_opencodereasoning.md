---
title: "OpenCodeReasoning: Advancing Data Distillation for Competitive Coding"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b><sup>*</sup>, Sean Narenthiran<sup>*</sup>, Somshubra Majumdar, Aleksander Ficek, Siddhartha Jain, Jocelyn Huang, Vahid Noroozi, and Boris Ginsburg.'
date: 04/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.01943'
dataurl: 'https://huggingface.co/datasets/nvidia/OpenCodeReasoning'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2504.01943' target="_blank">[Download Paper]</a><a href='https://huggingface.co/datasets/nvidia/OpenCodeReasoning' target="_blank">[Download Dataset]</a>
<p align="justify">
Since the advent of reasoning-based large language models, many have found great success from distilling reasoning capabilities into student models. Such techniques have significantly bridged the gap between reasoning and 
standard LLMs on coding tasks. Despite this, much of the progress on distilling reasoning models remains locked behind proprietary datasets or lacks details on data curation, filtering and subsequent training. To address this, 
we construct a superior supervised fine-tuning (SFT) dataset that we use to achieve state-of-the-art coding capability results in models of various sizes. Our distilled models use only SFT to achieve 61.8% on LiveCodeBench 
and 24.6% on CodeContests, surpassing alternatives trained with reinforcement learning. We then perform analysis on the data sources used to construct our dataset, the impact of code execution filtering, and the importance of 
instruction/solution diversity. We observe that execution filtering negatively affected benchmark accuracy, leading us to prioritize instruction diversity over solution correctness. Finally, we also analyze the token efficiency 
and reasoning patterns utilized by these models. We will open-source these datasets and distilled models to the community.
</p>
