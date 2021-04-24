# Webcam Heart Rate Monitor

This project can monitor a user's heart rate in real time using just a webcam. It is a PPG ([Photoplethysmogram](https://en.wikipedia.org/wiki/Photoplethysmogram)) solution based on a color magnification [algorithm](http://people.csail.mit.edu/mrub/papers/vidmag.pdf) which makes it possible to see the color of your face change as blood rushes in and out of your head. This project allows you to visualize your face as it pulsates in real time. Since it is able to detect your pulses, it also calculates your heart rate in beats per minute (BPM). 

To quit the program press 'q' on your keyboard.

In case to analyze a video, instead of the real time webcam, simply pass the location of the video as a parameter. The program will generate an output based on the provided video. The input video must be 320x240. 


# Tips for Best Results

- Make sure your face is well lit
- Place your forehead in the green box (area of detection)
- Try not to move too much

