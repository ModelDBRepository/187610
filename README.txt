////////////////////////////////////////////////////////////////////////////////
//
// Code by Mark Cembrowski, Janelia Research Campus, 2015-16.
// Correspondence can be addressed to cembrowskim@janelia.hhmi.org
// 
// Computational modeling involved in Bloss, Cembrowski, Karsh, Colonell,
// Fetter, and Spruston, Neuron, 2016.
//
// The enclosed code distributes excitation and inhibition (the latter in a 
// genotype-specific manner) across the dendritic arbor and provides scripts
// for the easy simulation of inputs onto CA1 pyramidal cells.
//
// To load in the NEURON simulation environment:
// 1. Download and install NEURON (http://www.neuron.yale.edu/neuron/) if needed
// 2. Compile the arrayTomography directory via mknrndll. For help, see:
//    MSWindows: https://www.neuron.yale.edu/neuron/static/docs/nmodl/mswin.html
//    MacOS: http://www.neuron.yale.edu/neuron/static/docs/nmodl/macos.html
// 3. Launch start.hoc in the NEURON simulation environment.
//
////////////////////////////////////////////////////////////////////////////////