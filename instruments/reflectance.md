---
layout: single
title: Reflectance Measurements of Various Black and White Materials
sidebar:
  nav: "side"
toc: true
rtt: true
---
## Introduction

We report on a catalog of various common (and uncommon) black and white materials used in the construction and/or baffling of optical systems and as screen material for calibration systems. Black materials are characterized via total and specular reflectance measurements. White materials are characterized for total reflectance and deviation from a Lambertian surface. Total reflectance is measured over a broad wavelength range (250 < λ< 2500 nm) that is applicable to ultraviolet, visible, and near-infrared instrumentation. Lambertian characterization and specular reflectance were measured using a helium-neon laser and photodiode over a range of angles.

## Instrumentation

### Total Reflectance
The U-4100 dual beam spectrophotometer uses two different lamps to cover a wide range of wavelengths. For the deep UV, the U-4100 uses a deuterium lamp and switches to a tungsten lamp for UV, visible, and near IR measurements. The layout of the U-4100 includes monochromators, beam splitters, mirrors, focusing lenses, and detectors which can be used to analyze liquid or solid samples. Specifically, we obtained percent reflectance values for the wavelength range of 250-2500 nm and used a 5 percent reflectance standard (SRS-05) obtained from Labsphere Inc. to calculate the absolute reflectance of our samples. Below we will give descriptions of our experimental setup as well as the procedure we followed for measuring the reflectance of our samples.

Below is the experimental setup of the Hitachi High-Tech U-4100 UV-Visible-NIR Spectrophotometer used at the MCF at Texas A&M. The reference and test sample are placed in the 6 o'clock and 3 o'clock positions of the integrating sphere respectively. The U-4100 and all its experimental parameters are controlled by the program UV Solutions through the computer in the MCF.  

<figure style="margin:auto;">
  <img src="/instruments/assets/reflectance/UV-Vis-NIR_IntegratingSphere.png" alt="Spectrophotometer" style="max-width: 70%">
</figure>

Procedure:  
1. Set up parameters using the UV Solutions menu. Most of our parameters are the same as in the MCF handout for the U-4100 (linked here), but a complete list of our parameters are here.  
2. Collect a baseline measurement. This measurement records the reflectance of a reference substance and uses this as a baseline value to give relative (ratio) measurements of our samples. In our case, the baseline measurement was taken with BaSO4 wafers (~100% reflectance) in both the reference and sample slots of the dual beam spectrophotometer.  
3. Record calibration measurement of SRS-05.  
4. Record measurement of test sample in the 3 o'clock position of the integrating sphere.  
5. Data analysis and computation of absolute reflectance values using the calibration and sample measurements.  

Data Analysis:
1. Using a spreadsheet, we compared the SRS-05 MCF reflectance values to the Labsphere provided values. Take the ratio of the two SRS-05 (MCF/Labsphere) values and divide each sample's MCF reflectance value by this ratio at the appropriate wavelengths.  
2. To see the reflectance profile, plot these new absolute reflectance values versus wavelength.  

### [MADLaSR](/instruments/madlasr/)
We have designed and built a device capable of measuring both the specular reflectivity of black materials, as well as the Lambertian reflectivity of white materials over their full range of incident and observed angles, respectively. The MADLaSR (Multi-Angle Detection of Lambertian and Specular Reflectivity) is a device designed for specular reflectivity testing in the range of 10° < θ < 170° and for Lambertian reflectivity testing in the range of 10° < θ < 85°. Here, we will describe the design and functionality of the MADLaSR.  
<figure>
  <a href="/instruments/assets/madlasr/madlasr1.jpg" target="_blank">
  <img src="/instruments/assets/madlasr/madlasr1.jpg" alt="Figure 1"></a>
  <figcaption>Figure 1: MADLaSR Setup in the Munnerlyn Astronomical Instrumentation Laboratory in Texas A&M University</figcaption>
</figure>

#### Specular Reflectance
When testing for specular reflectivity, the laser and the sensor are moved to different positions symmetrically with respect to the central axis as defined by their pivot rod. An example of this setup is shown in Figure 2. By positioning iris diaphragms in front of both the laser and sensor, the diffuse scattering of the laser beam is minimized to ensure that we are measuring solely the specular reflection.  
<figure>
  <a href="/instruments/assets/madlasr/madlasr2.jpg" target="_blank">
  <img src="/instruments/assets/madlasr/madlasr2.jpg" alt="Figure 2"></a>
  <figcaption>Figure 2: MADLaSR's Specular Reflectivity Testing</figcaption>
</figure>

#### Lambertian Reflectivity Testing  
When testing for Lambertian reflectivity, the laser must be positioned perpendicular to the surface of the material while the sensor is moved to different angles. This setup, as shown in Figure 3, is designed to test for constant apparent surface brightness regardless of the angle of observation.  
<figure><a href="/instruments/assets/madlasr/madlasr3.jpg" target="_blank">
  <img src="/instruments/assets/madlasr/madlasr3.jpg" alt="Figure 3"></a>
  <figcaption>Figure 3: MADLaSR Running Lambertian Reflectivity Testing</figcaption>
</figure>
Data Analysis:  
1. Running these test programs produces .csv data files, which contain the range of angles and the corresponding power readings. Each file contains the reference sample's data as well as that of a test sample.  
2. This data is then plotted and the reflectivity properties of our samples are easily compared.  


## Characterization of Black Materials  
[Click here](/instruments/samples/) to view materials and their respective plots.  
[Click here](/instruments/reflectance_plots/) to view all plots.  

## Characterization of White Materials

[Click here](/instruments/samples/) to view materials and their respective plots.  
[Click here](/instruments/reflectance_plots/#lambertian-characterization---white-materials) to view all plots.  

## Labeling of Samples 
The original labeling of the metal samples was done using a 3-letter ID system separated by periods. The first letter identifies the metal type (C: cast aluminum, A: 6061 aluminum, I: invar, S: stainless steel). The second letter signifies the initial metal treatment (R: raw, P: Polished, M: machined, B: Bead-Blasted). Finally, the last letter identifies the coating treatment of the sample (B: Black-Dye Anodization, H: Hardcoat Non-Dyed Anodization, N: Electroless Nickel Coating).  

Example:  
C.R.B : Cast Aluminum, Raw, Black-Dye Anodization  

Anodizing:  
Black Anodization: MIL-A-8625, Type II, Class 2, Black  
Hardcoat Anodization: MIL-A-8625, Type III, Class 1, Non-dyed  
Electroless Nickel: MIL-C-26074  

Polishing:  
Polished samples were prepared by sanding the faces of the samples in increasing grit sizes of 500, 1000, 1500, and 2000.  

Thick/Thin Invar: Thick invar refers to regular cast invar and thin invar refers to cold rolled sheet invar.  

Our 2018 SPIE papers expanded this naming scheme to include paints, fabric, tape, etc. in subsequent years as the variety of samples has grown we have now adopted simplified labeling where black samples (including previously tested samples) are given a letter and number code, B####, and white materials W####.  A cross reference will be made available.

Labsphere SRS-05-100 [(calibration certificate link)](/instruments/assets/reflectance/DC13C-0276.pdf) [(data points)](/instruments/assets/reflectance/SRS-05.txt)  

---

*To send or suggest samples for testing, please contact Dr. Luke Schmidt [lschmidt@physics.tamu.edu](mailto:lschmidt@physics.tamu.edu) Due to variable availability of resources, we cannot guarantee a testing turn around time. We are also unable to return any samples submitted for testing and will publish measurement results on our website. Samples should be no more than 50mm square and 10mm thick, minimum size is 25mm square or circular.*