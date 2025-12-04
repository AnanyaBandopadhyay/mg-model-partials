![[DOI](https://zenodo.org/badge/1061540709.svg)](https://doi.org/10.5281/zenodo.17821880)

# The Maximum Gravity Model for partial Tidal Disruption Events -- Supplementary Material

**Ananya Bandopadhyay<sup>1</sup>, Eric R. Coughlin<sup>1</sup>, C. J. Nixon<sup>2</sup>**

**<sup>1</sup>Department of Physics, Syracuse University, Syracuse, NY 13244, USA**

**<sup>2</sup>School of Physics and Astronomy, Sir William Henry Bragg Building, Woodhouse Ln., University of Leeds, Leeds LS2 9JT, UK**

This repository is a companion data release. The preprint version of the paper is available on [arXiv](https://arxiv.org/abs/).

## License

![Creative Commons License](https://licensebuttons.net/l/by-sa/4.0/88x31.png)

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 United States License](https://creativecommons.org/licenses/by-sa/4.0/deed.en). 

## Abstract

A star entering the tidal sphere of a supermassive black hole (SMBH) can be partially stripped of mass, resulting in a partial tidal disruption event (TDE). Here we develop an analytical model for properties of these events, including the peak fallback rate, $\dot{M}\_{\rm peak}$, the time at which the peak occurs, $t_{\rm peak}$, and the amount of mass removed from the star, $\Delta M$, for any star and any pericenter distance associated with the stellar orbit about the black hole. We compare the model predictions to 1276 hydrodynamical simulations of partial TDEs of main-sequence stars by a $10^6 M_\odot$ SMBH. The model yields $t_{\rm peak}$ predictions that are in good agreement (to within tens of percent) with the numerical simulations for any stellar type. The agreement for $\dot{M}\_{\rm peak}$ is weaker due to the influence of self-gravity on the debris stream dynamics, which remains dynamically important for partial TDEs; the agreement for $\dot{M}\_{\rm peak}$ is, however, to within a factor of $\sim 2-3$ in the majority of cases considered, with larger differences for low-mass stars ($M_\star \lesssim 0.5 M_\odot$) on grazing orbits with small mass loss. We show that partial TDE lightcurves for disruptions caused by $\sim 10^6M_\odot$ SMBHs can span $\sim 20-100$ day peak timescales, whereas grazing encounters of high-mass stars with high-mass SMBHs can yield longer peak timescales ($t\gtrsim 1000$ days), associated with some observed transients. Our model provides a significant step toward an analytical prescription for TDE lightcurves and luminosity functions.

## Summary of Contents

Following is a summary of the scripts, data and other supplementary material included in this data release, organized according to directories as described.

* `fallbackrate_data` : fallback rate data for 23 stars at organized by mass and age, as follows:
 
  $0.2 \leqslant M_\star/M_\odot \leqslant 0.5$: Simulations included for ZAMS (zero-age main-sequence) stage only.
  
  $0.6 \leqslant M_\star/M_\odot \leqslant 0.8$: Simulations included for ZAMS and 14Gyr star.
  
  $0.9 \leqslant M_\star/M_\odot \leqslant 5.0$:  Simulations included for ZAMS, MAMS (middle-age main-sequence), and TAMS (terminal-age main sequence).

  Each star directory contains ~22 subdirectories labeled `beta$i$`, where $i$ is the value of $\beta$, i.e., the impact parameter of the orbit ($\beta \equiv r_{\rm t}/r_{\rm p}$, where $r_{\rm t}$ is the tidal radius and $r_{\rm p}$ is the pericenter distance of the orbit).

* `figures` : Directory containing figures for all the stars (fallback rates, $(t_{\rm peak},\dot{M}_{\rm peak})$, error estimates and $\Delta M$ vs $\beta$).

## Funding

A.B. acknowledges support from NASA through the FINESST program, grant 80NSSC24K1548. E.R.C. acknowledges support from NASA through the Astrophysics Theory Program, grant 80NSSC24K0897. C.J.N. acknowledges support from the Science and Technology Facilities Council (grant No. ST/Y000544/1) and from the Leverhulme Trust (grant No. RPG-2021-380).


