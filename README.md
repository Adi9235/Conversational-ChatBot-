# Conversational-ChatBot

## **Problem Statement** <br>
Suppose we want to get the details of lets say 100 -200 pdfs so it will take us more time to manually read and get the desired answer of our question. So we want 
to construct a chatbot which takes our query and performs desired semantic search by using convolutional Buffer Window which allows bot to hold memory for previous
chat history.


## **Solution**<br>
We will be going to construct a conversational chatbot that will take the inputs as number of pdfs and give a refined query based on the the users history.
We will be using a vector database for our text embeddings and the database would be pinecone. 

## **Architecture**<br>

![image](https://github.com/Adi9235/Conversational-ChatBot-/assets/88960354/d17d29e3-bf08-44b1-bdc6-149e4f3708f6)

## **Requirements**<br>
- [x] streamlit
- [x] streamlit_chat
- [x] langchain
- [x] sentence_transformers
- [x] streamlit>=1.25.0,<2.0.0
- [x] pillow<10,>=7.1.0

## **Future Scope**<br>
To built the UI for chatbot to work on Streamlit and also for chatbot to work on Textbase as I was getting the error of setting textbase. I tried both locally and 
also on Github codespaces but there was some error on vite.svg and that I was not able to configure. I was facing this error on Windows. I am aiming to work on 
solving this issue after this hackathon.

**Reference** <br>
https://blog.futuresmart.ai/building-an-interactive-chatbot-with-langchain-chatgpt-pinecone-and-streamlit

**Thank You!**








