# MassSpecDataExtraction
Extract data from Mass Spectrometry output files in order to normalize area fragments for peptides from different samples


#Usage
1. Place the downloaded MS1 and MS2 and the PGroupsTest .xlsm files into a directory.

2. In the same directory, create a folder called "Median Intensities". Drag any number of ProteinGroups.txt output files to process from MaxQuant into the folder.

3. Click the "Extract Data" button to generate normalization coefficients for all of the samples generated in the MS run. Click the "Multiply Areas" button to extract all of the peptide intensity data for each searched peptide in each sample, and automatically multiply them by the normalization coefficient. 

