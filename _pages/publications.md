---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

**Jin Zhang**, Xiaoyao Yu, Zhengwei Qi, and Haibing Guan. Falcon: A Timestamp-based Protocol to Maximize the Cache Efficiency in the Distributed Shared Memory. (IPDPS'22, *To Appear*)

**Jin Zhang**, Xingguo Jia\*, Boshi Yu, Xingyue Qian, Zhengwei Qi, and Haibing Guan. GiantVM: A Novel Distributed Hypervisor for Resource Aggregation with DSM-aware Optimizations. (TACO'22, *To Appear*)

**Jin Zhang**, Zhuocheng Ding, Yubin Chen, Xingguo Jia, Boshi Yu, Zhengwei Qi, and Haibing Guan. GiantVM: a Type-II Hypervisor Implementing Many-to-one Virtualization. (VEE'20)
[\[Paper\]](https://xianliang66.github.io/files/vee20.pdf) [\[Code\]](https://github.com/GiantVM) [\[Website\]](https://giantvm.github.io/)


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
