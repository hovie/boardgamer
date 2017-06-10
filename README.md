# boardgamer

Board Gamer is an Alexa Skill that enables you ask questions about board games using only your voice.
Special thanks to the developers and BoardGameGeek.com for the BGG API, and the [lcosmin](https://github.com/lcosmin) for the [boardgamegeek](https://github.com/lcosmin/boardgamegeek) API.

From the Full Skill Description:
You can use Board Gamer to ask for board game information sourced from BoardGameGeek.com.

You can ask for board game descriptions and stats, such as playing time, number of players, mechanics, etc.
"Alexa, ask Board Gamer about Pandemic Legacy."
"Alexa, ask Board Gamer for Twilight Struggle description."
"Alexa, ask Board Gamer how many people can play Terra Mystica."
"Alexa, ask Board Gamer for Terraforming Mars mechanics."

If you configure your BoardGameGeek username, you can also ask Board Gamer to choose a game from your collection by saying:
"Alexa, ask Board Gamer to choose a game", or
"Alexa, ask Board Gamer for a thirty minute game" or
"Alexa, ask Board Gamer for a five player, one and a half hour game"

Ask Board Gamer to tell you the size of your BGG game collection by saying:
"Alexa, ask Board Gamer how many games I own."

To confirm which BGG username is configured, you can have Board Gamer say or spell the username.
"Alexa, ask Board Gamer to say my username"

Known issues and limitations:
- Partial or base game name searches can be inaccurate. Board Gamer looks for closest matching full name, starting with the games in the Hotness, and then from a list of roughly the top 1000 games.
  For example, "Caverna" is a closer match for "Cartagena" than "Caverna: The Cave Farmers".
- no support asking for a range for number of players or playing time. Need to ask for a specific player count or time for best results.
  For example, say "Choose a game for five players" instead of "Choose a game for three to five players".
- ... and probably more. :)


(Board Gamer is personal project and not affiliated with BoardGameGeek.com)
