---
title: "LibEvolutionEval: A Benchmark and Study for Version-Specific Code Generation"
collection: publications
Authors: 'Sachit Kuhar, <b>Wasi Uddin Ahmad</b>, Zijian Wang, Nihal Jain, Haifeng Qian, Baishakhi Ray, Murali Krishna Ramanathan, Xiaofei Ma, and Anoop Deoras.'
date: 01/2025
venue: 'NAACL'
paperurl: 'https://arxiv.org/abs/2412.04478'
codeurl: ''
excerpt: ''
webpage: 'https://lib-evolution-eval.github.io/'
---
---
<a href='https://arxiv.org/pdf/2412.04478' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
Recent advancements in code completion models have primarily focused on local file contexts. However, these studies do not fully capture the complexity of real-world software development, which often requires the use of rapidly evolving public libraries. To fill the gap, we introduce LibEvolutionEval, a detailed study requiring an understanding of library evolution to perform in-line code completion accurately. LibEvolutionEval provides a version-specific code-completion task comprised of eight libraries (torch, torchvision, scipy, pil, tqdm, pyyaml, matplotlib, and pandas) as they evolve over the year along with a detailed analysis of the evolution of two popular and well-maintained public libraries: PyTorch and Matplotlib. We evaluate popular public models and find that public library evolution significantly influences model performance. We explored mitigation methods by studying how retrieved version-specific library documentation and prompting can improve the model's capability in handling these fast-evolving packages, paving a promising future path in better handling fast-evolving libraries.
</p>
