# Product-Performance-Dashboard


An Product-Performance-Dashboard built with FastAPI (backend) and Streamlit (frontend) to help users Visualize product-wise sales performance using a FastAPI backend (data provider) and a Streamlit frontend (visualization UI).

Project Structure
__________________________________________________________________________________

frontend/: Contains the Streamlit application code.

backend/: Contains the FastAPI backend server code.

tests/: Contains the test cases for both frontend and backend.

requirements.txt: Lists the required Python packages.

README.md: Provides an overview and instructions for the project.

Features
___________________________________________________________________________________
FastAPI backend hosts product sales and revenue data.
Streamlit fetches the data using the /products API.

Two charts visualize:

1.Revenue by Product

2.Units Sold Over Time

3.A sidebar filter lets you focus on one product at a time.

4.Interactive dashboards built with Streamlit

5.Fast, asynchronousSetup Instructions

Setup Instructions
__________________________________________________________________________________________
1.Clone the repository

    https://github.com/Apriya-sys/Product-Performance-Dashboard.git

    cd expense-management-system

2.Install dependencies::

    pip install -r requirements.txt
 
3.Run the FastAPI server:

     uvicorn server.server:app --reload
 
4.Run the Streamlit app:

     streamlit run frontend/app.py

 


