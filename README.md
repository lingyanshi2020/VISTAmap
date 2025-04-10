![VISTA](https://github.com/user-attachments/assets/196129ab-2399-4f74-8a4d-09d84700059d)
![graphical abstract VISTAmap](https://github.com/user-attachments/assets/5da43041-3e42-4239-91fa-5d2d2d0ec43b)

# VISTAmap
Single-Frame Vignetting Correction for Post-Stitched-Tile Im-aging using VISTAmap (VIgnetted Stitched-Tile Adjustment using Morphological Adaptive Processing)

**Disclaimer**: This is designed as a tutorial in image processing to mitigate the negative impacts of shaded artifacts in large, non-rectangular post-stitched tile images, especially when the raw individual tiles are not available. 
No method that modulates pixel intensities is suitable for all types of quantitative analyses. This simple method is intended for illustrative purposes.
Step-wise instruction can be found in the associated article in the special edition of _Nanomaterials (MDPI)_ titled: "New Advances in Applications of Nanoscale Imaging and Nanoscopy"

Cite as: Fung, Anthony A., Ashley H. Fung, Zhi Li, and Lingyan Shi. “Single-Frame Vignetting Correction for Post-Stitched-Tile Imaging Using VISTAmap.” Nanomaterials 15, no. 7 (January 2025): 563. https://doi.org/10.3390/nano15070563.

Instructions:
This was tested using:
13th Gen Intel(R) Core (TM) i9-13900H, 2600 Mhz, 14 Core(s), 20 Logical Processor(s)
64 GB DDR4 RAM
Windows 11 Pro

Simply press run, or section > run section to run an individual section 

Inputs are a single-frame (2D) stitched image, and optionally a binary mask image of the tissue (if not, the code will attempt to create a mask)

Demo images are included as "demo.tiff" and "demo_mask.tiff"
