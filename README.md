Software for study of the variability of the geomagnetic field. ConvectionVariance.ipynb describes a stochastic model for the convective power in the core. The convective power is used in a dynamo energy balance to predict fluctuations in the magnetic energy.

Files needed to read geodynamo simulations "neutral top" and "stabletop29percent" from Aubert et al. (2025) are also included. Input files power1.dat, e_mag1.dat and e_kin1.dat refer to neutral top. Input files power2.dat, e_mag2.dat and e_kin2.dat refer to "stabletop29percent". Notebooks NeutralTop.ipynb and StableTop29.ipynb are specifically written to read the dynamo files and displays the results. CorrectPower.ipynb corrects the convective power to account for the influence of viscous dissipation and inertia. Input files need to be set to the relevant simulation and the instructions for removing duplicate entries may need to be uncommented.

Reference:
Aubert et al., 2025. Core-surface kinematic control of polarity reversals in advanced geodynamo simulations, Phys. Earth Planet. Inter. 364, 107365.
