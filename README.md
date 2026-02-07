<div align="center">

# 🦜🔗 LangChain Prompts & Chatbots

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Inference%20API-FFD21E?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)

### Developed by **[Ghulam Muhammad]**
*Building the foundation for Agentic AI in 2026*

---
</div>

A comprehensive exploration of Prompt Engineering and Template Management within the LangChain ecosystem. This repository demonstrates how to build modular, scalable, and interactive LLM applications using open-source models via the Hugging Face Inference API.

## 📁 Project Structure

This module is organized into specialized scripts that demonstrate core LangChain concepts:

* **`chat_prompt_template.py`**: Implementation of `ChatPromptTemplate` for managing System and Human roles with dynamic variables.
* **`console-based-chatbot.py`**: A stateful CLI chatbot implementation utilizing `AIMessage` and `HumanMessage` to maintain conversational context.
* **`message_placehoder.py`**: Advanced use of `MessagesPlaceholder` to integrate external chat history from text files.
* **`messages.py`**: Low-level handling of message objects and model invocation.
* **`prompt_generator.py`**: Creating complex `PromptTemplate` objects for structured research summaries and saving them as serialized JSON.
* **`research_tool_with_dynamic_prompt.py`**: A Streamlit dashboard that loads prompts from JSON and uses LCEL (LangChain Expression Language) for automated research paper summarization.
* **`static_promtp_ui.py`**: A basic Streamlit interface for direct model interaction.
* **`template.json`**: Serialized prompt metadata including input variables and formatting.

## 🛠️ Key Technologies

* **LangChain Core**: For prompt templating and message management.
* **LangChain HuggingFace**: For seamless integration with Meta-Llama and Qwen models.
* **Streamlit**: For developing web-based AI research tools.
* **Python-Dotenv**: For secure management of API credentials.

## 🚀 Getting Started

1. **Clone Repository and Navigate to the Directory:**

    ```bash
    git clone https://github.com/imabid141/LangChain-Prompts.git

    cd LangChain-Prompts
    ```

2. **Set up the environment:**

    ```bash
    python -m venv langchain-env
    source langchain-env/bin/activate
    pip install -r requirements.txt
    ```

3. **API Keys:**
Create a `.env` file for Hugging Face Inference API access:

   ```env
   HUGGINGFACEHUB_API_TOKEN=your_token_here
   ```

4. **Run the applications:**

    For console scripts: `python console-based-chatbot.py`
    For Streamlit apps: `streamlit run research_tool_with_dynamic_prompt.py`
