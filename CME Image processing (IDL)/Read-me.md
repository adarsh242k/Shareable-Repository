This file includes codes in IDL for conversion of L0 and L0.5 images to L1 images for STEREO COR 2 images.
Sample L0 (20081212_103754_d4c2B.fts) and L1 (20081212_103754_cbsimg_c2BB.fits) images can be found in the folder.

The fts files undergo processes like - 
1. divide by exposure duration,
2. correcting for onboard image processing,
3. subtracting the CCD bias,
4. multiplying by the calibration factor (converts the image values from digital number (DN) to the physical units of mean solar brightness (MSB)),
5. vignetting and flat-field correction, and
6. optical distortion correction

followed by getting saved in a different directory.
