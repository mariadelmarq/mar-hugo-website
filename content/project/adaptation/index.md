---
title: "Adaptation and recurrent networks"
subtitle: "My PhD project"
excerpt: "For my PhD I studied how brain cells process visual information. More specifically, how the way our brain cells are densely connected to each other can generate perceptual changes known as adaptation."
date: 2015-01-31
author: "Maria del Mar Quiroga"
draft: false
tags:
  - hugo-site
categories:
  - Neuroscience
  - Visual system
  - Simulations
  - Psychophysics
layout: single
links:
- icon: open-access
  icon_pack: ai 
  name: model
  url: https://doi.org/10.1016/j.celrep.2016.08.089
- icon: open-access
  icon_pack: ai
  name: behaviour
  url: https://doi.org/10.3389/fnsys.2019.00067
---

I did my PhD at the [Center for Molecular and Behavioral Neuroscience](https://cmbn.rutgers.edu/) of Rutgers University Newark, in [Prof. Bart Krekelberg's lab](https://www.vision.rutgers.edu/).

### Recurrent network model

The first part of my PhD consisted in implementing a well studied model of primary visual cortex and testing what happened if I "presented" the model with two oriented gratings in very quick succession, like so:

![Gratings](featured-gratings.gif)

It turned out that the model exhibited a behavioral phenomenon known as adaptation: when the response to the second stimulus is contaminated by the response to the first, resulting in a different perceived orientation. Historically this was always attributed to plasticity, or changes within the synaptic weights, but my model displayed the same effect with no changes to weights, only as a consequence of the recurrent connections introducing a time lag to the response. This work got published in [Cell Reports](https://doi.org/10.1016/j.celrep.2016.08.089), and I wrote a [plain language explanation of the results](https://www.cibf.edu.au/plasticity-is-not-the-only-way-the-brain-adapts) as well.

### Effects on behaviour

I then tested the mathematical model in the real world using psychophysics tests, such as showing people images in quick succession and asking what they see. I found that the perceptual effects of showing these two oriented gratings in close succession, and for a short period of time, is consistent with the model predictions, further validating the idea! These results were published in [Frontiers in Systems Neuroscience](https://www.frontiersin.org/articles/10.3389/fnsys.2019.00067/full).
