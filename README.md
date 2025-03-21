# Sentiment Analysis
This project focuses on sentiment analysis using machine learning techniques. The notebook provides a structured workflow for preparing data, training a model, and visualizing results.
# Features
- **Data Preparation:** Cleaning and preprocessing text data.
- **Model Training:** Building and training a sentiment analysis model.
- **Result Visualization:** Analyzing predictions with visual representations.
- **Example Usage:** Running the model on sample data.
# Dataset
For this project, I used open source dataset from Kaggle.

Url of the dataset: https://www.kaggle.com/datasets/abhi8923shriv/sentiment-analysis-dataset/data
# Model Architecture
This project utilizes a Bidirectional LSTM (Long Short-Term Memory) network for sentiment classification. The model consists of:
- **Embedding Layer:** Converts text sequences into dense vectors of fixed size.
- **Bidirectional LSTM Layers:** Captures long-term dependencies in text.
- **Dropout Layers:** Reduces overfitting by randomly deactivating neurons during training.
- **Dense Layers:** Includes a fully connected layer with ReLU activation and an output layer with a softmax activation function for classification.
- **Optimizer:** Adam optimizer with a learning rate of 0.01.
- **Loss Function:** Sparse categorical cross-entropy.
# Results
![image](https://github.com/user-attachments/assets/176162cc-7794-4fdd-a668-1533215aab9b)
![image](https://github.com/user-attachments/assets/3a66e447-edbd-4abb-b95c-8ca65274bc9c)

**Accuracy:** Accuracy on the test set: 0.6814


