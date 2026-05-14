# bpmdetector

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A real-time BPM detection web app using the aubiojs library, a WASM version of the aubio audio processing library.

## Demo
~~https://code4fukui.github.io/bpmdetecor/~~ *(unavailable)*

## Features
- Real-time BPM detection from microphone input
- Visualizes the detected beats with a blinking indicator
- Provides average BPM and recent beat timestamps
- Allows adjusting detection parameters like window size, hop size, and sample rate

## Requirements
This web app runs in modern web browsers and requires access to the user's microphone.

## Usage
1. Click the "Start microphone" button to begin BPM detection.
2. Adjust the detection parameters as needed using the provided controls.
3. The current BPM and recent beat timestamps will be displayed.

## License
MIT License — see [LICENSE](LICENSE).