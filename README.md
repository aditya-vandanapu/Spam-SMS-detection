# 📧 Spam SMS Detection

## 📌 Project Overview
This project aims to detect spam messages using **Machine Learning (ML)** techniques. It classifies SMS messages as either **Spam (1)** or **Ham (0)** based on textual features. The model is trained using the **Naïve Bayes algorithm** and **TF-IDF vectorization**.

## 🎯 Task Objectives
✔ **Preprocess text messages** by removing punctuation, converting to lowercase, and eliminating numbers.  
✔ **Extract features** using **TF-IDF Vectorization** to convert text into numerical format.  
✔ **Train a Machine Learning Model** using the **Multinomial Naïve Bayes algorithm**.  
✔ **Evaluate model performance** using accuracy, precision, recall, F1-score, and ROC curve.  
✔ **Visualize important spam words** to understand which words contribute most to classification.  

---

## 🛠️ Steps to Run the Project

### **1️⃣ Install Python and Required Libraries**
Ensure Python is installed on your system. Install dependencies using:

```bash
pip install -r requirements.txt

2️⃣ Run the Spam Detection Script
Execute the script to train the model and evaluate its performance:

bash
Copy
Edit
python spam_sms_detection.py
3️⃣ View Results and Graphs
The script prints Accuracy, Precision, Recall, and F1 Score.
It displays a Confusion Matrix and ROC Curve for performance evaluation.
A bar chart of the top spam words is generated.
4️⃣ Save & Load the Model
The trained model and vectorizer are saved as:

spam_classifier.pkl
tfidf_vectorizer.pkl
You can load these for future predictions.

📊 Model Evaluation Metrics
Metric	Value (Example)
Accuracy	98%
Precision	97%
Recall	95%
F1 Score	96%
📂 Project Structure
bash
Copy
Edit
📦 Spam_SMS_Detection
 ┣ 📜 spam_sms_detection.py      # Main script
 ┣ 📜 requirements.txt           # Dependencies
 ┣ 📜 README.md                  # Project documentation
 ┣ 📂 models/
 ┃ ┣ 📜 spam_classifier.pkl       # Trained model
 ┃ ┣ 📜 tfidf_vectorizer.pkl      # TF-IDF vectorizer
🚀 Future Improvements
Implement deep learning-based text classification (e.g., LSTMs or Transformers).
Improve feature extraction using word embeddings (Word2Vec, BERT, etc.).
Deploy as a web API for real-time spam detection.
📌 Author
👤 Aditya Vandanapu
📧 aditya.vandanapu@gmail.com
🔗 GitHub Profile
