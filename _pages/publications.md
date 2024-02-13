---
permalink: /publications
title: "Publications"
author_profile: true
redirect_from: 
- /pub
---

## 2023
**Reasoning with Language Model is Planning with World Model**\
Shibo Hao<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu\
*Preprint* [[Paper]](https://arxiv.org/abs/2305.14992) [[Code]](https://github.com/Ber666/RAP)

**Language Models Meet World Models: Embodied Experiences Enhance Language Models**\
Jiannan Xiang<sup>\*</sup>, Tianhua Tao<sup>\*</sup>, **Yi Gu**, Tianmin Shu, Zirui Wang, Zichao Yang, Zhiting Hu\
*Preprint* [[Paper]](https://arxiv.org/abs/2305.10626) [[Code]](https://github.com/szxiangjn/world-model-for-language-model)

**JECC: Commonsense Reasoning Tasks Derived from Interactive Fictions**\
Mo Yu<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Xiaoxiao Guo, Yufei Feng, Xiaodan Zhu, Michael Greenspan, Murray Campbell, Chuang Gan\
*Findings of ACL 2023* [[Paper]](https://arxiv.org/abs/2210.15456) [[Code]](https://github.com/Gorov/zucc)

## 2022
**Revisiting the Roles of "Text" in Text Games**\
**Yi Gu**<sup>\*</sup>, Shunyu Yao<sup>\*</sup>, Chuang Gan, Joshua B. Tenenbaum, Mo Yu\
*Findings of EMNLP 2022* [[Paper]](https://arxiv.org/abs/2210.08384) [[Code]](https://github.com/wu-qing-157/textgame-revisiting-role)

**Finding Fallen Objects Via Asynchronous Audio-Visual Integration**\
Chuang Gan<sup>\*</sup>, **Yi Gu**<sup>\*</sup>, Siyuan Zhou, Jeremy Schwartz, Seth Alter, James Traer, Dan Gutfreund, Joshua B. Tenenbaum, Josh McDermott<sup>\*</sup>, Antonio Torralba<sup>\*</sup>\
*CVPR 2022* [[Paper]](https://arxiv.org/abs/2207.03483) [[Code]](https://github.com/chuangg/find_fallen_objects)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
