# Release Plan

This repository has been created to support the submitted manuscript and to provide a clear release plan for the dataset and supporting files.

## Current Stage

At the current submission stage, this repository provides:

- dataset description;
- data availability information;
- annotation format description;
- planned release arrangement.

The complete dataset and supporting files have not yet been publicly released at this stage.

## Planned Public Release

After the manuscript is formally accepted for publication, the complete dataset and supporting files will be made publicly available in this repository.

The planned repository structure after release will be:

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

The released materials will include:

- the complete image dataset used in the experiments;
- YOLO-format bounding-box annotation files;
- training, validation, and test split files;
- dataset configuration file;
- preprocessing and annotation description;
- source dataset information.

## Access During Review

Before public release, the necessary data files can be provided to the Editorial Office or reviewers upon reasonable request for internal editorial or review purposes.
