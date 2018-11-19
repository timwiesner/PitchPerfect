# PitchPerfect
## Project for Udacity's iOS App Development Nanodegree

This Pitch Perfect app is the first project for Udacity's iOS App Development Nanodegree course. 

## Implementation
This app uses `AVFoundation`  and `AVAudioRecorder` to allow users to record a sound with their device's built-in microphone. 

`AVAudioPlayer` handles playback of the recording and `AVAudioEngine` is used to apply the following sound effects: Snail (slow), Rabbit (fast), Chipmunk (high pitch), Darth Vader (low pitch), Parrot (echo), and Reverb. 

## Scenes
- **RecordSoundsViewController**: contains 1) a record button with microphone image and 2) a stop button to halt recording. When the microphone button is pressed, the app begins recording and the stop button is enabled. When the stop button is pressed, the app finishes the audio recording and performs a segue to the PlaySoundsViewController.
- **PlaySoundsViewController**: contains 1) six sound effect buttons (snail, rabbit, chipmunk, Vader, parrot, and reverb) which play the recorded sound file with their respective modulations and 2) a stop button that enables users to halt playback. A back button is also present to return users to the RecordSoundsViewController scene.

## Requirements
 - Xcode 9 +
 - Swift 4.0 +
