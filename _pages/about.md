---
permalink: /
title: # None
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


### About me

Hi! I am Lorenzo Pompili, a Research Fellow at the [Nottingham Centre of Gravity](https://www.nottingham.ac.uk/gravity/) 
and at the [School of Mathematical Sciences](https://www.nottingham.ac.uk/mathematics/) 
of the [University of Nottingham](https://www.nottingham.ac.uk/), working on gravitational-wave astrophysics. 
I completed my PhD in 2025 at the [Astrophysical and Cosmological Relativity Department](https://www.aei.mpg.de/astro-cosmo-rel) 
of the [Max Planck Institute for Gravitational Physics](https://www.aei.mpg.de/) in Potsdam, under the supervision of Prof. Alessandra Buonanno.

I am a member of the [LIGO Scientific Collaboration](https://www.ligo.org/), 
the [Einstein Telescope Collaboration](https://www.et-gw.eu/index.php) — 
where I coordinate the Waveforms Division of the Observational Science Board — 
and a member of the [LISA Consortium](https://www.lisamission.org/).

I am originally from [Perugia](https://en.wikipedia.org/wiki/Perugia), Italy, 
where I completed my undergraduate studies in Physics and went on to earn a Master's in Theoretical Physics at the University of Perugia. 

![Lorenzo Pompili](/images/pic.png)

### My work

My research lies at the intersection of gravitational-wave modeling and data analysis. 

I work on developing accurate and efficient models for the gravitational radiation emitted by coalescing compact binaries, 
both within General Relativity (GR) and in modified gravity theories, focusing on [effective-one-body](https://inspirehep.net/literature/479939) (EOB) 
models and their improvement through numerical relativity (NR). 
I am one of the main developers and a maintainer of the [pySEOBNR](https://git.ligo.org/waveforms/software/pyseobnr) python package, 
which underpins the SEOBNR family of waveform models widely used in LIGO-Virgo-KAGRA analyses. 

Additionally, I am interested in using these models to address open questions in fundamental physics and astrophysics. 
I employ them for Bayesian parameter estimation and tests of GR using data from current gravitational-wave detectors, LIGO, Virgo, and KAGRA. 
Some of the topics I am interested in include black-hole spectroscopy, parameter estimation for binaries in generic orbits, and 
understanding how waveform-modeling uncertainty propagates into astrophysical inference and how to account for it. 
I also make forecasts for next-generation detectors, including LISA and the Einstein Telescope, 
focusing on the challenges and accuracy requirements these future instruments will face.

More recently, I have been working on applications of artificial intelligence and machine-learning techniques 
to gravitational-wave data analysis and waveform modeling. 
This includes extensions and applications of the [DINGO](https://github.com/dingo-gw/dingo) framework for simulation-based inference
(neural posterior estimation), and machine-learning methods for the NR-calibration of waveform models.

### Research highlights

<div class="highlight-grid">
{% for h in site.data.highlights %}{% include highlight-card.html h=h %}{% endfor %}
</div>

