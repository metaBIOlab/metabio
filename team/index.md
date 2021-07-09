---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We are an very special team, trully multidisciplinary focused on solving big questions.

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{:.center}

{% include section.html %}
## Current team:
### Postdoc:
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{:.center}

### PhD:
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}

### Masters:
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters"
%}
{:.center}

### Undergrads:
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Check for updates! Soon.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Partners and collaborators
We would be nothing without them, our partners and collaborators.
{:.center}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: collaborator"
%}
{:.center}

{%
  include gallery.html
  
  image1="images/cnnplab_menor.png"
  link1="https://sites.google.com/view/cnnp-lab/"
  tooltip1="Computational Neurology, Neuroscience & Psychiatry Lab, CNNP - Newcastle University, Newcastle upon Tyne, UK"
  width="150px"
  
  image2="images/logoidor.png"
  link2="https://www.rededorsaoluiz.com.br/instituto/idor"
  tooltip2="Instituto D'Or de Pesquisa e Ensino - IDOR, Rio de Janeiro, Brasil"
  width="150px"
%}
{:.center}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="images/serrapilheira.png"
  link1="https://serrapilheira.org/"
  tooltip1="Instituto Serrapilheira"
  width="150px"

  image2="images/cnpq-logo-7.png"
  link2="https://www.gov.br/cnpq/pt-br"
  tooltip2="Conselho Nacional de Desenvolvimento Científico e Tecnológico - CNPq"
  width="150px"
%}
{:.center}
