# __Chatbot with Llama 2 and Streamlit__
This project demonstrates how to create an interactive chatbot using the Llama 2 model within a Streamlit app. The chatbot interacts with users based on data provided in CSV files. It leverages advanced techniques like sentence transformers for creating data embeddings and a vector store for efficient data retrieval.
## Features
* Upload CSV files to provide data for the chatbot
* Generate embeddings from CSV data using Sentence Transformers
* Store embeddings in a local vector store for quick retrieval
* Interactive chat interface powered by Streamlit
* Real-time responses to user queries based on the CSV data
## Installation
To run this project locally, follow these steps:
### Clone the repository:
```bash
git clone https://github.com/yourusername/chatbot-llama2-streamlit.git
cd chatbot-llama2-streamlit
```
### Create a virtual environment:
```bash
conda create --name chatcsv
conda activate chatcsv
```
### Install dependencies:
```bash
pip install -r requirements.txt
```
### Run the Streamlit app:
```bash
app.py
```
## Usage
* Open your browser and navigate to http://localhost:8501.
* Upload a CSV file containing data for the chatbot.
* Start asking questions through the chat interface.
The chatbot will respond based on the data from the uploaded CSV file.
## Components
1. Llama 2 Model
Role: Acts as the brain of the chatbot, interpreting user inputs and generating responses.
2. Streamlit App
Role: Provides the user interface for interacting with the chatbot, including file uploads and chat functionality.
3. CSV Data
Role: Serves as the knowledge base for the chatbot. Users upload CSV files containing the data the chatbot will use to generate responses.
4. Sentence Transformers
Role: Converts text data from the CSV files into embeddings (numerical representations) that the chatbot can understand and use.
5. Vector Store
Role: Stores the embeddings generated from the CSV data, allowing for quick and efficient retrieval when the chatbot needs to respond to a query.
6. Interactive Interface
Role: Enables users to upload CSV files, ask questions, and receive answers from the chatbot through an easy-to-use web interface.
