# Bioscreen resultsworkflow

## Growth rate analysis with Bioscreen or any 96-well plate

This notebook contain workflow to prepare and analyse the results of microbial growth rate in Bioscreen Honeycomb plates or any 96-well plate.

### Steps:
1. Install requirements.
2. Import raw data.
3. Prepare raw data for visualisation (numpy, pandas).
4. Visualisation of growth curves.
5. Usage of [pyphe-growthcurves made by Stephan Kamrad from Bahler Lab](https://github.com/Bahler-Lab/pyphe-growthcurves) for determination of maximal slope of growth curves and time of microbial lag phase.
6. Visualisation of max_slope and lap phase on box plots (matplotlib, seaborn).



### Requirements: 
    . numpy >= 1.8.0
    . scipy >= 0.17.0
    . pysam >= 0.8
    . matplotlib >= 1.4.0
    . seaborn
    . pytime
    . parsedatatime
    . pytimeparse
