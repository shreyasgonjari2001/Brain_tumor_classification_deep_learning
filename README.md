Key Features
Data Pipeline:

Utilized tf.data.Dataset for fast, scalable image loading and preprocessing (resizing, normalization, augmentation).

Model Architecture:

Used ResNet-based Transfer Learning with pre-trained weights (e.g., ResNet50).

Fine-tuned the top layers for high accuracy on tumor classification.

Training & Evaluation:

Implemented early stopping and learning rate scheduling.

Achieved high accuracy and generalization on validation/test sets.

Tech Stack
TensorFlow 2.x

Keras (ResNet50)

tf.data for preprocessing pipeline

Python (NumPy, Matplotlib)

Outcome
Successfully built an end-to-end deep learning pipeline for accurate classification of brain tumor X-ray images, demonstrating the effectiveness of transfer learning and efficient data handling.
