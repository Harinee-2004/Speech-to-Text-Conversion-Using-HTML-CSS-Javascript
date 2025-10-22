# Speech-to-Text-Conversion-Using-HTML-CSS-Javascript
# Speech-to-Text Web Application

This project is a simple web application that converts speech to text using the Web Speech API. The application starts recording when the "Start Recording" button is clicked and stops recording when the "Stop Recording" button is clicked. The recognized speech is continuously appended to the textarea, allowing you to speak in multiple sentences without interruption.

## Features

- Continuous speech recognition until explicitly stopped
- Appends recognized speech to a textarea
- Simple and intuitive interface
- Uses the Web Speech API

## Prerequisites

To run this project, you need:

- A modern web browser that supports the Web Speech API (e.g., Google Chrome)
- A microphone connected to your computer

## Getting Started

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/yourusername/speech-to-text-web-app.git
    ```

2. Navigate to the project directory:

    ```bash
    cd speech-to-text-web-app
    ```

3. Open the `index.html` file in your web browser to run the application.

## Usage

1. Open the `index.html` file in a modern web browser.
2. Click the "Start Recording" button to begin speech recognition. Grant microphone permissions when prompted.
3. Speak into your microphone. The recognized text will appear in the textarea.
4. Click the "Stop Recording" button to end speech recognition.

## Code Overview

### HTML

The HTML file defines the structure of the web application, including the textarea for displaying the recognized text and the buttons for controlling the recording.

### CSS

The CSS file styles the web application, providing a simple and clean user interface.

### JavaScript

The JavaScript code handles the speech recognition functionality:

- `createRecognition()`: Initializes the speech recognition object and sets up event handlers.
- `startRecording()`: Starts the speech recognition process and manages state.
- `stopRecording()`: Stops the speech recognition process and cleans up.

## Browser Compatibility

This application uses the Web Speech API, which is supported in the following browsers:

- Google Chrome (recommended)
- Microsoft Edge
- Safari

Note: The Web Speech API is not supported in all browsers. For the best experience, use Google Chrome.

