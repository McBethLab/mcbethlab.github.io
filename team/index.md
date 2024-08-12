---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: director" %}
{% include list.html data="members" component="portrait" filters="role: md" %}
{% include list.html data="members" component="portrait" filters="role: mp" %}
{% include list.html data="members" component="portrait" filters="role: phyres" %}
{% include list.html data="members" component="portrait" filters="role: masters" %}
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html background="images/background.jpg" dark=true %}

## Alumni Spotlight

Gone but never forgotten.
These are past lab members who have moved on to other school programs, new jobs, or elsewhere.
They have all made lasting contributions to science and to our hearts. ❤️

{% include list.html data="members" component="portrait" filters="role: alum" style="small" %}
