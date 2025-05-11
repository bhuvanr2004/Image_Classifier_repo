# Image_Classifier_repo
"A CNN-based image classifier using TensorFlow and Keras to distinguish between cats and dogs. Includes data augmentation, training/validation plots, and performance evaluation on test images. Dataset is auto-downloaded and works in both Colab and local environments."

 Features:
Built with Conv2D, MaxPooling2D, Dense, and Dropout layers

Uses ImageDataGenerator for data augmentation

Plots training/validation accuracy and loss

Predicts labels for unseen test images

Evaluates performance against a 63% accuracy threshold

📁 Dataset:
The dataset is automatically downloaded from FreeCodeCamp’s CDN (cats vs dogs images). In non-Colab environments, it uses a requests-based download method with headers to avoid HTTP 403 errors.

🚀 Technologies Used:
Python

TensorFlow 2.x

Keras

Matplotlib

NumPy

Requests (for dataset download)
