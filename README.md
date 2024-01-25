# 🧠 Mental Health AI Bot

Develop a chatbot powered by a specialized index, designed to provide insights and support based on mental health literature. This application enables users to interact with an extensive collection of mental health resources in a conversational manner, making it simpler to access relevant information and gain knowledge from the underlying content.

- Incorporates a user-friendly interface for submitting inquiries and displaying responses, enhancing the interactive experience.
- Employs a sophisticated indexing system to organize and process mental health books and articles, creating a responsive chat engine. This engine intelligently extracts information from the indexed materials to offer precise and helpful responses to user questions, aiding in mental health understanding and support.

## Getting Started

### Obtain an OpenAI API Key

To interact with GPT 3.5, you'll need an OpenAI API key:

1. Visit [OpenAI API Keys](https://platform.openai.com/account/api-keys).
2. Click on the `+ Create new secret key` button.
3. Optionally, enter an identifier name and click on the `Create secret key` button.

### Running Locally

To run this app locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/bdhaval/private-document-chat
   cd private-document-chat
   ```

2. **Set Up a Python Environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add Your Private Data:**
   
   Add your private data in the `data` folder

5. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

6. **Access the App:**

   Open your web browser and go to http://localhost:8501.

