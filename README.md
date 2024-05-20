## Features
-Interactive Chat Interface: The chatbot uses Streamlit to provide a web-based interface for user interaction.
-Google Gemini API Integration: Utilizes Google's Generative Model (gemini-pro) to generate intelligent and relevant responses.
-Session State Management: Maintains chat history across user interactions using Streamlit's session state.

## Getting Started

### Prerequisites
-Python 3.x
-Virtual environment tool (e.g., venv)
-Google Generative AI API Key

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
  
