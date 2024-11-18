# Automated-Information-Retrieval-Dashboard

This project features an AI-based dashboard that enables users to upload datasets in CSV format and choose a specific column they want to focus on, such as company names. 
It conducts web searches using flexible queries created from user templates. 
The search results are then processed by a language model like GPT-4 to pull out important information, such as where a company is located. Finally, the gathered data is shown in a table and can be exported as a CSV file.

Clone or Download the Repository:
Download the project files or open the Colab notebook provided.
Install Required Libraries: Run the following command in your Colab or local environment:

bash
Copy code
!pip install streamlit pandas openai requests google-auth gspread


Upload Required Files or use the API link for the dataset
Service Account Credentials: Upload credentials.json for Google Sheets integration if using this feature.
Run the Application:

In Colab, follow the Streamlit setup instructions to start the dashboard.

Usage Guide
Upload Dataset
Select Column
Set Query Template
Type in a dynamic query template, for example
Perform Web Search
Process Results with LLM
Export Results
