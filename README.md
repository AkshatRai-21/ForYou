
# See With Sound

Responsive Flutter App - Works on Android, iOS & Web! 

Our app is designed to help visually impaired people navigate their daily lives more easily. It utilizes DALL-E and ChatGPT APIs to allow voice instructions and text-based responses. The app reads out the response if it is not an image. This provides an accessible way for visually impaired individuals to communicate and access information.



## Features

- Generates A.I. images using DALL-E
- Uses ChatGPT API 
- Take voice command
- Readout the result 
- Works on android , ios and web



## Installation

To get started with this application, you will need to have the following:

- Flutter SDK installed on your computer
- ChatGPT API key
- An Android or iOS device

Once you have these requirements, follow these steps to run the application:

1.Clone the repository to  your local machine using the command:

```bash
  git clone  https://github.com/AkshatRai-21/SeeWithSound.git
```
2.Navigate to the project directory and run
```bash
flutter pub get
```
 to install the dependencies.

3.Open the ```lib/secrets.dart``` file and replace the ```openAIAPIkey``` placeholders with your actual API keys.

4.Connect your Android or iOS device to your computer and run
```bash 
flutter run
```
Then run the following commands to run your app on web :
```bash
    
    flutter run -d chrome --web-renderer html (to see the best output)

```
 

     ## How to Use the App
1.Launch the app on your device and grant microphone permissions if prompted.

2.Tap the microphone icon to start recording your voice input.

3.Speak your instruction into the device's microphone.
Wait for the app to generate a response.

4.If the response is not an image, the app will read out the response to you.