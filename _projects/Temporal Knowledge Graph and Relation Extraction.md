---
layout: page
title: Temporal Knowledge Graph and Relation Extraction
description: This project aims to improve the trustworthy of temporal reasoning in both temporal knowledge grpah and NLP models
importance: 1
category: work
related_publications: yuan2023gradxkg, yuan2023temporal
---

Temporal knowledge graphs (TKGs) model how facts evolve over time and enable automated reasoning over temporal data. However, existing TKG reasoning (TKGR) models lack interpretability due to their black-box nature, limiting their applicability. Similarly, temporal relation extraction, a key NLP temporal reasoning task, suffers from severe class imbalance, harming model performance on rare classes.

This project aims to address these limitations by:

1. Developing GradXKG, a novel gradient-based approach to generate post-hoc explanations for TKGR models. GradXKG provides model-agnostic explanations by leveraging gradient information to highlight the most critical nodes at each timestep. This provides crucial insights into a TKGR model's logic.
2. Designing a contrastive prototypical learning framework that distinguishes instances from rare classes by modeling spatial similarity in the embedding space. This is combined with a sampling memory queue for limited batch sizes and a context encoding layer to incorporate linguistic knowledge.

Together, these contributions will significantly enhance the interpretability, performance on rare classes, and overall capabilities of TKGR models. Thorough experiments on standard TKG and temporal relation extraction benchmarks will demonstrate GradXKG's explanatory power and the benefits of addressing class imbalance.

By tackling these key limitations, this project will drive progress in deployable, trustworthy TKGR models that robustly learn from all available training data. The proposed innovations in explainability and class imbalance learning have potential for broad impact beyond TKGs as well.