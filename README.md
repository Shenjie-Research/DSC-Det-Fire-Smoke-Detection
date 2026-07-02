**“DSC-Det: A Detail–Scale–Context Detection Network for Forest-Fire-Oriented Early Fire and Smoke Detection in UAV-View and Complex-Background Imagery”**

The manuscript proposes DSC-Det, a lightweight one-stage detection network for early fire and smoke detection under UAV-view and complex-background conditions.

## Repository Status

This repository has been created to support the transparency and reproducibility of the submitted manuscript. At the current submission stage, the repository provides the data availability information, dataset description, annotation format, and planned release arrangement.

The complete dataset and related supporting files will be made publicly available in this repository after the manuscript is formally accepted for publication.

If required by the Editorial Office or reviewers during the evaluation process, the necessary data files can be provided for internal editorial or review purposes.

## Dataset Description

The dataset used in this study is a constructed forest-fire-oriented fire and smoke detection dataset for bounding-box object detection. It contains two object categories: fire and smoke.

The dataset consists of 4178 images collected and organized from multiple public fire- and smoke-related image sources, including BoWFire, FLAME, FASDD_UAV, and Smoke_segmentation. The images cover different visual conditions, such as UAV-view fire and smoke scenes, small fire targets, weak or diffuse smoke regions, fire–smoke coexistence, and complex-background interference.

All annotations are converted into YOLO-format bounding boxes. The dataset is divided into training, validation, and test subsets for model training and evaluation:

train: 3342 images
val:   417 images
test:  419 images
total: 4178 images

## Planned Release Content

After the manuscript is formally accepted for publication, this repository will release the following materials:

```text
dataset/
├── images/
│   ├── train/
│   ├── val/
│   └── test/
├── labels/
│   ├── train/
│   ├── val/
│   └── test/
├── splits/
│   ├── train.txt
│   ├── val.txt
│   └── test.txt
├── data.yaml
└── README_dataset.md
