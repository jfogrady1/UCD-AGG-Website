---
title: Team
nav:
  order: 3
  tooltip: About our team
redirect_from:
  /lab-members:
  /alumns:
  /staff:
  /trainees:
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab is made up of a highly engaged and collaborative team of researchers. 
We recognize that diverse teams do better research. 
We foster an environment where team members are treated equally, and where we respect and admire our differences. 
The team includes postdocs, PhD students and MSc students.

{% include section.html dark=true %}

{% include list.html data="members" component="portrait" filters="role: pi, group: " %} 
{% include list.html data="members" component="portrait" filters="role: postdoc, group: " %} 
{% include list.html data="members" component="portrait" filters="role: phd, group: " %} 
{% include list.html data="members" component="portrait" filters="role: undergrad, group: " %} 
{% include list.html data="members" component="portrait" filters="role: laboratory, group: " %}
{% include section.html background="images/background.jpg" dark=true %}

We work with a wide range of outstanding groups from around the world, and we’re always on the lookout for new and unique perspectives. 
We want to push the frontier of data science and train the next generation of data scientists.

{% include button.html icon="fa-solid fa-handshake-angle" text="Join the Team" link="join" style="button" %}

{% include section.html dark=true %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
