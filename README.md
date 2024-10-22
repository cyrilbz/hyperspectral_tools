## list of contents and description

open_hyper_plot.py : opens a hyperspectral image (or a 3D image) and display it along with a slider to move across the 3D stack.

processing_functions.py : image processing : remove bright spots, focus in a prescribed zone, segment the leaves and clean the resulting binary mask (morphological operators), then apply the mask to the whole hyperspectral stack to compute the mean leaf intenisty per wavelength

main.py : launch the previous code for a list of files, compute the reflectance data, draw the plots

test_lauchPy_fromR.R : a R program to lauch the previous python program from R, get the data and plot them.
