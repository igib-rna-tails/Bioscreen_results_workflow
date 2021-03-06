# Bioscreen results workflow

## Growth rate analysis with Bioscreen or any 96-well plate

This notebook contain workflow to prepare and analyse the results of microbial growth rate in Bioscreen Honeycomb plates or any 96-well plate.


Lidia Lipinska, Postdoc

Institute of Genetics and Biotechnology, University of Warsaw


### Steps:
1. Install requirements.
2. Import raw data.
3. Prepare raw data for visualisation (numpy, pandas).
4. Visualisation of growth curves.
5. Usage of [pyphe-growthcurves made by Stephan Kamrad from Bahler Lab](https://github.com/Bahler-Lab/pyphe-growthcurves) for determination of maximal slope of growth curves and time of microbial lag phase.
6. Visualisation of the maximum slope and the lag phase on box plots (matplotlib, seaborn).
7. Visualisation of max_slope and the lag phase on heatmaps -- Let's look at __[Bioscreen_results_part2_heatmap.ipynb](./Bioscreen_results_part2/Bioscreen_results_part2_heatmap.ipynb)__.



### Requirements: 
    . numpy >= 1.8.0
    . scipy >= 0.17.0
    . pysam >= 0.8
    . matplotlib >= 1.4.0
    . seaborn
    . pytime
    . parsedatatime
    . pytimeparse
