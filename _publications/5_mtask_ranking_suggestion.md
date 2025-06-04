---
title: "Multi-Task Learning for Document Ranking and Query Suggestion"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Kai-Wei Chang, and Hongning Wang.'
date: 01/2018
venue: 'ICLR'
paperurl: 'https://openreview.net/forum?id=SJ1nzBeA-'
presentationurl: 'https://wasiahmad.github.io/files/publications/2018/poster_mtask_ranking_suggestion.pdf'
codeurl: 'https://github.com/wasiahmad/context_attentive_ir'
excerpt: ''
---
---
<a href='https://openreview.net/pdf?id=SJ1nzBeA-' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'>
  <img src='https://wasiahmad.github.io/files/publications/2018/MNSRF-1.png' 
alt='Image not Loading' style='height:350px;' align='middle'>
</div>
<div style='display: flex; justify-content: center;'><p>
  <br><b>Figure:</b>  General workflow of the proposed multi-task neural session relevance framework.<br>
</p></div>

<p align="justify">
We propose a multi-task learning framework to jointly learn document ranking and query suggestion for web search. 
It consists of two major components, a document ranker and a query recommender. Document ranker combines current query and 
session information and compares the combined representation with document representation to rank the documents. Query 
recommender tracks users’ query reformulation sequence considering all previous in-session queries using a sequence to 
sequence approach. As both tasks are driven by the users’ underlying search intent, we perform joint learning of these two 
components through session recurrence, which encodes search context and intent. Extensive comparisons against state-of-the-art 
document ranking and query suggestion algorithms are performed on the public AOL search log, and the promising results 
endorse the effectiveness of the joint learning framework.
</p>
