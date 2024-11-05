# React + Flask Web Scraper with Multi-LLM Visitor Classifier

This project is a full-stack web application that combines React for the frontend and Flask for the backend. It enables users to submit a URL for scraping, analyzes the content using both Ollama's and OpenAI's large language models (LLMs), generates questions based on the scraped data, and classifies users based on their responses. This multi-LLM setup provides robust, versatile language capabilities for content analysis and user classification.

![image](https://github.com/user-attachments/assets/108919fa-a40f-4450-8c9d-c0fd0ab26d59)
![image](https://github.com/user-attachments/assets/ed62e099-e7f1-469a-8192-ec54ff6b043b)

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)

## Features

- **Content Scraping**: Scrapes content from a user-provided URL.
- **Multi-LLM Integration**: Uses both Ollama and OpenAI APIs for content analysis, question generation, and user categorization.
- **Visitor Classification**: Asks questions and categorizes visitors based on their responses, utilizing the strengths of both LLMs.
- **Mock Responses**: Available for testing without consuming API quotas from Ollama or OpenAI.

## Tech Stack

- **Frontend**: React, Axios
- **Backend**: Flask, Flask-CORS, BeautifulSoup, Ollama API, OpenAI API
- **Libraries**: Python, Node.js
- **Third-Party Services**: Ollama API, OpenAI GPT API
