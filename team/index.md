---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our team:


{% include section.html %}

{% include list.html data="members" component="portrait" filters="description: Full Professor (Head of the Lab)" %}
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/unisa.jpg" dark=true %}

Do you want to hear more?

{% include section.html %}

Please contact if you are interested in joining our lab as a postdoc, PhD student, or an intern (e.g. during a PhD abroad period), we welcome international collaborations and students!

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
