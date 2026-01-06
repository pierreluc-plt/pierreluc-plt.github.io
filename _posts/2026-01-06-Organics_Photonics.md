---
layout: distill
title: The Integration of Organic Semiconductors in Nonlinear Photonics
date: 2026-01-06 09:56:00-0400
description: The Integration of Organic Semiconductors in Nonlinear Photonics
tags: formatting bib
categories: sample-posts
giscus_comments: true
related_posts: false
published: false
authors:
  - name: Pierre-Luc Thériault
    affiliations:
      name: Engineering Physics Department, Polytechnique Montréal
---
*To be updated*
## The Integration of Organic Semiconductors in Nonlinear Photonics

The field of integrated photonics has reached a point where the "passive" performance of platforms like Silicon Nitride ($Si_3N_4$) is excellent, but "active" nonlinear functionalities remain a challenge. While Lithium Niobate ($LiNbO_3$) is the current industry standard, it is not without significant drawbacks, leading to increased interest in evaporated organic thin films.

### The Limitations of Lithium Niobate

Despite its dominance, $LiNbO_3$ presents several hurdles for scalable, next-generation photonics:

* **Fabrication Complexity:** $LiNbO_3$ is notoriously difficult to etch. While Thin-Film Lithium Niobate (TFLN) has made strides, achieving smooth sidewalls to minimize scattering loss remains a high-cost, specialized process.
* **Photorefractive Instability:** At high optical powers—common in nonlinear optics—$LiNbO_3$ suffers from the photorefractive effect, where laser-induced charge migration changes the refractive index, leading to drift and instability.
* **Integration Constraints:** It is difficult to grow $LiNbO_3$ directly on top of processed CMOS wafers, often requiring complex wafer-bonding techniques.

### Distinguishing the Mechanisms: EO vs. NLO

To understand the role of organics, we must distinguish between two physical mechanisms:

* **Electro-Optics (EO):** The change in refractive index in response to a DC or low-frequency RF electric field (The Pockels Effect).
* **All-Optical Nonlinear Processes:** The interaction of light with light via the material's susceptibility, such as **Second-Harmonic Generation (SHG)**.

While both require a non-centrosymmetric medium, all-optical processes are significantly more sensitive to the presence of metal.

### The Problem with Electrodes

In traditional organic photonics, molecules are aligned using **electric-field poling**. While this works for EO modulators, it creates a major conflict for all-optical $\chi^{(2)}$ devices:

1.  **Optical Absorption:** Metal electrodes used for poling must be placed very close to the optical mode to achieve high field strengths. For all-optical processes like SHG, these electrodes introduce significant plasmonic absorption and scattering losses, which can severely degrade the efficiency of the frequency conversion.
2.  **Field Uniformity:** All-optical processes require phase-matching over long propagation lengths. Maintaining a perfectly uniform poled state across a long waveguide is difficult with discrete electrodes, leading to local variations in the nonlinear coefficient.


### Moving Beyond Poling: The Spontaneous Approach

Our recent work, **"Spontaneously-Oriented Evaporated Organic Semiconductor Thin Films for Second-Order Nonlinear Photonics"** ([*ACS Photonics* 2024](https://pubs.acs.org/doi/10.1021/acsphotonics.4c01190)), addresses these challenges by utilizing molecules that naturally align during vacuum deposition. 

By eliminating the need for poling, we also eliminate the need for permanent electrodes. This allows for:
* **Lower Loss:** No metal-induced absorption near the nonlinear medium.
* **Simplified Fabrication:** The film is "active" as soon as it is deposited, allowing for easier hybrid integration with $Si_3N_4$ waveguides.

However, the challenge shifts from electrical engineering to **molecular engineering**: designing molecules that not only have high hyperpolarizability but also the specific shape and dipole moment required to sustain orientation during the growth process—a focus of our latest [preprint on arXiv](https://arxiv.org/abs/2511.13682).

### Conclusion: Toward Scalable Quantum and Classic Light Sources

By overcoming the traditional trade-offs of organic materials, spontaneously oriented films pave the way for a new class of photonic devices. From efficient on-chip frequency doubling to the generation of entangled photon pairs via spontaneous parametric down-conversion (SPDC), these materials offer a path toward high-performance nonlinear circuits that are both CMOS-compatible and scalable. As we refine the molecular design rules for these systems, the goal is to transition from discrete components to fully integrated nonlinear systems-on-a-chip.
