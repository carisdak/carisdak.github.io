---
layout: project
type: project
image: img/coconet.png
title: CoCoNet
date: 2021
published: true
labels:
  - pytorch
  - clustering
  - metagenomics
  - whole genome sequencing
summary: Metagenomic binning of viral contigs
projecturl: https://github.com/Puumanamana/CoCoNet
---

CoCoNet (Composition and Coverage Network) is a binning method for viral metagenomes. It leverages deep learning to abstract the modeling of the k-mer composition and the coverage for binning contigs assembled form viral metagenomic data. Specifically, our method uses a neural network to learn from the metagenomic data a flexible function for predicting the probability that any pair of contigs originated from the same genome. These probabilities are subsequently combined to infer bins, or clusters representing the species present in the sequenced samples. Our approach was specifically designed for diverse viral metagenomes, such as those found in environmental samples (e.g., oceans, soil, etc.).

Publication: https://academic.oup.com/bioinformatics/article-abstract/37/18/2803/6211156
