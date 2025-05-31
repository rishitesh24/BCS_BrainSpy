DESCRIPTION OF APPROACH:
    1)Load the dataset(nii and dcm) files using nibabel and pydicom
    2)Extraction of metadata from both the files
    3)Visualized image volumes along standard anatomical planes: axial, sagittal, and coronal.
    4)Differences between DICOM and NIfTI

SCREENSHOT OF VISUALISATIONS:
    ![axial slices](image-1.png)
    ![saggital slices](image-2.png)
    ![coronal slices](image-3.png)

DATASET FOR DICOM:
    https://www.kaggle.com/datasets/ilknuricke/neurohackinginrimages

CHALLENGES:
    The shape of the dataset(dcm) I used is 22,512,512 so two of the planes have slices of shape 22,512 so the images are looking a bit odd.
    Couldn't figure out how to determine orientation using affine 