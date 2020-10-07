---
title: Home
---

<div> 
    <img src="{{ '/images/graduation shirt picture copy.jpg' | absolute_url }}" alt="graduation shirt pic" style="width:55%;" >
</div>

Junkun Ren

> Peking University

# Junkun's Homepage

Junkun's personal [webpage](https://junkunren.github.io/personal-web/) for academic work


# About
  
social:
  - icon: envelope
    icon_pack: fas
    link: "#contact"
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/GeorgeCushen
  - icon: google-scholar
    icon_pack: ai
    link: https://scholar.google.co.uk/citations?user=sIwtMXoAAAAJ
  - icon: github
    icon_pack: fab
    link: https://github.com/gcushen
    
Education:
    - course: M.S. in Epidemiology
      institution: Harvard University
      year: 2019
    - course: B.S. in Food Science and Engineering
      institution: Shanghai Jiaotong University
      year: 2017

Contact:
email: ""

I am currently working with [Dr. Shaopeng Wang](http://scholar.pku.edu.cn/spwang) at the Theoretical Ecology Group at Peking University in Beijing, China and  working on a project previously initiated at Dartmouth College with [Dr. Dorothy Wallace](https://math.dartmouth.edu/~dwallace/). 

Prior to working at the theoretical ecology lab at Peking University, I worked as a research assistant at the Space Medicine Lab at Dartmouth College, doing data and epidemiological analyses. I studied epidmeiology at Harvard University and food science & engineering at Shanghai Jiao Tong Univerisity, during which I developed good quantitative skills.

# Research interests

I am particularly passionate about understanding and developing models and theories related to ecology and biology. My research interests include food-webs, coexistence, and stability. I am also interested in applying mathematical modeling to questions like infectious disease transmission intervention.

interests:
- theoretical ecology 
- mathematical biology
  - Food-web
  - Coexistence
  - Stability
  - Disease ecology
  
<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> updated Oct 2020
