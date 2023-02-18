---
layout: publication
title:  Online Safety Property Collection and Refinement for Safe Deep Reinforcement Learning in Mapless Navigation
author: Luca Marzari, Enrico Marchesini, Alessandro Farinelli
conference: International Conference on Robotics and Automation (ICRA), 2023
---

<img title="CROP" alt="General architecture of CROP" src="/assets/img/publication_preview/ICRA2023_crop.png" class="post-image">

<p class="post-abstract">Safety is essential for deploying Deep Reinforcement Learning (DRL) algorithms in real-world scenarios.
Recently, verification approaches have been proposed to allow quantifying the number of violations of a DRL policy over input-output relationships, called properties. However, such properties are hard-coded and require task-level knowledge, making their application intractable in challenging safety-critical tasks. To this end, we introduce the Collection and Refinement of Online Properties (CROP) framework to design properties at training time. CROP employs a cost signal to identify unsafe interactions and use them to shape safety properties. Hence, we propose a refinement strategy to combine properties that model similar unsafe interactions.
Our evaluation compares the benefits of computing the number of violations using standard hard-coded properties and the ones generated with CROP. We evaluate our approach in several robotic mapless navigation tasks and demonstrate that the violation metric computed with CROP allows higher returns and lower violations over previous Safe DRL approaches.</p>

<h3>Citation</h3>
```bibtex
@inproceedings{ICRA2023_crop, 
    title={Online Safety Property Collection and Refinement for Safe Deep Reinforcement Learning in Mapless Navigation}, 
    author={Marzari, Luca and Marchesini, Enrico and Farinelli, Alessandro}, 
    booktitle={2023 International Conference on Robotics and Automation (ICRA)}, 
    year={2023}, 
}
```