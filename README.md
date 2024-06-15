# Gemini LLM Q&A Chatbot

This project is a Streamlit application that leverages the power of Google's Gemini Pro model, a cutting-edge language model, to create an interactive question-answering chatbot. Users can engage in natural language conversations and receive insightful responses from the AI model.

## Key Features

- **Conversational Interface**: The application provides a user-friendly chat interface, allowing users to seamlessly interact with the Gemini Pro model by typing their questions.
- **Real-Time Responses**: The Gemini Pro model generates responses in real-time, providing users with instantaneous feedback and answers to their queries.
- **Chat History**: The application keeps track of the conversation history, allowing users to review previous questions and responses.
- **Streamlit Integration**: Leveraging Streamlit, a powerful Python library for building interactive web applications, this project offers a smooth and responsive user experience.

## Prerequisites

Before running the application, ensure that you have the following prerequisites installed:

- Python 3.x
- Google Cloud Platform account (to obtain the API key for Generative AI)

## Getting Started

1. Clone the repository: `git clone https://github.com/your-repo/gemini-llm-qachat.git`
2. Navigate to the project directory: `cd gemini-llm-qachat`
3. Create a virtual environment (recommended): `python -m venv env`
4. Activate the virtual environment:
   - On Windows: `env\Scripts\activate`
   - On Unix or macOS: `source env/bin/activate`
5. Install the required dependencies: `pip install -r requirements.txt`
6. Set up the Google API key:
   - Obtain an API key from the Google Cloud Console.
   - Create a `.env` file in the project directory.
   - Add the following line to the `.env` file, replacing `<your-api-key>` with your actual API key:
     `GOOGLE_API_KEY=<your-api-key>`

## Usage

1. Run the Streamlit application: `streamlit run qachat.py`
2. The application will open in your default web browser.
3. Type your question in the input field and click the "Ask the Question" button.
4. The Gemini Pro model will generate a response, which will be displayed in real-time.
5. The conversation history will be updated with your question and the model's response.

## Contributing

Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or submit a pull request.


## Acknowledgements

- [Streamlit](https://streamlit.io/) for providing an excellent Python library for building interactive web applications.
- [Google Generative AI](https://cloud.google.com/generative-ai) for offering the powerful Gemini Pro language model.

Explore the capabilities of this Gemini LLM Q&A Chatbot and enjoy engaging conversations with cutting-edge AI technology!
