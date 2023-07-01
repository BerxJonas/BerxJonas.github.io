---
layout: archive
title: "Hierarchical deposition"
permalink: /research/deposition
author_profile: true
---

<i>Collaborators: [Joseph Indekeu](https://fys.kuleuven.be/itf/groups/joi) (KU Leuven, Belgium)</i>

## Hierarchical random deposition

The hierarchical random deposition model (HRDM) is a model used to examine the process of depositing particles or digging holes on a line segment. In this model, the particles are deposited in a specific order based on their size, with the larger ones being deposited first. The distribution of particles follows a hyperbolic pattern, and the number of particles of a given size follows a scaling relationship \[1\].

Traditionally, general deposition models (e.g., random solid-on-solid, ballistic deposition, etc.) assume that all particles are identical in every aspect and that deposition occurs sequentially. The HRDM deviates from the assumptions of these models by considering synchronous deposition. This means that particles of the same size are all deposited simultaneously in "generations." This synchronous deposition is governed by a power law based on the size of the particles. The HDM is particularly useful for studying systems with power-law particle distributions, as observed in, e.g., pyroclastic clouds originating from volcanic eruptions, asteroid fragmentation, and laboratory experiments involving multifragmentation.

The number of particles of linear size $s$ is denoted by $N(s)$ and follows a scaling relationship $N(s) = \lambda^{-1} N(s/\lambda)$, where the number of particles is proportional to the inverse impact cross-section. The resulting landscape exhibits a logarithmic fractal law for its surface or length. Initially, the unit interval is divided into subsets of length $1/\lambda$. Each subset is either populated with a particle "hill" with probability $P$ or a "hole" with probability $Q$, which reduces the height by a factor $\lambda$. The third option is to do nothing with probability $1 - S$. This process can be continued <i>ad infinitum</i>.

## Visibility networks

### References:

\[1\] Jonas Berx, Evi Bervoets, Claudiu V. Giuraniuc and Joseph O. Indekeu, &quot;Coastlines and percolation in a model for hierarchical random deposition&quot;, <i>Physica A</i> <b>574</b>, 125998 (2021) [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/regular/file-pdf.svg" width="20" height="20">](http://berxjonas.github.io/files/pdf/Coastlines.pdf) [<img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/solid/link.svg" width="20" height="20">](https://doi.org/10.1016/j.physa.2021.125998)
