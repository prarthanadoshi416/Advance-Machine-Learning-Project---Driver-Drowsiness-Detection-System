# Driver Drowsiness Detection System


<!-- ## Getting Started -->
_Attention- This project will require a system with a camera_
## Instructions to execute the program: 

1. Go to the given google drive link.

2. Download the zipped file 'Download_execute_DDDS' given in the folder and extract all the files.

3. From the zipped files upload the .ipynb file to jupyter notebook.

4. Import all the necessary libraries if not installed: tensorflow, sys ,opencv, numpy , pylab, matplotlib , scipy, pylab , pillow , time.

5. Change the path of the BestModel folder which is a part of the zipped file to the local path saved in the user's computer. This is stored in the variable 'model_import' in the jupyter file.

6. Path of the Haar cascade files to be used for face, eye detection are as follows:

    * Face Detection - This is stored in the variable cascade_face and the required file for this is: haarcascade_frontalface_default.xml
    
    * Eye Detection - This is stored in the variable cascade_eyes and the required file for this is: haarcascade_eye_tree_eyeglasses.xml

    These files haves to be downloaded to the local system and the corresponding local path should be given to the variable cascade_face and cascade_eyes.


7. Run all the cells of the jupyter file by going to Cell -> Run All.

8. This will turn on the web cam  and a screen will pop up that will start with the detection and the result of the detection will be declared in the bottom left corner of this screen.