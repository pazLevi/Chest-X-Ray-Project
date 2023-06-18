
# Chest X-Ray Pneumonia Image Classification

This project focuses on developing a computer vision model using chest X-ray images to accurately classify pneumonia-positive and pneumonia-negative cases, employing data preprocessing

![image](https://github.com/pazLevi/Chest-X-Ray-Project/assets/50837824/7e029086-eae2-436e-8531-bb9acc0b439f)


## Dataset

The dataset used for this project consists of Chest X-Ray images of pediatric patients from Guangzhou Women and Children’s Medical Center. The dataset is organized into three folders: train, test, and val, with separate subfolders for the Normal and Pneumonia categories.

## Prerequisites

- Python 3.x
- PyTorch
- NumPy
- pandas
- Matplotlib
- OpenCV
- scikit-learn
- tqdm

## Getting Started

1. Clone the repository:
git clone https://github.com/pazLevi/Chest-X-Ray-Project


2. Extract the dataset:

- Download the "Chest X-Ray Images (Pneumonia).zip" file.
- Specify the destination path in the code: `dest_path = "path-to-destination-directory"`.
- Run the code to extract the dataset.

3. Run the code:

- Modify the necessary parameters in the code according to your preferences.
- Execute the code to train the model and evaluate its performance.

## Usage

- `explore_dataset(dataset_dir)`: Explore the dataset and get the count of images in each category.
- `visualize_class_distribution(class_labels, train_counts, test_counts, val_counts)`: Visualize the class distribution in the dataset.
- `display_sample_images(image_paths)`: Display sample images from the dataset.
- `generate_augmented_images(dataset, num_augmentations)`: Generate augmented images from the original dataset.
- `model = vgg19(pretrained=True)`: Initialize the VGG19 model for image classification.
- Training and evaluation code: Train the model, evaluate its performance, and calculate accuracy on the test set.

## Results

The model achieved an accuracy of X% on the test set after training for Y epochs. More detailed results and analysis can be found in the code.

## Contributing

Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

