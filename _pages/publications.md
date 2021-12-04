---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

**Jin Zhang**, Zhuocheng Ding, Yubin Chen, Xingguo Jia, Boshi Yu, Zhengwei Qi, and Haibing Guan. GiantVM: a Type-II Hypervisor Implementing Many-to-one Virtualization. (VEE'20)
[\[Paper\]](https://xianliang66.github.io/files/vee20.pdf) [\[Code\]](https://github.com/GiantVM) [\[Website\]](https://giantvm.github.io/)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
