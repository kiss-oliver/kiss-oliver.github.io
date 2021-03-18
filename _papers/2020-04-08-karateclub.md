---
title: "Karate Club: An API Oriented Open-Source Python Framework for Unsupervised Learning on Graphs"
collection: publications
permalink: /paper/2020-04-08-karateclub
excerpt: "Karate Club consists of state-of-the-art methods to do unsupervised learning on graph structured data. To put it simply it is a Swiss Army knife for small-scale graph mining research. First, it provides network embedding techniques at the node and graph level. Second, it includes a variety of overlapping and non-overlapping community detection methods. Implemented methods cover a wide range of network science (NetSci, Complenet), data mining (ICDM, CIKM, KDD), artificial intelligence (AAAI, IJCAI) and machine learning (NeurIPS, ICML, ICLR) conferences, workshops, and pieces from prominent journals."
date: 2020-03-10
venue: 'CIKM 2020'
paperurl: 'https://dl.acm.org/doi/10.1145/3340531.3412757'
citation: 'B. Rozemberczki, O. Kiss and R. Sarkar. An API Oriented Open-source Python Framework for Unsupervised Learning on Graphs, Proceedings of the 29th ACM International Conference on Information & Knowledge Management, pp 3125-3132. 2020.'
---

We present Karate Club a Python framework combining more than 30 state-of-the-art graph mining algorithms which can solve unsupervised machine learning tasks. The primary goal of the package is to make community detection, node and whole graph embedding available to a wide audience of machine learning researchers and practitioners. We designed Karate Club with an emphasis on a consistent application interface, scalability, ease of use, sensible out of the box model behaviour, standardized dataset ingestion, and output generation. This paper discusses the design principles behind this framework with practical examples. We show Karate Club’s efficiency with respect to learning performance on a wide range of real world clustering problems, classification tasks and support evidence with regards to its competitive speed.

[Download the pre-print here](https://arxiv.org/abs/2003.04819)

[Download the published paper here](https://dl.acm.org/doi/10.1145/3340531.3412757)

Citing the paper:
```bibtex
>@inproceedings{10.1145/3340531.3412757,
author = {Rozemberczki, Benedek and Kiss, Oliver and Sarkar, Rik},
title = {Karate Club: An API Oriented Open-Source Python Framework for Unsupervised Learning on Graphs},
year = {2020},
isbn = {9781450368599},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3340531.3412757},
doi = {10.1145/3340531.3412757},
abstract = {Graphs encode important structural properties of complex systems. Machine learning on graphs has therefore emerged as an important technique in research and applications. We present Karate Club - a Python framework combining more than 30 state-of-the-art graph mining algorithms. These unsupervised techniques make it easy to identify and represent common graph features. The primary goal of the package is to make community detection, node and whole graph embedding available to a wide audience of machine learning researchers and practitioners. Karate Club is designed with an emphasis on a consistent application interface, scalability, ease of use, sensible out of the box model behaviour, standardized dataset ingestion, and output generation. This paper discusses the design principles behind the framework with practical examples. We show Karate Club's efficiency in learning performance on a wide range of real world clustering problems and classification tasks along with supporting evidence of its competitive speed.},
booktitle = {Proceedings of the 29th ACM International Conference on Information & Knowledge Management},
pages = {3125–3132},
numpages = {8},
keywords = {graph mining, node embedding, community detection, network embedding, graph embedding, graph classification, machine learning},
location = {Virtual Event, Ireland},
series = {CIKM '20}
}
```
