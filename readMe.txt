we need to download opencv for this program first 
After we download opencv package, we can import cv2 in python, 

Before running the program, make sure import cv2 works and data in correct path

we install opencv by using these three comment lines in order to install and set environment 

conda create -n opencv numpy scipy scikit-learn matplotlib python=3

source activate opencv

conda install -c https://conda.binstar.org/menpo opencv3

each time I run program, we need to make sure in cv2 environment, before we run the command line.

For example:

1. if "import cv2" works 

2. python proj3.py Data/02/06.jpg(which is the path of the test image)

3 . we can set our trainning set range after the first for loop.


