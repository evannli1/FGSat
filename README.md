# FGSat: A New Dataset and Performance Benchmark for Fine-Grained Satellite Classification

## Overview

**FGSat** is the first large-scale benchmark dataset specifically designed for **fine-grained satellite classification**, addressing the critical need for distinguishing between visually similar satellite models in orbital operations such as in-orbit servicing, formation flying, and active debris removal.

## Dataset Specifications

- **Scale**: 60,000 high-fidelity synthetic images (30K RGB + 30K Grayscale)
- **Classes**: 30 satellite types with 2,000 images per class
- **Resolution**: 1920×1080 pixels
- **Annotation**: Automatic bounding box generation
- **Rendering**: Unity Engine integrated Physically-Based Rendering (PBR) technology
- **Imaging Conditions**: Normal, overexposed, out-of-focus, and noise artifact scenarios
- **Data Split**: 70% training, 20% validation, 10% testing

## Satellite Categories

The dataset encompasses 30 distinct satellite models spanning Earth observation and scientific missions:

### Earth Observation Satellites (17 types)

| Satellite | Primary Function |
|-----------|------------------|
| **Aqua** | Global Water Cycle |
| **Aquarius** | Sea Surface Salinity |
| **Aura** | Atmospheric Chemistry & Ozone |
| **CALIPSO** | Clouds & Aerosols |
| **CloudSat** | Cloud Structure & Water Content |
| **GOES** | Weather & Storms |
| **GPM** | Global Precipitation |
| **ICESat-2** | Ice Sheets & Land Elevation |
| **LandSat8** | Land Cover & Vegetation |
| **OCO2** | Atmospheric CO₂ |
| **POES** | Meteorology & Environment |
| **SAC-C** | Land Use & Atmosphere |
| **SeaStar** | Ocean Color & Phytoplankton |
| **Terra** | Land & Climate Change |
| **TOPEX** | Ocean Topography |
| **TDRS** | Data Relay |
| **Tselina-2** | Electromagnetic Observation |

### Scientific Research Satellites (13 types)

| Satellite | Primary Function |
|-----------|------------------|
| **Cluster** | Magnetosphere Dynamics |
| **Double-Star** | Magnetosphere & Plasma |
| **FUSE** | Ultraviolet Astronomy |
| **GLAST** | Gamma-ray Astronomy |
| **Hinode** | Solar Magnetic Fields |
| **ICON** | Ionosphere & Atmosphere |
| **MMS** | Earth Magnetic Reconnection |
| **Polar** | Particles & Ionized Gas |
| **Proba-2** | New Spacecraft Technologies Validation |
| **Swift** | Gamma-ray Bursts |
| **SWAS** | Interstellar Water & Molecules |
| **Tango** | Formation Flying Technology Validation |
| **XMM-Newton** | X-ray Astronomy |

## Imaging Conditions

Each satellite class contains 2,000 images distributed across different imaging scenarios:
- **Standard conditions**: 700 images per class
- **Overexposed**: 100 images per class
- **Out-of-focus**: 100 images per class
- **Noise artifacts**: 100 images per class

## Applications

FGSat enables research in:
- **In-orbit servicing**: Precise satellite identification for robotic operations
- **Formation flying**: Multi-spacecraft coordination and control
- **Active debris removal**: Safe approach and capture of target objects
- **Space situational awareness**: Automated orbital object cataloging

## Citation

If you use this dataset in your research, please cite:

```bibtex
@misc{fgsat2025,
  title={FGSat: A New Dataset and Performance Benchmark for Fine-Grained Satellite Classification},
  author={Yifan Li, Jiayu He and Yang Gao},
  year={2025},
  note={Dataset available at: https://github.com/evannli1/FGSat}
}
```

## License

This dataset is licensed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

For more details, see: https://creativecommons.org/licenses/by/4.0/

---

## Pre-Release Version

A **pre-release version** containing 600 representative samples from standard imaging conditions (20 images per class) is currently available for researchers to conduct rapid evaluation and testing of satellite classification algorithms. The pre-release annotations have also been converted from the original JSON format to the YOLO format, facilitating faster evaluation and experimentation.  
The complete dataset will be released soon.
