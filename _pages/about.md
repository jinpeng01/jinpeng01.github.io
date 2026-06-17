---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# About Me

I am an Associate Professor at **Hefei University of Technology**. I obtained my Ph.D. from The Chinese University of Hong Kong, Shenzhen, supervised by [Prof. Xiang Wan](https://sds.cuhk.edu.cn/teacher/406) and [Prof. Tsung-Hui Chang](https://myweb.cuhk.edu.cn/changtsunghui/Home). Before that, I received a master's degree in Computer Science and Technology from Harbin Institute of Technology, supervised by [Prof. Yi Guan](http://homepage.hit.edu.cn/guanyi).

My research interests include **Multimodal Affective Computing**, **AI in Mental Health**, **Large Language Models**, **Summarization**, **Named Entity Recognition**, and **Natural Language Processing**.

---

# 🔥 News

- **[2026.05]** 🎉 Four papers accepted to **ACL 2026**!
- **[2026.03]** 🎉 One paper accepted to **WWW 2026** (oral)!
- **[2026.01]** 🎉 One paper accepted to **AAAI 2026**!
- **[2025.09]** 🎉 Three papers accepted to **EMNLP 2025**!
- **[2025.07]** 🎉 One paper accepted to **ACM MM 2025**!
- **[2024]** One paper accepted to **TCSS 2024**!
- **[2023]** Two papers accepted to **ACL 2023**!
- **[2023]** Two papers accepted to **AAAI 2023**!
- **[2022]** Three papers accepted to **NAACL 2022**!
- **[2022]** Two papers accepted to **ACL 2022**!
- **[2021]** One paper accepted to **ACL 2021**!

---

# 🚀 Projects

- **PsycoLLM** — LLM for psychological understanding and evaluation. \[[GitHub](https://github.com/MindIntLab-HFUT/PsycoLLM)\]
- **Psyche-R1** — Chinese psychological reasoning LLM. \[[GitHub](https://github.com/MindIntLab-HFUT/Psyche-R1)\]

---

# 📝 Publications

*\* denotes corresponding author.*

## 2026

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/papers/tears_or_cheers.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Tears or Cheers? Benchmarking LLMs via Culturally Elicited Distinct Affective Responses**

Chongyuan Dai, Yaling Shen, **Jinpeng Hu**, Zihan Gao, Jia Li, Yishun Jiang, Yaxiong Wang, Liu Liu, Zongyuan Ge

*ACL 2026*

\[[PDF](https://arxiv.org/abs/2601.13024)\]

</div>
</div>
-->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/papers/psyche_r1.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Psyche-R1: Towards Reliable Psychological LLMs through Unified Empathy, Expertise, and Reasoning**

Chongyuan Dai, **Jinpeng Hu***, Hongchang Shi, Zhuo Li, Xun Yang, Meng Wang

*ACL 2026*

\[[PDF](https://arxiv.org/abs/2508.10848)\] \[[Code](https://github.com/MindIntLab-HFUT/Psyche-R1)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2026</div><img src='images/papers/psychethics.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**PsychEthicsBench: Evaluating Large Language Models Against Australian Mental Health Ethics**

Yaling Shen, Stephanie Fong, Yiwen Jiang, Zimu Wang, Feilong Tang, Qingyang Xu, Xiangyu Zhao, Zhongxing Xu, Jiahe Liu, **Jinpeng Hu***, Dominic Dwyer, Zongyuan Ge

*Findings of ACL 2026*

\[[PDF](https://arxiv.org/abs/2601.03578)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026 (oral)</div><img src='images/papers/depression_www.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**From Social Media to Psychological Scale: An Adaptive Framework with Two-Hop Retrieval for Depression Screening**

Yangyang Xu, **Jinpeng Hu***, Peipei Song, Zhangling Duan, Xun Yang

*WWW 2026 (oral)*

\[[PDF](https://dl.acm.org/doi/abs/10.1145/3774904.3792594)\] \[[Code](https://github.com/MindIntLab-HFUT/AdaDepression)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/papers/agentmental.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**AgentMental: An Interactive Multi-Agent Framework for Explainable and Adaptive Mental Health Assessment**

**Jinpeng Hu**, Ao Wang, Qianqian Xie, Zhuo Li, Hui Ma, Dan Guo

*AAAI 2026*

\[[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/40365)\] \[[Code](https://github.com/MindIntLab-HFUT/AgentMental)\]

</div>
</div>

## 2025

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2025</div><img src='images/papers/emotion_bench.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Beyond Emotion Recognition: A Multi-Turn Multimodal Emotion Understanding and Reasoning Benchmark**

**Jinpeng Hu**, Hongchang Shi, Chongyuan Dai, Zhuo Li, Peipei Song, Meng Wang

*ACM MM 2025*

\[[PDF](https://dl.acm.org/doi/abs/10.1145/3746027.3755726)\] \[[Code](https://github.com/MindIntLab-HFUT/MTMEUR)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/papers/addonein.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Add-One-In: Incremental Sample Selection for Large Language Models via a Choice-Based Greedy Paradigm**

Zhuo Li, Yuhao Du, Xiaoqi Jiao, Steven Y. Guo, Yuege Feng, Xiang Wan, Anningzhe Gao, **Jinpeng Hu***

*EMNLP 2025*

[[PDF](https://aclanthology.org/2025.emnlp-main.270.pdf)] [[Code](https://github.com/BIRlz/comperative_sample_selection)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/papers/multiagentesc.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**MultiAgentESC: A LLM-based Multi-Agent Collaboration Framework for Emotional Support Conversation**

Yangyang Xu, **Jinpeng Hu***, Zhuoer Zhao, Zhangling Duan, Xiao Sun, Xun Yang

*EMNLP 2025*

[[PDF](https://aclanthology.org/2025.emnlp-main.232.pdf)] [[Code](https://github.com/MindIntLab-HFUT/MultiAgentESC)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2025</div><img src='images/papers/aplot.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**APLOT: Robust Reward Modeling via Adaptive Preference Learning with Optimal Transport**

Zhuo Li, Yuege Feng, Dandan Guo, **Jinpeng Hu**, Anningzhe Gao, Xiang Wan

*EMNLP 2025*

[[PDF](https://aclanthology.org/2025.emnlp-main.281.pdf)] [[Code](https://github.com/BIRlz/APLOT)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2025</div><img src='images/papers/selfprompt.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Self-Instructed Derived Prompt Generation Meets In-Context Learning: Unlocking New Potential of Black-Box LLMs**

Zhuo Li, Yuhao Du, **Jinpeng Hu**, Xiang Wan, Anningzhe Gao

*ACL 2025*

[[PDF](https://aclanthology.org/2025.acl-long.92.pdf)] [[Paper](https://aclanthology.org/2025.acl-long.92/)]

</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSS 2024</div><img src='images/papers/psycollm.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**PsycoLLM: Enhancing LLM for Psychological Understanding and Evaluation**

**Jinpeng Hu**, Tengteng Dong, Gang Luo, Hui Ma, Peng Zou, Xiao Sun, Dan Guo, Xun Yang, Meng Wang

*IEEE Transactions on Computational Social Systems, 2024*

\[[PDF](https://ieeexplore.ieee.org/abstract/document/10772313/)\] \[[Code](https://github.com/MindIntLab-HFUT/PsycoLLM)\]

</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2023</div><img src='images/papers/radiology_acl23.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Improving Radiology Summarization with Radiograph and Anatomy Prompts**

**Jinpeng Hu**, Zhihong Chen, Yang Liu, Xiang Wan, Tsung-Hui Chang

*Findings of ACL 2023*

\[[PDF](https://arxiv.org/pdf/2210.08303.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2023</div><img src='images/papers/gec_acl23.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Improving Grammatical Error Correction with Multimodal Feature Integration**

Tao Fang, **Jinpeng Hu**, Derek F. Wong, Xiang Wan, Lidia S. Chao, Tsung-Hui Chang

*Findings of ACL 2023*

\[[PDF](https://aclanthology.org/2023.findings-acl.594.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/papers/subseq_ner.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**A Simple yet Effective Subsequence-Enhanced Approach for Cross-Domain NER**

**Jinpeng Hu**, DanDan Guo, Yang Liu, Zhuo Li, Zhihong Chen, Xiang Wan, Tsung-Hui Chang

*AAAI 2023*

\[[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/26515)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2023</div><img src='images/papers/easal.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**EASAL: Entity-Aware Subsequence-based Active Learning for Named Entity Recognition**

Yang Liu, **Jinpeng Hu**, Zhihong Chen, Xiang Wan, Tsung-Hui Chang

*AAAI 2023*

\[[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/26069)\]

</div>
</div>

## 2022

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2022</div><img src='images/papers/herogang.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Hero-Gang Neural Model For Named Entity Recognition**

**Jinpeng Hu**, Yaling Shen, Yang Liu, Xiang Wan, Tsung-Hui Chang

*NAACL 2022*

\[[PDF](https://arxiv.org/pdf/2205.07177.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MICCAI 2022</div><img src='images/papers/m3ae.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Multi-modal Masked Autoencoders for Medical Vision-and-Language Pre-training**

Zhihong Chen, Yuhao Du, **Jinpeng Hu**, Yang Liu, Guanbin Li, Xiang Wan, Tsung-Hui Chang

*MICCAI 2022*

\[[PDF](https://arxiv.org/pdf/2209.07098)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of NAACL 2022</div><img src='images/papers/label_aware_ner.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**A Label-Aware Autoregressive Framework for Cross-Domain NER**

**Jinpeng Hu**, He Zhao, Dan Guo, Xiang Wan, Tsung-Hui Chang

*Findings of NAACL 2022*

\[[PDF](https://aclanthology.org/2022.findings-naacl.171.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of NAACL 2022</div><img src='images/papers/proto_rel.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Learn from Relation Information: Towards Prototype Representation Rectification for Few-Shot Relation Extraction**

Yang Liu, **Jinpeng Hu**, Xiang Wan, Tsung-Hui Chang

*Findings of NAACL 2022*

\[[PDF](https://aclanthology.org/2022.findings-naacl.139.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div><img src='images/papers/graph_contrastive_radiology.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Graph Enhanced Contrastive Learning for Radiology Findings Summarization**

**Jinpeng Hu**, Zhuo Li, Zhihong Chen, Zhen Li, Xiang Wan, Tsung-Hui Chang

*ACL 2022*

\[[PDF](https://arxiv.org/pdf/2204.00203.pdf)\]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2022</div><img src='images/papers/rel_extract_acl22.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**A Simple yet Effective Relation Information Guided Approach for Few-Shot Relation Extraction**

Yang Liu, **Jinpeng Hu**, Xiang Wan, Tsung-Hui Chang

*Findings of ACL 2022*

\[[PDF](https://arxiv.org/pdf/2205.09536.pdf)\]

</div>
</div>

## 2021

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Findings of ACL 2021</div><img src='images/papers/word_graph_radiology.png' alt='sym' width='100%'></div></div>
<div class='paper-box-text' markdown="1">

**Word Graph Guided Summarization for Radiology Findings**

**Jinpeng Hu**, Jianling Li, Zhihong Chen, Yaling Shen, Yan Song, Xiang Wan, Tsung-Hui Chang

*Findings of ACL 2021*

\[[PDF](https://arxiv.org/pdf/2112.09925.pdf)\]

</div>
</div>

---

# 🏫 Education

- *2019.09 - 2023.06*, **Ph.D.** in Computer Science, The Chinese University of Hong Kong, Shenzhen (CUHK-Shenzhen)
  - Supervised by [Prof. Xiang Wan](https://sds.cuhk.edu.cn/teacher/406) and [Prof. Tsung-Hui Chang](https://myweb.cuhk.edu.cn/changtsunghui/Home)
- *2016.09 - 2019.06*, **M.Sc.** in Computer Science and Technology, Harbin Institute of Technology (HIT)
  - Supervised by [Prof. Yi Guan](http://homepage.hit.edu.cn/guanyi)

---

# 📣 Services

- Reviewer for ACL, EMNLP, NAACL, AAAI, ACM MM, IEEE TCSS, etc.
- Area Chair: ACL Rolling Review (2025, 2026)

---

# 💼 Positions

- *2023.07 - Now*, **Associate Professor**, School of Computer Science and Information Engineering, Hefei University of Technology (HFUT)

