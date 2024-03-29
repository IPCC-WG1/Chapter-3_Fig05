TEMPORAL VARIABILITY OF NEAR-SURFACE AIR TEMPERATURE
====================================================
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6656167.svg)](https://doi.org/10.5281/zenodo.6656167)

Figure number: Figure 3.5
From the IPCC Working Group I Contribution to the Sixth Assessment Report: Chapter 3

![Figure 3.5](ar6_wg1_chap3_figure3_5_surface_temp_variablility.png?raw=true)


Description:
------------
The standard deviation of annually averaged zonal-mean near-surface air
temperature. This is shown for four detrended observed temperature datasets
(HadCRUT5, Berkeley Earth, NOAAGlobalTemp-Interim and Kadow et al. (2020), 
for the years 1995-2014) and 59 CMIP6 pre-industrial control simulations (one 
ensemble member per model, 65 years) (after Jones et al., 2013). For line 
colours see the legend of Figure 3.4. Additionally, the multi-model mean (red) 
and standard deviation (grey shading) are shown. Observational and model 
datasets were detrended by removing the least-squares quadratic trend.


Author list:
------------
- Bock, L.: DLR, Germany; lisa.bock@dlr.de
- Bellouin, N.: University of Reading, UK
- Gillett, N.: Environment and Climate Change Canada


ESMValTool Branch:
------------------
- ESMValTool-AR6-OriginalCode-FinalFigures: [ar6_chapter_3](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/tree/ar6_chapter_3)


ESMValCore Branch:
------------------
- ESMValCore-AR6-OriginalCode-FinalFigures: [fix_cmip6_models_newcore](https://github.com/ipcc-wgi/ESMValCore-AR6-OriginalCode-FinalFigures/tree/fix_cmip6_models_newcore)


Recipe & diagnostics:
---------------------
Recipe used: [recipes/ipccwg1ar6ch3/recipe_ipccwg1ar6ch3_atmosphere.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/recipes/ipccwg1ar6ch3/recipe_ipccwg1ar6ch3_atmosphere.yml)

Diagnostic used: [diag_scripts/ipcc_ar6/zonal_st_dev.ncl](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/ar6_chapter_3/esmvaltool/diag_scripts/ipcc_ar6/zonal_st_dev.ncl)


Expected image path:
--------------------
- recipe_ipccwg1ar6ch3_atmosphere_YYYYMMDD_HHMMSS/plots/fig_3_5/fig_3_5/tas_std_dev_zonmean.eps


Software description:
---------------------
- ESMValTool environment file: [IPCC_environments/ar6_newcore_lisa_conda_environment.yml](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_lisa_conda_environment.yml)
- pip file: [IPCC_environments/ar6_newcore_lisa_pip_environment.txt](https://github.com/ipcc-wgi/ESMValTool-AR6-OriginalCode-FinalFigures/blob/main/IPCC_environments/ar6_newcore_lisa_pip_environment.txt)


Hardware description:
---------------------
Machine used:  Mistral
