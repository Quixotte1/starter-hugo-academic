---
abstract: We present the SCR framework for enhancing the training of graph
  neural networks (GNNs) with consistency regularization. Regularization is a
  set of strategies used in Machine Learning to reduce overfitting and improve
  the generalization ability. However, it is unclear how to best design the
  generalization strategies in GNNs, as it works in a semi-supervised setting
  for graph data. The major challenge lies in how to efficiently balance the
  trade-off between the error from the labeled data and that from the unlabeled
  data. SCR is a simple yet general framework in which we introduce two
  strategies of consistency regularization to address the challenge above. One
  is to minimize the disagreements among the perturbed predictions by different
  versions of a GNN model. The other is to leverage the Mean Teacher paradigm to
  estimate a consistency loss between teacher and student models instead of the
  disagreement of the predictions. We conducted experiments on three large-scale
  node classification datasets in the Open Graph Benchmark (OGB). Experimental
  results demonstrate that the proposed SCR framework is a general one that can
  enhance various GNNs to achieve better performance. Finally, SCR has been the
  top-1 entry on all three OGB leaderboards as of this submission.
slides: ""
url_pdf: https://arxiv.org/pdf/2112.04319.pdf
publication_types:
  - "3"
authors:
  - Chenhui Zhang
  - admin
  - Yukuo Cen
  - Zhenyu Hou
  - Wenzheng Feng
  - Yuxiao Dong
  - Xu Cheng
  - Hongyun Cai
  - Feng He
  - Jie Tang
author_notes:
  - Equal contribution
  - Equal contribution
publication: arxiv
summary: We present a semi-supervised consistency regularization framework-SCR
  to improve the performance of graph neural networks.
url_dataset: ""
url_project: ""
publication_short: arxiv
url_source: ""
url_video: ""
title: "SCR: Training Graph Neural Networks with Consistency Regularization"
doi: ""
featured: true
tags: []
projects: []
image:
  caption: ""
  focal_point: ""
  preview_only: falsee
  alt_text: ""
date: 2021-12-01T09:46:20.828Z
url_slides: ""
publishDate: 2021-12-01T00:00:00.000Z
url_poster: ""
url_code: https://github.com/THUDM/SCR
---
