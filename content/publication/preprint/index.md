---
abstract: |-
  We propose to learn a data-adaptive convex regularizer, which
  is parameterized using an input-convex neural network, for
  variational image reconstruction. The regularizer parameters
  are learned adversarially by discriminating clean images from
  the artifact-ridden ones in a training dataset. Convexity of
  the regularizer is theoretically and practically important since
  (i) one can establish well-posedness guarantees for the corre-
  sponding variational reconstruction problem and (ii) devise
  provably convergent optimization algorithms for reconstruc-
  tion. In particular, the resulting method is shown to be conver-
  gent in the sense of regularization and can be solved provably
  using a gradient-based solver. To demonstrate the performance
  of our approach for solving inverse problems, we consider de-
  blurring natural images and reconstruction in X-ray computed
  tomography (CT) and show that the proposed convex regular-
  izer is on par with and sometimes superior to state-of-the-art
  classical and data-driven techniques for inverse problems, es-
  pecially with severely ill-posed forward operators (such as in
  limited-angle tomography).
slides: example
url_pdf: https://doi.org/10.48550/arXiv.2008.02839
publication_types:
  - "1"
authors:
  - Subhadip Mukherjee
  - Sören Dittmer
  - admin
  - Sebastian Lunz
  - Ozan Öktem
  - Carola-Bibiane Schönlieb
publication: "2024 IEEE International Conference on Acoustics, Speech & Signal Processing "
publication_short: 2024 IEEE ICASSP
featured: false
summary: We learn the regularizer from data and make sure that it is convex,
  which gives guarrantees on convergence of variational optimisation.
date: 2024-01-01T00:00:00.000Z
url_slides: ""
title: Data-Driven Convex Regularizers for Inverse Problems
tags:
  - Convex optimisation
  - Inverse problems
  - Data-driven regularization
  - Adversarial learning
links:
  - name: My Code
    url: https://github.com/Zakobian/CT_framework_
projects:
  - ML_in_inverseproblems
image:
  caption: ""
  focal_point: Smart
  preview_only: false
  filename: https://media.arxiv-vanity.com/render-output/5892693/figures/acr_diagram_test1.png
publishDate: 2017-01-01T00:00:00.000Z
url_code: https://github.com/Subhadip-1/data_driven_convex_regularization
doi: https://doi.org/10.48550/arXiv.2008.02839
---

#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}

#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
