# **News-Research-Tool-Project**  

## **Overview**  
The **News Research Tool** is an AI-powered application that enables users to perform **semantic news searches** using **FAISS (Facebook AI Similarity Search)** and **LangChain**. It processes unstructured news data and retrieves relevant articles efficiently. The user interface is built with **Streamlit**, making it interactive and user-friendly.  

## **Features**  
✔ **Semantic Search** – Finds relevant news articles based on meaning rather than keywords.  
✔ **FAISS Integration** – Uses vector embeddings for fast similarity-based retrieval.  
✔ **LangChain Processing** – Efficiently loads and splits text for better search results.  
✔ **Interactive Chatbot (Streamlit UI)** – A research assistant with a web-based interface.  
✔ **CSV & Text Support** – Works with structured (CSV) and unstructured (TXT) data.  
✔ **Easy Deployment** – Can be hosted locally or on cloud platforms like Streamlit Sharing.    
  

## **Installation**  
1️⃣ Clone the repository:  
   ```bash
   git clone https://github.com/SuriyanC/News-Research-Tool-Project.git
   cd News-Research-Tool-Project
   ```  
2️⃣ Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3️⃣ Run the Streamlit application:  
   ```bash
   streamlit run app.py
   ```  

## **Project Structure**  

📂 `Code for News_Research_chat_bot/` – Main chatbot implementation.  
📜 `FAISS_VECTOR.ipynb` – Notebook for FAISS-based vector search.  
📜 `Retrieval (RetrievalQAWithSourcesChain).ipynb` – Retrieval-based QA implementation using LangChain.  
📜 `text_loaders_splitters_using_langchain.ipynb` – Preprocessing and text-splitting pipeline.  
📜 `Top Indian Places to Visit.csv` – Sample dataset for testing.  
📜 `nvda_news_1.txt` – Example news text file.  
📜 `sample_text.csv` – Another sample dataset.  
🖼 `rockybot.jpg` – Image asset for the project.  
📜 `requirements.txt` – List of dependencies required for running the project.  


## **Usage**  
1️⃣ **Upload a news article or provide a news article link** in the **Streamlit UI**.  
2️⃣ The system **processes and vectorizes** the content using FAISS & LangChain.  
3️⃣ Users can **input queries** to retrieve the most relevant news articles.  
4️⃣ The chatbot will provide **contextual answers** based on the retrieved news data. 
