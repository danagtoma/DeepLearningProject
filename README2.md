This dataset was obtained using Ptychographic X-ray Tomography on a sample extracted from Solid Oxide Cells.

The microstructure presents three phases (nickel, yttria-stabilized zirconia and pores). 
The accurate segmentation of the three phases is crucial to extract quantitative morphological properties. 

So, the grayscale values need to be reduced to a set of labels, one for each phase. 

In the training dataset, you have:

- data: this folder contains the RAW data (gray-scale) in the TIFF format (16-bit) 
- labels: this folder contains the segmented data (manual segmentation) in the TIFF format (8-bit) 

The goal of the project is to  teach a neural network to perform this segmentation, eliminating the manual intervention. 
