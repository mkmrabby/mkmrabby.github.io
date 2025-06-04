---
title: "FixEval: Execution-based Evaluation of Program Fixes for Programming Problems"
collection: publications
Authors: 'Md Mahim Anjum Haque, <b>Wasi Uddin Ahmad</b>, Ismini Lourentzou, and Chris Brown.'
date: 02/2023
venue: 'APR'
paperurl: 'https://arxiv.org/abs/2206.07796'
codeurl: 'https://github.com/mahimanzum/FixEval'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2206.07796.pdf' target="_blank">[Download Paper]</a><a href='https://github.com/mahimanzum/FixEval' target="_blank">[Source Code]</a>

<p align="justify">
Source code repositories consist of large codebases, often containing error-prone programs. The increasing complexity of software has led to a drastic 
  rise in time and costs for identifying and fixing these defects. Various methods exist to automatically generate fixes for buggy code. However, due to 
  the large combinatorial space of possible solutions for a particular bug, there are not many tools and datasets available to evaluate generated code 
  effectively. In this work, we introduce FixEval, a benchmark comprising buggy code submissions to competitive programming problems and their respective 
  fixes. We introduce a rich test suite to evaluate and assess the correctness of model-generated program fixes. We consider two Transformer language 
  models pretrained on programming languages as our baselines, and compare them using match-based and execution-based evaluation metrics. Our experiments 
  show that match-based metrics do not reflect model-generated program fixes accurately, while execution-based methods evaluate programs through all cases 
  and scenarios specifically designed for that solution. Therefore, we believe FixEval provides a step towards real-world automatic bug fixing and 
  model-generated code evaluation.
</p>
