# Sentiment Analysis for Customer Reviews Challenge
In this comprehensive data analysis journey, we have included all the crucial stages of data science: Data Cleaning, Preprocessing, Exploratory Data Analysis, diverse Model application, rigorous Model Evaluation, and insightful Comparison for optimal decision-making and predictive accuracy.

## Data Cleaning 
Data cleaning is a crucial step in preparing datasets for analysis. We have used CleanText function
- **The CleanText function-** Data cleaning is a crucial step in preparing datasets for analysis, and the CleanText function is a versatile tool designed for efficient text preprocessing. It is a powerful tool designed to enhance text data preprocessing by seamlessly removing special characters, irrelevant symbols, HTML tags, and other unwanted elements.

## Data Preprocessing
Data preprocessing is a crucial step in preparing datasets for analysis, and the following code snippet demonstrates an insightful approach to enhance data understanding and categorization. 
**Upvote Metrics** Upvote metrics play a crucial role in understanding the perceived helpfulness and sentiment of user reviews or content
- **Helpful Percentage (Helpful %):** This metric calculates the percentage of helpful votes by taking the ratio of the 'HelpfulnessNumerator' (indicating the number of helpful votes) to the 'HelpfulnessDenominator' (representing the total number of votes, both helpful and unhelpful). 
- **Upvote Categorization (%upvote):** The '%upvote' column categorizes reviews into six distinct bins, each representing a percentage range of helpful votes.

## Data Analysis and Visualization
**- Pivot Table:**

Type: Data Analysis Tool
Function: Allows for dynamic restructuring and summarization of data in a tabular format.
Purpose: Facilitates the exploration and understanding of complex datasets by providing a customizable way to view and analyze data across different dimensions.

**- Heat Map:**

Type: Data Visualization Technique
Function: Represents data values in a matrix using color gradients, where color intensity corresponds to the magnitude of the data.
Purpose: Visualizes patterns, trends, and variations in data, making it easier to identify areas of interest or concentration within a dataset.

## Natural Language Processing (NLP)
**- Indented Block:**

Used for visually organizing or emphasizing text in documents or code. It doesn't specifically belong to NLP or machine learning but is a formatting feature in text-based documents or code.

**- CountVectorizer:**

Converts a collection of text documents to a matrix of token counts. It's a fundamental tool in NLP for turning text data into numerical vectors suitable for machine learning models.

**- Term Frequency-Inverse Document Frequency (TF-IDF) Vectorizer:**

Similar to CountVectorizer, TF-IDF is used to transform text data into numerical vectors. It assigns weights to terms based on their frequency in a document and their rarity across the entire dataset.

## Models

**- Random Forest (TF-IDF Vectorizer):**

A machine learning algorithm used for both classification and regression tasks. When coupled with TF-IDF Vectorizer, it can be particularly effective for processing and analyzing text data.

**- Linear Support Vector Machine (TF-IDF Vectorizer):**

A machine learning algorithm for classification tasks. When combined with TF-IDF Vectorizer, it becomes a powerful tool for text classification tasks, such as sentiment analysis.

**- Sentiment Analysis With Logistic Regression:**

Uses logistic regression, a machine learning algorithm, for sentiment analysis. It falls under the broader umbrella of NLP and machine learning applications for analyzing and determining sentiment in textual data.

## Model Comparison

**- Logistic Regressuion -** We got the accuracy of 92.322618

**- Random Forest -** We got the accuracy of 85.745509

**- Linear Support Vector Machine -** We got the accuracy of 88.637454

As we can see from the above result, Logistic Regression is giving the best result. Therefore, we will consider Logistic Regression as our final model.
## Libraries Used
Numpy

Pandas

NLTK

seaborn

sklearn

matplotlib
