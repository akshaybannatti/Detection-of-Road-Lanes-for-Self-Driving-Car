# Detection-of-Road-Lanes-for-Self-Driving-Car

Project Under Construction

![Lane_Detection_Demo](https://github.com/akshaybannatti/Detection-of-Road-Lanes-for-Self-Driving-Car/assets/50884750/986d32bb-3983-43d5-810e-2745e47e24fb)

# Detection of Road Lanes for Self-Driving Car

This project implements a computer vision-based lane detection system for self-driving cars using Python and OpenCV. The solution identifies lane markings on roads from video frames or images and helps in path planning and navigation.

## Project Overview

- **Objective**: Detect and highlight lane lines on a road in real-time or from video streams/images.
- **Technologies**: Python, OpenCV, NumPy, Matplotlib.
- **Methods**: Image processing techniques including Canny edge detection, Hough Transform, and masking.

## Features

- Lane line detection using edge detection and region masking.
- Robust handling of different lighting conditions.
- Works on pre-recorded videos or image frames.

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Matplotlib

Install dependencies using:
```bash
pip install opencv-python numpy matplotlib
```

## Project Files

- `lane_detection.py`: Main script for processing videos and detecting lanes.
- `test_video.mp4`: Sample input video for demonstration.
- `output_video.mp4`: Processed output showing detected lane lines.
- `README.md`: Documentation.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Detection-of-Road-Lanes-for-Self-Driving-Car.git
   cd Detection-of-Road-Lanes-for-Self-Driving-Car
   ```
2. Run the lane detection script:
   ```bash
   python lane_detection.py
   ```
3. The result will be saved as `output_video.mp4` showing detected lanes.

## Key Functions and Workflow

- **Grayscale Conversion**: Converts frames to grayscale to simplify processing.
- **Gaussian Blur**: Reduces noise for more accurate edge detection.
- **Canny Edge Detection**: Detects edges in the image.
- **Region of Interest Masking**: Focuses on the relevant region where lanes are expected.
- **Hough Transform**: Detects lines in the edge-detected image.
- **Lane Overlay**: Draws detected lanes on the original frame.

## Example Output

![Lane Detection Example](example_image.png)

## Improvements and Future Work

- Add curvature detection for curved roads.
- Implement lane departure warnings.
- Integrate object detection for a more comprehensive driving solution.

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with improvements or additional features.

## Author

[Akshay Bannatti]



1. Here above is the succesful detection of road lanes with video output.
2. Road Lane is shown by Green dotted line covering the lane line 
3. Road edge her is shown by red line over it.
   note: (i) Even the cars are detected by the lane detection.
         (ii) Need to make a different symbol and transparent and efficient detection of cars in lane.
         (iii) Lane changes are also detected somehow. Need to correct that.
         (iv) Need to find a subtle way of indicating road change.
         (vi) Devised a better algorithm for it.                                       
         (vi) I should improve the algorithm. 
         (vii) Algorithm can be better, to make it faster and efficient.
         (viii) Figured it out but to many variables

To be continued...
