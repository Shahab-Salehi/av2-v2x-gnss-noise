# V2X-Augmented Argoverse 2 Dataset

## Overview
This repository hosts a modified version of the [Argoverse 2 (AV2) Motion Forecasting Dataset](https://argoverse.github.io/user-guide/argoverse_2.html). 

To support research in robust trajectory prediction, we have extended the original AV2 dataset by introducing support for Vehicle-to-Everything (V2X) communication environments. Furthermore, we have modeled and applied realistic V2X noise—specifically introducing typical GNSS error of V2X messages and perception errors.

## Dataset Availability
**Status: Coming Soon**

The full dataset is currently being prepared for public release and will be linked here shortly. To enable comprehensive evaluation and comparative studies, we will publish two distinct versions:
*   **Clean Version:** V2X-supported data without added noise.
*   **Noisy Version:** V2X-supported data with applied GNSS and perception noise.

## Technical Methodology
*(Detailed documentation regarding the methodology will be added here prior to the dataset's release.)*

**Upcoming details will include:**
*   Mechanisms and criteria for determining when an object is detected via V2X.
*   Parameters and statistical distributions used for the applied GNSS and perception noise.

## License
This modified dataset is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0), in accordance with the original Argoverse 2 dataset terms. See the `LICENSE` file for more details.
