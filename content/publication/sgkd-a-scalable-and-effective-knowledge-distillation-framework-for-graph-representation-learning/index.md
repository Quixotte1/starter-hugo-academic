---
title: "SGKD: A Scalable and Effective Knowledge Distillation Framework for
  Graph Representation Learning"
publication_types:
  - "1"
authors:
  - admin
  - Yao Ma
publication: ICDM Workshops
publication_short: ICDM Workshops
abstract: As Graph Neural Networks (GNNs) are widely used in various fields,
  there is a growing demand for improving their efficiency and scalablity.
  Knowledge Distillation (KD), a classical methods for model compression and
  acceleration, has been gradually introduced into the field of graph learning.
  More recently, it has been shown that, through knowledge distillation, the
  predictive capability of a well-trained GNN model can be transferred to
  lightweight and easy-to-deploy MLP models. Such distilled MLPs are able to
  achieve comparable performance as their corresponding GNN teachers while being
  significantly more efficient in terms of both space and time. However, the
  research of KD for graph learning is still in its early stage and there exist
  several limitations in the existing KD framework. The major issues lie in
  distilled MLPs lack useful information about the graph structure and logits of
  teacher are not always reliable. In this paper, we propose a Scalable and
  effective Graph neural network Knowledge Distillation framework (SGKD) to
  address these issues. Specifically, to include the graph, we use feature
  propagation as preprocessing to provide MLPs with graph structure-aware
  features in the original feature space; to address unreliable logits of
  teacher, we introduce simple yet effective training strategies such as masking
  and temperature. With these innovations, our framework is able to be more
  effective while remaining scalable and efficient in training and inference. We
  conducted comprehensive experiments on eight datasets of different sizes - up
  to 100 million nodes - under various settings. The results demonstrated that
  SGKD is able to significantly outperform existing KD methods and even achieve
  comparable performance with their state-of-the-art GNN teachers
draft: false
featured: true
image:
  caption: ""
  focal_point: SMART
  preview_only: false
  alt_text: ""
summary: We propose SGKD-a new and more effective knowledge distillation
  framework for scalable graph representation learning.
date: 2022-10-10T03:27:17.667Z
---
