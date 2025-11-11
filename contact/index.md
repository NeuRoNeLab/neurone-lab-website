---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

You can find us at the [Laboratory for Molecular Cell Biology (LMCB)](https://www.ucl.ac.uk/life-sciences/lmcb) at [University College](https://www.ucl.ac.uk/)

{%
  include button.html
  type="email"
  text="j.delas@ucl.ac.uk"
  link="j.delas@ucl.ac.uk"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/EvCwEkcWjJmP7iBt6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/UCL_main.jpg"
  caption="UCL"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/LMCB_UCL.jpg"
  caption="LMCB within UCL"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

