# Lab of Behavior & Conservation
# 行为生态与保护生物学实验室

{% capture school_logo %}

{%
  include figure.html
  image="images/ecnu-logo.png"
  height="110px"
%}

{% endcapture %}

{% capture lab_logo %}

{%
  include figure.html
  image="images/mclab.png"
  height="110px"
%}

{% endcapture %}

{%
  include cols.html
  col1=school_logo
  col2=lab_logo
%}


{% include section.html %}


## Highlights

{% capture publication_text %}

Recent publications from the Lab.

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
  title="Publications"
  text=publication_text
%}


{% capture team_text %}

Lab members and alumni.

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
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=team_text
  flip=true
%}
