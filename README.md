# Sentiment Analysis with Traditional and Deep Learning ML Models

![What-is-Deep-Learning (1)](https://github.com/user-attachments/assets/42beb733-2243-4da7-9c2d-d0ec9ec41c2c)

### Project Overview
This project examines and compares the performance of various machine learning models for sentiment analysis on publicly available text datasets, such as the IMDb movie reviews dataset. The objective is to evaluate one traditional machine learning approach (SVM or Logistic Regression) against two deep learning architectures (RNN or LSTM), highlighting their respective strengths and weaknesses.


**Key Findings:**
* The comparison between deep learning and traditional models provides insights into the trade-offs between computational cost, architectural complexity, and predictive performance.
  
**Group Members**
* Branis Sumba
* NJean Pierre Niyongabo
* Tamanda kaunda
* Diana Ruzindana

### Project Structure
The repository is organized as follows:
 **`notebooks/`**: Contains the Jupyter/Colab notebooks for data exploration, preprocessing, model training, and comparison.
 **`processed_data/`**: Stores the output of the data preprocessing steps, including TF-IDF features and padded sequences.
 **`models/`**: Stores the trained machine learning and deep learning models.
 **`Model_Comparison_Charts.ipynb`**: Notebook for comparing and visualizing model performance.
 **`README.md`**: This file.
 **`requirements.txt`**: Lists all project dependencies.

## Setup and Installation
To run this project, you will need:

### Prerequisites
   Python 3.8+
   Access to a Google Colab environment is recommended.

### Dependencies
Install the required Python libraries using `pip`:
```bash
pip install -r requirements.txt
```
### Usage
Clone the repository:
```
git clone https://github.com/ngabo-dev/sentiment-analysis_group3
cd sentiment-analysis_group3
```

Open the notebooks in Google Colab. 
Please make sure your Google Drive is mounted to access the models stored in the models/ directory.
Run the Model_Comparison_Charts.ipynb notebook to see the comparison of all models.

### Results and Discussion
***Model Performance Comparison***
F1 score & Accuracy metrics of Deep learning vs Traditional Machine Learning Models
<img width="1366" height="768" alt="Untitled design (4)" src="https://github.com/user-attachments/assets/1d47648e-c471-41e1-b8cf-aea8ad63a584" />


### Discussion
The analysis reveals significant differences in performance, demonstrating the strengths and weaknesses of each modeling approach.
The comparison provides insight into the trade-offs between model complexity, computational cost, and predictive accuracy for this specific sentiment analysis task. 

### References
 **GeeksforGeeks Article**: "Introduction to Deep Learning" [https://www.geeksforgeeks.org/deep-learning/introduction-deep-learning/]
**Dataset**: `Reviews.csv` " Kaggle Sentiment Analysis" [https://github.com/ngabo-dev/sentiment-analysis_group3/blob/main/content/Reviews.csv]

### License
This project is licensed under the MIT License. 


