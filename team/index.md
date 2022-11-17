---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Our team is currently at the University of Arizona in the Atmospheric Science Department. Dr.Dong and Dr.Xi are the leaders.

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
  filters="role: lead"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{:.center}

{% include section.html background="images/ceres.clouds.jpg" dark=true%}

If interested in joining the team as a prospective student, please reached out to Dr.Dong. Further infromation for the University of Arizona Hydrology and Atmospheric Sciences degree program can be found [here.](https://has.arizona.edu/)

{% include section.html %}
