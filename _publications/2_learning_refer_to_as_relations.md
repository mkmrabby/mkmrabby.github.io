---
title: "A Corpus to Learn Refer-to-as Relations for Nominals"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b> and Kai-Wei Chang.'
date: 01/2018
venue: 'LREC'
paperurl: 'https://www.aclweb.org/anthology/L18-1062.pdf'
presentationurl: 'https://wasiahmad.github.io/files/publications/2018/poster_refer_to_as_relations.pdf'
codeurl: 'https://github.com/wasiahmad/mining_wikipedia/tree/master/WikiMiner'
excerpt: ''
---
---
<a href='https://www.aclweb.org/anthology/L18-1062.pdf' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'><img src='https://wasiahmad.github.io/files/publications/2018/LREC-1.png' 
alt='Image not Loading' style='height:350px;' align='middle'></div><br>

<p align="justify">
Continuous representations for words or phrases, trained on large unlabeled corpora are proved very useful for many natural language
processing tasks. While these vector representations capture many fine-grained syntactic and semantic regularities among words
or phrases, it often lacks coreferential information which is useful for many downstream tasks like information extraction, text
summarization etc. In this paper, we argue that good word and phrase embeddings should contain information for identifying refer-to-as
relationship and construct a corpus from Wikipedia to generate coreferential neural embeddings for nominals. The term nominal refers
to a word or a group of words that functions like a noun phrase. In addition, we use coreference resolution as a proxy to evaluate the
learned neural embeddings for noun phrases. To simplify the evaluation procedure, we design a coreferential phrase prediction task
where the learned nominal embeddings are used to predict which candidate nominals can be referred to a target nominal. We further
describe how to construct an evaluation dataset for such task from well known OntoNotes corpus and demonstrate encouraging baseline
results.
</p>
