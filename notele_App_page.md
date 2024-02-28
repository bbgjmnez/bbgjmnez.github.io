## Comprehensive Tool for a Phase Compensation Reconstruction Method in Digital Holographic Microscopy Operating in Non-telecentric Regime

**Project description:** Quantitative phase imaging (QPI) via Digital Holographic microscopy (DHM) has been widely applied in material and biological applications. The performance of DHM technologies relies heavily on computational reconstruction methods to provide accurate phase measurements. Among the optical configuration of the imaging system in DHM, imaging systems operating in a non-telecentric regime are the most common ones. Nonetheless, the spherical wavefront introduced by the non-telecentric DHM system must be compensated to provide undistorted phase measurements. Here, we describe in detail the steps for reconstructing phase images without distortions and provide a user interface tool with minimum user input to reconstruct holograms recorded in a non-telecentric DHM system. The proposed reconstruction approach can be divided into six main steps. In the first step, the selection of the +1-diffraction order in the hologram spectrum is performed. The interference angle is obtained from the selected +1 order. Secondly, the curvature of the spherical wavefront distorting the sample's phase map is estimated by analyzing the size of the selected +1 order in the hologram's spectrum. The third and fourth steps are the spatial filtering of the +1 order and the compensation of the interference angle, respectively. The next step involves the estimation of the center of the spherical wavefront. Finally, an optional final optimization step is required to fine-tune the estimated parameters and provide fully compensated phase images.

### Links

[PLOS ONE Link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0291103)

[GitHub Link](https://github.com/bbgjmnez/noteleDHM-Tool)

[Journal Publication PDF](/pdf//2023-nonteletool-PLoSONE-FINAL.pdf)

[Conference Presentation PDF](/pdf/SPIE2023-West-DHM-NonTele-Final.pdf)

Citation: B. Bogue-Jimenez, C. Trujillo, A. Doblas. “Comprehensive tool for a phase compensation reconstruction method in digital holographic microscopy operation in non-telecentric regime,” PLoS ONE, 18(9), e0291103 (2023); https://doi.org/10.1371/journal.pone.0291103.

### 1. Fundamental Working Principles

This implementation for the reconstruction of non-telecentric holograms relies on several typical Computer Vision methods including the Fourier Transform and Otsu Thresholding for binarization, which isolate and characterize several parameters of a spherical wave. These parameters are then used to create an synthetic inverted spherical wave which cancels out the original aberrations, returning a clean phase map.   

### 2. Workflow

<img src="images/noteleApp/Picture1.png?raw=true"/>

### 3. App GUI Layout

<img src="images/noteleApp/Picture3.png?raw=true"/>

### 4. Microscope Setup

<img src="images/noteleApp/Picture4.png?raw=true"/>

### 5. Results

<img src="images/noteleApp/Picture6.png?raw=true"/>

### Impact

The MATLAB and Python applications that were developed may aid researchers by simplifying the process of hologram reconstrction. 
