# Face Detection and Recognition using FaceNet PyTorch

This project aims to demonstrate the implementation of face detection and recognition using FaceNet PyTorch MTCNN. The project also employs InceptionResNetV1 as the classification model for the images.


## Installation
In order to run this project, you will need to install the following dependencies:


```
PyTorch
torchvision
facenet-pytorch
numpy
matplotlib
PIL
```

You can install these packages using pip by running the following command:

```
pip install torch torchvision  numpy matplotlib facenet-pytorch PIL
```


## Usage

To use this project, follow these steps:

Clone the repository to your local machine.
Open Jupyter Notebook or any Python IDE of your choice.
Navigate to the cloned repository and open the face_recognition.ipynb notebook.
Run the notebook cell by cell.
The notebook contains detailed explanations and instructions on how to use the implemented code.


## Testing

To test the implementation, you can use the provided test image located in the code folder and your images in datasetfolder. The image features five faces including yours and four other people. The implementation will detect the faces and classify them based on their identity. To test the implementation, simply run the provided notebook.


## Credits

The code for this project is based on the following repositories:

[FaceNet PyTorch](https://github.com/timesler/facenet-pytorch)
