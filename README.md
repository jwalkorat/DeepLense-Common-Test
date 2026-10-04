# DeepLense Common Test (practice)

My practice solution for the ML4SCI DeepLense (GSoC 2026) Common Test. Work in progress.

The task is to classify strong-lensing images into 3 classes: no substructure,
subhalo, and vortex. The score is the ROC curve and AUC.

The test is described on the [DeepLense project page](https://ml4sci.org/gsoc/projects/2026/project_DEEPLENSE.html).

## Files
- `common_test_1_classification.ipynb` - the main notebook

## Dataset
Not included here. Download it from the link in the test document and unzip it so
the folders look like this:

    dataset/dataset/train
    dataset/dataset/val

## Status
Dataset and dataloaders are done. Model training and evaluation are next.