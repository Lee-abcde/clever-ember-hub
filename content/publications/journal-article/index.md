---
title: "Contrastive feature decomposition for single image layer separation"
authors:
- Xin Feng
- Jingyuan Li
- Haobo Ji
- Wenjie Pei
- Guangming Lu
- David Zhang
author_notes:
- ""
- ""
- ""
- ""
- ""
- ""
date: "2024-05-01T00:00:00Z"

# Schedule page publish date (can be when you want the page live)
publishDate: "2025-11-04T00:00:00Z"

# Publication type
publication_types: ["article-journal"]

# Journal name
publication: "*Neural Computing and Applications, 36*(14)"
publication_short: "Neural Comput. Appl."

abstract: "The key challenge of image layer separation stems from recognizing different components in a single image. Typical methods optimize the modeling of different components by performing low-level supervision on the separated image to minimize its per-pixel difference from the groundtruth, which relies on substantial training samples to learn diverse components robustly and avoid overfitting spurious coupled patterns. In this work, we perform supervision on the contrastive distribution between the predicted separated images. Specifically, our proposed method separates components in parallel and seeks to maximize the distribution consistency between the separated components’ contrast and their corresponding groundtruth contrast in the latent space. Such supervision pushes the model to focus on contrastive modeling between different components of the input image. Besides, the learned latent representations of different components directly guide the weight optimization of convolution kernels in the decoder, which achieves more comprehensive separation than traditional skip connection while reconstructing target images by the decoder. We validate the effectiveness and generalization of our CFDNet on two single image layer separation tasks, including image reflection separation and intrinsic image decomposition. Extensive experiments demonstrate that our CFDNet consistently outperforms other state-of-the-art methods specifically designed for either of image separation applications."

# Summary
summary: "We propose CFDNet, a contrastive feature decomposition network for single image layer separation, which outperforms existing methods in reflection separation and intrinsic image decomposition."

tags:
- Image Separation
- Contrastive Supervision
- Reflection Separation
- Intrinsic Decomposition
featured: true

hugoblox:
  ids:
    doi: 10.1007/s00521-024-09478-4

links:
  - type: pdf
    url: "https://doi.org/10.1007/s00521-024-09478-4"
  - type: code
    url: ""
  - type: dataset
    url: ""
  - type: poster
    url: ""
  - type: project
    url: ""
  - type: slides
    url: ""
  - type: source
    url: ""
  - type: video
    url: ""

# Featured image
image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---