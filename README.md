# Image-caption-generator-Telegram-Bot
This repository contains the code for an Image Captioning Telegram Bot. The bot allows users to send an image, and it responds with a generated caption describing the image.

Features:
--> Receives images from users via Telegram.
--> Uses a pre-trained ResNet-50 model for feature extraction.
--> Uses the nlpconnect/vit-gpt2-image-captioning model for generating image captions.
--> Replies with the generated caption for the received image.

Prerequisites:
--> Python 3.6 or higher
--> Telegram account and a bot token from the BotFather
--> Required Python libraries

Installation:
Install the required packages:
      pip install torch torchvision transformers telebot requests Pillow
Set up your bot token:
      Replace 'YOUR_BOT_TOKEN' in the code with your actual Telegram bot token.

Usage
Run the bot:
      python bot.py
Interact with the bot:
--> Send /start or /help to the bot to get a welcome message.
--> Send an image to the bot, and it will reply with a generated caption.

File Structure:
bot.py: Main script for running the Telegram bot.
README.md: Documentation for the project.

How it works
1. Start and Help Commands:
--> The bot replies with a welcome message when the /start or /help commands are sent.

2.Handling Images:
--> The bot receives an image from the user.
--> The image is downloaded and saved locally.
--> The image is preprocessed and passed through a pre-trained ResNet-50 model to extract features.
--> The features are then used with the nlpconnect/vit-gpt2-image-captioning model to generate caption.
--> The generated caption is sent back to the user.

Acknowledgments:
--> PyTorch for the deep learning framework.
--> Transformers by Hugging Face for the image captioning model.
--> Python Telegram Bot API for the Telegram bot framework.

Output Images:
![Photos 01-06-2024 08_37_48](https://github.com/ReddySaran/Image-caption-generator-Telegram-Bot/assets/116064723/15fd99f4-5ae5-4cf0-ba5b-c59a0b636ab9)


![Telegram Web and 3 more pages - Personal - Microsoft​ Edge 01-06-2024 08_44_44](https://github.com/ReddySaran/Image-caption-generator-Telegram-Bot/assets/116064723/2db91d67-b82e-4d88-857f-7230ac067389)

