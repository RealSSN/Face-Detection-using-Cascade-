# Face-Detection-with-OpenCV-and-dlib
This Python code utilizes OpenCV, dlib, and matplotlib to perform face detection using the Haar Cascade algorithm. Additionally, it detects eyes and smiles within the detected faces. The code takes an image file as input, applies the cascades, and displays the result with the boxes around the detected faces, eyes, and smiles.

## Prerequisites:
* Python 3.x
* OpenCV (cv2) library
* Matplotlib library (plt)
* dlib library
* imutils library

Make sure to install the required libraries by running:

`pip install opencv-python matplotlib dlib imutils`

## Usage

### Clone the repository:

`git clone https://github.com/RealSSN/Face-Detection-using-Cascade.git`


### Navigate to the project directory:

`cd Face-Detection-using-Cascade`


### Use the face function by importing it into your script or running it in an interactive Python environment:

`from face_detection import face`

`image_path = 'path/to/your/image.jpg'
face(image_path)`

Ensure that you replace 'path/to/your/image.jpg' with the actual path to your image file.

## Cascades

### The code uses the following pre-trained Haar Cascade classifiers:

* haarcascade_frontalface_default.xml for face detection
* haarcascade_eye.xml for eye detection
* haarcascade_smile.xml for smile detection

## Parameters

The **face** function takes a single parameter:

* n: The path to the image file for face detection.

Feel free to modify and enhance the code according to your needs. Contributions and suggestions are welcome!
