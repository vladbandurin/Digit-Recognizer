# Digit-Recognizer
## Классификатор римских цифр от 1 до 8, используя TensorFlow.
## Requirements
- Python 3.5 +
- Scikit-Learn (latest version)
- Numpy
- pandas
- cv2
- tensorflow 1.3
- Matplotlib 3.0.2
- pillow 5.4.1

### Usage
1 Clone repository.

2 Unzip <b>data.zip</b> to project folder OR open and run all cells in <b>data_augmentation.ipynb</b> file.

3 To look how the model work open <b>test_loaded_model.ipynb</b> file and run all cells.

### Creating dataset
In the process of creating dataset, 20 examples of pictures for each class were drawn manually.
Further, augmentation of these images was carried out (Rotating, Cropping, Translation), after which 700 images were obtained for each class.
