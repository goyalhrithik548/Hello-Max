# Hello Max

Hello Max is an advanced AI assistant capable of recognizing speech, detecting faces, recognizing emotions, and interpreting hand gestures. It leverages several state-of-the-art technologies and libraries to provide a comprehensive interaction experience. The project includes features like sending emails, retrieving weather information, and opening various applications on your computer via voice commands.

## Features

- **Voice Command Interaction:**
  - **Speech Recognition:** Converts spoken language into text using the Google Web Speech API through the `speech_recognition` library.
  - **Natural Language Understanding (NLU):** Comprehends the meaning and context of the text using the OpenAI GPT-3.5 model, employing advanced deep learning techniques for tokenization, part-of-speech tagging, named entity recognition, and syntactic/semantic parsing.
  
- **Face and Emotion Recognition:**
  - Uses the `face_recognition` library for face detection and recognition.
  - Utilizes `DeepFace` for emotion analysis.
  - Employs OpenCV (`cv2`) for processing video frames.

- **Gesture Recognition:**
  - Interprets human gestures using computer vision methods with the MediaPipe library, leveraging deep learning models and mathematical algorithms to detect and classify hand movements in real time.

- **Additional Functionalities:**
  - Sends emails via the `smtplib` library.
  - Controls volume using the `pycaw` library.
  - Retrieves real-time weather data with the `requests` library.
  - Interacts with web browsers and local applications.

## Installation

### Prerequisites

- Python 3.x
- Required libraries:
  ```bash
  pip install pywin32
  pip install SpeechRecognition
  pip install pyaudio
  pip install wikipedia
  pip install webbrowser
  pip install openai
  pip install nltk
  pip install requests
  pip install opencv-python
  pip install face-recognition
  pip install smtplib
  pip install matplotlib
  pip install deepface
  pip install mediapipe
  pip install pycaw
  pip install comtypes
  ```

### Setting Up the Project

1. Set up the necessary API keys:
   - **OpenWeatherMap API Key:** Replace `"your_api_key"` in the `get_weather` function with your actual API key.
   - **OpenAI API Key:** Replace `"your_api_key"` in the code block handling GPT-3.5 interactions.

2. Set up your email credentials for the `send_mail` function:
   - Replace `"your_email@gmail.com"` and `"your_password"` with your actual email and password.

## Usage

1. Run the main script to start the assistant:
   ```bash
   python hello_max.py
   ```

2. Interact with Hello Max using voice commands. For example:
   - "Send mail"
   - "Open YouTube"
   - "What's the weather in [location]?"
   - "Hello Max" (to initiate a conversation with the AI assistant)

3. Use hand gestures to control the volume:
   - Thumbs up to increase volume.
   - Thumbs down to decrease volume.

## Contributing

We welcome contributions to enhance the functionality of Hello Max. Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [SpeechRecognition Library](https://pypi.org/project/SpeechRecognition/)
- [face_recognition Library](https://github.com/ageitgey/face_recognition)
- [DeepFace Library](https://github.com/serengil/deepface)
- [MediaPipe](https://mediapipe.dev/)
- [OpenAI GPT-3.5](https://openai.com/)
- [OpenWeatherMap API](https://openweathermap.org/api)
