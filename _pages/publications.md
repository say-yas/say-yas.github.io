---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016]
nav: true
---

[[Google scholar](https://scholar.google.com/citations?user=hBZ_tKsAAAAJ)] | [[DBLP](https://dblp.org/pid/19/2969-1.html)] | [[View by topic](https://jd92.wang/research/)]

#### Preprints

- On Catastrophic Inheritance of Large Foundation Models. Hao Chen, Bhiksha Raj, Xing Xie, Jindong Wang. [[arxiv](https://arxiv.org/abs/2402.01909)]
- DyVal 2: Dynamic Evaluation of Large Language Models by Meta Probing Agents. Kaijie Zhu, Jindong Wang, Qinlin Zhao, Ruochen Xu, Xing Xie. [[arxiv](https://arxiv.org/abs/2402.14865)]
- CultureLLM: Incorporating Cultural Differences into Large Language Models. Cheng Li, Mengzhou Chen, Jindong Wang, Sunayana Sitaram, Xing Xie. [[arxiv](https://arxiv.org/abs/2402.10946)]
- SpecFormer: Guarding Vision Transformer Robustness via Maximum Singular Value Penalization. Xixu Hu, Runkai Zheng, Jindong Wang, Cheuk Hang Leung, Qi Wu, Xing Xie. [[arxiv](https://arxiv.org/abs/2402.03317)]
- PromptBench: A Unified Library for Evaluation of Large Language Models. Kaijie Zhu, Qinlin Zhao, Hao Chen, Jindong Wang, Xing Xie. [[arxiv](https://arxiv.org/abs/2312.07910)]
- The Good, the Bad, and Why: Unveiling Emotions in Generative AI. Cheng Li, Jindong Wang, Yixuan Zhang, Kaijie Zhu, Xinyi Wang, Wenxin Hou, Jianxun Lian, Fang Luo, Qiang Yang, Xing Xie. [[arxiv](https://arxiv.org/abs/2312.11111)]
- CompeteAI: Understanding the Competition Behaviors in Large Language Model-based Agents. Qinlin Zhao, Jindong Wang, Yixuan Zhang, Yiqiao Jin, Kaijie Zhu, Hao Chen, Xing Xie. [[arxiv](https://arxiv.org/abs/2310.17512)]
- ZooPFL: Exploring Black-box Foundation Models for Personalized Federated Learning. Wang Lu, Hao Yu, Jindong Wang, Damien Teney, Haohan Wang, Yiqiang Chen, Qiang Yang, Xing Xie, Xiangyang Ji. [[arxiv](https://arxiv.org/abs/2310.05143)]
- Meta Semantic Template for Evaluation of Large Language Models. Yachuan Liu, Liang Chen, Jindong Wang, Qiaozhu Mei, Xing Xie. [[arxiv](https://arxiv.org/abs/2310.01448)]
- Frustratingly Easy Model Generalization by Dummy Risk Minimization. Juncheng Wang, Jindong Wang, Xixu Hu, Shujun Wang, Xing Xie. [[arxiv](https://arxiv.org/abs/2308.02287)]
- EmotionPrompt: Leveraging Psychology for Large Language Models Enhancement via Emotional Stimulus. Cheng Li, Jindong Wang, Kaijie Zhu, Yixuan Zhang, Wenxin Hou, Jianxun Lian, Xing Xie. [[arxiv](https://arxiv.org/abs/2307.11760)]
- PromptBench: Towards Evaluating the Robustness of Large Language Models on Adversarial Prompts. Kaijie Zhu, Jindong Wang, Jiaheng Zhou, Zichen Wang, Hao Chen, Yidong Wang, Linyi Yang, Wei Ye, Neil Zhenqiang Gong, Yue Zhang, Xing Xie. [[arxiv](https://arxiv.org/abs/2306.04528)] [[code](https://github.com/microsoft/promptbench)]
- Selective Mixup Helps with Distribution Shifts, But Not (Only) because of Mixup. Damien Teney, Jindong Wang, Ehsan Abbasnejad. [[arxiv](https://arxiv.org/abs/2305.16817)]
- Imprecise Label Learning: A Unified Framework for Learning with Various Imprecise Label Configurations. Hao Chen, Ankit Shah, Jindong Wang, Ran Tao, Yidong Wang, Xing Xie, Masashi Sugiyama, Rita Singh, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2305.12715)]
- An Embarrassingly Simple Baseline for Imbalanced Semi-Supervised Learning. Hao Chen, Yue Fan, Yidong Wang, Jindong Wang, Bernt Schiele, Xing Xie, Marios Savvides, Bhiksha Raj. [[arxiv](https://arxiv.org/abs/2211.11086)] 
- Conv-Adapter: Exploring Parameter Efficient Transfer Learning for ConvNets. Hao Chen, Ran Tao, Han Zhang, Yidong Wang, Wei Ye, Jindong Wang, Guosheng Hu, and Marios Savvides. [[arxiv](https://arxiv.org/abs/2208.07463)]
- Equivariant Disentangled Transformation for Domain Generalization under Combination Shift. Yivan Zhang, Jindong Wang, Xing Xie, and Masashi Sugiyama. [[arxiv](https://arxiv.org/abs/2208.02011)]
- Learning Invariant Representations across Domains and Tasks. Jindong Wang, Wenjie Feng, Chang Liu, Chaohui Yu, Mingxuan Du, Renjun Xu, Tao Qin, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2103.05114)]
- Learning to match distributions for domain adaptation. Chaohui Yu, Jindong Wang, Chang Liu, Tao Qin, Renjun Xu, Wenjie Feng, Yiqiang Chen, and Tie-Yan Liu. [[arxiv](https://arxiv.org/abs/2007.10791)]

#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
