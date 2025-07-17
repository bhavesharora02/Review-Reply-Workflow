# Review Reply Workflow

## Overview
This notebook implements an automated review response system using LangGraph and Google's Gemini 1.5 Pro AI model. The workflow processes customer reviews, analyzes their sentiment, and generates appropriate responses.

## Features
- Sentiment analysis of customer reviews
- Automated response generation
- Customizable workflow using LangGraph
- Integration with Google's Gemini 1.5 Pro model

## Prerequisites
- Python 3.7+
- Required Python packages:
  - langgraph
  - langchain-google-genai
  - python-dotenv
  - pydantic

## Setup
1. Clone the repository
2. Install the required packages:
   pip install langgraph langchain-google-genai python-dotenv pydantic

3. Create a `.env` file in the project root with your Gemini API key:
   GEMINI_API_KEY=your_api_key_here


## Usage
1. Open the `7_review_reply_workflow.ipynb` notebook
2. Run all cells to initialize the workflow
3. Input your review text when prompted
4. The system will analyze the sentiment and generate an appropriate response

## Workflow
1. Receives a customer review
2. Analyzes the sentiment (positive/negative)
3. Generates a context-appropriate response
4. Returns the formatted reply

## Configuration
The workflow can be customized by modifying the following:
- Temperature parameter for response generation
- Response templates
- Sentiment analysis criteria

## License
This project is licensed under the MIT License - see the LICENSE file for details.
