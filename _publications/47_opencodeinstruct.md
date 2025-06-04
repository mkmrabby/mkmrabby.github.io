---
title: "OpenCodeInstruct: A Large-scale Instruction Tuning Dataset for Code LLMs"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Aleksander Ficek, Mehrzad Samadi, Jocelyn Huang, Vahid Noroozi, Somshubra Majumdar, and Boris Ginsburg.'
date: 04/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.04030'
dataurl: 'https://huggingface.co/datasets/nvidia/OpenCodeInstruct'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2504.04030' target="_blank">[Download Paper]</a><a href='' target="_blank">[Download Dataset]</a>
<p align="justify">
Large Language Models (LLMs) have transformed software development by enabling code generation, automated debugging, and complex reasoning. However, their continued advancement is constrained by the scarcity of high-quality, 
  publicly available supervised fine-tuning (SFT) datasets tailored for coding tasks. To bridge this gap, we introduce OpenCodeInstruct, the largest open-access instruction tuning dataset, comprising 5 million diverse samples. 
  Each sample includes a programming question, solution, test cases, execution feedback, and LLM-generated quality assessments. We fine-tune various base models, including LLaMA and Qwen, across multiple scales (1B+, 3B+, and 7B+) 
  using our dataset. Comprehensive evaluations on popular benchmarks (HumanEval, MBPP, LiveCodeBench, and BigCodeBench) demonstrate substantial performance improvements achieved by SFT with OpenCodeInstruct. We also present a 
  detailed methodology encompassing seed data curation, synthetic instruction and solution generation, and filtering.
</p>
