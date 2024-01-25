# IT-project

## Aim 
This work aims to accomplish the task of _news classification_. The objective is to utilize well-known classification algorithms to train the model to distinguish between texts of different categories and identify similarities among those in the same category. To achieve this, the texts need to be converted into numerical representations, and several supervised machine-learning algorithms are employed.

The notebook is divided as follows: 
1. Web-Scraping
2. Data Preprocessing
3. Exploratory Data Analysis
4. Classification

## Overview 

The project begins with data retrieval through web scraping, focusing on the 'CNN' website as a valuable source of information. During data retrieval, attention is given to obtaining labels (news categories) for use as ground truth in the classification. Four categories are chosen: Politics, Business, Entertainment, and Health.

The text data undergoes preprocessing, including tokenization, stop word removal, and lemmatization. Following data cleaning, exploratory data analysis is performed to better understand the collected and processed data. This step is divided into four substeps, each exploring different aspects of the dataset.

Finally, the classification process involves transforming the text into numerical vectors, a prerequisite for classifier input. Techniques such as TF-IDF, Word2Vec, and Doc2Vec are employed to create representative vectors based on word frequencies or semantic meanings. These vectors serve as features for training four selected classifiers: Random Forest, Logistic Regression, Gradient Boosting, and Support Vector Machine.

The last part involves the creation of a neural network for classification. This experiment explores an alternative embedding technique and a different approach to classification.
