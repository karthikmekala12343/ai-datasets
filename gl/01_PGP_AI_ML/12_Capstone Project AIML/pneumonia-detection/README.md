# AI Dataset Pneumonia Detection

This repository contains metadata for a chest X-ray pneumonia-detection dataset. The image archives can be downloaded from the [dataset folder on MediaFire](https://www.mediafire.com/folder/iuap7l4gcqsp4/ai-dataset-pneumonia-detection).

## Repository contents

| File | Description |
| --- | --- |
| `stage_2_train_labels.csv` | Training labels with `patientId` and binary `Target` columns. |
| `stage_2_detailed_class_info.csv` | Detailed class for each `patientId`, in the `class` column. |
| `LICENSE` | MIT license for this repository's applicable code and materials. |

The label CSV currently contains 5,336 records: 4,134 with `Target` 0 and 1,202 with `Target` 1. The detailed class file contains 1,770 `Normal`, 2,364 `No Lung Opacity / Not Normal`, and 1,202 `Lung Opacity` records.

## Downloading the images

1. Open the [MediaFire dataset folder](https://www.mediafire.com/folder/iuap7l4gcqsp4/ai-dataset-pneumonia-detection).
2. Download the image archive(s) provided there.
3. Extract them locally, keeping the image files available alongside the CSV metadata. The CSV files reference records by `patientId`.

Image archives are not currently present in this working copy. Archive contents and names are determined by the linked download folder.

## Notes

- `Target` is the binary training label; the detailed class CSV provides the corresponding descriptive categories.
- Dataset licensing and usage terms are determined by the dataset provider. The repository's MIT license does not grant rights to the separately hosted dataset.
- This dataset is intended for research and educational use, not for medical diagnosis or treatment decisions.
