---
layout: page
title: N-ary Document-Level Relation Extraction
description: a project focusing on how to leverage binary intra-sentence relatione extraction to achieve n-ary document-level relation extraction
img: assets/img/ncre.PNG
importance: 1
category: work
related_publications: yuan2021unsupervised, 10020624, yuan2020reinforcement
---

Relation extraction is the problem of extracting relations between entities described in the text. Relations identify a common "fact" described by distinct entities. Conventional relation extraction approaches focus on supervised binary intra-sentence relations, where the assumption is relations only exist between two entities within the same sentence. These approaches have two key limitations. First, binary intra-sentence relation extraction methods can not extract a relation in a fact that is described by more than two entities. Second, these methods cannot extract relations that span more than one sentence, which commonly occurs as the number of entities increases. Third, these methods assume a supervised setting and are therefore not able to extract relations in the absence of sufficient labeled data for training. This work aims to overcome these limitations by developing n-ary cross-sentence relation extraction methods for both supervised and unsupervised settings. Our work has three main goals and contributions: 

(1) two unsupervised binary intra-sentence relation extraction methods
(2) a supervised n-ary cross-sentence relation extraction method 
(3) an unsupervised n-ary cross-sentence relation extraction method. 

To achieve these goals, our work includes the following contributions: 
(1) an automatic labeling method for n-ary cross-sentence data, which is essential for model training
(2) a reinforcement learning-based sentence distribution estimator to minimize the impact of noise on model training
(3) a generative clustering-based technique for intra-sentence unsupervised relation extraction
(4) a variational autoencoder-based technique for unsupervised binary intra-sentence relation extraction.
