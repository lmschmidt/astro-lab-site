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
The Traveling Calibration unit (TCal) is a mobile spectrophotometric calibration system that will be used to characterize the throughput as a function of wavelength of imaging systems at observatories around the world. TCal will work to augment and improve the science return of large scale surveys by calibrating telescope/instrument systems that plan to do a significant amount of survey followup and place them on a common photometric baseline. This will be done by using a tunable light source, and calibrated detector to measure a systems relative response as a function of wavelengh from 300nm to 1000nm. By characterizing the throughput of these astronomical imaging systems the systematic error introduced when combining measurements made with different telescopes/systems will be reduced.

## System Overview
The TCal system consists of a few main components- a tunable light source, a projection system, a monitor CCD and LABVIEW based control software. The components and opreration are described in more detail below, but briefly monochomatic light is projected onto a screen and observed by a lab calibrated monitor ccd, as well as the instrument to be calibrated. Then the ratio of these measurements can be used to derive the relative throughput of an instrument as a funciton of wavelength. A schematic of the system is shown in Figure 1. 

<figure>
  <a href="/instruments/assets/tcal/schematic.png" target="_blank"><img src="/instruments/assets/tcal/schematic.png" alt="schematic"></a>
  <figcaption>Figure 1: Schematic showing the major components of TCal</figcaption>
</figure>

## Tunable Light Source
To create the tunable light source we start by generating broadband light using an EQ-99x laser driven light source manufactured by Energetiq. This source provides strong emission from 170nm to 1700nm as shown in the Figure 2 below which entirely encompases the spectral range we plan to calibrate. This light is fed through a F108w filter wheel that can be controlled by our software, and contains short-pass and long-pass filters used to prevent out of band light in the output of the monochromator (eg. order-blocker filters). Finally the light is injected into an f/4 Czerny-Turner type monochromator that is used to select a ~2 nm bandpass to project.

<figure>
  <a href="/instruments/assets/tcal/EQ-99X_sprad.png" target="_blank"><img src="/instruments/assets/tcal/EQ-99X_sprad.png" alt="EQ-99x"></a>
  <figcaption>Figure 2: The spectral energy distribution of the EQ-99x LDLS.</figcaption>
</figure>

## Projection
We place a custom fiber bundle at the ouput of the monochromator. One fiber, from the bundle of 10, illuminates a monitoring spectrometer that gives us real time information on the output bandpass. The rest of the fibers are used to illuminate the flat field screen. This is done by placing an Engeneered Diffuser (EDC) between the fiber and screen. The material for the flat field screen is chosen to be highly reflective and lambertian over the spectral range we are calibrating. We use a nylon-spandex mix from strechyscreens.com for more information check out our white and black materials testing [here](/instruments/reflectance/).

## Monitor CCD
A SBIG 8300M CCD is used as the monitoring detector. This CCD has been calibrated using a NIST calibrated photodiode, and works better than the photodiode in the low signal to noise regime. 

<figure>
  <a href="/instruments/assets/tcal/tcal_lab.jpg" target="_blank"><img src="/instruments/assets/tcal/tcal_lab.jpg" alt="tcal_lab"></a>
  <figcaption>Figure 3: Image of TCal in the lab.</figcaption>
</figure>

## Software
The Labview scan software and data recduction notebooks as well as a list of the other required software and drivers can be found at [https://github.com/psferguson/TCal](https://github.com/psferguson/TCal)

## ETSI Scan
In the summer of 2019 TCal was taken along with ETSI to the 0.9M telescope at McDonald Observatory. As part of the testing of ETSI we scanned the mounted system using TCal. The results of this scan are shown below in Figure 4 as a blue line, we were able to make a measurement of the relative tranmission of the system with ~1 % accuracy. The dashed black line shows the predicted transmison calculated from lab measurements of an Alluxa Quad band filter, 435 nm long pass filter, and STF 8300M CCD quantum efficency curve.

<figure>
  <a href="/instruments/assets/tcal/etsi_scan_summer_2019.png" target="_blank"><img src="/instruments/assets/tcal/etsi_scan_summer_2019.png" alt="etsiscan"></a>
  <figcaption>Figure 4: An example scan of a prototype version of ETSI on the McDonald Observatory 0.9m telescope.</figcaption>
</figure>

# Additional Resources

For more information check out our [2018 SPIE paper](/publications/assets/2018-SPIE-10702-119-TCal_paper_1.pdf) or [poster](/publications/assets/2018-SPIE-10702-119-TCal_poster.pdf). The software used for tcal can be found on the TCal github repo [link](https://github.com/psferguson/TCal) 