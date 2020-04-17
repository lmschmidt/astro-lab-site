---
layout: single
title: ETSI
sidebar:
  nav: "side"
header:
  image: /instruments/assets/banners/tamu-astronomy.jpg
toc: true
rtt: true
---
## Introduction
Texas A&amp;M is currently developing a new type of instrument designed specifically for taking
transmission spectra of transiting exoplanets. The Exoplanet Transmission Spectroscopy Imager (ETSI)
instrument uses a prism and multiband filter to simultaneously image 15 bandpasses from 430-975nm
during exoplanet transits (a full list of ETSI parameters is given in Table 1).

#### Table 1: ETSI Instrument Parameters

|ETSI Parameter|Value|
|------|------|
|Wavelength Coverage|430-975 nm|
|Resolution|&lambda;/&Delta;&lambda; = 20|
|Number of Spectral Bands|15|
|Field of View|7.5' x 7.5'|
|Plate Scale|0.22"/px|
|Photometric Accuracy (1&sigma;, 20min Vstar = 7.5|250ppm*|

#### *Based on prototype on-sky testing

ETSI makes use of a novel instrument technique, called SIMPSS (single image multi-band photometry
with slitless spectroscopy), to collect spectral information during exoplanet transits at low resolutions (R
= λ/Δλ ≈ 20). The instrument can do this by using a novel picket fence multi-band interference filter (ETSI
will have 7 or 8 bands per detector, but up to 25 bands across the visible is possible, see example 25-band filter in Figure 1) followed by a prism to separate the all spectral bands.
<figure>
  <a href="/instruments/assets/etsi/Figure1_blockDiagram.jpg" target="_blank"><img src="/instruments/assets/etsi/Figure1_blockDiagram.jpg" alt="Block Diagram"></a>
  <figcaption>Figure 1: Layout of Single Image, Multi-band Photometry with Slitless Spectroscopy (SIMPSS) Instrument.</figcaption>
</figure>
A detector then images the dispersed color bands such that there are up to 8 images of each star in the field of view. A second detector and prism set can be used to image the bands that are reflected (rather than transmitted) by
the multi-band interference filter allowing for up to 15 distinct spectral measurements of the
exoplanet&#39;s atmosphere in the visible. The layout of a SIMPSS instrument is shown in Figure 1 including
an example on-sky image of HD189733 taken with our prototype SIMPSS instrument which uses a
commercially available 5-band Alluxa filter. The optical layout of ETSI is shown in Figure 2.
<figure>
  <a href="/instruments/assets/etsi/Figure2_OpticalLayout.jpg" target="_blank"><img src="/instruments/assets/etsi/Figure2_OpticalLayout.jpg" alt="Optical Layout"></a>
  <figcaption>Figure 2: ETSI optical layout.</figcaption>
</figure>

## Preliminary Results
A prototype of the ETSI instrument was assembled using all COTS parts and tested on-sky at the
McDonald 0.9m in July 2019. The prototype instrument successfully measured the color during a WASP-
3b transit at the σ = 340ppm level (WASP-3 V mag = 10.6). The results from that measurement are shown
in Figure 3.
<figure>
  <a href="/instruments/assets/etsi/Figure3_OnSkyData.jpg" target="_blank"><img src="/instruments/assets/etsi/Figure3_OnSkyData.jpg" alt="On Sky Data"></a>
  <figcaption>Figure 3: Measurement of two colors of WASP-3b during transit with a prototype of the ETSI instrument on the McDonald 0.9 mtelescope in July of 2019.  An on-sky accuracy of 340ppm with 122 mintues of transit data on Wasp-3 (V = 10.6) at &lambda;=510 nm (FWHM = 16nm).</figcaption>
</figure>

## Current Status
ETSI is currently in the final design phase. Over the next year ETSI will be assembled at Texas A&amp;M and
begin commissioning on a 2 meter telescope. We estimate that during a two year survey, ETSI will
collect transmission spectra from approximately 100 exoplanets doubling the number of exoplanets
with measured transmission spectra. Figure 4 illustrates simulated exoplanet spectra of T = 600K and T =
1000K “Jupiters” with the ETSI bands overlaid. As is shown in this figure, ETSI is capable of detecting up
to six atmospheric features (Na, K, water, methane, TiO and Rayleigh scattering) and has bands tuned
specifically to maximize sensitivity to these features.
<figure>
  <a href="/instruments/assets/etsi/Figure4_SimExoplanetSpectra.jpg" target="_blank"><img src="/instruments/assets/etsi/Figure4_SimExoplanetSpectra.jpg" alt="Simulated Spectra"></a>
  <figcaption>Figure 4: Simulated spectra of T=600K (left) and 1000K (right) Jupiters with ETSI spectral bands overlaid. Gray bands are transmitted and red bands are reflected by the multi-band filter.  Plots illustrate that the 15 tuned ETSI spectral bands shoudl be sensitive to six atmospheric features.</figcaption>
</figure>
The ETSI project is funded by the NSF MRI grant no. 1920312.