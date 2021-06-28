---
title: Home
---

# metaBio

We are a neurosciences lab at a Physics Institute. Working with theoretical biology and experimental mathematics lab.
Today, our multidisciplinary team works with mainly on cortical folding models: their implications for cortical development and evolution in mammals, and applications for human health and disease.
  
{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Today, our multidisciplinary team works with mainly on cortical folding models: their implications for cortical development and evolution in mammals, and applications for human health and disease.

[See what we've published &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/rh.pialmesh3.png"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
We are creating a lot of good and cool stuff, wait for it.

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="resources"
  headline="Our Resources"
  text=text
%}

{% capture text %}
We are an very special team, trully multidisciplinary focused on solving a big question. Our PI, Bruno Mota has a Physics degree with masters and PhD in Astrophysics. We current have a physicist Postdoc, Victor B. Mello; two PhDs: Fernanda de Moraes (medical physicist) and Kamilla Souza (biologist); one Physics Master Degree student, Heitor Gessner...

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  headline="Our Team"
  text=text
%}
