---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

We are located in the Instituto de Física at the Universidade Federal do Rio de Janeiro. Currently working from home.
Be safe and use masks!

{%
  include link.html
  type="email"
  icon=""
  text="scrooge@mcduck.com"
  tooltip=""
  link="scrooge@mcduck.com"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(555) 867-5309"
  tooltip=""
  link="+1-555-867-5309"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://goo.gl/maps/6V7kYjvPdbk7Noni6"
  style="button"
%}
{:.center}

{% include section.html %}

### <i class="fas fa-mail-bulk"></i>Mailing Address

Instituto de Física \\
Centro de Tecnologia - Bloco A - Universidade Federal do Rio de Janeiro\\
Av. Athos da Silveira Ramos, 149 - Cidade Universitária\\
Rio de Janeiro - RJ, Brasil CEP: 21941-972
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="http://www.parque.ufrj.br/wp-content/uploads/2014/04/ct.png"
  caption="Centro de Tecnologia - UFRJ"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/photo.jpg"
  caption="Department of Metaphor"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
