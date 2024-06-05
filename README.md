# Face Detection using VGG16

This project implements a face detection model using transfer learning with the VGG16 architecture. The project leverages TensorFlow, Keras, OpenCV, and Albumentations for building, training, and evaluating the model. Image annotations are handled using Labelme.


## Prerequisites

Ensure you have the following libraries installed:

- TensorFlow
- Keras
- OpenCV
- Albumentations
- Labelme

You can install all required libraries using the `requirements.txt` file:

```sh
pip install -r requirements.txt
```

## Usage

1. **Annotate Images**:
   - Use Labelme to annotate your images.

2. **Data Augmentation**:
   - Utilize the Albumentations library for data augmentation to enhance the dataset.

3. **Training, Testing, Evaluation**:
   - Ensure that your dataset is properly organized in the relevant directories.
   - Use the `FaceDetection.ipynb` notebook in the `notebooks` directory to train the model.


## Running the Script

To use the model, simply run:

```sh
python face.py
```


## License

This project is licensed under the MIT License.
