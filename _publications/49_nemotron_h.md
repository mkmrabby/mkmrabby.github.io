---
title: "Nemotron-H: A Family of Accurate and Efficient Hybrid Mamba-Transformer Models"
collection: publications
Authors: 'NVIDIA: <b>Wasi Uddin Ahmad</b> (Contributed to Data), and 198 others.'
date: 04/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2504.03624'
modelurl: 'https://huggingface.co/nvidia/Nemotron-H-56B-Base-8K'
webpage: 'https://research.nvidia.com/labs/adlr/nemotronh/'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2504.03624' target="_blank">[Download Paper]</a><a href='' target="_blank">[Download Dataset]</a>
<p align="justify">
As inference-time scaling becomes critical for enhanced reasoning capabilities, it is increasingly becoming important to build models that are efficient to infer. We introduce Nemotron-H, a family of 8B and 56B/47B hybrid Mamba-Transformer models designed to reduce inference cost for a given accuracy level. To achieve this goal, we replace the majority of self-attention layers in the common Transformer model architecture with Mamba layers that perform constant computation and require constant memory per generated token. We show that Nemotron-H models offer either better or on-par accuracy compared to other similarly-sized state-of-the-art open-sourced Transformer models (e.g., Qwen-2.5-7B/72B and Llama-3.1-8B/70B), while being up to 3× faster at inference. To further increase inference speed and reduce the memory required at inference time, we created Nemotron-H-47B-Base from the 56B model using a new compression via pruning and distillation technique called MiniPuzzle. Nemotron-H-47B-Base achieves similar accuracy to the 56B model, but is 20% faster to infer. In addition, we introduce an FP8-based training recipe and show that it can achieve on par results with BF16-based training. This recipe is used to train the 56B model. All Nemotron-H models will be released, with support in Hugging Face, NeMo, and Megatron-LM.
</p>
