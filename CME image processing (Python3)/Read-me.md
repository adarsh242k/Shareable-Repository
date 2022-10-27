This directory consists of Python3 versions of (initial) IDL codes that is used by the community for solar physics.

The codes in IDL_Techniques mainly serve the following purposes -
1. Getting L1 images directly from Helioviewer (an API used for visualising solar images).
2. Processing L0.5 images to get a better view of the CMEs.
3. Implementing Graduated Cylindrical Shell (GCS) model (the mesh) on images obtained from 1. and 2. to measure the geometric parameters of Coronal mass ejections.

The GCS_python was adapted from - Freiherr von Forstner, J. L. (2021). GCS in Python (Version 0.2.2) [Computer software]. https://doi.org/10.5281/zenodo.5084818

A fitting code 'CME measurements evaluation (just fitting - submitted_20220825)-Copy1.ipynb' was developed for impementation of FRIS model for studying the thermodynamic state of CMEs as they travel through IP space. (refer - Mishra, W., & Wang, Y. (2018). Modeling the Thermodynamic Evolution of Coronal Mass Ejections Using Their Kinematics. The Astrophysical Journal, 1, 50. https://doi.org/10.3847/1538-4357/aadb9b) 
