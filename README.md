# Computer-Vision-Tasks

## 📋 Project Overview
This repository contains three image processing tasks completed as academic coursework. The tasks demonstrate different techniques for processing images such as smoothing, edge detection, and thresholding.

1. **Task 1:** Image thresholding and connected components analysis using OpenCV
2. **Task 2:** Image smoothing with various kernel sizes (3x3, 5x5, 7x7, etc.)
3. **Task 3:** Edge detection using Sobel, Prewitt, and Roberts operators

The primary goal is to explore different methods for image processing, enhancing the understanding of these techniques and their applications in various fields.

## Projects in Detail

### 🔍 Task 1: Image Thresholding and Connected Components
- **Objective:** To classify distinct areas in an image using thresholding and connected components analysis.
- **Key Steps:**
  - Load and convert the image to grayscale.
  - Calculate the average grayscale value of the image.
  - Apply binary thresholding based on the average grayscale value.
  - Perform connected component analysis to count the number of distinct areas.
- **Results:** The task demonstrates how to segment an image and identify individual regions of interest.

### 🧹 Task 2: Image Smoothing
- **Objective:** To apply different smoothing filters (3x3, 5x5, 7x7, 9x9) to an image and observe the effects.
- **Key Steps:**
  - Load and convert the image to grayscale.
  - Apply various smoothing filters (e.g., 3x3, 5x5, 7x7).
  - Display the original image alongside the smoothed images for comparison.
- **Results:** This task showcases how smoothing filters reduce noise and detail in an image.

### 🖼️ Task 3: Edge Detection with Sobel, Prewitt, and Roberts Operators
- **Objective:** To detect edges in an image using three different edge detection operators: Sobel, Prewitt, and Roberts.
- **Key Steps:**
  - Load and convert the image to grayscale.
  - Apply Sobel, Prewitt, and Roberts edge detection filters.
  - Display the gradient magnitudes and directions for each operator.
- **Results:** This task highlights how edge detection helps in identifying boundaries and structures within an image.

## How to Run the Code

1. **Clone the repository:**
    ```bash
    git clone https://github.com/marhum456/Computer_Vision_Tasks.git
    cd Computer_Vision_Tasks
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebooks or Python scripts:**
    Launch Jupyter Lab and open the notebooks in the `notebooks/` directory, or run the Python scripts directly.
    ```bash
    jupyter lab
    ```

## Technologies Used
- **Programming Language:** Python
- **Libraries:** OpenCV, NumPy, Matplotlib, PIL

## Key Insights & Conclusion
- **Thresholding and Connected Components Analysis** is a basic yet powerful method for segmenting images into distinct regions.
- **Image Smoothing** helps reduce noise and is commonly used as a preprocessing step for many image analysis tasks.
- **Edge Detection** operators such as Sobel, Prewitt, and Roberts are foundational techniques used to identify boundaries and contours within images.

## Author
**Your Name**
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/muhammad-arhum01/)
- Email: [muhammadarhum277@gmail.com]
