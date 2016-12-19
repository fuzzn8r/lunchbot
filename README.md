# lunchbot
A slackbot used to give recommendations for lunch spots and happy hours.

# What it uses (not an exclusive list)
- nodejs to run the bot
- maybe some python for the backend stuff
- maybe some mongo for the database stuff
- probably javascript for the top-level/user-interaction stuff
- Botkit to make our lives easier https://howdy.ai/botkit/

# To Start It
Download and install the botkit
```
git clone git@github.com:howdyai/botkit.git
cd botkit
npm install
```

Copy the `lib` folder into the lunchbot repo.

Get the token from https://thelunchcrew.slack.com/services/B345QSEDV (don't generate a new one unless you believe it to be compromised)

NEVER SHARE THIS TOKEN WITH ANYONE OUTSIDE THE PROJECT

Start lunchbot with the following command (currently using a demo file):
```
token=REPLACE_THIS_WITH_YOUR_TOKEN nodejs slack_bot.js
```

I have no idea what happens when multiple users try to start up the same bot. Let's try to avoid that.
