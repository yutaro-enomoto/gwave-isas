---
title: Members
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Members

どこから学生が来ているかなど。

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'faculty-staff' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'posdoc' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'master' and group != 'alum'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad' and group != 'alum'" %}

## Alumni -- 旧メンバー

{% include list.html data="members" component="portrait" filter="group == 'alum'" %}

{% include section.html background="images/background.jpg" dark=true %}

## Group Photos 集合写真

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
