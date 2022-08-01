# CollectiveBehaviorFlowLight
Dataset of experiments of fish swimming behavior in the presence and absence of flow and light

The Excel files contain all the data for the manuscript: Collective response of zebrafish to combined manipulations of illumination and flow

The first 9000 rows (neglecting the first two rows for names/labels) correspond to the time trajectories of one of the subject of the pair while the remaining 9000 rows correspond to the second subject of the pair

Columns correspond to X, Y, Heading and Tail position for different trials


Matlab files
There are two .mat files corresponding to the data of fish across all experimental conditions. These files contain the same data of the excel files and are arranged in cells.

Each .mat file has 1 row and 4 columns.

Wb1 =

  1×4 cell array

    {1×12 struct}    {1×12 struct}    {1×12 struct}    {1×11 struct}

Each column corresponds to an experimental conditions of one fish of the pair

Condition Bright - No flow: first column 
Condition Bright - Flow: second column 
Condition Dark - No flow: third column 
Condition Dark - Flow: fourth column

Each cell position contains a structure with all the data of fish across trials


The file Data_main.csv contains the scoring of the behavioral variables studied in the paper. 
This file was utilized to perform the statistical analysis in the manuscript. The columns correspond to:
- ID
- Illuminatio (variable)
- Flow (variable)	
- Polarization	
- Distance (relative distance)	
- Exploration	
- orientation	
- TBA	(tail beat frequency)
- TBF	(tail beat amplitude)
- Inline (time spent swimming in line [s])	
- SidebySide (time spent swimming side-by-side [s])	 
- PreferenceSidebyside (preference index to swim in side-by-side configuration)






