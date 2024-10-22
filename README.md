## list of contents and description

open_hyper_plot.py : opens a hyperspectral image (or a 3D image) and display it along with a slider to move across the 3D stack.

processing_functions.py : image processing (remove brigh spots, focus in a presrived zone, segment the leaves and clean the resulting binary mask (morphological operators), then apply to the whole hyperspectral stack to compute the mean leaf intensity per wavelength

main.py : launch the previous code for a list of files, draw the plots

test_lauchPy_fromR.R : a R program to lauch the previous python program from R, get the data and plot them.
