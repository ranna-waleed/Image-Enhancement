# Image-Enhancement
# Computer Vision Mini Project
This project showcases the application of classical computer vision techniques to solve real-world image processing challenges, including component extraction, image enhancement, and noise removal using Python and OpenCV.

# Tasks Overview
## Task 1: Component Extraction
1.1 Circle Detection
- Techniques: Median Filtering → Canny Edge Detection → Hough Circle Transform
- Purpose: Detect circular objects in noisy images.
- Key Strengths: High accuracy in detecting distinct circles with edge preservation.

1.2 COVID-19 Chart Object Separation
- Techniques: Thresholding → Contour Filtering → Morphological Operations
- Purpose: Separate rectangular components from a chart image (removing arrows).
- Key Strengths: Efficient multi-object isolation from complex charts.

## Task 2: Enhancement of Blurry Images
2.1 Buildings & Dogs
- Technique: CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Purpose: Improve local contrast in low-quality images.
- Key Strengths: Enhances textures and details with minimal color distortion.

## Task 3: Noise Removal
3.1 Rocket, Text, and Wind Charts
- Techniques: Box Filter → Gaussian Filter → Median Filter
- Purpose: Remove salt-and-pepper and Gaussian noise.
- Key Strengths: Median filtering effectively preserves edges while denoising.

## Task 4: Challenging Image Enhancement
4.1 Newspaper
- Techniques: Median Filtering → CLAHE → Unsharp Masking
- Purpose: Restore degraded text visibility.
- Key Strengths: Achieves >90% text recovery in noisy scanned documents.

4.2 Name Plate
- Techniques: Sharpening Kernel + CLAHE
- Purpose: Enhance faded or blurred nameplates.
- Key Strengths: Improves text readability in grayscale and low-contrast regions.

# Technologies Used
- Python 3
- OpenCV
- NumPy
- Matplotlib (for display)
  
# How to Run
Clone the repository:

git clone https://github.com/ranna-waleed/Image-Enhancement
cd computer-vision-mini-project

Install dependencies:
pip install -r requirements.txt

Run any script:
python circle_detection.py
