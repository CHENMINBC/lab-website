---
title: Home
---

# 行为生态与生物保护实验室&nbsp;&nbsp;&nbsp;&nbsp;Lab of Behavior & Conservation

{% capture logo_1 %}

{% include figure.html image="images/ecnu-logo.png" width="200%" %}

{% endcapture %}

{% capture logo_2 %}

{% include figure.html image="images/mclab.png" height="250px" %}

{% endcapture %}

{% include cols.html col1=logo_1 col2=logo_2 %}

{% include section.html %}

## Highlights

{% capture research_text %}

Our lab's research focuses on behavioural ecology and conservation biology of vertebrates. 本实验室主要开展脊椎动物行为生态学与保护生物学研究。

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=research_text
%}


{% capture team_text %}

Our lab members and alumni. 实验室成员及毕业生。

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}


{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=team_text
  flip=true
%}
