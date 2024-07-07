# Covid-19 Detection using Chest X-Ray

## Overview:
COVID- 19 global pandemic affects health care and lifestyle worldwide,
and its early detection is critical to control cases’ spreading and mortality.
The actual leader diagnosis test is the Reverse transcription Polymerase
chain reaction (RT-PCR), result times and cost of these tests are high,
so other fast and accessible diagnostic tools are needed. 
This projects’
approach various machine learning models to process these images and classify them
as positive or negative for COVID-19.
after this initial stage comes the classification model trained
under the transfer learning scheme; and finally, results analysis. The best
models achieved a detection accuracy of COVID-19 around 85%
## Dataset Description
The dataset contains two main folders, one for the X-ray images, which includes two separate sub-folders of 5500 Non-COVID images and 4044 COVID images.
## Source of Dataset
[X Ray Images](https://data.mendeley.com/datasets/8h65ywd2jr/3)

## Built using:
- [Scikit Learn: ](https://scikit-learn.org/stable/) ML Library used
- [TensorFlow Keras: ](https://www.tensorflow.org/api_docs/python/tf/keras) ML Libraries used
- [Pandas: ](https://pandas.pydata.org/) Python data manipulation libraries
- [Seaborn: ](https://seaborn.pydata.org/) Data visualisation library
- [OpenCV2: ](https://pypi.org/project/opencv-python/) Image Preprocessing library
## Pipeline:
This is the main file containing EDA, preprocessing, application of various machine learning and deep learning models.
- Installing libraries and dependencies
- Importing the dataset
- Exploratory Data Analysis and Visualisation
- Data Preprocessing
  - Normalisation
  - Resizing image
- Machine Learning Models
  - Dimensonality reduction using PCA
  - Decision tree Clasifier
  - Random Forest Classifier
  - XG Boost
  - Light GBM
  - Support vector machine
  - Logistic Regression
  - Comparitive Analysis  