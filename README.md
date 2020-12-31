# Heart-Rate-Detector


Monitor your heart rate in real time using just a webcam. It calculates your heart rate in beats per minute (BPM). 


### Install
Ensure the computer you are using to run this project has a webcam. 

These are the library versions that will work with this project:
```
python 2.7.13
numpy  1.13.1
opencv 2.4.11
```

### Installing

Install python 

Install numpy: `pip install numpy`

Install opencv2 on MacOS: `brew install opencv@2`


Use the following commands in the terminal to check the library versions installed:
```
python --version
python -c "import numpy; print numpy.__version__"
python -c "import cv2; print cv2.__version__"
```

### Usage

Once the project is downloaded. Run the python file:

```
python main.py
```

Once the webcam light is activated, a small window will appear. The program takes a few seconds to detect the pulse and start calculating your heart rate. The unmodified webcam video will be saved as 'original.mov' as well as a video of the output called 'output.mov'. Both of these videos will be overwritten every time the program runs, so make a copy and save to another directory.

To quit the program press 'q' on your keyboard.


If you would like this program to analyze a video, instead of the real time webcam, simply pass the location of the video as a parameter. The program will generate an output based on the provided video.
