---
title: "Word and sentence embedding tools to measure semantic similarity of Gene Ontology terms by their definitions"
collection: publications
Authors: 'Dat Duong, <b>Wasi Uddin Ahmad</b>, Eleazar Eskin, Kai-Wei Chang, and Jingyi Jessica Li.'
date: 01/2019
venue: 'Journal of Computational Biology'
paperurl: 'https://www.biorxiv.org/content/biorxiv/early/2018/05/14/103648.full.pdf'
codeurl: 'https://github.com/datduong/NLPMethods2CompareGOterms'
excerpt: ''
---
---
<a href='https://www.biorxiv.org/content/biorxiv/early/2018/05/14/103648.full.pdf' target="_blank">[Download Paper]</a>

<p align="justify">
The gene ontology (GO) database contains GO terms that describe biological functions of genes. Previous methods for comparing 
GO terms have relied on the fact that GO terms are organized into a tree structure. Under this paradigm, the locations of two 
GO terms in the tree dictate their similarity score. In this article, we introduce two new solutions for this problem by 
focusing instead on the definitions of the GO terms. We apply neural network-based techniques from the natural language 
processing (NLP) domain. The first method does not rely on the GO tree, whereas the second indirectly depends on the GO tree. 
In our first approach, we compare two GO definitions by treating them as two unordered sets of words. The word similarity is 
estimated by a word embedding model that maps words into an N-dimensional space. In our second approach, we account for the 
word-ordering within a sentence. We use a sentence encoder to embed GO definitions into vectors and estimate how likely one 
definition entails another. We validate our methods in two ways. In the first experiment, we test the model's ability to 
differentiate a true protein-protein network from a randomly generated network. In the second experiment, we test the model
in identifying orthologs from randomly matched genes in human, mouse, and fly. In both experiments, a hybrid of NLP and GO 
tree-based method achieves the best classification accuracy.
</p>
