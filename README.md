# Network83
Files and Mathematica notebook for "An Introduction to Network Models of Neurodegenerative Diseases"
by Georgia Brennan and Alain Goriely

All files necessary to simulate the progression of neurodegenerative diseases on a 83-node connectome

ROI: Region Of Interest

NamesAndPosition.csv contains the name and position of each ROI (and their label)

VolumeOfNodes.csv contains the name and volume of each ROI (and their label)

LengthOfFibers.csv  is a 83 x 83 matrix that contains the axonal length between two ROIs

NumberOfFibers.csv  is a 83 x 83 matrix that contains the number of fibers between two ROIs

A0.csv is the normalised, weighted-adjacecncy matrix with length-free weights.

A1.csv is the normalised, weighted-adjacecncy matrix with ballistic weights.

A2.csv is the normalised, weighted-adjacecncy matrix with diffusive weights.

F.csv is the normalised, weighted-adjacecncy matrix with Eucidian distance weights.

Network83.nb is the Mathematica (13.0) workbook that simulate and displays the evolution of the concentration on the connectome.
