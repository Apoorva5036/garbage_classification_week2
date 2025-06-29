# garbage_classification_week1

🗂️ Dataset = 
The dataset used for this project is a garbage classification dataset, containing images categorized into multiple classes such as glass, plastic, paper, metal, organic, and cardboard. Due to file size constraints, the dataset is organized into class-specific subfolders under the dataset/ directory. Each folder represents a single class of garbage.

📓 Google Colab Notebook = 
The Google Colab notebook provided in this repository is used to clone the dataset from GitHub and prepare it for training. It resizes all images to 260×260 pixels to ensure compatibility with the EfficientNetV2B2 model and splits the dataset into training and validation sets using TensorFlow’s image_dataset_from_directory utility. Data augmentation techniques such as flipping, rotation, zoom, and translation are applied to improve generalization. The notebook also normalizes pixel values to the [0, 1] range and constructs a model based on EfficientNetV2B2 with custom classification layers. The model is compiled and training is initiated with callbacks like early stopping and model checkpointing. TensorFlow’s prefetching mechanism is used to optimize the data pipeline for efficient training.
