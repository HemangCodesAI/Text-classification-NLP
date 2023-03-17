
# Text Classification with BERT

This project demonstrates how to use BERT for text classification. We will use the News Category Dataset available on Kaggle to classify news headlines and short descriptions into six categories: politics, world news, entertainment, sports, business, and tech.

## Data Preprocessing

We first load the dataset and preprocess the text by converting to lowercase, removing punctuations, tokenizing, removing stop words, and stemming the words. We then filter out rows with categories not in the top six.

## Model Training and Evaluation

We split the preprocessed text and category labels into train and test sets. We use the pre-trained BERT tokenizer to tokenize the text and convert the labels to numerical values. We then load the pre-trained BERT model and modify the last layer for classification.

We train the model for three epochs and evaluate it on the test set. We use the AdamW optimizer and a batch size of 16. We compute the test accuracy and print the classification report, which includes precision, recall, and F1-score for each category.

## Conclusion

We demonstrate how to use BERT for text classification and achieve good accuracy on the News Category Dataset. This approach can be applied to other text classification tasks with similar performance.










