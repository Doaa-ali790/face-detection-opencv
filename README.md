# Face Detection with OpenCV

A simple project to detect faces using **OpenCV** and **Jupyter Notebook**.

## Project Description
This project reads an image and detects all faces in it using a **Haar Cascade** model.  
It draws green rectangles around each detected face and shows the total number of faces.

## Requirements
- Python 3
- OpenCV
- Matplotlib
- Jupyter Notebook

## How to Run
1. Open the file `face_detection.ipynb` in Jupyter Notebook.
2. Run the cells step by step.
3. You will see the detected faces with green rectangles and the total count.

## Files Included
- `face_detection.ipynb` : Notebook with the face detection code.
- `haarcascade_frontalface_default.xml` : Haar Cascade model for face detection.
- Any image (.jpg/.png) for testing the code.

## Notes
- Make sure the image file is in the same folder as the Notebook or update the path in the code.
- You can adjust `scaleFactor` and `minNeighbors` to change the detection sensitivity.
