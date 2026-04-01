---
permalink: /
title: "BenChen"
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

I'm Ben Chen (陈犇), now working on Generative Recommendation, and AI Search. My research interest includes MultiModal Retreival, GRs, and Deep Search (Multi Agent). If you are seeking any form of academic or work collaboration, please feel free to email **benchen4395@gmail.com**. I have published more than 30 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=aE8P-fwAAAAJ'>google scholar citations <strong><span id='total_cit'>700+</span></strong></a>.

# 📖 Employments
- *2024.06 - Now*, Multimodal Retreival and AI Search, **Kuaishou Technology**. 
- *2020.07 - 2024.06*, International Commerce Business Unit, **Alibaba Group**. 

# 🔥 News
- *2026.03*: &nbsp;🎉🎉 [OneSearch-V2](https://arxiv.org/pdf/2603.24422) is realsed. Codes and data are public on [OneSearch-Family](https://github.com/benchen4395/onesearch-family)
- *2026.01*: &nbsp;🎉🎉 [CRS](https://arxiv.org/pdf/2510.16925) are accepted in WWW 2026 Main, The Context-aware Reasoning Generative E-commerce Search.
- *2026.01*: &nbsp;🎉🎉 [OneVision](https://arxiv.org/pdf/2510.05759) is released, The first end-to-end generative framework for Image Retreival.
- *2025.11*: &nbsp;🎉🎉 [OneSug](https://arxiv.org/pdf/2506.06913) is accepted in AAAI 2026, and reported by [*机器之心*](https://mp.weixin.qq.com/s/PfeXNCLokJ36uHb2lNxMbw).
- *2025.09*: &nbsp;🎉🎉 [*OneSearch*](https://arxiv.org/pdf/2509.03236) is released, and reported by [*机器之心*](https://mp.weixin.qq.com/s/PfeXNCLokJ36uHb2lNxMbw). 

# 📝 Publications 

<div class='paper-box'> <!-- 论文卡片容器 -->
  <div class='paper-box-image'> <!-- 左侧图片区 -->
    <div>
      <div class="badge">Arxiv 2603</div>  <!-- 会议标识 -->
      <img src='images/comparison.png' alt="sym" width="100%"> <!-- 论文配图 -->
    </div>
  </div>
  <div class='paper-box-text' markdown="1"> <!-- 右侧文本区（支持Markdown） -->

[*OneSearch-V2*: The Latent Reasoning Enhanced Self-distillation Generative Search Framework](https://arxiv.org/pdf/2603.24422) \\
**Ben Chen**, Ben Chen, Siyuan Wang, Yufei Ma, Zihan Liang, Xuxin Zhang, et. al.
- A latent reasoning enhanced self-distillation generative search framework. Codes and data are public on [OneSearch-Family](https://github.com/benchen4395/onesearch-family)
- It effectively mitigates common issues such as information bubbles and long-tail sparsity, without incurring additional inference costs or serving latency
</div>
</div>


<div class='paper-box'> <!-- 论文卡片容器 -->
  <div class='paper-box-image'> <!-- 左侧图片区 -->
    <div>
      <div class="badge">Arxiv 2509</div>  <!-- 会议标识 -->
      <img src='images/OneSearch_main.png' alt="sym" width="100%"> <!-- 论文配图 -->
    </div>
  </div>
  <div class='paper-box-text' markdown="1"> <!-- 右侧文本区（支持Markdown） -->

[*OneSearch*: A Preliminary Exploration of the Unified End-to-End Generative Framework for E-commerce Search](https://arxiv.org/pdf/2509.03236) \\
**Ben Chen**, Xian Guo, Siyuan Wang, Zihan Liang, Yue Lv, Yufei Ma, Xinlong Xiao, Bowen Xue, Xuxin Zhang, Ying Yang, Huangyu Dai, et. al.
- The first  industrial-deployed end-2-end generative framework for e-commerce search, with 24.06% gains in MFU and 75.40% reduction in OPEX.
- Various offline and online A/B tests are conducted, verifying its effectiveness and efficiency for the real e-commerce search scenarios.
</div>
</div>

- [OneSug: The Unified End-to-End Generative Framework for E-commerce Query Suggestion](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Xian Guo, **Ben Chen**, Siyuan Wang, Ying Yang, Chenyi Lei, Yuqing Ding, Han Li, **AAAI 2025**
- [CSMCIR: CoT-Enhanced Symmetric Alignment with Memory Bank for Composed Image Retrieval](https://www.arxiv.org/abs/2601.03728), Zhipeng Qian, Zihan Liang, Yufei Ma, **Ben Chen**, Huangyu Dai, Yiwei Ma, et. al. **Arxiv:2601.03728**
- [UniDGF: A Unified Detection-to-Generation Framework for Hierarchical Object Visual Recognition](https://arxiv.org/pdf/2511.15984), Xinyu Nan, Lingtao Mao, Huangyu Dai, Zexin Zheng, Xinyu Sun, Zihan Liang, **Ben Chen**, Yuqing Ding, Chenyi Lei, Wenwu Ou, Han Li, **Arxiv:2511.15984**
- [H-PRM: A Pluggable Hotword Pre-Retrieval Module for Various Speech Recognition Systems](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Huangyu Dai, Lingtao Mao, **Ben Chen**, Zihan Wang, Zihan Liang, Ying Han, Chenyi Lei, Han Li, **CIKM 2025**
- [UniECS: Unified Multimodal E-Commerce Search Framework with Gated Cross-modal Fusion](https://dl.acm.org/doi/pdf/10.1145/3746252.3761170), Zihan Liang, Yufei Ma, ZhiPeng Qian, Huangyu Dai, Zihan Wang, **Ben Chen**, Chenyi Lei, Yuqing Ding, Han Li, **CIKM 2025**
- [InfoGain-RAG: Boosting Retrieval-Augmented Generation through Document Information Gain-based Reranking and Filtering](https://aclanthology.org/2025.emnlp-main.365.pdf), Zihan Wang, Zihan Liang, Zhou Shao, Yufei Ma, Huangyu Dai, **Ben Chen**, Lingtao Mao, Chenyi Lei, Yuqing Ding, Han Li, **EMNLP 2025**
- [Towards Context-aware Reasoning-enhanced Generative Searching in E-commerce](https://arxiv.org/pdf/2510.16925), Zhiding Liu, **Ben Chen**, Mingyue Cheng, Enhong Chen, Li Li, Chenyi Lei, Wenwu Ou, Han Li, Kun Gai, **WWW 2026**
- [COINS: SeMantiC Ids Enhanced COld Item RepresentatioN for Click-through Rate Prediction in E-commerce Search](https://arxiv.org/pdf/2510.12604), Qihang Zhao, Zhongbo Sun, Xiaoyang Zheng, Xian Guo, Siyuan Wang, Zihan Liang, Mingcan Peng, **Ben Chen**, **WWW 2026**
- [OneVision: An End-to-End Generative Framework for Multi-view E-commerce Vision Search](https://arxiv.org/pdf/2510.05759), Zexin Zheng, Huangyu Dai, Lingtao Mao, Xinyu Sun, Zihan Liang, **Ben Chen**, Yuqing Ding, Chenyi Lei, Wenwu Ou, Han Li, Kun Gai, **Arxiv:2510.05759**
- [Adaptive User Interest Modeling via Conditioned Denoising Diffusion For Click-Through Rate Prediction](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Qihang Zhao, Xiaoyang Zheng, **Ben Chen**, Zhongbo Sun, Chenyi Lei, **ArXiv:2509.19876**
- [Preference Aware Item Cold-Start Recommendation With Hierarchical Item Alignment](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Wenbo Wang, **Ben Chen**, Bingquan Liu, Lili Shan, Chengjie Sun, Qian Chen, Feiyang Xiao, Jian Guan, **TKDE 2025**
- [LLMs-based machine translation for E-commerce](https://papers.ssrn.com/sol3/Delivery.cfm?abstractid=4682559), Qihang Zhao, Xiaoyang Zheng, **Ben Chen**, Zhongbo Sun, Chenyi Lei, **ESWA 2025**
- [Modula: Mixture of domain-specific and universal lora for multi-task learning](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Yufei Ma, Zihan Liang, Huangyu Dai, **Ben Chen**, Dehong Gao, Zhuoran Ran, et. al. **EMNLP 2025**
- [Self-Renewal Prompt Optimizing with Implicit Reasoning](https://dl.acm.org/doi/pdf/10.1145/3746252.3760880), Zihan Liang, **Ben Chen**, Zhuoran Ran, Zihan Wang, Huangyu Dai, Yufei Ma, Dehong Gao, Xiaoyan Cai, Libin Yang, **EMNLP 2025**
- [Contrastive Token Learning with Similarity Decay for Repetition Suppression in Machine Translation](https://arxiv.org/pdf/2409.19877), Huangyu Dai, **Ben Chen**, Kaidi Chen, Ying Han, Zihan Liang, Wen Jiang, **ArXiv:2509.19876**
- [Robust Interaction-Based Relevance Modeling for Online e-Commerce Search](https://arxiv.org/pdf/2406.02135?), **Ben Chen**, Huangyu Dai, Xiang Ma, Wen Jiang, Wei Ning, **ECML-PKDD** <span style="color:red">(Outstand Paper)</span>
- [General2specialized llms translation for e-commerce](https://dl.acm.org/doi/pdf/10.1145/3589335.3651510), Kaidi Chen, **Ben Chen**, Dehong Gao, Huangyu Dai, Wen Jiang, Wei Ning, Shanqing Yu, Libin Yang, Xiaoyan Cai, **WWW 2024**
- [Mutual Information Assisted Graph Convolution Network for Cold-Start Recommendation](https://ieeexplore.ieee.org/abstract/document/10447656), Wenbo Wang, **Ben Chen**, Bingquan Liu, Xinxin Wang, Luwei Yang, Wen Jiang, Wei Ning, Jian Guan, **ICASSP 2024**
- [Preference aware dual contrastive learning for item cold-start recommendation](https://ojs.aaai.org/index.php/AAAI/article/view/28763/29465), Wenbo Wang, Bingquan Liu, Lili Shan, Chengjie Sun, **Ben Chen**, Jian Guan, **AAAI 2024**
- [RCDN--Robust X-Corner Detection Algorithm based on Advanced CNN Model](https://arxiv.org/pdf/2307.03505), **Ben Chen**, Caihua Xiong, Quanlin Li, Zhonghua Wan, **Arxiv 2024**
- [Fashionklip: Enhancing e-commerce image-text retrieval with fashion multi-modal conceptual knowledge graph](https://aclanthology.org/2023.acl-industry.16.pdf), Xiaodan Wang, Chengyu Wang, Lei Li, Zhixu Li, **Ben Chen**, Linbo Jin, Jun Huang, Yanghua Xiao, Ming Gao, **ACL 2024**
- [Unified Vision-Language Representation Modeling for E-Commerce Same-Style Products Retrieval](https://dl.acm.org/doi/pdf/10.1145/3543873.3584632), **Ben Chen**, Linbo Jin, Xinxin Wang, Dehong Gao, Wen Jiang, Wei Ning, **WWW 2023**
- [Automatic checkerboard detection for robust camera calibration](https://www.computer.org/csdl/proceedings-article/icme/2021/09428389/1uilx7JUJyw), **Ben Chen**, Yuyao Liu, Caihua Xiong, **ICME 2021**
- [Leveraging domain agnostic and specific knowledge for acronym disambiguation](https://arxiv.org/pdf/2107.00316), Qiwei Zhong, Guanxiong Zeng, Danqing Zhu, Yang Zhang, Wangli Lin, **Ben Chen**, Jiayu Tang, **AAAI 2021**
- [LNSMM: Eye gaze estimation with local network share multiview multitask](https://arxiv.org/pdf/2101.07116), Yong Huang, **Ben Chen**, Daiming Qu, **ArXiv:2101.07116**
- [Transformer-based language model fine-tuning methods for COVID-19 fake news detection](https://arxiv.org/pdf/2101.05509), **Ben Chen**, Bin Chen, Dehong Gao, Qijin Chen, Chengfu Huo, Xiaonan Meng, Weijun Ren, Yang Zhou, **AAAI 2021** <span style="color:red">(Share Task Best Paper)</span> 
- [Kaleido-bert: Vision-language pre-training on fashion domain](http://openaccess.thecvf.com/content/CVPR2021/papers/Zhuge_Kaleido-BERT_Vision-Language_Pre-Training_on_Fashion_Domain_CVPR_2021_paper.pdf), Mingchen Zhuge, Dehong Gao, Deng-Ping Fan, Linbo Jin, **Ben Chen**, Haoming Zhou, Minghui Qiu, Ling Shao, **CVPR 2021**
- [Fashionbert: Text and image matching with adaptive loss for cross-modal retrieval](https://ieeexplore.ieee.org/abstract/document/10447656), Dehong Gao, Linbo Jin, **Ben Chen**, Minghui Qiu, Peng Li, Yi Wei, Yi Hu, Hao Wang, **SIGIR 2020**
- [CCDN: Checkerboard corner detection network for robust camera calibration](https://arxiv.org/pdf/2302.05097), **Ben Chen**, Caihua Xiong, Qi Zhang, **ICIRA 2018 Oral**

# 📖 Educations
- *2017.09 - 2020.06*, Master, Huazhong University of Science and Technology, Wuhan. 
- *2013.09 - 2017.06*, Undergraduate, Wuhan University, Wuhan. 

# 🎖 Honors and Awards
- *2024.05*, The Outstanding paper of ECML-PKDD 2024. 
- *2021.02*, The Best paper of AAAI2021 Shared Task Track. 


# 💬 Invited Talks
- *2025.11*, [The 4th National Large Model and Generation Conference (LMG2025)](https://mp.weixin.qq.com/s/R46_AxdH1dSniAmesIqHvQ). 
- *2025.10*, The KuaiShou Technical Sharing Seminar
- 

# 💻 Internships
- *2019.07 - 2020.06*, Alibaba, Hangzhou.