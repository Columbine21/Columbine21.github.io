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

Hi there, I am Ziqi Yuan (袁子麒 in Chinese), a Ph.D. student at the the THUNLP group with State Key Laboratory of Intelligent Technology and Systems, Department of Computer Science and Technology (DCST), Tsinghua University, Beijing, China. My supervisor is [Prof. Zhiyuan Liu](https://nlp.csai.tsinghua.edu.cn/~lzy/). My research mainly focused on Robustness of Multimodal Models (including MLLMs), and its Interpretability. I have published several papers at the top international AI journals and conferences, such as T-MM, T-ASLP, ACM MM, AAAI, and ACL. <a href='https://scholar.google.com/citations?user=m7b3r2kAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fcolumbine21%2Fcolumbine21.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

https://cdn.jsdelivr.net/gh/sunlicai/sunlicai.github.io@google-scholar-stats/gs_data_shieldsio.json

Feel free to reach out if you’re interested in my work and want to explore potential collaborations: x@y, where x = yzq21 and y = mails.tsinghua.edu.cn.

# 📖 Experiences
- *2021.09 - 2026.06 (Expected)*, Ph.D. student, Department of Computer Science and Technology, Tsinghua University, China.
- *2020.06 - 2020.09*, [快手-社区科学部-算法工程师](https://www.kuaishou.com/about), advised by Bin Han, China.
- *2019.07 - 2019.08*, Summer School at University of California, Berkeley, China.
- *2017.09 - 2021.06*, B.S., Department of Computer Science and Technology, Beijing University of Posts and Telecommunications (BUPT), China.



# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Got one first-author full paper accepted by IEEE/ACM TASLP.
- *2024.06*: &nbsp;🎉🎉 Got one first-author full paper accepted by ACL 2024 (Demo Track).
- *2024.05*: &nbsp;🎉🎉 Got one co-first author full paper accepted by IEEE Trans. on Multimedia.
- *2024.02*: &nbsp;🎉🎉 Got one first-author full paper accepted by IEEE Trans. on Multimedia.
- *2023.10*: &nbsp;🎉🎉 Successfully passed the thesis proposal report and obtained an A- (4.0/4.0)
- *2023.04*: &nbsp;🎉🎉 Got one first-author full paper accepted by IEEE Trans. on Multimedia.

# 📝 Publications 

Research Interests: Trustworthy Multimodal Machine Learning and Explainable AI (XAI) in Future.
- Robustness under Modality Noise: Reconstruction based [1], Adversarial Training [2], Meta Learning [3] Approaches.
- Modality Dominant Challenge: Generated Unimodal Labels [11] and Weights [6], SIMS v2 dataset and Mixup [8].
- Visualization and Demos of Noise Impact: M-SENA Platform [9], Robust-MSA Toolkit [7] and its extension [4].
- Others: Multimodal Conversations [10], Semi-supervised Methods [5].


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACMMM 2021</div><img src='images/mm21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ [1] Transformer-based feature reconstruction network for robust multimodal sentiment analysis](https://dl.acm.org/doi/abs/10.1145/3474085.3475585)

**Ziqi Yuan*** , Wei Li*, Hua Xu, Wenmeng Yu

[**Project**](https://github.com/thuiar/TFR-Net) <strong><span class='show_paper_citations' data='m7b3r2kAAAAJ:qjMakFHDy7sC'></span></strong>
- This work introduces a transformer-based feature reconstruction network (TFR-Net) to improve the robustness of models for the random missing in non-aligned modality sequences. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2023</div><img src='images/tmm-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ [2] Noise imitation based adversarial training for robust multimodal sentiment analysis](https://ieeexplore.ieee.org/abstract/document/10103636)

**Ziqi Yuan*** , YiHe Liu*, Hua Xu, Kai Gao

[**Project**](https://github.com/thuiar/NIAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this work, we formulate the imperfection with the modality feature missing at the training period and propose the noise intimation based adversarial training framework to improve the robustness against various potential imperfections at the inference period.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">T-MM 2024</div><img src='images/tmm-2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ [3] Meta Noise Adaption Framework for Multimodal Sentiment Analysis with Feature Noise](https://dl.acm.org/doi/abs/10.1145/3474085.3475585)

**Ziqi Yuan*** , Baozheng Zhang*, Hua Xu, Kai Gao

[**Project**](https://github.com/thuiar/NIAT) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents one of the earliest efforts utilizing the meta learning perspective which treats each specific noise pattern as an individual task within the broader noisy Multimodal Sentiment Analysis task family. 
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/acl24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ [4] OpenVNA: A Framework for Analyzing the Behavior of Multimodal Language Understanding System under Noisy Scenarios](https://arxiv.org/pdf/2407.02773)

**Ziqi Yuan**, Baozheng Zhang, Zhiyun Liang, Hua Xu, Kai Gao

[**Project**](https://github.com/thuiar/OpenVNA) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents OpenVNA, an open-source framework designed for analyzing the behavior of multimodal language understanding systems under noisy conditions. Demo video can be found on [Youtube](https://www.youtube.com/watch?v=0Z9cW7RGct4).
</div>
</div>

- [ [5] Multimodal Consistency-based Teacher for Semi-supervised Multimodal Sentiment Analysis](https://ieeexplore.ieee.org/abstract/document/10603417), **Ziqi Yuan**, Jingliang Fang, Hua Xu, Kai Gao, **IEEE/ACM Transactions on Audio, Speech, and Language Processing**

- [ [6] Crossmodal Translation Based Meta Weight Adaption for Robust Image-Text Sentiment Analysis](https://ieeexplore.ieee.org/abstract/document/10603417), Baozheng Zhang* , **Ziqi Yuan***, Hua Xu, Kai Gao, **IEEE Transactions on Multimedia** \| [![](https://img.shields.io/github/stars/thuiar/CTMWA?style=social&label=Code+Stars)](https://github.com/thuiar/CTMWA)

- [ [7] Robust-MSA: Understanding the impact of modality noise on multimodal sentiment analysis](https://ojs.aaai.org/index.php/AAAI/article/view/27078), Huisheng Mao, Baozheng Zhang, Hua Xu, **Ziqi Yuan**, Yihe Liu, **AAAI 2023** \| [![](https://img.shields.io/github/stars/thuiar/MMSA-FET?style=social&label=Code+Stars)](https://github.com/thuiar/MMSA-FET)

- [ [8] Make acoustic and visual cues matter: Ch-sims v2. 0 dataset and av-mixup consistent module](https://dl.acm.org/doi/abs/10.1145/3536221.3556630), Yihe Liu* , **Ziqi Yuan*** , Huisheng Mao, Zhiyun Liang, Wanqiuyue Yang, Yuanzhe Qiu, Tie Cheng, Xiaoteng Li, Hua Xu, Kai Gao, **ICMI 2022** \| [![](https://img.shields.io/github/stars/thuiar/ch-sims-v2?style=social&label=Code+Stars)](https://github.com/thuiar/ch-sims-v2)

- [ [9] M-SENA: An Integrated Platform for Multimodal Sentiment Analysis](https://aclanthology.org/2022.acl-demo.20/), Huisheng Mao* , **Ziqi Yuan*** , Hua Xu, Wenmeng Yu, Yihe Liu, Kai Gao, **ACL 2022** \| [![](https://img.shields.io/github/stars/thuiar/MMSA?style=social&label=Code+Stars)](https://github.com/thuiar/MMSA)

- [ [10] Gar-net: A graph attention reasoning network for conversation understanding](https://dl.acm.org/doi/abs/10.1145/3536221.3556630), Hua Xu* , **Ziqi Yuan*** ,Kang Zhao, Yunfeng Xu, Jiyun Zou, Kai Gao, **Knowledge-Based Systems**

- [ [11] Learning modality-specific representations with self-supervised multi-task learning for multimodal sentiment analysis](https://github.com/thuiar/Self-MM), Wenmeng Yu, Hua Xu, **Ziqi Yuan**, **AAAI 2021** \| [![](https://img.shields.io/github/stars/thuiar/Self-MM?style=social&label=Code+Stars)](https://github.com/thuiar/Self-MM)

# 🎖 Honors and Awards
- *2023.10* **Overall Excellent Scholarship** (Second Prize), Tsinghua University. (**Top 10%**) 
- *2022.10* **Overall Excellent Scholarship** (First Prize), Tsinghua University. (**Top 5%**)
- *2021.06* **Beijing Outstanding graduates**, from Beijing University of Posts and Telecommunications (BUPT), **rank 2 / 404**.
- *2019.10* **Huawei Scholarship**. (Top 2%)
- *2020.04* Meritorious Winner, MCM/ICM 2020.
- *2018.11* First prize, the Chinese Mathematics Competitions for College Students. (Top 5%)
- *2018.10* **National Scholarship for Undergraduate Student** (2018 No.01215). (Top 1%)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
