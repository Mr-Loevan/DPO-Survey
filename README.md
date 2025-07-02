# A Comprehensive Survey of Direct Preference Optimization:<br> *Datasets, Theories, Variants, and Applications*

[![arXiv](https://img.shields.io/badge/arXiv-2410.15595-b31b1b.svg)](http://arxiv.org/abs/2410.15595)

## 📢 Updates

- **2024.10**: We released a survey paper "[A Comprehensive Survey of Direct Preference Optimization: Datasets, Theories, Variants, and Applications](http://arxiv.org/abs/2410.15595)". Feel free to cite or open pull requests.

## 👀 Introduction

Welcome to the repository for our survey paper, "A Comprehensive Survey of Direct Preference Optimization: Datasets, Theories, Variants, and Applications". This repository provides resources and updates related to our research. For a detailed introduction, please refer to [our survey paper](http://arxiv.org/abs/2410.15595).

......


![image](./assets/develope.jpg)

This image highlights the components of our survey organization.

![image](./assets/timeline_2.png)
The recent timeline of reasoning LLMs, covering core methods and the release of open-source and closed-source reproduction projects.

## 📒 Table of Contents

- [Research Questions and Variants](#research-questions-and-variants)
  - [RQ0: Why DPO?](#rq0-why-dpo)
  - [RQ1: Effect of Implicit Reward Modeling](#rq1-effect-of-implicit-reward-modeling)
  - [RQ2: Effect of Different Feedback](#rq2-effect-of-different-feedback)
  - [RQ3: Effect of KL Penalty Coefficient and Reference Model](#rq3-effect-of-kl-penalty-coefficient-and-reference-model)
  - [RQ4: Online DPO](#rq4-online-dpo)
  - [RQ5: Reward Hacking](#rq5-reward-hacking)
  - [RQ6: Alignment Tax](#rq6-alignment-tax)
- [Datasets](#datasets)
  - [Human Labeled Datasets](#human-labeled-datasets)
  - [AI Labeled Datasets](#ai-labeled-datasets)
- [Applications](#applications)
  - [Application on Large Language Models](#application-on-large-language-models)
    - [Application on Reasoning](#application-on-reasoning)
    - [Application on Instruction-Following](#application-on-instruction-following)
    - [Application on Anti-Hallucination](#application-on-anti-hallucination)
    - [Application on Code-Generation](#application-on-code-generation)
  - [Application on Multi-modal Understanding and Generation](#application-on-multi-modal-understanding-and-generation)
    - [Multi-modal Understanding](#multi-modal-understanding)
    - [Multi-modal Generation](#multi-modal-generation)
  - [More Applications](#more-applications)

---
### RQ0: Why DPO?

  * Training language models to follow instructions with human feedback [[Paper]](https://arxiv.org/abs/2203.02155) 
  * Direct Preference Optimization: Your Language Model is Secretly a Reward Model [[Paper]](https://arxiv.org/abs/2305.18290) 

### RQ1: Effect of Implicit Reward Modeling

  * On the Limited Generalization Capability of the Implicit Reward Model Induced by Direct Preference Optimization [[Paper]](https://arxiv.org/abs/2409.03650) 
  * Policy Optimization in RLHF: The Impact of Out-of-preference Data [[Paper]](https://arxiv.org/abs/2312.10584) 
  * A General Theoretical Paradigm to Understand Learning from Human Preferences [[Paper]](https://arxiv.org/abs/2310.12036) 
  * Generalizing Reward Modeling for Out-of-Distribution Preference Learning [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-70362-1_7) 
  * Regularizing Hidden States Enables Learning Generalizable Reward Model for LLMs [[Paper]](https://arxiv.org/abs/2406.10216) 
  * 3D-Properties: Identifying Challenges in DPO and Charting a Path Forward [[Paper]](https://openreview.net/forum?id=9Hxdixed7p) 

### RQ2: Effect of Different Feedback

  * RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment [[Paper]](https://arxiv.org/abs/2304.06767) 
  * RRHF: Rank Responses to Align Language Models with Human Feedback without tears [[Paper]](https://arxiv.org/abs/2304.05302) 
  * Advancing LLM Reasoning Generalists with Preference Trees [[Paper]](https://arxiv.org/abs/2404.02078) 
  * Step-DPO: Step-wise Preference Optimization for Long-chain Reasoning of LLMs [[Paper]](https://arxiv.org/abs/2406.18629) 
  * KTO: Model Alignment as Prospect Theoretic Optimization [[Paper]](https://arxiv.org/abs/2402.01306) 
  * Token-level Direct Preference Optimization [[Paper]](https://arxiv.org/abs/2404.11999) 
  * Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models [[Paper]](https://arxiv.org/abs/2401.01335) 
  * Contrastive Preference Optimization: Pushing the Boundaries of LLM Performance in Machine Translation [[Paper]](https://arxiv.org/abs/2401.08417) 
  * Iterative Reasoning Preference Optimization [[Paper]](https://arxiv.org/abs/2404.19733) 
  * Critical Tokens Matter: Token-Level Contrastive Estimation Enhence LLM's Reasoning Capability [[Paper]](https://arxiv.org/abs/2411.19943) 

### RQ3: Effect of KL Penalty Coefficient and Reference Model

  * β-DPO: Direct Preference Optimization with Dynamic β [[Paper]](https://arxiv.org/abs/2407.08639) 
  * Understanding Reference Policies in Direct Preference Optimization [[Paper]](https://arxiv.org/abs/2407.13709) 
  * From r to Q\*: Your Language Model is Secretly a Q-Function [[Paper]](https://arxiv.org/abs/2404.12358) 
  * ORPO: Monolithic Preference Optimization without Reference Model [[Paper]](https://arxiv.org/abs/2403.07691) 
  * SimPO: Simple Preference Optimization with a Reference-Free Reward [[Paper]](https://arxiv.org/abs/2405.14734) 
  * Towards Analyzing and Understanding the Limitations of DPO: A Theoretical Perspective [[Paper]](https://arxiv.org/abs/2404.04626) 
  * Is DPO Superior to PPO for LLM Alignment? A Comprehensive Study [[Paper]](https://arxiv.org/abs/2404.10719) 
  * Learn Your Reference Model for Real Good Alignment [[Paper]](https://openreview.net/forum?id=H0qIWXXLUR) 
  * KL Penalty Control via Perturbation for Direct Preference Optimization [[Paper]](https://arxiv.org/abs/2502.13177) 

### RQ4: Online DPO

  * Self-Rewarding Language Models [[Paper]](https://arxiv.org/abs/2401.10020) 
  * Some things are more CRINGE than others: Iterative Preference Optimization with the Pairwise Cringe Loss [[Paper]](https://arxiv.org/abs/2312.16682) 
  * Direct Language Model Alignment from Online AI Feedback [[Paper]](https://arxiv.org/abs/2402.04792) 
  * sDPO: Don't Use Your Data All at Once [[Paper]](https://arxiv.org/abs/2403.19270) 
  * OPTune: Efficient Online Preference Tuning [[Paper]](https://arxiv.org/abs/2406.07657) 
  * Online DPO: Online Direct Preference Optimization with Fast-Slow Chasing [[Paper]](https://arxiv.org/abs/2406.05534) 
  * Self-Play Fine-Tuning Converts Weak Language Models to Strong Language Models [[Paper]](https://arxiv.org/abs/2401.01335) 
  * Understanding the performance gap between online and offline alignment algorithms [[Paper]](https://arxiv.org/abs/2405.08448) 
  * Offline RLHF Methods Need More Accurate Supervision Signals [[Paper]](https://arxiv.org/abs/2408.09385) 
  * Hybrid Preference Optimization for Alignment: Provably Faster Convergence Rates by Combining Offline Preferences with Online Exploration [[Paper]](https://openreview.net/forum?id=YBBXsVta2x) 

### RQ5: Reward Hacking

  * AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback [[Paper]](https://arxiv.org/abs/2305.14387) 
  * A Long Way to Go: Investigating Length Correlations in RLHF [[Paper]](https://arxiv.org/abs/2310.03716) 
  * Is Stack Overflow Obsolete? An Empirical Study of the Characteristics of ChatGPT Answers to Stack Overflow Questions [[Paper]](https://www.google.com/search?q=https://doi.org/10.1145/3613904.3642596) 
  * How Far Can Camels Go? Exploring the State of Instruction Tuning on Open Resources [[Paper]](https://arxiv.org/abs/2306.04751) 
  * Disentangling Length from Quality in Direct Preference Optimization [[Paper]](https://aclanthology.org/2024.findings-acl.297) 
  * Following Length Constraints in Instructions [[Paper]](https://arxiv.org/abs/2406.17744) 
  * Length Desensitization in Directed Preference Optimization [[Paper]](https://arxiv.org/abs/2409.06411) 
  * Sail into the Headwind: Alignment via Robust Rewards and Dynamic Labels against Reward Hacking [[Paper]](https://openreview.net/forum?id=I8af9JdQTy) 

### RQ6: Alignment Tax

  * Rethinking the Role of Proxy Rewards in Language Model Alignment [[Paper]](https://arxiv.org/abs/2402.03469) 
  * Online merging optimizers for boosting rewards and mitigating tax in alignment [[Paper]](https://arxiv.org/abs/2405.17931) 
  * SPO: Multi-Dimensional Preference Sequential Alignment With Implicit Reward Modeling [[Paper]](https://arxiv.org/abs/2405.12739) 
  * PAFT: A Parallel Training Paradigm for Effective LLM Fine-Tuning [[Paper]](https://arxiv.org/abs/2406.17923) 
  * Mitigating the Alignment Tax of RLHF [[Paper]](https://arxiv.org/abs/2309.06256) 
  * Disperse-Then-Merge: Pushing the Limits of Instruction Tuning via Alignment Tax Reduction [[Paper]](https://arxiv.org/abs/2405.13432) 
  * Controllable Preference Optimization: Toward Controllable Multi-Objective Alignment [[Paper]](https://arxiv.org/abs/2402.19085) 
  * Beyond one-preference-fits-all alignment: Multi-objective direct preference optimization [[Paper]](https://aclanthology.org/2024.findings-acl.889/) 
  * Restoring Calibration for Aligned Large Language Models: A Calibration-Aware Fine-Tuning Approach [[Paper]](https://openreview.net/forum?id=51tMpvPNSm) 
<br>

## Datasets

*(This section corresponds to Section 4 of the paper, providing an overview of key datasets used for DPO training.)*

### Human Labeled Datasets
*(Details on datasets where preference pairs are annotated by humans, e.g., SHP, HelpSteer, OpenAssistant.)*

### AI Labeled Datasets
*(Details on datasets where preference pairs are generated or labeled by AI models like GPT-4, e.g., UltraFeedback, RLAIF-V, Nectar.)*

<br>

## Applications

*(This section corresponds to Section 5 of the paper, showcasing the application of DPO across various domains.)*

### Application on Large Language Models

#### Application on Reasoning
*(How DPO and its variants like Step-DPO are used to improve the mathematical and logical reasoning abilities of LLMs.)*

#### Application on Instruction-Following
*(Methods using DPO to enhance the model's ability to accurately follow complex user instructions.)*

#### Application on Anti-Hallucination
*(Using DPO to reduce the generation of factually incorrect or non-existent information by training models to prefer truthful responses.)*

#### Application on Code-Generation
*(Applying DPO to fine-tune models for generating correct, efficient, and performant code.)*

### Application on Multi-modal Understanding and Generation

#### Multi-modal Understanding
*(Application of DPO to align models for tasks like image/video captioning and audio understanding, often to mitigate hallucination.)*

#### Multi-modal Generation
*(Using DPO to align generative models like diffusion models for text-to-image, text-to-audio, and text-to-motion synthesis based on human preferences.)*

### More Applications
*(Highlighting DPO's use in other specialized fields such as recommender systems, bioinformatics (protein design), and scientific research.)*

---






## Citation
If you find this work useful, welcome to cite us.
```bib
@misc{xiao2024comprehensivesurveydirectpreference,
      title={A Comprehensive Survey of Direct Preference Optimization: Datasets, Theories, Variants, and Applications}, 
      author={Wenyi Xiao and Zechuan Wang and Leilei Gan and Shuai Zhao and Wanggui He and Luu Anh Tuan and Long Chen and Hao Jiang and Zhou Zhao and Fei Wu},
      year={2024},
      eprint={2410.15595},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2410.15595}, 
}
```

<!-- omit in toc -->
## ⭐ Star History

<a href="https://star-history.com/#Mr-Loevan/DPO-Survey&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=Mr-Loevan/DPO-Survey&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=Mr-Loevan/DPO-Survey&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=Mr-Loevan/DPO-Survey&type=Date" />
 </picture>
</a>
