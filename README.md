description :::  This Python script uses OpenAI's Whisper model to transcribe audio files into text. It allows the user to input the full path of an audio file, and upon successful transcription, it prints the transcribed text. It supports various audio file formats for transcription.  



readme :::

# Audio Transcription using OpenAI Whisper

This project provides a simple Python script that uses OpenAI's Whisper model to transcribe audio files into text. The script prompts the user to input the full path to an audio file, processes it using Whisper, and prints the transcribed text.

## Features
- Transcribe various audio file formats such as .mp3, .wav, .m4a, .flac, and more.
- Simple command-line interface where users input the path to the audio file.
- Uses OpenAI's Whisper model to perform transcription, providing accurate and reliable results.

## Installation

Before running the script, ensure that you have installed the required dependencies.

### Step 1: Install Whisper

You need to install the Whisper model and its dependencies. Run the following command to install Whisper:

```bash
pip install git+https://github.com/openai/whisper.git
