---
title: "From Output to Evaluation: Does Raw Instruction-Tuned Code LLMs Output Suffice for Fill-in-the-Middle Code Generation?"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Somshubra Majumdar, and Boris Ginsburg.'
date: 05/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2505.18789'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2505.18789' target="_blank">[Download Paper]</a>
<p align="justify">
Post-processing is crucial for the automatic evaluation of LLMs in fill-in-the-middle (FIM) code generation due to the frequent presence of extraneous code in raw outputs. This extraneous generation suggests a lack of awareness regarding 
  output boundaries, requiring truncation for effective evaluation. However, determining an optimal truncation strategy often proves intricate, particularly when the scope includes several programming languages. This study 
  investigates the necessity of post-processing instruction-tuned LLM outputs. Our findings reveal that supervised fine-tuning significantly enhances FIM code generation, enabling LLMs to generate code that seamlessly integrates with the 
  surrounding context. Evaluating our fine-tuned \texttt{Qwen2.5-Coder} (base and instruct) models on HumanEval Infilling and SAFIM benchmarks demonstrates improved performances without post-processing, especially when the \emph{middle} 
  consists of complete lines. However, post-processing of the LLM outputs remains necessary when the \emph{middle} is a random span of code.
</p>
