# Financial Advisor Chatbot

A chatbot that provides financial advice on saving, investing, debt management, and real-time stock prices using a knowledge base and Google Gemini AI.

## Features
- *Knowledge Base:* Matches user queries with predefined financial advice.
- *Stock Price Lookup:* Fetches real-time stock prices using Yahoo Finance.
- *Basic Financial Queries:* Answers general financial questions (savings, investment, debt management).
- *Google Gemini AI:* Handles complex queries via Google's Gemini API.

## Installation & Setup
### Prerequisites
Ensure you have Python installed along with the following dependencies:
bash
pip install yfinance google-generativeai


### API Key Configuration
Replace key = '' with your Google Gemini API key.

### Run the Chatbot
Save the script as chatbot.py and execute:
bash
python chatbot.py


## Usage
1. Run the chatbot and ask financial questions.
2. Get investment tips, saving strategies, and stock prices.
3. Type exit, quit, or bye to end the session.

## File Structure

📂 Financial-Advisor-Chatbot
 ├── chatbot.py        # Main chatbot script
 ├── knowledge_base.json # Financial knowledge base (optional)
 ├── README.md         # Documentation


## Contributing
Feel free to fork the repository and submit pull requests with improvements.

## License
This project is licensed under the MIT License.
