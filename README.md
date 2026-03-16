# Distributed Metric Learning for Approximate Nearest Neighbor Search on Polygon Datasets

## Proposal
- [Term Project Writeup (PDF)](https://github.com/ruban-s-utsa/hpml-term-project/blob/main/HPML%20Term%20Project.pdf)

## Milestones
- Feb 25: Problem statement (proposal)
- Mar 4: Bibliography + algorithms
- Mar 18: Algorithm/Method 1
- Apr 1: Algorithm/Method 2 + merged paper draft
- Apr 27: Algorithm/Method 3 + final implementation paper

## Project Summary
This project learns neural embeddings for polygon shapes (parks, cemeteries, etc.) stored in WKT format,
and compares three distributed training methods (DDP, FSDP/ZeRO-style, and a communication-optimized method).
Evaluation includes scaling, communication/computation breakdown, and retrieval Recall@K using ANN indexing.

## References

- Mai, G., et al. [Towards General-Purpose Representation Learning of Polygonal Geometries](https://arxiv.org/pdf/2209.15458)

- Li, et al. [Latent Representation Learning for Geospatial Entities](https://dl.acm.org/doi/10.1145/3663474)

- [Spatial Representation Learning for Geospatial Data](https://dl.acm.org/doi/10.1145/3681769.3698582)

- [Geoinformatica Journal Paper on Spatial Representation Learning](https://link.springer.com/content/pdf/10.1007/s10707-025-00554-y.pdf)

- [Recent Advances in Geospatial Representation Learning (2025)](https://arxiv.org/pdf/2506.05016)

- Malkov, Y., & Yashunin, D. [Efficient and Robust Approximate Nearest Neighbor Search Using Hierarchical Navigable Small World Graphs](https://arxiv.org/abs/1603.09320)
