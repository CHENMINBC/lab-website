# Lab of Behavior & Conservation
# 行为生态与保护生物学实验室

<div class="lab-logo-row">
  
  <img
    src="{{ 'images/ecnu-logo.png' | relative_url }}"
    alt="School logo"
    class="school-logo"
  >

  <img
      src="{{ 'images/mclab.png' | relative_url }}"
      alt="Lab of Behavior and Conservation logo"
      class="lab-logo"
    >
    
</div>

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
  image="images/publication.jpg"
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

<div class="reverse-feature">
  <div class="reverse-feature-text">
    <h3>
      <a href="{{ 'team' | relative_url }}">Our Team</a>
    </h3>

    {{ team_text }}
  </div>

  <div class="reverse-feature-image">
    <a href="{{ 'team' | relative_url }}">
      <img
        src="{{ 'images/team.jpg' | relative_url }}"
        alt="Members of the Lab of Behavior and Conservation"
      >
    </a>
  </div>
</div>
