---
title: "Llama-Nemotron: Efficient Reasoning Models"
collection: publications
Authors: 'NVIDIA: <b>Wasi Uddin Ahmad</b> (Contributed to Data), and 123 others.'
date: 05/2025
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2505.00949v1'
dataurl: 'https://huggingface.co/datasets/nvidia/Llama-Nemotron-Post-Training-Dataset'
modelurl: 'https://huggingface.co/nvidia/Llama-3_1-Nemotron-Ultra-253B-v1'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2505.00949v1' target="_blank">[Paper]</a><a href='https://huggingface.co/collections/nvidia/llama-nemotron-67d92346030a2691293f200b' target="_blank">[Models and Datasets]</a>
<p align="justify">
We introduce the Llama-Nemotron series of models, an open family of heterogeneous reasoning models that deliver exceptional reasoning capabilities, inference efficiency, and an open license for enterprise use. The family comes in three sizes -- Nano (8B), Super (49B), and Ultra (253B) -- and performs competitively with state-of-the-art reasoning models such as DeepSeek-R1 while offering superior inference throughput and memory efficiency. In this report, we discuss the training procedure for these models, which entails using neural architecture search from Llama 3 models for accelerated inference, knowledge distillation, and continued pretraining, followed by a reasoning-focused post-training stage consisting of two main parts: supervised fine-tuning and large scale reinforcement learning. Llama-Nemotron models are the first open-source models to support a dynamic reasoning toggle, allowing users to switch between standard chat and reasoning modes during inference. To further support open research and facilitate model development, we provide the following resources: 1. We release the Llama-Nemotron reasoning models -- LN-Nano, LN-Super, and LN-Ultra -- under the commercially permissive NVIDIA Open Model License Agreement. 2. We release the complete post-training dataset: Llama-Nemotron-Post-Training-Dataset. 3. We also release our training codebases: NeMo, NeMo-Aligner, and Megatron-LM.
</p>
