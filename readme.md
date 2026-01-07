# Multi LLM RequestsType

A simple Python tool for simultaneously receiving responses from multiple LLMs via the OpenRouter API.

## Key Features
- **Multi-model requests:** Sending one request to a list of models in a single cycle.
- **Error Handling:** Handling API errors, timeouts, and network issues.
- **Security:** Using `.env` to securely store API keys.

## Технології
- Python 3.9.13
- Requests (for HTTP-requests)
- Python-dotenv (for configuration)
- OpenRouter API

## How to launch
1. Clone repository:
   ```bash
   git clone [https://github.com/MykhailoTymoshenko08/multi-llm-interface.git](https://github.com/MykhailoTymoshenko08/multi-llm-interface.git) 
   ```
2. Set dependency:
    ```bash
    pip install requests python-dotenv
    ```
3. Create a .env file in the root folder and add your key:
    ```bash
    API_KEY=you_API_key
    ```
4. Launch the script:
    ```bash
    py app1.py
    ```
    or
    ```
    python app1.py
    ```
