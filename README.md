# Task-3-Feb-Internship-NLP---Build-a-Chatbot-using-Hugging-Face-Transformers.
# 🤖 Chatbot using Transformers (FLAN-T5)

## 📌 Project Overview

This project is a conversational AI chatbot built using Hugging Face Transformers. It uses the FLAN-T5 model to generate meaningful and accurate responses to user queries in natural language.

The chatbot runs in an interactive loop where users can ask questions and receive AI-generated answers.

## 🎯 Objective

* Build a chatbot using a pre-trained transformer model
* Generate meaningful responses dynamically
* Simulate a real conversational AI system

## 🛠️ Technologies Used

* Python
* Hugging Face Transformers
* PyTorch
* Google Colab

## ⚙️ Model Used

* **google/flan-t5-large**

This model is instruction-tuned and provides better accuracy compared to traditional conversational models.
## 🔄 How It Works

1. User enters a query
2. Input is converted into a structured prompt
3. Transformer model processes the input
4. Model generates a response
5. Output is displayed to the user
6. Loop continues until user exits

## 💻 How to Run

1. Open the notebook in Google Colab
2. Install required libraries:

   ```bash
   pip install transformers accelerate
   ```
3. Run all cells step-by-step
4. Start interacting with the chatbot

## 💬 Sample Interaction
Chatbot: Hello! I am your AI assistant. Type 'exit' to stop.

You: What is Artificial Intelligence?
Chatbot: Artificial Intelligence is the simulation of human intelligence in machines that can learn and make decisions.

You: Who created Python?
Chatbot: Python was created by Guido van Rossum and released in 1991.

## ✨ Features

* Uses pre-trained transformer model
* Generates dynamic responses (no hardcoding)
* Interactive console-based chatbot
* Handles multiple user queries
* Exit condition implemented

## 📊 Learning Outcomes

* Understanding transformer-based models
* Working with Hugging Face libraries
* Prompt-based text generation
* Building conversational AI systems



## 🚀 Future Improvements

* Add conversation memory (context awareness)
* Build web interface using Gradio
* Improve response accuracy with fine-tuning

