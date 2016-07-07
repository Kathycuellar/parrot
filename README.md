# Parrot
Telegram Bot for transcribing voice messages via wit.ai

## Requirements
You need to install ffmpeg.

## Getting started
- Create a telegram bot
  - Set privacy to ```Disable```
  - Add a command called ```setlanguage```
- Create a wit.ai app for each language you want to support
- Copy ```config.sample.json``` to ```config.json```, add the telegram / wit tokens and specify your ffmpeg path
- Start it with ```npm start```

## Demo
You can add the ```@parrotparrot_bot``` to your group and it will transcribe your voice messages. To change from english to german enter: ```/setlanguage DE```.
But remember it is only for demonstration purpose.
