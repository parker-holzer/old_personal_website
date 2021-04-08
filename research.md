---
layout: default
---

## [About Me](./)  &nbsp; &nbsp;  CV   &nbsp; &nbsp; [Consulting](./consulting.html)

# Research Projects

## Astrostatistics

* **A Hermite-Gaussian Based Radial Velocity Estimation Method**: The radial velocity method is one of the techniques used to detect the signal of a planet orbiting a distant star by analyzing the light from that star. This project uses the Hermite-Gaussian functions to mathematically formulate the radial velocity method as weighted linear regression. This is shown through both simulation studies and analysis of real data to outperform the traditional cross-correlation function approach. [Paper](https://arxiv.org/abs/2005.14083) &nbsp; &nbsp; [R package](https://CRAN.R-project.org/package=rvmethod) &nbsp; &nbsp; [Python source code](https://github.com/parkerholzer/hgrv_method) ![](./assets/img/HGRV_51Peg_rvs.png)
* **A Stellar Activity F-statistic for Exoplanet Surveys (SAFE)**: In the radial velocity method for finding exoplanets, stellar activity in the atmosphere of the host star can distort the signal imposed by the orbiting planet. This project introduces a new statistic designed to detect the presence of such stellar activity. We demonstrate that this new F-statistic behaves as expected when no stellar activity is present, and has higher statistical power than many traditional stellar activity indicators designed for the same purpose. Paper &nbsp; &nbsp; R package &nbsp; &nbsp; [Python source code](https://github.com/parkerholzer/safe_statistic) ![](./assets/img/StellarActivity_Comp.png)

## Human Placenta

* **Trophoblasst Inclusions in the Human Placenta: Identification, Characterization, Quantification, and Interrelations of Subtypes**: Trophoblast inclusions are a feature that can occur on the human placenta during pregnancy. In this project I used statistical bootstrapping to demonstrate that the four subtypes of these inclusions have statistcally significant Spearman correlations with each other. [Paper](https://www.sciencedirect.com/science/article/pii/S0143400420304082) ![](./assets/img/TI_venndiag.png)
* **Causes of Unexplained Pregnancy Loss**: 
* **Genetics, Not the Uterine Environment, Drive the Formation of Trophoblast Inclusions: Insights From a Twin Study**: In this study I derived and implemented a generalized likelihood ratio test for testing whether two samples of exponentially-distributed random variables have the same mean. Applying this to a study of monozygotic and dizygotic twins, we find that the trophoblast inclusion difference is greater for dizygotic twins than for monozygotic twins. Paper (see Supplementary File)

## Other Projects

* **Bountiful Real Estate Home Value Modeling**: Here I use webscraping to obtain data on recently (as of March 2021) sold houses in Bountiful, Utah. Using multiple regression I demonstrate that after acconting for effects of lot size, year built, living area, and bathroom count, the value *decreases* by about $15,000 for each additional bedroom. Furthermore, I demonstrate that the value depends more quadratically than linearly on the living area. [R source code] ![](./assets/img/bed_avp.png)
