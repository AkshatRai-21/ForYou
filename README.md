## DALL-E and ChatGPT Assistant App

This is a Flutter application that utilizes the DALL-E and ChatGPT APIs to allow users to provide voice instructions and receive text-based responses from the app.

The app uses the device's microphone to capture the user's voice input, which is then processed by the DALL-E and ChatGPT APIs to generate a response. If the response is not an image, the app will read out the response to the user.

# Getting Started
To get started with this application, you will need to have the following:

 Flutter SDK installed on your computer
 DALL-E and ChatGPT API keys
 An Android or iOS device

Once you have these requirements, follow these steps to run the application:

  Clone the repository to your local machine using the command git clone 
  https://github.com/AkshatRai-21/Voice-Assistant.git
  Navigate to the project directory and run flutter pub get to install the dependencies.
  Open the lib/secrets.dart file and replace with your YOUR_CHATGPT_API_KEY placeholders with your actual API keys.
  Connect your Android or iOS device to your computer and run flutter run to build and run the application on your device. 

# How to Use the App
  
  Launch the app on your device and grant microphone permissions if prompted.
  Tap the microphone icon to start recording your voice input.
  Speak your instruction into the device's microphone.
  Wait for the app to generate a response.
  If the response is not an image, the app will read out the response to you.  