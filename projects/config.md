---
layout: project
title: "ConFiG: Contextual Fibre Growth"
short_title: ConFiG
github_url: rcallagh.github.io
thumbnail: config.png
summary: ConFiG enables us to generate more realistic synthetic white matter tissues than ever
related_links:
    - title: ConFiG Overview
      link: _posts/2020-06-22-config.md
      internal: true
    - title: "Callaghan et al. 2020, NeuroImage"
      link: https://doi.org/10.1016/j.neuroimage.2020.117107
gallery: config_phantoms
---
ConFiG is a new numerical phantom generator capable of creating realstic synthetic white matter tissues for diffusion MRI simulation.
{% include vimeoPlayer.html id=402472645 %}

ConFiG can achieve the state-of-the-art packing density in complex WM phantoms including up to three crossing bundles of fibres, outperforming the previous state-of-the-art, MEDUSA.  
{% include figure.html path="/assets/img/project/config/improvements.png" caption="" %}

Not only can we generate high density phantoms, but ConFiG phantoms also capture microstructural features found in real axons including fine details like bends and bulges
{% include figure.html path="/assets/img/project/config/fibre_examples.png" caption="" %}
Moreover, ConFiG captures complex fibre cross-sections that we see in real axons, including axons being deformed around one another and naturally occurring pockets of space between axons
{% include figure.html path="/assets/img/project/config/virthist.png" caption="" %}

This microstructural realism carries over to the simulated diffusion MRI signal. We show that the simulated signal from ConFiG phantoms made to represent WM regions matches real signal well
{% include figure.html path="/assets/img/project/config/signal.png" caption="" %}

We hope to make ConFiG a useful tool for the wider community to validate and develop new microstructure imaging techniques. We’re working on tidying up the code for release – check back here for updates 
