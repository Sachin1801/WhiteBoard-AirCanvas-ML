# Air Canvas

Computer Vision project with OpenCV and Machine Learning using Mediapipe:

Imagine being able to create art just by waving your hand in the air. Imagining this necessity I tried to implement an Air Canvas that allows us to draw anything by tracking hand landmarks and gestures. This project showcases the power of Machine Learning combined with Computer Vision techniques using OpenCV. The preferred language for implementation is Python due to its extensive libraries and user-friendly syntax, but the basic principles can be applied to any language that supports OpenCV.

The algorithm for the Air Canvas project is as follows:

1. Read the video frames and convert them to the HSV color space for easy color detection.
2. Prepare the canvas frame and add buttons for different ink colors.
3. Adjust the parameters of the Mediapipe initialization to detect only one hand.
4. Utilize Mediapipe's hand detection to identify the landmarks on the detected hand.
5. Specifically, extract the coordinates of the index finger and store them in an array for successive frames. This array will be used to track the drawing points on the canvas.
6. Finally, draw the points stored in the array onto the video frames and the canvas, creating the illusion of drawing in the air.
Requirements for this project include Python 3, numpy, OpenCV, and Mediapipe libraries installed on your system.

<img width="1792" alt="Screenshot 2023-08-01 at 11 59 51 PM" src="https://github.com/Sachin1801/WhiteBoard-AirCanvas-ML/assets/87144268/5245ab59-ff5b-4d46-a5ce-4ec6a0474ef7">
