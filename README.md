# Character AI Bot

Character AI Bot is a Python application that interacts with the CharacterAI API to simulate conversations with an AI character.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#license)

## Getting Started

### Prerequisites

Before using Character AI Bot, you need to set up your environment and obtain API credentials:

1. You must have Python 3.x installed on your machine.
2. You need to sign up for an API key from CharacterAI and store it as an environment variable. You can find more information on how to obtain the API key in the CharacterAI documentation.

   ```shell
   export CLIENT=your-api-key
   export CHAR=your-character-identifier
   ```

# Installation

1. Clone the repository to your local machine:
  ```shell
  git clone https://github.com/your-username/character_ai_bot.git
  cd character_ai_bot
  ```
2. Install the required Python packages:
   ```shell
   pip install -r requirements.txt
   ```
# Usage

To use Character AI Bot, follow these steps:

1. Run the Python script:
```shell
python character_ai_bot.py
```
2. The bot will prompt you for input. You can enter your message, and the bot will send it to the AI character and display the response.
3. Interact with the bot by providing input and receiving responses.

# Examples
 
```
You: Hello, how are you?
AI Bot: I'm doing well, thank you! How can I assist you today?

You: Tell me a joke.
AI Bot: Why did the AI break up with the computer? It had too many trust issues!

You: Goodbye!
AI Bot: Farewell! Have a great day.
```
#License
This project is licensed under the MIT License 
