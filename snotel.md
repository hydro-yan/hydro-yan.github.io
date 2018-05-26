## 3-Stage Filtered SNOTEL DATA 
<img src="https://image.ibb.co/jAAiRT/Picture1.png" class="image2" width="630" height="630" align="left" border="0" style="border-style: none;"> 
<img src="https://image.ibb.co/m68WD8/Screen_Size_Figure.png" class="image2" width="630" height="719" align="left" border="0" style="border-style: none;">
<img src="https://image.ibb.co/n3eVqo/qaqc_procedure.png" class="image2" width="630" height="1415" align="left" border="0" style="border-style: none;">

<br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> 

Two sets of QA/QC daily SNOTEL data (compressed zip file) up through 09/30/2017 for 825 active stations located in western United States and Alaska are available to download.

- [two_stage_filtered_data](https://dhsvm.pnnl.gov/downloads/data/two_stage_filtered_data.zip): Removed erroneous values and outliers in precipitation, temperature, and SWE using a two-stage filter. The two-stage filter was first proposed by [Serreze et al. (1999)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/1999WR900090) and later enhanced by [Yan et al. (2018)](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1002/2017WR021290).
- [three_stage_filtered_data](https://dhsvm.pnnl.gov/downloads/data/three_stage_filtered_data.zip): Removed erroneous values and outliers in precipitation, temperature, and SWE, as well as “inconsistent water year” data using a three-stage filter (see [Yan et al., 2018](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1002/2017WR021290) for details).

In each folder, the file of each station is named as “f_lat_lon.txt”. In each text file, there are nine columns:
- 1st col: year
- 2nd col: month
- 3rd col: day
- 4th col: PREC (accumulated precipitation), in inch, reset to zero on 1 October at the start of each water year
- 5th col: PRCP (daily precipitation), in inch
- 6th col: maximum air temperature, in °F
- 7th col: minimum air temperature, in °F
- 8th col: average air temperature, in °F
- 9th col: SWE (snow water equivalent), in inch, reset to zero on 1 October at the start of each water year

Note: The raw daily SNOTEL observations were downloaded from U.S. Department of Agricultural Natural Resources Conservation Service (NRCS) at: [https://www.wcc.nrcs.usda.gov/snow/](https://www.wcc.nrcs.usda.gov/snow/)

If you decide to use the data, please cite the source as noted below:

<strong>Yan, H., Sun, N., Wigmosta, M., Skaggs, R., Hou, Z., and Leung, R. (2018). “Next-generation intensity-duration-frequency curves for hydrologic design in snow-dominated environments.” <em>Water Resources Research</em>, 54(2), 1093–1108. <a href="https://doi.org/10.1002/2017WR021290">https://doi.org/10.1002/2017WR021290</a></strong>
