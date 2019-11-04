# Mihai's Summary of EMNLP 2019

Disclaimer: this is obviously a small subset of the awesome papers/talks at EMNLP and the associated workshops. I selected them subjectively, based solely on my own research interests. The papers are listed chronologically.

The proceedings for EMNLP and all the workshops are available here: https://www.aclweb.org/anthology/events/emnlp-2019/

# Tutorials

### Graph Neural Networks for NLP
**URL**: https://github.com/svjan5/GNNs-for-NLP

**Mihai's comments**: if your data is a graph, you need this.

# Workshop papers

### Syntax-aware Multi-task Graph Convolutional Networks for Biomedical Relation Extraction
**URL**: https://www.aclweb.org/anthology/D19-6204/

**Abstract**: In this paper we tackle two unique challenges in biomedical relation extraction. The first challenge is that the contextual information between two entity mentions often involves sophisticated syntactic structures. We propose a novel graph convolutional networks model that incorporates dependency parsing and contextualized embedding to effectively capture comprehensive contextual information. The second challenge is that most of the benchmark data sets for this task are quite imbalanced because more than 80\% mention pairs are negative instances (i.e., no relations). We propose a multi-task learning framework to jointly model relation identification and classification tasks to propagate supervision signals from each other and apply a focal loss to focus training on ambiguous mention pairs. By applying these two strategies, experiments show that our model achieves state-of-the-art F-score on the 2013 drug-drug interaction extraction task.

**Mihai's comments**: a nice example of graph convolutional NNs (GCN). Also, a good dataset for relation extraction. Relevant to people working on relation/event extraction.

### Layerwise Relevance Visualization in Convolutional Text Graph Classifiers
**URL**: https://www.aclweb.org/anthology/D19-5308/

**Abstract**: Representations in the hidden layers of Deep Neural Networks (DNN) are often hard to interpret since it is difficult to project them into an interpretable domain. Graph Convolutional Networks (GCN) allow this projection, but existing explainability methods do not exploit this fact, i.e. do not focus their explanations on intermediate states. In this work, we present a novel method that traces and visualizes features that contribute to a classification decision in the visible and hidden layers of a GCN. Our method exposes hidden cross-layer dynamics in the input graph structure. We experimentally demonstrate that it yields meaningful layerwise explanations for a GCN sentence classifier.

**Mihai's comments**: Layerwise relevance propagation for GCNs!


### Title
**URL**:
**Abstract**:
**Mihai's comments**: 
