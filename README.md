# Shibboleth bot

This is a Discord bot to play the hidden-team word game Shibboleth remotely via real-time text on the [Shibboleth discord server](https://discord.com/invite/TmHxFfG).

### Table of Contents
1. [Using the bot](#using-the-bot)
2. [How to play Shibboleth](#how-to-play-shibboleth)
    - [Rules](#rules)
    - [Veto phase](#veto-phase)
    - [Partial team guesses](#partial-team-guesses)
3. [Playing on Discord](#playing-on-discord)
    - [Round logistics](#round-logistics)
    - [Fairness](#fairness)
    - [Discord tricks](#discord-tricks)
        - [Reactions](#reactions)

## Using the bot
Write `!help` to see the Shibboleth bot's list of commands. You can do this in any channel in the server or by messaging the bot. Use `!help command` to get details on using the command.

## How to play Shibboleth

### Rules

Shibboleth (aka Castlefall) is a hidden-team word game for 4 to 12 players. It's kind-of like Codenames, Spyfall, and Castle of the Devil. A round takes about 5-20 minutes.

You are given a secret word that only you know. Half the players have one secret word and half have another. For example, in a five-player game, three players might get "banana" and two might get "skateboard". 

The people sharing your word are your team, while the opposing team all has another word. You want to work together with them and figure out who they are. At any point in the round, you can submit a guess of either:
- The full set of people on your team
- The opposing team's word
Whether you're right determines whether your team wins or the opposing team. After any guess, the round immediately ends and the teams and words are revealed.

You try to find your team by giving clues about your word. The idea is to convince teammates that you share the same word, while being vague or tricky enough that the opposing team won't figure out your word. You can say whatever you want in your clues, and you can clue whenever you want -- there aren't any turns. The only rule is your clues have to be public to everyone.

A list of 14 or so random words including both secret words is publicly displayed. Scanning through it can help you look for words that the other team might be cluing. If you find one that seems to match, you might then give clues pretending that's your word to test this theory and try to infiltrate their team.

### Veto phase

If you play with a veto phase, when a player guesses their team, the round does not end and nothing is revealed yet. Instead, there is a 45-second veto period where anyone may guess the opposing team's word. If someone does, this word guess takes precedence and immediately determines who wins the round, and the earlier team guess is ignored. Otherwise, if this period ends without anyone guessing a word, the original team guess goes through and decides the winner. 

A veto phase is not triggered when someone guesses the opposing team's word, and the round still ends as usual.

The idea of the veto phase is that if the other team that gives too obvious clues for their word and then quickly guesses their team, you have a bit of time to review their clues and check the word list to figure out their word and take the win. While usually players it's not among the guessed team who try to figure out the guessed team's word, anyone may submit a word guess, including a player who was guessed or even the guesser themselves.

### Partial team guesses

In games with many players, guessing your exact team is hard, so there's an option to allow guessing only part of your team. For example, in a 9-player game, you might play that you need to guess exactly 3 people on your team counting yourself. The guess counts as  right if all those people are your on team, even though some teammates won't be included.

## Playing on Discord

You can play on the [Shibboleth discord server](https://discord.com/invite/TmHxFfG). Just follow the link, click to accept the invite, and type in a name to show for you. If Discord asks for your e-mail to link your account, you can ignore this by clicking outside the prompt.

The bot automatically sends players their secret words and resolves guesses. Write `!help` to see the list of bot commands. You can play with your friends online at any time. If the Shibboleth user doesn't appear as online under "Bot", it must be offline -- please let the maintainer know.

It's recommended to play Shibboleth on a computer rather than a phone.

### Round logistics

The game usually happens in the channel `shibboleth-game`. Go to that channel and write `!join` to play in the next round. You can see who is playing in the panel on the right. Players' names are highlighted in chat. There can be multiple games going at once in the various game channels.

When a round starts, you'll get a DM (direct message) from the Shibboleth bot with your secret word. This will appear as a notication in "Home" (the Discord controller symbol) at the top of the list of channels on the left side. Click `Home`, then under direct messages click `Shibboleth` to see the message with your secret word. Then return to the game by clicking the Shibboleth server icon.

You clue by typing in the chat. If players agree, you can instead clue over voice. To join the voice channel, click the Voice Chat channel corresponding to the game room.

During a round, the list of words is pinned to the channel, and you can view it with the shortcut Ctrl+P or pressing the pin icon. There is unfortunately not a way to keep it open while typing a clue. You might want to open a separate broswer window with it. You can write  `!words` to display it in the channel, or `!words [your username]` to message it to yourself.

### Fairness

This games runs on the honor system. To make cluing fair:

- Don't look up information such as by Googling things
- Don't tell things to other players except through the chat

### Discord tricks

Use `@username` to direct your message to someone, such as to indicate that your message is aimed at them. You can reply to a message of theirs by clicking the `...` menu on their message on it and choosing `Quote`, such as to indicate that your clue confirms you understand their clue.

You might want to use Compact Mode when playing, which makes messages take up less space so you can see more clues. Set this by going to the setting gear next to your user name at the bottom, under `App settings` click `Appearance`, then check `Compact`.

#### Reactions

You can post reactions (emoji) on a message by clicking the smiley-face while hovering over it. You can also include them in your own message by clicking the smiley on the far right of the message box, or pressing Ctrl+E. You can also type the name like `:tree:`, which will autocomplete. Beware that the emoji might not appear exactly the same on different people's screens.

Reactions on a clue can be used as a shorthand to express what you think about it. Some emoji with a conventional meaning are listed in the Shibboleth server category for convenience. For example, the `:vouch:` star symbol expresses that you fully trust the cluer as being on your team, and the `:fishing:` rod accuses the cluer of cluing a word that isn't theirs as bait. These have no rules function and are just a means of communication. Feel free to suggest more emoji to add to the server.
