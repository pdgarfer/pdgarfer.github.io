---
title: "Complex optomechanics"
excerpt: "<br/><img src='/images/OM_RC.png'>"
collection: portfolio
---

After many years exploring the role of disorder and imperfection in systems used in quantum photonics, I turned my attention to the field of optomechanics. The nanostructures used in photonics are sufficiently small to become highly sensitive to thermal fluctuations and mechanical motion at room temperature. Thermal energy naturally activates vibrations with frequencies ranging from hundreds of MHz to several GHz, creating a rich interplay between optical and mechanical degrees of freedom.

While phonons are often regarded as detrimental for quantum photonics because they induce decoherence and spectral broadening, my interest has focused on understanding and exploiting the interaction between telecom-wavelength photons and thermally activated mechanical motion in complex nanophotonic systems. In particular, I investigate how structural disorder, nonlinear dynamics, and dissipation shape the interaction between light and vibrations in optomechanical cavities and waveguides.

Fig. 1. Complex nonlinear optomechanics and reservoir computing  
<br/><img src='/images/OM_RC.png' alt="drawing" width="900"/>

## Nonlinear dynamics and phonon lasing in optomechanical systems

I have studied complex optomechanical systems in which GHz mechanical modes are thermally activated at room temperature, eliminating the need for external mechanical driving. In these systems, structural disorder mediates the interaction between THz optical fields and GHz vibrations, producing rich nonlinear dynamics that emerge from the interplay between optical, thermal, electronic, and mechanical degrees of freedom.

At high optical powers, silicon optomechanical cavities exhibit strong nonlinear behavior dominated by two-photon absorption (TPA), free-carrier dispersion (FCD), and thermo-optic (TO) effects. The competition between free-carrier-induced blueshifts and thermo-optic redshifts drives the cavity into self-pulsing regimes, where the intracavity field oscillates periodically under continuous-wave excitation. These self-sustained oscillations correspond to stable limit cycles in the phase space defined by carrier density, temperature, and mechanical displacement.

The nonlinear modulation of the intracavity field generates time-dependent radiation-pressure forces that coherently drive the mechanical resonator. This mechanism enables mechanical amplification and self-sustained phonon lasing, even in the presence of disorder-induced scattering and losses. Beyond conventional dynamical backaction, these systems exhibit hybrid nonlinear dynamics where optical nonlinearities, thermal relaxation, free-carrier dynamics, and mechanical motion become strongly intertwined across multiple timescales.

## Optomechanical reservoir computing and physical information processing

More recently, this research line has evolved toward physical information processing using nonlinear optomechanical dynamics. An optomechanical oscillator undergoes a Hopf bifurcation separating two regimes with very different computational properties: a stochastic Brownian-motion regime below threshold and a coherent self-sustained oscillation regime above threshold.

Above threshold, radiation pressure, free-carrier dynamics, and thermo-optic relaxation sustain a coherent optomechanical limit cycle that simultaneously provides nonlinearity, fading memory, and reproducible dynamics. By weakly perturbing this attractor with an input signal, the cavity itself can operate as a physical reservoir computer without requiring external feedback loops.

Using a single chip-integrated optomechanical cavity with time multiplexing and virtual nodes, we demonstrated nonlinear function reconstruction, short-term memory, prediction of chaotic Mackey–Glass time series, and spoken-digit classification. In contrast to many photonic reservoir architectures, the nonlinearity, memory, and dynamical timescale all emerge from the same physical interaction inside the cavity itself.

The intrinsic processing speed of the reservoir is determined by the mechanical resonance frequency. In the present devices, this corresponds to frequencies near 0.4 GHz and nanosecond-scale dynamics, while related optomechanical and nanomechanical systems provide a route toward multi-GHz and potentially sub-terahertz physical computing platforms.

### Related publication

**Computing with the complex nonlinear dynamics of an optomechanical oscillator**  
Shulamit Edelstein, Marcos Menéndez, Bingrui Lu, Babak Vosoughi Lahijani, Cefe López, Miguel C. Soriano, Søren Stobbe, Pedro David García  
[arXiv:2505.01792](https://arxiv.org/abs/2505.01792)

## Disorder as a resource in optomechanics

Any photonic or optomechanical nanostructure is affected by some degree of imperfection due to the unavoidable finite tolerance of the fabrication process. In this line of research, we investigate the role and limitations imposed by disorder in photon-phonon interactions, while also exploring how disorder itself can become a physical resource to enhance optomechanical coupling in complex systems.

Fig. 2. Shamrock optomechanical crystals  
<br/><img src='/images/Shamrock.png' alt="drawing" width="800"/>

We have explored Anderson-localized cavity optomechanics in a two-dimensional optomechanical platform based on suspended silicon photonic-crystal waveguides with slotted line defects. Inherent fabrication imperfections induce sufficient multiple scattering to produce Anderson localization of optical modes. The introduction of an air slot strongly enhances electromagnetic confinement and increases the coupling between light and in-plane mechanical motion.

The resulting tightly confined Anderson-localized modes can be driven into regimes of mechanical amplification and self-sustained phonon lasing through optomechanical backaction. These systems exhibit rich nonlinear dynamics arising from the coexistence of dynamical backaction, self-pulsing instabilities, thermo-optic nonlinearities, and carrier dynamics operating on different timescales.

We design photonic and phononic band structures to realize mechanical lasing up to 6.8 GHz resulting from strong confinement of the mechanical mode. The existence of these modes is confirmed through cavity optomechanics and Brillouin light scattering spectroscopy. While disorder in cavity optomechanics has often been regarded as detrimental, our work shows that disorder can play a decisive role in device functionality and also opens new perspectives for studying multiple scattering and Anderson localization of bosonic excitations coupled parametrically to mechanical motion.

## Related work

This research line has been extensively developed through two PhD theses I supervised:

**[Light-motion interaction in disordered nanostructures](https://ddd.uab.cat/pub/tesis/2021/hdl_10803_672001/gab1de1.pdf)**  
*Guillermo Arregui Bravo (2021)*

This thesis provides a comprehensive theoretical and experimental analysis of optomechanical interactions in disorder-induced cavities. It includes detailed studies of nonlinear dynamics arising from two-photon absorption, free-carrier dispersion, and thermo-optic effects in silicon cavities. The work demonstrates self-pulsing phenomena in Anderson-localized optical modes and shows how these limit cycles can drive mechanical oscillations through radiation pressure modulation. The thesis also presents the statistical enhancement of optomechanical coupling rates in Anderson-localized systems and demonstrates mechanical lasing up to 6.8 GHz in slotted photonic crystal waveguides.

**[Brillouin scattering in bosonic systems](https://ddd.uab.cat/pub/tesis/2023/hdl_10803_688308/oefp1de1.pdf)**  
*Omar Enrique Florez Peñaloza (2023)*

This thesis focuses on the design and experimental characterization of phononic crystals and waveguides using Brillouin light scattering spectroscopy. It demonstrates full hypersonic bandgaps with gap-to-midgap ratios reaching 64% in shamrock phononic crystals and provides direct experimental evidence of guided modes at GHz frequencies measured at room temperature. The work explores both trivial defect waveguides and topological waveguides based on quantum spin Hall and quantum valley Hall analogies, addressing the constraints imposed by elastic anisotropy and experimental accessibility.

I summarize many of the results of this research line in this [invited talk](https://www.youtube.com/watch?v=jx5lNSxwHSw).
