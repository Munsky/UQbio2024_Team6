# UQbio2024_Team6 Drug-E
1. Load image dataset
2. Make mask to determine treshold(0,1)
    -> cell
    -> nucleus
    -> RNA
    ->
3. Grayscale image (0-225)
4. Measure the grayscale on the segment area at each timepoint
5. Measure the sum of pixels on the segment area (they should be the same for cell)
6. Divide intenisty by area.
