---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-We are building a team with diverse background and expertises."></i>Team



{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: Lead"
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
  filters="role: programmer"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: master"
%}
{:.center}

{% include section.html background="images/banner.svg" dark=true%}

We are multiple opennings for master students with various projects in bioimage analysis and machine learning.

{% include section.html %}
