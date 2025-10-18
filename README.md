# Product-Performance-Dashboard


An Product-Performance-Dashboard built with FastAPI (backend) and Streamlit (frontend) to help users Visualize product-wise sales performance using a FastAPI backend (data provider) and a Streamlit frontend (visualization UI).

Project Structure

frontend/: Contains the Streamlit application code.
backend/: Contains the FastAPI backend server code.
tests/: Contains the test cases for both frontend and backend.
requirements.txt: Lists the required Python packages.
README.md: Provides an overview and instructions for the project.

Features
FastAPI backend hosts product sales and revenue data.

Streamlit fetches the data using the /products API.

Two charts visualize:
Revenue by Product
Units Sold Over Time
A sidebar filter lets you focus on one product at a time.
Interactive dashboards built with Streamlit
Fast, asynchronous backend API using FastAPI
