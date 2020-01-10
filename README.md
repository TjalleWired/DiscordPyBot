# DiscordPyBot

## Disclaimer
 At this moment in time, the bot only fully works in Windows 10.

 This is because it has been developed and tested on this platform.
 
 I am in the works of making a Ubuntu compatible version as we speak, but the windows version has priority.
 (Note; most functions do work on ubuntu, but they can spit unneccesairy errors, also the tmp file system isnt working on Ubuntu)

### Tech

DiscordPyBot uses a number of Python libraries to work properly:

* [PRAW](https://pypi.org/project/praw/)
* [wikipedia](https://pypi.org/project/wikipedia/)
* [Discord.py](https://pypi.org/project/discord.py/)
* [google_images_download](https://pypi.org/project/google_images_download/)
* [deeppyer](https://pypi.org/project/deeppyer/)

Use the provided ```installPip.bat ``` (located in installation files folder) script to install all the PIP libraries for you.

###  Installation and Configuration

Install all required pip files by running ```installPip.bat ``` which is located in the installation files folder.

 The only file that needs configuration right now is the "credentials.py"
 Edit the "example_crediantials.py" with your own credentials, and rename the file to "credentials.py"

### Running the Bot

Run in the source directory using:
```sh
py ./main.py
```
Or using your own preferred method. Just run main.py

### Current commands

 * !help - See available commands
 * !ping - Pong!
 * !wiki (wikiarticle) - Get a wiki article
 * !imgwiki (wikiarticle) - Get the first image on a Wiki Article
 * !rkarma (redditUserName) - Get an user's total karma on reddit
 * !sourcecode - Get a GitHub link to the bot's source code
 * !imgsearch (query) - Google and post an image
 * !deepfry (imgSearch) - Google and deepfry an image

### Planned Updates
 
 * More reddit API feature implementations
 * Add some form of music player (spotify and/or youtube)
 * add gay-o-meter
 * ...