---
title: Members
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}

{% include section.html background="images/background.jpg" dark=true %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

{% include section.html %}

{% capture content %}

[Maedeh Hemmat, PhD'21](https://wiscad.github.io/wiscad/members/maedeh-hemmat.html)

{% include list.html data="members" component="portrait" filters="name: Wei Zeng" %}

{% include list.html data="members" component="portrait" filters="name: Boyu Zhang" %}

{% include list.html data="members" component="portrait" filters="name: Jonathon Magaña" %}

{% include list.html data="members" component="portrait" filters="name: Daohang Shi" %}

{% include list.html data="members" component="portrait" filters="name: Daniel Seemuth" %}

{% include list.html data="members" component="portrait" filters="name: Min Li" %}

{% include list.html data="members" component="portrait" filters="name: Hamid Shojaei" %}

{% include list.html data="members" component="portrait" filters="name: Tai-Hsuan Wu" %}

{% include list.html data="members" component="portrait" filters="name: Lin Xie" %}










{% endcapture %}

{% include grid.html style="square" content=content %}
