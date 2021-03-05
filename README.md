# Medical_Dicom_3D
1-This project takes MRI or CT scan raw *.dicom files as an input then it transform it to a visible picture in Hounsfield scale.
Next it builds a 3d model based on the slices data. Older version of this project is written in python 2.7 but Now It is updated as per python 3 

2-STL Exporting : A 3d printable model export feature will be added to enable the users
to print a real size replica of the organ for educational and medical purposes
This STL exporting is done via VTK. The STL file created is further viewed by any STL viewer.

# Further Updates List:
1-Front End: A GUI will added to enable user frindely usages for non-programmers

2-The postprocessing is done through blender and adobe meshmixer. This will summarize our final 3D STL file. which is ready for 3D printing.

The code for 3D visualizaton of dicom files is based on the following tutorial:
https://www.raddq.com/dicom-processing-segmentation-visualization-in-python/

#Note :
Due to github's limitation on large files I couldn't upload the *.npy and STL Output files however you can generate them using the provided data.
