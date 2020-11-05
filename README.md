# Pencil-Sketch-Using-Open-CV-In-Python
Open CV (Open Source Computer Vision) is a very powerful library of programming functions mainly aimed at real-time computer vision. Created by Intel in 1999, it is written in C++ (we will be using the Python bindings).   In this brief code, we will see how one can change from: photo to cartoon effect and photo to pencil sketch effect

Create a cartoon effect
 
Stylization aims to produce digital imagery with a wide variety of effects not focused on photorealism. Stylization can abstract regions of low contrast while preserving, or enhancing, high-contrast features.
 
### Parameters
src Input 8-bit 3-channel image.

dst Output image with the same size and type as src.

sigma_s Range between 0 to 200.

sigma_r Range between 0 to 1.

### Note
sigma_s controls how much the image is smoothed - the larger its value, the more smoothed the image gets, but it's also slower to compute.

sigma_r is important if you want to preserve edges while smoothing the image. Small sigma_r results in only very similar colors to be averaged (i.e. smoothed), while colors that differ much will stay intact.
