# Discord Caption Bot

This is a Discord bot that can add captions to images.
Created for @whiskeyspurs' Replit bounty.

**Features:**

* Supports PNG, JPEG, and WebP images
* Allows users to specify the caption text
* Automatically resizes the caption to fit the image

**Usage:**

1. Attach an image to a Discord message.
2. Type the following command:

"
!caption <caption text>
"

3. The bot will reply with a new message containing the captioned image.

**Example:**

!caption Hello world!


**Requirements:**

* Python 3
* Discord.py library
* PIL library

**Installation:**

1. Clone this repository:

"
git clone https://github.com/Bard/discord-caption-bot.git
"

2. Install the required dependencies:

"
pip install -r requirements.txt
"

3. Set your Discord bot token in the `.env` file:

DISCORD_TOKEN=YOUR_BOT_TOKEN


**Running the bot:**

"
python main.py
"

**License:**

This project is licensed under the MIT License.
