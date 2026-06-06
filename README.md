# AI Product Support Chatbot

An AI-powered customer support chatbot that provides intelligent product-related assistance using Large Language Models (LLMs). The application retrieves product information from a MySQL database and generates context-aware responses using Groq's Llama 3 model.

## Features

* AI-powered product support
* FastAPI REST API backend
* Groq Llama 3 integration
* MySQL product database
* Session-based conversation handling
* Chat history storage
* CORS-enabled API
* Easy integration with web applications

## Architecture

User Query → FastAPI Backend → MySQL Product Database → Prompt Engineering → Groq Llama 3 → AI Response → Chat History Storage

## Tech Stack

### Backend

* FastAPI
* Python
* Pydantic

### Database

* MySQL

### AI/LLM

* Groq API
* Llama 3 8B

### Utilities

* python-dotenv
* requests







## Database Tables

### products

| Column      | Type    |
| ----------- | ------- |
| name        | VARCHAR |
| price       | FLOAT   |
| description | TEXT    |

### chat_history

| Column       | Type    |
| ------------ | ------- |
| session_id   | VARCHAR |
| user_message | TEXT    |
| bot_response | TEXT    |


## Future Enhancements

* Retrieval-Augmented Generation (RAG)
* Product recommendation engine
* Multi-language support
* Voice-enabled chatbot
* Analytics dashboard
* User authentication
* Vector database integration

## Author

Sravs Jyos

MBA | AI & Machine Learning Enthusiast | Generative AI Developer

