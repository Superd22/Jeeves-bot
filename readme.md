# Jeeves Concierge Bot
Jeeves is butler bot for #concierge Spectrum's channel.

# Commands list

**every commands must start with !jeeves**

ex: `kill add @Haverson` in this guide will be `!jeeves kill add @Haverson` on Spectrum

## Chat Kills & Saves
There is a rudimentary kill system in place to track who killed the #concierge chat and when. (and who saved it)
see : http://whokilledconcierge.com/

**rules** 
- Is presently considered a chat-kill any period of time where the chat is inactive for more than *10 minutes* after having been previously active
- Is presently considered a chat-save a message triggering activity after any period >5 mins without talking.

**commands**
- `kill add @Handle` 
    Adds a chat-kill to @Handle's killcount
- `kill top`
    Displays a top-3 list of people with the most kills
- `kill remove last`
    Remove the last added kill.
- `save add @Handle`
- `save top`
- `save remove last`


## Giftables
You can ask Jeeves to give you certain very basic amenities

*note: in every case here, the (@handle) is optional, if supplied Jeeves will gift to @Handle from you.
If not supplied, jeeves will gift to you.* 

**commands**
- `top hat (@Handle)` 
    Gifts a top hat
- `pizza (@Handle)`
    Bakes and brings a pizza
- `tea (@Handle)`
    Brews and brings tea
- `coffee (@Handle)`
    Warms and brings coffee
- `coffeemate (@Handle)`
    Enhances coffee with a creamer
- `wine (@Handle)`
    Selects and serves wine
- `beer (@Handle)`
    Opens and serves beer

## ATV
- `atv is out` check if the ATV for this week is out.

## MOTD
staff/admins/mods as well as a select few people can set the Message Of The Day for concierge.
- `motd set [breakline]` set the motd to whatever is after the line break
- `motd` display the current motd

## Misc.

**commands**
- `isup`
    Displays whether or not the bot is up and running.
- `rules (details)?`
    Displays the rules/laws jeeves will *always* follow.
    
    Note:`!jeeves rules details` will display more specific rules.
- `roll NdX` Rolls N dices of size X 

    *1<=N<=100 (only 20 in public lobbies) & 1<=X<=100*
- `when (question|release date)`
    *Where (question|release date) is a desired release date.* Will use machine learning on the spectrums/forums/reddit to try and come up with a best estimate as to when required featured will release.
    
    Example: `!jeeves when will 3.0 be out ?` will compute most likely release date.
- `help`
    Displays an unhelpful help screen
