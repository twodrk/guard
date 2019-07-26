.. raw:: html

  <img src="https://i.imgur.com/RtXS5Yo.png" width="150" align="right">

EduuRobot
=========

This is a complete rewrite of bot's code with Python + Pyrogram

Requirements
============
- Python 3.6+
- A Linux operating system (Windows may work, but isn't tested yet)

Setup
=====
- Install the required modules from the requirements.txt with ``pip3 install -rU requirements.txt``
- Go to https://my.telegram.org/apps and create a new app
- Create a config.ini file with the following:
.. code-block::

  [pyrogram]
  api_id = YOUR_API_ID_HERE
  api_hash = YOUR_API_HASH_HERE
- Create a new ``config.py`` file from the ``config.py.example`` file (``cp config.py.example config.py``)
- Put your tokens, ids and keys to your config.py file

Running
=======
- To run the bot you just need to run ``python3 bot.py``
- Running it on `screen <https://en.wikipedia.org/wiki/GNU_Screen>`__ or `tmux <https://en.wikipedia.org/wiki/Tmux>`__ is highly recommended if you want to keep the bot running for long times