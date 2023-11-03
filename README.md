# BirdCall_Filtering
Filtering audio data using the concepts of FIR

# Audio Processing in Python

## Overview

This Python script performs audio processing tasks such as loading audio, computing spectrograms, applying FIR filters, and playing audio. 

## Prerequisites

Before running the code, make sure you have the following Python libraries installed:
- NumPy
- SciPy
- Matplotlib
- IPython (for audio playback)

You can install these libraries using pip:

```bash
pip install numpy scipy matplotlib ipython

Usage
Clone or download this repository to your local machine.

Place your audio file in the same directory as the Python script. Ensure the audio file is in a supported format (e.g., WAV or MP3).

Modify the script to specify the correct audio file name:

python
Copy code
fs, bc = wavfile.read('your_audio_file.wav')
Run the Python script in your preferred Python environment.

The script will compute a spectrogram, apply FIR filters to different frequency ranges, and play the original and filtered audio. The results will be displayed in the matplotlib window, and you will hear the audio through your computer's audio output.




