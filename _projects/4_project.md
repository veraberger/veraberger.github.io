---
layout: page
title: ML for flare finding
description: 
img: assets/img/flare_predictions.png
importance: 4
category: work
---

I'm developing a neural network to identify stellar flares in 20-second cadence observations from the Transiting Exoplanet Survey Satellite (TESS) in collaboration with the TESS team at NASA Goddard. With this model, a user can input a target name and observation dates, and **the network will download and process all TESS data within the given timespan and output predictions** for flares. 

<div style="display: flex; align-items: center;">
    <img src="assets/img/flare_predictions.png" alt="Flare predictions" style="margin: auto; width: 600px;">
</div>

While the model is in the final stages of development, the project is available on [GitHub](https://github.com/veraberger/flarenet).
