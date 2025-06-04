---
title: "AVATAR: A Parallel Corpus for Java-Python Program Translation"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Md Golam Rahman Tushar, Saikat Chakraborty, and Kai-Wei Chang.'
date: 05/2023
venue: 'Findings of the ACL'
paperurl: 'https://aclanthology.org/2023.findings-acl.143'
codeurl: 'https://github.com/wasiahmad/AVATAR'
excerpt: ''
---
---
<a href='https://aclanthology.org/2023.findings-acl.143' target="_blank">[Download Paper]</a><a href='https://github.com/wasiahmad/AVATAR' target="_blank">[Source Code]</a>

<p align="justify">
  Program translation refers to migrating source code from one programming language to another. It has a tremendous practical value in software development as 
  porting software across different languages is time-consuming and costly. Automating program translation is of paramount importance in software migration, 
  and recently researchers explored unsupervised approaches due to the unavailability of parallel corpora. However, the availability of pre-trained language 
  models for programming languages enable supervised fine-tuning with a small amount of labeled examples. In this work, we present a corpus of 8,475 programming 
  problems and their solutions written in two popular languages, Java and Python. We collect the dataset from competitive programming sites, online platforms, 
  and open source repositories. We present several baselines, including models trained from scratch or pre-trained on large-scale source code collection and 
  fine-tuned on our proposed dataset. Experiment results show that while the models perform relatively well in terms of the lexical match, they lack in 
  generating code that is accurate in terms of syntax and data-flow match.
</p>
