# Dicom-to-STL
1-This project takes MRI or CT scan raw *.dicom files as an input then it transform it to a visible picture in Hounsfield scale.It is done via pydicom package. It creates a 3D image which is useful for better visualization of 3D dicom data. Next it builds a 3d model based on the slices data. Older version of this project is written in python 2.7 but Now It is updated as per python 3 

2-STL Exporting : This STL exporting is done via VTK. In this project we have to specify the path of dicom files and then scripts will be run to create a STL file from CT data. The front and side views are also generated for instant visualisation. The STL file created is further viewed by any STL viewer.

3- 3D Innovators : This is a website which enables user friendly interface for non programmers.  User can add dicom data directly in this website and the created STL file is generated within few minutes and is ready for download. It uses django as a backend and HTML, Bootstrap as a frontend.

4-Post-processing : The post processig can be done by using diffrent softwares like blender and meshmixer. 
Blender: It is used for smoothening of STL file and removing unwanted extra materials.
Meshmixer: It is used to remove defects which may arise in 3D printing of created STL file. after this sep our STL file is ready for 3D printing.

# Further Work
Currently postprocessing is done through blender and adobe meshmixer. This also can be automated which will geberate a fully automated program in which user adds dicom files and will get final STL(free from any defects) file which is ready for 3D printng.

The code for 3D visualizaton of dicom files is based on the following tutorial:
https://www.raddq.com/dicom-processing-segmentation-visualization-in-python/

#Note :
Due to github's limitation on large files I couldn't upload the *.npy and STL Output files however you can generate them using the provided data.
