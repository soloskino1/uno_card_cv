**Uno Card Recognition – uno\_card\_cv** 

This repository contains Jupyter Notebook files for recognizing Uno cards. 

Video demonstrations can be fine on these links:
Part1: <https://youtu.be/nRWiw0EtqKo>

Part2: <https://youtu.be/k9-xhOXJ6SE>

The repository contains the following Notebooks:

- **hsv\_limits\_app**: For isolating a color in an image and getting the lower and upper HSV limits of the color for better identification.
- **Uno\_card**: The main program for Uno card recognition.

The program performs three main functions:

1. Creating a dataset from images
1. Training a random forest classifier
1. Uno card recognition in an image or folder or on camera

**Requirements**

To use the **uno\_cv** repository, you need to install OpenCV-Python (**cv2**) for image processing and computer vision tasks. Other libraries/modules used are:

- **os**: to iterate through the images in a folder
- **numpy**: to deal with large arrays
- **pickle**: to save and load the trained machine learning model
- **sklearn**: the main library used for building the machine learning model
- **tkinter**: used to open the file and folder directory
- **glob**: provides a way to generate lists of files that match a specified pattern
- **pandas**: provides fast, flexible, and expressive data structures designed to work with relational or labeled data both easily and intuitively
- **matplotlib**: a plotting library for the Python programming language
- **sklearn**: a machine learning library for Python, which provides tools for classification and regression
- **IPython.display**: provides a way to display rich media such as HTML, Markdown, images, and videos in the Jupyter Notebook.

**Usage**

To use this repository:

1. Download or clone the repository.
1. Run all the cells in the **Uno\_card.ipynb** notebook.
1. Follow the prompts in the output cell.

References:
https://stackoverflow.com/questions/10948589/choosing-the-correct-upper-and-lower-hsv-boundaries-for-color-detection-withcv
https://pyimagesearch.com/2021/05/12/opencv-edge-detection-cv2-canny/#:~:text=The%20Canny%20edge%20detector%20is%20a%20multi%2Dstep%20algorithm%20used,Computational%20Approach%20to%20Edge%20Detection.
https://pyimagesearch.com/2021/01/19/opencv-bitwise-and-or-xor-and-not/
towardsdatascience.com/hyperparameter-tuning-the-random-forest-in-python-using-scikit-learn-28d2aa77dd74
https://github.com/CiprianFlorin-Ifrim/uno_recognition_computervision
datacamp.com/tutorial/random-forests-classifier-python
https://opencv24-python-tutorials.readthedocs.io/en/latest/py_tutorials/py_feature2d/py_shi_tomasi/py_shi_tomasi.html
https://stackoverflow.com/questions/10592605/save-classifier-to-disk-in-scikit-learn
-----

