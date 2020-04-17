---
layout: single
title: TCal
sidebar:
  nav: "side"
header:
  image: /instruments/assets/banners/tamu-astronomy.jpg
toc: true
rtt: true
---
## Introduction
The Traveling Calibration unit (TCal) is a mobile spectrophotometric calibration system that will be used to characterize the throughput as a function of wavelength of imaging systems at observatories around the world. TCal will work to augment and improve the science return of large scale surveys by placing telescope/instrument systems that plan to do survey followup on a common photometric baseline. This will be done by using a 2nm wide tunable source to measure the measured systems response function from 300nm to 1000nm. By characterizing the throughput of these astronomical imaging systems the systematic error introduced by combining measurements made with different instruments will be reduced.

## System Overview
The TCal system consists of a few main components- a tunable light source, a projection system, a monitor CCD and LABVIEW based control software. The tunable light source uses the EQ-99x a laser driven light source to provide broadband emission. Then an OBB monochromator is used to select the wavelength of light to be projected and feed the light into a fiber optic bundle. The light is then projected onto a flat field screen and measured by a calibrated monitor CCD as well as the system to be calibrated. This measurement made at many wavelengths give a relative measure of the instrumental transmission as a function of wavelength. 

<figure>
  <a href="/instruments/assets/tcal/190630_etsi_scan_smoothed.png" target="_blank"><img src="/instruments/assets/tcal/190630_etsi_scan_smoothed.png" alt="etsi scan"></a>
  <figcaption>Figure 1: An example scan of a prototype version of <a href="/instruments/etsi">ETSI</a> on the McDonald Observatory 0.9m telescope.</figcaption>
</figure>

<figure>
  <a href="/instruments/assets/tcal/schematic.png" target="_blank"><img src="/instruments/assets/tcal/schematic.png" alt="schematic"></a>
  <figcaption>Figure 2: Schematic showing the major components of TCal.</figcaption>
</figure>