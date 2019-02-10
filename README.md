# Digit-Recognizer
## Requirements
- Python 3.5 +
- Scikit-Learn (latest version)
- Numpy
- pandas
- cv2
- tensorflow 1.3
- Matplotlib 3.0.2
- pillow 5.4.1

### Overview 
- <b>model</b> - contain weights for the CNN
- <b>handwritten_data.zip</b> - contain 20 pictures for each class
- <b>data_augmentation.ipynb</b> - for make augmentation with images from handwritten_data
- <b>data.zip</b> - contain already augmented 700 pictures for each class
- <b>test_loaded_model.ipynb</b> - for see how the model work. Loading model weights from model folder and test on dataset from data folder.
  Train accuracy - 0.989, test accuracy - 0.986
- <b>training.ipynb</b> - contain code to train model. To speed up the learning process was used <b>google colab</b> to train model.
### Usage
1 Clone repository.

2 Unzip <b>data.zip</b> to project folder OR unzip file <b>handwritten_data.zip</b> and run all cells in <b>data_augmentation.ipynb</b> file.

3 To look how the model work open <b>test_loaded_model.ipynb</b> file and run all cells.

### Creating dataset
In the process of creating dataset, 20 examples of pictures for each class were drawn manually.
Further, augmentation of these images was carried out (Rotating, Cropping, Translation), after which 700 images were obtained for each class.
