# UQbio2024_Team6 Drug-E
1. Load image dataset (tif file)
2. Use function to determine best
4. Deifne variables and their type:
   -> number of cells (int)
   -> number of nucleus (int)
   -> cell size 
   ->nucleus size
   ->protein concentrations (AU) - given
   -> number of mRNA
       ->Nucleus
       ->Cytoplasm
   ->num transciption site (int)
   ->intensity of transcription site
   -> intensity
6. Make mask to determine treshold in binary (0,1)
   ->Limit will determine number of type (cell, nucleus, mRNA, transcription)
8. Grayscale image (0-225)
   ->to determine intensity
10. Measure the grayscale on the segment area at each timepoint
11. Measure the sum of pixels on the segment area (they should be the same for cell)
12. Divide intenisty by area.
13. Output
    -> table (csv file) Features by Observation
    time, cell, type of analysis, area of structure
    
