# WASHTONE DETECTOR

## Overview
This project is an audio-based fault detection application designed to identify anomalies in industrial machinery using sound analysis. The system enables non-invasive, scalable, and cost-effective monitoring, supporting predictive maintenance strategies.

## Intended End User
The primary users are maintenance engineers working in industrial environments such as manufacturing plants. These users are responsible for monitoring equipment health and preventing unexpected failures.

## Value Proposition
- Non-invasive monitoring (no physical sensors required)
- Lower cost compared to vibration-based systems
- Scalable across multiple machines
- Enables early fault detection through acoustic anomalies
- Supports predictive maintenance and reduces downtime

## Features
- Load and analyze audio files
- Playback functionality with volume control
- Real-time status, result, and scoring display
- Visualization tools:
  - Waveform
  - Spectrogram
  - Frequency spectrum

## Run Instructions
1. Open the application interface by clicking on app1.mlapp and run the app
2. Load an audio file by clicking load audio file button
3. Click the "Analyze" button
4. View results and system status
5. Playback audio if needed
6. Adjust volume using the sidebar
7. Review score and detection output
8. Select visualization type from dropdown

## Technical Stack
- Audio Processing: MATLAB
- Machine Learning: Classification Learner
- Frontend: MATLAB app builder
- Visualization: Matplotlib 

## Development Roadmap

###  Reliability Enhancements
- confidence scoring
- Implement error handling
- Ensure system stability under edge cases
