# Awesome Vision-and-Language Navigation

<!-- Vision-and-Language Navigation (VLN) has becoming an important topic. This repo keeps tracking the recent advancements in VLN. -->
<!-- Create an issue or email to jgu110@ucsc.edu if you have any suggestions on this repo! -->

A curated list of VLN papers. Please check out our VLN survey paper for the catogerization approach and the detailed discussions of tasks, methods, and future directions: [Vision-and-Language Navigation: A Survey of Tasks, Methods, and Future Directions]().

>A long-term goal of AI research is to build intelligent agents that can communicate with humans in natural language, perceive the environment, and perform real-world tasks. Vision-and-Language Navigation (VLN) is a fundamental and interdisciplinary research topic towards this goal, and receives increasing attention from the natural language processing, computer vision, and machine learning communities. In this paper, we review contemporary studies in the emerging field of VLN, covering tasks, evaluation metrics, methods, etc. Through structured analysis of current progress and challenges, we also highlight the limitations of current VLN and opportunities for future work.

## Datasets and Benchmarks

<!-- - Visual Navigation for Mobile Robots: A Survey [paper](https://link.springer.com/article/10.1007/s10846-008-9235-4) -->

### Initial Instruction
- Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments [paper](https://arxiv.org/abs/1711.07280) 

- Stay on the Path: Instruction Fidelity in Vision-and-Language Navigationn [paper](https://doi.org/10.18653/v1/P19-1181)

- Cross-Lingual Vision-Language Navigation [paper](http://arxiv.org/abs/1910.11301)

- Room-Across-Room: Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding [paper](https://arxiv.org/abs/2010.07954)

- Landmark-RxR: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision [paper](https://proceedings.neurips.cc/paper/2021/hash/0602940f23884f782058efac46f64b0f-Abstract.html)

- Beyond the Nav-Graph: Vision-and-Language Navigation in Continuous Environments [paper](https://arxiv.org/abs/2004.02857) 

- Hierarchical Cross-Modal Agent for Robotics Vision-and-Language Navigation [paper](https://arxiv.org/abs/2104.10674)

- Touchdown: Natural Language Navigation and Spatial Reasoning in Visual Street Environments [paper](https://doi.org/10.1109/CVPR.2019.01282)

- The Streetlearn Environment and Dataset [paper](https://arxiv.org/abs/1903.01292)

- Retouchdown: Releasing Touchdown on StreetLearn as a Public Resource for Language Grounding Tasks in Street View [paper](https://doi.org/10.18653/v1/2020.splu-1.7)

- Learning To Follow Directions in Street View [paper](https://arxiv.org/abs/1903.00401)

- Talk2Nav: Long-Range Vision-and-Language Navigation with Dual Attention and Spatial Memory [paper](https://arxiv.org/abs/1910.02029)

- Mapping Instructions to Actions in 3D Environments with Visual Goal Prediction [paper](https://arxiv.org/abs/1809.00786)

- Following High-level Navigation Instructions on a Simulated Quadcopter with Imitation Learning [paper](https://arxiv.org/abs/1806.00047)
 
- Building Generalizable Agents with a Realistic and Rich 3D Environment [paper](https://openreview.net/forum?id=rkaT3zWCZ)

- REVERIE: Remote Embodied Visual Referring Expression in Real Indoor Environments [paper](https://arxiv.org/abs/1904.10151)

- SOON: Scenario Oriented Object Navigation with Graph-based Exploration [paper](https://arxiv.org/abs/2103.17138)

- AI2-THOR: An Interactive 3D Environment for Visual AI [paper](https://arxiv.org/abs/1712.05474)

- ALFRED: A Benchmark for Interpreting Grounded Instructions for Everyday Tasks [paper](https://arxiv.org/abs/1912.01734)

### Guidance

- Just Ask:An Interactive Learning Framework for Vision and Language Navigation [paper](https://arxiv.org/abs/1912.00915)

- Vision-based Navigation with Language-based Assistance via Imitation Learning with Indirect Intervention [paper](https://arxiv.org/abs/1812.04155)

- Help, Anna! Visual Navigation with Natural Multimodal Assistance via Retrospective Curiosity-Encouraging Imitation Learning [paper](https://aclanthology.org/D19-1063/)

- Executing Instructions in Situated Collaborative Interactions [paper](https://aclanthology.org/D19-1218/)

### Dialog 

- The RobotSlang Benchmark: Dialog-guided Robot Localization and Navigation [paper](https://arxiv.org/abs/2010.12639)

- Vision-and-Dialog Navigation [paper](https://arxiv.org/abs/1907.04957)

- Talk the Walk: Navigating New York City through Grounded Dialogue [paper](https://arxiv.org/abs/1807.03367)

- Collaborative Dialogue in Minecraft [paper](https://aclanthology.org/P19-1537/)

- TEACh: Task-driven Embodied Agents that Chat [paper](https://arxiv.org/abs/2110.00534)

## Evaluation 

- Vision-and-Dialog Navigation [paper](https://arxiv.org/abs/1907.04957)

- On Evaluation of Embodied Navigation Agents [paper](https://arxiv.org/abs/1807.06757)

- TOUCHDOWN: Natural Language Navigation and Spatial Reasoning in Visual Street Environments [paper](https://ieeexplore.ieee.org/document/8954308) 

- Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation [paper](https://aclanthology.org/P19-1181/)

- General Evaluation for Instruction Conditioned Navigation using Dynamic Time Warping [paper](https://arxiv.org/abs/1907.05446)


## Methods

### Representation Learning 

#### Pretraining 

- Deep Residual Learning for Image Recognition [paper](https://arxiv.org/abs/1512.03385) 

- An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale [paper](https://arxiv.org/abs/2010.11929) 

- DD-PPO: Learning Near-Perfect PointGoal Navigators from 2.5 Billion Frames [paper](https://arxiv.org/abs/1911.00357)

- Beyond the Nav-Graph: Vision-and-Language Navigation in Continuous Environments [paper](https://arxiv.org/abs/2004.02857)

- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding [paper](https://arxiv.org/abs/1810.04805) 

- Language Models are Unsupervised Multitask Learners [paper](http://www.persagen.com/files/misc/radford2019language.pdf)

- Robust Navigation with Language Pretraining and Stochastic Sampling [paper](https://arxiv.org/abs/1909.02244)

- Episodic Transformer for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2105.06453) 

- ViLBERT: Pretraining Task-Agnostic Visiolinguistic Representations for Vision-and-Language Tasks [paper](https://arxiv.org/abs/1908.02265) 

- The Road to Know-Where: An Object-and-Room Informed Sequential BERT for Indoor Vision-Language Navigation [paper](https://arxiv.org/abs/2104.04167) 

- Improving Vision-and-Language Navigation with Image-Text Pairs from the Web [paper](https://arxiv.org/abs/2004.14973) 

- Towards Learning a Generic Agent for Vision-and-Language Navigation via Pre-training [paper](https://arxiv.org/abs/2002.10638) 

- A Recurrent Vision-and-Language BERT for Navigation [paper](https://arxiv.org/abs/2011.13922) 

- SOAT: A Scene- and Object-Aware Transformer for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2110.14143) 

- Airbert: In-domain Pretraining for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2108.09105) 

#### Semantic Understanding 

- Shifting the Baseline: Single Modality Performance on Visual Navigation & QA [paper](https://aclanthology.org/N19-1197/)

- Are You Looking? Grounding to Multiple Modalities in Vision-and-Language Navigation [paper](https://aclanthology.org/P19-1655/) 

- Diagnosing the Environment Bias in Vision-and-Language Navigation [paper](https://www.ijcai.org/proceedings/2020/124)

- Diagnosing Vision-and-Language Navigation: What Really Matters [paper](https://arxiv.org/abs/2103.16561)

- Object-and-Action Aware Model for Visual Language Navigation [paper](https://arxiv.org/abs/2007.14626)

- Room-and-Object Aware Knowledge Reasoning for Remote Embodied Referring Expression [paper](https://ieeexplore.ieee.org/abstract/document/9577507)

- Embodied Vision-and-Language Navigation with Dynamic Convolutional Filters [paper](https://arxiv.org/abs/1907.02985)

- Language-guided Navigation via Cross-Modal Grounding and Alternate Adversarial Learning [paper](https://arxiv.org/abs/2011.10972)

#### Graph Representation 

- Language and Visual Entity Relationship Graph for Agent Navigation [paper](https://arxiv.org/abs/2010.09304)

- Evolving Graphical Planner: Contextual Global Planning for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2007.05655)

- Chasing Ghosts: Instruction Following as Bayesian State Tracking [paper](https://arxiv.org/abs/1907.02022)

- Topological Planning with Transformers for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2012.05292)

#### Memory-augmented Model 

- A Recurrent Vision-and-Language BERT for Navigation [paper](https://arxiv.org/abs/2011.13922) 

- Vision-Dialog Navigation by Exploring Cross-modal Memory [paper](https://arxiv.org/abs/2003.06745)

- Scene-Intuitive Agent for Remote Embodied Visual Grounding [paper](https://arxiv.org/abs/2103.12944)

- Help, Anna! Visual Navigation with Natural Multimodal Assistance via Retrospective Curiosity-Encouraging Imitation Learning [paper](https://aclanthology.org/D19-1063/)

- History Aware Multimodal Transformer for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2110.13309) 

#### Auxiliary Tasks 

- Vision-Language Navigation with Self-Supervised Auxiliary Reasoning Tasks [paper](https://arxiv.org/abs/1911.07883)

- Self-Monitoring Navigation Agent via Auxiliary Progress Estimation [paper](https://arxiv.org/abs/1901.03035)

- Transferable Representation Learning in Vision-and-Language Navigation [paper](https://arxiv.org/abs/1908.03409) 

### Action Strategy Learning 

#### Reinforcement Learning 

- Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation [paper](https://arxiv.org/abs/1811.10092) 

- Landmark-RxR: Solving Vision-and-Language Navigation with Fine-Grained Alignment Supervision [paper](https://proceedings.neurips.cc/paper/2021/hash/0602940f23884f782058efac46f64b0f-Abstract.html)
- Stay on the Path: Instruction Fidelity in Vision-and-Language Navigation [paper](https://aclanthology.org/P19-1181/) 

- General Evaluation for Instruction Conditioned Navigation using Dynamic Time Warping [paper](https://arxiv.org/abs/1907.05446) 

- Multimodal Attention Networks for Low-Level Vision-and-Language Navigation [paper](https://arxiv.org/abs/1911.12377) 

- Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation [paper](https://arxiv.org/abs/1803.07729) 

- Language-guided Navigation via Cross-Modal Grounding and Alternate Adversarial Learning [paper](https://arxiv.org/abs/2011.10972) 

#### Exploration during Navigation

- Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments [paper](https://arxiv.org/abs/1711.07280) 

- Active Visual Information Gathering for Vision-Language Navigation [paper](https://arxiv.org/abs/2007.08037) 

- Tactical Rewind: Self-Correction via Backtracking in Vision-and-Language Navigation [paper](https://arxiv.org/abs/1903.02547) 

- Pathdreamer: A World Model for Indoor Navigation [paper](https://arxiv.org/abs/2105.08756) 

#### Navigation Planning 

- Waypoint Models for Instruction-guided Navigation in Continuous Environments [paper](https://arxiv.org/abs/2110.02207) 

- Look Before You Leap: Bridging Model-Free and Model-Based Reinforcement Learning for Planned-Ahead Vision-and-Language Navigation [paper](https://arxiv.org/abs/1803.07729)

- Pathdreamer: A World Model for Indoor Navigation [paper](https://arxiv.org/abs/2105.08756)

- Neighbor-view Enhanced Model for Vision and Language Navigation [paper](https://arxiv.org/abs/2107.07201) 

- Chasing Ghosts: Instruction Following as Bayesian State Tracking [paper](https://arxiv.org/abs/1907.02022)

#### Asking for Help 

- Just Ask:An Interactive Learning Framework for Vision and Language Navigation [paper](https://arxiv.org/abs/1912.00915) 

- Self-Motivated Communication Agent for Real-World Vision-Dialog Navigation [paper](https://ieeexplore.ieee.org/document/9711423)

- A Framework for Learning to Request Rich and Contextually Useful Information from Humans [paper](https://arxiv.org/abs/2110.08258) 

- TEACh: Task-driven Embodied Agents that Chat [paper](https://arxiv.org/abs/2110.00534)

- RMM: A Recursive Mental Model for Dialog Navigation [paper](https://arxiv.org/abs/2005.00728)

- Vision-and-Dialog Navigation [paper](https://arxiv.org/abs/1907.04957) 

### Data-centric Learning 

#### Data Augmentation 

- Speaker-Follower Models for Vision-and-Language Navigation [paper](https://arxiv.org/abs/1806.02724) 

- On the Evaluation of Vision-and-Language Navigation Instructions [paper](https://arxiv.org/abs/2101.10504) 

- Transferable Representation Learning in Vision-and-Language Navigation [paper](https://arxiv.org/abs/1908.03409)

- Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling [paper](https://arxiv.org/abs/1911.07308) 

- Learning to Navigate Unseen Environments: Back Translation with Environmental Dropout [paper](https://aclanthology.org/N19-1268/) 

- Vision-Language Navigation with Random Environmental Mixup [paper](https://arxiv.org/abs/2106.07876) 

- Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling [paper](https://arxiv.org/abs/1911.07308) 

#### Curriculum Learning

- Curriculum Learning [paper](https://ronan.collobert.com/pub/matos/2009_curriculum_icml.pdf) 

- BabyWalk: Going Farther in Vision-and-Language Navigation by Taking Baby Steps [paper](https://arxiv.org/abs/2005.04625) 

- Curriculum Learning for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2111.07228) 


#### Multitask Learning 

- Environment-agnostic Multitask Learning for Natural Language Grounded Navigation [paper](https://arxiv.org/abs/2003.00443)

- Vision-and-Dialog Navigation [paper](https://arxiv.org/abs/1907.04957) 

- Embodied Multimodal Multitask Learning [paper](https://arxiv.org/abs/1902.01385) 

- Embodied Question Answering in Photorealistic Environments with Point Cloud Perception [paper](https://arxiv.org/abs/1904.03461) 

#### Instruction Interpretation

- Multi-View Learning for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2003.00857) 

- Sub-Instruction Aware Vision-and-Language Navigation [paper](https://aclanthology.org/2020.emnlp-main.271/) 

### Prior Exploration  

- Are You Looking? Grounding to Multiple Modalities in Vision-and-Language Navigation [paper](https://aclanthology.org/P19-1655/) 

- Counterfactual Vision-and-Language Navigation: Unravelling the Unseen [paper](https://proceedings.neurips.cc/paper/2020/hash/39016cfe079db1bfb359ca72fcba3fd8-Abstract.html) 

- Learning to Navigate Unseen Environments: Back Translation with Environmental Dropout [paper](https://aclanthology.org/N19-1268/) 

- Reinforced Cross-Modal Matching and Self-Supervised Imitation Learning for Vision-Language Navigation [paper](https://arxiv.org/abs/1811.10092) 

- Counterfactual Vision-and-Language Navigation via Adversarial Path Sampling [paper](https://arxiv.org/abs/1911.07308) 

- Topological Planning with Transformers for Vision-and-Language Navigation [paper](https://arxiv.org/abs/2012.05292) 

- Rethinking the Spatial Route Prior in Vision-and-Language Navigation [paper](https://arxiv.org/abs/2110.05728) 

### Bibtex:
```
@InProceedings{jing2022vln,
      title={Vision-and-Language Navigation: A Survey of Tasks, Methods, and Future Directions}, 
      author={Jing Gu, Eliana Stefani, Qi Wu, Jesse Thomason, Xin Eric Wang},
      booktitle = {Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)},
      year = {2022}
}
```