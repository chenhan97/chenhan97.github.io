---
layout: page
title: Leveraging GANs for Personalized and Efficient Text Generation
description: a project that leverages GANs for Personalized and Efficient Text Generation
importance: 1
category: work
related_publications: yuan2020personalized, yuan2019efficient
---

This project aims to develop a personalized text generation system using generative adversarial networks (GANs). The system will allow users to generate coherent paragraphs on a specified topic and with a desired sentiment.

The generator model will be based on multiple LSTM layers to capture syntactic structure and paragraph-level coherence. To enable personalized text generation, the model will incorporate author-specific features such as function words and named entities. The discriminator will ensure the generated text matches the desired attributes in two stages: first evaluating overall coherence and structure, then evaluating similarity to the target topic and sentiment.

The key novelty of our approach is the ability to efficiently re-generate text for new topics and sentiments specified by the user, without full re-training. Only the higher-level discriminator will be re-trained, significantly reducing computation time.

We evaluate the system by comparing the quality and relevance of generated text against other GAN models. Both automated metrics like BLEU and SimHash as well as human evaluations are used. Overall, this project demonstrate how GANs can be extended to conditional and personalized text generation with minimal re-training costs.

