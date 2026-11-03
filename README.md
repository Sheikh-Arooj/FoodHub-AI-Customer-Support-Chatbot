# FoodHub – AI-Powered Customer Support Chatbot

An AI-powered customer support chatbot built using Google Gemini, LangChain, LangGraph, and SQLite to handle customer queries and retrieve order-specific information.

## Project Overview

FoodHub explores how Large Language Models (LLMs) can be integrated with structured databases to build intelligent customer support systems.

The chatbot understands customer queries, provides general support responses, and retrieves order information using an SQL Agent.

## Key Features

- **LLM Integration:** Uses Google Gemini to understand and respond to customer queries.
- **Prompt Engineering:** Refined prompts for accurate and responsible customer support.
- **SQL Agent:** Retrieves order-specific information from a structured database.
- **Database Integration:** Uses SQLite for storing and querying order details.
- **Order Tracking:** Handles order-status and delivery-related queries.
- **Query Validation:** Handles missing and invalid Order IDs.
- **Privacy Awareness:** Restricts unauthorized access to customer information.

## Technology Stack

- Python
- Google Gemini
- LangChain
- LangGraph
- SQLite
- Google Colab

## Project Structure

```text
FoodHub-AI-Customer-Support-Chatbot/
│
├── Foodhub_support (4).ipynb
├── README.md
└── .gitignore
```

## How to Run

1. Open the notebook in Google Colab.
2. Configure your Google Gemini API key securely.
3. Connect your Google Drive if using the existing database path.
4. Install the required dependencies.
5. Run the notebook cells sequentially.

**Note:** The notebook currently uses a Google Drive database path. Update it according to your environment before running the project.

## Learning Outcomes

This project provided practical experience in Generative AI, LLM integration, prompt engineering, SQL Agents, database interaction, and AI-powered application development.

---

**Project:** FoodHub – AI-Powered Customer Support Chatbot
