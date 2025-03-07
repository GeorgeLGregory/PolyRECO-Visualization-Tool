# PolyRECO Visualization Tool

*Overview*

The PolyRECO Visualization Tool is a MATLAB application designed to help explore and visualize potential polymer combinations that meet specific mechanical thresholds. This tool converts SMILES strings into chemical names and allows users to explore different polymer combinations based on parameters such as:

* Degree of polymerization (DP) <br>
*  Glass transition temperature (Tg) <br> 
* Copolymer compositions <br>

## Requirements

MATLAB Runtime (R2024a) is required to run this application

Download and install the Windows version of the MATLAB Runtime for R2024a from:
https://www.mathworks.com/products/compiler/mcr/index.html

Note: Administrator rights may be required to install the MATLAB Runtime

## Download

You can download the PolyRECO Visualization Tool directly:
[Download PolyRECOVisualizationTool.zip](https://github.com/GeorgeLGregory/PolyRECO-Visualization-Tool/raw/main/PolyRECOVisualizationTool.zip)
      
## Installation Instructions

1. Download [PolyRECOVisualizationTool.zip](https://github.com/GeorgeLGregory/PolyRECO-Visualization-Tool/raw/main/PolyRECOVisualizationTool.zip)
2. Download and install [MATLAB Runtime R2024a](https://www.mathworks.com/products/compiler/mcr/index.html) <br>
3. Extract all files from the .zip maintaining the folder structure <br>
4. Run PolyRecoVisualizationTool.exe

## Files Included

* PolyRECOVisualizationTool.exe - Main application executable
* Case Study Files (Case1-3.xlsx) - Example datasets for exploration
* Mapping.xlsx - Required for SMILES to chemical name conversion
* User_Guide.md - Detailed instructions on using the application
* README.md - This file

## Basic Usage

1. Load a case study file using the "LoadData" button
2. Load the mapping file using the "LoadMapping" button
3. Convert SMILES to chemical names using the "SMILEStoNAME" button
4. Calculate weight percentages with the "Calculate wt%" button
5. Explore polymer combinations using the interactive visualization tools

For more detailed instructions, please refer to the included User_Guide.md file.

## Naming Convention
Polymer names follow this format:

* ROCOP polyesters: Epoxide_Anhydride
* ROCOP polycarbonates: Epoxide_CO2
* Copolymer blocks are indicated with a comma (,). e.g. CHO_CO2,CPO_CO2

## Case Studies
The tool includes three case studies demonstrating different polymer combination scenarios:

* Case Study 1: Exploring partner A blocks for poly(εCL)
* Case Study 2: Examining low-Tg B blocks
* Case Study 3: Investigating high-Tg copolymer A blocks with varied compositions

## Troubleshooting
If you encounter issues running the application:

* Verify you have installed the correct MATLAB Runtime version (R2024a)
* Ensure all required data files are in the correct location
* Ensure all required data files have unchanged column headings
* Check that you have sufficient permissions on your system

*Contact Information* <br>
[Georgina L. Gregory, University of Oxford]
