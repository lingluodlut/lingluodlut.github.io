---
title: ""
permalink: /BioNLP-Progress/
author_profile: true
---

# BioNLP-progress #
Repository to track the progress in Biomedical Natural Language Processing (BioNLP), including the datasets and the current state-of-the-art for the most common BioNLP tasks.

## English ##
### [1. BioNER](https://github.com/lingluodlut/BioNER-Progress) ###

**Named entity recognition (NER)** is the problem of finding references to entities (mentions) in natural language text, and labeling them with their location and type. In biomedical domain, **biomedical NER (BioNER)** focuses on the biomedical entities like gene, protein, chemical, disease, mutation, etc. 

![image](../images/BioNLP/bioner.png)

- [Papers](https://github.com/lingluodlut/BioNER-Progress/blob/master/BioNER_paper.md)
- [SOTA](https://github.com/lingluodlut/BioNER-Progress/blob/master/BioNER_sota.md)
 



### 2. BioRE(Building) ###

**Relation Extraction (RE)** is the problem of extracting pairs of entities with relations from unstructured text in natural language text. In biomedical domain, the gold of **biomedical RE (BioRE)** is to automatically capture valuable biomedical relations, such as protein-protein interactions (PPIs), drug-drug interactions (DDIs) and chemical-protein interactions (CPIs), from the unstructured biomedical text with high accuracy and efficiency through advanced natural language processing (NLP) and machine learning techniques.Most BioRE methods are pipelined methods that decompose the extraction process into two subtasks and address them incrementally. First, biomedical entity mentions in a given text are recognized using the technologies of NER. Here, we focus the second subtask, classifying each entity pair into the task-specific relations (i.e., relation classification, RC).  

![image](../images/BioNLP/biore.png)



- Papers
- SOTA

## Chinese ##
### [1. 电子病历命名实体识别CNER](https://github.com/lingluodlut/Chinese-BioNLP) ###

中文电子病历命名实体识别（Chinese Clinical Named Entity Recognition, Chinese-CNER）任务目标是从给定的电子病历纯文本文档中识别并抽取出与医学临床相关的实体提及，并将它们归类到预定义的类别。

<div  align="center">    
<img src="../images/BioNLP/CNER.png" width = "400" height = "200" align=center />
</div>

- [Papers](https://github.com/lingluodlut/Chinese-BioNLP/blob/main/CNER_paper.md)
- [SOTA](https://github.com/lingluodlut/Chinese-BioNLP/blob/main/CNER_sota.md)