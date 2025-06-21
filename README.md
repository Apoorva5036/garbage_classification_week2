# garbage_classification_week1

🗂️ Dataset
The dataset used for this project is a garbage classification dataset, consisting of images categorized into multiple classes such as glass, plastic, paper, metal, organic, and cardboard. Due to size limitations on GitHub, the dataset has been uploaded in organized batches within a dataset/ directory, with each class stored in its own subfolder.

📓 Google Colab Notebook
The Google Colab notebook provided in this repository is used to clone the dataset from GitHub and preprocess the images. This includes resizing all images to 260×260 pixels for compatibility with the EfficientNetV2B2 model, normalizing pixel values, and splitting the dataset into training and validation sets. The notebook also implements TensorFlow’s efficient data pipeline using prefetching for faster model training.
