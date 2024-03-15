# AIC-2273 -- EVANGELION UNIT-02

# softec24-aic-finalist

![softec24-aic-finalist](https://img.shields.io/badge/softec24--aic--finalist-orange)
![Python](https://img.shields.io/badge/Made%20with-Python-blue)

Welcome to the Final Round Mitotic Cell Detection Challenge! This competition is a platform for data scientists, machine learning enthusiasts, and computer vision experts to showcase their skills and develop innovative solutions for a critical task in cellular biology and medical research - distinguishing mitotic cells from normal cells in biological images.

## Overview
- **Training Dataset**: The training dataset comprises 66 labeled microscopic images.
- **Labels**: Each image is labeled as either 'Mitosis' or 'Normal'.
- **Test Data**: The test data includes 99 images, all of which are unlabeled.

## Tools and Libraries
- **OpenCV**: Utilized for image reading, resizing, and preprocessing. To learn more about OpenCV, refer to the [documentation](https://docs.opencv.org/4.x/index.html).
- **MultiOtsu**: Primary preprocessing method employed. For more information on MultiOtsu, visit the [documentation](https://scikit-image.org/docs/stable/auto_examples/segmentation/plot_multiotsu.html).
- **Plotly**: A dynamic Python plotting tool used for visualizing data. Also, some visualization tasks were performed using Matplotlib.
- **VGG-19**: The model was trained using the VGG-19 architecture. Parameters for VGG-19 can be found in the code. Here's the documentation for [VGG-19](https://keras.io/api/applications/vgg/).

## Installation
To set up the environment for running this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/softec24-aic-finalist.git
   ```
2. Navigate to the project directory:
   ```bash
   cd softec24-aic-finalist
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Data Exploration**: Explore the provided datasets to understand the structure and characteristics of the images.
2. **Preprocessing**: Utilize OpenCV and MultiOtsu for image preprocessing to enhance the quality and extract relevant features.
3. **Model Training**: Train the model using the VGG-19 architecture on the preprocessed training dataset.
4. **Evaluation**: Evaluate the performance of the trained model using appropriate metrics and techniques.
5. **Prediction**: Use the trained model to predict the classes of the unlabeled test dataset.

## Contributing
Contributions to this project are welcomed and appreciated. If you have any suggestions, feature requests, or bug reports, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
