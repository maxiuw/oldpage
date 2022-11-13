---
layout: page
title: Scientific Papers
subtitle: 
---

## IEEE ITSC 2022
#### *2022 IEEE 25th International Conference on Intelligent Transportation Systems (ITSC)*

**Title**: *Semantic 3D Grid Maps for Autonomous Driving*

**Abstract**: Maps play a key role in rapidly developing area of autonomous driving. We survey the literature for different map representations and find that while the world is three-dimensional, it is common to rely on 2D map representations in order to meet real-time constraints. We believe that high levels of situation awareness require a 3D representation as well as the inclusion of semantic information. We demonstrate that our recently presented hierarchical 3D grid mapping framework UFOMap meets the real-time constraints. Furthermore, we show how it can be used to efficiently support more complex functions such as calculating the occluded parts of space and accumulating the output from a semantic segmentation network.


**Cite**: @inproceedings{khoche2022semantic,
  title={Semantic 3D Grid Maps for Autonomous Driving},
  author={Khoche, Ajinkya and Wozniak, Maciej K and Duberg, Daniel and Jensfelt, Patric},
  booktitle={2022 IEEE 25th International Conference on Intelligent Transportation Systems (ITSC)},
  pages={2681--2688},
  year={2022},
  organization={IEEE}
}

**Article**: [Read online](https://ieeexplore.ieee.org/abstract/document/9922537)


## PeerJ Computer Science 2022
#### *(Journal Paper)*

**Title**: *FCMpy: a python module for constructing and analyzing fuzzy cognitive maps*

**Abstract**: FCMpy is an open-source Python module for building and analyzing Fuzzy Cognitive Maps (FCMs). The module provides tools for end-to-end projects involving FCMs. It is able to derive fuzzy causal weights from qualitative data or simulating the system behavior. Additionally, it includes machine learning algorithms (e.g., Nonlinear Hebbian Learning, Active Hebbian Learning, Genetic Algorithms, and Deterministic Learning) to adjust the FCM causal weight matrix and to solve classification problems. Finally, users can easily implement scenario analysis by simulating hypothetical interventions (i.e., analyzing what-if scenarios). FCMpy is the first open-source module that contains all the functionalities necessary for FCM oriented projects. This work aims to enable researchers from different areas, such as psychology, cognitive science, or engineering, to easily and efficiently develop and test their FCM models without the need for extensive programming knowledge.

**Cite**: @article{mkhitaryan2022fcmpy,
  title={FCMpy: a python module for constructing and analyzing fuzzy cognitive maps},
  author={Mkhitaryan, Samvel and Giabbanelli, Philippe and Wozniak, Maciej K and N{\'a}poles, Gonzalo and De Vries, Nanne and Crutzen, Rik},
  journal={PeerJ Computer Science},
  volume={8},
  pages={e1078},
  year={2022},
  publisher={PeerJ Inc.}
}

**Article**: [Read online](https://peerj.com/articles/cs-1078/)


## IEEE RO-MAN 2022
#### *31st IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)*

**Title**: *Virtual Reality Framework for Better Human-Robot Collaboration and Mutual Understanding*

**Abstract**: Humans interact with robotic systems on a daily basis. User-friendly and efficient interfaces connecting us with these systems are critical for efficient collaboration and a good user experience. In the latest machine learning developments, many robotic platforms have used deep learning models to understand the environment and surroundings better. However, what a robot senses and how it takes decisions are usually hidden from the user. It is believed that soon we will be able to work side-by-side with these machines in a connected, collaborative space. Thus, it is essential to understand the robot and easily reason with it about the state of the environment or how it wants to execute a particular task. This work presents a virtual reality (VR) framework for human-robot collaboration, focused on improving communication and understanding between humans and robots.

**Cite**: @article{wozniakvirtual,
  title={Virtual Reality Framework for Better Human-Robot Collaboration and Mutual Understanding},
  author={Wozniak, Maciej K and Jensfelt, Patric}
}

**Article**: [Read online](https://ml-hri2022.ivai.onl/uploads/papers/ML-HRI_2022_paper_2423.pdf)


## ICCS 2022
#### *2022 INTERNATIONAL CONFERENCE ON COMPUTATIONAL SCIENCE (ICCS)*

**Title**: *Automatic Generation of Individual Fuzzy Cognitive Maps from Longitudinal Data*

**Abstract**: Fuzzy Cognitive Maps (FCMs) are computational models that represent how factors (nodes) change over discrete steps based on causal impacts (weighted directed edges) from other factors. This approach has traditionally been used as an aggregate, similarly to System Dynamics, to depict the functioning of a system. There has been a growing interest in taking this aggregate approach at the individual-level, for example by equipping each agent of an Agent-Based Model with its own FCM to express its behavior. Although frameworks and studies have already taken this approach, an ongoing limitation has been the difficulty of creating as many FCMs as there are individuals. Indeed, current studies have been able to create agents whose traits are different, but whose decision-making modules are often identical, thus limiting the behavioral heterogeneity of the simulated population. In this paper, we address this limitation by using Genetic Algorithms to create one FCM for each agent, thus providing the means to automatically create a virtual population with heterogeneous behaviors. Our algorithm builds on prior work from Stach and colleagues by introducing additional constraints into the process and applying it over longitudinal, individual-level data. A case study from a real-world intervention on nutrition confirms that our approach can generate heterogeneous agents that closely follow the trajectories of their real-world human counterparts. Future works include technical improvements such as lowering the computational time of the approach, or case studies in computational intelligence that use our virtual populations to test new behavior change interventions.


**Cite**: @InProceedings{10.1007/978-3-031-08757-8_27,
author="Wozniak, Maciej K.
and Mkhitaryan, Samvel
and Giabbanelli, Philippe J.",
title="Automatic Generation of Individual Fuzzy Cognitive Maps from Longitudinal Data",
booktitle="Computational Science -- ICCS 2022",
year="2022",
publisher="Springer International Publishing",
address="Cham",
pages="312--325",
isbn="978-3-031-08757-8"
}

**Article**: [Read online](https://link.springer.com/chapter/10.1007/978-3-031-08757-8_27)


## ACM SIGSIM PADS 2021
#### *International Conference on Principles of Advanced Discrete Simulation (PADS)*

**Title**: *Comparing implementations of cellular automata as images: A novel approach to verification by combining image processing and machine learning*

**Abstract**: Discrete models such as cellular automata may be ported from one platform or language onto another to improve performances, for instance by rewriting legacy Matlab code into C++ or adding optimizations into a Python implementation. Although such transformations can offer benefits such as scalability or maintainability, they also have the risk of introducing bugs. While standard verification techniques can always be applied, this situation presents a unique opportunity since the two implementations can be directly compared based on their simulation runs. Although comparing average results across runs of a same configuration is a common practice, our paper shows that many bugs would not be detected at this aggregate level. We thus propose comparing implementations of cellular automata by analyzing their outputs as images. In this paper, we examine the detection of several implementation errors using five different techniques (supervised/unsupervised image processing, decision trees, random forests, or deep learning) across three different cellular automata models (forest fire, tumor, HIV). We show that in some models, random forests can detect 4 out of 5 erroneous runs, although the accuracy depends both on the model and on the nature of the errors.

**Cite**:
@inproceedings{wozniak2021comparing,
  title={Comparing implementations of cellular automata as images: A novel approach to verification by combining image processing and machine learning},
  author={Wozniak, Maciej K and Giabbanelli, Philippe J},
  booktitle={Proceedings of the 2021 ACM SIGSIM Conference on Principles of Advanced Discrete Simulation},
  pages={13--25},
  year={2021}
}

**Article**: [Read online](https://dl.acm.org/doi/abs/10.1145/3437959.3459256)
