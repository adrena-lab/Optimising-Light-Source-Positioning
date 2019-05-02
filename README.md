# Optimising Light Source Positioning for Even and Flux-Efficient Illumination

Designing imaging systems is a challenge faced by researchers in many fields.  For example, many studies require optical set-ups with uniform illumination for data acquisition which must be rapidly assembled and optimised to meet the needs of each experiment.  Similarly, when prototyping new pieces of equipment with imaging systems, the lighting must be carefully designed.  Non-uniform illumination can contribute to low quality data, particularly so when illumination variation approaches or exceeds the sensitivity range of the capture device. Furthermore, low flux efficiency may negatively impact the reliability of the data and subsequent analysis.
This software is aimed at researchers who are optimising equipment for any application, from fluorescence measurements to image analysis, which require even and flux-efficient illumination.  The code can be easily adjusted to model a variety of light source configurations and rapidly calculates results for many thousands of possible arrangements.  This will significantly reduce the resources required to design an effective lighting system. 

## Dependencies

This software was designed for Matlab R2018a (Version 9.4) and requires the following toolboxes:

* Image Processing Toolbox
* Statistics and Machine Learning Toolbox
* Parallel Computing Toolbox
* MATLAB Distributed Computing Server

## Installation instructions

To install the software, please download “Optimising_Light_Sources.zip” and extract all of the files to the same folder. 

In order to run this software the following files are required:

**Optimising_Light_Source_Positioning.m**
    
    This is the main function file for the software.  In this file, the user provides the required information for each of the following functions. 
* Create_Variable_Combinations.m 
* Exclude_Unallowed_Combinations.m 
* Illumination_Calculations.m 
* Convhull_Option_Reduction.m 
* Plot_Save_Results.m

Optimising_Light_Source_Positioning.m is the main function file from which the entire code is run.  Within this file are instructions to the user for each step advising them where to make changes to adapt the code to their specific needs.  

## Example usage


