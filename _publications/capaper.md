---
title: "Comparing Implementations of Cellular Automata as Images: A Novel Approach to Verification by Combining Image Processing and Machine Learning"
collection: publications
permalink: /publication/capaper
excerpt: 'Discrete models such as cellular automata may be ported from one platform or language onto another to improve performances, for instance by rewriting legacy Matlab code into C++ or adding optimizations into a Python implementation. Although such transformations can offer benefits such as scalability or maintainability, they also have the risk of introducing bugs. While standard verification techniques can always be applied, this situation presents a unique opportunity since the two implementations can be directly compared based on their simulation runs. Although comparing average results across runs of a same configuration is a common practice, our paper shows that many bugs would not be detected at this aggregate level. We thus propose comparing implementations of cellular automata by analyzing their outputs as images. In this paper, we examine the detection of several implementation errors using five different techniques (supervised/unsupervised image processing, decision trees, random forests, or deep learning) across three different cellular automata models (forest fire, tumor, HIV). We show that in some models, random forests can detect 4 out of 5 erroneous runs, although the accuracy depends both on the model and on the nature of the errors.'
date: 2021-06-01
venue: 'SIGSIM-PADS 21'
paperurl: 'https://dl.acm.org/doi/10.1145/3437959.3459256'
---

[Download paper here](https://dl.acm.org/doi/pdf/10.1145/3437959.3459256?casa_token=dPjERe4dE9kAAAAA:Yw0efT8H7IbqmLvli79hQuouHGnHPlBrRj3npm6cPkYt1ORvjBKmXX3-x9LEiNOhdQnGEoFFLOXsnw)

Recommended citation:

@inproceedings{10.1145/3437959.3459256,
author = {Wozniak, Maciej K. and Giabbanelli, Philippe J.},
title = {Comparing Implementations of Cellular Automata as Images: A Novel Approach to Verification by Combining Image Processing and Machine Learning},
year = {2021},
isbn = {9781450382960},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3437959.3459256},
doi = {10.1145/3437959.3459256},
pages = {13–25},
numpages = {13},
keywords = {forest fire, tumor, cellular automata, HIV, image processing, verification},
location = {Virtual Event, USA},
series = {SIGSIM-PADS '21}
}