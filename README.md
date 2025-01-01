# SAM Medical Imaging

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) [![Demo](https://img.shields.io/badge/Demo-0066ff.svg?style=for-the-badge&logo=<badge>&logoColor=<logo-color>)]

The Medical SAM (Segment Anything Model) repository is a fork of the [original SAM repository](https://github.com/facebookresearch/segment-anything) with modifications to support object segmentation in medical imaging using DICOM files. The SAM model is a state-of-the-art object segmentation model that predicts object masks given prompts that indicate the desired object. This implementation uses SAM to efficiently produce high-quality masks from prompts for medical imaging tasks using DICOM files. It allows the user to provide box prompt via the SamPredictor class to predict masks for a given medical DICOM file.

![SAM-medical-imaging](https://user-images.githubusercontent.com/37108394/230678827-f53b684c-6bca-491f-9f67-8fd1cd642717.png)

---

### Demo Notebook 📓

This repository provides a demo notebook demonstrating how to use SAM for medical imaging. The notebook includes:

- **Lung CT**: Examples of segmenting lung structures from CT DICOM files.
- **Axial CBCT View**: Examples of segmenting regions of interest in axial CBCT slices.

#### Screenshots from the Demo:

1. **Lung CT Segmentation Example**  
   ![image](https://github.com/user-attachments/assets/a05bc961-6e76-45c9-b7e0-375dd3c72356) 

2. **Axial CBCT Segmentation Example**  
   ![image](https://github.com/user-attachments/assets/6be84080-289a-4ab4-9e88-267f6084d357)   

---

### Shoutout 🎉

A special shoutout to [Mohammed El Amine Mokhtari](https://github.com/amine0110) for his great tutorials on medical imaging and computer vision. His work has been an inspiration and a valuable resource for the community!
