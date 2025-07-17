# Telegram AI bot

Model used is gpt-3.5-turbo to make chat completion.

## Requirements
- create a .env file with open api key (OPENAI_API_KEY).
- create a new environment and install all required packages.
- aiogram (for connecting telegram and open ai)
- openai
- python-dot-env (for using .env file)

## Setup

- create a project folder with requirements file.
- Research folder has echo bot, for testing the bot connectivity, when it is running the bot will reply the input given.
- download telegram and open bot father
    - sent message to create a new bot (/newbot)
    - give bot name (animebot(bot name), my_best_anime_bot (username))
    - open the url given by the bot to access the created bot.
- create a new environment with requirement file.

```bash
conda create -n telegrambot python=3.10 -y
conda activate telegrambot
pip install -r requirements.txt
```