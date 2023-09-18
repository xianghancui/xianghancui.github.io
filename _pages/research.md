---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

----

## Fast Radio Burst

Fast radio bursts (FRBs) may be one of the most important and unique discoveries in the field of radio astronomy in the past decade or so. Its significance lies in the huge burst luminosity (isotropic), remote distances, and brief flashes. Its uniqueness lies in the fact that, to this day, we still do not know where they originate from and the potential inspiration they may provide for new physics. In such a process, the aspects that interest me are statistical research and the physical mechanisms involved.

### Statistical Analysis

In the statistical aspect, we attempt  to analyze the statistical characteristics of FRBs using statistical methods to uncover their population distribution. In this way, we may be able to provide some clues about the origin and mechanisms of FRBs. 

In the previous works, we analyzed both [repeating and non-repeating FRBs](https://ui.adsabs.harvard.edu/abs/2021MNRAS.500.3275C/abstract) based on the data available at that time (in mid-2020) and found that they exhibit different statistical distributions in terms of their intrinsic pulse widths and isotropic radio luminosities. During this process, we applied statistical methods to small samples for the first time, enhancing the comprehensiveness of our statistics. This led to an earlier perspective of the potential diversity of FRBs, suggesting that they might have multiple origins or mechanisms.

Later, we conducted a statistical analysis of the [isotropic luminosity distribution](https://ui.adsabs.harvard.edu/abs/2022Ap%26SS.367...66C/abstract) using the data of CHIME/FRB Catalog 1. To account for the influence of DM errors on distance more reasonably, we introduced different distributions and scales of DM-z conversion errors when estimating distances using the Macquart relation. We found that when the errors were less than 40%, the log-normal characteristics of the distribution were more pronounced compared to the power-law distribution. However, beyond this point, the log-normal characteristics gradually decreased. This result further indicated the crucial importance of an accurate DM-z relation in obtaining the intrinsic population of FRBs.

### Mechanism Model

The mechanism of FRBs is another significant question in this field. Currently, there are numerous models, such as propagation mechanism models and radiation mechanism models, proposed to explain FRBs. Here, we are particularly interested in how FRBs emit radiation. While there is still some disagreement regarding this issue like inside or outside the magnetosphere, coherent radiation is generally acknowledged as a key aspect of FRB emission. Therefore, we built our model with this perspective.

Our [compressed bunch model](https://ui.adsabs.harvard.edu/abs/2023arXiv230810258C/abstract) was constructed within the framework of coherent curvature radiation and magnetized neutron stars. In this kind of model, it is generally believed that coherent curvature radiation is produced by bunches moving along curved magnetic field lines, and the generation of these bunches is one of the fundamental issues in such models. Therefore, the core of our model focuses on how these bunches are formed before the emission of FRBs. Here, we proposed a new approach (different from two-stream instability) that outflowing particles undergo an energy loss dominated by inverse Compton scattering. This process leads to a compression effect in the particle flow (imagine a toll booth on a high-speed highway), which could potentially facilitate the formation of bunches.

<img src="https://xianghancui.github.io/images/model.png" alt="camp-lightning"/>

In our model, we have divided the entire FRB radiation into three parts: the trigger region, the outflow region, and the FRB emission region. The outflow part is where the compression effect, i.e., the formation of bunches, is more pronounced. This model provided a comprehensive physical picture of the FRB radiation process.

----

## Pulsar

Pulsars, which are believed to be rapidly rotating neutron stars, have been discovered for over half a century since 1976. Despite extensive research over the years, the population distribution of pulsars and the evolution of magnetic field and spin period still remain subjects of great interest.

### Statistical Analysis

In our statistical work, we analyzed the period and characteristic magnetic field distributions of  [young normal radio pulsars](https://ui.adsabs.harvard.edu/abs/2021MNRAS.508..279C/abstract). We then classified the data into two categories based on whether they contained supernova remnants (SNR): those with remnants and those without. We found that they have different statistical distributions, which may suggest that they have different birth processes.

Moreover, based on the spin-down age, we compared the cumulative number distribution of the two categories and found that they diverge around 10k to 15 years for different braking indices. This indicated that the lifetime boundary between the two types of SNRs is approximately 10k to 15k years. Subsequently, we also analyzed the progenitor star properties based on the initial mass function. These results further support the hypothesis of multiple origins for pulsars and provide quantitative statistical analysis to substantiate it.

### Evolution Model

The magnetic dipole radiation (MDR) model is widely discussed and applied to the evolution of pulsars. However, the MDR for pulsar evolution has its challenges. One of the most prominent issues is that the model predicts a braking index of 3, yet no pulsar has a precisely measured braking index of 3, and they all fall within a range between 1 and 3. This discrepancy between theory and observation is a topic of ongoing research and debate in the field of pulsar astronomy.

Our evolutionary model, which combined the [MDR and particle outflow wind](https://ui.adsabs.harvard.edu/abs/2022Univ....8..628Z/abstract), provided an analysis of this problem and offered precise analytical solutions to address it. By applying this model to the Crab pulsar, we have arrived at three conclusions: (1) the initial period of the Crab pulsar is approximately 18.3 ms; (2) secondly, its characteristic magnetic field (also called $P \dot P$ magnetic field) increases as it evolves when we assumed that the real magnetic doesn't change; (3) there is an upper limit to the characteristic age, which is around 10k years.

<img src="https://xianghancui.github.io/images/P-Pdot.png" alt="camp-lightning" style="zoom: 50%;" />

The most intriguing conclusions were the last two regarding the characteristic magnetic field and characteristic age. This implied that we cannot solely rely on the characteristic magnetic field to determine if a magnetar has an ultra-strong magnetic field, and additional evidence such as high-energy bursts and other indicators is needed for confirmation. Meanwhile, it further indicated that the characteristic age cannot represent the true age of the pulsar.
