# Lab of Behavior & Conservation
# 行为生态与生物保护实验室


{% capture logo_1 %}

{% include figure.html image="images/ecnu-logo.png" %}

{% endcapture %}


{% capture logo_2 %}

{% include figure.html image="images/mclab.png" %}

{% endcapture %}


{% include cols.html col1=logo_1 col2=logo_2 %}


{% include section.html %}


## Highlights


{% capture research_text %}

Our research

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

Lab members and alumni

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
