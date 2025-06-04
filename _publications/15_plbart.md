---
title: "Unified Pre-training for Program Understanding and Generation"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b><sup>*</sup>, Saikat Chakraborty<sup>*</sup>, Baishakhi Ray, and Kai-Wei Chang.'
date: 03/2021
venue: 'NAACL'
paperurl: 'https://aclanthology.org/2021.naacl-main.211/'
presentationurl: 'https://www.youtube.com/watch?v=VNqVrYtpgTc'
codeurl: 'https://github.com/wasiahmad/PLBART'
excerpt: ''
---
---
<a href='https://aclanthology.org/2021.naacl-main.211.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/wasiahmad/PLBART' target="_blank">[Source Code]</a>

<p align="justify">
Code summarization and generation empower conversion between programming language (PL) and natural language (NL), while code translation avails the migration of legacy code from one PL to another. This paper introduces PLBART, a sequence-to-sequence model capable of performing a broad spectrum of program and language understanding and generation tasks. PLBART is pre-trained on an extensive collection of Java and Python functions and associated NL text via denoising autoencoding. Experiments on language generation tasks, including code summarization, generation, translation in seven programming languages show that PLBART outperforms or rivals state-of-the-art models. Moreover, experiments on discriminative tasks, e.g., program repair, clone detection, and vulnerable code detection demonstrate PLBART's effectiveness in program understanding. Furthermore, analysis reveals that PLBART learns program syntax, style (e.g., identifier naming convention), logical flow (e.g., <i>if</i> block inside an <i>else</i> block is equivalent to <i>else if</i> block) that are crucial to program semantics and thus excels even with limited annotations.
</p>

