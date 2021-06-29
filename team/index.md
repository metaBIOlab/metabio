---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: masters"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: collaborator"
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

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html

  image1="https://upload.wikimedia.org/wikipedia/commons/a/a2/Instituto_Serrapilheira_logo.png"
  link1="https://serrapilheira.org/"
  tooltip1="Instituto Serrapilheira"

  image2="images/cnpq.jpg"
  link2="https://www.gov.br/cnpq/pt-br"
  tooltip2="Conselho Nacional de Desenvolvimento Científico e Tecnológico - CNPq"

  image3="images/photo.jpg"
  link3="https://nasa.gov/"
  tooltip3="Cool Initiative"
%}


{% include section.html %}

## Partners
We would be nothing without them, our partners and collaborators.


{%
  image3="images/logoidor.png"
  link3="https://www.rededorsaoluiz.com.br/instituto/idor"
  tooltip3="Instituto D'Or de Pesquisa e Ensino - IDOR"
%}

