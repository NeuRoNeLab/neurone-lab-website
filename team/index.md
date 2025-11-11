---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet our team:


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/UCL.jpg" dark=true %}

Do you want to hear more?

{% include section.html %}

Please [reach out](/recruitment) if you are interested in joining. We are happy to support Early Career/postdoc fellowships. 

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}
