# FLORA: FLEX Leaf Observation and Retrieval via Hybrid Machine Learning Approaches

**FLORA** is a multi-sensor calibration and validation (Cal/Val) framework supporting **ESA’s FLEX mission**, targeting:

-   **FLEX Level-2B**: Sun-Induced Fluorescence (**SIF**).

-   **FLEX Level-2C** vegetation products: **LCC, LAI, LCARC, fPAR**.

The project integrates **field sampling**, **UAV campaigns**, **eddy covariance flux towers**, **radiative transfer modelling**, and **multi-sensor satellite observations** to quantify spatial heterogeneity and enable robust upscaling to the **FLEX 300 m footprint**.

## Why FLORA?

Vegetation controls carbon and water cycles across scales, and **FLEX SIF provides a direct optical link to photosynthetic activity**, bridging plant physiology with ecosystem-scale carbon fluxes (e.g., **GPP**).

## Study sites

FLORA is designed around **four contrasting European ecosystems**, including ICOS reference infrastructure:

**Netherlands**

-   **NL-Loobos** (ICOS Scots pine forest; continuous eddy covariance fluxes)

-   **Speulderbos** (mixed temperate forest; complementary forest scaling site)

-   **NL-Cabauw** (ICOS managed grasslands)

**Italy**

-   **Lombardy alfalfa cropland sites** (biotic stress test sites; linked to multi-crop stress context)

## Validation concept and multi-scale workflow

FLORA uses a **multi-scale validation strategy**, moving from leaf/canopy measurements to hyperspectral satellite observations and finally to **FLEX-scale (300 m) validation**.

Key components:

-   **Field campaigns** to measure biochemical and structural traits (e.g., chlorophyll, LAI, water content, leaf physiology).

-   **Aerial campaigns (UAV)** for high-resolution hyperspectral/thermal mapping and scaling.

-   **Satellite synergy** for spatial/temporal context and scaling: Sentinel-2, EnMAP, PRISMA, FLEX, TROPOMI, GOME-2.

-   **Physically-based modelling** (RTMs) and hybrid inversion approaches to retrieve traits consistently across sensors.

-   **Flux-tower linkage (ICOS)** to analyse footprint effects and connect SIF to ecosystem GPP.

## ESU-based sampling design (Elementary Sampling Units)

To support statistically robust field design and upscaling, FLORA defines **Elementary Sampling Units (ESUs)** to quantify spatial variability (e.g., NDRE / red-edge metrics, PRI), identify homogeneous zones within each **300 m FLEX pixel**, and guide aerial/field sampling strategies in heterogeneous landscapes.

## Synergy with HYDRA-EO (ESA)

Several methodological components developed in FLORA are aligned with and reusable for **HYDRA-EO**, including: - ESU-based sampling design for heterogeneous landscapes - Multi-sensor scaling (UAV → hyperspectral satellites → FLEX 300 m) - Hybrid RTM–ML retrieval concepts for vegetation traits and physiology - SIF-informed assessment of photosynthetic function for robust validation

HYDRA-EO workflow repository: <https://github.com/CCGCAM/HYDRA-EO-workflow>

[HYDRA-EO website](https://ccgcam.github.io/HydraEO/)

## Citation

If you use **ToolsRTM** and **SCOPEinR** packages, please cite the following references:

Camino et al., (2024). RT-Simulator: An Online Platform to Simulate Canopy Reflectance from Biochemical and Structural Plant Properties Using Radiative Transfer Models, *IGARSS 2024 - 2024 IEEE International Geoscience and Remote Sensing Symposium*, Athens, Greece, 2024, pp. 2811-2814, [doi: 10.1109/IGARSS53475.2024.10642442](https://ieeexplore.ieee.org/document/10642442).

Arano et al., (2024). Enhancing Chlorophyll Content Estimation With Sentinel-2 Imagery: A Fusion of Deep Learning and Biophysical Models, *IGARSS 2024 - 2024 IEEE International Geoscience and Remote Sensing Symposium*, Athens, Greece, 2024, pp. 4486-4489, [doi: 10.1109/IGARSS53475.2024.10641613](https://ieeexplore.ieee.org/document/10641613).

Camino et al., (in prep). Integrating physiological plant traits with Sentinel-2 imagery for monitoring gross primary production and detecting forest disturbances.

### License

[![](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

The **ToolsRTM** and **SCOPEinR** package is licensed under the MIT License, allowing for free use, modification, and distribution. This package is available on GitLab, and we encourage contributions and collaborations from the community. For more details, please refer to the LICENSE file in the repository.
