# Factorial Bot by Dopamine Studios

A specialized Discord bot built with `discord.py` on top of [Dopamine Framework](https://github.com/dopaminestudios/dopamine-framework) that silently monitors conversations to catch accidental factorials. When a user sends a message that contains digit(s) followed by an exclamation mark `!`,, the bot formats replies to the message with the solution to that factorial expression.

---

## Features

Detects factorials! It's pretty simple. It listens to all messages in the server and sends its message when someone types an exclamation mark `!` after any digit(s).

Additionally, since the bot is built on top of [Dopamine Framework](https://github.com/dopaminestudios/dopamine-framework), you get access to all its commands and features, including smart command syncing, owner dashboard (accessed through `/od`), and more.

---

## Installation

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/dopaminestudios/factorialbot.git
    cd haikubot
    ```

2.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Setup Environment:**

    Create a `.env` file in the root directory:
    ```env
    DISCORD_TOKEN=your_bot_token_here
    ```

4.  **Initialize Databases**
    Ensure a `databases/` folder exists in your root directory.

---

## Usage
Run the bot using:
```bash
python main.py
```

### Commands
* `/factorial` – Toggle Factorial detection in the current server.

...and all commands included in [Dopamine Framework](https://github.com/dopaminestudios/dopamine-framework).

---

## License & Attribution
This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0). This means if you modify the bot and run it as a service, you must share your modified source code under the same license.

The bot already mentions credit to **Dopamine Studios** in the message sent when the bot is invited to a server. **You must not remove the attribution** from that message.

---

<sub>This bot is a distilled version of [Dopamine](https://github.com/dopaminestudios/dopamine), the Giveaway, Moderation, and multi-purpose bot that includes the same Factorial detection feature. If you want to use this Factorial detection feature without self-hosting, invite Dopamine by [clicking here](https://top.gg/bot/1411266382380924938/invite).