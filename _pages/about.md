---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at [School of Computer Science](https://cs.pku.edu.cn/), [Peking University](https://www.pku.edu.cn), supervised by Professor [Guoping Wang](https://www.graphics.pku.edu.cn/xztd/jgfaculty/wgp2/index.htm#CN_intro). I pursued my master's degree from the [Software College of Northeastern University](http://sc.neu.edu.cn) under the guidance of Associate Professor [Rongfei Zeng](https://wingfeitsang.github.io/home/) from 2020 to 2023. I earned my bachelor's degree from [Northeastern University](http://www.neu.edu.cn) in 2020.

## Research Interest
My research is on 3D Reconstruction, Novel View Synthesis, and Computer Graphics.

## Publications

{% if site.author.googlescholar %}
You can also find my articles on [my Google Scholar profile]({{ site.author.googlescholar }}).
{% endif %}

{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}

<sup>*</sup> Equal authorship<br>
<sup>†</sup> Corresponding author
