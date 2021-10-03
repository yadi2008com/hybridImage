# hybridImage
I implement the convolution operator and not a different (but similar) operator.  A hybrid image is the sum of a low-pass filtered version of the one image and a high-pass filtered version of a second image. There is a free parameter, which can be tuned for each image pair, which controlshow much high frequency to remove from the first image and how much low frequency to leave in the second image. This is called the "cutoff-frequency". Low-pass filtering (removing all the high frequencies) can be achieved by convolving the image with a Gaussian filter. The cutoff-frequency is controlled by changing the standard deviation, sigma, of the Gaussian filter used in constructing the hybrid images. 
