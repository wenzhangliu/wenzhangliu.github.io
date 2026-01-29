@article{liu2016overcoming,
title = {Overcoming catastrophic forgetting in robotic manipulation via knowledge-compositional reinforcement learning},
journal = {Neurocomputing},
volume = {664},
pages = {131800},
year = {2026},
issn = {0925-2312},
doi = {https://doi.org/10.1016/j.neucom.2025.131800},
url = {https://www.sciencedirect.com/science/article/pii/S0925231225024725},
author = {Wenzhang Liu and Wanyi Yao and Keke Yang and Lu Ren and Changyin Sun},
keywords = {Deep reinforcement learning, Knowledge composition, Robotic manipulation, Sequential multi-task, Catastrophic forgetting},
abstract = {Deep reinforcement learning (DRL) for continuous robotic manipulation faces a critical challenge in catastrophic forgetting, where models gradually lose previously learned skills when acquiring new tasks. While traditional multi-model control methods address this issue, they encounter other limitations, such as gradient conflicts in continuous learning scenarios. In this paper, we propose knowledge-compositional reinforcement learning (KCRL), a framework that trains sequential robotic manipulation tasks continuously via parameter composition. KCRL explicitly separates the parameters into task-agnostic and task-specific components, allowing the agent to extract useful knowledge for learning new tasks. Hence, it mitigates catastrophic forgetting and reduces gradient conflicts common in conventional fully shared networks. Specifically, we formulate robotic manipulation as a temporally dependent sequential decision-making problem, and extend the soft actor-critic (SAC) algorithm following the KCRL framework. Our experimental results show that the method achieves robust and adaptive manipulation in dynamic environments, significantly enhancing learning stability and efficiency across sequential tasks. The results highlight the capability of KCRL to preserve knowledge across sequential manipulation tasks and overcome catastrophic forgetting in continual robotic learning.}
}