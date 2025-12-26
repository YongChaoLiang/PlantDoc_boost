# PlantDoc_boost (Under Curation)

This repository is associated with our paper:

**A Wavelet-Based Frequency-Domain Approach for Accurate Multi-Crop Disease Detection**

and the proposed model **WGA-YOLO**.

To ensure responsible reuse, we are currently conducting a thorough **license audit**, **per-image provenance/attribution completion**, and **annotation quality verification**. Therefore, the full dataset is temporarily **not publicly released** in this repository.

## Current Status
We are finalizing the dataset package with the following steps:
- License audit and provenance tracking (per-image source URL, author/uploader, license type, license URL, retrieval date).
- Data curation (quality filtering, class mapping, and de-duplication).
- YOLO-format annotation verification and quality checks (e.g., spot-checking / reviewer-facing summaries).

## Planned Release
Upon acceptance/publication of the paper, we plan to release the finalized dataset version, including (subject to final verification):
- A complete README (data sources, licensing, selection/curation criteria, annotation protocol, dataset split).
- YOLO-format annotations
- Versioning and changelog.

## Annotation Format (Planned)
The dataset will be released in **YOLO format**:
`<class_id> <x_center> <y_center> <width> <height>` (normalized to [0,1]).

## Data Sources & Licensing (Preliminary)
The additional images used to construct PlantDoc_boost are collected from publicly available resources (e.g., **Wikimedia Commons**). We will only include images with clear open licenses that allow redistribution and adaptation (e.g., **CC BY-SA 3.0**), and we will provide **per-image attribution and licensing metadata** in the final release.

Before the final release, please do not treat this repository as a redistributable dataset package.

## Citation
If you use this work in your research, please cite our paper:
- <To be updated after acceptance/publication>
