---
permalink: /publications
title: "Publications"
author_profile: true
redirect_from: 
- /pub
---

## 2024
<a name="pandora"></a>
**Pandora: Towards General World Model with Natural Language Actions and Video States**\
Jiannan Xiang<sup>\*</sup>, Guangyi Liu<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Qiyue Gao, Yuting Ning, Yuheng Zha, Zeyu Feng, Tianhua Tao, Shibo Hao, Yemin Shi, Zhengzhong Liu, Eric P. Xing, Zhiting Hu\
***Preprint*** [[Website]](https://world-model.ai) [[YouTube]](https://www.youtube.com/watch?v=nSKqr1Fl91g) [[Code]](https://github.com/maitrix-org/Pandora) [[Paper]](https://world-model.maitrix.org/assets/pandora.pdf)

<a name="k2"></a>
**LLM360 K2-65B: Scaling Up Fully Transparent Open-Source LLMs**\
Zhengzhong Liu, Bowen Tan, Hongyi Wang, Willie Neiswanger, Tianhua Tao, Haonan Li, Fajri Koto, Yuqi Wang, Suqi Sun, Omkar Pangarkar, Richard Fan, **Yi Gu**, Victor Miller, Liqun Ma, Liping Tang, Nikhil Ranjan, Yonghao Zhuang, Guowei He, Renxi Wang,Mingkai Deng, Robin Algayres, Yuanzhi Li, Zhiqiang Shen, Preslav Nakov, Eric Xing\
***Preprint*** [[Blog]](https://www.llm360.ai/blog/several-new-releases-to-further-our-mission.html) [[Paper]](https://www.llm360.ai/paper2.pdf) [[Weights]](https://huggingface.co/LLM360/K2)

<a name="reasoners"></a>
**LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models**\
Shibo Hao<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Haotian Luo<sup>\*</sup>, Tianyang Liu, Xiyan Shao, Xinyuan Wang, Shuhua Xie, Haodi Ma, Adithya Samavedhi, Qiyue Gao, Zhen Wang, Zhiting Hu\
***COLM 2024*** [[Website]](https://www.llm-reasoners.net) [[Library]](https://github.com/maitrix-org/llm-reasoners) [[Paper]](https://arxiv.org/abs/2404.05221)

**Text Grafting: Near-Distribution Weak Supervision for Minority Classes in Text Classification**\
Letian Peng, **Yi Gu**, Chengyu Dong, Zihan Wang, Jingbo Shang\
***EMNLP 2024*** [[Paper]](https://arxiv.org/abs/2406.11115)

**LLM360: Towards Fully Transparent Open-Source LLMs**\
Zhengzhong Liu, Aurick Qiao, Willie Neiswanger, Hongyi Wang, Bowen Tan, Tianhua Tao, Junbo Li, Yuqi Wang, Suqi Sun, Omkar Pangarkar, Richard Fan, **Yi Gu**, Victor Miller, Yonghao Zhuang, Guowei He, Haonan Li, Fajri Koto, Liping Tang, Nikhil Ranjan, Zhiqiang Shen, Xuguang Ren, Roberto Iriondo, Cun Mu, Zhiting Hu, Mark Schulze, Preslav Nakov, Tim Baldwin, Eric P. Xing\
***COLM 2024*** [[Blogpost]](https://www.llm360.ai/blog/introducing-llm360-fully-transparent-open-source-llms.html) [[Website]](https://www.llm360.ai) [[Code]](https://github.com/llm360) [[Models]](https://huggingface.co/LLM360) [[Paper]](https://arxiv.org/abs/2312.06550)

## 2023
**Reasoning with Language Model is Planning with World Model**\
Shibo Hao<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu\
***EMNLP 2023*** [[Paper]](https://arxiv.org/abs/2305.14992) [[Code]](https://github.com/Ber666/RAP) [[State of AI Report 2023]](https://docs.google.com/presentation/d/156WpBF_rGvf4Ecg19oM1fyR51g4FAmHV3Zs0WLukrLQ/edit#slide=id.g24daeb7f4f0_0_3930)

**Language Models Meet World Models: Embodied Experiences Enhance Language Models**\
Jiannan Xiang<sup>\*</sup>, Tianhua Tao<sup>\*</sup>, **Yi Gu**, Tianmin Shu, Zirui Wang, Zichao Yang, Zhiting Hu\
***NeurIPS 2023*** [[Paper]](https://arxiv.org/abs/2305.10626) [[Code]](https://github.com/szxiangjn/world-model-for-language-model)

**JECC: Commonsense Reasoning Tasks Derived from Interactive Fictions**\
Mo Yu<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Xiaoxiao Guo, Yufei Feng, Xiaodan Zhu, Michael Greenspan, Murray Campbell, Chuang Gan\
***Findings of ACL 2023*** [[Paper]](https://arxiv.org/abs/2210.15456) [[Code]](https://github.com/Gorov/zucc)

## 2022
**Revisiting the Roles of "Text" in Text Games**\
**Yi Gu**<sup>\*</sup>, Shunyu Yao<sup>\*</sup>, Chuang Gan, Joshua B. Tenenbaum, Mo Yu\
***Findings of EMNLP 2022*** [[Paper]](https://arxiv.org/abs/2210.08384) [[Code]](https://github.com/wu-qing-157/textgame-revisiting-role)

**Finding Fallen Objects Via Asynchronous Audio-Visual Integration**\
Chuang Gan<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Siyuan Zhou, Jeremy Schwartz, Seth Alter, James Traer, Dan Gutfreund, Joshua B. Tenenbaum, Josh McDermott<sup>\*</sup>, Antonio Torralba<sup>\*</sup>\
***CVPR 2022*** [[Paper]](https://arxiv.org/abs/2207.03483) [[Code]](https://github.com/chuangg/find_fallen_objects)

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
