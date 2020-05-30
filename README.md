![bot_message](bot_message.gif?raw=true)

# Discord Bot

Discord bot for greetings from Space :milky_way:  :earth_americas:

## Installation

This installation assumes that you already created your application and the bot via the [Discord](https://discord.com/) website under the [Documentation](https://discord.com/developers/docs/intro#bots-and-apps) section.

1. Clone this repo: ``git clone https://github.com/wbail/discord-bot``
2. Download and install [Node](https://nodejs.org/).
3. Use the package manager [npm](https://www.npmjs.com/) to install dependencies.
4. Open ``terminal`` or ``cmd`` (Windows)
5. Navigate into the project folder and execute the statements:

```bash
npm install discord.io winston
npm install https://github.com/woor/discord.io/tarball/gateway_v6
```
6. Rename the file ``auth-example.json`` to ``auth.json``.
7. Copy and replace the ``BOT_TOKEN`` with the real token.

```json
//auth.json
{
    "token": "BOT_TOKEN"
}
```
8. In the terminal, start the bot executing ``node bot.js``
9. Your bot is up and running!

## Usage

1. On Discord, type ``!intro`` to receive the bot's message!

## Demo

* Starting the bot :rocket:

![bot_startup](bot_startup.gif?raw=true)

* Sending and receiving the bot's message :milky_way:

![bot_message](bot_message.gif?raw=true)

## Author

* [wbail](https://github.com/wbail)