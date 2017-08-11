# EnglishMaster
A Telegram bot. Grammar correction, spell checking, automatic translation and more (e.g. tools for admins).

-----------

## When is the official release of the bot?
1. I don't know, but it's very soon though!
2. Until i think that the bot is perfect and detects your message correctly. I signed up for Google Translate API for this :).
3. I tried NLTK, langid and langdetect. Seems like i have to train them; Google Translate API worked best.

-----------

## When will you release the source code?
1. Not very soon.

Original description of the bot:
```
I correct grammar, translate and spell check messages. 
To help building the master wordlist; you would need to be a trusted admin (for now).
Otherwise if you want to add a word (/add word), you will get a special number. 
Admins can use /accept N (n = number) to accept your word. 
The same thing is with /dict (e.g. /dict onw > on my way)

```

-----------

# Commands?
1. OK, here are __some__ of the commands you will probably use.

`/add WORD` = Add a new word to the wordlist.

(if the user is not admin):
`/add word` = Add a word to get reviewed by an admin. With a number.

`/accept N` = (N = number) accept a word. Only admins.

`/del WORD` = delete a word.

`/dict ur > your` = add a special word to the dictionary. The bot corrects ur with your.

`/correct text = BADGRAMMARMESSAGE` = correct that text's grammar. You can also reply to a message and use it. 

`/correct (reply_to_message)` = correct someone's message. 

`/translate text > lang` = translate from that language to English. You can also reply to a message and use it.

`/translate (reply_to_message)` = automatically detects the message's language and translates it to English.

__There are many other admin tools which you don't need to know right now.__

-----------

# Demo?
1. Yes; here is a demo of correcting grammar in Telegram:
![Demo](https://i.imgur.com/dz0Ohef.png)

2. Translation demo; please don't cringe if you're Russian or Japanese, i used Google Translate to make this possible.
![Demo](https://i.imgur.com/lH4LvmE.png)

3. Automatic deletion; input.
![Demo](https://i.imgur.com/ddd0xee.png)

3. Automatic deletion; output.
![Demo](https://i.imgur.com/reSkzu1.png)
-----------

# License
1. The bot is licensed under the MIT license.

# More info
1. The bot is completely written in Python. 
2. I'm using the [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot) wrapper. It sure is [fun](https://python-telegram-bot.org/)

----------

# Special message from the bot:
1. `Your grammar sucks, get on my level.`

----------
[Just for now, the logo might change. I used logomkr.com OKAY? OKAY? ]
Technology graphic by <a href="http://www.flaticon.com/authors/pixel-buddha">pixel_buddha</a> from <a href="http://www.flaticon.com/">Flaticon</a> is licensed under <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0">CC BY 3.0</a>.
