---
permalink: /projects/
title: Research projects
sidebar:
  title: " "
  nav: sidebar-projects

excerpt: ""
header:
  overlay_image: /assets/images/teaser.jpeg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background

---

### Mass determination of protoplanetary disks from dust evolution

The mass of protoplanetary disks is arguably one of their most important quantities shaping their evolution toward planetary systems, but it remains a challenge to determine this quantity. Using the high spatial resolution now available on telescopes such as the Atacama Large Millimeter/submillimeter Array (ALMA), recent studies derived a relation between the disk surface density and the location of the "dust lines". This is a new concept in the field, linking the disk size at different continuum wavelengths with the radial distribution of grain populations of different sizes.

We use dust evolution modes to test the dependence of the dust line location on disk gas mass, and we calibrate the analytic relation between the dust line location and the disk mass using a population of synthetic disks. We find that radial pressure bumps can alter the location of the dust line by up to ~10 au, while its location is mainly determined by the disk mass. In particular, we tested the reliability of the method for disks showing radial substructures, as recent high-resolution observations revealed. Therefore, we used these models to calibrate the relation between the dust grain drift timescale and the disk gas mass. We investigated under which condition the dust line location is a good mass estimator and tested how different stellar and disk properties (disk mass, stellar mass, disk age, and dust-to-gas ratio) affect the dust line properties. Finally, we apply this method to observed disks such as TW Hya and AS 209, which have been observed at high angular resolution with ALMA and show pronounced disk structures.

Our models show that the determination of the dust line location is a promising approach to the mass estimate of protoplanetay disks, but the exact relation between the dust line location and disk mass depends on the structure of the particular disk. We calibrated the relation for disks without evidence of radial structures, while for more complex structures we ran a simple dust evolution model.

<figure class="half">
    <a href="/assets/images/TWHya_page-0001.jpg"><img src="/assets/images/TWHya_page-0001.jpg"></a>
    <a href="/assets/images/heat_value_M_g_med_page-0001.jpg"><img src="/assets/images/heat_value_M_g_med_page-0001.jpg"></a>
    <figcaption>(left) Comparison of the dust continuum emission at 0.87 mm as predicted by our model (blue solid line) to the observational data (orange
solid line) from Andrews et al. (2016). The blue dotted line shows the model result without accounting for radial structures, highlighting their importance for this mass estimate. (right) Difference between the Powell (2017, 2019) analytical mass estimate from the dust line location (white slashed line) and our estimate based on dust evolution models (red line) for a large population of syntetic disks. The analytical relation sistematically overestimates the disk mass by a constant factor.</figcaption>
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

### A semiempirical approach to low-energy cosmic ray propagation in the diffuse interstellar medium

We investigate the ionization of the diffuse interstellar medium by cosmic rays by modeling their propagation along the
wandering magnetic fields using a Monte Carlo method. We explore how particle trapping and second-order Fermi processes affect
the ionization of the medium.

We study how low-energy comic rays propagate in turbulent, translucent molecular clouds, and how they regulate the ionization
and both lose and gain energy from the medium.

As a test case, we used high spatial resolution (0.03 pc) CO maps of a well-studied high latitude translucent cloud, MBM 3,
to model turbulence. The propagation problem is solved with a modified Monte Carlo procedure that includes trapping, energization,
and ionization losses.

In the homogeneous medium, trapping and re-energization do not produce a significant effect. In the nonuniform medium,
particles can be trapped for a long time inside the cloud. This modifies the cosmic ray distribution due to stochastic acceleration at
the highest energies (∼ 100 MeV). At lower energies, the re-energization is too weak to produce an appreciable effect. The change in
the energy distribution does not significantly affect the ionization losses, so ionization changes are due to trapping effects.

Our Monte Carlo approach to cosmic ray propagation is an alternative method for solving the transport equation. This
approach can be benchmarked to gas observations of molecular clouds. Using this approach, we demonstrate that stochastic Fermi
acceleration and particle trapping occurs in inhomogeneous clouds, significantly enhancing their ionization.
