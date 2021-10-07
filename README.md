# Conversational-AI-Assistant
It is a voice assistant that can engage in human-like dialogue, capturing context and providing intelligent responses. Its counterparts include Automatic Speech Recognition, Natural Language Processing, Text-to-Speech Synthesis, etc. It can also perform day-to-day functions like sending an e-mail, play music, web-scraping, search YouTube, launch programs etc.

To run this program you will require a bunch of API keys. You will need to register your API key for OpenWeatherMap API, Wolframalpha and Google Calendar API.

## Steps to follow for running the Assistant:
  1. Update the config.py file in Assistant\configuration folder path with your mail ID, password and Wolframalpha API key.
  1. Make a new python environment If you are using anaconda just type: **conda create -n jarvis python==3.8.5**, in anaconda prompt.
  1. To activate the environment: **conda activate assistant**.
  1. Navigate to the directory of the project.
  1. Install all the requirements: **pip install -r requirements.txt**.
  1. Install PyAudio from wheel file by following instructions given here.
  1. Run the program: **python mymain.py**.

## To add new features to your assistant:
  1. Make a new file in features folder, write the feature's function you want to add.
  1. Add the function's definition in __init__.py
  1. Add the voice commands through which you want to invoke the function.

We use NVIDIA's Jarvis, an application framework for multimodal conversational AI services that delivers real-time performance on GPUs, to perform sophisticated conversational AI tasks. We use NVIDIA Riva, which is a fully accelerated SDK for building multimodal conversational AI applications that use an end-to-end deep learning pipeline.
