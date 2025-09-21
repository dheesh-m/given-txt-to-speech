Speech synthesis (or Text to Speech) is the computer-generated simulation of human speech. It converts human language text into human-like speech audio. In this tutorial, you will learn how to convert text to speech in Python.

Please note that I will use text-to-speech or speech synthesis interchangeably in this tutorial, as they're essentially the same thing.

In this tutorial, we won't be building neural networks and training the model from scratch to achieve results, as it is pretty complex and hard to do for regular developers. Instead, we will use some APIs, engines, and pre-trained models that offer it.

More specifically, we will use four different techniques to do text-to-speech:

gTTS: There are a lot of APIs out there that offer speech synthesis; one of the commonly used services is Google Text to Speech; we will play around with the gTTS library.
pyttsx3: A library that looks for pre-installed speech synthesis engines on your operating system and, therefore, performs text-to-speech without needing an Internet connection.
openai: We'll be using the OpenAI Text to Speech API.
Huggingface Transformers: The famous transformer library that offers a wide range of pre-trained deep learning (transformer) models that are ready to use. We'll be using a model called SpeechT5 that does this.
To clarify, this tutorial is about converting text to speech and not vice versa. If you want to convert speech to text instead, check this tutorial.

Table of contents:

Online Text to Speech
Offline Text to Speech
Speech Synthesis using OpenAI API
Speech Synthesis using 🤗 Transformers
To get started, let's install the required modules:
