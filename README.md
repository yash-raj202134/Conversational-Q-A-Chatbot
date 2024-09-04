# Gemini Q&A Chatbot Application

## Overview

This Streamlit application demonstrates a Q&A chatbot using Google's Gemini Generative AI model. The application allows users to input questions and receive responses from the AI model. The chatbot maintains a history of the conversation to provide context and continuity.

## Features

- **User Input:** Users can type questions into a text input field.
- **AI Responses:** The application sends user queries to the Gemini model and displays the responses.
- **Chat History:** Maintains a history of the conversation, displaying both user questions and AI responses.

## Requirements

- Python 3.x
- Streamlit
- `python-dotenv`
- `google-generativeai`

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yash-raj202134/Conversational-Q-A-Chatbot.git
   cd Conversational-Q-A-Chatbot
   ```
2. Create a Virtual Environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install Dependencies:
```bash
pip install -r requirements.txt
```
5. Create a .env File: Create a .env file in the root directory of the project and add your Google API key:
```bash
GOOGLE_API_KEY=your_google_api_key_here
```
6. Run the Streamlit App:
```bash
streamlit run app.py
```


## Interact with the Chatbot:

- Input Prompt: Type your question in the text input field.
- Submit: Click the "Ask the question" button to send your query.
- Response: View the AI-generated response and the chat history below the input field.

## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any questions or feedback, please contact yashraj3376@gmail.com
