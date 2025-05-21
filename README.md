# Spam vs Ham Email Classifier

This project implements a binary text classification system to distinguish between **spam** and **ham** (legitimate) emails/messages using traditional machine learning techniques.

---

## Features

- Preprocesses email text using tokenization, stopword removal, and stemming.
- Uses TF-IDF vectorization to convert text into numerical features.
- Trains a **Multinomial Naive Bayes** classifier on the dataset.
- Provides a **Streamlit** web app for easy message classification via a user-friendly interface.
- Includes example spam and ham messages for quick testing.

---

## Dataset

The model is trained on a publicly available spam dataset with columns:

- `label`: Indicates whether the message is `spam` or `ham`.
- `text`: The email or SMS message content.

---

## Installation

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd spam-ham-classifier
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Train the Model
Run the training script to preprocess data, train the model, and save the model and vectorizer:

bash
Copy
Edit
python spam_classifier.py
Run the Streamlit App
Start the web app for interactive classification:

bash
Copy
Edit
streamlit run streamlit_app.py
How to Use the App
Enter any email or message text in the input box.

Alternatively, use the sidebar buttons to load example spam or ham messages.

Click Classify to see if the message is spam or ham.

Dependencies
Python 3.7+

pandas

numpy

scikit-learn

nltk

streamlit

Notes
The classifier performs well on balanced datasets but may miss some spam messages.

Feel free to improve the model by experimenting with other algorithms or features.

License
This project is open source and available under the MIT License.

yaml
Copy
Edit

---

Would you like me to help generate this file so you can download it?







