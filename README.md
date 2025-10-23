# The Maximum Gravity Model for partial Tidal Disruption Events: Mass Loss, Peak Fallback Rate and Dependence on Stellar Type

## Summary of Contents

Following is a summary of the scripts, data and other supplementary material included in this data release, organized according in directories as described.

* `fallbackrate_data` : fallback rate data for 23 stars at organized by mass and age, as follows:
 
  $0.2 \leqslant M_\star/M_\odot \leqslant 0.5$: Simulations included for ZAMS (zero-age main-sequence) stage only.
  
  $0.6 \leqslant M_\star/M_\odot \leqslant 0.8$: Simulations included for ZAMS and 14Gyr star.
  
  $0.9 \leqslant M_\star/M_\odot \leqslant 5.0$:  Simulations included for ZAMS, MAMS (middle-age main-sequence), and TAMS (terminal-age main sequence).

  Each star directory contains ~22 subdirectories labeled `beta$i$`, where $i$ is the value of $\beta$, i.e., the impact parameter of the orbit ($\beta \equiv r_{\rm t}/r_{\rm p}$, where $r_{\rm t}$ is the tidal radius and $r_{\rm p}$ is the pericenter distance of the orbit).

* `figures` : Directory containing figures for all the stars (fallback rates, $(t_{\rm peak},\dot{M}_{\rm peak})$, error estimates and $\Delta M$ vs $\beta$).
