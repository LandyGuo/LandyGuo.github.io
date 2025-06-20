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

# About me
I am currently a staff algorithm engineer of Ant Group, leading a team of over ten individuals for research and development in multi-modal LLMs. My main interest is to design and deliver cognitive computing services, including computer vision, visual language alignment and multimodal video understanding. I have published 30+ papers in top-tier conferences and journals, including CVPR/ICML/SIGIR/ECCV/IJCAI/AAAI.

I am currently looking for full-time algorithm engineers and research interns. Please contact me (qingpei.gqp@antgroup.com) with your CV if you are interested!


# 🔥 News
- *2025.05*: &nbsp;🎉🎉 We proposed [Ming-Omni](https://arxiv.org/pdf/2506.09344) \| [![](https://img.shields.io/github/stars/inclusionAI/Ming?style=social&label=Stars)], a unified multimodal model capable of processing images, text, audio, and video, while demonstrating strong proficiency in both speech and image generation. 

# 📝 Selected Publications ([Complete publication list](https://scholar.google.com/citations?hl=zh-CN&user=11HDEbkAAAAJ&view_op=list_works&sortby=pubdate))
### (* : Corresponding author)   

- ## Unified multimodal model 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/Ming.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Ming-Omni: A Unified Multimodal Model for Perception and Generation](https://arxiv.org/pdf/2506.09344)

**Project lead**.

[**Project**](https://github.com/inclusionAI/Ming) \| ![](https://img.shields.io/github/stars/inclusionAI/Ming?style=social&label=Stars)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/M2omni.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[M2-omni: Advancing omni-mllm for comprehensive modality support with competitive performance](https://arxiv.org/pdf/2502.18778)

**Qingpei Guo**, Kaiyou Song, Zipeng Feng, Ziping Ma, Qinglong Zhang, Sirui Gao, Xuzheng Yu, Yunxiao Sun, Tai-Wei Chang, Jingdong Chen, Ming Yang, Jun Zhou
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/CVPR25_1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SegAgent: Exploring Pixel Understanding Capabilities in MLLMs by Imitating HumanAnnotator Trajectories](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhu_SegAgent_Exploring_Pixel_Understanding_Capabilities_in_MLLMs_by_Imitating_Human_CVPR_2025_paper.pdf)

 Muzhi Zhu, Yuzhuo Tian, Hao Chen, Chunluan Zhou, **Qingpei Guo**<sup><b>*</b></sup>, Yang Liu, Ming Yang, Chunhua Shen

  [**Code**](https://github.com/aim-uofa/SegAgent) \| ![](https://img.shields.io/github/stars/aim-uofa/SegAgent?style=social&label=Stars)
</div>
</div>

- ## Multimodal video understanding

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/CVPR25.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DynFocus: Dynamic Cooperative Network Empowers LLMs with Video Understanding](https://openaccess.thecvf.com/content/CVPR2025/papers/Han_DynFocus_Dynamic_Cooperative_Network_Empowers_LLMs_with_Video_Understanding_CVPR_2025_paper.pdf)

Yudong Han, **Qingpei Guo**<sup><b>*</b></sup>, Liyuan Pan, Liu Liu, Yu Guan, Ming Yang

 [**Code**](https://github.com/Simon98-AI/DynFocus) \| ![](https://img.shields.io/github/stars/Simon98-AI/DynFocus?style=social&label=Stars)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SIGIR 2024</div><img src='images/SIGIR2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[M2-RAAP: A Multi-Modal Recipe for Advancing Adaptation-based Pre-training towards Effective and Efficient Zero-shot Video-text Retrieval](https://dl.acm.org/doi/pdf/10.1145/3626772.3657833)
 
 XingningDong, ZipengFeng, ChunluanZhou, XuzhengYu, MingYang, **Qingpei Guo**<sup><b>*</b></sup>
 </div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2024</div><img src='images/ICML2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[SyCoCa: Symmetrizing Contrastive Captioners with Attentive Masking for Multimodal Alignment](https://dl.acm.org/doi/10.5555/3692070.3693455)

Ziping Ma, Furong Xu, Jian Liu, Ming Yang, **Qingpei Guo**<sup><b>*</b></sup>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2024</div><img src='images/NIPS2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Referencing Where to Focus: Improving Visual Grounding with Referential Query](https://neurips.cc/virtual/2024/poster/93628)

Yabing Wang, Zhuotao Tian, **Qingpei Guo**, Zheng Qin, Sanping Zhou, Ming Yang, Le Wang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/CVPR2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[Pink: Unveiling the Power of Referential Comprehension for Multi-modal LLMs](https://openaccess.thecvf.com/content/CVPR2024/papers/Xuan_Pink_Unveiling_the_Power_of_Referential_Comprehension_for_Multi-modal_LLMs_CVPR_2024_paper.pdf)

Shiyu Xuan1, **Qingpei Guo**, Ming Yang, Shiliang Zhang

[**Code**](https://github.com/SY-Xuan/Pink)\| ![](https://img.shields.io/github/stars/SY-Xuan/Pink?style=social&label=Stars)
</div>
</div>

- ## Application of MLLMs

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2024</div><img src='images/ACL2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
  
[HOTVCOM: Generating buzzworthy comments for videos](https://aclanthology.org/2024.findings-acl.130.pdf)
 
 Yuyan Chen, Yiwen Qian, Songzhou Yan, Jiyuan Jia, Zhixu Li, Yanghua Xiao, Xiaobo Li, Aaron Xuxiang Tian, Ming Yang, **Qingpei Guo**<sup><b>*</b></sup>
</div>
</div>

# 💬 Invited Talks
- *2024.07*, My speech about our model [Ming-Omni](https://www.isc.org.cn/article/21390285410922496.html).

# 📖 Educations
- *2014 - 2017*,   Master of Computer Applied Technology           [Institute of Software, Chinese Academy of Sciences](http://english.is.cas.cn/). 
- *2010 - 2014*,   Bachelor of Telecommunications Engineering      [Huazhong  University of Science and Technology](https://english.hust.edu.cn/)
- *2010 - 2014*,   Bachelor of Business Management (Dual Degrees)  [Huazhong  University of Science and Technology](https://english.hust.edu.cn/)


# 🎖 Fellowships & Awards
- Master Enterprise Supervisor of Chinese Academy of Sciences the Enterprise mentor.      
- [Master Enterprise Supervisor of Fudan University.](https://gs.fudan.edu.cn/1f/fe/c11107a663550/page.htm)                                                                             
- [The first place of ICDAR MLT Text Localization.](https://rrc.cvc.uab.es/?ch=8&com=evaluation&task=1)                                                                                            
- [Third place in ICCV COCO Panoptic Segmentation Challenge.](https://competitions.codalab.org/competitions/19507)                                                                      
- [Project Li Pei Bao - Fully automated claims settlement without intervention for the first time. ](https://www.sohu.com/a/242140481_99940985)                            
- [Project Ding Sun Bao - Shenzhen Fintech Innovation Award.](https://developer.aliyun.com/article/814342)
- Reviewer of TPAMI/ CVPR/ ICCV/ IJCAI/ ECCV/ ACL/ ACM MM/ CoLM.
- China National Scholarship.            
- Extreme Ownership Award- Ant Group Annual Awards

