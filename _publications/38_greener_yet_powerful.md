---
title: "Greener yet Powerful: Taming Large Code Generation Models with Quantization"
collection: publications
Authors: 'Xiaokai Wei, Sujan Gonugondla, <b>Wasi Uddin Ahmad</b>, Shiqi Wang, Baishakhi Ray, Haifeng Qian, Xiaopeng Li, Varun Kumar, Zijian Wang, Yuchen Tian, 
Qing Sun, Ben Athiwaratkun, Mingyue Shang, Murali Krishna Ramanathan, Parminder Bhatia, and Bing Xiang.'
date: 05/2023
venue: 'ESEC/FSE'
paperurl: 'https://arxiv.org/abs/2303.05378'
codeurl: ''
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2303.05378.pdf' target="_blank">[Download Paper]</a><a href='' target="_blank">[Source Code]</a>

<p align="justify">
ML-powered code generation aims to assist developers to write code in a more productive manner, by intelligently generating code blocks based on natural language 
  prompts. Recently, large pretrained deep learning models have substantially pushed the boundary of code generation and achieved impressive performance. Despite 
  their great power, the huge number of model parameters poses a significant threat to adapting them in a regular software development environment, where a 
  developer might use a standard laptop or mid-size server to develop her code. Such large models incur significant resource usage (in terms of memory, latency, 
  and dollars) as well as carbon footprint. Model compression is a promising approach to address these challenges. Several techniques are proposed to compress 
  large pretrained models typically used for vision or textual data. Out of many available compression techniques, we identified that quantization is mostly 
  applicable for code generation task as it does not require significant retraining cost. As quantization represents model parameters with lower-bit integer 
  (e.g., int8), the model size and runtime latency would both benefit from such int representation. We extensively study the impact of quantized model on code 
  generation tasks across different dimension: (i) resource usage and carbon footprint, (ii) accuracy, and (iii) robustness. To this end, through systematic 
  experiments we find a recipe of quantization technique that could run even a 6B model in a regular laptop without significant accuracy or robustness degradation. 
  We further found the recipe is readily applicable to code summarization task as well.
</p>
