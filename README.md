MATADOR
=======

The application enables automatic analysis of acquired image data from flood illumination adaptive optic camera.
The images are automatically registered and the montage image is created. 
Further is possible to analyze the photoreceptor's location, density, and spacing in the montage image or its cropped part.

DESCRIPTION
-----------
The application was created in Matlab 2021b in Brno University of technology and
can be used freely for non-commercial research and medical purposes. 
Please cite the following publication when using the application:

"E. Valterova, J.D. Unterlauft, T. Kirsten, R. Kolar, F. G. Rauscher,
“Comprehensive Automatic Processing and Analysis of Flood Illumination Retinal Images,”
Biomed. Opt. Express.."

DATA
----
The application can be tested on our publicly available dataset on:
https://doi.org/10.5281/zenodo.6635685

CONTACT
-------
valterova@vut.cz


REQUIREMENTS
------------
Matlab Runtime 2021b
https://www.mathworks.com/products/compiler/matlab-runtime.html


USAGE
-----

1. Select the folder with AO-FIO images in ".png" format with no heading.
2. Choose the analyzed eye (right or left) and the range of uploaded data by the slider. Then press the Load and Montage button.
3. Set the Axial length of the eye.
   Choose the analyzing metric (photoreceptor's location, spacing or density).
   Choose the analyzed area (entire montage image or its cropped region). The area can be selected manually or by coordinates inscription.
   Press the Analyze button.

The displayed image is possible to zoom by the navigation buttons in the upper right corner of the image.

