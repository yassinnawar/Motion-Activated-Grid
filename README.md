# Background Subtraction with Interactive Grid Visualization


## Overview

This project demonstrates a simple real-time background subtraction technique using live webcam video input. It visualizes the difference between the current frame and a previously captured background image to detect motion. The detected movement is visualized using an interactive grid, where activated cells are highlighted when motion is detected.

This project is implemented using the p5.js library and provides an adjustable threshold slider for interactive control of the sensitivity.


## Features

- **Real-Time Background Subtraction**: Captures video and computes differences with a reference background frame to detect movement.
- **Interactive Threshold Adjustment**: Use a slider to adjust the sensitivity of motion detection.
- **Grid-Based Visualization**: A grid overlays the detected motion, highlighting active areas where movement is detected.


## Demo

The canvas displays two panels side-by-side:
1. **Left Panel**: The current video feed from the webcam.
2. **Right Panel**: The result of the background subtraction, with white indicating unchanged areas and black highlighting detected movement.


## How It Works

1. **Background Subtraction**:
   - The video feed is captured in real-time, and each frame is compared with a saved "background" frame.
   - Pixel-by-pixel comparison is performed to detect differences, and a threshold value is used to determine whether a pixel should be classified as part of the background or as movement.

2. **Grid Visualization**:
   - A `Grid` class is used to create a grid overlay, where each cell lights up when movement is detected in that area.


### To run this project, you will need:
- A browser that supports JavaScript.
- A webcam connected to your computer.
- The p5.js library.
- Brackets IDE

## Authors

- **Yassin Nawar** - Initial work, analysis, and documentation.
- **Goldsmith College** - Academic supervision and project guidance.
- **University of London** - Institutional support and resources.

