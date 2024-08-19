# sc23r2p
This is the repository to my Dissertation project.

# Diabetic Retinopathy Classification Project
### This project focuses on classifying the severity of Diabetic Retinopathy using four different deep learning models: VGG16, InceptionV3, Xception, and ResNet50. The project is implemented in Python and was executed in a Jupyter Notebook environment.

### System Requirements
#### Processor: Intel(R) Core(TM) i5 or higher
#### RAM: at least 16 gb's of RAM
#### Environment: Jupyter Notebook

### Required Libraries
To run this project, you need to install the following libraries. You can install them using the 
***
`
pip package manager
pip install pandas
pip install numpy
pip install opencv-python
pip install tensorflow
pip install matplotlib
pip install scikit-learn
pip install seaborn
`

## Dataset
### The dataset used in this project is the APTOS 2019 Blindness Detection dataset, which can be downloaded from Kaggle:

APTOS 2019 Blindness Detection Dataset
Please download the dataset and place the files as described in the "Project Structure and File Placement" section. 
### URL: https://www.kaggle.com/competitions/aptos2019-blindness-detection/data

### Project Structure and File Placement
To ensure that the code runs correctly, you must organize your files in the following structure:

`project_folder/`
***
`│ Ritik Parihar SC23R2P.ipynb  # Jupyter Notebook file containing the code`
***
`├── test_images/                 # Directory containing test images`
***
`│   └── *.png, *.jpg, etc.       # Test image files`
***
`├── test.csv                     # CSV file containing metadata for the test images`
***
`├── train_images/                # Directory containing training images`
***
`│   └── *.png, *.jpg, etc.       # Training image files`
***
`└── train.csv                    # CSV file containing metadata for the training images`
1. Ritik Parihar SC23R2P.ipynb: The Jupyter Notebook file containing all the code for the project.
2. test_images/: A folder that contains all the test images.
3.  test.csv: A CSV file that contains metadata for the test images, such as image labels and other relevant information.
4. train_images/: A folder that contains all the training images.
5. train.csv: A CSV file that contains metadata for the training images, such as image labels and other relevant information.
*** 
### Installation Instructions
1. Download the Ipynb file from the repository: Ritik Parihar SC23R2P.ipynb and paste it in your designated folder with the files from the traing and validation dataset.
### install Required Libraries:
2. Install the necessary libraries by running the following commands:
   `pip install pandas
pip install numpy
pip install opencv-python
pip install tensorflow
pip install matplotlib
pip install scikit-learn
pip install seaborn`

3. Set Up the Directory Structure:
Make sure that your project folder is structured as outlined in the "Project Structure and File Placement" section.
4. Run the Jupyter Notebook:
Open the Jupyter Notebook (Ritik Parihar SC23R2P.ipynb) and run the cells in sequence to execute the project. Make sure you have a compatible Python environment and Jupyter installed.
5. System Specifications:
The project was executed on a machine with an Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz and 24 GB of RAM. Depending on your system's specifications, the performance may vary.
***
### Usage
1. Data Preprocessing:
The project includes code for loading and preprocessing the APTOS 2019 Blindness Detection dataset. Ensure that the dataset is properly placed in the expected directory structure.

2. Model Training:
The notebook includes code to train four models: VGG16, InceptionV3, Xception, and ResNet50. You can train these models using the provided code.

3. Evaluation:
After training, the models are evaluated based on various metrics, including accuracy, precision, recall, F1 score, and ROC curves. Confusion matrices are also provided to assess the classification performance.

