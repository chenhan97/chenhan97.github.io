---
layout: page
title: Temporal Reasoning in LLM
description: a project focusing on benchmarking and improving large language models' temporal reasoning ability.
img: assets/img/gig.jpg
importance: 4
category: work
related_publications: yuan2023future, yuan-etal-2023-zero
---

Temporal reasoning is an important capability for natural language understanding, but most existing work has focused on extracting direct temporal cues rather than complex temporal inference and prediction. In this project, we aim to advance the state-of-the-art in temporal reasoning for language models through two key thrusts:

1. Explainable temporal event prediction: We introduce a new task and dataset for explainable temporal reasoning, ExpTime, requiring models to forecast future events from a context while also generating explanations for their predictions. As detailed in the paper, current methods cannot provide such explanations to illustrate their reasoning process. We develop instruction-tuned language models capable of multi-step reasoning to predict future timestamps and generate natural language justifications. This advances research on temporal reasoning, future event forecasting, and explainability.

2. Analysis of language models on temporal relation extraction: As discussed in the paper, there has been little study of how well large language models can perform on temporal relation extraction without traditional supervision. We conduct extensive experiments probing the capabilities of models like ChatGPT for zero-shot temporal inference, using various prompt design techniques. We analyze where such models succeed and fail compared to supervised approaches, such as on longer-range temporal reasoning.

Together, these two thrusts provide a comprehensive investigation into state-of-the-art large language model for complex temporal reasoning and inference, advancing research on future prediction, temporal relation extraction, and explainability. The project outcomes will include new models, datasets, analyses, and insights to push forward language understanding for time-sensitive tasks.
