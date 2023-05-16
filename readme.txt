Run program from command line as follows:
(while in directory containing file and images)
__init__.py image.pgm sigma

Sigma must be a positive integer.

The program will then ask you to name the 2 resulting images,
the sobel gradient image and the non-maximum suppression image.
Filenames must include '.pgm' extension.

Sigma for all my example images is 1, threshold for gradient magnitudes
is 90.