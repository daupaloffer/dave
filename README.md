# Dave Prime
## A modern Discord bot for the squishypickle1 community

This is the source for the specialised bot for Twitch streamer [squishypickle1](https://www.twitch.tv/squishypickle1)'s Discord server.
Please excuse any mistakes - I'm fairly new to discord.py 2.0.0 still.

## Current features

- "Streamerboost": Give any member who is currently streaming a special role. This can be used to show people streaming above everyone else on the member list in order to promote them. NOTE: This will unfortunately cause your Audit Log to fill up if triggered often.
- "owo-ify": owo-ify a piece of text. Defaults to previous message in chat, and user can optionally specify input in the same command as well as anonymity.
- Moderation Alerts: Instant Discord time-out, ban, and unban alerts.
- WIP - Miniature stock market: A tiny stock market based on real-world listing prices that server members can trade on to accumulate fake internet points.

All commands in this bot use Discord's slash-commands. Type a "/" in chat and select Dave Prime's icon to see all of the commands.

## Setup

1.  Clone this repo
2.  Install dependencies from requirements.txt file
3.  Create ".env" file in bot directory
4.  Format like so:
    
    ```
    BOT_TOKEN=""
    MAIN_GUILD=""    # ID (Snowflake)
    TEST_GUILD=""    # ID (Snowflake)
    TEST_ENV=""      # true/false
    ```

3.  Fill the variables with the appropriate values
4.  Run main.py
5.  Go wild

## Formatting

This project is formatted with the [Black](https://github.com/psf/black) formatter.
