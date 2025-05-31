DESCRIPTION OF APPROACH:
    1)Load the dataset(nii and dcm) files using nibabel and pydicom
    2)Extraction of metadata from both the files
    3)Visualized image volumes along standard anatomical planes: axial, sagittal, and coronal.
    4)Differences between DICOM and NIfTI

SCREENSHOT OF VISUALISATIONS:
    ![axial slices](https://github.com/user-attachments/assets/15543d32-51ed-4eb9-b715-e624a30a63cb)
    ![Saggital slices](https://github.com/user-attachments/assets/a9c9e1b9-74d6-4beb-a009-3e82cbf855b2)
    ![coronal slices](https://github.com/user-attachments/assets/14dcd9cc-2c76-4988-91ce-de9a2c13ff78)




DATASET FOR DICOM:
    https://www.kaggle.com/datasets/ilknuricke/neurohackinginrimages

CHALLENGES:
    The shape of the dataset(dcm) I used is 22,512,512 so two of the planes have slices of shape 22,512 so the images are looking a bit odd.
    Couldn't figure out how to determine orientation using affine 
