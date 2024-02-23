+++
title = "WhatsApp Transcription app"
subtitle = "WhatsApp Transcription for Deaf Users to use voice notes."
tags = ['project']
date = 2020-08-01

# For description meta tag
description = "Personal projects"


# Comment next line and the default banner wil be used.
banner = 'img/AboutBanner.jpeg'

+++

## Overview
Developed a WhatsApp transcription application that serves as a translation service for deaf individuals. The application converts voice messages into text, allowing seamless communication between users, especially for those with hearing impairments.


## Key Features:

Utilizes WhatsApp Business API for message handling.
Transcribes audio messages using OpenAI's Whisper ASR model.
Implements Flask for webhook handling and message delivery.
Provides a user-friendly interface for easy communication.

## How it Works
: Receives incoming audio messages through the WhatsApp API.
Downloads and transcribes the audio using OpenAI's Whisper ASR model.
Sends back the transcribed text to the user via WhatsApp.

## Technologies Used:

- Python (Flask) for backend development.
- OpenAI API for audio transcription.
- WhatsApp Business API for message handling.

## Impact:
Facilitates inclusive communication, enhancing accessibility for deaf individuals using WhatsApp. The application ensures that users can easily engage in conversations by transcribing voice messages into text.

## Future Improvements:
Continued enhancement of the application's features, potential integration with additional languages, and optimizing for faster response times.

*Note*: Ensure compliance with privacy and ethical considerations when using and showcasing the application.

[github repository](https://github.com/one-eyed-bat/whatsapp_webhook)

![code snippet](/img/WhisappCode.webp)