# JARVIS - Your Personal AI Assistant 

Welcome to the JARVIS project! This web-based application is designed to act as a personal AI assistant and is capable of voice commands, facial expression analysis, and more. This README provides an overview of the code structure, features, and application usage.


## Overview
This project is a simple web-based AI assistant called JARVIS. It features a user interface where you can interact with JARVIS through voice commands, capture video from your webcam, and process face detection using the face-api.js library. 
</br>
This application consists of two main parts:
<ol>
  <li>
    HTML and CSS - Defines the structure and styling of the web page.
  </li>
   <li>
     JavaScript - Handles the functionality for voice recognition, facial expression analysis, and interactive features.
   </li>
</ol>

## Features
<ul>
  <li>Interactive User Interface: Includes a microphone button to initiate voice commands, a video feed, and buttons to capture and process video frames. </li>
<li>
  Face Detection: Uses face-api.js to detect, and analyze faces in the video feed.
</li>
<li>
    Audio Feedback: JARVIS provides spoken responses to user commands.
</li>
</ul>	


## Code overview
<ol>
  <li>
    <b>HTML and CSS components: </b> 
    <ul>
      <li>
        Meta Tags: Ensure proper character encoding, compatibility, and responsive design.
      </li>
      <li>
        CSS Links: Includes external stylesheets for Font Awesome icons and Google Fonts.
      </li>
      <li>
        Internal Styles: Styles for layout, colors, fonts, and responsiveness.
      </li>    
      <li>
        Audio Elements: For playing introductory and activation sounds.
      </li>
      <li>
        Main Section contains:
      <ul>
        <li>Input button: To start voice recognition.</li>
        <li>A video container for capturing video and a canvas for facial recognition analysis.</li>
        <li>Buttons: Capture, Process, and J.V.</li>
      </ul>
      </li>
    </ul>
  </li>
</br>
  <li>
    <b>Javascript Component</b>  </br>
    The Javascript file adds interactivity and functionality to the application.
    <ul>
      <li>
        Imports: Loads the face-api.js library for facial expression analysis.
      </li>
      <li>
        Model Loading: Loads pre-trained models for face detection, landmark recognition, and expression analysis.
      </li>
      <li>
        Event Listeners:
        <ul>
            <li>Capture Button: Accesses the camera and streams video to the video element. </li>
            <li>Process Button: Analyzes facial expressions from the video feed and updates the canvas.</li>
            <li>J.V. Button: Performs sentiment analysis based on facial expressions and responds accordingly.</li>
        </ul>
      </li>
      <li>
        Voice Recognition:
        <ul>
            <li>SpeechRecognition: Uses the Web Speech API for voice command recognition.</li>
            <li>Command Handling: Processes voice commands to perform various actions like opening websites or providing information.</li>
        </ul>
      </li>
      <li>
        Facial Expression Analysis:
        <ul>
          <li>Analyze Expressions: Calculates the average expression values from detected faces and responds based on the predominant emotion.
          </li>
          <li>
            Based on the detected sentiment, JARVIS can open relevant content or provide comforting messages.
          </li>
        </ul>
      </li>
    </ul>
  </li>
</ol>

## How to use
<ol>
  <li>
    Opening the application: Load the HTML file in your browser
  </li>
  <li>
    Interacting with JARVIS: 
    <ul>
      <li>
        Click the microphone button to start voice recognition
      </li>
      <li>
        Use voice commands like "Jarvis, Open Wikipedia", "Jarvis, What's the time?" and "Jarvis, Play Believer". </br>
        Remember to use "Jarvis" before any command you give! </br>
        Also, make sure to give your command within 4 seconds.
      </li>
      <li>
        Click the Capture button to start the video stream.
      </li>
      <li>
        Click the Process button to analyze facial expressions
      <li>
        Click the J.V. button to analyze facial expressions and get a response based on detected emotions.
      </li>
    </ul>
  </li>
</ol>

## List of Commands available
Remember to use "Jarvis" before any command you give! 
<ol>
  <li>
    Hey/Hello
  </li>
  <li>
    What is your name?
  </li>
  <li>
    Open Google
  </li>
  <li>
    Introduce yourself
  </li>
  <li>
    Open YouTube
  </li>
  <li>
    Open Facebook
  </li>
  <li>
    Search "keyword"
  </li>
  <li>
    Chatgpt
  </li>
  <li>
    Bitcoin
  </li>
  <li>
    Game
  </li>
  <li>
    Wikipedia "keyword"
  </li>
  <li>
    Time
  </li>
  <li>
    Play "keyword"
  </li>
  <li>
    Date
  </li>
  <li>
    "keyword" Youtube
  </li>    
  <li> 
    Shutdown
  </li>
  <li>
    Many more commands that can be searched on Google.
  </li>  
</ol>


## Dependencies
<ol>
  <li>
    face-api.js: For facial expression analysis.
  </li>
  <li>
    Google Fonts: For the custom font "Roboto Mono".
  </li>
</ol>


## Conclusion
This README provides an overview of the JARVIS web application, including its structure, features, and code functionality. Feel free to explore the code to fit your needs. For any issues, please do contact us.
