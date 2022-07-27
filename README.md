# Shazam Lite

Coding a lightweight version of Shazam to recognize songs through Fourier Transforms.

## Description

This Python program uses spectrograms of songs to match them in the same way as Shazam. Each song is first processed in order to be added to the database for later matching. This is generally done by taking a spectrogram of a song, selecting the most important peaks, and recording the time difference between peaks into the database. When matching a song, this same process is repeated to find its frequency/time difference "fingerprint" in order to look it up in the database. 

## Getting Started

### Dependencies

* There are several Python libraries that must be installed. Refer to the "Import" section at the beginning.

### Installing

* Install .ipynb file into a local directory
* Create a "mp3" folder with snippets of songs you want to add to the database. The song must be sampled at 44.1 kHz and with 2 channels.
* Create a "test_mp3" folder with snippets of songs you want to try matching. These can be mp3s from Youtube, for example.

### Executing program

* Since this is a Jupyter notebook, each block must be run sequentially using Shift + Enter. 

## Authors
* Bhushan Patel
* ENG-SCI 156: Signals and Communication class staff

## Acknowledgments
* Professor Flavio Calmon
* ENG-SCI 156: Signals and Communication class staff
