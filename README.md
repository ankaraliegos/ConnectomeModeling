# ConnectomeModeling
This is the latest revision for cones and ON cone bipolar cells.

For detailed information on the model refer to the word and powerpoint files in the Documentation folder.

Instruction to run the model files:

	Before starting, compile the main folder using the mknrndll command. NEURON version at the time of upload is 7.7.1.

	To start the simulation run the init.hoc file. This will save the results as .txt files in the main folder upon completion.

	A run has already been saved in the output folder. These can be plotted in MATLAB using the script provided.

	Parameters of simulation such as time of stimulation, duration and time step can be adjusted in the parameters.hoc file.

	The cone input can be adjusted in the stimulation.hoc file. Note that the first part is for rods and second part is for cones.
	Amplitude, duration and repetition of photocurrent can be changed here.

	The cell morphology files (swc) are located in the morphology folder. The cell types and synaptic information is located
	in the topology folder.

	Conversion to .txt format is handled in the export_v.hoc file. Note that the cell numbering follows the ordering in the 
	CellTypes.txt file. For example, cell[0] would refer to the first line in the file.

