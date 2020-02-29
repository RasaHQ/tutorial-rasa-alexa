<img src="square-logo.svg" width=200 height=200 align="right">

# Tutorial: Building a Rasa-powered Alexa Assistant

This repository contains the code of the tutorial of connecting Rasa-powered assistant to Alexa. You can find the [step-by-step tutorial here](ADD LINK) or in [this YouTube Playlist](https://www.youtube.com/playlist?list=PL75e0qA87dlGBbO8rWacgq9ejr5stsGnh).

## What's in this repository?

This repository consists of the following files and directories:  
- **mood_bot_text** - a directory which contains a pre-built Rasa assistant called Moodbot Text, based on the [Moodbot](https://github.com/RasaHQ/rasa/tree/master/examples/moodbot) example that's built when you run `init rasa`. This assistant is used to demonstrate the integration to Alexa.
- **alexa_schema.json** - a custom Alexa configuration file that will create an intent and slot to return the user's complete response.
- **alexa_connector.py** - a custom Rasa-Alexa Assistant connector. If you follow the tutorial using your own assistant, add this connector to your project directory.

## How to use this repository?

The best way to use this repository is to follow [this step-by-step tutorial](ADD LINK) on how to integrate the Rasa assistant to Alexa. 

You can download the code for this repository by running:

`git clone https://github.com/RasaHQ/tutorial-rasa-alexa.git`

From here, install the required packages in your virtual environment by running:

 `cd tutorial-rasa-alexa/mood_bot_text
 pip install -r requirements.txt`

You should now be able to train your assistant using:

	`rasa train`

Once your assistant is trained, you can try interacting with it in the shell by running: 

	`rasa shell`


## Let us know how you are getting on!

If you have any questions about this tutorial or this repository, feel free to share them on [Rasa Community Forum](https://forum.rasa.com). 
