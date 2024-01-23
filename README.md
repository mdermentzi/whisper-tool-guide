# Transcribing Oral Testimonies with Automatic Speech Recognition
#### *by Maria Dermentzi*

The purpose of this beginner-friendly tutorial is to demonstrate how you can use AI to automatically transcribe oral testimonies using Python. 
We'll be using OpenAI's [Whisper](https://openai.com/research/whisper) (Radford et al., 2022) Automatic Speech Recognition (ASR) model. 

Since all of the code is provided along with detailed instructions, you do not need to be familiar with computer programming in order to follow the steps. However, it is advised that you pay careful attention to the instructions.

##### Language support:
For supported languages and Whisper's Word Error Rate (WER) per language see [here](https://github.com/openai/whisper/blob/main/language-breakdown.svg) (the lower the error rate, the better).

##### Credits:
The audio files used in this tutorial were kindly provided by the [United States Holocaust Memorial Museum (USHMM)](https://www.ushmm.org/). You can follow this tutorial by downloading them from the subdirectory named `audio` which accompanies this tutorial.

## How to use
The Jupyter notebook included in this tutorial was designed to run in the Google Colab environment, taking advantage of Google's infrastructure and preinstalled software. 
To run it on Google Colab click [here](https://github.com/EHRI/ehri-data-analysis-tools/blob/master/automatic-speech-recognition/Oral_Testimonies_ASR_Tool_Guide.ipynb).

The notebook assumes (and was tested with) a **T4 GPU** runtime environment provided by Google Colab. Google Colab should automatically connect to a T4 GPU runtime. 
If it doesn't, follow the instructions found [here](https://www.geeksforgeeks.org/how-to-use-gpu-in-google-colab/) to change the runtime type manually.

Alternatively, if you are familiar with Python, installing Python packages and using Jupyter notebooks, you can download and run the Jupyter notebook on your local device.
You might need to install the correct version of Python and any packages that are not already installed on your device. 

This tutorial was built using **Python 3.10.12** and requires the following packages:


`faster_whisper 0.10.0`  
`pysubs2 1.6.1`

In case of installation errors, please consult the installation instructions of each package individually.

## How to cite
Dermentzi, M. (2024, January). Transcribing Oral Testimonies with Automatic Speech Recognition. EHRI Collection of Digital Tools Guides. https://github.com/EHRI/ehri-data-analysis-tools/tree/master/automatic-speech-recognition
