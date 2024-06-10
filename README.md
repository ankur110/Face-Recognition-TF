
# Face Recognition with MTCNN, OpenCV, VGG-Face2, and Siamese Model

This repository contains the code and resources for face recognition model.


## Key Features

This project implements a face recognition system using several powerful techniques:

__1.__ __MTCNN Face Detection:__

* Utilizes MTCNN (Multi-task Cascaded Convolutional Networks) for accurate and efficient face detection in images.

__2.__ __FaceNet:__
* Generates face embeddings using the pre trained Facenet model implemented in Tensorflow, capturing distinctive features of each face.

__3.__ __Siamese Model for Recognition:__
* Implements a Siamese neural network for face recognition, comparing and matching face embeddings to identify individuals.

__4.__ __OpenCV Bounded Boxes:__
* Uses OpenCV to draw bounding boxes around detected faces in images, providing a visual representation of face localization.

__5.__ __Python Dictionary for Storage:__
* Utilizes a Python dictionary to store face embeddings, associating each person's name with their corresponding embedding for easy retrieval.

__6.__ __Model Training and Recognition Workflow:__
* Provides a seamless workflow for training the face recognition model using the generated embeddings and subsequently recognizing faces in new images.

## If you see 'Unable to render code block':
* ## __Please download the Notebook__


## Prerequisites and Dependencies

Before running the code, ensure you have the following dependencies installed:

- OpenCV (`opencv-python`)
- NumPy (`numpy`)
- Matplotlib (`matplotlib`)
- Tensorflow (`tensorflow`)
- Keras-Facenet (`facenet`)
- MTCNN (`mtcnn`)

**Installation using pip:**

```bash
pip install opencv-python numpy matplotlib tensorflow mtcnn keras_facenet
```


