---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Resume](https://github.com/fachra/fachra.github.io/raw/master/files/CV_english.pdf) in pdf format.

Education
---------

* Ph.D. in Computer science and applied mathematics, University of Paris-Saclay, 2023 (expected)
* M.S. in Signal processing, École Centrale de Lyon, 2019 (diplôme d'ingénieur)
* M.S. in Electrical engineering, Beihang University, 2019
* B.S. in Applied mathematics, Beihang University, 2016

Software
--------

* Author of [swc2mesh](https://github.com/fachra/swc2mesh): A robust and automatic neuron mesh generator.
* Author of [FourierPotential](https://github.com/fachra/FourierPotential): A Fourier representation of the diffusion MRI signal using layer potentials.
* Contributor of [SpinDoctor](https://github.com/SpinDoctorMRI/SpinDoctor): A diffusion MRI simulation toolbox in Matlab.

Skills
------

* Programming language: Python, Matlab
* Language: Chinese, English, French

Publications
------------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Talks
-----
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

