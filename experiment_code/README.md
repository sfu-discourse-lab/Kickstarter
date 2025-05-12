# Experiment Code

## Overview

This folder contains the code to run the experiment

It runs on JATOS as a system and uses JsPsych as its method of delivery

## Installation & Usage

A local installation of JATOS is required to run the code in this folder. Its installation as well as instructions can be found [here](https://www.jatos.org/Installation.html).

Within the local machine, ensure that the files are placed within the ```study_assets_root``` subfolder of the JATOS installation folder.

## Usage of the code with different datasets

The code in experiment.html makes a call to the file ```stimuli.js```, which consists of an array of filepaths to be used by the code's sampling mechanic. The code has been set up to sample files from a folder within its directory named ```media```, where files must be placed. To use this experiment code with a different dataset, substitute the content of ```stimuli.js``` with the desired array of data to use, such as audio files of a different language, and ensure their filepaths are contained within the ```media``` subfolder.



