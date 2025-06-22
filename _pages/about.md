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

I am an Associate Professor with the School of Computer Science and Information Engineering (School of Artificial Intelligence), Hefei University of Technology under Prof. <a href="https://faculty.hfut.edu.cn/wm12/zh_CN/index.htm/">Meng Wang</a>.
I received my Ph.D. degree in the Institute of Information Science, Beijing Jiaotong University (BJTU), China, 2022, supervised by Prof. <a href="http://faculty.bjtu.edu.cn/8181/">Huihui Bai</a>. 
I was a Joint Ph.D. Student from Jul. 2021 to Jul. 2022 in the School of Computer Science and Engineering, Nanyang Technological University (NTU), Singapore, supervised by Prof. <a href="https://personal.ntu.edu.sg/wslin/Home.html">Weisi Lin</a>. 
I was fortunate to complete my Ph.D. degree in <a href="http://mepro.bjtu.edu.cn/">Mepro</a> Led by <a href="http://faculty.bjtu.edu.cn/5900/">Yao Zhao</a> (BJTU).
I also was fortunate to work closely with Prof. <a href="https://rmcong.github.io/">Runmin Cong</a> (SDU).



# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 One TIP paper is accepted. -->
- 🎉🎉 One TIP paper is accepted.
- 🎉🎉 One CVPR paper is accepted. Congratulations to Shuoyan.
- 🎉🎉 One ICLR paper is accepted. Congratulations to Anqi.
- 🎉🎉 Three AAAI papers are accepted.
- 🎉🎉 One TPAMI paper is accepted. Congratulations to Man Liu.
- 🎉🎉 One IJCV paper is accepted.
- 🎉🎉 We won the 2nd place on NTIRE 2024 Stereo Image Super-Resolution Challenge-Track 1 (CVPR2024). Congratulations to Rongxin.
- 🎉🎉 One TII paper and one TOMM paper are accepted.
- 🎉🎉 Two TMM papers are accepted.
- 🎉🎉 One TCSVT paper is accepted.
- 🎉🎉 One paper is accepted by CVPR 2023 and was selected as 1 of 10% highlight.

# 📝 Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><img src='images/RIISSR_TIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Reference-based Iterative Interaction with P^2-Matching for Stereo Image Super-Resolution

Runmin Cong, Rongxin Liao, <strong style="color: purple;">Feng Li*</strong>, Ronghui Sheng, Huihui Bai, Renjie Wan, Sam Kwong, and Wei Zhang

IEEE Transactions on Image Processing (<strong>IEEE TIP</strong>), 2025
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/EvEnhancerV1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
EvEnhancer: Empowering Effectiveness, Efficiency and Generalizability for Continuous Space-Time Video Super-Resolution with Events

Shuoyan Wei, <strong style="color: purple;">Feng Li\*</strong>, Shengen Tang, Yao Zhao, Huihui Bai*

IEEE Conference on Computer Vision and Pattern Recognition (**CVPR, Top 13.5% highlight**), 2025

[[Arxiv]](https://arxiv.org/pdf/2505.04657)
[[Code]](https://github.com/W-Shuoyan/EvEnhancer)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/ControlGIC.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Once-for-All: Controllable Generative Image Compression with Dynamic Granularity Adaption

Anqi Li, <strong style="color: purple;">Feng Li\*</strong>, Yuxi Liu, Runmin Cong, Yao Zhao, Huihui Bai*

International Conference on Learning Representations (**ICLR**), 2025

[[Arxiv]](https://arxiv.org/pdf/2406.00758)
[[Code]](https://github.com/lianqi1008/Control-GIC)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/SRConvNet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
SRConvNet: A Transformer-Style ConvNet for Lightweight Image Super-Resolution

<strong style="color: purple;">Feng Li</strong>, Runmin Cong*, Jingjing Wu, Huihui Bai, Meng Wang, Yao Zhao

International Journal of Computer Vision (**IJCV**), 2025

[[PDF]](https://link.springer.com/content/pdf/10.1007/s11263-024-02147-y.pdf)
[[Code]](https://github.com/lifengcs/SRConvNet)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/GranularDQ.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Thinking in Granularity: Dynamic Quantization for Image Super-Resolution by Intriguing Multi-Granularity Clues

Mingshen Wang, Zhao Zhang*, <strong style="color: purple;">Feng Li*</strong>, Ke Xu, Kang Miao, Meng Wang

AAAI Conference on Artificial Intelligence (**AAAI**), 2025

[[Arxiv]](https://arxiv.org/pdf/2409.14330)
[[Code]](https://github.com/MmmingS/Granular-DQ.git)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/AENet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Attend and Enrich: Enhanced Visual Prompt for Zero-Shot Learning

Man Liu, Huihui Bai*, <strong style="color: purple;">Feng Li*</strong>, Chunjie Zhang, Yunchao Wei, Tat-Seng Chua, and Yao Zhao

AAAI Conference on Artificial Intelligence (**AAAI**), 2025

[[Arxiv]](https://arxiv.org/abs/2406.03032)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/sign-idd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Sign-IDD: Iconicity Disentangled Diffusion for Sign Language Production

Shengeng Tang, Jiayi He, Dan Guo, Yanyan Wei*, <strong style="color: purple;">Feng Li</strong>, Richang Hong*

AAAI Conference on Artificial Intelligence (**AAAI, Oral**), 2025

[[Arxiv]](https://arxiv.org/pdf/2412.13609)
[[Code]](https://github.com/NaVi-start/Sign-IDD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/tpami.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
PSVMA+: Exploring Multi-granularity Semantic-visual Adaption for Generalized Zero-shot Learning

Man Liu, Huihui Bai*, <strong style="color: purple;">Feng Li*</strong>, Chunjie Zhang, Yunchao Wei, Meng Wang, Tat-Seng Chua, Yao Zhao

IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2024

[[PDF]](https://ieeexplore.ieee.org/document/10693541)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/blinddiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
BlindDiff: Empowering Degradation Modelling in Diffusion Models for Blind Image Super-Resolution

<strong style="color: purple;">Feng Li</strong>, Yixuan Wu, Zichao Liang, Runmin Cong, Huihui Bai*, Yao Zhao, and Meng Wang.

Science China-Information Science (**SCIS**), 2024

[[Arxiv]](https://arxiv.org/abs/2403.10211)
[[Code]](https://github.com/lifengcs/BlindDiff)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/psvma.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Progressive Semantic-Visual Mutual adaption for Generalized Zero-Shot Learning

Man Liu, <strong style="color: purple;">Feng Li</strong>, Chunjie Zhang, Yunchao Wei, Huihui Bai*, and Yao Zhao

IEEE Conference on Computer Vision and Pattern Recognition (**CVPR, Top 10% highlight**), 2023

[[PDF]](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Progressive_Semantic-Visual_Mutual_Adaption_for_Generalized_Zero-Shot_Learning_CVPR_2023_paper.pdf)
[[Code]](https://github.com/ManLiuCoder/PSVMA)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/fdsr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Towards Fast and Accurate Real-World Depth Super-Resolution: Benchmark Dataset and Baseline

Lingzhi He, Hongguang Zhu, <strong style="color: purple;">Feng Li</strong>, Huihui Bai, Runmin Cong, Chunjie Zhang, Chunyu Lin, Meiqin Liu, Yao Zhao

IEEE Conference on Computer Vision and Pattern Recognition (**CVPR**), 2021

[[PDF]](https://openaccess.thecvf.com/content/CVPR2021/papers/He_Towards_Fast_and_Accurate_Real-World_Depth_Super-Resolution_Benchmark_Dataset_and_CVPR_2021_paper.pdf)
[[Supplementary Material]](https://openaccess.thecvf.com/content/CVPR2021/supplemental/He_Towards_Fast_and_CVPR_2021_supplemental.pdf) 
[[Homepage]](http://mepro.bjtu.edu.cn/resource.html)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/CDINet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Cross-Modality Discrepant Interaction Network for RGB-D Salient Object Detection

Chen Zhang, Runmin Cong, Qinwei Lin, Lin Ma, <strong style="color: purple;">Feng Li</strong>, Yao Zhao, Sam Kwong

ACM International Conference on Multimedia (**ACM MM**), 2021

[[PDF]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475364)
[[Code]](https://github.com/1437539743/CDINet-ACM-MM21)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/ROP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Towards Complete Scene and Regular Shape for Distortion Rectification by Curve-aware Extrapolation

Kang Liao, Chunyu Lin, Yunchao Wei, <strong style="color: purple;">Feng Li</strong>, Shangrong Yang, Yao Zhao

IEEE International Conference on Computer Vision (**ICCV**), 2021

[[PDF]](https://openaccess.thecvf.com/content/ICCV2021/papers/Liao_Towards_Complete_Scene_and_Regular_Shape_for_Distortion_Rectification_by_ICCV_2021_paper.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/din.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Deep Interleaved Network for Single Image Super-Resolution with Asymmetric Co-attention

<strong style="color: purple;">Feng Li†</strong>, Runmin Cong†, Huihui Bai, Yifan He

International Joint Conference on Artificial Intelligence (**IJCAI**), 2020

[[PDF]](https://arxiv.org/pdf/2004.11814.pdf)
[[Code]](https://github.com/lifengcs/DIN)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/DDAN.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Learning a Deep Dual Attention Network for Video Super-Resolution

<strong style="color: purple;">Feng Li</strong>, Huihui Bai, and Yao Zhao

IEEE Transactions on Image Processing (**TIP**), 2020

[[PDF]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8995790)
[[Code]](https://github.com/lifengcs/DDAN)
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- 
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div>
</div> -->

<!-- Orther pubs (list) -->
<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->