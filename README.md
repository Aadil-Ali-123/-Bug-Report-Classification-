# -Bug-Report-Classification-
A machine learning based bug report classification system using Random Forest and SMOTE to address class imbalance. Includes preprocessing, evaluation, and comparison with Naïve Bayes across multiple open source projects.

# -Requirements-
Python 3.11+  
Scikit-learn  
Pandas & NumPy  
NLTK  
Matplotlib & Seaborn  
Imbalanced-learn (SMOTE)  
Google Colab (preferred environment)

# -Execution (Google Colab)-
This project is designed to run on Google Colab and loads the dataset from Google Drive using the following command:

from google.colab import drive  
drive.mount('/content/drive')

The dataset is accessed using a dynamic path like:  
filePath = f'/content/drive/MyDrive/{project}.csv'

To run the notebook:
1. Upload the dataset (e.g. pytorch.csv) to your Google Drive under MyDrive.
2. Change the `project` variable in the notebook to match the dataset.
3. Run the notebook in Google Colab.

If you wish to run this locally (outside Colab), replace the file path with your local directory (e.g. './data/pytorch.csv') and comment out the drive.mount line.

