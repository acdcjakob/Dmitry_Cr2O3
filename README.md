# W6725
## data
Folders:
- Transmission data (not corrected)
- "XRD_2ThetaOmega"
    - 10-130deg (whole range)
    - 58-72deg (range where we can see the peak)
    - "W6725_peaks.txt" tab seperated file with information about the film and substrate peak (important: Pos. [°2Th.])
- "XRD_Omega"
    - .xy-file containing data about the \omega-scan (Rocking curve)
    - "W6725_omega_peaks.txt" tab seperated file with information about the film peak (important: FWHM left [°])
- "XRD_Phi"
    - one file for the substrate (fix 2theta-position and rotate sample by 360°)
    - one file for the film
- "XRD_RSM"
    - not important for you, I think


Files:
- the highscore-plus files for omega and 2theta-scan (not important, i gave you everything extracted in the folders)
## the tilt angles
In the folder "tilt angle w6725" there is a picture of the reciprocal space maps. Along the c-direction (plane 30.6 and 30.-6) there is a tilt of ~32 arcseconds (32 (1/60)°). Also another picture zoomed onto the film peaks, ignore the numbers, they are just for correction.

The tilt angle perpendicular to the c-axis is only ~2 arcseconds.

# W6911m
Folders: same as above but wihtout transmission, Phi and RSM's

# Literature about growth

Here are 4 papers relevant for heteroepitaxial growth: (but be careful not to dive too deep, I am not sure how important the theoretical background is for you.)

Grundmann, M. (2018). Elastic theory of pseudomorphic monoclinic and rhombohedral heterostructures. Journal of Applied Physics, 124(18), 185302. https://doi.org/10.1063/1.5045845

Grundmann, M. (2020). A Most General and Facile Recipe for the Calculation of Heteroepitaxial Strain. Physica Status Solidi (b), 257(12), 2000323. https://doi.org/10.1002/pssb.202000323

Grundmann, M., & Lorenz, M. (2021). Azimuthal Anisotropy of Rhombohedral (Corundum Phase) Heterostructures. Physica Status Solidi (b), 258(7), 2100104. https://doi.org/10.1002/pssb.202100104

Kneiß, M., Splith, D., Von Wenckstern, H., Lorenz, M., Schultz, T., Koch, N., & Grundmann, M. (2021). Strain states and relaxation for alpha-Ga2O3 thin films on prismatic planes of alpha-Al2O3 in the full composition range: Fundamental difference of a- and m-epitaxial planes in the manifestation of shear strain and lattice tilt. Journal of Materials Research, 36(23), 4816–4831. https://doi.org/10.1557/s43578-021-00375-3

# Additional stuff
## W6725
fabrication details (probably not important for you)
- 650mJ laser energy, 40 000 pulses at 20 Hz
- 1e-3 mbar O2
- 760°C growth temperature
- 7.5mm offset from plasma center
- highest laser focus (high energy density)

In the folder additional stuff:

"1-RSM_latticeData.png"
- here you can see all three lattice constants extracted for some samples; the W6725 is the one in the middle

"1-shift_vs_d_combined.png"
- here you can see the 2theta scan compared to other samples from the series; the W6725 is the thickest (400nm)

## W6911m
"5-latticeOnly_m.png"
-  comparison to other samples of different thickness and different laser energy density during fabrication; the W6911m is one of the 0.76 J/cm^2 ones (the thicker one)
