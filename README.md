Hearing Impairment Assistant
This project aims to assist individuals with hearing impairments by translating spoken words into visual representations using sign language GIFs and images of letters. The application leverages speech recognition to identify spoken words and display corresponding sign language animations or images.

Features
Speech Recognition: Uses Google's speech recognition API to transcribe spoken words.
Sign Language GIFs: Displays animated GIFs representing common phrases in sign language.
Alphabet Images: Shows images of individual letters when spoken words are detected.
Graphical User Interface (GUI): Utilizes Tkinter for displaying GIFs and images.
Requirements
Python 3.x
speech_recognition
numpy
matplotlib
opencv-python
easygui
Pillow
tkinter (usually included with Python)
Install the required Python packages using pip:

bash
Copy code
pip install SpeechRecognition numpy matplotlib opencv-python easygui Pillow
How to Use
Clone the Repository

bash
Copy code
git clone https://github.com/TheVinnay/audio-to-sign-language-converter.git
cd hearing-impaired-assistant
Prepare Your Environment

Make sure all required packages are installed. If not, install them using the provided pip command.

Prepare Sign Language GIFs and Alphabet Images

Place your sign language GIF files in the ISL_Gifs directory.
Place the images of letters in the letters directory. Ensure each image file is named with the corresponding letter (e.g., a.jpg, b.jpg, etc.).
Run the Application

Execute the main script:

bash
Copy code
python main.py
Follow the prompts to start recognizing speech and displaying sign language GIFs or alphabet images.

Code Overview
func(): Main function to handle speech recognition and display of sign language GIFs or alphabet images.
ImageLabel: Custom Tkinter label class for displaying GIFs.
Main Loop: Provides a GUI for the user to choose between live voice recognition or exiting the application.
Notes
Ensure your microphone is working and properly configured.
The application continuously listens for speech input until 'goodbye', 'good bye', or 'bye' is spoken.
Modify the list of common phrases and their corresponding GIFs as needed.
Contributing
Feel free to open issues or submit pull requests to improve the application. Contributions are welcome!
