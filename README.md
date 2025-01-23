Overview:
This project is an AI-powered chatbot that enables users to query a product and supplier database using natural language. The chatbot interacts with an open-source LLM and utilizes the LangGraph framework for efficient agent workflows, fetching relevant data from a MySQL/PostgreSQL database and summarizing information using AI.

Tech Stack:
Frontend: React (Material UI/Tailwind CSS, Axios, Redux/Context API)
Backend: Python (FastAPI/Flask, LangGraph, Open-source LLM)
Database: MySQL/PostgreSQL
 Features:
 Natural Language Queries – Users can ask questions like:

"Show me all products under brand X."
"Which suppliers provide laptops?"
"Give me details of product ABC."
 AI-Powered Responses – The chatbot fetches structured data and enhances responses using LLM-based summarization.
 Responsive UI – Built with React, featuring a conversational chat interface and query history tracking.
 Efficient Query Handling – Optimized MySQL/PostgreSQL schema for fast supplier/product data retrieval.
 Error Handling – Graceful handling of incorrect/missing queries.
 Bonus Enhancements (Optional):
 JWT-based Authentication
 Product Comparisons & Analytics Dashboard
 Chatbot Memory for User Preferences

 Setup & Installation:
 Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/ai-chatbot-supplier-product.git
 Install dependencies & set up the database.
 Run the backend & frontend services.

 Future Improvements:

Enhance chatbot memory for better personalization
Integrate with external supplier APIs for real-time data
 Contributions & Feedback Welcome!
