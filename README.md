# UIOPS: University of Illinois Optical Array Probe (OAP) Processing Software

This is the software developed in University of Illinois at Urbana-Champaign to process the Optical Array Probe Datasets.
Please consult this repository's wiki for full, detailed instructions to run the software, and also information on optional parameters to run.

## Current Developers & Contributers
- **Joe Finlon** (finlon2@illinois.edu)
- **Dan Stechman** (stechma2@illinois.edu)
- **Adam Majewski** (amajewsk@uwyo.edu)

## What's New
**February 26, 2018**
- **sizeDist:** Added support for adjusting the TAS when NaN values are encountered  

## Dependencies
**Supported OSes:** Linux, Mac (MATLAB Windows support coming in the future)  
**MATLAB Versions:** R2015a and higher (see https://www.mathworks.com/products/matlab.html for download and more info; student version from $99 USD; check w/ university for possible university-wide license)  
**MATLAB Toolboxes:** Parallel Computing, Statistics and Machine Learning, Curve Fitting, Image Processing  
**Supported Probes:** 2DS, HVPS, CIP, PIP, 2DC, 2DP  
**Supported Platforms:** SPEC, DMT, PMS, NCAR  

## Minimum Working Example
The UIOPS repository contains a sample dataset for you to test UIOPS on your system. Included are sample image files and helper scripts that allow the individual scripts to be executed. To save file space, the first step in processing (_read\_binary\_\*_) is skipped. Output files and plots are saved to a 'files' directory within the downloaded repository. To run this example execute the following scripts below within the _minimum\_working\_example/_ directory.

1. run\_imgProc\_Munich
2. run\_intArrAnalysis\_Munich (only analyzes 2DS inter-arrival times)
3. run\_sizeDist\_Munich
4. run\_sdPlots\_Munich
