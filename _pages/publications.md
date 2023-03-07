---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<!--

[[1]于佳妮,贾西平,**马先盛**等.基于神经网络的ICF康复组合评定量化标准功能分级算法模型构建及其验证[J].中国康复医学杂志,2022,37(10):1347-1353+1370.]( https://kns.cnki.net/kcms2/article/abstract?v=OF-ZeHn9XyWNgpz8e29M6COuFORMTJi15BrO1wAFcRJ8uhm9cvb8HEKeEnwAU86hXoqlI_sh1R5BlubYDQU7X678zJxsTbqimm4T762HOnW54hkbfI0GnsRoVA9c4RoO&uniplatform=NZKPT&language=CHS)

-->
