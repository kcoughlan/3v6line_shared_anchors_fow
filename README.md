# 3-line and 6-line shared anchor systems in deep water: OpenFAST model

This repository contains OpenFAST v3.3.0 input files for 3-line and 6-line shared anchor systems using the IEA 15 MW reference turbine on the VolturnUS semisubmersible platform. While the mooring designs and thus MoorDyn files are unique, the other input files are based on the repository found here:https://github.com/IEAWindTask37/IEA-15-240-RWT

The OpenFAST input files are found in the input_files directory. Within this folder, they are organized into:
* 3line: files for the 3-line system specifically
* 6line: files for the 6-line system specifically
* common_files: ElastoDyn and WaterKin files used for both systems, as well as the MoorDyn files for all systems and load cases.

Within the 3line and 6line folders, subfolders exist for a 0deg analysis and a WWC analysis. Each folder contains subfolders for three IEC design load cases: DLC 1.6, DLC 6.1, and SLC. 

The results folder contains Matlab .mat files of the mooring line and anchor loads for both 0deg and sweep. 

Please reference the following for detailed information on the design and analysis of these systems:
* Coughlan, K. (2024). Mooring systems for floating offshore wind: Mooring design, biocolonisation, and shared anchors [PhD]. University of Massachusetts Amherst.
* Coughlan, K; Davis, M; Westgate, Z; Junho, J; Arwade, S; Martin, B; DeGroot, D. "Design and analysis of shared anchor layouts for floating wind farms in deep water". Ocean Engineering (under revision).
