Task 4: Email Spam Detection Using Machine Learning
Project Overview
This project builds a machine learning model to classify text messages
or emails as Spam or Ham (Not Spam). It uses Natural Language
Processing (NLP) techniques to convert text into numerical features and
train classification models.
Objective
To develop and evaluate a binary text-classification model that can
identify spam messages and distinguish them from legitimate messages.
Technologies Used
- Python
- Google Colab / Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- TF-IDF Vectorizer
- Matplotlib and Seaborn (for visualizations, if used)
Project Workflow
1. Load the dataset into a pandas DataFrame.
2. Inspect the data and check for missing values and duplicates.
3. Clean and prepare the text data.
4. Convert text into numerical features using TF-IDF Vectorization.
5. Split the dataset into training and testing sets.
6. Train a Multinomial Naive Bayes classifier.
7. Evaluate the model using suitable classification metrics.
8. If included, train and compare an additional classification model.
Model Evaluation
The model can be evaluated using: - Accuracy - Precision - Recall -
F1-score - Confusion matrix

These metrics help assess how well the classifier detects spam while
avoiding incorrect spam predictions for legitimate messages.
Dataset
Use the dataset selected for this task. Keep the downloaded dataset in
the project folder or upload it to Google Colab before running the
notebook.

Note: Update the dataset filename and loading path in the notebook
to match the file you downloaded. Do not upload private or personal
messages.
How to Run
1. Open the notebook in Google Colab.
2. Upload the dataset when prompted, or connect the notebook to the
   folder containing it.
3. Run the notebook cells in order, from top to bottom.
4. Review the model evaluation results and visualizations.
Repository Structure
OIBSIP/
└── Data Science-Task 4-Email Spam Detection/
    ├── README.md
    ├── Email_Spam_Detection.ipynb
    └── dataset.csv
The notebook and dataset filenames above are examples. Keep the actual
filenames used in your project.
Outcome
The project demonstrates a basic NLP and machine learning workflow for
spam detection, including text preprocessing, feature extraction with
TF-IDF, model training, and performance evaluation.
Internship: Oasis Infobyte (OIBSIP)
Task: Task 4 -- Email Spam Detection with Machine Learning