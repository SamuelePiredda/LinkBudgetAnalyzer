# LinkBudgetAnalyzer
This script Python (3.11) works together with GMAT to analyze the link margin between satellite and ground stations network on the Earth.


You create the GMAT scenario including all the ground stations that you need. You perform the propagation and
create report files

1) PosSat.txt

This contains the X,Y,Z position of the satellite, the altitude and the date time.

2) PosGS.txt

This contains the X,Y,Z position of all the ground stations.


Do not fear to have files that are GB large since the analysis is done line by line, it will not load all the content
in the RAM.

