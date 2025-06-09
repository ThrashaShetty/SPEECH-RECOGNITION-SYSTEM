## SPEECH-RECOGNITION-SYSTEM

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: THRASHA SHETTY

*INTERN ID*: CT04DN376

*DOMAIN*: ARTIFICIAL INTELLIGENCE

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

## TASK DESCRIPTION

Speech Recognition Tool using Natural Language Processing

This Python program is a GUI-based Speech-to-Text Transcription App built using the tkinter library for the graphical interface and the speech_recognition library for converting spoken words into written text. The app allows users to record their voice through a microphone, transcribe it into text, and view or save that transcription in real-time. This Python desktop application effectively combines two powerful Python libraries—tkinter for the user interface and speech_recognition for handling audio input and speech recognition—to create a seamless experience. The application is structured using object-oriented programming principles, ensuring modularity, reusability, and easy maintenance. It provides a clean, interactive GUI for users to operate with ease, featuring clear buttons and a scrollable text area. The primary goal of this application is to offer a simple, user-friendly way to transcribe speech into text. It is suitable for tasks like dictation, creating written notes from meetings or lectures, or helping users with accessibility needs who may find speaking easier than typing.

How it works:The Speech-to-Text App captures audio from the user through the microphone and converts it to text using Google's powerful cloud-based speech recognition API. When the user clicks the “Start Recording” button, the app begins to listen actively to the microphone input while showing a status message indicating calibration and recording phases. The audio is recorded for a limited duration (up to 10 seconds), ensuring that the app does not hang indefinitely. Once the recording is complete, the captured audio is sent to the speech recognition service, which transcribes it into written text. The result is then displayed in a scrollable text box, allowing users to review and edit the text if needed. If the auto-save option is enabled, the app saves the transcription automatically in a timestamped text file, making file management easy and organized. Additionally, users have control over stopping the recording early, clearing the text box, and switching between dark and light themes for visual comfort. The app runs smoothly by performing audio capture and transcription in a background thread, preventing the user interface from freezing. Comprehensive error handling ensures that users receive meaningful feedback if issues occur, such as microphone timeouts or network errors.

Key Components: tkinter: Used to build the graphical interface. It provides windows, buttons, labels, text areas, and themes.

speech_recognition: A Python library that allows voice input from the microphone and converts it to text using an online API (like Google’s).

threading: Used to keep the GUI responsive while audio recording and transcription are performed in the background.

datetime: Generates timestamps for naming the output transcription files.

sys.stdout.reconfigure: Ensures Unicode characters (like emojis) are supported in the terminal or output window.

Key features: The Speech-to-Text Transcription App offers real-time voice recognition by converting spoken words into text using Google’s speech API. It features a clean and easy-to-use interface with controls to start, stop, and clear recordings. The app automatically saves transcriptions with timestamps for convenient file management. Users can switch between dark and light themes to enhance visual comfort. Additionally, it runs smoothly with background threading and includes robust error handling for a seamless experience.

Real word Applications: This Speech-to-Text app can be used in real-world settings to quickly transcribe meetings, lectures, or interviews, improving efficiency and accessibility.

Note Taking: Students and professionals can use this to take quick voice notes.

Accessibility: Helps users with physical impairments who cannot type.

Interviews/Meetings: Journalists or meeting participants can transcribe spoken content automatically.

Language Practice: Learners can test pronunciation and clarity by seeing how well their speech is transcribed.

In essence, this application offers a user-friendly interface for converting spoken language into written text, with several practical features such as auto-saving, theming, and error handling. The use of threading ensures smooth performance without GUI interruptions. By integrating the speech_recognition library, the program leverages powerful cloud-based transcription capabilities, making it suitable for simple dictation tasks, note-taking, or accessibility tools. Its clear layout and intuitive controls make it accessible even for non-technical users.

## OUTPUT

![Image](https://github.com/user-attachments/assets/5b721e75-0e97-4482-94a7-1cf0b25fa625)

![Image](https://github.com/user-attachments/assets/37b92bd5-30d3-4452-b914-468d31231ad1)








