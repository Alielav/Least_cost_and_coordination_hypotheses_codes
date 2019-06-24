
# R code for predicting leaf internal to ambient CO2 concentrations (ci/ca) and gross primary production (GPP) based on the least-cost and coordination hypotheses (Prentice et al. 2014; Wang et al. 2017)
# by Alienor Lavergne
# Last update: 24 June 2019

Output: Ratio of leaf-internal to ambient CO2 concentrations (ci/ca or chi, unitless)
Input:  Elevation (elv, m), 
        Temperature (tc, C), 
        Vapour pressure deficit (vpd, kPa), 
        CO2 concentrations (ca, ppm, optional)
Ref:    Wang et al. (2017), Nature Plants: equation (8) or (9) 


Output: Ratio of to ambient CO2 concentrations (cc/ca, or chc, unitless)
Input:  Elevation (elv, m), 
        Temperature (tc, C), 
        Vapour pressure deficit (vpd, kPa), 
        Ratio of mesophyll to stomatal conductance (teta, unitless),
        CO2 concentrations (ca, ppm, optional)
Ref:    Wang et al. (2017), Nature Plants: equation (33) or (34) 
        
Outputs: Gross primaray production (GPP, gC m-2 time-1)
Input:  Elevation (elv, m), 
        Temperature (tc, C), 
        Vapour pressure deficit (vpd, kPa), 
        CO2 concentrations (ca, ppm),
        Photosynthetic photon flux density (PPFD, mol m-2 time-1),
        fraction of absorbed photosynthetically active radiation (fAPAR, unitless)
Ref:    Wang et al. (2017), Nature Plants: equation (2) 

 
