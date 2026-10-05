# CodeAlpha FAQ Chatbot

A simple FAQ chatbot built for the CodeAlpha Artificial Intelligence internship (Task 2).

## How it works
- Text preprocessing with NLTK (tokenizing and stopword removal)
- TF-IDF converts questions into vectors
- Cosine similarity finds the closest matching FAQ
- The bot replies with the answer to the best match, or asks the user to rephrase if nothing matches

## Technologies used
- Python
- NLTK
- scikit-learn

## How to run
1. Open `chatbot.py` in Google Colab or any Python environment
2. Install the libraries: `pip install nltk scikit-learn`
3. Run the code and type your question after `You:`
4. Type `quit` to exit

## Example
You: do you deliver
Bot: Yes, we deliver to most cities. Delivery takes 3-5 days.
