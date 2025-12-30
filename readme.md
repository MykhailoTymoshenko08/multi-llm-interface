# Multi LLM Interface

Простий Python-інструмент для одночасного отримання відповідей від декількох LLM (Llama 3.1, Llama 3.2 тощо) через OpenRouter API.

## Основні можливості
- **Multi-model requests:** Надсилання одного запиту до списку моделей за один цикл.
- **Error Handling:** Обробка помилок API, таймаутів та мережевих проблем.
- **Security:** Використання `.env` для безпечного зберігання API-ключів.

## Технології
- Python 3.x
- Requests (для HTTP-запитів)
- Python-dotenv (для конфігурації)
- OpenRouter API

## Як запустити
1. Клонуйте репозиторій:
   ```bash
   git clone [https://github.com/MykhailoTymoshenko08/multi-llm-interface.git](https://github.com/MykhailoTymoshenko08/multi-llm-interface.git) 
   ```
2. Встановити залежність:
    ```bash
    pip install requests python-dotenv
    ```
3. Створіть файл .env у кореневій папці та додайте свій ключ:
    ```bash
    API_KEY=you_API_key
    ```
4. Lunch the script:
    ```bash
    py app1.py

    or

    python app1.py
    ```