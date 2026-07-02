# Annotation Format

The annotations of the dataset follow the YOLO bounding-box format.

Each image has a corresponding annotation file with the same file name and a `.txt` extension. Each row in an annotation file represents one object instance.

## Format

Each annotation row follows the format below:

| Field | Description |
|---|---|
| class_id | Object category ID |
| x_center | Normalized x-coordinate of the bounding-box center |
| y_center | Normalized y-coordinate of the bounding-box center |
| width | Normalized bounding-box width |
| height | Normalized bounding-box height |

The coordinates are normalized by the image width and height, so all coordinate values are between 0 and 1.

## Class Definition

| Class ID | Category |
|---|---|
| 0 | fire |
| 1 | smoke |

## Example

An annotation file may contain rows such as:

| class_id | x_center | y_center | width | height |
|---|---:|---:|---:|---:|
| 0 | 0.5123 | 0.4387 | 0.1245 | 0.0962 |
| 1 | 0.6421 | 0.3519 | 0.2764 | 0.1885 |

In this example, the first row represents a fire object, and the second row represents a smoke object.

The complete YOLO-format annotation files will be released in this repository after the manuscript is formally accepted for publication. Before public release, the necessary annotation files can be provided to the Editorial Office or reviewers upon reasonable request for internal editorial or review purposes.
