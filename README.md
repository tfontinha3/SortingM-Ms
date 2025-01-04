# M&M Sorting System using Computer Vision

This repository contains a project developed to implement a computer vision system for sorting M&M chocolates by type and color. The system uses Python and OpenCV to process images, detect contours, analyze color distributions, and classify M&Ms based on visual data. The project involves camera calibration, image analysis, and classification tasks to simulate an automated sorting center in an M&M factory.

## Project Features

1. **Camera Calibration**:
   - Calibrates intrinsic and extrinsic camera parameters.
   - Computes lens distortion coefficients and re-projection errors.

2. **Object Detection and ROI Analysis**:
   - Detects M&Ms in images and processes regions of interest (ROIs).
   - Calculates histograms for color analysis in the HSV color space.

3. **Classification of M&Ms**:
   - Determines the type (peanut or regular) and color of M&Ms.
   - Computes average area and standard deviation of each type and color.

4. **Image Processing on Different Backgrounds**:
   - Processes M&M images retrieved from white and brown backgrounds.
   - Counts and classifies M&Ms in mixed scenarios.

5. **Recommendations for Improved Sorting**:
   - Provides insights and recommendations to enhance the performance of the sorting process.

## Tools and Libraries Used
- Python
- OpenCV
- Numpy
- Pandas
- Google Colab

## How to Use
1. Install necessary dependencies (e.g., OpenCV, gdown).
2. Follow the notebook to process images and analyze M&M characteristics.
3. Explore the generated visualizations and classifications for insights.


