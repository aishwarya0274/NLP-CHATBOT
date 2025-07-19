Simple ChatBot using Naive Bayes and Scikit-learn

This project is a basic command-based ChatBot built using Python's **Scikit-learn** library. It uses **CountVectorizer** to convert text data into numerical format and trains a **Naive Bayes classifier** to predict suitable responses based on user input.

Features

- Simple rule-based text classification
- Predefined training data (can be expanded)
- Real-time text input from users
- Clean and beginner-friendly code

 Technologies Used

- Python
- scikit-learn
  - `CountVectorizer` for text vectorization
  - `MultinomialNB` for classification

How It Works

1. **Training Data:** A small set of question-response pairs is used for training.
2. **Preprocessing:** The input sentences are transformed into numerical vectors.
3. **Model Training:** A Multinomial Naive Bayes model is trained on the input data.
4. **Prediction:** The model predicts the best response for a given user input.

Files Included

- chatbot.py: Main chatbot script
- README.md: This documentation file

---

Example Interaction

```bash
ChatBot is ready! Type 'exit' to quit.
You: hi
ChatBot: Hello! How can I help you today?
You: what is your name
ChatBot: I'm ChatBot, your assistant.
You: bye
ChatBot: Goodbye! Have a nice day.

 How to Run
Make sure Python is installed on your system.

Install scikit-learn if you haven't already:

bash
Copy
Edit
pip install scikit-learn
Run the chatbot:

bash
Copy
Edit
python chatbot.py


Future Improvements
Expand the training dataset for more complex conversations

Add NLP preprocessing (e.g., stemming, stopwords removal)

Integrate with a GUI or web interface

Add fallback/default responses for unknown queries 
