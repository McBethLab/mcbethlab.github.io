---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the [Penn Medicine](https://www.pennmedicine.org/)'s [Department of Radiation Oncology](https://www.pennmedicine.org/departments-and-centers/radiation-oncology). We are located on the CN level of the [Perelman Center for Advanced Medicine.](https://www.pennmedicine.org/for-patients-and-visitors/penn-medicine-locations/perelman-center-for-advanced-medicine)

{%
  include button.html
  type="email"
  text="Rafe.Mcbeth@pennmedicine.upenn.edu"
  link="Rafe.Mcbeth@pennmedicine.upenn.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/tPArMR3cBF1tx2fz7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
