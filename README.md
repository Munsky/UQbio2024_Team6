# UQbio2024_Team6 Drug-E

STAGE 1
1. Load image dataset (tif file)
2. Make and define variables/types
    -> cell number (int)
    -> nucleus number (int)
    -> number of mRNA (int)
    -> number of transcription sites (int)
    -> cell intensity (this will help to determine viability)
    ->mRNA intensity
    ->protein concentrations
    ->transcription site intensity

3. Make mask to determine treshold(0,1)
    -> cell number
    -> nucleus number
    -> mRNA number
    
4. Grayscale image (0-225) (min-max value)
    -> intensity
5. Measure the grayscale on the segment area at each timepoint
6. Measure the sum of pixels on the segment area (they should be the same for cell)
7. Divide intenisty by area.
8. output a table (csv type) with : time, cell, type of analysis, sum of pix intensity, area of structure.
