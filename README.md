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

1. [PyTorch Distributed: Experiences on Accelerating Data Parallel Training](https://arxiv.org/abs/2006.15704)
2. [PyTorch FSDP: Experiences on Scaling Fully Sharded Data Parallel Training](https://www.vldb.org/pvldb/vol16/p3848-huang.pdf)
3. [Local SGD Converges Fast and Communicates Little](https://arxiv.org/abs/1805.09767)
4. [Scaling Distributed Machine Learning with the Parameter Server](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-li_mu.pdf)
5. [Large Scale Distributed Deep Networks](https://www.cs.toronto.edu/~ranzato/publications/DistBeliefNIPS2012_withAppendix.pdf)
