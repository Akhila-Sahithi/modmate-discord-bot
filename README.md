# **ModMate Discord Bot**

A modular and beginner-friendly Discord bot built with **Python** and **discord.py**, featuring moderation tools, automatic message filtering, welcome messages, reaction polls, role assignment, and helpful utility commands.

---

## **Features**

### Moderation

* Deletes messages containing banned words
* Warns users automatically
* Reply & DM utilities
* Assign/remove roles safely

### Member Experience

* Sends a welcome DM when a user joins
* Custom reply commands
* Poll creation using embeds

### Role System

* Assigns a hidden role (`Gamer`) using `!assign`
* Removes it using `!remove`
* Restricts access to secret commands unless you have the role

### Utility Commands

| Command            | Description                            |
| ------------------ | -------------------------------------- |
| `!hello`           | Greets the user                        |
| `!assign`          | Assigns the secret role                |
| `!remove`          | Removes the secret role                |
| `!dm <message>`    | Sends a DM to yourself                 |
| `!reply`           | Bot replies to your message            |
| `!poll <question>` | Creates a thumbs-up/down poll          |
| `!secret`          | Only works if you have the secret role |

---

## **Tech Stack**

* **Python 3.10+**
* **discord.py v2**
* **dotenv** for environment variables
* **Logging** for debugging

---

## **Project Structure**

```
modmate-discord-bot/
│
├── main.py              # Main bot code
├── requirements.txt     # Python dependencies
├── .env.example         # Environment variable template
└── README.md            # You're reading it :)
```

---

## **Setup Instructions**

### Clone this repository

```bash
git clone https://github.com/Akhila-Sahithi/modmate-discord-bot.git
cd modmate-discord-bot
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Create your `.env` file

Copy `.env.example` to `.env`:

```
DISCORD_TOKEN=your_bot_token_here
```

> Never commit your real token to GitHub.

### 4️⃣ Run the bot

```bash
python3 main.py
```

---

## **Security Notes**

* Your Discord bot token **must stay private**
* Always use `.env` for secrets
* `.env` is already ignored by `.gitignore`
* If your token leaks, **reset it immediately** in the Discord Developer Portal

---

## Author

**Akhila Sahithi**
*ModMate Discord Bot Creator*


Just tell me!
