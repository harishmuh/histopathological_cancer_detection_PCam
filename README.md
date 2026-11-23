# Histopathological Cancer Detection PCam

**- This repository is still under construction.**

### Dataset Source



* This project uses the **PatchCamelyon (PCam) dataset**, a histopathology image classification benchmark derived from the Camelyon16 challenge (Veeling et al., 2018).

* PCam consists of 96 × 96 pixel RGB image patches extracted from H&E-stained whole-slide images of lymph node sections. Each image carries a binary annotation indicating the presence or absence of metastatic tumour tissue within the central 32 × 32 pixel region.

![images](https://github.com/basveeling/pcam/blob/master/pcam.jpg)

*Image Credit: Bas Veeling*

* This project uses the **duplicate-filtered version of PCam** distributed through the *Histopathologic Cancer Detection* dataset. This version retains the original PCam image dimensions and classification task while excluding duplicate images present in the original dataset release.

**Dataset documentation:** https://github.com/basveeling/pcam

**Original publication:** 

Veeling, B. S., Linmans, J., Winkens, J., Cohen, T., & Welling, M. (2018). Rotation Equivariant CNNs for Digital Pathology.

