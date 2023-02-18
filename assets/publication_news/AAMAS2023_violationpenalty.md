---
layout: publication
title:  Safe Deep Reinforcement Learning by Verifying Task-Level Properties
author: Enrico Marchesini, Luca Marzari, Alessandro Farinelli, Christopher Amato
conference: International Conference on Autonomous Agents and MultiAgent Systems (AAMAS), 2023
---

<img title="Violation Penalty" alt="Difference between indicator cost functions and violation" src="/assets/img/publication_preview/AAMAS2023_violationpenalty.png" class="post-image">

<p class="post-abstract">Cost functions are commonly employed in Safe Deep Reinforcement Learning (DRL). However, the cost is typically encoded as an indicator function due to the difficulty of quantifying the risk of policy decisions in the state space. Such an encoding requires the agent to visit numerous unsafe states to learn a cost-value function to drive the learning process toward safety. Hence, increasing the number of unsafe interactions and decreasing sample efficiency. In this paper, we investigate an alternative approach that uses domain knowledge to quantify the risk in the proximity of such states by defining a \textit{violation} metric. This metric is computed by verifying task-level properties, shaped as input-output conditions, and it is used as a penalty to bias the policy away from unsafe states without learning an additional value function. We investigate the benefits of using the violation metric in standard Safe DRL benchmarks and robotic mapless navigation tasks. The navigation experiments bridge the gap between Safe DRL and robotics, introducing a framework that allows rapid testing on real robots. Our experiments show that policies trained with the violation penalty achieve higher performance over Safe DRL baselines and significantly reduce the number of visited unsafe states.</p>

<h3>Citation</h3>
```bibtex
@inproceedings{AAMAS2023_violationpenalty, 
    title={Safe Deep Reinforcement Learning by Verifying Task-Level Properties}, 
    author={Marchesini, Enrico and Marzari, Luca and Farinelli, Alessandro and Amato, Christopher}, 
    booktitle={Proceedings of the 22nd International Conference on Autonomous Agents and MultiAgent Systems (AAMAS)}, 
    year={2023}, 
}
```