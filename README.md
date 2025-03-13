<div align="center">
  <a >
    <img src="https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/openart-image_4UuZ2nYy_1740848959131_raw.jpg" alt="Banner" width="150"><br>
  </a>

  <div id="user-content-toc">
    <ul>
      <summary><h1 style="display: inline-block;">Cdiscount Chatbot Assistant</h1></summary>
    </ul>
  </div>
  
  <p>A Customer Service Chatbot Trained on Cdiscount Data</p>
    🏓
    <a href="https://youtu.be/slYyGwTECTQ" target="_blank">Demo YouTube</a>
    🔮
    <a href="https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/issues" target="_blank">Request Feature</a>
</div>
<br>
<div align="center">
      <img src="https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/Logo_Cdiscount.svg" alt="Banner" width="150"><br>
</div>

## 📝 Table of Contents

1. [Project Overview](#project-overview)
2. [Chatbot Description](#chatbot-description)
3. [Technologies Used](#technologies-used)
4. [Disclaimer](#disclaimer)
5. [Installation](#installation)
6. [Contact](#contact)
<hr>

### 💬 Chatbot Pages

Check out some examples of the chatbot in action:

1. **Example 1:**
   ![image](https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/1.png)

2. **Example 2:**
   ![image](https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/2.png)

3. **Example 3:**
   ![image](https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/3.png)

<a name="project-overview"></a>
## 🔬 **Project Overview** :

### 🎯 **Goal** :

The goal is to develop an AI-powered chatbot that interacts with users by providing relevant and professional responses. This chatbot uses data sourced from the official Cdiscount Q&A section to provide accurate and interactive information.

<a name="chatbot-description"></a>
## 💬 **Chatbot Description** :

The **Cdiscount Chatbot** works as follows:

1. **Data Scraping**: Data is extracted from the official Cdiscount Q&A pages using **Langchain's WebBaseLoader**.
2. **Data Processing**: The scraped content is processed using **Langchain's RecursiveCharacterTextSplitter**.
3. **Embedding**: The processed data is converted into vectors with **llama-text-embed-v2** and stored in **Pinecone**.
4. **User Interaction**: The **Gemini 2.0 Flash** model utilizes the data in Pinecone to interact with users and respond to their questions in a credible and professional manner.

🔎 **Memory Feature**:  
This chatbot has a memory feature that allows it to remember the last 5 messages of the conversation, and this number is scalable, ensuring more context-aware and coherent interactions. By retaining this context, it provides more relevant, personalized responses, improving the overall user experience and maintaining continuity throughout the interaction.

## **📝 Chatbot Architecture**

![chatbot-architecture](https://github.com/ChahiriAbderrahmane/CDiscount_Assistant_Chatbot/blob/master/assets/Architecture_Cdiscount_bot.jpg)


<a name="technologies-used"></a>
## 🛠️ **Technologies Used** :
  
![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=python&logoColor=white)  ![Pinecone](https://img.shields.io/badge/Pinecone-412991?style=for-the-badge&logo=Pinecone&logoColor=white) ![Llama](https://img.shields.io/badge/Llama2-000000?style=for-the-badge&logo=meta&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini%202.0%20Flash-000000?style=for-the-badge&logo=google&logoColor=white)

<a name="disclaimer"></a>

## **🚨 Disclaimer :**
This project is a personal initiative and is not affiliated with Cdiscount. It was created for educational and personal development purposes.

<a name="contact"></a>

<a name="installation"></a>
## 🖥️ Installation : 
1. Clone the repository:

```git clone private_repository_link```

2. Install the required packages:

```pip install -r .\chatbot_Cdiscount\requirements.txt```

### Usage : 

1. Change directory to :

```cd Chatbot-Cdsicount```

2. Run the app:

```streamlit run .\chatbot_Cdiscount\CdiscountMarketplaceBot.py  ```

<a name="contact"></a>
## 📨 Contact Me
[LinkedIn](https://www.linkedin.com/in/abderrahmane-chahiri-151b26237/) •
[Gmail](chahiri.abderrahmane.eng@gmail.com) •
[Demo on Youtube](https://youtu.be/slYyGwTECTQ)
