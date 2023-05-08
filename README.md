# Mental-Health-Chatbot
<h1><b>Project Overview</b></h1>

The goal of this project is to build a chatbot that can have a conversation with users regarding mental health. The chatbot is designed to understand user's inquiries about mental health and respond with helpful information or resources.

<h1><b>Project Structure</b></h1>
The project has the following files:

intents.json: Contains all the intents of the chatbot.
MentalHeathChatbot.ipynb: The main Jupyter Notebook containing the code for training the chatbot.
MentalHeathChatbot.pkl: The trained chatbot model.
README.md: This file containing project overview.

<h1><b>Technical Overview</b></h1>
The chatbot uses a neural network trained on the intents.json file to understand user's inquiries about mental health. The neural network is trained using the PyTorch library. The chatbot uses the nltk library for natural language processing, including tokenization, stemming and bag of words model.

The chatbot can be trained by running the mental_health_chatbot.ipynb file. Once trained, the model is saved as a pickle file, which can be loaded and used for chatbot response generation.
