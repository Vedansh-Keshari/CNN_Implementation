# CNN_Implementation
CNN Implementation is a collection of three image-classification projects built with Convolutional Neural Networks (CNNs) in Python, using TensorFlow/Keras, OpenCV and Matplotlib. Each project sits in its own folder with its Jupyter notebook, dataset and test images, and follows the same workflow: data loading and cleaning, preprocessing, model building, training, evaluation and testing on new images.

1. DOG_CAT: a binary classifier that identifies whether an image shows a dog or a cat, and also checks predictions on custom test images.
2. HANDWRITEEN_DIGITS: a digit-recognition project that classifies handwritten digit images, a classic CNN benchmark for learning how convolutional layers pick up shapes and strokes.
3. ZOO_ANIMALS: a multi-class classifier that recognises different zoo animal species from images, extending the same approach to many categories.

*The folder is built to be reused. Every notebook has the same path-setup cell and the same layout (code and dataset side by side, with data on Google Drive and code on GitHub). A new project can be added by creating a new sub-folder, dropping in a dataset and copying an existing notebook as a starting template. The same structure can later support more advanced work such as data augmentation, transfer learning with pretrained models (e.g. MobileNet or ResNet), larger multi-class datasets, model comparison and deployment as a simple web or mobile app.*
