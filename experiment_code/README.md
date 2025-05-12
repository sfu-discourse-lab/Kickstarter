# Experiment Code

## Overview

This folder contains all necessary code required to run the Kickstarter Seed experimental study. The basis of the experiment procedure is that participants listen to an audio clip, and then are instructed to rate their agreement of that audio clip on a Likert scale. This procedure is run as a loop for repeated randomized trials over the course of the experiment. The content of the audio clips in the experiment stimuli consists of audio recordings of Canadian political videos available on YouTube Shorts. The procuedure in which the stimuli were gathered are outlined in ```audio_scraper.ipynb``` and ```text_scraper.ipynb```.

The experiment is run on JATOS framework, using JsPsych as its method of delivery.

## Installation & Usage

A local installation of JATOS is required to run the code in this folder. Its installation as well as instructions can be found [here](https://www.jatos.org/Installation.html).

Within the local machine, ensure that the files are placed within the ```study_assets_root``` subfolder of the JATOS installation folder.

## Usage of the code with different datasets

The code in experiment.html makes a call to the file ```stimuli.js```, which consists of an array of filepaths to be used by the code's sampling mechanic. The code has been set up to sample files from a folder within its directory named ```media```, where files must be placed. To use this experiment code with a different dataset, substitute the content of ```stimuli.js``` with the desired array of data to use, such as audio files of a different language, and ensure their filepaths are contained within the ```media``` subfolder.



