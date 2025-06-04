---
title: "Select, Extract and Generate: Neural Keyphrase Generation with Layer-wise Coverage Attention"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Xiao Bai, Soomin Lee, and Kai-Wei Chang.'
date: 05/2021
venue: 'ACL'
paperurl: 'https://aclanthology.org/2021.acl-long.111/'
presentationurl: 'https://www.youtube.com/watch?v=7oQbMqEiESE'
excerpt: ''
---
---
<a href='https://arxiv.org/pdf/2008.01739.pdf' target="_blank">[Download Paper]</a>
<div style='display: flex; justify-content: center;'><img src='https://wasiahmad.github.io/files/publications/2020/seg_net.png' 
alt='Image not Loading' style='height:700px;' align='middle'></div>
<div style='display: flex; justify-content: center;'><p>
  <b>Figure:</b>  Overview of the Extractor-Generator module of our proposed model, SEG-Net.<br>
</p></div>


<p align="justify">
In recent years, deep neural sequence-to-sequence framework has demonstrated promising results in keyphrase generation. However, processing long documents using such deep neural networks requires high computational resources. To reduce the computational cost, the documents are typically truncated before given as inputs. As a result, the models may miss essential points conveyed in a document. Moreover, most of the existing methods are either extractive (identify important phrases from the document) or generative (generate phrases word by word), and hence they do not benefit from the advantages of both modeling techniques. To address these challenges, we propose <i>SEG-Net</i>, a neural keyphrase generation model that is composed of two major components, (1) a selector that selects the salient sentences in a document, and (2) an extractor-generator that jointly extracts and generates keyphrases from the selected sentences. SEG-Net uses a self-attentive architecture, known as, <i>Transformer</i> as the building block with a couple of uniqueness. First, SEG-Net incorporates a novel <i>layer-wise</i> coverage attention to summarize most of the points discussed in the target document. Second, it uses an <i>informed</i> copy attention mechanism to encourage focusing on different segments of the document during keyphrase extraction and generation. Besides, SEG-Net jointly learns keyphrase generation and their part-of-speech tag prediction, where the later provides syntactic supervision to the former. The experimental results on seven keyphrase generation benchmarks from scientific and web documents demonstrate that SEG-Net outperforms the state-of-the-art neural generative methods by a large margin in both domains.
</p>

