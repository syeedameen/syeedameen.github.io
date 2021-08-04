---
layout: archive
title: "Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

<p style="margin-left: 40px"><b>B.TECH in Computer Science & Engineering </b>
<br>Rajasthan Technical University, kota
<br><i>August 2017 - september 2021</i></p>

## Employment

<p style="margin-left: 40px"><b>Assistant Professor</b>
<br>Department of Psychological Sciences
<br>University of Connecticut
<br><i>August 2018 — present</i></p>

<p style="margin-left: 40px"><b>Moore-Sloan Data Science Fellow</b>
<br>Berkeley Institute for Data Science
<br>University of California, Berkeley
<br><i>August 2016 — July 2018</i></p>

<p style="margin-left: 40px"><b>Postdoctoral Scholar</b>
<br>Institute of Cognitive and Brain Sciences
<br>University of California, Berkeley
<br><i>January 2016 — July 2018</i></p>

## Peer-Reviewed Journal Publications

Mentees’ names underlined. Asterisk indicates dual first-author position.
Open access articles or preprints <nobr>(<i class="ai ai-fw ai-open-access-square"></i>)</nobr>
are linked below; all other PDFs <nobr>(<i class="fa fa-file-pdf-o" aria-hidden="true"></i>)</nobr>
are provided for **personal use only.** Supplementary materials on
GitHub <nobr>(<i class="fa fa-github" aria-hidden="true"></i>)</nobr> and
OSF <nobr>(<i class="ai ai-fw ai-osf"></i>)</nobr> for each publication are linked below the
citation.

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Refereed Conference Proceedings

Mentees’ names underlined. Asterisk indicates dual first-author position.
Open access articles or preprints <nobr>(<i class="ai ai-fw ai-open-access-square"></i>)</nobr>
are linked below; all other PDFs <nobr>(<i class="fa fa-file-pdf-o" aria-hidden="true"></i>)</nobr>
are provided for **personal use only.** Supplementary materials on
GitHub <nobr>(<i class="fa fa-github" aria-hidden="true"></i>)</nobr> and
OSF <nobr>(<i class="ai ai-fw ai-osf"></i>)</nobr> for each publication are linked below the
citation.

{% for post in site.proceedings reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
