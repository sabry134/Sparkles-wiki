API
===

List of the following commands using an API and how is the request made.

Ratings
-------

!ratings - Shows the Tanki Online ratings of the specified username. More informations are available here::

   API: https://ratings.tankionline.com/api/eu/profile/

**Algorithm:** This command takes the rating API and parses it to take the following data:
   - Kills
   - Deaths
   - K/D
   - Earned Crystals
   - Gear Score
   - Active Premium
   - Gold Boxes caught
   - Battle Statistics
   
Once the data is parsed, it is sent to the bot and the parsed data is retrieved on the ratings command.

Lyrics
------

!lyrics - Gets the lyrics for the given song title. More informations are available here::

   API: https://some-random-api.ml/lyrics?

**Algorithm:** The lyrics command first of all parses the argument and is sent to the API as an argument. The API makes the request with the specified argument and gets the music lyrics. Therefore the music lyrics are parsed and sent back to the bot. Once the bot receives the lyrics, the bot sends a reply to the user with the lyrics.

Online
------

!online - Shows the number of online players and in battle players on Tanki Online. More informations are available here::

   API: https://balancer.eu.tankionline.com/balancer

**Algorithm:** The API is divided into 10 sections representing the servers. The command parses the number of online players on each server and makes a calculation to add them up to retrieve the total number of online players. 

Start
-----

!start -  Enables the ChatBot system. You must have the Moderate Members permission to enable it. More informations are available here::

   API: http://api.brainshop.ai/get?bid=157572&key=3IwX8FUcY1MBGlQV&uid="1

**Algorithm:** The API receives an argument given by the player. The argument is represented by any kind of text the user might write. This argument is added at the end of the API and is parsed. What's parsed is the reply of the bot. Once it is done, the bot retrieves the answer and sends it to the user.

Webstatus
---------

!webstatus - Gives you the status of the specified website. The url must start with http or https. More informations are available here::

   API: The link given as an argument.

**Algorithm:** The bot sends a request to the specified website. The website is represented by the user's argument. If the request result is successful, the website will be shown as online, otherwise it will be offline.


.. autosummary::
   :toctree: generated

   lumache
