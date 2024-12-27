---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# <i class="fa fa-id-card" aria-hidden="true"></i>&ensp; About Me
I am a research assistant at [**BGI Research**](https://en.genomics.cn/), utilizing large language models to predict health with human microbiome. I earned my Bachelor's degree in Medicine with a specialization in Preventive Medicine from [**Sun Yat-sen University**](https://www.sysu.edu.cn/sysuen/), honored to be advised by  [Prof. Qian Jun](https://phs.sysu.edu.cn/zh-hans/teacher/510). Previously, I completed a clinical internship at [**the Seventh Affiliated Hospital, Sun Yat-sen University**](https://www.sysush.com/en). To date, I have published 7 research papers with <a href='https://scholar.google.com/citations?user=jqslgHAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

<span style="color: purple;">I am now preparing to pursue a PhD, with the intention of enrolling in either the School of Computer Science or the School of Medicine. If your research team has opportunities that align with my background and aspirations, I would be thrilled to discuss. Feel free to contact me!</span>

My research interest includes: 
- AI in Healthcare
- Machine Learning and Deep Learning
- Statistical analysis
- Medical imaging analysis
- Natural Language Processing
- Programming


<!-- # 🎓 Educations 
 -->
<span class='anchor' id='educations'></span>
# <i class="fa fa-graduation-cap" aria-hidden="true"></i>&ensp;Education
<div id="Education" class="bio" style="margin-bottom:-15px">
    {% include educations.html %}
  <br>
</div>

<span class='anchor' id='publications'></span>
# <i class="fa fa-book" aria-hidden="true" ></i> &ensp;Publications 
{% include publication.html %}


# 🏅 Honors and Awards
- *2015.11*  Win the `1st Prize` in the 14th "Challenge Cup" National Undergraduate Curricular Academic Science and Technology Works Competition.
- *2015.06* Win the `1st Prize` in the 13rd  "Challenge Cup" Sichuan Undergraduate Curricular Academic Science and Technology Works Competition. [[Newsreport]](https://www.sc.gov.cn/10462/10778/10876/2015/7/1/10341562.shtml)
- *2014.12* Win the `1st Prize` in the 4th National Undergraduate Engineering Training Integration Ability Competition (Sichuan Division).

# 💬 Conferences

- *2021.10*, National Seminar on Electromagnetic Nondestructive Testing Technology and the 14th Plenary Session of the 11th Session of the Electromagnetic Professional Technology Conference of China, Xian China, Oral.
- *2019.09*, The 19th International Symposium on Applied Electromagnetics and Mechanics (ISEM 2019), Nanjing China, Poster.
- *2017.10*, The 6th China International Pipeline Conference (CIPC 2017), Langfang China, Visit.


# 🏭 Internships
- *2018.05 - 2020.02*, Chongqing Changjiang Bearing Co., Ltd., Chongqing China.
- *2020.11.25 - 2020.12.02*, Hubei Xinyegang Steel Ltd., Huangshi China.
- *2017.6 - 2021.1*, Wuhan Huayu-M Testing Equipment Co., Ltd., Wuhan China.
  
