# Document Chatbot 📑

This project is a chatbot designed to assist students in interacting with their textbooks in a conversational manner. The chatbot has been developed using the RAG (Retrieval-Augmented Generation) model, which enables it to understand and respond to natural language queries. It can be run locally on a machine using LM Studio or accessed via the internet using the Hugging Face API.

## Features 🌐

* *Select a textbook of your choice and initiate a conversation with it.*
* *Accessible via a user-friendly interface created with Streamlit.*
* *Contains chat memory: reponse of each chat is based on previous chats.*
* *View chat history to keep track of conversations.*
* *Select LLM of your own.*
* *Runs on both local machine and via internet.*

## Project Screenshots 📸

![Chat_history](https://github.com/abhikalparya/Document-Chatbot/assets/81465377/15a381d5-5ae7-441b-8480-f67c3113141b)

![HF](https://github.com/abhikalparya/Document-Chatbot/assets/81465377/a31e807a-7ce1-4159-8f74-203124cbf5cb)

## Workflow 🎯

![Flowchart](https://github.com/abhikalparya/Document-Chatbot/assets/81465377/a0c6d004-e5a5-4b72-b034-83118a8a0002)

## Setup 📝

1. `Clone this repo to your PC.`
2. `Install LM studio and download LLM which satisfy your hardware requirements.`
3. `Setup gpu on your PC based on your hardware.`
    * `Setup GPU on LM studio`
    * `In vectordb.py, Line 21; app.py, Line 58 and 2_Huggingface.py, Line 73 change device to cuda`
3. `Add your huggingface token with read access in:- pages\2_Huggingface.py`
4. `Add required textbook in pdf format inside 'Material' folder.`
5. `streamlit run app.py`
6. `In sidebar select book and click 'Create Requirements' (need to do only once if new textbook is added)`
7. `Whooo 🎉 Your setup is completed !!`

