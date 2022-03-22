# Awesome Vision-and-Language Navigation

<!-- Vision-and-Language Navigation (VLN) has becoming an important topic. This repo keeps tracking the recent advancements in VLN. -->
<!-- Create an issue or email to jgu110@ucsc.edu if you have any suggestions on this repo! -->

A curated list of VLN papers. Please check out our ACL 2022 VLN survey paper for the catogerization approach and the detailed discussions of tasks, methods, and future directions: [Vision-and-Language Navigation: A Survey of Tasks, Methods, and Future Directions]().

>A long-term goal of AI research is to build intelligent agents that can communicate with humans in natural language, perceive the environment, and perform real-world tasks. Vision-and-Language Navigation (VLN) is a fundamental and interdisciplinary research topic towards this goal, and receives increasing attention from the natural language processing, computer vision, and machine learning communities. In this paper, we review contemporary studies in the emerging field of VLN, covering tasks, evaluation metrics, methods, etc. Through structured analysis of current progress and challenges, we also highlight the limitations of current VLN and opportunities for future work.

## Datasets and Benchmarks

<!-- - Visual Navigation for Mobile Robots: A Survey [paper](https://link.springer.com/article/10.1007/s10846-008-9235-4) -->

### Initial Instruction
- [R2R]: Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments  
  CVPR 2018 [paper](https://arxiv.org/abs/1711.07280) 

- [Room-for-Room] Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation  
ACL 2019 [paper](https://doi.org/10.18653/v1/P19-1181)

- [Room-Across-Room]: Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding 
EMNLP 2020 [paper](https://arxiv.org/abs/2010.07954)

- [XL-R2R] Cross-Lingual Vision-Language Navigation  
EMNLP 2020 [paper](http://arxiv.org/abs/1910.11301)  

- [Landmark-RxR]: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision  
NeurIPS 2021  [paper](https://proceedings.neurips.cc/paper/2021/hash/0602940f23884f782058efac46f64b0f-Abstract.html)

- [VLNCE] Beyond the Nav-Graph: Vision-and-Language Navigation in Continuous Environments   
[ECCV 2020] [paper](https://arxiv.org/abs/2004.02857)

- Hierarchical Cross-Modal Agent for Robotics Vision-and-Language Navigation  
arXiv 2021 [paper](https://arxiv.org/abs/2104.10674)

- [Touchdown]: Natural Language Navigation and Spatial Reasoning in Visual Street Environments  
CVPR 2019 [paper](https://doi.org/10.1109/CVPR.2019.01282)

- The Streetlearn Environment and Dataset  
arXiv 2019 [paper](https://arxiv.org/abs/1903.01292)

- [Retouchdown]: Releasing Touchdown on StreetLearn as a Public Resource for Language Grounding Tasks in Street View  
Spatial Language Understanding Workshop 2020 [paper](https://doi.org/10.18653/v1/2020.splu-1.7)

- Learning To Follow Directions in Street View  
arXiv 2019 [paper](https://arxiv.org/abs/1903.00401)

- [Talk2Nav]: Long-Range Vision-and-Language Navigation with Dual Attention and Spatial Memory  
IJCV 2021 [paper](https://arxiv.org/abs/1910.02029)

- [LANI]: Mapping Instructions to Actions in 3D Environments with Visual Goal Prediction
EMNLP 2018 [paper](https://arxiv.org/abs/1809.00786)

- Following High-level Navigation Instructions on a Simulated Quadcopter with Imitation Learning  
 RSS 2018 [paper](https://arxiv.org/abs/1806.00047)

- Building Generalizable Agents with a Realistic and Rich 3D Environment  
arXiv 2018 [paper](https://openreview.net/forum?id=rkaT3zWCZ)

- [REVERIE]: Remote Embodied Visual Referring Expression in Real Indoor Environments  
CVPR 2020 [paper](https://arxiv.org/abs/1904.10151)

- [SOON]: Scenario Oriented Object Navigation with Graph-based Exploration  
CVPR 2021 [paper](https://arxiv.org/abs/2103.17138)

- [ALFRED]: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks  
CVPR 2020 [paper](https://arxiv.org/abs/1912.01734)

### Guidance

- [Just Ask]:An Interactive Learning Framework for Vision and Language Navigation  
AAAI 2020 [paper](https://arxiv.org/abs/1912.00915)

- Vision-based Navigation with Language-based Assistance via Imitation Learning with Indirect Intervention  
CVPR 2019 [paper](https://arxiv.org/abs/1812.04155)

- Help, Anna! Visual Navigation with Natural Multimodal Assistance via Retrospective Curiosity-Encouraging Imitation Learning  
EMNLP 2019 [paper](https://aclanthology.org/D19-1063/)

- Executing Instructions in Situated Collaborative Interactions  
ACL 2019 [paper](https://aclanthology.org/D19-1218/)

### Dialog 

- The RobotSlang Benchmark: Dialog-guided Robot Localization and Navigation  
CoRL 2020 [paper](https://arxiv.org/abs/2010.12639)

- [CVDN]: Vision-and-Dialog Navigation  
CoRL 2019 [paper](https://arxiv.org/abs/1907.04957)

- [Talk the Walk]: Navigating New York City through Grounded Dialogue  
arXiv 2018 [paper](https://arxiv.org/abs/1807.03367)

- Collaborative Dialogue in Minecraft 
ACL 2019 [paper](https://aclanthology.org/P19-1537/)

- [TEACh]: Task-driven Embodied Agents that Chat  
arXiv 2021 [paper](https://arxiv.org/abs/2110.00534)


## Evaluation 

There we introduce papers that includes new evaluation metrics.

- Vision-and-Dialog Navigation  
CoRL 2019 [paper](https://arxiv.org/abs/1907.04957)

- On Evaluation of Embodied Navigation Agents  
arXiv 2018 [paper](https://arxiv.org/abs/1807.06757)

- Touchdown: Natural Language Navigation and Spatial Reasoning in Visual Street Environments  
CVPR 2019 [paper](https://doi.org/10.1109/CVPR.2019.01282)

- Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation  
ACL 2019 [paper](https://doi.org/10.18653/v1/P19-1181)

- General Evaluation for Instruction Conditioned Navigation using Dynamic Time Warping  
arXiv 2019 [paper](https://arxiv.org/abs/1907.05446)


## Methods

### Representation Learning 

#### Pretraining 

- Beyond the Nav-Graph: Vision-and-Language Navigation in Continuous Environments  
[ECCV 2020] [paper](https://arxiv.org/abs/2004.02857)

- Robust Navigation with Language Pretraining and Stochastic Sampling  
EMNLP 2019 [paper](https://arxiv.org/abs/1909.02244)

- Episodic Transformer for Vision-and-Language Navigation  
ICCV 2021 [paper](https://arxiv.org/abs/2105.06453) 

- The Road to Know-Where: An Object-and-Room Informed Sequential BERT for Indoor Vision-Language Navigation  
ICCV 2021 [paper](https://arxiv.org/abs/2104.04167) 

- Improving Vision-and-Language Navigation with Image-Text Pairs from the Web  
ECCV 2020 [paper](https://arxiv.org/abs/2004.14973) 

- Towards Learning a Generic Agent for Vision-and-Language Navigation via Pre-training  
CVPR 2020 [paper](https://arxiv.org/abs/2002.10638)

- A Recurrent Vision-and-Language BERT for Navigation  
CVPR 2021 [paper](https://arxiv.org/abs/2011.13922)  

- SOAT: A Scene- and Object-Aware Transformer for Vision-and-Language Navigation  
 CVPR 2021 [paper](https://arxiv.org/abs/2110.14143)  

- Airbert: In-domain Pretraining for Vision-and-Language Navigation  
ICCV 2021 [paper](https://arxiv.org/abs/2108.09105) 


#### Semantic Understanding 

- Shifting the Baseline: Single Modality Performance on Visual Navigation & QA  
ACL 2019 [paper](https://aclanthology.org/N19-1197/)

- Are You Looking? Grounding to Multiple Modalities in Vision-and-Language Navigation  
ACL 2019 [paper](https://aclanthology.org/P19-1655/) 

- Diagnosing the Environment Bias in Vision-and-Language Navigation  
IJCAI 2020 [paper](https://www.ijcai.org/proceedings/2020/124)

- Diagnosing Vision-and-Language Navigation: What Really Matters  
arXiv 2021 [paper](https://arxiv.org/abs/2103.16561)

- Object-and-Action Aware Model for Visual Language Navigation  
ECCV 2020 [paper](https://arxiv.org/abs/2007.14626)

- Room-and-Object Aware Knowledge Reasoning for Remote Embodied Referring Expression  
CVPR 2021 [paper](https://ieeexplore.ieee.org/abstract/document/9577507)

- Embodied Vision-and-Language Navigation with Dynamic Convolutional Filters  
BMVC 2019 [paper](https://arxiv.org/abs/1907.02985)

- Language-guided Navigation via Cross-Modal Grounding and Alternate Adversarial Learning  
IEEE CAS 2021 [paper](https://arxiv.org/abs/2011.10972)

#### Graph Representation 

- Language and Visual Entity Relationship Graph for Agent Navigation  
NeurIPS 2020 [paper](https://arxiv.org/abs/2010.09304)

- Evolving Graphical Planner: Contextual Global Planning for Vision-and-Language Navigation  
NeurIPS 2020 [paper](https://arxiv.org/abs/2007.05655)

- Chasing Ghosts: Instruction Following as Bayesian State Tracking  
NeurIPS 2019 [paper](https://arxiv.org/abs/1907.02022)

- Topological Planning with Transformers for Vision-and-Language Navigation  
CVPR 2021 [paper](https://arxiv.org/abs/2012.05292)

#### Memory-augmented Model 

- A Recurrent Vision-and-Language BERT for Navigation  
CVPR 2021 [paper](https://arxiv.org/abs/2011.13922) 

- Vision-Dialog Navigation by Exploring Cross-modal Memory 
CVPR 2020 [paper](https://arxiv.org/abs/2003.06745)

- Scene-Intuitive Agent for Remote Embodied Visual Grounding  
CVPR 2021 [paper](https://arxiv.org/abs/2103.12944)

- Help, Anna! Visual Navigation with Natural Multimodal Assistance via Retrospective Curiosity-Encouraging Imitation Learning  
EMNLP 2019 [paper](https://aclanthology.org/D19-1063/)

- History Aware Multimodal Transformer for Vision-and-Language Navigation  
NeurIPS 2021 [paper](https://arxiv.org/abs/2110.13309) 

#### Auxiliary Tasks 

- Vision-Language Navigation with Self-Supervised Auxiliary Reasoning Tasks  
CVPR 2020 [paper](https://arxiv.org/abs/1911.07883)

- Self-Monitoring Navigation Agent via Auxiliary Progress Estimation  
ICLR 2019 [paper](https://arxiv.org/abs/1901.03035)

- Transferable Representation Learning in Vision-and-Language Navigation  
ICCV 2019 [paper](https://arxiv.org/abs/1908.03409) 

### Action Strategy Learning 

#### Reinforcement Learning 

- Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation  
CVPR 2019 [paper](https://arxiv.org/abs/1811.10092) 

- Landmark-RxR: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision  
NeurIPS 2021 [paper](https://proceedings.neurips.cc/paper/2021/hash/0602940f23884f782058efac46f64b0f-Abstract.html)

- Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation  
ACL 2019 [paper](https://aclanthology.org/P19-1181/) 

- General Evaluation for Instruction Conditioned Navigation using Dynamic Time Warping 
arXiv 2019 [paper](https://arxiv.org/abs/1907.05446) 

- Perceive, transform, and act: Multi-modal attention networks for vision-and-language navigation  
arXiv 2019 [paper](https://arxiv.org/abs/1911.12377)

- From language to goals: Inverse reinforcement learning for vision-based instruction following.  
arXiv 2019 [paper](https://arxiv.org/abs/1902.07742) 

- Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation  
ECCV 2018 [paper](https://arxiv.org/abs/1803.07729) 

- Language-guided Navigation via Cross-Modal Grounding and Alternate Adversarial Learning  
IEEE CAS 2021 [paper](https://arxiv.org/abs/2011.10972) 

#### Exploration during Navigation

- Active Visual Information Gathering for Vision-Language Navigation  
ECCV 2020 [paper](https://arxiv.org/abs/2007.08037) 

- Tactical Rewind: Self-Correction via Backtracking in Vision-and-Language Navigation  
CVPR 2019 [paper](https://arxiv.org/abs/1903.02547) 

- Pathdreamer: A World Model for Indoor Navigation  
ICCV 2021 [paper](https://arxiv.org/abs/2105.08756) 

#### Navigation Planning 

- Waypoint Models for Instruction-guided Navigation in Continuous Environments  
ICCV 2021 [paper](https://arxiv.org/abs/2110.02207) 

- Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation  
ECCV 2018 [paper](https://arxiv.org/abs/1803.07729) 

- Pathdreamer: A World Model for Indoor Navigation  
ICCV 2021 [paper](https://arxiv.org/abs/2105.08756) 

- Neighbor-view Enhanced Model for Vision and Language Navigation  
arXiv 2021 [paper](https://arxiv.org/abs/2107.07201) 

- Chasing Ghosts: Instruction Following as Bayesian State Tracking  
NeurIPS 2019 [paper](https://arxiv.org/abs/1907.02022)

#### Asking for Help 

- Just Ask:An Interactive Learning Framework for Vision and Language Navigation  
AAAI 2020 [paper](https://arxiv.org/abs/1912.00915)

- Self-Motivated Communication Agent for Real-World Vision-Dialog Navigation  
ICCV 2021 [paper](https://ieeexplore.ieee.org/document/9711423)

- Learning when and what to ask: a hierarchical reinforcement learning framework   
EMNLP 2019 [paper](https://arxiv.org/abs/2110.08258)

- TEACh: Task-driven Embodied Agents that Chat   
arXiv 2021 [paper](https://arxiv.org/abs/2110.00534)

- RMM: A Recursive Mental Model for Dialog Navigation  
EMNLP Findings 2020 [paper](https://arxiv.org/abs/2005.00728)

- CVDN: Vision-and-Dialog Navigation  
CoRL 2019 [paper](https://arxiv.org/abs/1907.04957)

### Data-centric Learning 

#### Data Augmentation 

- Speaker-Follower Models for Vision-and-Language Navigation  
NeurIPS 2018 [paper](https://arxiv.org/abs/1806.02724) 

- Transferable Representation Learning in Vision-and-Language Navigation  
ICCV 2019 [paper](https://arxiv.org/abs/1908.03409)

- Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling  
CVPR 2020 [paper](https://arxiv.org/abs/1911.07308) 

- Learning to Navigate Unseen Environments: Back Translation with Environmental Dropout  
NAACL 2019 [paper](https://aclanthology.org/N19-1268/) 

- Vision-Language Navigation with Random Environmental Mixup  
ICCV 2021 [paper](https://arxiv.org/abs/2106.07876) 


#### Curriculum Learning

- Curriculum Learning  
ICML 2009 [paper](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf) 

- BabyWalk: Going Farther in Vision-and-Language Navigation by Taking Baby Steps  
ACL 2020 [paper](https://arxiv.org/abs/2005.04625) 

- Curriculum Learning for Vision-and-Language Navigation  
NeurIPS 2021 [paper](https://arxiv.org/abs/2111.07228) 


#### Multitask Learning 

- Environment-agnostic Multitask Learning for Natural Language Grounded Navigation  
ECCV 2020 [paper](https://arxiv.org/abs/2003.00443)

- Embodied Multimodal Multitask Learning  
IJCAI 2020 [paper](https://arxiv.org/abs/1902.01385) 

#### Instruction Interpretation

- Multi-View Learning for Vision-and-Language Navigation  
arXiv 2020 [paper](https://arxiv.org/abs/2003.00857) 

- Look wide and interpret twice: Improving performance on interactive instructionfollowing tasks  
arXiv 2021 [paper](https://arxiv.org/abs/2106.00596) 

- Sub-Instruction Aware Vision-and-Language Navigation  
EMNLP 2020 [paper](https://aclanthology.org/2020.emnlp-main.271/) 

### Prior Exploration  

- Are You Looking? Grounding to Multiple Modalities in Vision-and-Language Navigation  
ACL 2019 [paper](https://aclanthology.org/P19-1655/) 

- Counterfactual Vision-and-Language Navigation: Unravelling the Unseen  
NeurIPS 2020 [paper](https://proceedings.neurips.cc/paper/2020/hash/39016cfe079db1bfb359ca72fcba3fd8-Abstract.html) 

- Learning to Navigate Unseen Environments: Back Translation with Environmental Dropout  
NAACL 2019 [paper](https://aclanthology.org/N19-1268/) 

- Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation  
CVPR 2019 [paper](https://arxiv.org/abs/1811.10092) 

- Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling  
CVPR 2020 [paper](https://arxiv.org/abs/1911.07308) 

- Topological Planning with Transformers for Vision-and-Language Navigation  
CVPR 2021 [paper](https://arxiv.org/abs/2012.05292)

- Rethinking the Spatial Route Prior in Vision-and-Language Navigation   
arXiv 2021 [paper](https://arxiv.org/abs/2110.05728)

### If you find this repo useful for your research, please cite
```
@InProceedings{jing2022vln,
      title={Vision-and-Language Navigation: A Survey of Tasks, Methods, and Future Directions}, 
      author={Jing Gu and Eliana Stefani and Qi Wu and Jesse Thomason and Xin Eric Wang},
      booktitle = {Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (ACL)},
      year = {2022}
}
```
