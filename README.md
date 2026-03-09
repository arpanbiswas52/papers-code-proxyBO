[![Paper](https://img.shields.io/badge/paper-arXiv%3AXXXX.YYYYY-B31B1B.svg)](https://arxiv.org/abs/XXXX.YYYYY)


# HUMAN–AI COLLABORATIVE BAYESIAN OPTIMIZATION WITH PROXY MODELING FOR COMPARATIVE OBSERVATION IN AUTONOMOUS EXPERIMENTATION

**Arpan Biswas**, Hiroshi Funakubo, Yongtao Liu

[arXiv:XXXX.YYYYY](https://arxiv.org/abs/XXXX.YYYYY)

### Abstract
Optimization for different tasks like material characterization, synthesis, and functional properties for desired applications over multi-dimensional control parameters need a rapid strategic search through active learning such as Bayesian optimization (BO). However, such high-dimensional experimental physical descriptors are complex and noisy, from which realization of a low-dimensional mathematical scalar metrics or objective functions can be erroneous. Moreover, in traditional purely data-driven autonomous exploration, such objective functions often ignore the subtle variation and key features of the physical descriptors, thereby can fail to discover unknown phenomenon of the material systems. To address this, here we present a proxy-modelled Bayesian optimization (px-BO) via on-the-fly teaming between human and AI agents. Over the loop of BO, instead of defining a mathematical objective function directly from the experimental data, we introduce a voting system on the fly where the new BO samples (high-dimensional experimental descriptors) will be compared with existing samples, and the human agents will choose the preferred samples. These human-guided comparisons are then transformed into a proxy-based objective function via fitting Bradley–Terry (BT) model. Then, to minimize human interaction, this iteratively trained proxy model also acts as an AI agent for future surrogate human votes. Finally, these surrogate votes are periodically validated by human agents, and the corrections are then learned by the proxy model (adjusting function space and AI agent) on-the-fly. We demonstrated the performance of the proposed (px-BO) framework into simulated and BEPS data generated from PTO sample. We find that our approach provided better control of the domain experts for an improved search over traditional data-driven exploration. Over (px-BO) iterations, we see that while proxy-modelled AI agents accelerate exploration via providing highly accurate decisions to compare learned patterns of physical descriptors, human agents help to steer the AI agents in learning any new preferable pattern of physical descriptors. Overall, our method signifies the importance of human-AI teaming in an accelerated and meaningful material space exploration.

### Description
This repository includes links, code, scripts, and data to generate the figures in a paper. All the required installation and import of python packages are provided at the top of each notebooks. If you are using Colab, please !pip install the required packages first.

### Requirements
Information on the dataset is provided in the main paper and notebooks. Link to download the datasets is provided in the notebook.

### Support
This work (A.B) was supported by the University of Tennessee startup funding. The authors acknowledge the use of facilities and instrumentation at the UT Knoxville Institute for Advanced Materials and Manufacturing (IAMM) and the Shull Wollan Center (SWC) supported in part by the National Science Foundation Materials Research Science and Engineering Center program through the UT Knoxville Center for Advanced Materials and Manufacturing (DMR-2309083). This effort (datasets) is supported by the Center for Nanophase Materials Sciences (CNMS), which is a US Department of Energy, Office of Science User Facility at Oak Ridge National Laboratory. This work (H.F) was supported by Japan Science and Technology Agency (JST) as part of Adopting Sustainable Partnerships for Innovative Research Ecosystem (ASPIRE), Grant Number JPMJAP2312. 

