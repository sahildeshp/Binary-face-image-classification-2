ECE 763 Computer Vision Project 1

Binary face image classification ω ∈ {0,1} using 
Gaussian model, Mixture of Gaussian model, t-distribution, and Factor Analysis.

I have used the FDDB dataset (http://vis-www.cs.umass.edu/fddb/), which contains the annotations for
5171 faces in a set of 2845 images taken from the Faces in the Wild data set. The data set comes with a annotations
folder which contains files with names: FDDB-fold-xx.txt and FDDB-fold-xx-ellipseList.txt, where xx = {01, 02, ..., 10} represents
the fold-index. Each line in the "FDDB-fold-xx.txt" file specifies a path to an image in the above-mentioned data set.
The corresponding annotations are included in the file "FDDB-fold-xx-ellipseList.txt".
Here, each face is denoted by: <major_axis_radius minor_axis_radius angle center_x

Run notebook 0_Data_Generation to create training and testing images 

Run each individual model notebook to get the results 

