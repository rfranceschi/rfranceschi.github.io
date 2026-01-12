---
author_profile: true
permalink: /projects/
title: Projects
sidebar:
  title: " "
  nav: sidebar-projects

excerpt: ""
header:
  overlay_image: /assets/images/teaser_projects.jpeg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background

---

### Modeling Cosmic Ray Propagation with Data-Driven Simulations

I explored how low-energy cosmic rays travel through turbulent, inhomogeneous molecular clouds. Using high-resolution observational data and Monte Carlo simulations, I analyzed how particles gain and lose energy, get trapped, and contribute to ionization in the interstellar medium.

The work combined computational modeling, statistical analysis, and the handling of complex datasets to uncover subtle patterns in particle behavior. By comparing simulations with observations, I was able to test and refine models of cosmic ray propagation in realistic, non-uniform environments.

This project highlights how advanced data techniques and modeling can be applied to study complex, stochastic systems, revealing insights that are not immediately apparent from raw data alone.

<figure>
    <a href="/assets/images/CR_uniform_medium.png">
        <img src="/assets/images/CR_uniform_medium.png">
    </a>
    <figcaption>
        Example of simulated random-walk particle trajectories in the medium.
    </figcaption>
</figure>

### Mass determination of protoplanetary disks from dust evolution

Determining the mass of protoplanetary disks remains one of the key challenges in understanding how planetary systems form. Using high-resolution ALMA observations, I modeled the evolution of dust grains within disks to explore how their radial distribution—the “dust lines”—relates to the underlying disk mass.

The approach combines synthetic populations of disks with numerical simulations of dust evolution, accounting for radial substructures, pressure bumps, and variations in stellar and disk properties. By comparing the models with well-studied systems such as TW Hya and AS 209, the work highlights how disk structures influence measurable properties and allows for refined mass estimates based on dust dynamics.

<figure>
    <a href="/assets/images/heat_value_M_g_med_page-0001.jpg"><img src="/assets/images/heat_value_M_g_med_page-0001.jpg"></a>
    <figcaption> Comparison between the Powell (2017, 2019) analytical mass estimates from dust line locations (white slashed line) and our estimates based on dust evolution models (red line) across a large population of synthetic disks. The analytical method consistently overestimates disk masses by a roughly constant factor.</figcaption>
</figure>

### Constraining the turbulence and the dust disk in IM Lup: onset of planetesimal formation

Observations of protoplanetary disks provide information on planet formation and the reasons for the diversity of planetary systems. The key to understanding planet formation is the study of dust evolution from small grains to pebbles. Smaller grains ($$ \sim 1 \;\mu m $$) are well coupled to the gas dynamics, and their distribution is significantly extended above the disk midplane. Larger grains settle much faster and are efficiently formed only in the midplane. By combining near-infrared polarized light and millimeter observations, it is possible to constrain the spatial distribution of both the small and large grains.

We aim to construct detailed models of the size distribution and vertical/radial structure of the dust particles in protoplanetary disks based on observational data. In particular, we are interested in recovering the dust distribution in the IM Lup protoplanetary disk.

We create a physical model for the dust distribution of protoplanetary disks. We then simulate the radiative transfer of the millimeter continumm and the near-infrared polarized radiation. Using a Markov chain Monte Carlo method, we compare the derived images to the observations available for the IM Lup disk to constrain the best physical model for IM Lup and to recover the vertical grain size distribution.

The millimeter and near-infrared emission tightly constrain the dust mass and grain size distribution of our model. We find size segregation in the dust distribution, with millimeter-sized grains in the disk midplane. These grains are efficiently formed in the disk, possibly by sedimentation-driven coagulation, in accord with the short settling timescales predicted by our model. This also suggests a high dust-to-gas ratio at smaller radii in the midplane, possibly triggering streaming instabilities and planetesimal formation in the inner disk. We obtain a turbulent $$ \alpha $$ parameter of $$ 3 \times 10^{-3} $$.

<figure class="half">
    <a href="/assets/images/IMLup_images_comparison.png"><img src="/assets/images/IMLup_images_comparison.png"></a>
    <a href="/assets/images/IMLup_corner.png"><img src="/assets/images/IMLup_corner.png"></a>
    <figcaption>(left) Comparison between the best-fit model 1.25 mm continuum and 1.65 μm polarized emission, and the ALMA and SPHERE data. (right) Posterior probability distribution of the fit parameter. </figcaption>
</figure>
