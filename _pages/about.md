---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in the [School of Computer Science](https://cs.pku.edu.cn/) at [Peking University](https://www.pku.edu.cn), where my advisor is Professor [Guoping Wang](https://www.graphics.pku.edu.cn/xztd/jgfaculty/wgp2/index.htm#CN_intro). After earning my bachelor’s degree from [Northeastern University](http://www.neu.edu.cn) in 2020, I continued at its [Software College](http://sc.neu.edu.cn) and completed my master’s degree in 2023 under the supervision of Associate Professor [Rongfei Zeng](https://wingfeitsang.github.io/home/).

## Research Interest
My research focuses on 3D vision, with interests in 3D reconstruction, novel view synthesis, world models, and computer graphics.

## Publications

{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship<br>
<sup>†</sup> Corresponding author
