# Create Telegram Chatbot💬 using ChatGPT, Flask, and EC2

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-360/)

## [Watch the Tutorial for this Project](https://youtu.be/Fej2wb4YHes)

![YouTube Thumbnail](https://github.com/Spidy20/ChatGPT_Whatsapp_Bot/blob/master/yt_thumb.jpg)

## Overview

This project demonstrates how to create a Telegram chatbot using ChatGPT, Flask, and EC2. The following technologies and services are used:

- Ngrok and Flask as a server.
- Telegram BOT Token obtained from "BotFather".
- ChatGPT API for generating responses.
- Flask App as an API for the Request/Response model.
- AWS EC2 for deployment (24/7 running).

## Steps

1. Create free accounts on [OpenAI](https://platform.openai.com/account/api-keys), [AWS](https://console.aws.amazon.com/), and [Ngrok](https://dashboard.ngrok.com/).
2. Create a Flask App.
3. Create an EC2 instance on AWS.
4. Git clone this repository on the EC2 instance.
5. Create a Telegram bot using "BotFather" and obtain the API Token.
6. Use the `TELEGRAM_BOT_TOKEN` and `OPENAI_API_KEY` in your code (avoid using static values, use global variables).
7. Run the script on the EC2 instance.
8. Open a second terminal and use Ngrok to create a tunnel on port `5000`.
9. Set up a webhook for Telegram verification.

## Usage

To use this project:

1. Clone the repository.
2. Open a terminal in the working directory.
3. Run the following command to install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. `telegram_bot.py` is the Flask API that handles the request/response of the chatbot.
5. Run the script with the following command:

    ```
    python3 telegram_bot.py
    ```

6. To set up the webhook, use the following format:

    ```
    https://api.telegram.org/bot<Your Bot Token>/setWebhook?url=<URL of App>
    ```

For a more detailed explanation of this project, refer to the tutorial on the Machine Learning Hub YouTube channel.

## Screenshots

<img src="https://github.com/Spidy20/ChatGPT_Whatsapp_Bot/blob/master/sc_1.jpg" width="270" height="500">

## Support

If you find this project helpful, consider supporting me:

- [Buy me a Coffee☕](https://www.buymeacoffee.com/spidy20)
- [Donate via PayPal](https://www.paypal.me/spidy1820) (It will inspire me to work on more projects)

Feel free to follow me and star⭐ this repository!