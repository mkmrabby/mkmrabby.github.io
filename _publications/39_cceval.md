---
title: "CrossCodeEval: A Diverse and Multilingual Benchmark for Cross-File Code Completion"
collection: publications
Authors: 'Yangruibo Ding<sup>*</sup>, Zijian Wang<sup>*</sup>, <b>Wasi Uddin Ahmad</b><sup>*</sup>, Hantian Ding, Ming Tan, Nihal Jain, Murali Krishna Ramanathan, Ramesh Nallapati, Parminder Bhatia, Dan Roth, and Bing Xiang.'
date: 09/2023
venue: 'NeurIPS Datasets and Benchmarks Track'
paperurl: 'https://arxiv.org/abs/2310.11248'
presentationurl: 'https://www.youtube.com/watch?v=Y80j3H3HPfU'
codeurl: 'https://github.com/amazon-science/cceval'
excerpt: ''
webpage: 'https://crosscodeeval.github.io'
---
---
<a href='https://arxiv.org/pdf/2310.11248.pdf' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
Code completion models have made significant progress in recent years, yet current popular evaluation datasets, such as HumanEval and MBPP, predominantly focus on code completion tasks within a single file. This over-simplified setting falls short of representing the real-world software development scenario where repositories span multiple files with numerous cross-file dependencies, and accessing and understanding cross-file context is often required to complete the code correctly.

To fill in this gap, we propose CrossCodeEval, a diverse and multilingual code completion benchmark that necessitates an in-depth cross-file contextual understanding to complete the code accurately. CrossCodeEval is built on a diverse set of real-world, open-sourced, permissively-licensed repositories in four popular programming languages: Python, Java, TypeScript, and C#. To create examples that strictly require cross-file context for accurate completion, we propose a straightforward yet efficient static-analysis-based approach to pinpoint the use of cross-file context within the current file.

Extensive experiments on state-of-the-art code language models like CodeGen and StarCoder demonstrate that CrossCodeEval is extremely challenging when the relevant cross-file context is absent, and we see clear improvements when adding these context into the prompt. However, despite such improvements, the pinnacle of performance remains notably unattained even with the highest-performing model, indicating that CrossCodeEval is also capable of assessing model's capability in leveraging extensive context to make better code completion. Finally, we benchmarked various methods in retrieving cross-file context, and show that CrossCodeEval can also be used to measure the capability of code retrievers.
</p>
