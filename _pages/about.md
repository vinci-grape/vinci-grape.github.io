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

**Xin Yin (殷鑫)** is the second-year Ph.D. student at [Zhejiang University](https://www.zju.edu.cn/english/), supervised by [Prof. Chao Ni](https://jacknichao.github.io/). I also obtained Bachelor’s degree at Central South University. 

<!-- During my graduate study, I was lucky to collaborate with the CMU Speech Team led by [Prof. Shinji Watanabe](https://scholar.google.com/citations?user=U5xRA6QAAAAJ), and Audio Research Team at Zhejiang University. I was grateful to intern or collaborate at TikTok, Shanghai AI Lab, Tencent Seattle Lab, Alibaba Qwen, with [Yi Ren](https://github.com/RayeRen), [Jinglin Liu](https://github.com/MoonInTheRiver), [Chunlei Zhang](https://scholar.google.com/citations?user=NCKZGb0AAAAJ) and [Dong Yu](https://scholar.google.com/citations?user=tMY31_gAAAAJ). -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

My research interest includes **Software Testing, Software Security, and Software Analytics**. I have published papers at the top international conferences such as **FSE/ISSTA/ICSE**. I developed a few well-known approaches including:
- [SVulD](https://github.com/vinci-grape/SVulD) and [MVulD](https://github.com/vinci-grape/MVulD): vulnerability detection
- [ThinkRepair](https://github.com/vinci-grape/ThinkRepair): program repair
- [Rectifier](https://github.com/vinci-grape/Rectifier): code translation
- [AUGER](https://github.com/vinci-grape/AUGER): unit test generation
<!-- - AudioGPT, UniAudio, Make-A-Voice: Multitask, Multilingual LLMs -->
<!-- - Make-An-Audio, GenerSpeech: Zero-shot text-guided synthesis -->
<!-- - FastDiff 1/2, ProDiff: AIGC diffusion models -->
<!-- - TranSpeech, and AV-TranSpeech: Multimodal Translation -->

In 2024, I lead or participate in the following research topics:
- Software Testing: unit test generation
- Large Language Models (LLMs): knowledge editing
<!-- - Diffusion models: Image/Audio/3D -->

# 🔥 News
<!-- - *2024.09*: &nbsp;🎉 One paper was accepted by APSEC 2024! -->
- *2024.10*: &nbsp;🎉 One paper was accepted by ICSE 2025!
- *2024.09*: &nbsp;🎉 One paper was accepted by TPAMI 2024!
- *2024.09*: &nbsp;🎉 One paper was accepted by TSE 2024!
- *2024.07*: &nbsp;🎉 One paper was accepted by ISSTA 2024!
<!-- - *2023.09*: &nbsp;🎉 One paper was accepted by EMNLP 2023! -->
- *2023.05*: &nbsp;🎉 One paper was accepted by FSE 2023! 
<!-- - *2023.03*: &nbsp;🎉 One paper was accepted by ICPC 2023! -->
<!-- - *2022.11*: &nbsp;🎉 One paper was accepted by ISPA 2022! -->

# 📝 Publications
<!-- * denotes co-first authors, # denotes co-supervised -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->
## Preprints
- [Enhancing Discriminative Tasks by Guiding the Pre-trained Language Model with Large Language Model's Experience](https://arxiv.org/pdf/2408.08553), **Xin Yin**, Chao Ni, Xiaodan Xu, Xinrui Li, Xiaohu Yang, **Arxiv**
<!-- - [Learning-based Models for Vulnerability Detection: An Extensive Study](https://arxiv.org/pdf/2408.07526), Chao Ni, Liyu Shen, Xiaodan Xu, **Xin Yin**, Shaohua Wang, **Arxiv** -->
- [Abundant Modalities Offer More Nutrients: Multi-Modal-Based Function-level Vulnerability Detection](), Zhi Yu, **Xin Yin**, Chao Ni, Xiaodan Xu, **Arxiv** -->
- [Rectifier: Code Translation with Corrector via LLMs](https://arxiv.org/pdf/2407.07472), **Xin Yin**, Chao Ni, Tien N. Nguyen, Shaohua Wang, Xiaohu Yang, **Arxiv**
<!-- - [Pros and Cons! Evaluating ChatGPT on Software Vulnerability](https://arxiv.org/pdf/2404.03994), **Xin Yin**, **Arxiv** -->

## Peer-Reviewed
<!-- - [Automatic Commit Range Identification of Untagged Version](), Yan Zhu, Lingfeng Bao, Chengjie Chen, Lexiao Zhang, **Xin Yin**, Chao Ni, **APSEC 2024, CCF-C** -->
- [What You See Is What You Get: Attention-based Self-guided Automatic Unit Test Generation](), **Xin Yin**, Chao Ni, Xiaodan Xu, Xiaohu Yang, **ICSE 2025, CCF-A**
- [Multitask-based Evaluation of Open-Source LLM on Software Vulnerability](https://arxiv.org/pdf/2404.02056), **Xin Yin**, Chao Ni, Shaohua Wang, **TSE 2024, CCF-A**
- [ThinkRepair: Self-Directed Automated Program Repair](https://arxiv.org/pdf/2407.20898), **Xin Yin**, Chao Ni, Shaohua Wang, Zhenhao Li, Limin Zeng, Xiaohu Yang, **ISSTA 2024, CCF-A**
- [Distinguishing Look-Alike Innocent and Vulnerable Code by Subtle Semantic Representation Learning and Explanation](https://arxiv.org/pdf/2308.11237), Chao Ni, **Xin Yin**, Kaiwen Yang, Dehai Zhao, Zhenchang Xing, Xin Xia, **FSE 2023, CCF-A**
<!-- - [FVA: Assessing Function-Level Vulnerability by Integrating Flow-Sensitive Structure and Code Statement Semantic](https://ieeexplore.ieee.org/abstract/document/10174072), Chao Ni, Liyu Shen, Wei Wang, Xiang Chen, **Xin Yin**, Lexiao Zhang, **ICPC 2023, CCF-B** -->
<!-- - [Spatio-temporal aware knowledge graph embedding for recommender systems](https://ieeexplore.ieee.org/abstract/document/10070740), Liu Yang, **Xin Yin**, Jun Long, Tingxuan Chen, Jie Zhao, Wenti Huang, **ISPA 2022, CCF-C** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.09 - Present*, Ph.D. student, Zhejiang University. 
- *2018.09 - 2022.06*, Bachelor, Central South University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2024.06 - Present*, State Key Laboratory of Blockchain and Data Security, Hangzhou.
- *2023.07 - 2023.10*, Software Engineering Application Technology Lab at Huawei, Hangzhou.
