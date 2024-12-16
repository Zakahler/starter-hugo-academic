---
abstract: "The quest for robust and generalizable machine learning models has
  driven recent interest in exploiting symmetries through equivariant neural
  networks. In the context of PDE solvers, recent works have shown that Lie
  point symmetries can be a useful inductive bias for Physics-Informed Neural
  Networks (PINNs) through data and loss augmentation. Despite this, directly
  enforcing equivariance within the model architecture for these problems
  remains elusive. This is because many PDEs admit non-compact symmetry groups,
  oftentimes not studied beyond their infinitesimal generators, making them
  incompatible with most existing equivariant architectures. In this work, we
  propose Lie aLgebrA Canonicalization (LieLAC), a novel approach that exploits
  only the action of infinitesimal generators of the symmetry group,
  circumventing the need for knowledge of the full group structure. To achieve
  this, we address existing theoretical issues in the canonicalization
  literature, establishing connections with frame averaging in the case of
  continuous non-compact groups. Operating within the framework of
  canonicalization, LieLAC can easily be integrated with unconstrained
  pre-trained models, transforming inputs to a canonical form before feeding
  them into the existing model, effectively aligning the input for model
  inference according to allowed symmetries. LieLAC utilizes standard Lie group
  descent schemes, achieving equivariance in pre-trained models. Finally, we
  showcase LieLAC's efficacy on tasks of invariant image classification and Lie
  point symmetry equivariant neural PDE solvers using pre-trained models. "
draft: false
url_pdf: https://arxiv.org/pdf/2410.02698
publication_types:
  - "3"
authors:
  - admin
  - Peter Zaika
  - James Rowbottom
  - Ferdia Sherry
  - Melanie Weber
  - Carola-Bibiane Schönlieb
author_notes:
  - Equal contribution
  - Equal contribution
featured: false
date: 2024-10-04T12:45:34.051Z
url_slides: ""
title: "Lie Algebra Canonicalization: Equivariant Neural Operators under
  arbitrary Lie Groups"
doi: https://doi.org/10.48550/arXiv.2410.02698
---