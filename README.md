# RockPaperScissor with Real Time Hand Detection And Evaluation Using Open CV and MediaPipe

This Python script creates an interactive Rock-Paper-Scissors hand game that you can play using your webcam. The game utilizes the MediaPipe and OpenCV libraries to detect hand gestures and determine the winner based on Rock, Paper, or Scissors signs.

Prerequisites
Ensure you have the following libraries installed:

1) OpenCV (cv2)

2) MediaPipe (mediapipe)

You can install these libraries using the following command:

	pip install opencv-python mediapipe

 ----------How to Play----------
 
1) Clone this repository to your local machine.


2) Make sure your webcam is functional and accessible to the script.


3) Run the script using a Python interpreter.


4) When the game starts, you'll see a countdown: "READY?", "3...", "2...", "1...", "GO!".


5) After the countdown, make Rock, Paper, or Scissors hand gestures in front of the webcam.


6) The game will detect the gestures of both players and determine the winner.


7) The result will be displayed on the screen, showing which player wins or if the game is tied.



--------Rules-------

1) Rock beats Scissors

2) Scissors beats Paper

3) Paper beats Rock


-------Important Notes----


This script assumes a two-player game.


For accurate hand gesture detection, ensure proper lighting and hand positioning.


Gestures may need to be exaggerated for better detection.


You can adjust detection parameters (model_complexity, min_detection_confidence, min_tracking_confidence) as needed.


Feel free to customize and enhance the script to suit your preferences. Enjoy playing the Rock-Paper-Scissors game with hand gestures! 

If you encounter any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request. 

Have fun!
