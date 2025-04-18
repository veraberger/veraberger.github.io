---
title: Research
layout: template
filename: research
--- 

# Research

I am primarily interested in how stars change on short timescales (seconds to minutes) and how those changes impact the surrounding environment.
Currently, I study stellar flares and their potential impact on the habitability of orbiting planets. 

## Stellar Flares
Stellar flares are energetic bursts of radiation caused by rapid realignments of magnetic fields on the surface of a star. These events release energy across the electromagnetic spectrum, from radio waves to X-rays, with significant implications for planetary atmospheres and surface conditions.

### Flares in the UV

Ultraviolet (UV) emission from stellar flares plays a crucial role in determining the **habitability** of exoplanetary systems. Flare UV emission may drive prebiotic chemistry, erode planetary atmospheres, or produce false biosignatures.

What began as an NSF-REU project at the University of Hawaii to search for stellar flares became the most **comprehensive statistical analysis of UV flares** with simultaneous observations in near- and far-ultraviolet. We showed for the first time that uniformly selected **stellar flares are far-ultraviolet luminous**, and widely-used assumptions for flare emission significantly underestimate the levels of FUV emission we observe ([Berger et al. 2024, MNRAS](https://academic.oup.com/mnras/article/532/4/4436/7725642)).

Our work was featured by [Space.com](https://www.space.com/red-dwarf-stars-uv-radation-harmful-to-life), the [American Geophysical Union](https://eos.org/articles/small-stars-produce-mighty-uv-flares), [University of Hawaii](https://www.hawaii.edu/news/2024/08/05/risks-to-planets-that-could-host-life/) and the [University of Cambridge](https://www.cam.ac.uk/research/news/astronomers-uncover-risks-to-planets-that-could-host-life).

I've also been experimenting with data sonification; here's a sonified light curve where brightness of the flare is mapped to pitch. This flare displays complex behaviour with multiple peaks in brightness.

<iframe width="560" height="315" src="https://www.youtube.com/embed/GS9zs6-GDws?si=R0ovySS7AW7R5hLk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


### Deep learning for flare detection
I'm developing a neural network to identify flares in 20-second cadence observations from the Transiting Exoplanet Survey Satellite (TESS). With this model, a user can input a target name and observation dates, and **the network will download and process all TESS data within the given timespan and output predictions** for flares.

<div style="display: flex; align-items: center;">
    <img src="flare_predictions.png" alt="Flare predictions" style="margin: auto; width: 600px;">
</div>

While the model is in the final stages of development, the project is available on [GitHub](https://github.com/veraberger/flarenet).

## Supernova Host Galaxies
Despite the importance of Type Ia supernovae (SNe Ia) as cosmological distance indicators, much remains unknown about the environments in which they happen. Past studies have shown that supernova properties relate to host galaxy properties, and that SN Ia host galaxies are similar to random field galaxies. Research on host properties has largely focused on more luminous galaxies, leaving low-luminosity hosts under-sampled. 

As an intern at Carnegie Observatories, I conducted a spectroscopic analysis of 45 dim host galaxies of nearby supernovae detected by the All-Sky Automated Survey for Supernovae (ASAS-SN). Using the emission lines from our dataset I measured metallicities and star formation rates, and compared host galaxy properties to SDSS field galaxies and previous SN Ia host samples. 

We find that the least massive hosts of Type Ia supernova may have higher metallicities than field galaxies of similar mass, and star formation activity representative of normal field galaxies ([Holoien, Berger et al. 2023, ApJ](https://iopscience.iop.org/article/10.3847/1538-4357/acce35)).

## Side Projects
### Density and Age Estimates for Messier 15
Globular clusters are collections of gravitationally-bound stars formed roughly all at once. Using photometry, we can construct color-magnitude diagrams alongside stellar evolution models to place constrains on the ages and distances of these clusters. 

I took archival data from the Hubble Space Telescope's Advanced Camera for Surveys and performed multi-object aperture photometry on Messier 15, a dense globular cluster containing over 100,000 stars. I used images taken in two filters: a wide V-band filter called F606W, and  a filter bordering the near-infrared, F814W. Using $YY^2$ Yale Yonsei stellar evolution isochrones we estimate a minimum cluster age of 11.5 Gyrs, $\pm$ 1 Gyr. We compute a distance of $47,863$ pc.

### Photometric Variability of $\delta$ Scuti Stars
$\delta$ Scuti is a class of variable stars that undergo radial oscillations. Like Cepheids, $\delta$ Scuti stars may be used as cosmological distance indicators, or "standard candles." Given photometric observational data, we can plot a star's light curve and glean information about how stellar properties like luminosity, temperature, and radius are correlated as the star pulsates. 

In this project, I observed a field of view containing a mystery star using the TMO 1-m telescope (FOV 6.3'x6.3').  I performed data reduction and photometry to isolate a star displaying varying brightness over time, calculated a period of variability of 102 minutes and observed temperature and luminosity trends consistent with those of $\delta$ Scuti stars.
