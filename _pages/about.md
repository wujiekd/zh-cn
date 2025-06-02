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

**算法研究围绕多模态交互与建模，业务涉及LLM大模型和图像生成。**

我目前就职于**华为，终端云小艺**。硕士毕业于**中国科学技术大学**, 导师是於俊副教授, 企业导师是平安科技美国硅谷研究院院长Peng Chang和Iek-Heng Chu。本科毕业于广州大学, 导师是人工智能研究院执行院长李进教授和王显珉副教授。目前参与发表文章10余篇。 <a href='https://scholar.google.com/citations?user=MmZ_y1QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

本科和研究生期间以来经常参加算法比赛，累计国内外AI算法竞赛获奖10余次，掌握丰富的比赛经验和策略。 此外，担任阿里安全学生专家小组成员, [阿里安全挑战者计划排行榜](https://s.alibaba.com/challenge?spm=a2c22.12281976.0.0.46db2a69WaN1Te)第七名。




我的研究领域包括：
- 多模态交互与建模 (CV/NLP)
- AIGC
- 细粒度图像识别
- 鲁棒机器学习

我的业务方向包括：
- 大语言模型
- 探索性数据分析 (EDA)
- 数据挖掘
- 风格迁移 (Autoencoder、GAN、Diffusion model)
- 目标检测


<!-- <span class='anchor' id='-news'></span>

# 🔥 新闻 -->


<span class='anchor' id='-lwzl'></span>

# 📝 发表论文



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024 (CCF-A)</div><img src='images/CEAM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dialogue Cross-Enhanced Central Engagement Attention Model for Real-Time Engagement Estimation](https://www.ijcai.org/proceedings/2024/353) \\
Jun Yu, **Keda Lu**, Ji Zhao et al. (学生一作)

1. 为了解决sliding window的重复推理问题，提出cente-based sliding window，推理效率提升100%。
2. 提出基于自注意力机制的核心参与度注意力模型，超越先前的SOTA的BiLSTM模型，推理效率提升300%。
3. 基于交叉注意力提出交叉增强模块，和核心参与度注意力模型无缝集成，交互对话者的特征，实现了实时参与度估计任务新的SOTA。

<!-- [**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech) -->
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024 (CCF-A) workshop</div><img src='images/mvav.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MvAV-pix2pixHD: Multi-view Aerial View Image Translation](https://openaccess.thecvf.com/content/CVPR2024W/PBVS/html/Yu_MvAV-pix2pixHD_Multi-view_Aerial_View_Image_Translation_CVPRW_2024_paper.html) \\
Jun Yu, **Keda Lu**, Shenshen Du et al. (学生一作)

1. 设计针对多视角图像翻译任务的时间优先采样和随机采样方法。
2. 提出了用于多视角图像翻译的MvAV-pix2pixHD，使用了三个强大的loss。
3. 该论文的方法应用于MAVIC-T竞赛中的2个多视角图像翻译任务中取得了1个冠军和1个亚军。


<!-- [**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech) -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM-MM 2023 (CCF-A)</div><img src='images/sw2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `ACM-MM 2023(CCF-A)` [Sliding Window Seq2seq Modeling for Engagement Estimation](https://dl.acm.org/doi/abs/10.1145/3581783.3612852) \\
Jun Yu, **Keda Lu**, Mohan Jing et al. (学生一作)

- `TOMM 2024在投(CCF-B)` [Exploring Seq2seq Models for Engagement Estimation in
Dyadic Conversations]() \\
Jun Yu, **Keda Lu**, Lei Wang et al. (学生一作)

1. 基于Transformer和BiLSTM模型提出Seq2seq参与度估计模型，实现了当前参与度估计任务新的SOTA。Transformer尝试4种绝对和相对位置编码，包括RoPE。
2. 针对长视频直接划分遇到的上下文大量丢失问题，提出滑动窗口提升性能。
3. 提出Ai-BiLSTM去对齐和交互对话者的多模态特征，进一步提升性能。
4. 该论文的方法应用于ACM-MM 2023中的参与度估计竞赛中取得了冠军。

<!-- [**Project**](https://portaspeech.github.io/) \| [![](https://img.shields.io/github/stars/NATSpeech/NATSpeech?style=social&label=Code+Stars)](https://github.com/NATSpeech/NATSpeech) \| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/NATSpeech/PortaSpeech) -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Trans 在投</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Comprehensive and Unified Out-of-Distribution Classification Solution Framework]() \\
Jun Yu, **Keda Lu**, Yifan Wang et al. (学生一作)

1. (数据)提出semantic masking数据增强用于提升模型针对occlusion场景的鲁棒性，并提出了OOD-DAS，一个全面且鲁棒的数据增强集合。
2. (模型)提出OOD-Attention，可用于SOTA分类模型无缝集成，提升模型鲁棒性。
3. (策略)提出多架构模型集成的迭代伪标签方法，进一步提升OOD识别的精度。
4. 该论文的方法应用于ICCV 2023的OOD识别竞赛中取得了冠军。

</div>
</div>

- `ACM-MM 2024` [End-to-end Spatio-Temporal Information Aggregation For Micro-Action Detection]() Jun Yu, Mohan Jing, Gongpeng Zhao, **Keda Lu** et al.

- `ACM-MM 2024` [Building Robust Video-Level Deepfake Detection via Audio-Visual Local-Global Interactions]() Yifan Wang, Xuecheng Wu, Jia Zhang, Mohan Jing, **Keda Lu** et al.

- `ACM-MM 2023` [Answer-Based Entity Extraction and Alignment for Visual Text Question Answering](https://dl.acm.org/doi/abs/10.1145/3581783.3612850) Jun Yu, Mohan Jing, Weihao Liu, Tongxu Luo, Bingyuan Zhang, **Keda Lu** et al.


- `CLEF 2022` [Bag of Tricks and a Strong Baseline for FGVC.](https://ceur-ws.org/Vol-3180/paper-182.pdf) Jun Yu, Hao Chang, **Keda Lu** et al.


- `CLEF 2022` [Efficient Model Integration for Snake Classification](https://ceur-ws.org/Vol-3180/paper-181.pdf) Jun Yu, Hao Chang, Zhongpeng Cai, Guochen Xie, Liwen Zhang, **Keda Lu** et al.


- `CVPR 2022 workshop` [Pseudo-label generation and various data augmentation for semi-supervised hyperspectral object detection](https://openaccess.thecvf.com/content/CVPR2022W/PBVS/html/Yu_Pseudo-Label_Generation_and_Various_Data_Augmentation_for_Semi-Supervised_Hyperspectral_Object_CVPRW_2022_paper.html) Jun Yu, Liwen Zhang, Shenshen Du, Hao Chang, **Keda Lu** et al.


- `AAAI 2022 workshop` [Mining limited data for more robust and generalized ML models](https://alisec-competition.oss-cn-shanghai.aliyuncs.com/competition_papers/20211201/rank10.pdf), Jun Yu, Hao Chang, **Keda Lu** et al.


- `International Journal of Machine Learning and Cybernetics` [Generating transferable adversarial examples based on perceptually-aligned perturbation](https://link.springer.com/article/10.1007/s13042-020-01240-1), Hongqiao Chen, **Keda Lu**, Xianmin Wang et al.



<span class='anchor' id='-ywxm'></span>

# 💻 业务项目

- *2024.03 - 至今* 多模态大模型

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EDA展示</div><img src='images/eda.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2023.10 - 2024.02* 贷款客户还款意愿识别

1. 基于百万级别宽表数据和千万级别通话文本进行探索性数据分析(EDA)。
2. EDA->数据清洗->特征工程，使用Bert对文本建模，识别客户的还款意愿。
3. 尝试利用LLM对通话文本进行数据增强，提高模型鲁棒性。
</div>
</div>

- *2023.05 - 2023.09* 垂直领域聊天助手(构建训练语料，基于ChatGLM、Bloomz、Qwen等lora微调对比)



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OCR大模型展示</div><img src='images/ocrdemo.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2023.03 - 2023.06* OCR大模型展示平台(左图为本人实现demo，以防侵权)

1. 使用Gradio作为前后端，搭建了整个OCR大模型展示接口，包括DocQA、MLLM和纯OCR模块。
2. 本人独立维护，方便对内分析调试，对外业务展示，该项目获得2023年H1【XXX·企点荣誉激励】——技术进步奖。
3. 独立负责DocQA模块，具体细节是对输入的文档、图片等采用ocr提取得到文字后，分段采用embedding后存储到数据库，根据输入的问题也进行embedding，将与之匹配的TopK个段落，一起输入LLM。


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">中文字体生成</div><img src='images/font.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2023.01 - 2023.03* 任意风格中文字体生成 (GAN、Diffusion model)

1. 调研了中文字体生成算法，主流采用GAN，唯一一个采用了Diffusion model(Diff-Font)，但其风格编码器采用的是GAN预训练的模块。
2. 自行搜集400类字体数据，基于Diffusion model(DDPM)设计端到端的字体生成模型，在SSIM、LPIPS等指标上略优于Diff-Font和DG-Font，但加入风格编码的整体结构训练缓慢。

- 未来改进点：End2end、对比学习、Diffusion model
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">文档生成和风格迁移</div><img src='images/style.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2022.11 - 2023.01* 文档生成和风格迁移（独立调研）

1. 探索Diffusion model和GAN在端到端文档生成的可能性。
2. 调研了各大顶会五年来的风格迁移文章，CNN->Attention->Transformer，包括AdaIN(ICCV2017)、MetaNet(CVPR2018)、SANet(CVPR2019)、MAST(ACM-MM 2020)、StyleFormer(ICCV2021)、AdaAttN(ICCV2021)和StyTr2(CVPR2022)。
3. 复现其中的StyTr2(CVPR2022)和AdaAttN(ICCV2021)，并迁移到文档生成任务中，用于数据增强。

- 未来改进点：对比学习、GAN、Diffusion model

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">人脸识别和文本检测</div><img src='images/mindspore.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2022.06 - 2022.12* 基于Mindspore算法框架复现主流算法

1. 参与复现了[RetinaFace人脸检测算法](https://github.com/mindspore-lab/mindface)
2. 独立复现了[FCENet文本检测算法](https://github.com/mindspore-lab/mindocr)
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">课程管理系统</div><img src='images/class.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
- *2020.12 - 2021.01* 遗传算法智能排课——课程管理系统（独立实现）

<!-- 1. 使用广州大学本年级的全部师生真实数据进行设计，包含学号、姓名、专业、入学年份、课程信息等详细信息。 -->
1. 使用sqlite3进行数据库管理，使用Bootstrap-Flask进行可视化设计，学生、教师和系主任采用统一登陆界面，不同客户端界面；包含各种选课功能等。
2. 提出排课智能算法，对排课情况提出了一种新型的优化目标函数（利用课程方差），使用了**遗传算法**对其优化进行排课。
3. 该项目有2000+行的python代码和1000+行的html代码，已开源至[个人博客](https://blog.csdn.net/weixin_43999137/article/details/113178364)与[Github](https://github.com/wujiekd/Integrated-course-design-of-software-direction)，阅读量3,000+，累计下载量50+。

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">学生成绩管理系统</div><img src='images/score.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- *2019.04 - 2019.06* 基于MFC(C++)学生成绩管理系统（独立实现）

1. 包含增删查改全部基础功能，并且有导入、保存、排序等功能。
2. 设计主要参考了QQ的大登录按钮界面，让人产生清晰干净的感觉。
3. 该项目有10000+行的C++代码，已开源至[个人博客](https://blog.csdn.net/weixin_43999137/article/details/91184179)与[Github](https://github.com/wujiekd/MFC-student-performance-management-system)，阅读量10,000+，累计下载量200+。
</div>
</div>


<span class='anchor' id='-cyjs'></span>

# 🏅 参与竞赛

### 研究生阶段（主要参与）
---

- *2024.07* [ACM-MM 2024: Grand challenge, Multi-Domain Engagement Estimation](https://multimediate-challenge.org/) (个人solo, **冠军**🏆) [[排行榜]](https://multimediate-challenge.org/leaderboards/leaderboard_engagement/)
  
- *2024.03* [CVPR 2024: Multi-modal Aerial View Image Challenge - Translation](https://codalab.lisn.upsaclay.fr/competitions/17224) (Top3奖金池2500$, 个人solo, **亚军**🥈) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/17224#results) [[论文]](https://openaccess.thecvf.com/content/CVPR2024W/PBVS/html/Yu_MvAV-pix2pixHD_Multi-view_Aerial_View_Image_Translation_CVPRW_2024_paper.html)


- *2023.10* [ICCV 2023: Out Of Distribution Generalization: Object Classification track](https://codalab.lisn.upsaclay.fr/competitions/14068#results) (个人solo, **冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/14068#results) [[论文在投]]()


- *2023.10* [ICCV 2023: Out Of Distribution Generalization: Pose Estimation track](https://codalab.lisn.upsaclay.fr/competitions/14074#learn_the_details) (个人solo, **冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/14074#results) [[技术报告]](https://www.ood-cv.org/reports/pose/ImageNet1k-1st.pdf)


- *2023.07* [ACM-MM 2023: Grand challenge, Engagement Estimation](https://multimediate-challenge.org/) (个人solo, **冠军**🏆) [[排行榜]](https://multimediate-challenge.org/leaderboards/leaderboard_engagement/) [[论文]](https://dl.acm.org/doi/abs/10.1145/3581783.3612852) [[新闻]](https://cloud.tencent.com/developer/news/1167803)


- *2022.10* [ECCV 2022: Out Of Distribution Generalization Track-1: Object Classification](https://www.ood-cv.org/challenge.html) (Top3奖金池3300$, 个人solo, **亚军**🥈) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/6781#results) [[代码]](https://github.com/wujiekd/ECCV2022-OOD-CV-Challenge-Classification-Track-2nd-USTC-IAT-United) 


- *2022.10* [ECCV 2022: Out Of Distribution Generalization Track-2: Object Detection](https://www.ood-cv.org/challenge.html) (Top3奖金池3300$, **亚军**🥈) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/6784#results) [[代码]](https://github.com/wujiekd/ECCV2022-OOD-CV-Challenge-detection-Track-2nd-Place-Program) 


- *2022.05* [CVPR 2022: FGVC9 workshop FungiCLEF2022 challenge](https://sites.google.com/view/fgvc9/competitions/fungiclef2022) (**亚军**🥈) [[排行榜]](https://www.kaggle.com/c/fungiclef2022/leaderboard) [[代码]](https://github.com/wujiekd/Bag-of-Tricks-and-a-Strong-Baseline-for-Fungi-Fine-Grained-Classification) [[论文]](https://ceur-ws.org/Vol-3180/paper-182.pdf) 


- *2022.03* [CVPR 2022: Multi-modal Aerial View Object Classification - Track 2 (SAR+EO)](https://codalab.lisn.upsaclay.fr/competitions/1392) (Top3奖金池6000$, **冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/1392#results) [[技术报告]](https://arxiv.org/abs/2205.01920) [[新闻]](https://zhuanlan.zhihu.com/p/493603389)


- *2022.03* [CVPR 2022: Multi-modal Aerial View Object Classification - Track 1 (SAR)](https://codalab.lisn.upsaclay.fr/competitions/1388) (Top3奖金池6000$, **冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/1388#results) [[技术报告]](https://arxiv.org/abs/2205.01920) [[新闻]](https://zhuanlan.zhihu.com/p/493603389)


### 研究生阶段（协助参与）
<!-- MM jmh 季军 iccv zj 冠军 cvpr shooc 和 mavic 冠军 ROSE冠军 -->
---
- *2024.07* [ACM-MM 2024: 1M-Deepfakes Detection Challenge](https://deepfakes1m.github.io/) (**冠军**🏆) [[排行榜]](https://deepfakes1m.github.io/2024) [[论文]](https://dl.acm.org/doi/10.1145/3664647.3688985)

- *2024.07* [ACM-MM 2024: Micro-Action Analysis Grand Challenge：Multi-label Micro-Action Detection](https://sites.google.com/view/micro-action) (**冠军**🏆) [[排行榜]](https://sites.google.com/view/micro-action/challenge/winners?authuser=0) [[论文]](https://dl.acm.org/doi/10.1145/3664647.3688974)

- *2024.07* [ACM-MM 2024: Micro-Action Analysis Grand Challenge：Micro-Action Detection](https://sites.google.com/view/micro-action) (**亚军**🥈) [[排行榜]](https://sites.google.com/view/micro-action/challenge/winners?authuser=0) [[论文]](https://dl.acm.org/doi/10.1145/3664647.3688974)

- *2023.12* [ICCV 2023: WECIA - Caption Generation Challenge](https://eval.ai/web/challenges/challenge-page/2104/overview) (**冠军**🏆) [[排行榜]](https://eval.ai/web/challenges/challenge-page/2104/leaderboard/5203)


- *2023.07* [ACM-MM 2023: Visual Text Question Answering](https://visual-text-qa.github.io/) (**季军**🥉) [[排行榜]](http://vtqa-challenge.fixtankwun.top:20010/) [[论文]](https://dl.acm.org/doi/abs/10.1145/3581783.3612850)


- *2023.03* [CVPR 2023: Multi-modal Aerial View Imagery Challenges - Translation](https://codalab.lisn.upsaclay.fr/competitions/9968) (Top3奖金池2250$, **冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/9968#results) [[论文]](https://link.springer.com/chapter/10.1007/978-981-99-8388-9_8) 


- *2022.06* [CVPR 2022: Robustness in Sequential Data challenge](https://codalab.lisn.upsaclay.fr/competitions/2618#learn_the_details) (**冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/2618#results) [[技术报告]](https://www.crcv.ucf.edu/wp-content/uploads/2018/11/USTC_IAT_first_solution_rose_challenge_22.pdf) [[新闻]](https://nelslip.ustc.edu.cn/2022/0608/c26914a562921/page.htm)


- *2022.03* [CVPR 2022: Semi-Supervised Hyperspectral Object Detection Challenge](https://codalab.lisn.upsaclay.fr/competitions/1752) (**冠军**🏆) [[排行榜]](https://codalab.lisn.upsaclay.fr/competitions/1752#results) [[论文]](https://openaccess.thecvf.com/content/CVPR2022W/PBVS/html/Yu_Pseudo-Label_Generation_and_Various_Data_Augmentation_for_Semi-Supervised_Hyperspectral_Object_CVPRW_2022_paper.html)


### 本科生阶段
---

- *2022.08* [中国高校计算机大赛—微信大数据挑战赛](https://algo.weixin.qq.com/) (前十奖金池56万¥, 个人solo, **全国二等奖**, Top30/3000+)  [[排行榜]](https://algo.weixin.qq.com/) [[代码]](https://github.com/wujiekd/WeChat-Big-Data-Challenge-2022-National-Second-Prize-Top30) 


- *2022.01* [AAAI 2022：以数据为中心的鲁棒机器学习竞赛](https://advml-workshop.github.io/aaai2022/) (前十奖金池100万¥, 个人solo, 初赛2/3692, **复赛10/3692**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/531939/rankingList) [[代码]](https://github.com/wujiekd/RTA-Iterative-Search-AAAI2022) [[论文]](https://alisec-competition.oss-cn-shanghai.aliyuncs.com/competition_papers/20211201/rank10.pdf) 


- *2021.11* [OPPO安全AI挑战赛-人脸识别攻击](https://security.oppo.com/challenge/home.html) (前十奖金池60万¥, 个人solo, 初赛6/2000+, **复赛12/2000+**) [[排行榜]](https://security.oppo.com/challenge/rank.html) [[代码]](https://github.com/wujiekd/Hot-restart-black-box-face-adversarial-attack) 


- *2021.03* [CVPR 2021：防御模型的白盒对抗攻击](https://aisecure-workshop.github.io/amlcvpr2021/) (前十奖金池10万$, 个人solo, **排名20/1681**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/531847/rankingList?lang=zh-cn) [[代码]](https://github.com/wujiekd/CVPR2021_ODI_BIM_Attack?spm=a2c22.21852664.0.0.7830775fHm2G8V)  [[博客]](https://tianchi.aliyun.com/forum/post/208313)

- *2020.10* [伪造图像的对抗攻击竞赛(阿里天池和清华大学联合举办)](https://tianchi.aliyun.com/competition/entrance/531812) (前十奖金池200万¥, **排名6/1666**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/531812/rankingList)


- *2020.08* [腾讯广告算法大赛](https://algo.qq.com/) (前十奖金池10万$, 初赛第6名, **复赛第11名**, 1万+人参加) [[代码]](https://github.com/wujiekd/2020-Tencent-advertising-algorithm-contest-rank11) [[博客]](https://blog.csdn.net/weixin_43999137/article/details/107657517?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522171314962516800222817673%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fall.%2522%257D&request_id=171314962516800222817673&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~first_rank_ecpm_v1~rank_v31_ecpm-1-107657517-null-null.142^v100^pc_search_result_base3&utm_term=%E8%85%BE%E8%AE%AF%E5%B9%BF%E5%91%8A%E7%AE%97%E6%B3%95%E5%A4%A7%E8%B5%9Bwujiekd&spm=1018.2226.3001.4187)


- *2020.04* [二手车交易价格预测正式赛(阿里天池联合Datawhale举办)](https://tianchi.aliyun.com/competition/entrance/231784) (个人solo, 优胜奖,  **排名13/2815**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/231784/rankingList) [[代码]](https://github.com/wujiekd/Predicting-used-car-prices) [[博客]](https://tianchi.aliyun.com/forum/post/104728) 

- *2020.03* [文本分类对抗攻击竞赛(阿里天池和清华大学联合举办)](https://tianchi.aliyun.com/competition/entrance/231762) (前十奖金池6.8万¥, **排名4/1666**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/231762/rankingList) [[代码]](https://github.com/wujiekd/NLP_Chinese_adversarial_attack) [[博客]](https://tianchi.aliyun.com/forum/post/95886) 



- *2019.12* [ImageNet图像分类对抗(阿里天池和清华大学联合举办)](https://tianchi.aliyun.com/competition/entrance/231761) (前十奖金池6.8万¥, **排名5/1522**) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/231761/rankingList) [[博客]](https://tianchi.aliyun.com/forum/post/87389)


- *2019.10* [国际安全极客大赛(GeekPwn2019)CAAD CTF总决赛](https://geekcon.top/hof/zh/index.html) (总决赛奖金池10万¥，**上海总决赛第五名**, 唯一本科生队伍) [[排行榜]](https://tianchi.aliyun.com/competition/entrance/231784/rankingList) [[新闻]](https://www.gzhu.edu.cn/info/1070/3803.htm) 


<span class='anchor' id='-ryjx'></span>

# 🎖 荣誉奖项
- *2025.03* 安徽省优秀毕业生
- *2025.03* 中国科学技术大学优秀毕业生
- *2024.10* 国家奖学金(研究生前1%)
- *2023.11* 华为奖学金(全校30位)
- *2023.10* 国家奖学金(研究生前1%)
- *2022.10* 国家奖学金(研究生前1%)
- *2021.10* 国家奖学金(本科前1%)
- *2020.10* 国家奖学金(本科前1%)


<span class='anchor' id='-xl'></span>

# 🎓 教育
- *2022.09 - 2025.07*, <a href="https://www.ustc.edu.cn/"><img class="svg" src="/images/ustclogo.png" width="23pt"></a> 中国科学技术大学, 计算机技术, 推荐免试, 硕士
- *2018.09 - 2022.06*, <a href="https://www.gzhu.edu.cn/"><img class="svg" src="/images/gzhulogo.png" width="20pt"></a> 广州大学, 计算机科学与技术(1/591), 本科


<span class='anchor' id='-xshy'></span>

# 🏛️ 学术会议
- *2024.03*, 昇思人工智能框架产业峰会(华为主办), 受华为邀请, 北京。
- *2023.11*, 第31届ACM多媒体国际会议, 渥太华, 加拿大。
- *2020.12*, 第一届AI与安全研讨会(清华大学人工智能研究院和阿里安全共同主办), 受阿里巴巴邀请, 北京。
- *2019.10*, 第五届GeekPwn国际安全极客大赛, 上海。

<span class='anchor' id='-gzsx'></span>

# 💻 工作经历
- *2025.06 - 至今*, 华为, 终端云服务小艺业务部
- *2023.10 - 2025.06*, 平安科技(实习), 美国硅谷研究院
- *2023.04 - 2023.06*, 网易(实习), 伏羲实验室
- *2022.11 - 2023.09*, 腾讯(实习), 优图实验室
- *2022.06 - 2022.12*, 华为(实习), 2012实验室



**Thank you very much for every visitor, and I look forward to hearing from you!**


<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=ffffff&w=a&t=tt&d=3TTDcMspE9blO-62HMEnb2GXkKIYDXKNLl2EQC_ygm4'></script>