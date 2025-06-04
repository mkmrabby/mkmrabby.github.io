---
title: "Genetic Instruct: Scaling up Synthetic Generation of Coding Instructions for Large Language Models"
collection: publications
Authors: 'Somshubra Majumdar, Vahid Noroozi, Mehrzad Samadi, Sean Narenthiran, Aleksander Ficek, <b>Wasi Uddin Ahmad</b>, Jocelyn Huang, Jagadeesh Balam, and Boris Ginsburg.'
date: 05/2025
venue: 'ACL (Industry Track)'
paperurl: 'https://arxiv.org/abs/2407.21077'
codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2407.21077' target="_blank">[Download Paper]</a><a href='' target="_blank">[Download Dataset]</a>
<p align="justify">
Large Language Models (LLMs) require high quality instruction data for effective alignment, particularly in code generation tasks where expert curated datasets are expensive to produce. We present Genetic-Instruct, a scalable algorithm for synthesizing large-scale, high quality coding instructions using evolutionary principles. Starting from a small set of seed instructions, Genetic-Instruct generates diverse and challenging instruction-code pairs by leveraging an Instructor-LLM for generation, a Coder-LLM for code synthesis, and a Judge-LLM for automatic quality evaluation. Our proposed approach is highly parallelizable and effective even with a small seed data and weaker generator models. We generated more than 7.5 million coding instructions with the proposed approach. Then we evaluated it by fine-tuning LLMs with the synthetic samples and demonstrated a significant improvement in their code generation capability compared to the other synthetic generation approaches and publicly available datasets. Our results highlight the efficiency, scalability, and generalizability of the Genetic-Instruct framework.
</p>
