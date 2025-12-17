---
title: "Can a Single Proton Be Excited? And the Neutron Lifetime Puzzle"
date: 2025-04-13
permalink: /posts/2025/04/proton-excitations-and-neutron-puzzle/
published: false
tags:
  - particle physics
  - neutron lifetime
  - baryons
  - physics-stackexchange
  - blog
mathjax: true
---

> _"An electron in hydrogen can absorb light and jump to a higher energy level. Can the same happen to the protium nucleus (a lone proton)?"_

This question was posted on [Physics Stack Exchange](https://physics.stackexchange.com/q/805534), and I took it as an opportunity to revisit some basics from undergraduate particle physics—plus, I was introduced to a fascinating recent hypothesis regarding **excited neutron states**.

Before diving in, it's worth noting: **a free electron cannot absorb a single photon** in empty space without violating conservation of energy and momentum. It must be part of a bound system (like an atom) or interact with something else (like a nucleus or another photon) for photon absorption to occur.

While conventional particle physics tells us that proton and neutron resonances exist at hundreds of MeV above the ground state and decay within $$10^{-23}$$ seconds, the paper by Koch and Hummel (2024) suggests something more subtle: **low-lying, long-lived excited states of the free neutron** that might resolve the neutron lifetime discrepancy.

## What Does It Mean for a Proton to Be “Excited”?

The nucleus of protium (a single proton) lacks internal nuclear structure—there are no other nucleons for collective excitations. So from a nuclear physics perspective, protium has no excited nuclear states.

But the proton itself is a composite particle, made of three quarks (two up, one down) bound by gluons. These internal degrees of freedom can be excited, giving rise to **baryon resonances**.

There are two main families:
- The $$\Delta$$ baryons with isospin $$I = 3/2$$ and $$I_3 = \pm 3/2, \pm 1/2$$. For example, $$\Delta^+$$ and $$\Delta^0$$ have the same quark content as the proton and neutron, respectively, but belong to a different isospin multiplet. Thus, they are **not** true excited states of the proton or neutron. Instead, $$\Delta$$ particles can decay into a nucleon and a pion (which carries isospin 1).
- The $$N^*$$ resonances are the true excitations of the nucleon doublet ($$p$$ and $$n$$), with isospin $$I = 1/2$$ and $$I_3 = +1/2$$ for the proton, $$I_3 = -1/2$$ for the neutron.

These resonances — e.g., $$N(1440)$$, $$N(1520)$$ — decay rapidly, within $$10^{-23}$$ seconds, because they decay via the strong interaction. This timescale is much shorter than the timescale for atomic electrons to form stable orbitals ($$\sim 10^{-19}$$ seconds), so a hydrogen atom with an "excited" proton nucleus could not meaningfully exist.

You can read about these states in the [Particle Data Group booklet](https://pdg.lbl.gov/2023/download/db2022.pdf), or specifically the $$N$$ and $$\Delta$$ resonances [review](https://pdg.lbl.gov/2023/reviews/rpp2022-rev-n-delta-resonances.pdf).

## A New Twist: Excited Neutrons?

In their recent paper [arXiv:2403.00914](https://arxiv.org/abs/2403.00914), **Koch and Hummel** propose that **free neutrons**—such as those produced in nuclear reactors—may exist in slightly excited quantum states. These are **not** $$N^*$$ resonances, but low-energy ($$\sim$$meV to MeV) excitations with longer electromagnetic decay times.

### The idea in brief:
- These states have the same quark content ($$udd$$) as the neutron.
- They may decay electromagnetically into the ground state, with a characteristic timescale $$\tau_\gamma$$.
- Crucially, they may have **different beta decay rates** ($$\tau_\beta$$) than the neutron ground state, which decays via the familiar beta decay to a proton.
- This could explain why **beam neutrons** live ~9 seconds longer than **bottle neutrons**: the excited states are present in beam experiments and decay electromagnetically before being detected in bottle setups.

_(In the bottle method, free neutrons are trapped in an ultracold, magnetized chamber about the size of a bathtub, where they begin to decay into protons over time.)_

### What kind of states?

Their toy model uses spatially excited wavefunctions of the three quarks. Most of these states have **reduced overlap** with the weak interaction operator, resulting in suppressed beta decay rates. Three of the four modeled states have lifetimes 2–25 times longer than the neutron ground state.

These excited states are expected to decay electromagnetically (via dipole or quadrupole transitions), emitting soft photons and converting into ground-state neutrons.

### What can we do to test this?

Koch and Hummel suggest several experimental strategies:
- **Look for delayed gamma emissions** along neutron beamlines.
- **Vary the beam pipe length**: longer paths give excited states time to decay before reaching detectors.
- **Reanalyze gamma backgrounds** in past experiments, especially those not triggered by beta decays.
- **Search for early-time gamma signals** in bottle experiments, before excited states decay.

These are all testable and could lead to a resolution of the neutron lifetime puzzle if verified.

## Why This Matters

It is often assumed that the proton and neutron are fully understood—but ideas like this challenge that assumption. The possibility of **long-lived, low-energy excitations** of the free neutron is bold and potentially revolutionary. Whether the hypothesis holds or not, it opens a fascinating new frontier in precision experimental particle physics.

**References**  
Koch, B., & Hummel, F. (2024). *Exciting hint toward the solution of the neutron lifetime puzzle*.  
Phys. Rev. D 110, 073004.  
[arXiv:2403.00914](https://arxiv.org/abs/2403.00914) | [Journal version](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.073004)

Discussion thread: [Physics Stack Exchange](https://physics.stackexchange.com/q/805534)
