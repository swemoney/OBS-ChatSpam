# OBS Chat Spam Script
This is a small Python script for OBS Studio that allows you to post messages in Twitch chat using OBS hotkeys. This can be used for posting general chat messages, spamming emotes, or triggering chat bot commands.

## Installation
The script only works with OBS Studio versions 21.x and later. If you have an older version you will need to update.

You need [Python 3](https://www.python.org/downloads/) installed on your PC. The bit version of your Python installation must match your OBS installation (e.g. 64-bit OBS requires 64-bit Python). In the menu in OBS Studio, go to `Tools` and then `Scripts`. Then in the "Python Settings" tab, set the path to point to the Python installation folder.

Add the chat spam script to the "Scripts" window using the '+' icon on the bottom left. Select the script in the "Loaded Scripts" panel, and if everything is set up correctly you should see the script properties show up on the right.

## Setup
Fill out the configuration settings in the script properties:
* **Channel**: The Twitch channel to post messages in.
* **User**: The username that messages will be posted under.
* **Oauth**: Oauth key used for authentication. If you don't have an oauth key, you can easily get one using [this site](https://twitchapps.com/tmi/). Do not share your oauth key with anyone.

Add messages to the message list for things you want to say in chat. Each message gets a dedicated hotkey that can be configured in the OBS hotkey settings.

## License
This script is licensed under the terms of the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).
