PolyRECOVisualizationTool

Overview
The PolyRECO Visualization Tool is a MATLAB application designed to help explore and visualize potential polymer combinations that meet specific mechanical thresholds. This tool converts SMILES strings into chemical names and allows users to explore different polymer combinations based on parameters such as:

Degree of polymerization (DP)
Glass transition temperature (Tg)
ABA Block Weight percentages
Copolymer compositions

1. Requirements for Deployment

MATLAB Runtime (R2024a) is required to run this application

Download and install the Windows version of the MATLAB Runtime for R2024a from:
https://www.mathworks.com/products/compiler/mcr/index.html
Note: Administrator rights may be required to install the MATLAB Runtime
      
2. Installation Instructions

Download and install MATLAB Runtime (R2024a) from the link above
Download the PolyRECO Visualization Tool package
Extract all files, maintaining the folder structure
Run PolyRecoVisualizationTool.exe

3. Files Included

PolyRECOVisualizationTool.exe - Main application executable
Case Study Files (Case1-3.xlsx) - Example datasets for exploration
Mapping.xlsx - Required for SMILES to chemical name conversion
User_Guide.md - Detailed instructions on using the application
README.md - This file

4. Basic Usage

Load a case study file using the "LoadData" button
Load the mapping file using the "LoadMapping" button
Convert SMILES to chemical names using the "SMILEStoNAME" button
Calculate weight percentages with the "Calculate wt%" button
Explore polymer combinations using the interactive visualization tools

For more detailed instructions, please refer to the included User_Guide.md file.

5. Naming Convention
Polymer names follow this format:

ROCOP polyesters: Epoxide_Anhydride
ROCOP polycarbonates: Epoxide_CO2
Copolymer blocks are indicated with a comma (,). e.g. CHO_CO2,CPO_CO2

6. Case Studies
The tool includes three case studies demonstrating different polymer combination scenarios:

Case Study 1: Exploring partner A blocks for poly(εCL)
Case Study 2: Examining low-Tg B blocks
Case Study 3: Investigating high-Tg copolymer A blocks with varied compositions

Troubleshooting
If you encounter issues running the application:

Verify you have installed the correct MATLAB Runtime version (R2024a)
Ensure all required data files are in the correct location
Ensure all required data files have unchanged column headings
Check that you have sufficient permissions on your system

Contact Information
[Georgina L. Gregory, University of Oxford]
