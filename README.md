# LLM_sentiment_outcome
Customer Service Transcript Sentiment and Outcome Analyzer

This project provides a Python script that leverages OpenAI’s GPT-4 API to analyze customer service transcripts. The tool reads transcripts from .txt files and determines the sentiment (positive, neutral, or negative) of the customer ("member") and whether the issue was resolved or requires a follow-up.
Key Steps:
1.	Setup: Install required dependencies and set up the OpenAI API key.
2.	Reading Transcripts: The script reads .txt files from a specified directory containing customer service transcripts.
3.	API Integration: Each transcript is processed using the GPT-4-turbo-preview model to analyze sentiment and outcome.
4.	Results: Sentiment and outcome data are saved into a CSV file for further analysis.
This tool helps businesses efficiently analyze customer interactions, allowing them to measure customer satisfaction and monitor unresolved issues.
