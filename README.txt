AIC-2273 -- EVANGELION UNIT-02

Welcome to the Final Round Mitotic Cell Detection Challenge! In this competition, we invite data scientists, machine learning enthusiasts, and computer vision experts to develop innovative solutions for a critical task in cellular biology and medical research - distinguishing mitotic cells from normal cells in biological images.

Provided with a dataset of labeled microscopic images categorized into two classes: "Mitotic" and "Normal" cells, the competition required us to develop a model which can accurately predict the classes of an unseen dataset.

Overview
The training dataset consists of 66 images

The training labels mention the image file name and the corresponding labels ('Mitosis' or 'Normal')

The test data consists of 99 images, all unlabeled

OpenCV is used for most of the image reading, resising and preprocessing. To know more about what OpenCV does, refer the link: https://docs.opencv.org/4.x/index.html

MultiOtsu is the primary preprocessing method used. To learn more about MultiOtsu, visit: https://scikit-image.org/docs/stable/auto_examples/segmentation/plot_multiotsu.html

Plotly (https://plotly.com/python/) is the most dynamic python plotting tool. We used Plotly to visualise our data. We also used some Matplotlib :)

Using VGG-19, we trained our model. Our parameters for VGG-19 can be seen in the code. Here's the documentation for VGG-19: https://keras.io/api/applications/vgg/