---
title: Members
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Past Members

{% include section.html %}

{% capture content %}

{% include list.html data="members" component="portrait" filters="role: alum" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
