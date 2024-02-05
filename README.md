# Real-Time-Speech-Recognition
This project was built to have a system that can record live speech using your own microphone and transcribing it using speech recognition. Some usecases include, lectures, meetings and news.
I have utilized python and jupyter notebook for this project, and built interactive widgets for starting and stopping of recordings.

NOTE: You will have to see which index your microphone is assigned to in order to choose the right audio input

To begin we will need to install a few python packages such as:
- vosk (pip install vosk)
- pydub (pip install pydub)
- transformers (pip install transformers)
- torch (pip install torch -f https://download.pytorch.org/whl/torch_stable.html)
- pyaudio (pip install pyaudio)
- ipywidgets (pip install ipywidgets)

Vosk requires a separate file to be downloaded using this code:
from vosk import Model
Model(model_name="vosk-model-small-en-us-0.15")
