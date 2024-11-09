---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is located in Gateway South Room 328. We also have regular meet ups scheduled as part of HCI@Stevens. Please see the information below.

{%
  include button.html
  type="email"
  text="jhuhyoo@stevens.edu"
  link="jhuhyoo@stevens.edu"
%}
{%
  include button.html
  type="email list"
  text="hci-sig@lists.stevens.edu"
  link="hci-sig@lists.stevens.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Gateway South 328, Stevens Institute of Technology"
  link="https://g.co/kgs/9eENfG1"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/flyer.jpg"
  caption="Flyer for HCI@Stevens"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/stevens.jpg"
  caption="Stevens Institute of Technology"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
{% endcapture %}

{% capture col2 %}
{% endcapture %}

{% capture col3 %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
