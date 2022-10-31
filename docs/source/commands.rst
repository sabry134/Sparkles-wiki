Commands
========

Moderation Module
-----------------

**Most of the moderation commands have a command that makes a specific request on the bot. For example for the kick command, it makes the request to kick the bot if the user did use the command. It is also logged if the logs are enabled. For this, it simply checks if the logs are enabled. If there are then it sends the message in the channel used and set by the user to send the logs.**

Build Module
------------

**The Build module is a list of commands that makes specific requests on the bot which are mostly about deleting channels, creating voice channels, creating chat channels or categories. The most special command is a command called "setup". This command automatically creates the most necessary channels to the bot.**

Fun Module
----------

**The Fun module is a list of commands making specific requests on the bot that varies from utilities commands to a chat bot. The chat bot is a command that checks the API and sends the reply to it. More informations about it can be found on the :ref:`API` page.**

Economy Module
--------------

** The economy module is a list of command that uses variables that is used for the number of crystals, containers, UT containers and skin containers. When a purchase is made, it first checks if the user has more or the same number as the price set. If it is not the case, an error message is displayed, else the purchase is made and the price is removed from the user's economy, and his item is added.**

.. autosummary::
   :toctree: generated

   lumache
