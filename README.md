Project Overview

Traditional biometrics like fingerprints require physical contact, leading to hygiene concerns and spoofing risks. This project proposes a contactless authentication system using deep learning to recognize individuals based on unique blood vessel patterns in the sclera (white region of the eye).



&#x20;Key Features:

* Contactless Authentication: Hygienic and secure user identification.
* Deep Learning Segmentation: Utilizes a U-Net and Siamese network architecture for accurate identification.
* Robustness: Works under varying lighting conditions with advanced preprocessing.



System Architecture:



* Image Acquisition: Capture eye images using a camera.
* Preprocessing: Resizing, normalization, and noise removal.
* Segmentation: Isolate the sclera region.
* Feature Extraction: Extract unique vessel patterns using a CNN.
* Matching: Compare features against the database to grant or deny access.

