# Conversational AI Chatbot

This project implements a conversational AI chatbot using a local Large Language Model (LLM) and Gradio for the user interface.

## Description

The chatbot is built with:

* **Local LLM:** Utilizes a locally hosted LLM (in this case, accessed via Ollama). This allows for private and offline chat capabilities.
* **OpenAI Library:** The OpenAI Python library is used to interact with the LLM, even though it's a local instance.
* **Gradio:** Provides a user-friendly web interface for interacting with the chatbot.
* **System Message:** The chatbot's behavior can be customized using a system message, allowing you to define its role (e.g., "You are a helpful assistant" or "You are an excellent joke cracker").
* **Chat History Management:** The application maintains chat history to provide context for ongoing conversations.

##  Requirements

* Python 3.x
* Ollama (or a similar tool for running local LLMs)
* Required Python libraries:  `openai`, `gradio`, `dotenv` (you might need to install these using `pip install openai gradio python-dotenv`)
* A local LLM (e.g., Llama 2, Llama 3) downloaded and accessible via Ollama.

##  Setup

1.  **Install Dependencies:**
    ```bash
    pip install openai gradio python-dotenv
    ```
2.  **Set up Ollama (or your LLM server):**
    * Make sure Ollama is installed and running.
    * Download your desired LLM (e.g., Llama 2, Llama 3) in Ollama.
3.  **Run the Notebook:**
    * Execute the Jupyter Notebook (`Chatbot.ipynb`).  The Gradio interface will launch in your browser.

##  Usage

* Interact with the chatbot through the Gradio web interface.
* Modify the `system_message` variable in the notebook to change the chatbot's persona.

##  Notes

* This project demonstrates how to create a chatbot with a local LLM, offering benefits like data privacy and reduced reliance on external APIs.
* The specific LLM used (e.g., "llama3.2") is hardcoded in the notebook and should be changed according to your setup.
* Error handling and more robust input validation could be added to improve the application.

## Author

\[Your Name]

## License

\[Choose a license, e.g., MIT License]
