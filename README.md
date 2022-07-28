# CollectiveBehaviorFlowLight
Dataset of experiments of fish swimming behavior in the presence and absence of flow and light


The Excel files contains all the data for the manuscrip: 
Dataset of experiments of fish swimming behavior in the presence and absence of flow and light

The first 9000 rows (neglecting the first two ows for names/lables) correspond to the time trajectories of one of the subject of the pair while the remaining 9000 rows correspond to the second subject of the pair

Columns correspond to X, Y, Heading and Tail position for different trials


Matlab file
Contains the same data of the excel files but is arranged in cells.
The cell has four rows and 2 colums. 

    {1×12 struct}    {1×12 struct}
    {1×12 struct}    {1×12 struct}
    {1×12 struct}    {1×12 struct}
    {1×11 struct}    {1×11 struct}

Rows correspond to experimental conditions and colums to one fish of the pair

Condition Bright - No flow: first row
Condition Bright - Flow:    second row
Condition Dark - No flow:   third row
Condition Dark - Flow:      fourth row


Each cell position constains an structure with all the data of fish across trials


