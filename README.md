# MackenzieConnectivity

** For use during the review process for WRR ** 
Data is unpublished

## Folder contains 6 R markdown scripts:
0_surfaceReflectanceCorrection: Corrects landsat 5 and 8 reflectance to landsat 7

1_connectivityClassification: Classifies each landsat observation into class 0 (no functional connectivity), 1 (some/intermediate functional connectivity) or 2 (high functional connectivity)

2_summaryResultFigures: Plots many of the connectivity classification results figures

3_waterLevelSillElevationCalculation: Calculates the functional connectivity elevation thresholds and resulting connectivity durations

4_trendAnalysis: Calculates trends in connectivity

5_resuspension: Analyzes the occurrence of resuspension

## Inputs needed for each script can be found here organized by script:
https://doi.org/10.5281/zenodo.10798879

## Google Earth Engine Script run prior to R analysis can be found here
Primary reflectance export code: https://code.earthengine.google.com/f6e00bc218f99556fba99815f7961fa7

Training dataset generation code:
https://code.earthengine.google.com/b49d60e299b9384bcd416af0fead3da3
