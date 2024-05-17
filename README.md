# To Run
Download the repository on your system and run  'streamlit run app.py' on terminal to reach the page and see the website.
# Approach
This project is all about classifying the spam messages separately from those of non spam messages.
After transforming the messages by stemming, removing punctuations and unnecessary words, I used vectorization technique to form the vector usin sklearn library.
Used the vector matrix to train different models and choosing the one with highest precision alongwith good accuracy.
Finally used the same model to predict on the new input message, using streamlit for the frontend page and taking inputs and showing spam or non spam message.
