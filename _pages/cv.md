---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education 教育经历
======
* M.S. in Guangdong Polytechnic Normal University, Pattern recognition and intelligent system, 2021.09-2024.06
硕士研究生, 广东技术师范大学，模式识别与智能系统(控制科学与工程), 2021.09-2024.06
* B.S. in Foshan University, Electronic Information Engineering, 2016.09-2020.06
佛山科学技术学院，本科, 电子信息工程, 2016.09-2020.06

Project
===
|No.|proj_name|infos|
|--|--|--|
|1|数据挖掘与量化功能分级任务|在医院康复科的数据来源下，我参与了一个数据挖掘项目，完成康复患者的量化功能分级任务。我的主要职责是实验部分,包括数据收集、数据清理以及机器学习/深度学习模型的建模。通过使用 Pandas 库进行数据收集和清理， NumPy 进行数据预处理,并借助 Matplotlib 进行初步的数据可视化，有效地分析了数据的分布和趋势。最终，我基于 sklearn和PyTorch 框架分别构建了机器学习,深度学习模型，用于量化评估康复患者的功能水平。|
|2|商标图像检索挑战赛|我参与了2022年的“云图搜”商标图像检索挑战赛，该比赛旨在开发一个高效的商标图像检索模型,并以F1-score分数衡量参赛队伍算法模型性能。我基于 PyTorch 框架进行数据处理，并自主编写了训练脚本，完成了模型的训练和验证。通过优化模型架构和训练策略，最终地提高了商标图像检索的准确性和效率。|
|3|图像分类与模型对比分析|我在图像分类领域开展了一系列项目，涵盖了多个数据集，包括CIFAR-10、CIFAR-100、Imagenette和Imagewoof，以及大型数据集 IP102 农业害虫数据集。我在项目中负责数据预处理、模型搭建和改进，并与多个先进模型进行了对比分析。在过程中,掌握了pytorch lighting的训练框架，wandb进行实验记录。通过实践，我不仅熟练掌握了数据增强和模型调优的技巧，还深入了解了现有模型的优缺点和适用场景。|
|4|目标检测与农业虫情监测系统|在 IP102 害虫数据集中，我基于 mmdetection 框架开展了目标检测任务。利用数据集中部分有标注信息的图像，我训练了一个目标检测模型，成功地实现了农业虫情的监测和识别。在此过程中，学习掌握了分布式训练，单机多卡的训练能加速我的训练过程。此外，我还参与了“挑战杯”计算机科学学院大学生课外科技作品竞赛，获得了优秀奖，我与团队合作开发了基于深度学习和物联网的农业虫情监测系统，为农业生产提供了智能化解决方案。|


比赛
======
* 2022年第十七届"挑战杯"计算机科学学院大学生课外科技作品竞赛 优秀奖：“基于深度学习和物联网的农业虫情监测系统”

Skills
======
* Python
* deep learning libraries: 
  * Pytorch, mmdet, mmyolo, ...
  * pillow, pandas, numpy, matplotlib, 
  * wandb, tensorboard, pytorch-lightning, timm, 
* CET-6 : 520

Publications
======

  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Volunteer services:
* 第三届广东院士高峰年会 志愿者, 2017/5/12 ~ 2017/5/14

<!--

Talks
======

  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
# Teaching

  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Service and leadership
======
* Currently signed in to 43 different slack teams

Work experience
======



-->