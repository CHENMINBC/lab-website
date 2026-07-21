---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Team

## Current Lab Members

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'msc'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}

{% include section.html %}

## Alumni

{% include list.html data="members" component="portrait" filter="role == 'alumni'" %}