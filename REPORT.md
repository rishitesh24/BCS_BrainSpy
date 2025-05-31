DESCRIPTION OF APPROACH:
    1)Load the dataset(nii and dcm) files using nibabel and pydicom
    2)Extraction of metadata from both the files
    3)Visualized image volumes along standard anatomical planes: axial, sagittal, and coronal.
    4)Differences between DICOM and NIfTI

SCREENSHOT OF VISUALISATIONS:
    ![axial_slices](https://github.com/user-attachments/assets/e49b1228-500b-4400-ba80-eff03040c536)
    ![saggital_slices](https://github.com/user-attachments/assets/a5f0e10a-bb23-4084-9038-e0612814ff5d)
    ![coronal slices](https://github.com/user-attachments/assets/e2ac2407-40ac-4833-a3a9-a11da5e8e6c5)

DATASET FOR DICOM:
    https://www.kaggle.com/datasets/ilknuricke/neurohackinginrimages

CHALLENGES:
    The shape of the dataset(dcm) I used is 22,512,512 so two of the planes have slices of shape 22,512 so the images are looking a bit odd.
    Couldn't figure out how to determine orientation using affine 
