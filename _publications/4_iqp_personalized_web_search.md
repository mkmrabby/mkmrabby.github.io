---
title: "Intent-aware Query Obfuscation for Privacy Protection in Personalized Web Search"
collection: publications
Authors: '<b>Wasi Uddin Ahmad</b>, Kai-Wei Chang, and Hongning Wang.'
date: 04/2018
venue: 'ACM SIGIR'
paperurl: 'https://dl.acm.org/doi/10.1145/3209978.3209983'
presentationurl: 'https://wasiahmad.github.io/files/publications/2018/iqp_presentation.pdf'
codeurl: 'https://github.com/wasiahmad/intent_aware_privacy_protection_in_pws'
excerpt: ''
---
---
<a href='https://dl.acm.org/doi/pdf/10.1145/3209978.3209983' target="_blank">[Download Paper]</a>

<div style='display: flex; justify-content: center;'><img src='https://wasiahmad.github.io/files/publications/2018/IQP-1.png' 
alt='Image not Loading' style='height:300px;' align='middle'></div><br>

<p align="justify">
Modern web search engines exploit users' search history to personalize search results, with a goal of improving their service 
utility on a per-user basis. But it is this very dimension that leads to the risk of privacy infringement and raises serious 
public concerns. In this work, we propose a client-centered intent-aware query obfuscation solution for protecting user 
privacy in a personalized web search scenario. In our solution, each user query is submitted with l additional cover queries
and corresponding clicks, which act as decoys to mask users' genuine search intent from a search engine. The cover queries 
are sequentially sampled from a set of hierarchically organized language models to ensure the coherency of fake search intents 
in a cover search task. Our approach emphasizes the plausibility of generated cover queries, not only to the current genuine 
query but also to previous queries in the same task, to increase the complexity for a search engine to identify a user's true 
intent. We also develop two new metrics from an information theoretic perspective to evaluate the effectiveness of provided 
privacy protection. Comprehensive experiment comparisons with state-of-the-art query obfuscation techniques are performed on 
the public AOL search log, and the propitious results substantiate the effectiveness of our solution.
</p>
