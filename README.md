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
В процессе создания датасета были нарисованы в ручную по 20 примеров картинок на каждый класс.
Далее была проведена аугментация этих изображений (Rotating, Cropping, Translation), после чего было получено по 700 изображений на каждый класс.
