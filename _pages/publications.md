---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

A list of my publications in reverse chronological order. For a complete and continuously updated record, see [INSPIRE-HEP](https://inspirehep.net/authors/2776658) or [arXiv](https://arxiv.org/a/pompili_l_1).

Publications of which I am lead or co-lead author are marked with <span class="pub-legend-star">&#9733;</span>. Publications with author-list in alphabetical order, as common in the high-energy physics community, are marked with **&lowast;&lowast;**.

### Short author-list publications

<div class="pub-grid">
{% assign last_year = "" %}{% for pub in site.data.publications.short %}{% if pub.year %}{% assign gy = pub.year %}{% else %}{% assign gy = pub.arxiv | slice: 0, 2 | prepend: '20' %}{% endif %}{% if gy != last_year %}<div class="pub-year">{{ gy }}</div>{% assign last_year = gy %}{% endif %}{% include pub-card.html pub=pub %}{% endfor %}
</div>

![Gravitational waveform from a binary black hole merger](/images/SXS_BBH_1225_Res5_polarisation_hp-1.png)

### Long author-list publications with direct personal contribution

As a member of the LIGO Scientific Collaboration, I am a co-author on many full-collaboration papers; see [INSPIRE](https://inspirehep.net/authors/2776658) for a complete list. Highlighted below are those to which I made a direct personal contribution. Papers for which I was part of the LIGO–Virgo–KAGRA Editorial Team are marked with <span class="pub-legend-star">&#9733;</span>.

<div class="pub-grid">
{% assign last_year = "" %}{% for pub in site.data.publications.long %}{% if pub.year %}{% assign gy = pub.year %}{% else %}{% assign gy = pub.arxiv | slice: 0, 2 | prepend: '20' %}{% endif %}{% if gy != last_year %}<div class="pub-year">{{ gy }}</div>{% assign last_year = gy %}{% endif %}{% include pub-card.html pub=pub %}{% endfor %}
</div>

### Press &amp; media coverage

Selected coverage of work I contributed to, from the Max Planck Institute for Gravitational Physics (AEI):

- **May 2026** — [Gravitational-wave detectors can now "autotune" their signals](https://www.aei.mpg.de/1445425/gravitational-wave-detectors-can-now-autotune-their-signals?c=26160)
- **March 2026** — [New catalog of LIGO-Virgo-KAGRA observations published](https://www.aei.mpg.de/1415736/new-catalog-of-ligo-virgo-kagra-observations-published?c=26160)
- **January 2026** — [Testing Einstein's theory of relativity with the clearest gravitational-wave signal yet](https://www.aei.mpg.de/1391414/testing-einstein-s-theory-of-relativity-with-the-clearest-gravitational-wave-signal-yet?c=26160)
- **October 2025** — [LIGO-Virgo-KAGRA observe unlike twin signals](https://www.aei.mpg.de/1317243/ligo-virgo-kagra-observe-unlike-twin-signals?c=26160)
- **October 2025** — [Are we ready for the next gravitational-wave observing runs?](https://www.aei.mpg.de/1318214/are-we-ready-for-the-next-gravitational-wave-observing-runs)
- **September 2025** — [Ten years of gravitational-wave astronomy — and the clearest signal yet](https://www.aei.mpg.de/1286736/ten-years-of-gravitational-wave-astronomy-and-the-clearest-signal-yet?c=26160)
- **July 2025** — [LIGO-Virgo-KAGRA detect most massive black hole merger to date](https://www.aei.mpg.de/1262522/ligo-virgo-kagra-detect-most-massive-black-hole-merger-to-date?c=26160)
- **April 2024** — [Mysterious object in the gap](https://www.aei.mpg.de/1138125/mysterious-object-in-the-gap?c=26160)
- **May 2023** - [Next generation waveform models for observing run O4](https://www.aei.mpg.de/1034138/new-waveform-models-for-o4?c=26149)
