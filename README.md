<p align="center">
  <img src="https://raw.githubusercontent.com/MahyarGarshasbi/3D-PMWPrecipitation/main/Figures/Fig03.png" width="850">
</p>

---

# Multi-spectral 3-D Encoding for Passive Microwave Extreme Precipitation Retrievals
**Mahyar Garshasbi**, **Buddha Subedi**, **Ardeshir Ebtehaj**, and **George J. Huffman**

*Saint Anthony Falls Laboratory, Department of Civil, Environmental, and Geo-Engineering, University of Minnesota*

---

## Abstract
Deep learning methods for retrieving precipitation from passive microwave satellite observations commonly encode radiometric channels as stacked 2-D feature maps, allowing spectral information to be mixed across channels but not explicitly preserving spectral structure as a convolutional dimension. Such an encoding can underutilize the spectral coherence of microwave observations, which capture complementary signatures ranging from low-frequency emission from liquid hydrometeors to high-frequency scattering by ice particles throughout the atmospheric column. This study examines whether 3-D convolutional encoding of multispectral observations from the Global Precipitation Measurement (GPM) Microwave Imager improves near-surface precipitation retrievals. Using otherwise identical U-shaped encoder–decoder architectures trained against ground-based radar observations, we isolate and compare the effects of 2-D and 3-D convolutional encoding. Results show that 3-D encoding improves retrieval of surface precipitation rates, with the largest gains occurring in the upper tail of the precipitation distribution and during extreme events. For the unseen Hurricanes Milton and Ida, the 3-D architecture recovers more than 6,600 km² of precipitation exceeding 16 mm hr⁻¹ relative to its 2-D counterpart. Across all test storms, the 3-D encoding increases the chance of retrieving rainfall rates greater than 64 mm hr⁻¹ by 10% and reduces distributional similarity to the reference radar observations by 38%, as measured by the Wasserstein distance.

---

## Code Availability
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Xj4AlvYSF5nIfrCL68XSCH_JDoirzWgs?usp=sharing)


---

## Contact
📧 garsh011@umn.edu
