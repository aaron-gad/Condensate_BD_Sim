# Condensate_BD_Sim
Brownian dynamics simulation of simple system capable of condensate formation. Droplet-forming particles experience attraction at short distances, allowing them to form stable condensates at sufficiently high concentrations. A polymer comprising non-interactive sections and interactive sections that attract the droplet-forming particles can be added. This polymer (or surface) can lead to surface-condensation below the critical concentration for classical phase separation. The presence of condensates or droplets is determined by DB-scan (distance=40nm, min_samples=10).
Implementation in python using ReaDDy for particle dynamics.
<br>
<br>
<br>
![NanomotifSimulations_2](https://github.com/user-attachments/assets/d6b4f7ba-c6f1-45c6-8bde-bbc294fef31d)


A) Interactive particles can form condensates due to short-ranged attraction. Attractive sections on a polymer can lead to surface condensation. B) Low concentrations of the droplet-forming particles do not form stable condensates, however, surface condensation can be observed when adding the polymer. At high concentrations, droplets form via phase separation followed by coarsening even without surface. C) DB-scan can be used to detect droplets in the simulation. The threshold concentration for formation of droplets is notably decreased in the presence of a condensation surface. Here, 5 simulation runs of $10\cdot 10^6$ steps were averaged.
