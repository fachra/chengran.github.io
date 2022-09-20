---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* Ph.D in Computer science and applied mathematics, Paris-Saclay University, 2022 (expected)
* M.S. in Signal processing, Ecole Centrale de Lyon, 2019 (double degree)
* M.S. in Electrical engineering, Beihang University, 2019
* B.S. in Applied mathematics, Beihang University, 2016

Software
======

* [swc2mesh](https://github.com/fachra/swc2mesh): Robust and automatic neuron meshes generator
* [FourierPotential](https://github.com/fachra/FourierPotential): Fourier representation of the diffusion MRI signal using layer potentials
* [SpinDoctor](https://github.com/SpinDoctorMRI/SpinDoctor): Diffusion MRI Simulation Toolbox in Matlab

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
