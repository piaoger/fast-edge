FAST-EDGE seeks to be the fastest edge detection implementation in C.  Edge detection has many applications in computer vision and image processing and is a key component in feature detection and extraction.

# Goals #
Be the fastest edge detection implementation in C - with no external dependencies, just the standard C library.  Have clean and easy to understand code, that will be understandable by just about anyone.  Be the go-to implementation for the robotics community where speed is paramount while maintaining high accuracy.

# What's in the Current Version #
Contains several helpful functions to aid in edge detection.  Most notably, a full implementation of the Sobel operator (and Scharr's version of the Sobel operator which may have better rotational symmetry), a Gaussian noise reduction function, a threshold estimator, non-maximum suppression, and all the functions necessary for the implementation of the Canny edge detector.  Additionally, functions to read and write PGM image files is included.

# What's Needed #
Implementation of a general Gaussian function.
**More Speed**

# Bounties #
From time to time, bounties will be given out for implementing or improving code.