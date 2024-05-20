## RedPill AI with Streamlit
This repository contains a simple chatbot application built using Streamlit and Google's Gemini API. The bot, named "RedPill AI," can interact with users and generate responses based on their queries.
## Features
1. Interactive Chat Interface: The chatbot uses Streamlit to provide a web-based interface for user interaction.
2. Google Gemini API Integration: Utilizes Google's Generative Model (gemini-pro) to generate intelligent and relevant responses.
3. Session State Management: Maintains chat history across user interactions using Streamlit's session state.

## Getting Started

### Prerequisites
1. Python 3.x
2. Virtual environment tool (e.g., venv)
3. Google Generative AI API Key

### Installation
1. Clone the repository:
   ```sh
        git clone https://github.com/darshanm17/RedPill-AI-with-Streamlit.git
        cd RedPill-AI-with-Streamlit

2. Create and activate a virtual environment:
    ```sh
         python -m venv venv
         source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. Install the required packages:
    ```sh
         pip install streamlit google-auth google-auth-oauthlib google-generativeai
4. Set up your Google API Key:
   -Replace the placeholder API key in the code with your actual Google API key.

### Running the App

1. Activate the virtual environment if not already active:
   ```sh
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
2. Run the Streamlit app:
   ```sh
   streamlit run app.py
3. Open your browser and navigate to http://localhost:8501 to interact with RedPill AI.

## Code Description
1. Title and Environment Setup: The app starts by setting the title and configuring the Google API key.
2. Model Initialization: Configures the gemini-pro model from Google's Generative AI API.
3. Chat History Management: Initializes and manages chat history using Streamlit's session state.
4. Message Display: Displays chat messages from the session history on app rerun.
5. Response Handling: Defines a function to handle user queries and generate responses using the Gemini API.
6. User Input Handling: Accepts user input and triggers the response function when a query is provided.

## Future Enhancements
1. Add error handling for network and API issues.
2. Implement user authentication for personalized sessions.
3. Enhance the UI with custom styling and additional features.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.
  
