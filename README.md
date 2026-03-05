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
