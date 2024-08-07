# Image Detection PowerPoint Controller

This project utilizes computer vision techniques to control PowerPoint presentations by detecting your hand in the camera feed. It moves to the next slide when a hand is moved across from left to right and changes to the previous slide when the hand is moved from right to left.

This project was tested with the use of pink and orange pens so you might see some testing code for that in the project. you can also test the project using them.


## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)
- PyAutoGUI (`pip install pyautogui`)


## Usage

1. Clone the repository:

```bash
git clone https://github.com/Jeet18t/Image-Detection-Powerpoint-Controller.git
```

2. Navigate to the project directory:

```bash
cd image-detection-powerpoint-controller
```

3. Run the script:
```bash
python main.py
```
4. If you want to test it:
   ### Use your hand to make a left-->right gesture to move to next slide, and move your hand in a right-->left gesture to move to previous slide.
   ## or
   ### You can also use different color pens eg: orange and pink pens to move to next and previous slide respectively


## Configuration

By default, the script assumes the PowerPoint application is in the foreground. Ensure PowerPoint is open and active while running the script.
You can adjust the stationary threshold and displacement threshold in the script to fine-tune the sensitivity of the detection.
If your camera feed is inverted, set invert_camera to True to flip the camera feed horizontally.


## License

This project is licensed under the MIT License.
