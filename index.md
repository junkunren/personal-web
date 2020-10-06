---
title: Home
---

<div> 
    <img src="{{ '/images/graduation shirt picture copy.jpg' | absolute_url }}" alt="graduation shirt pic" style="width:55%;" >
</div>

# Junkun's Homepage

Junkun's personal [webpage](https://junkunren.github.io/personal-web/) for academic work


# About

I am currently working with [Dr. Shaopeng Wang](http://scholar.pku.edu.cn/spwang) at the Theoretical Ecology Group at Peking University in Beijing, China and  working on a project previously initiated at Dartmouth College with [Dr. Dorothy Wallace](https://math.dartmouth.edu/~dwallace/). I am particularly passionate about understanding models and theories related to ecology and biology. My research interests include food-webs, coexistence, and stability. I am also interested in applying mathematical modeling to questions like infectious disease transmission intervention.

Prior to working at the theoretical ecology lab at Peking University, I worked as a research assistant at the Space Medicine Lab at Dartmouth College, doing data and epidemiological analyses. I studied epidmeiology at Harvard University and food science & engineering at Shanghai Jiao Tong Univerisity, during which I developed good quantitative skills.

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> updated Oct 2020

> built using [Jekyll](https://jekyllrb.com/), [GitHub Pages](https://pages.github.com/), and [workshop-template](https://github.com/evanwill/workshop-template).

