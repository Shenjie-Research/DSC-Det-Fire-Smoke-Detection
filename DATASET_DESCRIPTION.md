# Dataset Description

The dataset used in this study is a constructed forest-fire-oriented fire and smoke detection dataset for bounding-box object detection. It is designed to evaluate early fire and smoke detection under UAV-view and complex-background conditions.

## Categories

The dataset contains two object categories:

| Class ID | Category |
|---|---|
| 0 | fire |
| 1 | smoke |

## Dataset Scale

The dataset consists of 4178 images and is divided into training, validation, and test subsets.

| Subset | Number of Images |
|---|---:|
| Train | 3342 |
| Validation | 417 |
| Test | 419 |
| Total | 4178 |

## Data Sources

The dataset was collected and organized from multiple public fire- and smoke-related image sources, including:

- BoWFire
- FLAME
- FASDD_UAV
- Smoke_segmentation

These sources provide different fire and smoke appearances, viewpoints, and background conditions, which help construct a more challenging evaluation dataset for early fire and smoke detection.

## Visual Conditions

The dataset covers different visual conditions, including:

- UAV-view fire and smoke scenes;
- small fire targets;
- weak or diffuse smoke regions;
- fire-smoke coexistence;
- complex-background interference;
- fire-like or smoke-like visual distractions.

The dataset was constructed to evaluate early fire and smoke detection under challenging visual conditions, rather than to represent a single-source or single-scene dataset.

## Annotation and Split

All annotations are converted into YOLO-format bounding boxes. Each image has a corresponding annotation file, and the dataset is divided into training, validation, and test subsets for model training and evaluation.

The complete images, YOLO-format annotations, split files, and dataset configuration file will be released in this repository after the manuscript is formally accepted for publication.

Before public release, the necessary data files can be provided to the Editorial Office or reviewers upon reasonable request for internal editorial or review purposes.
